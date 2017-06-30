# pokemon-escape [![Build Status](https://travis-ci.org/bukinoshita/pokemon-escape.svg?branch=master)](https://travis-ci.org/bukinoshita/pokemon-escape)

> Check if Pokemon flee from battle


## Install

```
$ npm install --save pokemon-escape
```


## Usage
```js
const pokemonEscape = require('pokemon-escape')

pokemonEscape(20)
// => true
```


## API

### pokemonEscape(fleeRate)

returns a `boolean`

#### fleeRate

Type: `integer`<br/>
Required

Pokemon's flee rate. Can check [here](https://pokemongo.gamepress.gg/sites/default/files/2016-10/flee_rate_img_1.png)


## Related

- [pokemon-game](https://github.com/bukinoshita/pokemon-game) — Pokemon game — Get 'em all
- [catch-pokemon](https://github.com/bukinoshita/catch-pokemon) — Algorithm to catch a pokemon
- [pokedex-api](https://github.com/bukinoshita/pokedex-api) — Pokedex API
- [pokemon-catch-probability](https://github.com/bukinoshita/pokemon-catch-probability) — Check probabilty to catch a pokemon
- [get-pokeball](https://github.com/bukinoshita/get-pokeball) — Get pokeball information
- [pokeball-shake](https://github.com/bukinoshita/pokeball-shake) — Algorithm to determine how many times pokeball shakes
- [pokemon-capture-quote](https://github.com/bukinoshita/pokemon-capture-quote) — Pokemon capture quote
- [pokemon-f](https://github.com/bukinoshita/pokemon-f) — Algorithm to calculate `f` on capture pokemon method


## License

MIT © [Bu Kinoshita](https://bukinoshita.io)
