[![Build Status](https://travis-ci.org/telemark/tfk-saksbehandling-elev-varsel-templates.svg?branch=master)](https://travis-ci.org/telemark/tfk-saksbehandling-elev-varsel-templates)
[![Coverage Status](https://coveralls.io/repos/telemark/tfk-saksbehandling-elev-varsel-templates/badge.svg?branch=master&service=github)](https://coveralls.io/github/telemark/tfk-saksbehandling-elev-varsel-templates?branch=master)
[![Code Climate](https://codeclimate.com/github/telemark/tfk-saksbehandling-elev-varsel-templates/badges/gpa.svg)](https://codeclimate.com/github/telemark/tfk-saksbehandling-elev-varsel-templates)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
# tfk-saksbehandling-elev-varsel-templates

[![Greenkeeper badge](https://badges.greenkeeper.io/telemark/tfk-saksbehandling-elev-varsel-templates.svg)](https://greenkeeper.io/)
Maler for tfk-saksbehandling-elev-varsel økosystemet.

Oversikt over alle malene og koder for de ulike ligger [her](docs/templates.md)

## Installasjon

Fra npm

```sh
$ npm install --save tfk-saksbehandling-elev-varsel-templates
```

Fra GitHub

```sh
$ git clone git@github.com:telemark/tfk-saksbehandling-elev-varsel-templates.git
```

Deretter går du inn i mappen og kjører setup

```sh
$ npm run setup
```

## Bruk

Send inn id på malen du skal benytte og få fullstendig filbane i retur.

Maler
- atferd
- fag
- foresatte
- hemmelig-adresse
- orden

```javascript
'use strict'

var getTemplatePath = require('tfk-saksbehandling-elev-varsel-templates')

console.log(getTemplatePath('orden'))

//=> path/to/template/orden.docx
```

## Lisens
[MIT](LICENSE)