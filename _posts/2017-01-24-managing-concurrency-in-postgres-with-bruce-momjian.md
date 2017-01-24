---
title: Managing Concurrency in Postgres with Bruce Momjian
abstract: "Exploration into how Relational databases such as Postgres manage concurrency using MVCC"
date: 2017-01-24T09:30:00.000Z
file: 117-managing-concurrency-in-postgres-with-bruce-momjian.mp3
layout: podcast
number: 117
size: 47481779
duration: 4898
---

Following on from our previous look at the Query planner - we are joined again by Bruce Momjian to extend this exploration into looking how Postgres manages concurrency.
We start off by discussing some of the challenges and workarounds used in the past to handle concurrent access, particularly in the eyes of a database administrator.
We then highlight the concept of MVCC, how it works from a high-level, how Postgres implements it and the clean-up considerations that are present.
Finally, we mention how Postgres stores data in page-form, how projects such as pg_compact work to regain space and what the fill-factor is.

### Show Links

- [Bruce Momjian](https://momjian.us/)
- [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))
- [MVCC Unmasked](https://momjian.us/main/writings/pgsql/mvcc.pdf)
- [Multi-user Operating Systems](https://en.wikipedia.org/wiki/Multi-user)
- [Multiversion concurrency control](https://en.wikipedia.org/wiki/Multiversion_concurrency_control)
- [Dirty Reads](https://en.wikipedia.org/wiki/Isolation_(database_systems)#Dirty_reads)
- [PostgreSQL - Transaction Isolation Levels](https://www.postgresql.org/docs/9.6/static/transaction-iso.html)
- [PostgreSQL - Database Page Layout](https://www.postgresql.org/docs/9.6/static/storage-page-layout.html)
- [PostgreSQL - VACUUM](https://www.postgresql.org/docs/9.6/static/sql-vacuum.html)
- [grayhemp/pgtoolkit: Tools for PostgreSQL maintenance](https://github.com/grayhemp/pgtoolkit)
- [reorg/pg_repack: Reorganize tables in PostgreSQL databases with minimal locks](https://github.com/reorg/pg_repack)
