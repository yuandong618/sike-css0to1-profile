# sike.io CSS 0 to 1 Starter Kit

To do the exercises, just edit the files with your favourite editor.

If you want a live-edit experience, install [BrowserSync](http://www.browsersync.io/).

To install BrowserSync:

```
npm install browser-sync@2.7.1
```

To run the live-edit web server:

```
browser-sync start --server --port 4000 --files index.html --files css/main.css
```

It should open the url `http://localhost:4000` immediately. Editing index.html or css/main.css would cause the browser to automatically refresh.


---

You may meet error like ` command not found: browser-sync` ,don't panic,here provides two solutions.

- `npm install -g browser-sync`   globally install  browser-sync
- `export PATH=$PATH:./node_modules/.bin` in current project dir

