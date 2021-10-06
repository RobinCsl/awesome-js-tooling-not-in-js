# Awesome JS Tooling not in JS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of JavaScript tooling not written in JavaScript


## Contents

- [Bundlers](#bundlers)
- [Compilers](#compilers)
- [Engines](#engines)
- [Formatters](#formatters)
- [Linters](#linters)
- [Miscellaneous](#miscellaneous)
- [Related Articles](#related-articles)

## Bundlers

- [esbuild](https://esbuild.github.io/getting-started/) - JavaScript bundler in Go.
- [Parcel](https://parceljs.org) - Web application bundler, with its JavaScript transformer written in Rust on top of swc ([source](https://parceljs.org/blog/beta3/)).
- [Bun](https://github.com/Jarred-Sumner/bun) - JS, TS, JSX bundler, JS and CSS transpiler, dev server and JS runtime environment, written in Zig. ([access to repository through Discord invite](https://twitter.com/jarredsumner/status/1444036635239215106?s=20))

## Compilers

- [swc](https://github.com/swc-project/swc) - TypeScript/JavaScript compiler in Rust.
- [(experimental) Relay compiler](https://github.com/facebook/relay/tree/master/compiler) - in Rust.
- [Paperclip](https://paperclip.dev/) - Presentational component compiler in Rust + WASM.
- [Closure Compiler](https://github.com/google/closure-compiler) - in Java.

## Engines

- [Boa](https://github.com/boa-dev/boa) - Embeddable and experimental Javascript engine, written in Rust.
- [Goja](https://github.com/dop251/goja) - ECMAScript/JavaScript engine, written in Go .
- [Hermes](https://hermesengine.dev/) - JavaScript engine optimized for React Native, written in C++.
- [V8](https://v8.dev/) - High-performance JavaScript and WebAssembly engine, written in C++.


## Formatters

- [dprint](https://dprint.dev) - Pluggable and configurable code formatting platform written in Rust; supports several languages such as [JavaScript/TypeScript](https://dprint.dev/plugins/typescript/).

## Linters

- [Deno Lint](https://github.com/denoland/deno_lint)
- [Flow](https://flow.org/) - Static type checker for JavaScript, written in OCaml.
- [quick-lint-js](https://quick-lint-js.com/) - Written in C++.
- [RSLint](https://github.com/rslint/rslint) - Extremely fast JavaScript and TypeScript linter, written in Rust. (WIP)

## Miscellaneous

_If you can think of a more appropriate category for the items below, PRs welcome!_

- [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) - Node.js version manager, written in Rust.
- [Volta](https://volta.sh/) - JavaScript Tool Manager, written in Rust.
- [es-module-lexer](https://github.com/guybedford/es-module-lexer) - JavaScript module syntax lexer, written in C.
- [npm-dep-check-rust](https://github.com/saiumesh535/npm-dep-chek-rust) - Find unused dependencies in Node.js applications, written in Rust.
- [Rome](https://rome.tools) - Linter, compiler, bundler, and more for JavaScript, TypeScript, JSON, HTML, Markdown, and CSS, 🚧 currently being re-written in Rust ([source](https://rome.tools/blog/2021/09/21/rome-will-be-rewritten-in-rust)).
- [Wrangler](https://github.com/cloudflare/wrangler) - CLI tool to develop Clouflare Workers, written in Rust.

## Related Articles

- [Writing JavaScript tools in other languages – a new trend?, Dr. Axel Rauschmayer](https://2ality.com/2020/10/js-plus-other-languages.html)
- [The Third Age of JavaScript, Shawn (@swyx) Wang](https://www.swyx.io/js-third-age/)

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
