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
npm start

> sass-patterns@1.0.0 start /Users/piotrblazejewicz/git/sass-patterns
> npm-run-all clean build postcss serve


> sass-patterns@1.0.0 clean /Users/piotrblazejewicz/git/sass-patterns
> rimraf css/ dist/


> sass-patterns@1.0.0 build /Users/piotrblazejewicz/git/sass-patterns
> node-sass --output-style expanded --source-map true scss/ --output css/

Rendering Complete, saving .css file...
Wrote CSS to /Users/piotrblazejewicz/git/sass-patterns/css/bootstrap-grid.css
Wrote Source Map to /Users/piotrblazejewicz/git/sass-patterns/css/bootstrap-grid.css.map
Rendering Complete, saving .css file...
Wrote Source Map to /Users/piotrblazejewicz/git/sass-patterns/css/bootstrap-reboot.css.map
Wrote CSS to /Users/piotrblazejewicz/git/sass-patterns/css/bootstrap-reboot.css
Rendering Complete, saving .css file...
Wrote Source Map to /Users/piotrblazejewicz/git/sass-patterns/css/bootstrap.css.map
Wrote CSS to /Users/piotrblazejewicz/git/sass-patterns/css/bootstrap.css
Rendering Complete, saving .css file...
Wrote CSS to /Users/piotrblazejewicz/git/sass-patterns/css/starter-template.css
Wrote Source Map to /Users/piotrblazejewicz/git/sass-patterns/css/starter-template.css.map
Wrote 4 CSS files to /Users/piotrblazejewicz/git/sass-patterns/css/

> sass-patterns@1.0.0 postcss /Users/piotrblazejewicz/git/sass-patterns
> postcss --use autoprefixer --config postcss.config.js --dir dist/css/ css/*css

✔ Finished css/bootstrap-reboot.css (517ms)
✔ Finished css/bootstrap-grid.css (865ms)
✔ Finished css/bootstrap.css (482ms)
✔ Finished css/starter-template.css (484ms)

> sass-patterns@1.0.0 serve /Users/piotrblazejewicz/git/sass-patterns
> browser-sync start --server .

[BS] Access URLs:
 -------------------------------------
       Local: http://localhost:3000
    External: http://192.168.1.16:3000
 -------------------------------------
          UI: http://localhost:3001
 UI External: http://192.168.1.16:3001
 -------------------------------------
[BS] Serving files from: .

```

## Author

@peterblazejewicz
