# Deezer-Ad-Free

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40CHEF-KOCH)](https://twitter.com/CKsTechNews)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/CHEF-KOCH)
[![Discord](https://img.shields.io/discord/418256415874875402.svg?colorA=7289da&colorB=99aab5&label=Discord&logo=discord&maxAge=60)](https://discord.me/CHEF-KOCH)
[![Tip Me via PayPal](https://img.shields.io/badge/PayPal-tip%20me-green.svg?logo=paypal)](https://www.paypal.me/nvinside)

Make Deezer great again by blocking the ads and other annoyances. 


### DeezLoader 2.1.8 and CAPTCHAS

Deezer started with version 1.4.x.x to rollout login [Captcha](https://en.wikipedia.org/wiki/CAPTCHA) world-wide, which means external apps like Deez(er)Loader might fail to login or you're forced to solve CAPTCHAS after each downloaded song/album.

Known non-working countries:
* France
* Russia
* Germany
* Netherlands
* UK
* USA 
* India 
* China
* Others (w/wo VPN) (_needs confirmation_)

Tested:
* Swiss/US/Canada & UK with VPN


### Login with username/pass Vs. userToken?

For [several functions you need a userToken](http://developers.deezer.com/inapp/config/permissions) in order to allow Deezer to read e.g. the access token. The login itself might need `127.0.0.1:1730` unblocked in order to receive your token.

Test token:
`f6dc5be19b685b1186828b5a1b28507b2e7ae1d74d457f9ef51fcd9477ebb9dbd3b8539b051c5e399557b2f04c6b0d4808c8610b878e23a3a1c350ecaf441eee6a594d889355dd542ee54436b6e02bc9a3da18a524e669c5ed2c8231cefa01ed`


Reference:
* [DeezloaderRemix (notabug.org)](https://notabug.org/RemixDevs/DeezloaderRemix)
* [DeezLoader-Android (gitlab.com)](https://gitlab.com/Nick80835/DeezLoader-Android)
