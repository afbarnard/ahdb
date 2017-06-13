AHDB
====


Ad Hoc DB (AHDB) is an analysis-oriented, zero-configuration, embedded,
relational database.  It is intended for data science and machine
learning workloads that fit on a single machine but exceed the
capabilities of SQLite.  That is, AHDB aims to be a column store version
of SQLite with the addition of a Spark-like API.

Well, those are my ideas, anyway.  (There's nothing much else to see
here yet, although I am prototyping some of the ideas in another
project, [Fitamord](https://github.com/afbarnard/fitamord).)

I intend to prototype the system in Python 3 and implement it in Rust.


-----

Copyright (c) 2017 Aubrey Barnard.  This is free software released under
the MIT License.  See `LICENSE.txt` for details.
