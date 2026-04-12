# midi

opensource astrology midpoint interface inspired by musical instrument digital interfaces

abstract interface to calculate midpoint between degrees such as the sun and moon

`midi(sun, moon)` => <var>midpoint</var>

`midi(30, 70)` => `50`

*currently this is an ideation* 

### possible dot interface <br> tbd on naming and i18n

```js
midi.gemini(10).libra(10).sign() // "leo"
midi.gemini(10).libra(10).arc() // 130
midi.gemini(10).libra(10).dms() // [130, 0, 0]
midi.sign(2).degree(22).arc() => 52
```

#### degree needs disambiguation from <i>celestial longitude</i> verse <i>zodiacal longitude</i>

* <dfn>celestial longitude</dfn> is degree of 360º
* <dfn>zodiacal longitude</dfn> is degree of 30º of each sign

### beyond
* [Learn from perspective online](https://p9e.page)
* [Support our github development](https://github.com/sponsors/p9e)
