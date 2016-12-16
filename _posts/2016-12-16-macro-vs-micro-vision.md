---
title: Macro vs. Micro Vision
abstract: "Discussion on Postgres MVCC, JavaScript Unicode support and testing time-dependent processes"
date: 2016-12-16T11:00:00.000Z
file: 113-macro-vs-micro-vision.mp3
layout: podcast
number: 113
size: 28678079
duration: 3109
---

In this weeks episode we start off by congratulating Mick on handing in his masters dissertation.
We then move on to discuss decision trees, ordinal regression and genetic algorithms.
Edd then mentions managing large tables in Postgres, MVCC, Fill factors and Vacuuming a table.
From here we highlight an interesting JavaScript Unicode/New-Line length issue that occurred recently.
Finally, we touch upon testing time-dependent processes in isolation, dreaded CRM integration and sign-up processes.

**Corrections:** Couple of mistakes by Edd; its' MVCC not MVVC, and any character that can't be represented using 8 bits in PHP will have a `strlen` > 1.

### Show Links

- [Decision trees](https://en.wikipedia.org/wiki/Decision_tree)
- [Ordinal regression](https://en.wikipedia.org/wiki/Ordinal_regression)
- [Weka - Data Mining with Open Source Machine Learning Software in Java](http://www.cs.waikato.ac.nz/ml/weka/)
- [Learning to rank](https://en.wikipedia.org/wiki/Learning_to_rank)
- [Shannon entropy](https://en.wiktionary.org/wiki/Shannon_entropy)
- [The Awesome Table Fillfactor to speedup UPDATE and SELECT statement](http://www.dbrnd.com/2016/03/postgresql-the-awesome-table-fillfactor-to-speedup-update-and-select-statement/)
- [PostgreSQL - Difference between table fillfactor and index fillfactor](http://dba.stackexchange.com/questions/15306/difference-between-table-fillfactor-and-index-fillfactor/15307#15307)
- [PostgreSQL Concurrency with MVCC](https://devcenter.heroku.com/articles/postgresql-concurrency)
- [grayhemp/pgtoolkit: Tools for PostgreSQL maintenance](https://github.com/grayhemp/pgtoolkit)
- [Reducing bloat without locking ](http://blog.endpoint.com/2010/09/reducing-bloat-without-locking.html)
- [Reduce bloat of table without long/exclusive locks](https://www.depesz.com/2010/10/17/reduce-bloat-of-table-without-longexclusive-locks/)
- [TOAST - PostgreSQL](https://wiki.postgresql.org/wiki/TOAST)
- [Understanding Character Sets and Encodings - Three Devs and a Maybe](http://threedevsandamaybe.com/understanding-character-sets-and-encodings/)
- [JavaScript has a Unicode problem - Mathias Bynens](https://mathiasbynens.be/notes/javascript-unicode)
- [bestiejs/punycode.js: A robust Punycode converter that fully complies to RFC 3492 and RFC 5891.](https://github.com/bestiejs/punycode.js)
- [Basic Multilingual Plane (Unicode)](https://en.wikipedia.org/wiki/Plane_(Unicode)#Basic_Multilingual_Plane)
- [The Great Newline Schism](https://blog.codinghorror.com/the-great-newline-schism/)
- [cemerson/clock - Packagist](https://packagist.org/packages/cemerson/clock)
- [krakjoe/uopz: User Operations for Zend](https://github.com/krakjoe/uopz)
- [Carbon - A simple PHP API extension for DateTime.](http://carbon.nesbot.com/docs/#api-testing)
- [Test Doubles](http://martinfowler.com/bliki/TestDouble.html)
- [seanpowell/Email-Boilerplate: The email boilerplate for sending out nicely formatted messages.](https://github.com/seanpowell/Email-Boilerplate)
- [Taylor Otwell on Twitter: "Laravel 5.4: write your mail / notifications in simple Markdown with Blade..."](https://twitter.com/taylorotwell/status/808359354139312129)
