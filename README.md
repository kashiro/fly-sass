<div align="center">
  <a href="http://github.com/flyjs/fly">
    <img width=200px  src="https://cloud.githubusercontent.com/assets/8317250/8430194/35c6043a-1f6a-11e5-8cbd-af6cc86baa84.png">
  </a>
</div>

> [node-sass](https://github.com/sass/node-sass) plugin for _[Fly][fly]_.

[![][fly-badge]][fly]
[![npm package][npm-ver-link]][releases]
[![][dl-badge]][npm-pkg-link]
[![][travis-badge]][travis-link]
[![][mit-badge]][mit]

## Usage
> Check out the [documentation](https://github.com/sass/node-sass) to see the available options.

### Install

```a
npm install -D fly-sass
```

### Example

```js
export function* text () {
  yield this
    .source("./src/styles/**/*.sass")
    .sass({includePaths: ["./src/styles"]})
    .target("dist/")
}
```

# License

[MIT][mit] © [Tomoyuki Kashiro][author] et [al][contributors]


[mit]:          http://opensource.org/licenses/MIT
[author]:       http://tomoyukikashiro.me
[contributors]: https://github.com/kashiro/fly-sass/graphs/contributors
[releases]:     https://github.com/kashiro/fly-sass/releases
[fly]:          https://www.github.com/flyjs/fly
[fly-badge]:    https://img.shields.io/badge/fly-JS-05B3E1.svg?style=flat-square
[mit-badge]:    https://img.shields.io/badge/license-MIT-444444.svg?style=flat-square
[npm-pkg-link]: https://www.npmjs.org/package/fly-sass
[npm-ver-link]: https://img.shields.io/npm/v/fly-sass.svg?style=flat-square
[dl-badge]:     http://img.shields.io/npm/dm/fly-sass.svg?style=flat-square
[travis-link]:  https://travis-ci.org/kashiro/fly-sass
[travis-badge]: http://img.shields.io/travis/kashiro/fly-sass.svg?style=flat-square
