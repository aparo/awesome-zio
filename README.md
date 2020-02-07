Awesome ZIO [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
=============

[![](https://raw.githubusercontent.com/aparo/awesome-zio/master/awesome-zio.png)](https://github.com/aparo/awesome-zio)

A community driven list of useful ZIO libraries, frameworks and software.  Inspired by [awesome-python](https://github.com/vinta/awesome-python). Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

Projects with over 500 stargazers are in bold.

Based partial on ZIO documentation.


## Table of Contents

- [Projects](#projects)
    - [Actors](#actors)
    - [Algorithm](#algorithm)
    - [Config](#config)
    - [Database](#database)
    - [Dependency Injection](#dependency-injection)
    - [Email](#email)
    - [Framework](#framework)
    - [HTTP](#http)
    - [IO](#io)
    - [Logging](#logging)
    - [Metrics and Monitoring](#metrics-and-monitoring)
    - [Misc](#misc)
    - [NoSQL](#nosql)
    - [Sample](#sample)
- [Official ZIO Libraries](#official-zio-libraries)
- [Blog Articles](#blog-articles)
- [Talks](#talks)
- [CheatSheet](#cheatsheet)
- [News](#news)
- [Support](#support)
- [Contributing](#contributing)

## Projects

* [Rudder](https://github.com/normation/rudder): an example about how to manage error ADT in several sub-projects and specialized sub-domains, and how one can gradually contextualize error messages in domain layers. Uses queues, brackets, interop with Java, and historical code. See [context and references](https://issues.rudder.io/issues/14870).
* [ZIO AI Platform Backend](https://github.com/Clover-Group/zio_front): Clover Group AI Platform backend, which employs ZIO, Doobie, http4s and Kafka .
* [Polynote](https://github.com/polynote/polynote): a new, polyglot notebook with first-class Scala support, Apache Spark integration, multi-language interoperability including Scala, Python, and SQL, as-you-type autocomplete, and more.
* [TicTacToe command line game using Module Pattern](https://github.com/ioleo/zio-by-example) by [ioleo](https://github.com/ioleo)
* [Hello world with ZIO and http4s](https://gitlab.com/maplambda/zio-http4s) by [maplambda](https://gitlab.com/maplambda)
* [STM Partitioning - Code for the 'Exploring the STM functionality in ZIO' blog post](https://github.com/freskog/stm-partitioning)
* [ZIO Todo Backend](https://github.com/mschuwalow/zio-todo-backend) by [mschuwalow](https://github.com/mschuwalow)
* [Event Driven Messenger](https://github.com/edvmorango/event-driven-messenger) by [edvmorango](https://github.com/edvmorango)
* [Zorechka Bot](https://github.com/wix-incubator/zorechka-bot) by [wix-incubator](https://github.com/wix-incubator)
* [A ZIO + http4s + Circe + Quill + Tapir giter8 template](https://github.com/pandaforme/ultron.g8) by [pandaforme](https://github.com/pandaforme)
* [More ZIO/http4s: with http4s authentication, encoding/decoding + zio tests](https://github.com/TimPigden/zio-http4s-examples) by [Tim Pigden](https://github.com/TimPigden)
* [GitHub Release Pager with ZIO](https://github.com/psisoyev/release-pager) by [Pavels Sisojevs](https://github.com/psisoyev)
* [Seed Build Tool](https://github.com/tindzk/seed): by [Tim Nieradzik](https://github.com/tindzk/seed) [Build tool](https://tindzk.github.io/seed/) for Scala projects
* [A Ray tracer built using ZIO to learn environmental effects](https://github.com/pierangeloc/ray-tracer-zio): by [Pierangelo Cecchetto](https://github.com/pierangeloc) a ray tracer to learn ZIO modules
* [zio3D](https://github.com/wongelz/zio3d): An experimental 3D game built with ZIO and OpenGL (LWJGL)
- [ZIO modules with different implementations - Code for the 'Decouple the Program from its Implementation...' blog post 12/2019](https://github.com/pme123/zio-comps-module) by [pme123](https://github.com/pme123)
- [Long Polling with ZIO - Code for the 'What can ZIO do for me?' blog post 11/2019](https://github.com/pme123/zio-http4s-long-polling) by [pme123](https://github.com/pme123)
- [Full Scala Stack, a sample project that uses akka-http, slick, zio, scalajs, react, ScalablyTyped and semantic ui](https://github.com/rleibman/full-scala-stack) by Roberto Leibman
- [A minimal ZIO giter8 template](https://github.com/jchoffmann/zio-seed.g8) by [jchoffmann](https://github.com/jchoffmann)


## Actor

* [ZIO Actors](https://github.com/zio/zio-actors): A high-performance, purely-functional library for building, composing, and supervising typed actors based on ZIO
* [ZIO Akka Cluster](https://github.com/zio/zio-akka-cluster): A ZIO wrapper for Akka Cluster

## Algorithm

* [cakeless](https://github.com/itkpi/cakeless): Better reader monad for deeply-nested cakes
* [zio-saga](https://github.com/VladKopanev/zio-saga): Purely functional transaction management with Saga pattern

## Config

* [ZIO Config](https://github.com/zio/zio-config): A ZIO based configuration parsing library

## Database

* [zio-slick](https://github.com/rleibman/zio-slick): Bridge library between ZIO and Slick Functional Relational Mapping Library

## Dependency Injection

* [distage](https://github.com/7mind/izumi): Staged, transparent and debuggable runtime & compile-time Dependency Injection Framework

## Email

* [zio-email](https://github.com/funcit/zio-email): Purely functional email client

## Frameworks

* [caliban](https://github.com/ghostdogpr/caliban): Functional GraphQL backend in Scala
* [idealingua](https://github.com/7mind/izumi): API Definition, Data Modeling and RPC Language, optimized for fast prototyping – like gRPC, but with a human face

## HTTP

*ZIO libraries and wrappers for HTTP clients.*

* [ZIO HTTP](https://github.com/zio/zio-http): A ZIO-powered HTTP server and client
* **[Http4s ★ 732 ⧗ 3](https://github.com/http4s/http4s)** - A minimal, idiomatic Scala interface for HTTP.
* [sttp](https://github.com/softwaremill/sttp) - The Scala HTTP client you always wanted!
* [zio-google-cloud-oauth2](https://github.com/jkobejs/zio-google-cloud-oauth2) - zio-google-cloud-ouath2 is effectful API for [Google OAuth 2.0](https://developers.google.com/identity/protocols/OAuth2) flows for Scala.


## IO

* [ZIO NIO](https://github.com/zio/zio-nio): A performant, purely-functional, low-level, and unopinionated wrapper around Java NIO functionality

## Logging

*ZIO libraries and wrappers for Logging*

* [logstage](https://github.com/7mind/izumi): Automatic structural logs from Scala string interpolations
* [ZIO Logging](https://github.com/zio/zio-logging): An environmental effect for adding logging into any ZIO application, with choice of pluggable back-ends
* [slf4zio](https://github.com/mlangc/slf4zio): Simple convenience layer on top of SLF4J for ZIO
* [zio-slf4j](https://github.com/NeQuissimus/zio-slf4j): Referentially transparent logging with slf4j
* [zio-interop-log4j2](https://github.com/mlangc/zio-interop-log4j2): Fiber aware MDC logging for Log4j 2

## Metrics and Monitoring

* [ZIO Metric](https://github.com/zio/zio-metrics): A high-performance, purely-functional library for adding instrumentation to any application, with a simple web client and JMX support.
* [ZIO Telemetry](https://github.com/zio/zio-telemetry): A ZIO-powered OpenTelemetry library

## Misc

* [zio-graphviz](https://github.com/alexknvl/zio-graphviz): Simple Graphviz API for ZIO.
* [zio-wayback](https://github.com/alexknvl/zio-wayback): ZIO + Wayback Machine API
* [Zparkio](https://github.com/leobenkel/Zparkio): Boiler plate framework to use Spark and ZIO together.

## NoSQL

* [ZIO Kafka](https://github.com/zio/zio-kafka): A Kafka client for ZIO and ZIO Streams
* [zio-kafka-registry](https://github.com/TimPigden/zio-kafka-registry): Project to use zio-kafka in combination with the Confluent Schema Registry.
* [zio-elasticsearch](https://github.com/aparo/zio-elasticsearch): ElasticSearch client for Scala based on ZIO and FP by [Alberto Paro](https://github.com/aparo) 
* [elastic4s](https://github.com/sksamuel/elastic4s): Elasticsearch Scala Client - Reactive, Non Blocking, Type Safe, HTTP Client
* [neotypes](https://github.com/neotypes/neotypes): A Scala lightweight, type-safe & asynchronous driver for neo4j
* [scanamo](https://github.com/scanamo/scanamo): Simpler DynamoDB access for Scala
* [ZIO SQS](https://github.com/zio/zio-sqs): A ZIO-powered client for AWS SQS
* [ZIO Keeper](https://github.com/zio/zio-keeper): A functional library for consistent replication of metadata across dynamic clusters
* [SwayDB](https://github.com/simerplaha/SwayDB): [Embeddable persistent & in-memory database](http://www.SwayDB.io)
* [zio-amqp](https://github.com/svroonland/zio-amqp): ZIO AMQP is a ZIO-based wrapper around the RabbitMQ client. It provides a streaming interface to AMQP queues and helps to prevent you from shooting yourself in the foot with thread-safety issues.
* [zio-kinesis](https://github.com/svroonland/zio-kinesis): ZIO Kinesis is a ZIO-based wrapper around the AWS Kinesis SDK. All operations are non-blocking. It provides a streaming interface to Kinesis streams. 
* [zio-rocksdb](https://github.com/zio/zio-rocksdb): A ZIO-based interface to RocksDB.


## Sample

Some repositories that contains useful code to look at.

* [zio-cookbook](https://github.com/Neurodyne/zio-cookbook): Cookbook apps for ZIO


## Official ZIO Libraries

These libraries are hosted in the [ZIO organization](https://github.com/zio/) on Github, and are generally maintained by core contributors to ZIO.

* [ZIO Actors](https://github.com/zio/zio-actors): A high-performance, purely-functional library for building, composing, and supervising typed actors based on ZIO
* [ZIO Akka Cluster](https://github.com/zio/zio-akka-cluster): A ZIO wrapper for Akka Cluster
* [ZIO Config](https://github.com/zio/zio-config): A ZIO based configuration parsing library
* [ZIO HTTP](https://github.com/zio/zio-http): A ZIO-powered HTTP server and client
* [ZIO Kafka](https://github.com/zio/zio-kafka): A Kafka client for ZIO and ZIO Streams
* [ZIO Keeper](https://github.com/zio/zio-keeper): A functional library for consistent replication of metadata across dynamic clusters
* [ZIO Logging](https://github.com/zio/zio-logging): An environmental effect for adding logging into any ZIO application, with choice of pluggable back-ends
* [ZIO NIO](https://github.com/zio/zio-nio): A performant, purely-functional, low-level, and unopinionated wrapper around Java NIO functionality
* [ZIO SQS](https://github.com/zio/zio-sqs): A ZIO-powered client for AWS SQS
* [ZIO Telemetry](https://github.com/zio/zio-telemetry): A ZIO-powered OpenTelemetry library

## Blog Articles

_These articles reflect the state of ZIO at the time of their publication. The code samples might be outdated, considering ZIO was early in development at the time they were written. However, the concepts are still relevant._

* [Effective testing with ZIO Test](https://scala.monster/zio-test/) by Pavels Sisojevs (January 2020)
* [Implementing your future with ZIO](https://scala.monster/welcome-zio/) By Pavels Sisojevs (December 2019)
* [How to write a command line application with ZIO?](https://scalac.io/write-command-line-application-with-zio/) by Piotr Gołębiewski (November 2019)
* [Simulating IoT Events with ZIO Streams](https://timpigden.github.io/_pages/zio-streams/GeneratingChillEvents.html) by Tim Pigden (November 2019)
* [Speeding up time with ZIO TestClock](https://timpigden.github.io/_pages/zio-streams/SpeedingUpTime.html) by Tim Pigden (October 2019)
* [ZIO with http4s, Auth, Codecs and zio-tests](https://timpigden.github.io/_pages/zio-http4s/intro.html) by Tim Pigden (October 2019)
* [Functional dependency injection in Scala using ZIO environments](https://blog.jdriven.com/2019/10/functional-dependency-injection-in-scala-using-zio-environments/) by Chiel van de Steeg (October 2019)
* [Making ZIO, Akka and Slick play together nicely](https://scalac.io/making-zio-akka-slick-play-together-nicely-part-1-zio-and-slick/) by Jakub Czuchnowski (August 2019)
* [Wrapping impure code with ZIO](https://medium.com/@ghostdogpr/wrapping-impure-code-with-zio-9265c219e2e) by Pierre Ricadat (July 2019)
* [Combining ZIO and Akka to enable distributed FP in Scala](https://medium.com/@ghostdogpr/combining-zio-and-akka-to-enable-distributed-fp-in-scala-61ffb81e3283) by Pierre Ricadat (July 2019)
* [tAPIr’s Endpoint meets ZIO’s IO](https://blog.softwaremill.com/tapirs-endpoint-meets-zio-s-io-3278099c5e10) by Adam Warski (July 2019)
* [ZIO with http4s and doobie](https://medium.com/@wiemzin/zio-with-http4s-and-doobie-952fba51d089) by Wiem Zine Elabadine (June 2019)
* [Thread shifting in cats-effect and ZIO](https://blog.softwaremill.com/thread-shifting-in-cats-effect-and-zio-9c184708067b) by Adam Warski (June 2019)
* [Exploring the STM functionality in ZIO](https://freskog.github.io/blog/2019/05/30/explore-zio-stm/) by Fredrik Skogberg (May 2019)
* [Performant Functional Programming to the Max with ZIO](https://cloudmark.github.io/A-Journey-To-Zio/) by Mark Galea (May 2019)
* [Using 47 Degree's Fetch library with ZIO](http://justinhj.github.io/2019/05/05/using-47degs-fetch-with-zio.html) by Justin Heyes-Jones (May 2019)
* [ZIO & Cats Effect: A Match Made in Heaven](http://degoes.net/articles/zio-cats-effect) by John De Goes (April 2019)
* [Hacker News API Part 5](http://justinhj.github.io/2019/04/07/hacker-news-api-5.html) by Justin Heyes-Jones (April 2019)
* [Testing Incrementally with ZIO Environment](http://degoes.net/articles/testable-zio) by John De Goes (March 2019)
* [Beautiful, Simple, Testable Functional Effects for Scala](http://degoes.net/articles/zio-environment) (introducing ZIO Environment) by John De Goes (February 2019)
* [Thread Pool Best Practices with ZIO](http://degoes.net/articles/zio-threads) by John De Goes (January 2019)
* [Building the Hangman Game using ScalaZ ZIO](https://abhsrivastava.github.io/2018/11/03/Hangman-Game-Using-ZIO/) by Abhishek Srivastava (November 2018)
* [Elevator Control System using ZIO](https://medium.com/@wiemzin/elevator-control-system-using-zio-c718ae423c58) by Wiem Zine Elabadine (September 2018)
* [Scalaz 8 IO vs Akka (typed) Actors vs Monix (part 1)](https://blog.softwaremill.com/scalaz-8-io-vs-akka-typed-actors-vs-monix-part-1-5672657169e1) + [part 2](https://blog.softwaremill.com/akka-vs-zio-vs-monix-part-2-communication-9ce7261aa08c) + [part 3](https://blog.softwaremill.com/supervision-error-handling-in-zio-akka-and-monix-part-3-series-summary-abe75f964c2a) by Adam Warski (June 2018)
* [Bifunctor IO: A Step Away from Dynamically-Typed Error Handling](http://degoes.net/articles/bifunctor-io) by John De Goes (May 2018)

## Talks

* [Magic Tricks with Functional Effects](https://www.youtube.com/watch?v=xpz4rf1RS8c) by John A. De Goes (November 2019)
* [12 Steps To Better Scala (Part I)](https://www.youtube.com/watch?v=71yhnTGw0hY) by John De Goes (October 2019)
* [Upgrade Your Future](https://www.youtube.com/watch?v=USgfku1h7Hw) by John De Goes (September 2019)
* [One Monad to Rule Them All](https://www.youtube.com/watch?v=POUEz8XHMhE) by John De Goes (August 2019)
* [Functional Concurrency in Scala with ZIO](https://www.youtube.com/watch?v=m5nas4Hndqo) by Itamar Ravid (June 2019)
* [Error Management: Future vs ZIO](https://www.youtube.com/watch?v=mGxcaQs3JWI) by John De Goes and Kai (May 2019)
* [Atomically { Delete Your Actors }](https://www.youtube.com/watch?v=d6WWmia0BPM) by John De Goes and Wiem Zine Elabadine (April 2019)
* [Thinking Functionally](https://www.youtube.com/watch?v=-KA3BSdqYug) by John De Goes (March 2019)
* [Tour of ZIO](https://www.youtube.com/watch?v=5s0GOA3WQnY&t=1405s) by Oleksandra Holubitska (March 2019)
* [The Death of Tagless Final](https://skillsmatter.com/skillscasts/13247-scala-matters) by John De Goes (February 2019)
* [ZIO Queue](https://www.youtube.com/watch?v=lBYkLc-j7Vo) by Wiem Zine Elabadine (January 2019)
* [ZIO Stream: Rebirth](https://www.youtube.com/watch?v=mLJYODobz44&t=15s) by John De Goes and Itamar Ravid (November 2018)
* [ZIO Schedule: Conquering Flakiness and Recurrence with Pure Functional Programming](https://www.youtube.com/watch?v=onQSHiafAY8&t=1s) by John De Goes (October 2018)
* [ZIO: Next-Generation Effects in Scala](https://www.youtube.com/watch?v=mkSHhsJXjdc&t=6s) by John De Goes (October 2018)
* [ZIO Queue: A new Queue for a new Era](https://www.youtube.com/watch?v=8JLprl34xEw&t=2437s) by John De Goes (September 2018)


## News

* [ZIO News 1](https://www.getrevue.co/profile/zio/issues/zio-news-issue-1-208701): ZIO News 1
* [ZIO News 2](https://www.getrevue.co/profile/zio/issues/zio-news-issue-2-209078): ZIO News 2

## CheatSheet

* [ZIO Cheat Sheet](https://github.com/ghostdogpr/zio-cheatsheet)
* [Snippets for Future/Scalaz Task](https://gist.github.com/ubourdon/7b7e929117343b2324cde6eab57674a6)

## Support

* [Offical Discord Server](https://discord.gg/2ccFBr4)
* [Official Gitter Channel](https://gitter.im/ZIO/Core)


# Contributing
* Make sure you are about to post a valuable resource that belongs to this list
* Do NOT group ++Add and --Remove changes in same PR. Make them separate pull requests
* Use spellchecker
* All spelling and grammar corrections are welcome (except for the rule above)
* Fork this repo, do your edits, send the pull request
* Feel free to create any new sections
* Do not even try to add this repo to any awesome-awesome-* lists 
