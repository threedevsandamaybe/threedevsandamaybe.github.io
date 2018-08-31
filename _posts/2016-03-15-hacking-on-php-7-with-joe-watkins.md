---
title: Hacking on PHP 7 with Joe Watkins
abstract: Hacking on the PHP 7 core to develop new language constructs
date: 2016-03-15T19:00:00.000Z
layout: screencast
hosts: [Edd Mann]
guests: [Joe Watkins]
---

In this screencast episode Edd n' Joe discuss designing language constructs for the PHP 7 core.
Following you through firstly a simple 'hipster' example, this will give you a good basis to understand the places (Lexer, Parser and Compiler) that will need to be modified to create features that you typically see in RFC proposals.

<div data-type="youtube" data-video-id="_arORgEVl-M"></div>

Now that we have explored all the areas required to implement a new feature, we will now look into some more contrived examples which help expand upon this understanding.

<div data-type="youtube" data-video-id="f9N-v-JUbTQ"></div>

### Source-code

- [hipster](https://github.com/krakjoe/php-src/commit/4efb1a487bf71fc129c95ebefaf6e216fa4767e7)
- [loop](https://github.com/krakjoe/php-src/commit/1624d45f5e1a87cada201ecf2fa7b8ab250d07f1)
- [unless](https://github.com/krakjoe/php-src/commit/936ac4008977c2e4ff2a022879dc2c3c11a43a39)
- [for-guard](https://github.com/krakjoe/php-src/commit/5bce5ae538d99e8725492337c6820e182672d0e2)
- [with](https://github.com/krakjoe/php-src/compare/de3e033010d624ea22aa38211bb854f17762362c...with)
