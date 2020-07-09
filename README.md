# next-rollup-banner
> Rollup banner for next.

[![version][version-image]][version-url]
[![license][license-image]][license-url]
[![size][size-image]][size-url]
[![download][download-image]][download-url]

## installation
```bash
npm install -S @feizheng/next-rollup-banner
```

## usage
```js
import '@feizheng/next-rollup-banner';

nx.rollupBanner();

/*
     name: <%= pkg.name %>
     description: <%= pkg.description %>
     homepage: <%= pkg.homepage %>
     version: <%= pkg.version %>
     date: 2020-07-09T13:42:26.535Z
     license: <%= pkg.license %>
*/
```

## license
Code released under [the MIT license](https://github.com/afeiship/next-rollup-banner/blob/master/LICENSE.txt).

[version-image]: https://img.shields.io/npm/v/@feizheng/next-rollup-banner
[version-url]: https://npmjs.org/package/@feizheng/next-rollup-banner

[license-image]: https://img.shields.io/npm/l/@feizheng/next-rollup-banner
[license-url]: https://github.com/afeiship/next-rollup-banner/blob/master/LICENSE.txt

[size-image]: https://img.shields.io/bundlephobia/minzip/@feizheng/next-rollup-banner
[size-url]: https://github.com/afeiship/next-rollup-banner/blob/master/dist/next-rollup-banner.min.js

[download-image]: https://img.shields.io/npm/dm/@feizheng/next-rollup-banner
[download-url]: https://www.npmjs.com/package/@feizheng/next-rollup-banner
