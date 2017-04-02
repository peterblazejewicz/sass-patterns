# sass-patterns

A different approach to SASS project compared to: https://sass-guidelin.es. Based on: https://egghead.io/courses/learn-the-best-and-most-useful-scss by Ari Picker: https://github.com/Pickra.

## Development

### Start local server

```bash
npm start
```

### Develop locally

Starts a local server with `watch` options enabled for static and SASS transpiled content

```bash
npm run dev
```

`Yarn` client package tool is supported instead of `NPM`

```bash
npm run dev

> sass-patterns@1.0.0 dev /Users/piotrblazejewicz/git/sass-patterns
> npm-run-all --parallel build:watch serve:watch postcss:watch


> sass-patterns@1.0.0 build:watch /Users/piotrblazejewicz/git/sass-patterns
> node-sass --output-style expanded --source-map true --watch scss/ --recursive --output css/


> sass-patterns@1.0.0 serve:watch /Users/piotrblazejewicz/git/sass-patterns
> browser-sync start --server . --files=index.html,dist/css/*.css


> sass-patterns@1.0.0 postcss:watch /Users/piotrblazejewicz/git/sass-patterns
> postcss --use autoprefixer --config postcss.config.js --dir dist/css/ --watch css/*css

⠋ Processing css/starter-template.css[BS] Access URLs:
 -------------------------------------
       Local: http://localhost:3000
    External: http://192.168.1.16:3000
 -------------------------------------
          UI: http://localhost:3001
 UI External: http://192.168.1.16:3001
 -------------------------------------
[BS] Serving files from: .
[BS] Watching files...
⠙ Processing css/starter-template.css[BS] File event [change] : dist/css/starter-template.css
✔ Finished css/starter-template.css (296ms)
✔ Finished css/bootstrap-reboot.css (163ms)
✔ Finished css/bootstrap.css (920ms)
✔ Finished css/bootstrap-grid.css (107ms)
[BS] File event [change] : dist/css/starter-template.css
Waiting for file changes...

```

## Author

@peterblazejewicz
