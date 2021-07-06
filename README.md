# Rust WASM Conway's game of Life

Made by following [rustwasm.com's book](https://rustwasm.github.io/docs/book). Changed a few things from the tutorial version:

- Replaced the whole Webpack setup with a simple setup without any bundler.
- Made the Universe's size customizable from JS.
- Some other minor stuff

## How to use?

### Install
- Install [the Rust toolchain](https://www.rust-lang.org/tools/install)
- Install [wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)
- Install [NPM](https://nodejs.org/en/)
- Install [http-server](https://www.npmjs.com/package/http-server) globally with NPM `npm install --global http-server`

### Compile & run
1. Run `wasm-pack build --target web` to compile Rust code to WASM
2. Go to `./pkg` and run `npx http-server` to start the web server
3. Open your browser and go to `localhost:8080`
4. Have fun 👍