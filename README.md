# dennis.life

Source code for my personal website. [dennis.life](https://dennis.life/)

## Prerequisites

The source is written in languages from which HTML & CSS can be generated. Their advantage (for me) is mainly that the resulting files are very compact (and avoid some strange edge-cases in the HTML semantics).

* Install [Node.js and npm](https://nodejs.org/)
* Install Pug (`npm install -g pug-cli`)
* Install Sass (`npm install -g sass`)

## Development

Run both Pug and Sass (in different terminals) in watch mode as:

```
pug index.pug --watch
```

```
sass style.sass style.css --no-source-map --style compressed --watch
```

## Demos

The hosted website includes demos for projects. Those are independently compiled from their respective source code:

* [non-euclidean-grid](https://github.com/sourcedennis/non-euclidean-grid)
* [pathtracer](https://github.com/sourcedennis/wasm-pathtracer)

## License

Source code: BSD-3

Images: CC BY-SA
