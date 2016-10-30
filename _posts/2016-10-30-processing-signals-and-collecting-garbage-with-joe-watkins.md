---
title: Processing Signals and Collecting Garbage with Joe Watkins
abstract: "Discussion on long-running PHP processes, Unix signals, Garbage collection and PHP UI development"
date: 2016-10-30T14:00:00.000Z
file: 109-processing-signals-and-collecting-garbage-with-joe-watkins.mp3
layout: podcast
number: 109
size: 18517435
duration: 1987
---

In this weeks episode we have a long overdue catch-up with Joe Watkins.
We start off discussion with progress on PHP 7.1 and work Joe has been doing to provide an interface to libui within PHP.
We then move on to chat about a couple of interesting RFC's that are currently under-discussion, followed by managing long-running PHP processes with Supervisor and Unix signaling.
Finally, we highlight how Garbage collection works and how PHP implements the concept to help manage memory.

### Show Links

- [PHP 7.1.0 Release Candidate 4 Released](http://php.net/archive/2016.php#id2016-10-19-1)
- [PHP 7.1.0 Release Candidate 5 Released](http://php.net/archive/2016.php#id2016-10-27-1)
- [krakjoe/ui - Cross platform UI development in PHP](https://github.com/krakjoe/ui)
- [andlabs/libui - Simple and portable GUI library in C](https://github.com/andlabs/libui)
- [Pong example using krakjoe/ui](https://twitter.com/krakjoe/status/790719896711725056)
- [Space example using krakjoe/ui](https://twitter.com/krakjoe/status/790235457284087808)
- [PHP-GTK](http://gtk.php.net/)
- [Trending repositories on GitHub](https://github.com/trending)
- [PHP Next (7.2)](https://wiki.php.net/rfc#php_next_72)
- [PHP RFC - Deprecate bundling PEAR/PECL and replace with composer/pickle](https://wiki.php.net/rfc/deprecate-pear-include-composer)
- [PHP RFC - Traits with interfaces](https://wiki.php.net/rfc/traits-with-interfaces)
- [Traits](https://en.wikipedia.org/wiki/Trait_(computer_programming))
- [Unix signals](https://en.wikipedia.org/wiki/Unix_signal)
- [Supervisor - A Process Control System](http://supervisord.org/)
- [PHP PCNTL Extension](http://php.net/manual/en/book.pcntl.php)
- [PHP - pcntl_signal_dispatch](http://php.net/manual/en/function.pcntl-signal-dispatch.php)
- [PHP - declare](http://php.net/manual/en/control-structures.declare.php#control-structures.declare.ticks)
- [Taking PHP Seriously](https://slack.engineering/taking-php-seriously-cf7a60065329?gi=c1d4e24358ec)
- [Garbage collection](https://en.wikipedia.org/wiki/Garbage_collection_(computer_science))
- [Garbage collection in PHP](http://php.net/manual/en/features.gc.php)
- [Concurrent Cycle Collection in Reference Counted Systems](http://researcher.watson.ibm.com/researcher/files/us-bacon/Bacon01Concurrent.pdf)
- [PHP - a fractal of bad design](https://eev.ee/blog/2012/04/09/php-a-fractal-of-bad-design/)
- [Circular references](https://en.wikipedia.org/wiki/Circular_reference)
- [ircmaxell's blog - What About Garbage?](http://blog.ircmaxell.com/2014/12/what-about-garbage.html)
- [composer/composer - Disable GC when computing deps](https://github.com/composer/composer/commit/ac676f47f7bbc619678a29deae097b6b0710b799)
