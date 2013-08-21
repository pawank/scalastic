---
layout: default
---

Scalastic is an interface for [ElasticSearch](http://www.elasticsearch.org), designed to provide more flexible
and Scala-esque interface around the native [ElasticSearch Java API](http://www.elasticsearch.org/guide/reference/java-api/).


# Installation

Add the following to your sbt build:

```scala
libraryDependencies += "org.scalastic" %% "scalastic" % "0.90.0.1"
```

**Please note**, Scalastic supports Scala 2.10.x only.

# Way cool, but how do I use it?

In general, look at the [test sources](https://github.com/{{ site.github_user }}/scalastic/tree/master/src/test/scala)
for usage examples or refer to [the documentation](https://github.com/{{ site.github_user }}/scalastic#way-cool-but-how-do-i-use-it).

## Versioning scheme
Scalastic versions correspond to ElasticSearch versions (starting from `0.90.0` binaries are available via Maven repo)
with a small addition - *the fourth* component of the version is used to reflect Scalastic improvements/bug fixes.

For example:
given ElasticSearch 0.90.0 - Scalastic versions will be 0.90.0, 0.90.0.1, 0.90.0.2 and so on.

## Contributors
* Benny Sadeh <benny.sadeh@gmail.com>
* Ivan Yatskevich ([github](https://github.com/yatskevich))
* you?

# License

This software is available under [Apache 2 license](http://www.apache.org/licenses/LICENSE-2.0.html).
