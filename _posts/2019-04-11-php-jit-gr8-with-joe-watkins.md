---
title: "PHP + JIT = GR8 with Joe Watkins"
abstract: "Discussion on PHP 8 getting a JIT, a new parallel concurrency API and much more..."
date: 2019-04-11T12:30:00.000Z
file: 162-php-jit-gr8-with-joe-watkins.mp3
layout: podcast
number: 162
size: 21926897
duration: 3064
hosts: [Edd Mann]
guests: [Joe Watkins]
---

In this weeks episode we have good friend of the show Joe Watkins back on to discuss the recent developments in PHP.
We start off by highlighting how code is currently compiled and executed using the Zend VM, and distill how the recently approved JIT (for PHP 8) will change this.
From here we mention the reasoning for going down this path now, the difference between I/O vs CPU bound code, and the use-cases where the JIT will improve performance.
This leads us to the PHP compiler project Anthony Ferrara is working on (with the goal of Ahead-of-Time PHP compilation), and the new parallel concurrency API Joe is working on which uses a model similar to Goroutines.
Finally, we discuss his recently approved Weak References and Abolish Narrow Margins RFC's.

### Show Links

- [Musings, ninja ones - PHP GR8](https://blog.krakjoe.ninja/2019/03/php-gr8.html)
- [PHP RFC - JIT](https://wiki.php.net/rfc/jit)
- [nikic/php-ast - Extension exposing PHP 7 abstract syntax tree](https://github.com/nikic/php-ast)
- [ircmaxell/php-ast-visualizer - An AST visualizer, for PHP](https://github.com/ircmaxell/php-ast-visualizer)
- [PHPNG](https://wiki.php.net/phpng)
- [PHP OPcache](https://www.php.net/manual/en/book.opcache.php)
- [ircmaxell/php-compiler - A compiler. For PHP](https://github.com/ircmaxell/php-compiler)
- [ircmaxell/php-compiler-toolkit - A compiler toolkit. For PHP](https://github.com/ircmaxell/php-compiler-toolkit)
- [ircmaxell/FFIMe - A FFI Wrapper library and header parser!](https://github.com/ircmaxell/FFIMe)
- [Anthony Ferrara - High Performance PHP - YouTube](https://www.youtube.com/watch?v=qjYyC47rdVs)
- [Musings, ninja ones - Parallel PHP - The Next Chapter](https://blog.krakjoe.ninja/2019/02/parallel-php-next-chapter.html)
- [krakjoe/parallel - A succinct parallel concurrency API for PHP7](https://github.com/krakjoe/parallel)
- [Joe Watkins on Twitter - "parallel+jit+php-nes-emulator = 80's fun at full speed"](https://twitter.com/krakjoe/status/1107169368457265152)
- [PHP RFC - Weak References](https://wiki.php.net/rfc/weakrefs)
- [PHP RFC - Abolish Narrow Margins](https://wiki.php.net/rfc/abolish-narrow-margins)
