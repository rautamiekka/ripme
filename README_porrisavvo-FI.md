# RipMe [![Licensed under the MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/RipMeApp/ripme/blob/master/LICENSE.txt) [![Join the chat at https://gitter.im/RipMeApp/Lobby](https://badges.gitter.im/RipMeApp/Lobby.svg)](https://gitter.im/RipMeApp/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Subreddit](https://img.shields.io/badge/discuss-on%20reddit-blue.svg)](https://www.reddit.com/r/ripme/)

[![Build Status](https://travis-ci.org/RipMeApp/ripme.svg?branch=master)](https://travis-ci.org/RipMeApp/ripme)
[![Coverage Status](https://coveralls.io/repos/github/RipMeApp/ripme/badge.svg?branch=master)](https://coveralls.io/github/RipMeApp/ripme?branch=master)

# Osallistu

*RipMe*:t ylpirrettää ♥️:rel **[@MetaPrime](https://github.com/metaprime)**, **[@cyian-1756](https://github.com/cyian-1756)** ja **[@kevin51jiang](https://github.com/kevin51jiang)** vap'aikkan. Jos hallussit ossallistuu muttet ossaa koorat voit pittee meij illossen lahjjottammal!

[![Tippii PayPalil](https://img.shields.io/badge/PayPal-Buy_us...-lightgrey.svg)](https://www.paypal.me/ripmeapp)
[![Tippii PayPalil](https://img.shields.io/badge/coffee-%245-green.svg)](https://www.paypal.com/paypalme/ripmeapp/send?amount=5.00&currencyCode=USD&locale.x=en_US&country.x=US)
[![Tippii PayPalil](https://img.shields.io/badge/beer-%2410-yellow.svg)](https://www.paypal.com/paypalme/ripmeapp/send?amount=10.00&currencyCode=USD&locale.x=en_US&country.x=US)
[![Tippii PayPalil](https://img.shields.io/badge/lunch-%2420-orange.svg)](https://www.paypal.com/paypalme/ripmeapp/send?amount=20.00&currencyCode=USD&locale.x=en_US&country.x=US)
[![Tippii PayPalil](https://img.shields.io/badge/dinner-%2450-red.svg)](https://www.paypal.com/paypalme/ripmeapp/send?amount=50.00&currencyCode=USD&locale.x=en_US&country.x=US)
[![Tippii PayPalil](https://img.shields.io/badge/custom_amount-...-lightgrey.svg)](https://www.paypal.me/ripmeapp)

# Tiatto

*RipMe* o album ripper monil saiteil joka ajjettaa tiatskallas. Vaatti Java >=8.

![Screenshot](http://i.imgur.com/kWzhsIu.png)

## [Lattauksse](https://github.com/ripmeapp/ripme/releases)

Lattaa `ripme.jar` [viimessimmist julkassuist](https://github.com/ripmeapp/ripme/releases).

**Huam: Jos käytät täl hetkel versijoit 1.2.x tai 1.3.x et saa uussimppia updatei. Lattaa uussin käyttäjje yl ollevvaa linkki.**

Tiatto `.jar`-filu ajjammissest löytty [Mite ajjaa -wikist](https://github.com/ripmeapp/ripme/wiki/How-To-Run-RipMe).

## [Muutoslista](https://github.com/ripmeapp/ripme/blob/master/ripme.json) (ripme.json)

# Toimminno

* Noppeest lattaa kaik kuvva albummis (kat tuettujje saittijje lista al)
* Helepost *re-rip* albummi sisält
* Intekroit *updater*
* Voi ripat Tumblrist kuvva alkuperäses muaros [Lue mitte ottaa käyttö](https://github.com/RipMeApp/ripme/wiki/Config-options#tumblrget_raw_image)
* Ohhittaa jo ripatu kuvva oletuksen

## [List tuetuist saiteist](https://github.com/ripmeapp/ripme/wiki/Supported-Sites)
Esimerkei:
* imgur
* twitter
* tumblr
* instagram
* flickr
* photobucket
* reddit
* gonewild
* motherless
* imagefap
* imagearn
* seenive
* vinebox
* 8muses
* deviantart
* xhamster
* (lissee)

## Ei tuet?

Pyyr tue lissäyst [täs GitHub-threadis](https://github.com/RipMeApp/ripme/issues/38).

Jos voit koorat voit ite tehr ripper seurraammal
[Mite ter ripper HTML-saitil](https://github.com/ripmeapp/ripme/wiki/How-To-Create-A-Ripper-for-HTML-websites).

# Compiloint ja buildaus

Tää project käyttää *[Maven](http://maven.apache.org/)*.
Buildatakseks `.jar`-filu käyttäjje *Maven*, navikoi juurkansioon ja ajja:

```bash
mvn clean compile assembly:single
```

Tää addaa kaik riippuvvuurre JAR-filuu.

# Testijje ajo

Buildaukse jälk voit ajjaa testei ajjamal:

```bash
mvn test
```

Huammijjoi et saittijje muuttujjes ripperrit voi hajjot.
Alot buildaamal ja tesmaamal uus *RipMe*
ja sit varmist ettei tekemäs muutoksse saa lissee testei feilaa.
