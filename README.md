# repl.history

Persist a node repl's history to a file.

## from node

install: `npm install repl.local.history`

```javascript
var repl = require('repl').start('> ');
require('repl.local.history')(repl, process.cwd() + '/.node_history');
```

this will drop a `.node_history` file in your current working directory. Useful for when working on multiple projects without wanting to clutter your history.

## from the command line

install: `npm install -g repl.local.history`

run `repl.local.history` on the command line

A file `.node_history` will be created.

I like to alias it to `nr` for node repl
