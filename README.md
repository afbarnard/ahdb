AHDB
====


Ad Hoc DB (AHDB) is an analysis-oriented, zero-configuration, embedded,
relational database.  It aims to make ad hoc queries on ad hoc
collections of files easy and fast, so that you say "Ah!" instead of
"Argh!".  It is intended for data science and machine learning workloads
that fit on a single machine but exceed the capabilities of SQLite.
That is, AHDB aims to be a column store version of SQLite with the
addition of a Spark-like API.  Or, to put it another way, AHDB aims to
provide an API for a relational collection of data frames (like in R or
Pandas) where the data can be larger than memory.

I intend to prototype the system in Python 3 and implement it in Rust.

Well, those are my ideas, anyway.  (There's nothing much else to see
here yet, although I am prototyping some of the ideas in another
project, [Fitamord](https://github.com/afbarnard/fitamord).)


-----

Copyright (c) 2017 Aubrey Barnard.  This is free software released under
the MIT License.  See `LICENSE.txt` for details.
