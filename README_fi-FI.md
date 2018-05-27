# RipMe [![Licensed under the MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/RipMeApp/ripme/blob/master/LICENSE.txt) [![Join the chat at https://gitter.im/RipMeApp/Lobby](https://badges.gitter.im/RipMeApp/Lobby.svg)](https://gitter.im/RipMeApp/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Subreddit](https://img.shields.io/badge/discuss-on%20reddit-blue.svg)](https://www.reddit.com/r/ripme/)

[![Build Status](https://travis-ci.org/RipMeApp/ripme.svg?branch=master)](https://travis-ci.org/RipMeApp/ripme)
[![Coverage Status](https://coveralls.io/repos/github/RipMeApp/ripme/badge.svg?branch=master)](https://coveralls.io/github/RipMeApp/ripme?branch=master)

# Osallistu

RipMe:tä ylläpidetään ♥️:lla ja **[@MetaPrime](https://github.com/metaprime)**n ja **[@cyian-1756](https://github.com/cyian-1756)**:n vapaa-aikana. Jos haluaisit osallistua mutta et osaa ohjelmoida voit pitää meidät iloisina lahjoittamalla!

[![Tippiä PayPalilla](https://img.shields.io/badge/PayPal-Buy_us...-lightgrey.svg)](https://www.paypal.me/ripmeapp)
[![Tippiä PayPalilla](https://img.shields.io/badge/coffee-%245-green.svg)](https://www.paypal.com/paypalme/ripmeapp/send?amount=5.00&currencyCode=USD&locale.x=en_US&country.x=US)
[![Tippiä PayPalilla](https://img.shields.io/badge/beer-%2410-yellow.svg)](https://www.paypal.com/paypalme/ripmeapp/send?amount=10.00&currencyCode=USD&locale.x=en_US&country.x=US)
[![Tippiä PayPalilla](https://img.shields.io/badge/lunch-%2420-orange.svg)](https://www.paypal.com/paypalme/ripmeapp/send?amount=20.00&currencyCode=USD&locale.x=en_US&country.x=US)
[![Tippiä PayPalilla](https://img.shields.io/badge/dinner-%2450-red.svg)](https://www.paypal.com/paypalme/ripmeapp/send?amount=50.00&currencyCode=USD&locale.x=en_US&country.x=US)
[![Tippiä PayPalilla](https://img.shields.io/badge/custom_amount-...-lightgrey.svg)](https://www.paypal.me/ripmeapp)

# Tietoa

RipMe on albumilataaja monille nettisivuille joka ajetaan tietokoneellasi. Vaatii Java >=8.

![Kuvakaappaus](http://i.imgur.com/kWzhsIu.png)

## [Lataukset](https://github.com/ripmeapp/ripme/releases)

Lataa `ripme.jar` [viimeisimmistä julkaisuista](https://github.com/ripmeapp/ripme/releases).

**Huomaa: Jos käytät tällä hetkellä versioita 1.2.x tai 1.3.x et saa uusimpia päivityksiä. Lataa uusin käyttäen yllä olevaa linkkiä.**

Tietoa `.jar`-tiedoston ajamisesta löytyy [Miten ajaa -wikistä](https://github.com/ripmeapp/ripme/wiki/How-To-Run-RipMe).

## [Muutoslista](https://github.com/ripmeapp/ripme/blob/master/ripme.json) (ripme.json)

# Toiminnot

* Nopeasti lataa kaikki kuvat albumissa (katso tuettujen sivujen lista alla)
* Helposti uudelleenlataa albumin uusi sisältö
* Sisäänrakennettu päivitystoiminto
* Voi ladata Tumblrista alkuperäisessä koossa [Lue miten ottaa käyttöön](https://github.com/RipMeApp/ripme/wiki/Config-options#tumblrget_raw_image)
* Ohittaa jo ladatut kuvat oletuksena

## [Lista tuetuista sivuista](https://github.com/ripmeapp/ripme/wiki/Supported-Sites)
Esimerkkejä:
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
* (lisää)

## Ei tuettu?

Pyydä tuen lisäystä [tässä GitHub-ketjussa](https://github.com/RipMeApp/ripme/issues/38).

Jos voit ohjelmoida voit itse tehdä lataajan seuraamalla
[Kuinka tehdä lataaja HTML-nettisivulle](https://github.com/ripmeapp/ripme/wiki/How-To-Create-A-Ripper-for-HTML-websites).

# Kompilointi ja kokoominen

Tämä projekti käyttää [Maven](http://maven.apache.org/).
Kootaksesi `.jar`-tiedoston käyttäen Mavenia, navigoitte juurikansioon ja aja:

```bash
mvn clean compile assembly:single
```

Tämä sisältää kaikki riippuvuudet JAR-tiedostoon.

# Testien ajo

Kokoamisen jälkeen voit ajaa testejä ajamalla:

```bash
mvn test
```

Huomioi että sivujen muuttuessa lataajat voivat hajota.
Aloit kokoamalla ja testaamalla uusi RipMe
ja sitten varmista ettei tekemäsi muutokset saa lisää testejä epäonnistumaan.
