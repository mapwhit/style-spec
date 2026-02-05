[![NPM version][npm-image]][npm-url]
[![Build Status][build-image]][build-url]
[![Dependency Status][deps-image]][deps-url]

# @mapwhit/style-spec

Module to process expressions in map style. Based on the code for expressions processing in [maplibre-gl-js] (an open-source fork of [mapbox-gl-js], before their switch to a non-OSS license in December 2020.)

## Install

```sh
$ npm install --save @mapwhit/style-spec
```

## Usage

```js
import { createExpression } from '@mapwhit/style-spec';

const expression = createExpression();
```

## License

BSD-3-Clause © [Natalia Kowalczyk](https://melitele.me)

[npm-image]: https://img.shields.io/npm/v/@mapwhit/style-spec
[npm-url]: https://npmjs.org/package/@mapwhit/style-spec

[build-url]: https://github.com/mapwhit/style-spec/actions/workflows/check.yaml
[build-image]: https://img.shields.io/github/actions/workflow/status/mapwhit/style-spec/check.yaml?branch=main

[deps-image]: https://img.shields.io/librariesio/release/npm/@mapwhit/style-spec
[deps-url]: https://libraries.io/npm/@mapwhit%2Fstyle-spec

[mapbox-gl-js]: https://github.com/mapbox/mapbox-gl-js
[maplibre-gl-js]: https://github.com/maplibre/maplibre-gl-js
