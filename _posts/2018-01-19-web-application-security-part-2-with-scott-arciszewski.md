---
title: "Web Application Security, Part 2 with Scott Arciszewski"
abstract: "Continuing our discussion on Security and Cryptography within Web Applications"
date: 2018-01-19T14:15:00.000Z
file: 141-web-application-security-part-2-with-scott-arciszewski.mp3
layout: podcast
number: 141
size: 33361437
duration: 3569
---

In this weeks episode we continue our discussion with Scott Arciszewski about all things Security and Cryptography.
We start off the show by highlighting what a SQL injection attack is and the differences between (emulated) prepared statements.
This leads us on to look into how to securely handle file uploads, what a reverse shell is and how to defend yourself against XSS/CSRF attacks.
From here we touch upon the recent inclusion of libsodium into PHP, why mcrypt should be avoided, and the side-channel vulnerabilities that brought way to Meltdown and Spectre.
Finally, we mention how computers generate seemingly random numbers, what a Web Application Firewall (WAF) is, and how WARD goes about protecting your systems.

### Show Links

- [Scott Arciszewski on Twitter](https://twitter.com/ciphpercoder)
- [Paragon Initiative Enterprises](https://paragonie.com/)
- [The 2018 Guide to Building Secure PHP Software](https://paragonie.com/blog/2017/12/2018-guide-building-secure-php-software)
- [Are PDO prepared statements sufficient to prevent SQL injection?](https://stackoverflow.com/questions/134099/are-pdo-prepared-statements-sufficient-to-prevent-sql-injection/12202218#12202218)
- [Preventing SQL Injection in PHP Applications](https://paragonie.com/blog/2015/05/preventing-sql-injection-in-php-applications-easy-and-definitive-guide)
- [paragonie/easydb - Easy-to-use PDO wrapper for PHP projects.](https://github.com/paragonie/easydb)
- [Security at the expense of usability comes at the expense of security.](https://security.stackexchange.com/questions/6095/xkcd-936-short-complex-password-or-long-dictionary-passphrase/6116#6116)
- [Security B-Sides Orlando 2017](https://www.bsidesorlando.org/2017/)
- [TimThumb WebShot Code Execution Exploit (Zeroday)](https://blog.sucuri.net/2014/06/timthumb-webshot-code-execution-exploit-0-day.html)
- [Reverse shell !?!](https://hackernoon.com/reverse-shell-cf154dfee6bd?gi=645807370574)
- [paragonie/anti-csrf - Full-Featured Anti-CSRF Library](https://github.com/paragonie/anti-csrf)
- [Using Libsodium in PHP Projects](https://paragonie.com/book/pecl-libsodium)
- [paragonie/sodium_compat - Pure PHP polyfill for ext/sodium](https://github.com/paragonie/sodium_compat)
- [libsodium](https://download.libsodium.org/doc/)
- [It Turns Out, 2017 is the Year of Simply Secure PHP Cryptography](https://paragonie.com/blog/2017/07/it-turns-out-2017-is-year-simply-secure-php-cryptography)
- [The ECB Penguin](https://blog.filippo.io/the-ecb-penguin/)
- [Cache-timing attacks on AES](https://cr.yp.to/antiforgery/cachetiming-20050414.pdf)
- [Side-Channel Attacks on Everyday Applications](https://www.youtube.com/watch?v=GPwNFrpd1KU)
- [Meltdown and Spectre](https://meltdownattack.com/)
- [PCID is now a critical performance/security feature on x86](http://archive.is/ma8Iw)
- [If You're Typing the Word MCRYPT Into Your PHP Code, You're Doing It Wrong](https://paragonie.com/blog/2015/05/if-you-re-typing-word-mcrypt-into-your-code-you-re-doing-it-wrong)
- [Myths about /dev/urandom](https://www.2uo.de/myths-about-urandom/)
- [PHP - random_bytes](http://php.net/manual/en/function.random-bytes.php)
- [PHP - random_int](http://php.net/manual/en/function.random-int.php)
- [Ward - Web Application Realtime Defender](https://ward.paragonie.com/)
