# Influx4s
This project intent is to be the missing functional ("a la typelevel") implementation of an [*InfluxDB*](https://docs.influxdata.com/influxdb/v1.5/introduction/) Scala driver.

**Important note: This project is a work in progress that has just started.**

## Motivation
At the time of this writing there are several repositories in GitHub that host an Scala implementation for an InfluxbDB driver; it happens that none of them are actually functional.

The hybrid, multi-paradigm nature of the Scala language allows different trends inside the Scala community. It seems that the mainstream one is a rather imperative / OO approach that is pretty much like it used to be with Java, but taking advantage of several nice Scala defaults (expression oriented, high order functions as first class citizens, immutability by default).

That is good; all those features are no-brainer software development best practices, and that multi-paradigm nature brings wider adoption and an smoother entry barrier from more mainstream programming habits. The use of Scala Futures brings a non-blocking, really natural way to work with a database. However, it is far from being as good as it could be. Scala allows us to do better in terms of modularity and therefore flexibility. For that we have to leverage Scala type system power and become functional.

This project aims to be that (for now) missing piece; inspired by the beautiful design of [Doobie](https://github.com/tpolecat/doobie) (a library to access relational databases using JDBC in a functional way).

I'm not sure how far this effort will go. [FLOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software) libraries are usually built on the sole effort of a few contributors (sometime one person!!) during their spare time. It is hard to complete any valuable work without sacrificing personal life and sometimes healthy habits (such as having enough sleep). I don't expect anyone to help me with this. Don't expect me to work seriously on it either.

This README file will be updated as progress is made.
