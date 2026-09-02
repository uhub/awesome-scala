# awesome-scala

A curated list of awesome Scala frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Editor and IDE Support](#editor-and-ide-support)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Frontend and UI Components](#frontend-and-ui-components)
	* [Web Servers and Proxies](#web-servers-and-proxies)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
	* [Search and Indexing](#search-and-indexing)
* Machine Learning and AI
	* [Machine Learning Frameworks](#machine-learning-frameworks)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Game Development](#game-development)
* Security
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Date and Time](#date-and-time)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
	* [Formal Methods and Proofs](#formal-methods-and-proofs)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [ochrons/scalajs-spa-tutorial](https://github.com/ochrons/scalajs-spa-tutorial) - Tutorial for creating a simple Single Page Application in ScalaJS
* [dehun/learn-fp](https://github.com/dehun/learn-fp) - learn-by-doing course/tutorial for functional programming on scala
* [slouc/concurrency-in-scala-with-ce](https://github.com/slouc/concurrency-in-scala-with-ce) - Introduction to concepts of asynchronous and concurrent programming in Scala, based on the Cats Effect library.
* [mbonaci/scala](https://github.com/mbonaci/scala) - Scala reference (as seen by Java developer)
* [lemastero/scala_typeclassopedia](https://github.com/lemastero/scala_typeclassopedia) - Abstractions from Category theory with simple description & implementation, links to further resources.
* [Baeldung/scala-tutorials](https://github.com/Baeldung/scala-tutorials) - Supporting code for the tutorials on https://www.baeldung.com/scala
* [twitter/scala_school2](https://github.com/twitter/scala_school2) - Scala School 2
* [rockthejvm/scala-2-beginners](https://github.com/rockthejvm/scala-2-beginners) - The official repository for the Rock the JVM Scala 2 for beginners course
* [rockthejvm/scala-at-light-speed](https://github.com/rockthejvm/scala-at-light-speed) - The repository for the free Scala at Light Speed mini-course
* [rockthejvm/spark-essentials](https://github.com/rockthejvm/spark-essentials) - The official repository for the Rock the JVM Spark Essentials with Scala course
* [EffectOrientedProgramming/book](https://github.com/EffectOrientedProgramming/book) - Effect-Oriented Programming: Creating Reliable Systems with Scala 3 and ZIO 2
* [scalacenter/scala-3-migration-guide](https://github.com/scalacenter/scala-3-migration-guide) - The Scala 3 migration guide for everyone.
* [creativescala/creative-scala](https://github.com/creativescala/creative-scala) - Quick, graphical, fun introduction to programming in Scala.
* [lunatech-labs/lunatech-scala2-to-scala3-course](https://github.com/lunatech-labs/lunatech-scala2-to-scala3-course) - Lunatech course - "Moving forward from Scala 2 to Scala 3" *(archived)*
* [opensourceteams/spark-scala-maven-2.4.0](https://github.com/opensourceteams/spark-scala-maven-2.4.0) - Spark2.4.0 学习笔记分享
* [makingthematrix/scalaonandroid](https://github.com/makingthematrix/scalaonandroid) - A tutorial and examples of how to write Android apps in Scala 2.13 and Scala 3.
* [bizreach-inc/play2-hands-on](https://github.com/bizreach-inc/play2-hands-on) - Play2 + Slick / ScalikeJDBCを使ってWebアプリケーションを作成するハンズオンです。
* [jdegoes/functional-scala](https://github.com/jdegoes/functional-scala) - The repository for the Functional Scala workshop.
* [jdegoes/lambdaconf-2014-introgame](https://github.com/jdegoes/lambdaconf-2014-introgame) - Online material for the Introduction to Functional Game Programming with Scala workshop.
* [rockthejvm/scala-2-advanced](https://github.com/rockthejvm/scala-2-advanced) - The Scala 2 version (old) of the Advanced Scala course
* [lihaoyi/hands-on-scala-js](https://github.com/lihaoyi/hands-on-scala-js) - Better documentation for Scala.js
* [evolution-gaming/scala-bootcamp](https://github.com/evolution-gaming/scala-bootcamp) - Scala Bootcamp
* [yareally/android-scala-intellij-no-sbt-plugin](https://github.com/yareally/android-scala-intellij-no-sbt-plugin) - Directions on how to create a Scala based project in Intellij IDEA without having to resort to additional plugins or external building that cripples the nice features of the IDE.
* [darrenjw/scala-course](https://github.com/darrenjw/scala-course) - Scala for Statistical Computing and Data Science Short Course
* [jleetutorial/scala-spark-tutorial](https://github.com/jleetutorial/scala-spark-tutorial) - Project for James' Apache Spark with Scala course
* [scala-lms/tutorials](https://github.com/scala-lms/tutorials) - Tutorials on Lightweight Modular Staging
* [SidneyXu/JGSK](https://github.com/SidneyXu/JGSK) - Java,Groovy,Scala,Kotlin 四种语言的特点对比
* [ashwinbhaskar/scala-to-dotty](https://github.com/ashwinbhaskar/scala-to-dotty) - Dotty way of writing Scala 2 code
* [ktonga/reactive-turtle](https://github.com/ktonga/reactive-turtle) - Scala and Akka for kids. A Functional Programming approach for the well known LOGO.
* [underscoreio/essential-scala](https://github.com/underscoreio/essential-scala) - Source code for Underscore's Essential Scala
* [microsoft/Azure-Databricks-NYC-Taxi-Workshop](https://github.com/microsoft/Azure-Databricks-NYC-Taxi-Workshop) - An Azure Databricks workshop leveraging the New York Taxi and Limousine Commission Trip Records dataset *(archived)*
* [scalasummerschool/lectures](https://github.com/scalasummerschool/lectures) - Learn Functional Programming in Scala
* [scalawarrior/scalawarrior](https://github.com/scalawarrior/scalawarrior) - Game written in Scala for learning Scala.

### Examples and Exercises

* [fpinscala/fpinscala](https://github.com/fpinscala/fpinscala) - Code, exercises, answers, and hints to go along with the book "Functional Programming in Scala"
* [scala-exercises/scala-exercises](https://github.com/scala-exercises/scala-exercises) - The easy way to learn Scala.
* [vkostyukov/scalacaster](https://github.com/vkostyukov/scalacaster) - Purely Functional Algorithms and Data Structures in Scala
* [TheAlgorithms/Scala](https://github.com/TheAlgorithms/Scala) - All Algorithms implemented in Scala
* [jacksu/utils4s](https://github.com/jacksu/utils4s) - scala、spark使用过程中，各种测试用例以及相关资料整理
* [pauljamescleary/scala-pet-store](https://github.com/pauljamescleary/scala-pet-store) - An implementation of the java pet store using FP techniques in scala
* [softwaremill/bootzooka](https://github.com/softwaremill/bootzooka) - Template project to quickly start developing a Scala-based microservice or web application, with the build & project structure provided
* [theiterators/akka-http-microservice](https://github.com/theiterators/akka-http-microservice) - Example of http (micro)service in Scala & akka-http
* [miguno/kafka-storm-starter](https://github.com/miguno/kafka-storm-starter) - [PROJECT IS NO LONGER MAINTAINED] Code examples that show to integrate Apache Kafka 0.8+ with Apache Storm 0.9+ and Apache Spark Streaming 1.1+, while using Apache Avro as the data serialization format. *(archived)*
* [handsonscala/handsonscala](https://github.com/handsonscala/handsonscala) - Discussion and and code examples for the book Hands-on Scala Programming
* [gvolpe/trading](https://github.com/gvolpe/trading) - 💱 Trading application written in Scala 3 that showcases an Event-Driven Architecture (EDA) and Functional Programming (FP)
* [deanwampler/programming-scala-book-code-examples](https://github.com/deanwampler/programming-scala-book-code-examples) - The code examples used in Programming Scala, 2nd and 3rd Editions (O'Reilly)
* [spark-examples/spark-scala-examples](https://github.com/spark-examples/spark-scala-examples) - This project provides Apache Spark SQL, RDD, DataFrame and Dataset examples in Scala language
* [gvolpe/pfps-shopping-cart](https://github.com/gvolpe/pfps-shopping-cart) - :shopping_cart: The Shopping Cart application developed in the book "Practical FP in Scala: A hands-on approach"
* [fosskers/scalaz-and-cats](https://github.com/fosskers/scalaz-and-cats) - Usage examples and benchmarks between Scalaz and Cats (w/ Haskell ground-truth).
* [spirom/LearningSpark](https://github.com/spirom/LearningSpark) - Scala examples for learning to use Spark
* [pathikrit/scalgos](https://github.com/pathikrit/scalgos) - algorithms in scala
* [vmunier/play-scalajs.g8](https://github.com/vmunier/play-scalajs.g8) - Giter8 template to get started with Play and Scala.js.
* [streaming-with-flink/examples-scala](https://github.com/streaming-with-flink/examples-scala) - Stream Processing with Apache Flink - Scala Examples
* [matthiasn/sse-chat](https://github.com/matthiasn/sse-chat) - Chat example app using Server Sent Events plus REST calls. Scala, Play Framework 2.3, AngularJS or React (alternatively).
* [bytedeco/javacv-examples](https://github.com/bytedeco/javacv-examples) - Examples of using JavaCV / OpenCV library on Java Virtual Machine
* [jrudolph/pekko-http-scala-js-websocket-chat](https://github.com/jrudolph/pekko-http-scala-js-websocket-chat) - An example app that integrates pekko-http and scala-js to implement a websocket chat
* [scala/scala3-example-project](https://github.com/scala/scala3-example-project) - An example sbt project that compiles using Dotty
* [spotify/big-data-rosetta-code](https://github.com/spotify/big-data-rosetta-code) - Code snippets for solving common big data problems in various platforms. Inspired by Rosetta Code
* [garyaiki/Scala-Algorithms](https://github.com/garyaiki/Scala-Algorithms) - Scala translations of Robert Sedgewick's Java Algorthms
* [scala-labs/scala-labs](https://github.com/scala-labs/scala-labs) - A collection of hands-on programming exercises aimed at teaching you to program in Scala
* [kyleu/boilerplay](https://github.com/kyleu/boilerplay) - Using the latest technology in the Scala ecosystem, Boilerplay is a reactive web application built on Play Framework, ScalaJS, Silhouette, Sangria/GraphQL, and PostgreSQL. It provides a good starting point for whatever you want to build.
* [typelevel/CT_from_Programmers.scala](https://github.com/typelevel/CT_from_Programmers.scala) - Scala sample code for Bartosz Milewski's CT for Programmers *(archived)*
* [playforscala/sample-applications](https://github.com/playforscala/sample-applications) - Sample applications that go with the book Play for Scala
* [jaceklaskowski/scalania](https://github.com/jaceklaskowski/scalania) - Learn Scala by examples
* [theiterators/reactive-microservices](https://github.com/theiterators/reactive-microservices) - Project showcasing different microservice communication styles using Scala, Akka, Play and other tools from Scala ecosystem
* [codeport/scala](https://github.com/codeport/scala) - LascoDan(Korea Scala Group) scala study
* [concurrent-programming-in-scala/learning-examples](https://github.com/concurrent-programming-in-scala/learning-examples) - Code examples for the book Learning Concurrent Programming in Scala
* [playframework/play-scala-rest-api-example](https://github.com/playframework/play-scala-rest-api-example) - Example Play Scala application showing REST API *(archived)*
* [daizikaikou/learningSpark](https://github.com/daizikaikou/learningSpark) - 学习spark写的scala代码，工具使用的是IDEA2017.1.6,欢迎star
* [josephguan/scala-design-patterns](https://github.com/josephguan/scala-design-patterns) - Design patterns implemented in Scala.
* [lihaoyi/workbench-example-app](https://github.com/lihaoyi/workbench-example-app) - An example application written in ScalaJS using scala-js-dom and scala-js-workbench
* [Algomancer/Full-Stack-Scala-Starter](https://github.com/Algomancer/Full-Stack-Scala-Starter) - Play 2.5, ScalaJS, Binding.scala starter project.
* [gvolpe/pfps-examples](https://github.com/gvolpe/pfps-examples) - :izakaya_lantern: Standalone examples shown in the book "Practical FP in Scala: A hands-on approach"
* [spirom/spark-streaming-with-kafka](https://github.com/spirom/spark-streaming-with-kafka) - Self-contained examples of Apache Spark streaming integrated with Apache Kafka.
* [SidneyXu/AndroidDemoIn4Languages](https://github.com/SidneyXu/AndroidDemoIn4Languages) - Comparison among Java, Groovy, Scala, Kotlin in Android Development.
* [playframework/play-scala-websocket-example](https://github.com/playframework/play-scala-websocket-example) - Example Play Scala application showing WebSocket use with Akka actors *(archived)*
* [ilya-klyuchnikov/tapl-scala](https://github.com/ilya-klyuchnikov/tapl-scala) - Code from the book "Types and Programming Languages" in Scala
* [jaspervz/todo-http4s-doobie](https://github.com/jaspervz/todo-http4s-doobie) - A sample project of a microservice using http4s, doobie, and circe.
* [wiringbits/scala-webapp-template](https://github.com/wiringbits/scala-webapp-template) - A pragmatic skeleton to build web applications in Scala/Scala.js, including user registration, login, admin portal, and, deployments
* [eligosource/eventsourced-example](https://github.com/eligosource/eventsourced-example) - A Scala web application demonstrating event-sourcing best practices
* [lamdor/scala-koans](https://github.com/lamdor/scala-koans) - The Scala Koans
* [miciek/grokkingfp-examples](https://github.com/miciek/grokkingfp-examples) - All examples and exercises from the Grokking Functional Programming book
* [ReactivePlatform/Pragmatic-Scala](https://github.com/ReactivePlatform/Pragmatic-Scala) - Pragmatic Scala 中文版——《Scala实用指南》代码清单（包含 SBT 版本（切到sbt分支））
* [pbassiner/sbt-multi-project-example](https://github.com/pbassiner/sbt-multi-project-example) - sbt multi-project example
* [mariussoutier/PlayBasics](https://github.com/mariussoutier/PlayBasics) - Example code for my tutorial series about Play Framework 2.x
* [scala-exercises/exercises-scalatutorial](https://github.com/scala-exercises/exercises-scalatutorial) - Exercises for the "Functional Programming Principles in Scala", part of the FP in Scala specialized program by EPFL.
* [sjrd/scala-js-example-app](https://github.com/sjrd/scala-js-example-app) - Example application built with Scala.js *(archived)*
* [scala-exercises/exercises-stdlib](https://github.com/scala-exercises/exercises-stdlib) - Scala Exercises' lessons for the standard library
* [scala/scala-seed.g8](https://github.com/scala/scala-seed.g8) - Giter8 template for a simple hello world app in Scala.
* [gothinkster/scala-play-realworld-example-app](https://github.com/gothinkster/scala-play-realworld-example-app) - Exemplary real world application built with Scala 2.13 & Play *(archived)*
* [playframework/play-scala-isolated-slick-example](https://github.com/playframework/play-scala-isolated-slick-example) - Example Play Slick Project *(archived)*
* [retronym/macrocosm](https://github.com/retronym/macrocosm) - Exploration of Scala macros
* [vasnake/Principles-of-Reactive-Programming](https://github.com/vasnake/Principles-of-Reactive-Programming) - Principles of Reactive Programming, Scala: assignments and other code from Coursera https://class.coursera.org/reactive-002
* [prnicolas/ScalaMl](https://github.com/prnicolas/ScalaMl) - Project, source code and data files for 1st edition "Scala for Machine Learning"
* [underscoreio/essential-macros](https://github.com/underscoreio/essential-macros) - Examples of simple Scala Macros
* [yawaramin/scala-modules](https://github.com/yawaramin/scala-modules) - Experimental implementations of ML-style modules in Scala
* [crossroad0201/ddd-on-scala](https://github.com/crossroad0201/ddd-on-scala) - DDD sample implementation by Scala.
* [CodelyTV/scala-ddd-example](https://github.com/CodelyTV/scala-ddd-example) - λ🎯 Hexagonal Architecture + DDD + CQRS applied in Scala using Akka HTTP
* [xebia-functional/scala-android](https://github.com/xebia-functional/scala-android) - Scala on Android Examples
* [scalafx/scalafx-ensemble](https://github.com/scalafx/scalafx-ensemble) - scalafx ensemble
* [ashwinbhaskar/functional-way](https://github.com/ashwinbhaskar/functional-way) - Write small programs (eg -algorithms) in a functional way.
* [exercism/scala](https://github.com/exercism/scala) - Exercism exercises in Scala.
* [taoran92/SwordOffer](https://github.com/taoran92/SwordOffer) - :fire:剑指offer题解（Java & Scala实现）
* [hussachai/play-scalajs-showcase](https://github.com/hussachai/play-scalajs-showcase) - Play+Scala.js Showcase
* [GrahamLea/scala-spring-hibernate-maven-webapp](https://github.com/GrahamLea/scala-spring-hibernate-maven-webapp) - [ARCHIVED] Code for kickstarting a webapp using Scala + Spring + Hibernate + Maven + Selenium WebDriver PageObject Web Tests *(archived)*
* [kogecoo/dl4j-examples-scala](https://github.com/kogecoo/dl4j-examples-scala) - [NO LONGER MAINTAINED] a simple scala porting of https://github.com/deeplearning4j/dl4j-examples *(archived)*
* [loicdescotte/pureWebappSample](https://github.com/loicdescotte/pureWebappSample) - Minimal http4s + Doobie + ZIO + Circe Scala application to show how to build a purely functional web application in Scala.
* [Sergey80/scala-samples](https://github.com/Sergey80/scala-samples) - There are pieces of scala code that explain Scala syntax and related things - like what you can do with all this
* [MasseGuillaume/ScalaKata](https://github.com/MasseGuillaume/ScalaKata) - Moved
* [nraychaudhuri/scalainaction](https://github.com/nraychaudhuri/scalainaction) - Code examples from scala in action book
* [potigol/beecrowd](https://github.com/potigol/beecrowd) - 800+ Soluções de Problemas do Beecrowd usando a Linguagem Potigol
* [vmunier/akka-http-scalajs.g8](https://github.com/vmunier/akka-http-scalajs.g8) - Giter8 template to get started with Akka HTTP and Scala.js.
* [debasishg/frdomain-extras](https://github.com/debasishg/frdomain-extras) - Additional accompaniment to Functional and Reactive Domain Modeling
* [jsuereth/scala-in-depth-source](https://github.com/jsuereth/scala-in-depth-source) - The source code for the Scala In Depth book.
* [scala-exercises/exercises-cats](https://github.com/scala-exercises/exercises-cats) - Scala Exercises' lessons for the Cats library
* [fernandoracca/skeleton](https://github.com/fernandoracca/skeleton) - Simple Scala project template
* [lihaoyi/scala-js-games](https://github.com/lihaoyi/scala-js-games) - Some simple games ported to Scala-Js
* [hempalex/scala-impatient](https://github.com/hempalex/scala-impatient) - My solutions for "Scala for the Impatient" exercises
* [pbugnion/s4ds](https://github.com/pbugnion/s4ds) - Code samples for Scala for data science
* [scala/scala-module-dependency-sample](https://github.com/scala/scala-module-dependency-sample) - Depend on Scala modules like a pro *(archived)*
* [djspiewak/extreme-cleverness](https://github.com/djspiewak/extreme-cleverness) - A set of functional collections created, ported and modified for my tak at NE Scala 2011
* [tonyskn/coursera-scala](https://github.com/tonyskn/coursera-scala) - My solutions to Coursera's "Functional Programming in Scala"
* [AtomicScala/atomic-scala-examples](https://github.com/AtomicScala/atomic-scala-examples) - Examples from the book "Atomic Scala" 2nd Edition by Bruce Eckel & Dianne Marsh

## Language and Tooling

### Compilers and Interpreters

* [scala/scala](https://github.com/scala/scala) - Scala 2 compiler and standard library. Scala 2 bugs at https://github.com/scala/bug; Scala 3 at https://github.com/scala/scala3
* [scala/scala3](https://github.com/scala/scala3) - The Scala 3 compiler, also known as Dotty.
* [chipsalliance/chisel](https://github.com/chipsalliance/chisel) - Chisel: A Modern Hardware Design Language
* [scala-js/scala-js](https://github.com/scala-js/scala-js) - Scala.js, the Scala to JavaScript compiler
* [scala-native/scala-native](https://github.com/scala-native/scala-native) - Your favorite language gets closer to bare metal.
* [com-lihaoyi/Ammonite](https://github.com/com-lihaoyi/Ammonite) - Scala Scripting
* [SpinalHDL/SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) - Scala based HDL
* [twitter/rsc](https://github.com/twitter/rsc) - Experimental Scala compiler focused on compilation speed
* [lihaoyi/Metascala](https://github.com/lihaoyi/Metascala) - A JVM written in Scala
* [scalameta/scalameta](https://github.com/scalameta/scalameta) - Library to read, analyze, transform and generate Scala programs
* [oleg-py/better-monadic-for](https://github.com/oleg-py/better-monadic-for) - Desugaring scala `for` without implicit `withFilter`s
* [tek/splain](https://github.com/tek/splain) - better implicit errors for scala
* [scala/legacy-svn-scala](https://github.com/scala/legacy-svn-scala) - OBSOLETE, we're over there: *(archived)*
* [sbt/zinc](https://github.com/sbt/zinc) - Scala incremental compiler library, used by sbt and other build tools
* [databricks/sjsonnet](https://github.com/databricks/sjsonnet) - A Scala implementation of the Jsonnet configuration language, running on JVM, GraalVM, Scala Native and JavaScript.
* [softwaremill/scala-clippy](https://github.com/softwaremill/scala-clippy) - Good advice for Scala compiler errors *(archived)*
* [typesafehub/zinc](https://github.com/typesafehub/zinc) - ⛔️ [DEPRECATED] sbt's scala incremental compiler *(archived)*
* [potigol/potigol](https://github.com/potigol/potigol) - Linguagem Potigol - Linguagem de programação funcional moderna para iniciantes - A Functional Programming Language for Beginners
* [scala-ts/scala-ts](https://github.com/scala-ts/scala-ts) - :wrench: Scala datamodel transpiler
* [ghik/silencer](https://github.com/ghik/silencer) - Scala compiler plugin for warning suppression
* [fogus/baysick](https://github.com/fogus/baysick) - An embedded Insane-specific Language for Scala implementing the BASIC programming language
* [ScalablyTyped/Converter](https://github.com/ScalablyTyped/Converter) - Typescript to Scala.js converter
* [sjrd/scala-js-ts-importer](https://github.com/sjrd/scala-js-ts-importer) - TypeScript Importer for Scala.js
* [timowest/scalagen](https://github.com/timowest/scalagen) - Java to Scala transformation
* [nativelibs4java/Scalaxy](https://github.com/nativelibs4java/Scalaxy) - Compiler plugin goodies for Scala (continuation of non-OpenCL part of ScalaCL)
* [epfldata/squid](https://github.com/epfldata/squid) - Squid – type-safe metaprogramming and compilation framework for Scala
* [nau/jscala](https://github.com/nau/jscala) - Scala macro that produces JavaScript from Scala code.
* [japgolly/scala-graal](https://github.com/japgolly/scala-graal) - Make usage of Graal features easy and safe from Scala. Also features Scala-based React SSR.
* [gkossakowski/kentuckymule](https://github.com/gkossakowski/kentuckymule) - Limits of Scala typechecking speed
* [lihaoyi/Scalite](https://github.com/lihaoyi/Scalite) - An experimental whitespace-delimited syntax for the Scala programming language
* [camunda/feel-scala](https://github.com/camunda/feel-scala) - FEEL parser and interpreter written in Scala
* [eed3si9n/treehugger](https://github.com/eed3si9n/treehugger) - treehugger.scala is a library to code Scala programmatically.
* [scalacenter/macros](https://github.com/scalacenter/macros) - Archived - Scala Macros *(archived)*
* [guillaumebort/scasm](https://github.com/guillaumebort/scasm) - A a dynamic x86_64 assembler in Scala — Code for the live coding session @ Devoxx france 2016
* [polyvariant/better-tostring](https://github.com/polyvariant/better-tostring) - (b2s) Scala compiler plugin for a better default toString.
* [shadaj/scala-native-wasm](https://github.com/shadaj/scala-native-wasm) - Running Scala in WebAssembly through Scala Native
* [stephentu/scala-sql-parser](https://github.com/stephentu/scala-sql-parser) - SQL parser written using Scala's parser combinator library
* [magarciaEPFL/scaladotnet](https://github.com/magarciaEPFL/scaladotnet) - Scala SDK (compiler and standard library) for .NET
* [scalan/scalan](https://github.com/scalan/scalan) - Generic framework for development of domain-specific compilers in Scala
* [scala/scala-continuations](https://github.com/scala/scala-continuations) - the Scala delimited continuations plugin and library *(archived)*

### Build Systems

* [sbt/sbt](https://github.com/sbt/sbt) - sbt, the interactive build tool
* [com-lihaoyi/mill](https://github.com/com-lihaoyi/mill) - A better build tool for Java, Scala and Kotlin: Simpler than Maven, easier than Gradle, with 3-7x faster dev workflows than other JVM build tools
* [sbt/sbt-native-packager](https://github.com/sbt/sbt-native-packager) - sbt Native Packager
* [scalacenter/bloop](https://github.com/scalacenter/bloop) - Bloop is a build server and CLI tool to compile, test and run Scala fast from any editor or build tool.
* [spray/sbt-revolver](https://github.com/spray/sbt-revolver) - An SBT plugin for dangerously fast development turnaround in Scala
* [marcus-drake/sbt-docker](https://github.com/marcus-drake/sbt-docker) - Create Docker images directly from sbt
* [sbt/sbt-release](https://github.com/sbt/sbt-release) - A release plugin for sbt
* [VirtusLab/scala-cli](https://github.com/VirtusLab/scala-cli) - Scala CLI is a command-line tool to interact with the Scala language. It lets you compile, run, test, and package your Scala code (and more!)
* [build-server-protocol/build-server-protocol](https://github.com/build-server-protocol/build-server-protocol) - Protocol for IDEs and build tools to communicate about compile, run, test, debug and more.
* [xerial/sbt-pack](https://github.com/xerial/sbt-pack) - A sbt plugin for creating distributable Scala packages.
* [cvogt/cbt](https://github.com/cvogt/cbt) - CBT - fun, fast, intuitive, compositional, statically checked builds written in Scala
* [jberkel/android-plugin](https://github.com/jberkel/android-plugin) - An sbt plugin for Android development in Scala *(archived)*
* [propensive/fury-old](https://github.com/propensive/fury-old) - A new build tool for JVM languages
* [typelevel/sbt-tpolecat](https://github.com/typelevel/sbt-tpolecat) - scalac options for the enlightened
* [scalameta/sbt-native-image](https://github.com/scalameta/sbt-native-image) - Plugin to generate native-image binaries with sbt
* [portable-scala/sbt-crossproject](https://github.com/portable-scala/sbt-crossproject) - Cross-platform compilation support for sbt.
* [tindzk/seed](https://github.com/tindzk/seed) - Build tool for Scala projects
* [lihaoyi/workbench](https://github.com/lihaoyi/workbench) - Tooling around scala-js
* [sbt/sbt-fresh](https://github.com/sbt/sbt-fresh) - sbt-plugin to create an opinionated fresh sbt project
* [vmunier/sbt-web-scalajs](https://github.com/vmunier/sbt-web-scalajs) - SBT plugin to use Scala.js along with any sbt-web server.
* [sbt/sbt-header](https://github.com/sbt/sbt-header) - sbt-header is an sbt plugin for creating file headers, e.g. copyright headers
* [typelevel/sbt-typelevel](https://github.com/typelevel/sbt-typelevel) - Let sbt work for you.
* [oyvindberg/bleep](https://github.com/oyvindberg/bleep) - A bleeping fast scala build tool!
* [sbt/sbt-site](https://github.com/sbt/sbt-site) - Site generation for sbt
* [sbt/sbt-protobuf](https://github.com/sbt/sbt-protobuf) - sbt plugin for compiling protobuf files
* [sbt/sbt-jni](https://github.com/sbt/sbt-jni) - SBT Plugin to ease working with JNI
* [julianpeeters/sbt-avrohugger](https://github.com/julianpeeters/sbt-avrohugger) - sbt plugin for generating Scala sources for Apache Avro schemas and protocols.
* [sbt/sbt-unidoc](https://github.com/sbt/sbt-unidoc) - sbt plugin to create a unified Scaladoc or Javadoc API document across multiple subprojects.
* [kitlangton/zio-app](https://github.com/kitlangton/zio-app) - Quickly create and develop full-stack Scala apps with ZIO and Laminar.
* [davidB/scala-archetype-simple](https://github.com/davidB/scala-archetype-simple) - a simple maven archetype for project in scala *(archived)*
* [sbt/sbt-boilerplate](https://github.com/sbt/sbt-boilerplate) - sbt plugin for generating scala.Tuple/Function related boilerplate code
* [agemooij/sbt-prompt](https://github.com/agemooij/sbt-prompt) - An SBT plugin for making your SBT prompt more awesome
* [xuwei-k/sbt-class-diagram](https://github.com/xuwei-k/sbt-class-diagram) - sbt plugin to create a class diagram

### Package Management

* [coursier/coursier](https://github.com/coursier/coursier) - Pure Scala Artifact Fetching
* [sbt/sbt-dependency-graph](https://github.com/sbt/sbt-dependency-graph) - sbt plugin to create a dependency graph for your project *(archived)*
* [scala-steward-org/scala-steward](https://github.com/scala-steward-org/scala-steward) - :robot: A bot that helps you keep your projects up-to-date
* [rtimush/sbt-updates](https://github.com/rtimush/sbt-updates) - sbt plugin that can check Maven and Ivy repositories for dependency updates
* [foundweekends/conscript](https://github.com/foundweekends/conscript) - Scala at your command
* [xerial/sbt-sonatype](https://github.com/xerial/sbt-sonatype) - A sbt plugin for publishing Scala/Java projects to the Maven central.
* [scala/scala-dist](https://github.com/scala/scala-dist) - sbt project that packages the Scala 2 distribution
* [scalacenter/scaladex](https://github.com/scalacenter/scaladex) - The Scala Package Index
* [tpunder/fm-sbt-s3-resolver](https://github.com/tpunder/fm-sbt-s3-resolver) - SBT Plugin that adds support for resolving and publishing using Amazon S3
* [kitlangton/scala-update](https://github.com/kitlangton/scala-update) - Update your Scala dependencies interactively
* [ohnosequences/sbt-s3-resolver](https://github.com/ohnosequences/sbt-s3-resolver) - :cloud:Amazon S3-based resolver for sbt
* [jvican/sbt-release-early](https://github.com/jvican/sbt-release-early) - Opinionated sbt plugin to release your artifacts early, both on merge and via git tag.

### Linters and Formatters

* [scalameta/scalafmt](https://github.com/scalameta/scalafmt) - Code formatter for Scala
* [wartremover/wartremover](https://github.com/wartremover/wartremover) - Flexible Scala code linting tool
* [scalacenter/scalafix](https://github.com/scalacenter/scalafix) - Refactoring and linting tool for Scala
* [scalastyle/scalastyle](https://github.com/scalastyle/scalastyle) - scalastyle
* [scapegoat-scala/scapegoat](https://github.com/scapegoat-scala/scapegoat) - Scala compiler plugin for static code analysis
* [scala-ide/scalariform](https://github.com/scala-ide/scalariform) - Scala source code formatter
* [scala-garden/mima](https://github.com/scala-garden/mima) - A tool for catching binary incompatibility in Scala
* [riy/degraph](https://github.com/riy/degraph) - Test and Visualize and Manage Dependencies of classes and packages in JVM Byte Code (think Scala and Java)
* [HairyFotr/linter](https://github.com/HairyFotr/linter) - Static Analysis Compiler Plugin for Scala *(archived)*
* [sbt/sbt-scalariform](https://github.com/sbt/sbt-scalariform) - sbt plugin adding support for source code formatting using Scalariform
* [com-lihaoyi/acyclic](https://github.com/com-lihaoyi/acyclic) - Acyclic is a Scala compiler plugin to let you prohibit circular dependencies between files
* [scalameta/sbt-scalafmt](https://github.com/scalameta/sbt-scalafmt) - sbt plugin for Scalafmt
* [scala/scala-abide](https://github.com/scala/scala-abide) - obsolete; visit https://github.com/scalacenter/scalafix instead *(archived)*
* [liancheng/scalafix-organize-imports](https://github.com/liancheng/scalafix-organize-imports) - A CI-friendly Scalafix semantic rule for organizing imports *(archived)*
* [scapegoat-scala/sbt-scapegoat](https://github.com/scapegoat-scala/sbt-scapegoat) - sbt plugin for scapegoat scala static analysis plugin
* [lucidsoftware/neo-sbt-scalafmt](https://github.com/lucidsoftware/neo-sbt-scalafmt) - Scalafmt SBT plugin
* [mikeyhu/scaladiagrams](https://github.com/mikeyhu/scaladiagrams) - Generate class diagrams from scala source code
* [scalastyle/scalastyle-sbt-plugin](https://github.com/scalastyle/scalastyle-sbt-plugin) - scalastyle-sbt-plugin
* [scalacenter/sbt-scalafix](https://github.com/scalacenter/sbt-scalafix) - sbt plugin for Scalafix
* [scala-garden/scala-sculpt](https://github.com/scala-garden/scala-sculpt) - Dependency extraction for Scala 2 codebases, to aid in modularizing
* [sonar-scala/sonar-scala](https://github.com/sonar-scala/sonar-scala) - A free and open-source SonarQube plugin for static code analysis of Scala projects. *(archived)*
* [codacy/codacy-analysis-cli](https://github.com/codacy/codacy-analysis-cli) - The Codacy Analysis CLI is a command line interface that enables you to execute Codacy code analysis locally.
* [scalacenter/scala3-migrate](https://github.com/scalacenter/scala3-migrate) - A tool to help migrating from Scala 2 to Scala 3
* [rorygraves/ScalaClean](https://github.com/rorygraves/ScalaClean) - Full program static analysis for Scala

### Editor and IDE Support

* [scalameta/metals](https://github.com/scalameta/metals) - Scala language server with rich IDE features 🚀
* [JetBrains/intellij-scala](https://github.com/JetBrains/intellij-scala) - Scala plugin for IntelliJ IDEA
* [scala-ide/scala-ide](https://github.com/scala-ide/scala-ide) - Scala IDE for Eclipse
* [psliwa/idea-composer-plugin](https://github.com/psliwa/idea-composer-plugin) - PhpStorm plugin that adds code completion in composer.json file
* [zio/zio-intellij](https://github.com/zio/zio-intellij) - A companion IntelliJ IDEA plugin for the ZIO library ecosystem.
* [harrah/browse](https://github.com/harrah/browse) - A Scala source code browser
* [scalameta/metabrowse](https://github.com/scalameta/metabrowse) - Static site generator for code search with IDE features for Scala
* [scala-ide/scala-ide-play2](https://github.com/scala-ide/scala-ide-play2) - Play 2 support for Scala IDE
* [scalafiddle/scalafiddle-editor](https://github.com/scalafiddle/scalafiddle-editor) - Web user interface for ScalaFiddle
* [scala-ide/scala-worksheet](https://github.com/scala-ide/scala-worksheet) - A Scala IDE plugin for a multi-line REPL (called worksheet)
* [JetBrains/intellij-scala-bundle](https://github.com/JetBrains/intellij-scala-bundle) - IntelliJ Scala Bundle - get started with Scala in a single click!

## Web

### Web Frameworks

* [playframework/playframework](https://github.com/playframework/playframework) - The Community Maintained High Velocity Web Framework For Java and Scala.
* [scalatra/scalatra](https://github.com/scalatra/scalatra) - Tiny Scala high-performance, async web framework, inspired by Sinatra
* [http4s/http4s](https://github.com/http4s/http4s) - A minimal, idiomatic Scala interface for HTTP
* [lagom/lagom](https://github.com/lagom/lagom) - Reactive Microservices for the JVM
* [spray/spray](https://github.com/spray/spray) - A suite of scala libraries for building and consuming RESTful web services on top of Akka: lightweight, asynchronous, non-blocking, actor-based, testable *(archived)*
* [twitter/finatra](https://github.com/twitter/finatra) - Fast, testable, Scala services built on TwitterServer and Finagle
* [finagle/finch](https://github.com/finagle/finch) - Scala combinator library for building Finagle HTTP services
* [lift/framework](https://github.com/lift/framework) - Lift Framework
* [tumblr/colossus](https://github.com/tumblr/colossus) - I/O and Microservice library for Scala
* [zio/zio-http](https://github.com/zio/zio-http) - A next-generation Scala framework for building scalable, correct, and efficient HTTP clients and servers
* [jdegoes/blueeyes](https://github.com/jdegoes/blueeyes) - A lightweight Web 3.0 framework for Scala, featuring a purely asynchronous architecture, extremely high-performance, massive scalability, high usability, and a functional, composable design.
* [skinny-framework/skinny-framework](https://github.com/skinny-framework/skinny-framework) - :monorail: "Scala on Rails" - A full-stack web app framework for rapid development in Scala
* [unfiltered/unfiltered](https://github.com/unfiltered/unfiltered) - A toolkit for servicing HTTP requests in Scala
* [com-lihaoyi/cask](https://github.com/com-lihaoyi/cask) - Cask: a Scala HTTP micro-framework. Cask makes it easy to set up a website, backend server, or REST API using Scala
* [fomkin/korolev](https://github.com/fomkin/korolev) - Single Page Applications running on the server side. *(archived)*
* [UdashFramework/udash-core](https://github.com/UdashFramework/udash-core) - Scala framework for building beautiful and maintainable web applications.
* [xitrum-framework/xitrum](https://github.com/xitrum-framework/xitrum) - Async and clustered Scala web framework and HTTP(S) server
* [brikis98/ping-play](https://github.com/brikis98/ping-play) - BigPipe streaming for the Play Framework
* [d2iq-archive/chaos](https://github.com/d2iq-archive/chaos) - A lightweight framework for writing REST services in Scala. *(archived)*
* [outr/youi](https://github.com/outr/youi) - Next generation user interface and application development in Scala and Scala.js for web, mobile, and desktop.
* [mDialog/smoke](https://github.com/mDialog/smoke) - Simple, asynchronous HTTP using Scala. *(archived)*
* [inca/circumflex](https://github.com/inca/circumflex) - [UNMAINTAINED] Circumflex — lightweight Scala-based Web application framework and ORM *(archived)*
* [Kanaka-io/play-monadic-actions](https://github.com/Kanaka-io/play-monadic-actions) - A simple scala DSL to allow clean and monadic style for Play! Actions
* [reactiverse/vertx-lang-scala](https://github.com/reactiverse/vertx-lang-scala) - Vert.x for Scala
* [bowler-framework/Bowler](https://github.com/bowler-framework/Bowler) - RESTful Web Framework based on Scala, built on top of Scalatra & Scalate
* [daviddenton/fintrospect](https://github.com/daviddenton/fintrospect) - Implement fast, type-safe HTTP webservices for Finagle

### HTTP and Networking Clients

* [softwaremill/sttp](https://github.com/softwaremill/sttp) - The Scala HTTP client you always wanted!
* [scalaj/scalaj-http](https://github.com/scalaj/scalaj-http) - Simple scala wrapper for HttpURLConnection. OAuth included. *(archived)*
* [com-lihaoyi/requests-scala](https://github.com/com-lihaoyi/requests-scala) - A Scala port of the popular Python Requests HTTP client: flexible, intuitive, and straightforward to use.
* [dispatch/reboot](https://github.com/dispatch/reboot) - Scala wrapper for the Java AsyncHttpClient.
* [dispatch/classic](https://github.com/dispatch/classic) - [UNSUPPORTED] Dispatch Classic. See dispatch/reboot for the modern Dispatch for Scala 2.11/2.12 *(archived)*
* [DanielaSfregola/twitter4s](https://github.com/DanielaSfregola/twitter4s) - An asynchronous non-blocking Scala client for both the Twitter Rest and Streaming API *(archived)*
* [47degrees/github4s](https://github.com/47degrees/github4s) - A GitHub API wrapper written in Scala
* [playframework/play-ws](https://github.com/playframework/play-ws) - Standalone Play WS, an async HTTP client with fluent API
* [slack-scala-client/slack-scala-client](https://github.com/slack-scala-client/slack-scala-client) - A scala library for interacting with the slack api and real time messaging interface
* [pepegar/hammock](https://github.com/pepegar/hammock) - Purely functional HTTP client
* [finagle/featherbed](https://github.com/finagle/featherbed) - Asynchronous Scala HTTP client using Finagle, Shapeless and Cats
* [eed3si9n/gigahorse](https://github.com/eed3si9n/gigahorse) - Gigahorse is an HTTP client for Scala with multiple backend support.
* [hmil/RosHTTP](https://github.com/hmil/RosHTTP) - Unified Scala.js + Scala HTTP client API

### API and GraphQL

* [sangria-graphql/sangria](https://github.com/sangria-graphql/sangria) - Scala GraphQL implementation
* [softwaremill/tapir](https://github.com/softwaremill/tapir) - Rapid development of self-documenting APIs
* [ghostdogpr/caliban](https://github.com/ghostdogpr/caliban) - Functional GraphQL library for Scala
* [guardrail-dev/guardrail](https://github.com/guardrail-dev/guardrail) - Principled code generation from OpenAPI specifications
* [endpoints4s/endpoints4s](https://github.com/endpoints4s/endpoints4s) - Describe HTTP endpoints in Scala and derive clients, servers, and documentation
* [iheartradio/play-swagger](https://github.com/iheartradio/play-swagger) - Swagger spec generator for play framework
* [disneystreaming/smithy4s](https://github.com/disneystreaming/smithy4s) - https://disneystreaming.github.io/smithy4s/
* [swagger-akka-http/swagger-akka-http](https://github.com/swagger-akka-http/swagger-akka-http) - Support for generating Swagger REST API documentation for Akka-Http based services.
* [RazorSh4rk/random-word-api](https://github.com/RazorSh4rk/random-word-api) - Simple scala rest api that serves random words
* [pathikrit/metarest](https://github.com/pathikrit/metarest) - Scala macros to generate RESTful Models
* [pheymann/typedapi](https://github.com/pheymann/typedapi) - Build your web API on the type level.
* [tofu-tf/typed-schema](https://github.com/tofu-tf/typed-schema) - Typelevel http service definition DSL *(archived)*
* [ebowman/api-first-hand](https://github.com/ebowman/api-first-hand) - API-First bootstrapping tool for building RESTful web services from a Swagger/OpenAPI spec
* [swagger-api/swagger-scala-module](https://github.com/swagger-api/swagger-scala-module) - Swagger support for scala *(archived)*
* [Tinkoff/typed-schema](https://github.com/Tinkoff/typed-schema) - Typelevel http service definition DSL *(archived)*

### Frontend and UI Components

* [japgolly/scalajs-react](https://github.com/japgolly/scalajs-react) - Facebook's React on Scala.JS
* [ThoughtWorksInc/Binding.scala](https://github.com/ThoughtWorksInc/Binding.scala) - Reactive data-binding for Scala
* [raquo/Laminar](https://github.com/raquo/Laminar) - Simple, expressive, and safe UI library for Scala.js
* [shadaj/slinky](https://github.com/shadaj/slinky) - Write Scala.js React apps just like you would in ES6
* [suzaku-io/diode](https://github.com/suzaku-io/diode) - Scala library for managing immutable application model
* [outwatch/outwatch](https://github.com/outwatch/outwatch) - The Functional and Reactive Web-Frontend Library for Scala.js
* [PurpleKingdomGames/tyrian](https://github.com/PurpleKingdomGames/tyrian) - Elm-inspired Scala UI library. *(archived)*
* [japgolly/scalacss](https://github.com/japgolly/scalacss) - Super type-safe CSS for Scala and Scala.JS.
* [scala-js/scala-js-dom](https://github.com/scala-js/scala-js-dom) - Statically typed DOM API for Scala.js
* [softwaremill/supler](https://github.com/softwaremill/supler) - Rapid Form Development library. Use your favourite JS frontend & Scala backend frameworks. *(archived)*
* [raquo/Airstream](https://github.com/raquo/Airstream) - State propagation and event streams with mandatory ownership and no glitches
* [greencatsoft/scalajs-angular](https://github.com/greencatsoft/scalajs-angular) - AngularJS Binding for Scala.js *(archived)*
* [OlivierBlanvillain/monadic-html](https://github.com/OlivierBlanvillain/monadic-html) - Tiny DOM binding library for Scala.js
* [chandu0101/scalajs-react-components](https://github.com/chandu0101/scalajs-react-components) - Reusable scalajs-react components
* [armanbilge/calico](https://github.com/armanbilge/calico) - Pure, reactive UI library for Scala.js
* [widok/widok](https://github.com/widok/widok) - Reactive web framework for the JVM and Scala.js
* [xored/scala-js-react](https://github.com/xored/scala-js-react) - ScalaJS interface for Facebook React
* [Ahnfelt/react4s](https://github.com/Ahnfelt/react4s) - Production ready React wrapper for Scala.js - composable lifecycle - no memoization, no macros, no implicits.
* [henrikerola/scaladin](https://github.com/henrikerola/scaladin) - Scala API for Vaadin Framework
* [julienrf/scalm](https://github.com/julienrf/scalm) - Elm-inspired Scala library for writing web user interfaces
* [fancellu/scalajs-vue](https://github.com/fancellu/scalajs-vue) - Scala.js bindings for Vue.js and an example application
* [suzaku-io/suzaku](https://github.com/suzaku-io/suzaku) - Suzaku web UI framework for Scala
* [spaced/scala-js-d3](https://github.com/spaced/scala-js-d3) - d3 facade types for Scala.js *(archived)*

### Web Servers and Proxies

* [MAIF/otoroshi](https://github.com/MAIF/otoroshi) - Lightweight api management on top of a modern http reverse proxy
* [mashupbots/socko](https://github.com/mashupbots/socko) - A Scala web server powered by Netty networking and AKKA processing.
* [lichess-org/lila-ws](https://github.com/lichess-org/lila-ws) - Lichess' websocket server
* [spray/spray-can](https://github.com/spray/spray-can) - A low-overhead, high-performance, fully async HTTP 1.1 server and client library implemented entirely in Scala on top of Akka
* [lolgab/snunit](https://github.com/lolgab/snunit) - Scala Native HTTP server based on FreeUnit
* [Spinoco/fs2-http](https://github.com/Spinoco/fs2-http) - Http Server and client using fs2
* [polynote/uzhttp](https://github.com/polynote/uzhttp) - Minimal HTTP server for Scala+ZIO
* [criteo/lolhttp](https://github.com/criteo/lolhttp) - An HTTP Server and Client library for Scala.

## Data and Storage

### Databases

* [filodb/FiloDB](https://github.com/filodb/FiloDB) - Distributed Prometheus time series database
* [apache/carbondata](https://github.com/apache/carbondata) - High performance data store solution
* [thatdot/quine](https://github.com/thatdot/quine) - Quine • the streaming graph • https://quine.io • Discord: https://discord.gg/GMhd8TE4MR
* [opencypher/morpheus](https://github.com/opencypher/morpheus) - Morpheus brings the leading graph query language, Cypher, onto the leading distributed processing platform, Spark.
* [BlueBrain/nexus](https://github.com/BlueBrain/nexus) - Blue Brain Nexus - A knowledge graph for data-driven science
* [simerplaha/SwayDB](https://github.com/simerplaha/SwayDB) - Persistent and in-memory key-value storage engine for JVM that scales on a single machine.
* [justin-db/JustinDB](https://github.com/justin-db/JustinDB) - ⚛️ JustinDB is a highly available globally distributed key-value data store.

### Database Clients and ORMs

* [slick/slick](https://github.com/slick/slick) - Slick (Scala Language Integrated Connection Kit) is a modern database query and access library for Scala
* [typelevel/doobie](https://github.com/typelevel/doobie) - Functional JDBC layer for Scala.
* [zio/zio-quill](https://github.com/zio/zio-quill) - Compile-time Language Integrated Queries for Scala
* [apache/cassandra-spark-connector](https://github.com/apache/cassandra-spark-connector) - Apache Spark to Apache Cassandra connector
* [typelevel/skunk](https://github.com/typelevel/skunk) - A data access library for Scala + Postgres.
* [Philippus/elastic4s](https://github.com/Philippus/elastic4s) - 🔍 Elasticsearch Scala Client - Reactive, Non Blocking, Type Safe, HTTP Client
* [mauricio/postgresql-async](https://github.com/mauricio/postgresql-async) - Async, Netty based, database drivers for PostgreSQL and MySQL written in Scala *(archived)*
* [scalikejdbc/scalikejdbc](https://github.com/scalikejdbc/scalikejdbc) - A tidy SQL-based DB access library for Scala developers. This library naturally wraps JDBC APIs and provides you easy-to-use APIs.
* [outworkers/phantom](https://github.com/outworkers/phantom) - Schema safe, type-safe, reactive Scala driver for Cassandra/Datastax Enterprise
* [ReactiveMongo/ReactiveMongo](https://github.com/ReactiveMongo/ReactiveMongo) - :leaves: Non-blocking, Reactive MongoDB Driver for Scala
* [tminglei/slick-pg](https://github.com/tminglei/slick-pg) - Slick extensions for PostgreSQL
* [playframework/play-slick](https://github.com/playframework/play-slick) - Slick Plugin for Play
* [etaty/rediscala](https://github.com/etaty/rediscala) - Non-blocking, Reactive Redis driver for Scala (with Sentinel support)
* [squeryl/squeryl](https://github.com/squeryl/squeryl) - A Scala DSL for talking with databases with minimum verbosity and maximum type safety
* [mpollmeier/gremlin-scala](https://github.com/mpollmeier/gremlin-scala) - [unmaintained] Scala wrapper for Apache TinkerPop 3 Graph DSL
* [ReactiveMongo/Play-ReactiveMongo](https://github.com/ReactiveMongo/Play-ReactiveMongo) - :leaves: ReactiveMongo plugin for Playframework
* [profunktor/redis4cats](https://github.com/profunktor/redis4cats) - :bookmark: Redis client built on top of Cats Effect, Fs2 and Lettuce
* [aselab/scala-activerecord](https://github.com/aselab/scala-activerecord) - ActiveRecord-like ORM library for Scala
* [scanamo/scanamo](https://github.com/scanamo/scanamo) - Simpler DynamoDB access for Scala
* [scalikejdbc/scalikejdbc-async](https://github.com/scalikejdbc/scalikejdbc-async) - ScalikeJDBC Extension: Non-blocking APIs in the JDBC way
* [akka/akka-persistence-jdbc](https://github.com/akka/akka-persistence-jdbc) - Asynchronously writes journal and snapshot entries to configured JDBC databases so that Akka Actors can recover state
* [fwbrasil/activate](https://github.com/fwbrasil/activate) - Abandoned: Pluggable persistence in Scala
* [jonifreeman/sqltyped](https://github.com/jonifreeman/sqltyped) - Embedding SQL as an external DSL into Scala
* [AugustNagro/magnum](https://github.com/AugustNagro/magnum) - A 'new look' for database access in Scala
* [mongodb/mongo-scala-driver](https://github.com/mongodb/mongo-scala-driver) - Former repository of MongoDB Scala driver. Official Scala driver can now be found here: https://github.com/mongodb/mongo-java-driver *(archived)*
* [hbase-rdd/hbase-rdd](https://github.com/hbase-rdd/hbase-rdd) - Spark RDD to read, write and delete from HBase
* [com-lihaoyi/scalasql](https://github.com/com-lihaoyi/scalasql) - Scala ORM to query SQL databases from Scala via concise, type-safe, and familiar case classes and collection operations. Connects to Postgres, MySql, H2, and Sqlite out of the box
* [playframework/anorm](https://github.com/playframework/anorm) - The Anorm database library
* [twitter-archive/cassie](https://github.com/twitter-archive/cassie) - A Scala client for Cassandra *(archived)*
* [sorm/sorm](https://github.com/sorm/sorm) - A functional boilerplate-free Scala ORM *(archived)*
* [zio-archive/zio-sql](https://github.com/zio-archive/zio-sql) - Type-safe, composable SQL for ZIO applications *(archived)*
* [zio/zio-protoquill](https://github.com/zio/zio-protoquill) - Quill for Scala 3
* [FaKod/neo4j-scala](https://github.com/FaKod/neo4j-scala) - Scala wrapper for Neo4j Graph Database
* [debasishg/scala-redis-nb](https://github.com/debasishg/scala-redis-nb) - Implementation of a non blocking Redis client in Scala using Akka IO
* [lastland/scala-forklift](https://github.com/lastland/scala-forklift) - Type-safe data migration tool for Slick, Git and beyond.
* [neotypes/neotypes](https://github.com/neotypes/neotypes) - Scala lightweight, type-safe, asynchronous driver for neo4j
* [lucidsoftware/relate](https://github.com/lucidsoftware/relate) - Performant database access in Scala
* [underscoreio/slickless](https://github.com/underscoreio/slickless) - Support for shapeless HLists/Generics in Slick.
* [gaelrenoux/tranzactio](https://github.com/gaelrenoux/tranzactio) - ZIO wrapper around Doobie and Anorm.
* [mybatis/scala](https://github.com/mybatis/scala) - The Scala version of MyBatis SQL Mapper
* [Livestream/scredis](https://github.com/Livestream/scredis) - Non-blocking, ultra-fast Scala Redis client built on top of Akka IO, used in production at Livestream
* [bwmcadams/hammersmith](https://github.com/bwmcadams/hammersmith) - Pure asynchronous MongoDB Driver for Scala.
* [schemasafe/troy](https://github.com/schemasafe/troy) - Type-safe and Schema-safe Scala wrapper for Cassandra driver
* [acrosa/scala-redis](https://github.com/acrosa/scala-redis) - A scala library for connecting to a redis server, or a cluster of redis nodes using consistent hashing on the client side.
* [scredis/scredis](https://github.com/scredis/scredis) - Non-blocking, ultra-fast Scala Redis client built on top of Akka IO.
* [sbt/flyway-sbt](https://github.com/sbt/flyway-sbt) - An sbt plugin for Flyway database migration
* [dwhjames/datomisca](https://github.com/dwhjames/datomisca) - Datomisca: a Scala API for Datomic
* [GravityLabs/HPaste](https://github.com/GravityLabs/HPaste) - HBase DSL for Scala with MapReduce support *(archived)*
* [AnormCypher/AnormCypher](https://github.com/AnormCypher/AnormCypher) - Neo4j Scala library based on Anorm in the Play Framework
* [Kirill5k/mongo4cats](https://github.com/Kirill5k/mongo4cats) - MongoDB Java client wrapper for Cats Effect & FS2 and ZIO
* [nafg/slick-migration-api](https://github.com/nafg/slick-migration-api) - Schema manipulation dialects and DSL for Slick
* [paulgoldbaum/scala-influxdb-client](https://github.com/paulgoldbaum/scala-influxdb-client) - Asynchronous InfluxDB client for Scala
* [gonmarques/slick-repo](https://github.com/gonmarques/slick-repo) - CRUD Repositories for Slick based persistence Scala projects.
* [crobox/clickhouse-scala-client](https://github.com/crobox/clickhouse-scala-client) - Clickhouse Scala Client with Reactive Streams support
* [ing-bank/scruid](https://github.com/ing-bank/scruid) - Scala + Druid: Scruid. A library that allows you to compose queries in Scala, and parse the result back into typesafe classes.
* [okumin/akka-persistence-sql-async](https://github.com/okumin/akka-persistence-sql-async) - A journal and snapshot store plugin for akka-persistence using RDBMS.
* [gideondk/Raiku](https://github.com/gideondk/Raiku) - A non-blocking - Akka IO driven - Riak client for Scala with a cute DSL
* [typr-dev/typr](https://github.com/typr-dev/typr) - Seal Your System's Boundaries
* [outworkers/morpheus](https://github.com/outworkers/morpheus) - Reactive type-safe Scala driver for SQL databases
* [longevityframework/longevity](https://github.com/longevityframework/longevity) - A Persistence Framework for Scala and NoSQL
* [krasserm/akka-stream-eventsourcing](https://github.com/krasserm/akka-stream-eventsourcing) - Event sourcing for Akka Streams
* [lendup/fs2-blobstore](https://github.com/lendup/fs2-blobstore) - Minimal, idiomatic, stream-based Scala interface for key/value store implementations

### Serialization and Formats

* [circe/circe](https://github.com/circe/circe) - Yet another JSON library for Scala
* [json4s/json4s](https://github.com/json4s/json4s) - JSON library
* [scalapb/ScalaPB](https://github.com/scalapb/ScalaPB) - Protocol buffer compiler for Scala.
* [spray/spray-json](https://github.com/spray/spray-json) - A lightweight, clean and simple JSON implementation in Scala
* [scala/pickling](https://github.com/scala/pickling) - Fast, customizable, boilerplate-free pickling support for Scala *(archived)*
* [plokhotnyuk/jsoniter-scala](https://github.com/plokhotnyuk/jsoniter-scala) - Scala macros for compile-time generation of safe and ultra-fast JSON codecs + circe booster
* [scodec/scodec](https://github.com/scodec/scodec) - Scala combinator library for working with binary data
* [com-lihaoyi/upickle](https://github.com/com-lihaoyi/upickle) - uPickle: a simple, fast, dependency-free JSON & Binary (MessagePack) serialization library for Scala
* [sksamuel/avro4s](https://github.com/sksamuel/avro4s) - Avro schema generation and serialization / deserialization for Scala
* [tototoshi/scala-csv](https://github.com/tototoshi/scala-csv) - CSV Reader/Writer for Scala
* [kaitai-io/kaitai_struct_compiler](https://github.com/kaitai-io/kaitai_struct_compiler) - Kaitai Struct: compiler to translate .ksy => .cpp / .cs / .dot / .go / .java / .js / .lua / .nim / .php / .pm / .py / .rb / .rs
* [twitter/chill](https://github.com/twitter/chill) - Scala extensions for the Kryo serialization library
* [hseeberger/akka-http-json](https://github.com/hseeberger/akka-http-json) - Integrate some of the best JSON libs in Scala with Akka HTTP *(archived)*
* [argonaut-io/argonaut](https://github.com/argonaut-io/argonaut) - Purely functional JSON parser and library in scala.
* [nightscape/spark-excel](https://github.com/nightscape/spark-excel) - A Spark plugin for reading and writing Excel files
* [FasterXML/jackson-module-scala](https://github.com/FasterXML/jackson-module-scala) - Add-on module for Jackson (https://github.com/FasterXML/jackson) to support Scala-specific datatypes
* [typelevel/jawn](https://github.com/typelevel/jawn) - Jawn is for parsing jay-sawn (JSON)
* [zio/zio-json](https://github.com/zio/zio-json) - Fast, secure JSON library with tight ZIO integration.
* [playframework/play-json](https://github.com/playframework/play-json) - The Play JSON library
* [nrinaudo/kantan.csv](https://github.com/nrinaudo/kantan.csv) - CSV handling library for Scala
* [eed3si9n/scalaxb](https://github.com/eed3si9n/scalaxb) - scalaxb is an XML data binding tool for Scala.
* [gnieh/diffson](https://github.com/gnieh/diffson) - A scala diff/patch library for Json
* [scala/scala-xml](https://github.com/scala/scala-xml) - The standard Scala XML library
* [mjakubowski84/parquet4s](https://github.com/mjakubowski84/parquet4s) - Read and write Parquet in Scala. Use Scala classes as schema. No need to start a cluster.
* [codahale/jerkson](https://github.com/codahale/jerkson) - [ABANDONED] The Scala applewood bacon to Jackson's chicken breast: JSON cordon bleu. *(archived)*
* [jrudolph/json-lenses](https://github.com/jrudolph/json-lenses) - A library to query and update JSON data in Scala.
* [sirthias/borer](https://github.com/sirthias/borer) - Efficient CBOR and JSON (de)serialization in Scala
* [altoo-ag/akka-kryo-serialization](https://github.com/altoo-ag/akka-kryo-serialization) - Kryo-based serialization for Akka
* [debasishg/sjson](https://github.com/debasishg/sjson) - Scala Json with capabilities for Scala Object Serialization
* [SandroGrzicic/ScalaBuff](https://github.com/SandroGrzicic/ScalaBuff) - the scala protocol buffers (protobuf) compiler
* [julianpeeters/avrohugger](https://github.com/julianpeeters/avrohugger) - Generate Scala case class definitions from Avro schemas
* [jto/validation](https://github.com/jto/validation) - validation api extracted from play *(archived)*
* [stevej/scala-json](https://github.com/stevej/scala-json) - Scala JSON toolkit. Originally from the Odersky "Stairway" Book, tightened up and tests added by Twitter, Inc.
* [jvican/dijon](https://github.com/jvican/dijon) - A Dynamically Typed Scala Json Library
* [norbert-radyk/spoiwo](https://github.com/norbert-radyk/spoiwo) - Scala POI Wrapper for the spreadsheet generation in Excel:
* [spotify/magnolify](https://github.com/spotify/magnolify) - A collection of Magnolia add-on modules
* [folone/poi.scala](https://github.com/folone/poi.scala) - Scala library for creating and manipulating Excel documents
* [sentenza/PureCSV](https://github.com/sentenza/PureCSV) - A type-safe and boilerplate-free CSV library for Scala
* [djspiewak/anti-xml](https://github.com/djspiewak/anti-xml) - The scala.xml library has some very annoying issues. Time for a clean-room replacement! *(archived)*
* [gnieh/fs2-data](https://github.com/gnieh/fs2-data) - streaming data parsing and transformation library
* [zio/zio-schema](https://github.com/zio/zio-schema) - Compositional, type-safe schema definitions, which enable auto-derivation of codecs and migrations.
* [zio/zio-blocks](https://github.com/zio/zio-blocks) - Powerful, joyful building blocks for modern cloud-native applications.
* [andyglow/scala-jsonschema](https://github.com/andyglow/scala-jsonschema) - Scala JSON Schema
* [circe/circe-derivation](https://github.com/circe/circe-derivation) - Fast type class instance derivation for Circe
* [tethys-json/tethys](https://github.com/tethys-json/tethys) - AST free JSON library for Scala
* [gzoller/ScalaJack](https://github.com/gzoller/ScalaJack) - Fast JSON parser/generator for Scala
* [nuttycom/xenomorph](https://github.com/nuttycom/xenomorph) - Scala library for free applicative schemas capable of parsing/rendering sums-of-products data structures.
* [scala-jsonapi/scala-jsonapi](https://github.com/scala-jsonapi/scala-jsonapi) - Scala support library for integrating the JSON API spec with Spray, Play! or Circe
* [jcazevedo/moultingyaml](https://github.com/jcazevedo/moultingyaml) - Scala wrapper for SnakeYAML
* [btlines/pbdirect](https://github.com/btlines/pbdirect) - Read/Write Scala objects directly to Protobuf with no .proto file definitions

### Caching and Queues

* [softwaremill/elasticmq](https://github.com/softwaremill/elasticmq) - In-memory message queue with an Amazon SQS-compatible interface. Runs stand-alone or embedded.
* [akka/alpakka-kafka](https://github.com/akka/alpakka-kafka) - Alpakka Kafka connector - Alpakka is a Reactive Enterprise Integration library for Java and Scala, based on Reactive Streams and Akka.
* [akka/alpakka](https://github.com/akka/alpakka) - Alpakka is a Reactive Enterprise Integration library for Java and Scala, based on Reactive Streams and Akka.
* [cb372/scalacache](https://github.com/cb372/scalacache) - Simple caching in Scala
* [cakesolutions/scala-kafka-client](https://github.com/cakesolutions/scala-kafka-client) - Scala helper modules for operating the Apache Kafka client library (0.9.x - 2.1.0)
* [softwaremill/kmq](https://github.com/softwaremill/kmq) - Kafka-based message queue
* [elodina/scala-kafka](https://github.com/elodina/scala-kafka) - Quick up and running using Scala for Apache Kafka
* [typelevel/fs2-kafka](https://github.com/typelevel/fs2-kafka) - Functional Kafka Streams for Scala
* [blemale/scaffeine](https://github.com/blemale/scaffeine) - Thin Scala wrapper for Caffeine (https://github.com/ben-manes/caffeine)
* [CleverCloud/pulsar4s](https://github.com/CleverCloud/pulsar4s) - Idiomatic, typesafe, and reactive Scala client for Apache Pulsar
* [SpinGo/op-rabbit](https://github.com/SpinGo/op-rabbit) - The Opinionated RabbitMQ Library for Scala and Akka
* [ShellRechargeSolutionsEU/akka-rabbitmq](https://github.com/ShellRechargeSolutionsEU/akka-rabbitmq) - RabbitMq client in Scala and Akka actors *(archived)*
* [lightbend/kafka-streams-scala](https://github.com/lightbend/kafka-streams-scala) - Thin Scala wrapper around Kafka Streams Java API *(archived)*
* [KarelCemus/play-redis](https://github.com/KarelCemus/play-redis) - Play framework 2 cache plugin as an adapter to redis-server
* [sstone/amqp-client](https://github.com/sstone/amqp-client) - [THIS PROJECT HAS BEEN ARCHIVED AND IS NO LONGER MAINTAINED] Simple fault-tolerant AMQP client written in Scala and based on Akka and the RabbitMQ java client *(archived)*
* [zio/zio-query](https://github.com/zio/zio-query) - Add efficient pipelining, batching, and caching to any data source
* [mmolimar/kukulcan](https://github.com/mmolimar/kukulcan) - A REPL for Apache Kafka
* [evolution-gaming/kafka-journal](https://github.com/evolution-gaming/kafka-journal) - Event sourcing journal implementation using Kafka as main storage
* [monix/shade](https://github.com/monix/shade) - Memcached client for Scala

### Search and Indexing

* [harana/search](https://github.com/harana/search) - Search everything, instantly.
* [plokhotnyuk/rtree2d](https://github.com/plokhotnyuk/rtree2d) - RTree2D is a 2D immutable R-tree for ultra-fast nearest and intersection queries in plane and spherical coordinates
* [meetuparchive/archery](https://github.com/meetuparchive/archery) - 2D R-Tree implementation in Scala *(archived)*
* [inoio/solrs](https://github.com/inoio/solrs) - An async, non-blocking solr client for java/scala, providing a query interface like SolrJ
* [gphat/wabisabi](https://github.com/gphat/wabisabi) - Scala Asynchronous ElasticSearch HTTP Client *(archived)*
* [ornicar/scalex](https://github.com/ornicar/scalex) - [abandoned] Hoogle-like documentation search engine, for scala

## Machine Learning and AI

### Machine Learning Frameworks

* [apache/predictionio](https://github.com/apache/predictionio) - PredictionIO, a machine learning server for developers and ML engineers. *(archived)*
* [microsoft/SynapseML](https://github.com/microsoft/SynapseML) - Simple and Distributed Machine Learning Python Library porting ML algorithms for Spark
* [metarank/metarank](https://github.com/metarank/metarank) - A low code Machine Learning personalized ranking service for articles, listings, search results, recommendations that boosts user engagement. A friendly Learn-to-Rank engine
* [salesforce/TransmogrifAI](https://github.com/salesforce/TransmogrifAI) - TransmogrifAI (pronounced trăns-mŏgˈrə-fī) is an AutoML library for building modular, reusable, strongly typed machine learning workflows on Apache Spark with minimal hand-tuning
* [combust/mleap](https://github.com/combust/mleap) - MLeap: Deploy ML Pipelines to Production
* [h2oai/sparkling-water](https://github.com/h2oai/sparkling-water) - Sparkling Water provides H2O functionality inside Spark cluster
* [eaplatanios/tensorflow_scala](https://github.com/eaplatanios/tensorflow_scala) - TensorFlow API for the Scala Programming Language
* [wzhe06/SparkCTR](https://github.com/wzhe06/SparkCTR) - CTR prediction model based on spark(LR, GBDT, DNN)
* [ThoughtWorksInc/DeepLearning.scala](https://github.com/ThoughtWorksInc/DeepLearning.scala) - A simple library for creating complex neural networks
* [factorie/factorie](https://github.com/factorie/factorie) - FACTORIE is a toolkit for deployable probabilistic modeling, implemented as a software library in Scala. It provides its users with a succinct language for creating relational factor graphs, estimating parameters and performing inference.
* [spotify/featran](https://github.com/spotify/featran) - A Scala feature transformation library for data science and machine learning
* [stripe-archive/brushfire](https://github.com/stripe-archive/brushfire) - Distributed decision tree ensemble learning in Scala *(archived)*
* [aws/sagemaker-spark](https://github.com/aws/sagemaker-spark) - A Spark library for Amazon SageMaker.
* [linkedin/isolation-forest](https://github.com/linkedin/isolation-forest) - A distributed Spark/Scala implementation of the isolation forest and extended isolation forest algorithms for unsupervised outlier detection, featuring support for scalable training and ONNX export for easy cross-platform inference.
* [ctongfei/nexus](https://github.com/ctongfei/nexus) - Experimental tensor-typed deep learning
* [danielkorzekwa/bayes-scala](https://github.com/danielkorzekwa/bayes-scala) - Bayesian Networks in Scala
* [tailhq/DynaML](https://github.com/tailhq/DynaML) - Scala Library/REPL for Machine Learning Research
* [vinta/albedo](https://github.com/vinta/albedo) - A recommender system for discovering GitHub repos, built with Apache Spark
* [linkedin/LiFT](https://github.com/linkedin/LiFT) - The LinkedIn Fairness Toolkit (LiFT) is a Scala/Spark library that enables the measurement of fairness in large scale machine learning workflows.
* [rjagerman/glint](https://github.com/rjagerman/glint) - Glint: High performance scala parameter server
* [bytedeco/storch](https://github.com/bytedeco/storch) - GPU accelerated deep learning and numeric computing for Scala 3.
* [maxpumperla/ScalphaGoZero](https://github.com/maxpumperla/ScalphaGoZero) - An independent implementation of DeepMind's AlphaGoZero in Scala, using Deeplearning4J (DL4J)
* [EmergentOrder/onnx-scala](https://github.com/EmergentOrder/onnx-scala) - An ONNX (Open Neural Network eXchange) API and backend for typeful, functional deep learning and classical machine learning in Scala 3
* [botkop/scorch](https://github.com/botkop/scorch) - scorch is a deep learning framework in Scala inspired by PyTorch
* [bytedeco/storch-recommend](https://github.com/bytedeco/storch-recommend) - pure pytorch recommend system on scala3
* [picnicml/doddle-model](https://github.com/picnicml/doddle-model) - :cake: doddle-model: machine learning in Scala.
* [mandubian/neurocat](https://github.com/mandubian/neurocat) - From neural networks to the Category of composable supervised learning algorithms in Scala with compile-time matrix checking based on singleton-types
* [microsoft/scala_torch](https://github.com/microsoft/scala_torch) - Scala bindings for LibTorch *(archived)*
* [Clustering4Ever/Clustering4Ever](https://github.com/Clustering4Ever/Clustering4Ever) - C4E, a JVM friendly library written in Scala for both local and distributed (Spark) Clustering.
* [ciren/cilib](https://github.com/ciren/cilib) - Typesafe, purely functional Computational Intelligence
* [zenecture/neuroflow](https://github.com/zenecture/neuroflow) - Artificial Neural Networks for Scala
* [bobye/neuron](https://github.com/bobye/neuron) - Scala library for neural networks
* [OndraFiedler/spark-recommender](https://github.com/OndraFiedler/spark-recommender) - Scalable recommendation system written in Scala using the Apache Spark framework

### Data Science and Analytics

* [apache/spark](https://github.com/apache/spark) - Apache Spark - A unified analytics engine for large-scale data processing
* [polynote/polynote](https://github.com/polynote/polynote) - A better notebook for Scala (and more)
* [awslabs/deequ](https://github.com/awslabs/deequ) - Deequ is a library built on top of Apache Spark for defining "unit tests for data", which measure data quality in large datasets.
* [twitter/scalding](https://github.com/twitter/scalding) - A Scala API for Cascading
* [spark-jobserver/spark-jobserver](https://github.com/spark-jobserver/spark-jobserver) - REST job server for Apache Spark
* [spotify/scio](https://github.com/spotify/scio) - A Scala API for Apache Beam and Google Cloud Dataflow.
* [geekyouth/SZT-bigdata](https://github.com/geekyouth/SZT-bigdata) - 深圳地铁大数据客流分析系统🚇🚄🌟
* [apache/sedona](https://github.com/apache/sedona) - A cluster computing framework for processing large-scale geospatial data
* [almond-sh/almond](https://github.com/almond-sh/almond) - A Scala kernel for Jupyter
* [mesos/spark](https://github.com/mesos/spark) - Lightning-fast cluster computing in Java, Scala and Python.
* [typelevel/frameless](https://github.com/typelevel/frameless) - Expressive types for Spark.
* [gearpump/gearpump](https://github.com/gearpump/gearpump) - Lightweight real-time big data streaming engine over Akka
* [vegas-viz/Vegas](https://github.com/vegas-viz/Vegas) - The missing MatPlotLib for Scala + Spark
* [AbsaOSS/spline](https://github.com/AbsaOSS/spline) - Data Lineage Tracking And Visualization Solution
* [YotpoLtd/metorikku](https://github.com/YotpoLtd/metorikku) - A simplified, lightweight ETL Framework based on Apache Spark
* [Stratio/sparta](https://github.com/Stratio/sparta) - Real Time Analytics and Data Pipelines based on Spark Streaming *(archived)*
* [NICTA/scoobi](https://github.com/NICTA/scoobi) - A Scala productivity framework for Hadoop.
* [spotify/ratatool](https://github.com/spotify/ratatool) - A tool for data sampling, data generation, and data diffing
* [mattpap/IScala](https://github.com/mattpap/IScala) - Scala backend for IPython
* [paypal/gimel](https://github.com/paypal/gimel) - Big Data Processing Framework - Unified Data API or SQL on Any Storage
* [cibotech/evilplot](https://github.com/cibotech/evilplot) - A Scala combinator-based plotting library.
* [G-Research/spark-extension](https://github.com/G-Research/spark-extension) - A library that provides useful extensions to Apache Spark and PySpark.
* [Azure/azure-event-hubs-spark](https://github.com/Azure/azure-event-hubs-spark) - Enabling Continuous Data Processing with Apache Spark and Azure Event Hubs
* [Qbeast-io/qbeast-spark](https://github.com/Qbeast-io/qbeast-spark) - Qbeast-spark: DataSource enabling multi-dimensional indexing and efficient data sampling. Big Data, free from the unnecessary!
* [alexarchambault/plotly-scala](https://github.com/alexarchambault/plotly-scala) - Scala bindings for plotly.js
* [heathermiller/progfun-stats](https://github.com/heathermiller/progfun-stats) - Visualize statistics from the MOOC "Functional Programming Principles in Scala" using Scala!
* [asdud/Bigdata_project](https://github.com/asdud/Bigdata_project) - 电商大数据项目-推荐系统(java和scala语言)
* [swoop-inc/spark-alchemy](https://github.com/swoop-inc/spark-alchemy) - Collection of open-source Spark tools & frameworks that have made the data engineering and data science teams at Swoop highly productive
* [SETL-Framework/setl](https://github.com/SETL-Framework/setl) - A simple Spark-powered ETL framework that just works 🍺
* [leobenkel/ZparkIO](https://github.com/leobenkel/ZparkIO) - Boiler plate framework to use Spark and ZIO together.
* [archivesunleashed/aut](https://github.com/archivesunleashed/aut) - The Archives Unleashed Toolkit is an open-source toolkit for analyzing web archives.
* [sparkling-graph/sparkling-graph](https://github.com/sparkling-graph/sparkling-graph) - SparklingGraph provides easy to use set of features that will give you ability to proces large scala graphs using Spark and GraphX.
* [ElAlev/Wayeb](https://github.com/ElAlev/Wayeb) - Wayeb is a Complex Event Processing and Forecasting (CEP/F) engine written in Scala.
* [scala-chart/scala-chart](https://github.com/scala-chart/scala-chart) - Scala Chart Library
* [coral-streaming/coral](https://github.com/coral-streaming/coral) - Coral is a real-time analytics and data science platform. It transforms streaming events and extract patterns from data via RESTful APIs. Built on Scala, Akka, Cassandra and Spray. *(archived)*
* [51zero/eel-sdk](https://github.com/51zero/eel-sdk) - Big Data Toolkit for the JVM
* [marklister/product-collections](https://github.com/marklister/product-collections) - A very simple, strongly typed, scala framework for tabular data. A collection of tuples. A strongly typed scala csv reader and writer. A lightweight idiomatic dataframe / datatable alternative.
* [VirtusLab/iskra](https://github.com/VirtusLab/iskra) - Typesafe wrapper for Apache Spark DataFrame API
* [bokeh/bokeh-scala](https://github.com/bokeh/bokeh-scala) - Scala bindings for Bokeh plotting library *(archived)*
* [yahoo/maha](https://github.com/yahoo/maha) - A framework for rapid reporting API development; with out of the box support for high cardinality dimension lookups with druid.
* [twitter/tormenta](https://github.com/twitter/tormenta) - Scala extensions for Storm
* [MemVerge/splash](https://github.com/MemVerge/splash) - Splash, a flexible Spark shuffle manager that supports user-defined storage backends for shuffle data storage and exchange
* [smart-data-lake/smart-data-lake](https://github.com/smart-data-lake/smart-data-lake) - Smart Automation Tool for building modern Data Lakes and Data Pipelines
* [xxxnell/flex](https://github.com/xxxnell/flex) - Probabilistic deep learning for data streams.
* [sameersingh/scalaplot](https://github.com/sameersingh/scalaplot) - Library to plot graphs using a scala frontend, and various backends such as gnuplot, jfreegraph, matplotlib, etc.
* [alexarchambault/ammonite-spark](https://github.com/alexarchambault/ammonite-spark) - Run spark calculations from Ammonite
* [flink-extended/flink-scala-api](https://github.com/flink-extended/flink-scala-api) - Flink Scala API is a thin wrapper on top of Flink Java API which support Scala Types for serialisation as well the latest Scala version
* [chitralverma/scala-polars](https://github.com/chitralverma/scala-polars) - Polars for Scala & Java projects!
* [holdenk/spark-validator](https://github.com/holdenk/spark-validator) - A library you can include in your Spark job to validate the counters and perform operations on success. Goal is scala/java/python support.

## Networking and Distributed

### Networking

* [playframework/play-mailer](https://github.com/playframework/play-mailer) - Play mailer plugin
* [sirthias/scala-ssh](https://github.com/sirthias/scala-ssh) - Remote shell access via SSH for your Scala applications
* [Comcast/ip4s](https://github.com/Comcast/ip4s) - Defines immutable, safe data structures for describing IP addresses, multicast joins, socket addresses and similar IP & network related data types
* [dmurvihill/courier](https://github.com/dmurvihill/courier) - send electronic mail with scala
* [ShellRechargeSolutionsEU/ocpp](https://github.com/ShellRechargeSolutionsEU/ocpp) - Open Charge Point Protocol *(archived)*

### RPC and Messaging

* [twitter/finagle](https://github.com/twitter/finagle) - A fault tolerant, protocol-agnostic RPC system
* [twitter/scrooge](https://github.com/twitter/scrooge) - A Thrift parser/generator
* [akka/akka-grpc](https://github.com/akka/akka-grpc) - A platform to build and run apps that are elastic, agile, and resilient. SDK, libraries, and hosted environments.
* [lihaoyi/autowire](https://github.com/lihaoyi/autowire) - Macros for simple/safe RPCs between Scala applications, including ScalaJS/ScalaJVM
* [higherkindness/mu-scala](https://github.com/higherkindness/mu-scala) - Mu is a purely functional library for building RPC endpoint based services with support for RPC and HTTP/2
* [boundary/scalang](https://github.com/boundary/scalang) - Scalang is a scala wrapper that makes it easy to write services that interface with erlang.
* [mDialog/scala-zeromq](https://github.com/mDialog/scala-zeromq) - Thread-safe ZeroMQ for Scala *(archived)*

### Distributed Systems

* [ACINQ/eclair](https://github.com/ACINQ/eclair) - A scala implementation of the Lightning Network.
* [wavesplatform/Waves](https://github.com/wavesplatform/Waves) - ⛓️ Reference Waves Blockchain Node (client) implementation on Scala
* [eligosource/eventsourced](https://github.com/eligosource/eventsourced) - A library for building reliable, scalable and distributed event-sourced applications in Scala
* [hyperledger-labs/Scorex](https://github.com/hyperledger-labs/Scorex) - Scorex 2.0 Core *(archived)*
* [devsisters/shardcake](https://github.com/devsisters/shardcake) - Sharding and location transparency for Scala
* [bitcoin-s/bitcoin-s](https://github.com/bitcoin-s/bitcoin-s) - Bitcoin Implementation in Scala
* [ing-bank/baker](https://github.com/ing-bank/baker) - Orchestrate microservice-based process flows
* [fun-cqrs/fun-cqrs](https://github.com/fun-cqrs/fun-cqrs) - Fun.CQRS is a Scala CQRS/ES framework. It provides the basic blocks to build event driven aggregates with Event Sourcing.
* [notxcain/aecor](https://github.com/notxcain/aecor) - Pure functional event sourcing runtime
* [khipu-io/khipu](https://github.com/khipu-io/khipu) - An enterprise blockchain platform based on Ethereum
* [fthomas/crjdt](https://github.com/fthomas/crjdt) - A conflict-free replicated JSON datatype (CRDT) in Scala
* [velvia/ScalaStorm](https://github.com/velvia/ScalaStorm) - Harness the power and elegance of Scala with nathanmarz's Storm real-time system
* [input-output-hk/mantis](https://github.com/input-output-hk/mantis) - A Scala based client for Ethereum-like Blockchains.
* [VladKopanev/zio-saga](https://github.com/VladKopanev/zio-saga) - Purely Functional Transaction Management In Scala With ZIO *(archived)*
* [pablosmedina/ckite](https://github.com/pablosmedina/ckite) - CKite - A JVM implementation of the Raft distributed consensus algorithm written in Scala *(archived)*
* [alephium/alephium](https://github.com/alephium/alephium) - Reference client for Alephium protocol
* [zio-archive/zio-keeper](https://github.com/zio-archive/zio-keeper) - A ZIO library for building distributed systems *(archived)*
* [svroonland/rezilience](https://github.com/svroonland/rezilience) - ZIO-native utilities for making resilient distributed systems
* [zio-archive/zio-akka-cluster](https://github.com/zio-archive/zio-akka-cluster) - ZIO wrapper for Akka Cluster *(archived)*
* [parapet-io/parapet](https://github.com/parapet-io/parapet) - A purely functional library for building distributed and event-driven systems.
* [blockchain-unica/blockapi](https://github.com/blockchain-unica/blockapi) - A general framework for blockchain analytics
* [SwissBorg/lithium](https://github.com/SwissBorg/lithium) - Lithium - A split-brain resolver for Akka-Cluster *(archived)*
* [VladKopanev/cats-saga](https://github.com/VladKopanev/cats-saga) - Purely Functional Transaction Management In Scala With Cats *(archived)*
* [iheartradio/kanaloa](https://github.com/iheartradio/kanaloa) - Make your service more resilient by providing protection against traffic oversaturation
* [ACINQ/bitcoin-lib](https://github.com/ACINQ/bitcoin-lib) - Simple bitcoin library written in Scala
* [openlawteam/openlaw-core](https://github.com/openlawteam/openlaw-core) - Shared Scala libraries for the OpenLaw project. *(archived)*
* [PaytmLabs/akka-batteries](https://github.com/PaytmLabs/akka-batteries) - Utilities for Akka cluster in production

### Cloud and Infrastructure

* [seratch/AWScala](https://github.com/seratch/AWScala) - Using AWS SDK on the Scala REPL *(archived)*
* [getnelson/nelson](https://github.com/getnelson/nelson) - Automated, multi-region container deployment
* [doriordan/skuber](https://github.com/doriordan/skuber) - A Scala Kubernetes client library
* [Bayer-Group/cloudformation-template-generator](https://github.com/Bayer-Group/cloudformation-template-generator) - A type-safe Scala DSL for generating CloudFormation templates
* [Tapad/sbt-docker-compose](https://github.com/Tapad/sbt-docker-compose) - Integrates Docker Compose functionality into sbt (archived as unmaintained) *(archived)*
* [VirtusLab/besom](https://github.com/VirtusLab/besom) - Besom - a Pulumi SDK for Scala. Also, incidentally, a broom made of twigs tied round a stick. Brooms and besoms are used for protection, to ward off evil spirits, and cleansing of ritual spaces.
* [sbt-jib/sbt-jib](https://github.com/sbt-jib/sbt-jib) - sbt version of sbt jib: https://github.com/GoogleContainerTools/jib
* [zio/zio-aws](https://github.com/zio/zio-aws) - Low level ZIO interface for the full AWS
* [mkotsur/aws-lambda-scala](https://github.com/mkotsur/aws-lambda-scala) - Writing AWS Lambdas in Scala
* [joan38/kubernetes-client](https://github.com/joan38/kubernetes-client) - A Kubernetes client for Scala
* [dwhjames/aws-wrap](https://github.com/dwhjames/aws-wrap) - Asynchronous Scala Clients for Amazon Web Services
* [alexkvak/teamcity-slack](https://github.com/alexkvak/teamcity-slack) - TeamCity Slack plugin
* [heroku/heroku-sbt-plugin](https://github.com/heroku/heroku-sbt-plugin) - An sbt plugin for deploying Heroku Scala applications *(archived)*
* [quaich-project/quaich](https://github.com/quaich-project/quaich) - Scala Serverless Microframework for AWS Lambda, inspired by Amazon's Chalice (https://github.com/awslabs/chalice)
* [Orkestra-Tech/orkestra](https://github.com/Orkestra-Tech/orkestra) - Functional DevOps with Scala and Kubernetes

### Monitoring and Observability

* [kamon-io/Kamon](https://github.com/kamon-io/Kamon) - Distributed Tracing, Metrics and Context Propagation for applications running on the JVM
* [twitter-archive/ostrich](https://github.com/twitter-archive/ostrich) - A stats collector & reporter for Scala servers (deprecated) *(archived)*
* [erikvanoosten/metrics-scala](https://github.com/erikvanoosten/metrics-scala) - The scala API for Dropwizard's Metrics.
* [typelevel/natchez](https://github.com/typelevel/natchez) - functional tracing for cats
* [typelevel/otel4s](https://github.com/typelevel/otel4s) - An OpenTelemetry library for Scala based on Cats-Effect
* [zalando-incubator/remora](https://github.com/zalando-incubator/remora) - Kafka consumer lag-checking application for monitoring, written in Scala and Akka HTTP; a wrap around the Kafka consumer group command. Integrations with Cloudwatch and Datadog. Authentication recently added
* [trace4cats/trace4cats](https://github.com/trace4cats/trace4cats) - Distributed app tracing implementation in pure scala using cats-effect
* [kubukoz/sup](https://github.com/kubukoz/sup) - Composable, purely functional healthchecks in Scala. *(archived)*
* [zio/zio-telemetry](https://github.com/zio/zio-telemetry) - ZIO-powered OpenTelemetry library
* [Colisweb/scala-opentracing](https://github.com/Colisweb/scala-opentracing) - A tracing library for Cats and Http4s, tailored for Opentracing tracers like Datadog and Jaeger *(archived)*

## User Interface

### Terminal and Console UI

* [marconilanna/REPLesent](https://github.com/marconilanna/REPLesent) - A neat little tool to build presentations using the Scala REPL
* [mattlianje/layoutz](https://github.com/mattlianje/layoutz) - Simple, beautiful CLI output
* [oyvindberg/jatatui](https://github.com/oyvindberg/jatatui) - A Java port of ratatui — build rich terminal UIs from Java
* [Tenchi2xh/Scurses](https://github.com/Tenchi2xh/Scurses) - Scurses, terminal drawing API for Scala, and Onions, a Scurses framework for easy terminal UI
* [com-lihaoyi/fansi](https://github.com/com-lihaoyi/fansi) - Scala/Scala.js library for manipulating Fancy Ansi colored strings

### Applications and End User Tools

* [lichess-org/lila](https://github.com/lichess-org/lila) - ♞ lichess.org: the forever free, adless and open source chess server ♞
* [yahoo/CMAK](https://github.com/yahoo/CMAK) - CMAK is a tool for managing Apache Kafka clusters
* [gitbucket/gitbucket](https://github.com/gitbucket/gitbucket) - A Git platform powered by Scala with easy installation, high extensibility & GitHub API compatibility
* [xxf098/shadowsocksr-v2ray-trojan-android](https://github.com/xxf098/shadowsocksr-v2ray-trojan-android) - A simple client for Android
* [PkmX/lcamera](https://github.com/PkmX/lcamera) - A camera app using the new camera2 API in Android Lollipop *(archived)*
* [Antox/Antox](https://github.com/Antox/Antox) - Android client for Project Tox - Secure Peer to Peer Messaging *(archived)*
* [TouK/nussknacker](https://github.com/TouK/nussknacker) - Low-code tool for automating actions on real time data | Stream processing for the users.
* [felixgborrego/simple-docker-ui](https://github.com/felixgborrego/simple-docker-ui) - Native Docker UI implemented using Scala.js and React - DEPRECATED
* [markwinter/Antox](https://github.com/markwinter/Antox) - Scala android client for Project Tox - secure p2p messaging
* [scalacenter/scastie](https://github.com/scalacenter/scastie) - An interactive playground for Scala
* [scalad/LayIM](https://github.com/scalad/LayIM) - 基于HTML5 WebSocket的一款IM即时通讯软件，使用Gradle集成了Scala、SpringBoot、Spring MVC、Mybatis、Redis等，前端使用了LayIm框架
* [MAIF/izanami](https://github.com/MAIF/izanami) - Izanami is a centralized versatile feature flag solution, well suited for micro service architectures.
* [hrj/abandon](https://github.com/hrj/abandon) - :relieved: Simple and Robust Accounting
* [atware/scuruto](https://github.com/atware/scuruto) - An internal knowledge sharing app
* [sndnv/stasis](https://github.com/sndnv/stasis) - Multiplatform backup and recovery system with emphasis on security and privacy
* [Nutomic/ensichat](https://github.com/Nutomic/ensichat) - Project discontinued *(archived)*
* [xebia-functional/scala-days-android](https://github.com/xebia-functional/scala-days-android) - Official Android app for Scala Days
* [yoshikyoto/lgtmoon](https://github.com/yoshikyoto/lgtmoon) - LGTM画像を簡単に作成できるアプリ
* [reibitto/command-center](https://github.com/reibitto/command-center) - A CLI-based launcher and general productivity tool.
* [MasseGuillaume/ScalaKata2](https://github.com/MasseGuillaume/ScalaKata2) - Interactive Playground *(archived)*

## Graphics and Media

### Game Development

* [MightyPirates/OpenComputers](https://github.com/MightyPirates/OpenComputers) - Home of the OpenComputers mod for Minecraft. *(archived)*
* [lichess-org/scalachess](https://github.com/lichess-org/scalachess) - Chess API written in scala. Immutable and free of side effects.
* [PurpleKingdomGames/indigo](https://github.com/PurpleKingdomGames/indigo) - An FP game engine for Scala. *(archived)*
* [scalatron/scalatron](https://github.com/scalatron/scalatron) - Scalatron, a multi-player programming game in which coders pit bot programs (written in Scala) against each other
* [nivanov/cosplay](https://github.com/nivanov/cosplay) - 🕹 2D ASCII Game Engine for Scala3
* [delorum/scage](https://github.com/delorum/scage) - game engine written in Scala
* [regb/scala-game-library](https://github.com/regb/scala-game-library) - Scala library for cross-platform game development
* [abbruzze/kernal64](https://github.com/abbruzze/kernal64) - A Scala Commodore 64, 128, VIC20, CBM2 and SuperCPU emulator

## Security

### Security Tools

* [TheHive-Project/TheHive](https://github.com/TheHive-Project/TheHive) - TheHive is a Collaborative Case Management Platform, now distributed as a commercial version *(archived)*
* [joernio/joern](https://github.com/joernio/joern) - Open-source code analysis platform for C/C++/Java/Binary/Javascript/Python/Kotlin based on code property graphs. Discord https://discord.gg/vv4MH284Hc
* [TheHive-Project/Cortex](https://github.com/TheHive-Project/Cortex) - Cortex: a Powerful Observable Analysis and Active Response Engine
* [makenowjust-labs/recheck](https://github.com/makenowjust-labs/recheck) - The trustworthy ReDoS checker
* [albuch/sbt-dependency-check](https://github.com/albuch/sbt-dependency-check) - SBT Plugin for OWASP DependencyCheck. Monitor your dependencies and report if there are any publicly known vulnerabilities (e.g. CVEs). :rainbow: *(archived)*
* [sief/play-guard](https://github.com/sief/play-guard) - Play2 module for rate limiting, based on token bucket algorithm

### Authentication and Authorization

* [mohiva/play-silhouette](https://github.com/mohiva/play-silhouette) - Silhouette is an authentication library for Play Framework applications that supports several authentication methods, including OAuth1, OAuth2, OpenID, CAS, 2FA, TOTP, Credentials, Basic Authentication or custom authentication schemes. *(archived)*
* [jwt-scala/jwt-scala](https://github.com/jwt-scala/jwt-scala) - JWT support for Scala. Bonus extensions for Play, Play JSON, Json4s, Circe, uPickle, Spray and Argonaut
* [nulab/scala-oauth2-provider](https://github.com/nulab/scala-oauth2-provider) - OAuth 2.0 server-side implementation written in Scala
* [softwaremill/akka-http-session](https://github.com/softwaremill/akka-http-session) - Web & mobile client-side akka-http sessions, with optional JWT support *(archived)*
* [jasongoodwin/authentikat-jwt](https://github.com/jasongoodwin/authentikat-jwt) - JWT Scala Implementation - Claims based auth for Scala.

## Concurrency and Performance

### Concurrency and Parallelism

* [zio/zio](https://github.com/zio/zio) - ZIO — A type-safe, composable library for async and concurrent programming in Scala
* [typelevel/fs2](https://github.com/typelevel/fs2) - Compositional, streaming I/O library for Scala
* [typelevel/cats-effect](https://github.com/typelevel/cats-effect) - The pure asynchronous runtime for Scala
* [monix/monix](https://github.com/monix/monix) - Asynchronous, Reactive Programming for Scala and Scala.js.
* [apache/pekko](https://github.com/apache/pekko) - Build highly concurrent, distributed, and resilient message-driven applications using Java/Scala
* [scala/scala-async](https://github.com/scala/scala-async) - An asynchronous programming facility for Scala
* [lihaoyi/scala.rx](https://github.com/lihaoyi/scala.rx) - An experimental library for Functional Reactive Programming in Scala
* [ReactiveX/RxScala](https://github.com/ReactiveX/RxScala) - RxScala – Reactive Extensions for Scala – a library for composing asynchronous and event-based programs using observable sequences
* [getkyo/kyo](https://github.com/getkyo/kyo) - Toolkit for Scala Development
* [softwaremill/ox](https://github.com/softwaremill/ox) - Safe direct-style streaming, concurrency and resiliency for Scala on the JVM
* [akka-js/akka.js](https://github.com/akka-js/akka.js) - Akka, for Scala.js
* [lampepfl/gears](https://github.com/lampepfl/gears) - A strawman for a low-level async library in Scala 3.
* [krasserm/streamz](https://github.com/krasserm/streamz) - A combinator library for integrating Functional Streams for Scala (FS2), Akka Streams and Apache Camel
* [zio-archive/zio-actors](https://github.com/zio-archive/zio-actors) - A high-performance, purely-functional library for building, composing, and supervising typed actors based on ZIO *(archived)*
* [nbronson/scala-stm](https://github.com/nbronson/scala-stm) - A library-based Software Transactional Memory (STM) for Scala, coupled with transactional sets and maps
* [traneio/arrows](https://github.com/traneio/arrows) - High-performance Arrow and Task in Scala
* [scala/scala-parallel-collections](https://github.com/scala/scala-parallel-collections) - Parallel collections standard library module for Scala 2.13+
* [TomasMikula/libretto](https://github.com/TomasMikula/libretto) - Declarative concurrency and stream processing library for Scala
* [runarorama/scala-machines](https://github.com/runarorama/scala-machines) - A stream processing library for Scala
* [rssh/scala-gopher](https://github.com/rssh/scala-gopher) - Implementation of CSP constructions (Communication Sequence Process, i.e. go-like channels) in scala
* [dotty-cps-async/dotty-cps-async](https://github.com/dotty-cps-async/dotty-cps-async) - experimental CPS transformer for dotty
* [travisbrown/iteratee](https://github.com/travisbrown/iteratee) - Iteratees for Cats
* [SystemFw/upperbound](https://github.com/SystemFw/upperbound) - A purely functional rate limiter
* [qifun/stateless-future](https://github.com/qifun/stateless-future) - Asynchronous programming in fully featured Scala syntax.
* [axel22/Ctries](https://github.com/axel22/Ctries) - Scala implementation of the Ctrie datastructure.
* [scala-blitz/scala-blitz](https://github.com/scala-blitz/scala-blitz) - Scala framework for efficient sequential and data-parallel collections -
* [sirthias/swave](https://github.com/sirthias/swave) - A lightweight Reactive Streams Infrastructure Toolkit for Scala.
* [Chymyst/chymyst-core](https://github.com/Chymyst/chymyst-core) - Declarative concurrency in Scala - The implementation of the chemical machine
* [storm-enroute/coroutines](https://github.com/storm-enroute/coroutines) - Scala coroutines implementation.
* [zio/zio-direct](https://github.com/zio/zio-direct) - Direct-Style Programming for ZIO
* [com-lihaoyi/castor](https://github.com/com-lihaoyi/castor) - Castor is a lightweight, typed Actor library for Scala and Scala.js
* [TimWSpence/cats-stm](https://github.com/TimWSpence/cats-stm) - A STM implementation for Cats Effect
* [johanandren/futiles](https://github.com/johanandren/futiles) - The missing utils for working with Scala Futures
* [ingoem/scala-react](https://github.com/ingoem/scala-react) - Scala.react is a reactive programming library for Scala.
* [sjrd/scala-js-actors](https://github.com/sjrd/scala-js-actors) - Actor system for Scala.js *(archived)*

### Performance and Optimization

* [sbt/sbt-jmh](https://github.com/sbt/sbt-jmh) - "Trust no one, bench everything." - sbt plugin for JMH (Java Microbenchmark Harness)
* [densh/scala-offheap](https://github.com/densh/scala-offheap) - Experimental type-safe off-heap memory for Scala. *(archived)*
* [scalameter/scalameter](https://github.com/scalameter/scalameter) - Microbenchmarking and performance regression testing framework for the JVM platform.
* [xerial/larray](https://github.com/xerial/larray) - Large off-heap arrays and mmap files for Scala and Java
* [nativelibs4java/ScalaCL](https://github.com/nativelibs4java/ScalaCL) - ScalaCL - run Scala on your GPU!
* [ComputeNode/cyfra](https://github.com/ComputeNode/cyfra) - Multi-platform GPGPU computations with Scala, seamlessly 🚀
* [Ichoran/thyme](https://github.com/Ichoran/thyme) - Thyme is a microbenchmark utility for Scala. It includes Parsley, a (simple) local profiling tool. *(archived)*
* [plokhotnyuk/actors](https://github.com/plokhotnyuk/actors) - Evaluation of API and performance of different actor libraries
* [johnynek/inliner](https://github.com/johnynek/inliner) - scala macros to inline idiomatic scala for maximum performance
* [sirthias/scala-benchmarking-template](https://github.com/sirthias/scala-benchmarking-template) - SBT template project for creating Scala (micro-)benchmarks based on Caliper

## Testing and Quality

### Testing

* [gatling/gatling](https://github.com/gatling/gatling) - Modern Load Testing as Code
* [typelevel/scalacheck](https://github.com/typelevel/scalacheck) - Property-based testing for Scala
* [seveniruby/AppCrawler](https://github.com/seveniruby/AppCrawler) - 基于appium的app自动遍历工具
* [scalatest/scalatest](https://github.com/scalatest/scalatest) - A testing tool for Scala and Java developers
* [etorreborre/specs2](https://github.com/etorreborre/specs2) - Software Specifications for Scala
* [testcontainers/testcontainers-scala](https://github.com/testcontainers/testcontainers-scala) - Docker containers for testing in scala
* [scalamock/scalamock](https://github.com/scalamock/scalamock) - Native Scala mocking framework
* [com-lihaoyi/utest](https://github.com/com-lihaoyi/utest) - A simple testing framework for Scala
* [scalameta/munit](https://github.com/scalameta/munit) - Scala testing library with actionable errors and extensible APIs
* [scoverage/scalac-scoverage-plugin](https://github.com/scoverage/scalac-scoverage-plugin) - Scoverage Scala Code Coverage Core Libs
* [whisklabs/docker-it-scala](https://github.com/whisklabs/docker-it-scala) - Docker integration testing kit with Scala
* [mockito/mockito-scala](https://github.com/mockito/mockito-scala) - Mockito for Scala language
* [softwaremill/diffx](https://github.com/softwaremill/diffx) - Pretty diffs for scala case classes *(archived)*
* [typelevel/discipline](https://github.com/typelevel/discipline) - Flexible law checking for Scala
* [manub/scalatest-embedded-kafka](https://github.com/manub/scalatest-embedded-kafka) - A library that provides an in-memory Kafka instance to run your tests against.
* [scalaprops/scalaprops](https://github.com/scalaprops/scalaprops) - property based testing library for Scala
* [hedgehogqa/scala-hedgehog](https://github.com/hedgehogqa/scala-hedgehog) - Release with confidence, state-of-the-art property testing for Scala.
* [alexarchambault/scalacheck-shapeless](https://github.com/alexarchambault/scalacheck-shapeless) - Generation of arbitrary case classes / ADTs instances with scalacheck and shapeless
* [agourlay/cornichon](https://github.com/agourlay/cornichon) - Testing tool in Scala for HTTP JSON API
* [stryker-mutator/stryker4s](https://github.com/stryker-mutator/stryker4s) - Mutation testing for Scala
* [typelevel/cats-effect-testing](https://github.com/typelevel/cats-effect-testing) - Integration between cats-effect and test frameworks
* [pniederw/expecty](https://github.com/pniederw/expecty) - Power assertions (as known from Groovy and Spock) for the Scala language.
* [DanielaSfregola/random-data-generator](https://github.com/DanielaSfregola/random-data-generator) - Random generator of test data in Scala based on Scalacheck and Shapeless
* [sbt-doctest/sbt-doctest](https://github.com/sbt-doctest/sbt-doctest) - Doctest for scala
* [japgolly/nyaya](https://github.com/japgolly/nyaya) - Random Data Generation and/or Property Testing in Scala & Scala.JS.
* [jpzk/mockedstreams](https://github.com/jpzk/mockedstreams) - Scala DSL for Unit-Testing Processing Topologies in Kafka Streams
* [monix/minitest](https://github.com/monix/minitest) - The super light testing library for Scala and Scala.js
* [bizzabo/diff](https://github.com/bizzabo/diff) - Visually compare Scala data structures with out of the box support for arbitrary case classes.
* [chiselverify/chiselverify](https://github.com/chiselverify/chiselverify) - A dynamic verification library for Chisel.
* [youzan/gatling-dubbo](https://github.com/youzan/gatling-dubbo) - A gatling plugin for running load tests on Apache Dubbo(https://github.com/apache/incubator-dubbo) and other java ecosystem.
* [japgolly/test-state](https://github.com/japgolly/test-state) - Scala Test-State.
* [scala/community-build](https://github.com/scala/community-build) - Scala 2 community build — a corpus of open-source repos built against Scala nightlies
* [leanovate/play-mockws](https://github.com/leanovate/play-mockws) - Mock WS client for Play Framework
* [mtkopone/scct](https://github.com/mtkopone/scct) - Scala Code Coverage Tool
* [sbt/sbt-jacoco](https://github.com/sbt/sbt-jacoco) - an sbt plugin for JaCoCo Code Coverage
* [47degrees/scalacheck-toolbox](https://github.com/47degrees/scalacheck-toolbox) - A helping hand for generating sensible data with ScalaCheck
* [ITV/scala-pact](https://github.com/ITV/scala-pact) - A Scala implementation of CDC using the Pact standard *(archived)*
* [playframework/scalatestplus-play](https://github.com/playframework/scalatestplus-play) - ScalaTest + Play
* [scoverage/sbt-coveralls](https://github.com/scoverage/sbt-coveralls) - sbt-plugin to upload sbt-scoverage reports to coveralls
* [mgonto/factory_pal](https://github.com/mgonto/factory_pal) - A Scala framework for creating objects as test data. Say no to Mocks
* [ca-archived/aeromock](https://github.com/ca-archived/aeromock) - Lightweight mock web application server
* [CyberAgent/aeromock](https://github.com/CyberAgent/aeromock) - Lightweight mock web application server

## Utilities

### Command Line Tools

* [rtyley/bfg-repo-cleaner](https://github.com/rtyley/bfg-repo-cleaner) - Removes large or troublesome blobs like git-filter-branch does, but faster. And written in Scala
* [foundweekends/giter8](https://github.com/foundweekends/giter8) - a command line tool to apply templates defined on GitHub
* [scallop/scallop](https://github.com/scallop/scallop) - a simple Scala CLI parsing library
* [bkirwi/decline](https://github.com/bkirwi/decline) - A composable command-line parser for Scala.
* [alexarchambault/case-app](https://github.com/alexarchambault/case-app) - Type-level & seamless command-line argument parsing for Scala
* [com-lihaoyi/mainargs](https://github.com/com-lihaoyi/mainargs) - A small, convenient, dependency-free library for command-line argument parsing in Scala
* [scala-garden/jardiff](https://github.com/scala-garden/jardiff) - A tool for comparing JAR files, including method bodies and Scala 2 pickled signatures
* [zio/zio-cli](https://github.com/zio/zio-cli) - Rapidly build powerful command-line applications powered by ZIO
* [backuity/clist](https://github.com/backuity/clist) - Command Line Interface Scala Toolkit

### Logging and Configuration

* [pureconfig/pureconfig](https://github.com/pureconfig/pureconfig) - A boilerplate-free library for loading configuration files
* [scala-garden/scala-logging](https://github.com/scala-garden/scala-logging) - Convenient and performant logging library for Scala wrapping SLF4J.
* [outr/scribe](https://github.com/outr/scribe) - The fastest logging library in the world. Built from scratch in Scala and programmatically configurable.
* [LEGO/woof](https://github.com/LEGO/woof) - A pure Scala 3 logging library with no reflection
* [vlovgr/ciris](https://github.com/vlovgr/ciris) - Functional Configurations for Scala
* [valskalla/odin](https://github.com/valskalla/odin) - Fast & Functional logger in Scala
* [zio/zio-config](https://github.com/zio/zio-config) - Easily use and document any config from anywhere in ZIO apps
* [Philippus/sbt-dotenv](https://github.com/Philippus/sbt-dotenv) - ⏺️ Dotenv implementation for Scala sbt builds. Configures environment for local development.
* [zio/zio-logging](https://github.com/zio/zio-logging) - Powerful logging for ZIO 2.0 applications, with compatibility with many logging backends out-of-the-box.
* [Verizon/knobs](https://github.com/Verizon/knobs) - A reasonable configuration library for Scala *(archived)*
* [ceedubs/ficus](https://github.com/ceedubs/ficus) - Scala-friendly companion to Typesafe config - moved to https://github.com/iheartradio/ficus *(archived)*
* [typesafehub/scalalogging](https://github.com/typesafehub/scalalogging) - Convenient and performant logging in Scala
* [Log4s/log4s](https://github.com/Log4s/log4s) - High-performance SLF4J wrapper for Scala.
* [kxbmap/configs](https://github.com/kxbmap/configs) - Scala wrapper for Typesafe config
* [japgolly/clear-config](https://github.com/japgolly/clear-config) - Scala FP configuration library with a focus on runtime clarity
* [ekrich/sconfig](https://github.com/ekrich/sconfig) - Scala configuration library supporting HOCON for Scala, Java, Scala.js, and Scala Native
* [paradigmatic/Configrity](https://github.com/paradigmatic/Configrity) - Simple, immutable and flexible configuration library for scala.
* [circe/circe-config](https://github.com/circe/circe-config) - Yet another Typesafe config Scala wrapper powered by circe
* [carueda/tscfg](https://github.com/carueda/tscfg) - Schema-first, boilerplate-free, type-safe access to configuration properties in Java and Scala
* [hanabix/config-annotation](https://github.com/hanabix/config-annotation) - A refactor-friendly way to use typesafe's config by scala macro annotation *(archived)*

### Text Processing

* [com-lihaoyi/fastparse](https://github.com/com-lihaoyi/fastparse) - Writing Fast Parsers Fast in Scala
* [com-lihaoyi/scalatags](https://github.com/com-lihaoyi/scalatags) - ScalaTags is a small XML/HTML construction library for Scala.
* [sirthias/parboiled2](https://github.com/sirthias/parboiled2) - A macro-based PEG parser generator for Scala 2.10+
* [scala/scala-parser-combinators](https://github.com/scala/scala-parser-combinators) - simple combinator-based parsing for Scala. formerly part of the Scala standard library, now a separate community-maintained module
* [scalate/scalate](https://github.com/scalate/scalate) - Scalate is a Scala based template engine which supports HAML, Mustache and JSP, Erb and Velocity style syntaxes.
* [tpolecat/tut](https://github.com/tpolecat/tut) - doc/tutorial generator for scala *(archived)*
* [playframework/twirl](https://github.com/playframework/twirl) - Twirl is Play's default template engine
* [rockymadden/stringmetric](https://github.com/rockymadden/stringmetric) - :dart: String metrics and phonetic algorithms for Scala (e.g. Dice/Sorensen, Hamming, Jaccard, Jaro, Jaro-Winkler, Levenshtein, Metaphone, N-Gram, NYSIIS, Overlap, Ratcliff/Obershelp, Refined NYSIIS, Refined Soundex, Soundex, Weighted Levenshtein). *(archived)*
* [typelevel/Laika](https://github.com/typelevel/Laika) - Site and E-book Generator and Customizable Text Markup Transformer for sbt, Scala and Scala.js
* [Eliah-Lakhin/papa-carlo](https://github.com/Eliah-Lakhin/papa-carlo) - Constructor of incremental parsers in Scala
* [scalameta/mdoc](https://github.com/scalameta/mdoc) - Typechecked markdown documentation for Scala
* [tpolecat/atto](https://github.com/tpolecat/atto) - friendly little parsers
* [lihaoyi/Scalatex](https://github.com/lihaoyi/Scalatex) - Programmable, Typesafe Document Generation
* [propensive/contextual](https://github.com/propensive/contextual) - Statically-checked string interpolation in Scala *(archived)*
* [com-lihaoyi/PPrint](https://github.com/com-lihaoyi/PPrint) - Pretty-printing value, types and type-signatures in Scala
* [j-mie6/parsley](https://github.com/j-mie6/parsley) - A fast and modern parser combinator library for Scala
* [spray/twirl](https://github.com/spray/twirl) - The Play framework Scala template engine, stand-alone and packaged as an SBT plugin
* [cloudify/sPDF](https://github.com/cloudify/sPDF) - Create PDFs from Scala using plain old HTML and CSS. Uses wkhtmltopdf on the back-end which renders HTML using Webkit.
* [djspiewak/parseback](https://github.com/djspiewak/parseback) - A Scala implementation of parsing with derivatives
* [typelevel/paiges](https://github.com/typelevel/paiges) - an implementation of Wadler's a prettier printer
* [propensive/kaleidoscope](https://github.com/propensive/kaleidoscope) - Statically-checked inline matching on regular expressions in Scala *(archived)*
* [foundweekends/pamflet](https://github.com/foundweekends/pamflet) - a publishing application for short texts
* [zalando/beard](https://github.com/zalando/beard) - A lightweight, logicless templating engine, written in Scala and inspired by Mustache *(archived)*
* [mwunsch/handlebars.scala](https://github.com/mwunsch/handlebars.scala) - A Scala implementation of the Handlebars templating language (a superset of Mustache).
* [sake92/hepek](https://github.com/sake92/hepek) - Typesafe HTML templates and static site generator in pure Scala
* [chenkelmann/actuarius](https://github.com/chenkelmann/actuarius) - A markdown processor for the JVM written in Scala.
* [sparsetech/pine](https://github.com/sparsetech/pine) - Functional HTML5 and XML library for the Scala platform
* [tristanjuricek/knockoff](https://github.com/tristanjuricek/knockoff) - A Markdown parser + object model in scala
* [ua-parser/uap-scala](https://github.com/ua-parser/uap-scala) - Scala port of ua-parser

### Files and Operating System

* [pathikrit/better-files](https://github.com/pathikrit/better-files) - Simple, safe and intuitive Scala I/O
* [com-lihaoyi/os-lib](https://github.com/com-lihaoyi/os-lib) - OS-Lib is a simple, flexible, high-performance Scala interface to common OS filesystem and subprocess APIs
* [zio-archive/zio-nio](https://github.com/zio-archive/zio-nio) - A small, unopinionated ZIO interface to NIO. *(archived)*
* [scalajs-io/nodejs](https://github.com/scalajs-io/nodejs) - This project provides Scala.js type-safe bindings for Node.js (current) v8.7.0 and LTS v6.11.4 APIs. The platform supports MEAN (MongoDB, Express, AngularJs, NodeJS), Cassandra, MySQL and many other npm projects.
* [jodersky/akka-serial](https://github.com/jodersky/akka-serial) - Reactive serial communication library for Akka and Scala.
* [jesseeichar/scala-io](https://github.com/jesseeichar/scala-io) - Repository for work on Scala Standard Library I/O components
* [lloydmeta/schwatcher](https://github.com/lloydmeta/schwatcher) - File-watching library for Scala. Built on Java 7's WatchService, RxScala and Akka actors. *(archived)*
* [HouzuoGuo/schale](https://github.com/HouzuoGuo/schale) - A subprocess interface for Scala
* [vigoo/prox](https://github.com/vigoo/prox) - A Scala library for working with system processes

### Date and Time

* [nscala-time/nscala-time](https://github.com/nscala-time/nscala-time) - A new Scala wrapper for Joda Time based on scala-time
* [jorgeortiz85/scala-time](https://github.com/jorgeortiz85/scala-time) - A Scala wrapper for Joda Time
* [PagerDuty/scheduler](https://github.com/PagerDuty/scheduler) - A Scala library for scheduling arbitrary code to run at an arbitrary time. *(archived)*
* [fthomas/fs2-cron](https://github.com/fthomas/fs2-cron) - FS2 streams based on cron expressions
* [alonsodomin/cron4s](https://github.com/alonsodomin/cron4s) - Cross-platform CRON expression parsing for Scala
* [maxcellent/lamma](https://github.com/maxcellent/lamma) - Lamma schedule generator for Scala is a professional schedule generation library for periodic schedules like fixed income coupon payment, equity deravitive fixing date generation etc.
* [scala-js/scala-js-java-time](https://github.com/scala-js/scala-js-java-time) - Scala.js implementation for java.time in JDK8

### Automation and Scripting

* [bot4s/telegram](https://github.com/bot4s/telegram) - Telegram Bot API Wrapper for Scala
* [augustjune/canoe](https://github.com/augustjune/canoe) - Functional Telegram Bot API for Scala
* [business4s/workflows4s](https://github.com/business4s/workflows4s) - Simple, Composable, Business-oriented Workflows for Scala
* [Katrix/AckCord](https://github.com/Katrix/AckCord) - A Discord library for Scala using Akka
* [criteo/cuttle](https://github.com/criteo/cuttle) - An embedded job scheduler.

### General Purpose Libraries

* [scalaz/scalaz](https://github.com/scalaz/scalaz) - Principled Functional Programming in Scala
* [milessabin/shapeless](https://github.com/milessabin/shapeless) - Generic programming for Scala
* [twitter/util](https://github.com/twitter/util) - Wonderful reusable code from Twitter
* [fthomas/refined](https://github.com/fthomas/refined) - Refinement types for Scala
* [optics-dev/Monocle](https://github.com/optics-dev/Monocle) - Optics library for Scala
* [softwaremill/macwire](https://github.com/softwaremill/macwire) - Zero-cost, compile-time, type-safe dependency injection library.
* [scalalandio/chimney](https://github.com/scalalandio/chimney) - Scala library for boilerplate-free, type-safe data transformations
* [lloydmeta/enumeratum](https://github.com/lloydmeta/enumeratum) - A type-safe, reflection-free, powerful enumeration implementation for Scala with exhaustive pattern match warnings and helpful integrations.
* [typelevel/simulacrum](https://github.com/typelevel/simulacrum) - First class syntax support for type classes in Scala
* [softwaremill/quicklens](https://github.com/softwaremill/quicklens) - Modify deeply nested case class fields
* [precog/matryoshka](https://github.com/precog/matryoshka) - Generalized recursion schemes and traversals for Scala.
* [softwaremill/magnolia](https://github.com/softwaremill/magnolia) - Easy, fast, transparent generic derivation of typeclass instances
* [wvlet/airframe](https://github.com/wvlet/airframe) - Essential Building Blocks for Scala
* [7mind/izumi](https://github.com/7mind/izumi) - Productivity-oriented collection of lightweight fancy stuff for Scala toolchain
* [frees-io/freestyle](https://github.com/frees-io/freestyle) - A cohesive & pragmatic framework of FP centric Scala libraries
* [atnos-org/eff](https://github.com/atnos-org/eff) - Eff monad for cats - https://atnos-org.github.io/eff
* [scala-graph/scala-graph](https://github.com/scala-graph/scala-graph) - Graph for Scala is intended to provide basic graph functionality seamlessly fitting into the Scala Collection Library. Like the well known members of scala.collection, Graph for Scala is an in-memory graph library aiming at editing and traversing graphs, finding cycles etc. in a user-friendly way.
* [scalapy/scalapy](https://github.com/scalapy/scalapy) - Use the world of Python from the comfort of Scala!
* [typelevel/cats-collections](https://github.com/typelevel/cats-collections) - Data structures for pure functional programming in Scala
* [Iltotore/iron](https://github.com/Iltotore/iron) - Strong type constraints for Scala
* [com-lihaoyi/sourcecode](https://github.com/com-lihaoyi/sourcecode) - Scala library providing "source" metadata to your program, similar to Python's __name__, C++'s __LINE__ or Ruby's __FILE__.
* [jsuereth/scala-arm](https://github.com/jsuereth/scala-arm) - This project aims to be the Scala Incubator project for Automatic-Resource-Management in the scala library
* [estatico/scala-newtype](https://github.com/estatico/scala-newtype) - NewTypes for Scala with no runtime overhead
* [wix-incubator/accord](https://github.com/wix-incubator/accord) - Accord: A sane validation library for Scala
* [xebia-functional/fetch](https://github.com/xebia-functional/fetch) - Simple & Efficient data access for Scala and Scala.js
* [zio/zio-prelude](https://github.com/zio/zio-prelude) - A lightweight, distinctly Scala take on functional abstractions, with tight ZIO integration
* [arainko/ducktape](https://github.com/arainko/ducktape) - Automatic and customizable compile time transformations between similar case classes and sealed traits/enums, essentially a thing that glues your code. Scala 3 only. Or is it duct 🤔
* [scala/scala-java8-compat](https://github.com/scala/scala-java8-compat) - A Java 8 (and up) compatibility kit for Scala.
* [higherkindness/droste](https://github.com/higherkindness/droste) - recursion schemes for cats; to iterate is human, to recurse, divine
* [dickwall/subcut](https://github.com/dickwall/subcut) - Scala Uniquely Bound Classes Under Traits
* [alexandrnikitin/bloom-filter-scala](https://github.com/alexandrnikitin/bloom-filter-scala) - Bloom filter for Scala, the fastest for JVM
* [typelevel/mouse](https://github.com/typelevel/mouse) - A small companion to cats
* [softwaremill/retry](https://github.com/softwaremill/retry) - because you should never give up, at least not on the first try
* [typelevel/cats-tagless](https://github.com/typelevel/cats-tagless) - Library of utilities for tagless final encoded algebras
* [scala-hamsters/hamsters](https://github.com/scala-hamsters/hamsters) - A mini Scala utility library
* [scaldi/scaldi](https://github.com/scaldi/scaldi) - Lightweight Scala Dependency Injection Library
* [monadless/monadless](https://github.com/monadless/monadless) - Syntactic sugar for monad composition in Scala
* [non/debox](https://github.com/non/debox) - Fast, deboxed, specialized data structures for Scala
* [kailuowang/henkan](https://github.com/kailuowang/henkan) - A small library for converting between case classes.
* [kitlangton/neotype](https://github.com/kitlangton/neotype) - A friendly newtype library for Scala 3
* [ThoughtWorksInc/Dsl.scala](https://github.com/ThoughtWorksInc/Dsl.scala) - A framework to create embedded Domain-Specific Languages in Scala
* [ThoughtWorksInc/each](https://github.com/ThoughtWorksInc/each) - A macro library that converts native imperative syntax to scalaz's monadic expressions
* [zalando/grafter](https://github.com/zalando/grafter) - Grafter is a library to configure and wire Scala applications *(archived)*
* [chrisokasaki/scads](https://github.com/chrisokasaki/scads) - Scala Algorithms and Data Structures
* [scala/scala-collection-compat](https://github.com/scala/scala-collection-compat) - makes some Scala 2.13 APIs (primarily collections, also some others) available on 2.11 and 2.12, to aid cross-building
* [typelevel/shapeless-3](https://github.com/typelevel/shapeless-3) - Generic programming for Scala
* [Verizon/quiver](https://github.com/Verizon/quiver) - A reasonable library for modeling multi-graphs in Scala *(archived)*
* [avast/scala-server-toolkit](https://github.com/avast/scala-server-toolkit) - Functional programming toolkit for building server applications in Scala. *(archived)*
* [scala/collection-strawman](https://github.com/scala/collection-strawman) - Implementation of the new Scala 2.13 Collections *(archived)*
* [kenbot/goggles](https://github.com/kenbot/goggles) - Pleasant, yet principled Scala optics DSL
* [mpilquist/Structures](https://github.com/mpilquist/Structures) - Functional type classes for Scala *(archived)*
* [aztek/scala-workflow](https://github.com/aztek/scala-workflow) - Boilerplate-free syntax for computations with effects
* [frees-io/iota](https://github.com/frees-io/iota) - Fast [co]product types with a clean syntax. For Cats & Scalaz.
* [pelotom/effectful](https://github.com/pelotom/effectful) - A syntax for type-safe effectful computations in Scala
* [fwbrasil/bond](https://github.com/fwbrasil/bond) - Type-level validation for Scala
* [oleg-py/meow-mtl](https://github.com/oleg-py/meow-mtl) - Next Level MTL for Scala
* [pathikrit/sauron](https://github.com/pathikrit/sauron) - Yet another Scala lens macro
* [fthomas/singleton-ops](https://github.com/fthomas/singleton-ops) - Operations for primitive and String singleton types *(archived)*
* [scala-records/scala-records](https://github.com/scala-records/scala-records) - Labeled records for Scala based on structural refinement types and macros.
* [kubuszok/hearth](https://github.com/kubuszok/hearth) - The first Scala macros' standard library
* [theiterators/kebs](https://github.com/theiterators/kebs) - Scala library to eliminate boilerplate
* [zio/izumi-reflect](https://github.com/zio/izumi-reflect) - TypeTag without scala-reflect. Supports Scala 2 and Scala 3.
* [dwickern/scala-nameof](https://github.com/dwickern/scala-nameof) - Get the name of an variable, function, class member, or type as a string--at compile-time!
* [krzemin/octopus](https://github.com/krzemin/octopus) - Scala library for boilerplate-free validation
* [stripe/dagon](https://github.com/stripe/dagon) - Tools for rewriting and optimizing DAGs (directed-acyclic graphs) in Scala
* [b-studios/scala-effekt](https://github.com/b-studios/scala-effekt) - Extensible algebraic effects with handlers
* [davenverse/fuuid](https://github.com/davenverse/fuuid) - Functional UUID's for Scala
* [yaes-io/yaes](https://github.com/yaes-io/yaes) - A direct-style effect system in Scala 3 that tracks effects using context parameters
* [heathermiller/spores](https://github.com/heathermiller/spores) - Scala Spores, safe mobile closures.
* [softwaremill/scala-common](https://github.com/softwaremill/scala-common) - Tiny independent libraries with a single purpose, often a single class *(archived)*
* [typelevel/spotted-leopards](https://github.com/typelevel/spotted-leopards) - Proof of concept for a cats-like library built using Dotty features
* [lloydmeta/diesel](https://github.com/lloydmeta/diesel) - Boilerplate-free, zero-overhead Tagless Final / typed-final / Finally Tagless DSLs in Scala
* [propensive/soundness](https://github.com/propensive/soundness) - A platform of libraries for Scala 3
* [Thangiee/Freasy-Monad](https://github.com/Thangiee/Freasy-Monad) - Easy way to create Free Monad using Scala macros with first-class Intellij support.
* [scala-interop/slinc](https://github.com/scala-interop/slinc) - Scala <-> C interop
* [scala/scala-collection-contrib](https://github.com/scala/scala-collection-contrib) - community-contributed additions to the Scala 2.13 collections
* [scala-tsi/scala-tsi](https://github.com/scala-tsi/scala-tsi) - Generate typescript interfaces from your scala classes
* [sisioh/scala-dddbase](https://github.com/sisioh/scala-dddbase) - Scala Library for Domain Driven-Design *(archived)*
* [rudogma/scala-supertagged](https://github.com/rudogma/scala-supertagged) - Unboxed (multi-nested-)tagged + unboxed newtypes. Better and much friendlier alternative to AnyVals.
* [rklaehn/radixtree](https://github.com/rklaehn/radixtree) - A fast and generic immutable radix tree for scala
* [denisrosset/metal](https://github.com/denisrosset/metal) - Metal - fast unboxed data structures for Scala
* [bfil/scala-automapper](https://github.com/bfil/scala-automapper) - Hassle-free case class mapping!
* [bmc/classutil](https://github.com/bmc/classutil) - Scala-friendly, fast class-finder library (using ASM under the covers)
* [kailuowang/mainecoon](https://github.com/kailuowang/mainecoon) - Transform and compose tagless final encoded algebras in scala *(archived)*
* [akisaarinen/rillit](https://github.com/akisaarinen/rillit) - Boilerplate-free Functional Lenses for Scala 2.10
* [vivri/Adjective](https://github.com/vivri/Adjective) - Programming is an exercise in linguistics; spice-up Scala types with Adjective.
* [w11k/scalamodules](https://github.com/w11k/scalamodules) - ScalaModules is an elegant and intuitive domain specific language for OSGi development written in the Scala programming language. *(archived)*
* [bmc/grizzled-scala](https://github.com/bmc/grizzled-scala) - A general-purpose library of miscellaneous stuff for Scala.
* [rklaehn/abc](https://github.com/rklaehn/abc) - Array-based immutable collections for scala

## Science and Math

### Mathematics

* [scalanlp/breeze](https://github.com/scalanlp/breeze) - Breeze is/was a numerical processing library for Scala.
* [twitter/algebird](https://github.com/twitter/algebird) - Abstract Algebra for Scala
* [typelevel/spire](https://github.com/typelevel/spire) - Powerful new number types and numeric abstractions for Scala.
* [typelevel/squants](https://github.com/typelevel/squants) - The Scala API for Quantities, Units of Measure and Dimensional Analysis
* [stripe/rainier](https://github.com/stripe/rainier) - Bayesian inference in Scala.
* [typelevel/algebra](https://github.com/typelevel/algebra) - Experimental project to lay out basic algebra type classes *(archived)*
* [scalala/Scalala](https://github.com/scalala/Scalala) - Scalala has been superseded by dlwh/breeze. Scalala is a high performance numeric linear algebra library for Scala, with rich Matlab-like operators on vectors and matrices; a library of numerical routines; support for plotting.
* [erikerlandson/coulomb](https://github.com/erikerlandson/coulomb) - coulomb: unit analysis for Scala
* [vagmcs/Optimus](https://github.com/vagmcs/Optimus) - Optimus is a mathematical programming library for Scala.
* [neysofu/tyche](https://github.com/neysofu/tyche) - Statistics utilities for the JVM - in Scala!
* [runarorama/Malakov](https://github.com/runarorama/Malakov) - Markov Chains for Scala

### Scientific Computing

* [chipsalliance/rocket-chip](https://github.com/chipsalliance/rocket-chip) - Rocket Chip Generator
* [riscv-boom/riscv-boom](https://github.com/riscv-boom/riscv-boom) - SonicBOOM: The Berkeley Out-of-Order Machine
* [broadinstitute/cromwell](https://github.com/broadinstitute/cromwell) - Scientific workflow engine designed for simplicity & scalability. Trivially transition between one off use cases to massive scale production environments
* [bigdatagenomics/adam](https://github.com/bigdatagenomics/adam) - ADAM is a genomics analysis platform with specialized file formats built using Apache Avro, Apache Spark, and Apache Parquet. Apache 2 licensed.
* [tensil-ai/tensil](https://github.com/tensil-ai/tensil) - Open source machine learning accelerators *(archived)*
* [fulcrumgenomics/fgbio](https://github.com/fulcrumgenomics/fgbio) - Tools for working with genomic and high throughput sequencing data.
* [ThoughtWorksInc/Compute.scala](https://github.com/ThoughtWorksInc/Compute.scala) - Scientific computing with N-dimensional arrays
* [ucsc-vama/essent](https://github.com/ucsc-vama/essent) - high-performance RTL simulator
* [eryk/squant](https://github.com/eryk/squant) - SQuant是使用scala语言编写的量化开发工具箱，提供开箱即用的A股股票数据和外汇数据（docker镜像），以及高效的回测框架与交易模块。方便Java/Scala爱好者进行量化投资研究。 QQ群：281599099，微信公众号：Python量化交易实战。对，我已经转python了。。。
* [openmole/openmole](https://github.com/openmole/openmole) - Workflow engine for exploration of simulation models using high throughput computing
* [sterglee/scalalab](https://github.com/sterglee/scalalab) - ScalaLab: Efficient MATLAB like scientific computing for the Java platform with the current Scala 2.13. For Scala 3 the equivalent project is dottylab: https://github.com/sterglee/dottylab
* [bioscala/bioscala](https://github.com/bioscala/bioscala) - Bioinformatics for the Scala programming language

### Formal Methods and Proofs

* [epfl-lara/stainless](https://github.com/epfl-lara/stainless) - Verification framework and tool for higher-order Scala programs. https://gitlab.epfl.ch/lara/stainless
* [Chymyst/curryhoward](https://github.com/Chymyst/curryhoward) - Automatic code generation for Scala functions and expressions via the Curry-Howard isomorphism
* [TyGuS/suslik](https://github.com/TyGuS/suslik) - Synthesis of Heap-Manipulating Programs from Separation Logic
* [epfl-lara/ScalaZ3](https://github.com/epfl-lara/ScalaZ3) - DSL in Scala for Constraint Solving with Z3 SMT Solver
* [gapt/gapt](https://github.com/gapt/gapt) - GAPT: General Architecture for Proof Theory

## Other

* [twitter/the-algorithm](https://github.com/twitter/the-algorithm) - Source code for the X Recommendation Algorithm
* [prisma/prisma1](https://github.com/prisma/prisma1) - 💾 Database Tools incl. ORM, Migrations and Admin UI (Postgres, MySQL & MongoDB) [deprecated] *(archived)*
* [akka/akka-core](https://github.com/akka/akka-core) - A platform to build and run apps that are elastic, agile, and resilient. SDK, libraries, and hosted environments.
* [lk-geimfari/awesomo](https://github.com/lk-geimfari/awesomo) - Cool open source projects. Choose your project and get involved in Open Source development now.
* [delta-io/delta](https://github.com/delta-io/delta) - An open-source storage framework that enables building a Lakehouse architecture with compute engines including Spark, PrestoDB, Flink, Trino, and Hive and APIs
* [twitter-archive/snowflake](https://github.com/twitter-archive/snowflake) - Snowflake is a network service for generating unique ID numbers at high scale with some simple guarantees. *(archived)*
* [OpenXiangShan/XiangShan](https://github.com/OpenXiangShan/XiangShan) - Open-source high-performance RISC-V processor
* [snowplow/snowplow](https://github.com/snowplow/snowplow) - The leader in Customer Data Infrastructure
* [lhartikk/ArnoldC](https://github.com/lhartikk/ArnoldC) - Arnold Schwarzenegger based programming language
* [apache/openwhisk](https://github.com/apache/openwhisk) - Apache OpenWhisk is an open source serverless cloud platform
* [guardian/frontend](https://github.com/guardian/frontend) - The Guardian DotCom.
* [typelevel/cats](https://github.com/typelevel/cats) - Lightweight, modular, and extensible library for functional programming.
* [linkerd/linkerd](https://github.com/linkerd/linkerd) - Old repo for Linkerd 1.x. See the linkerd2 repo for Linkerd 2.x.
* [airbnb/aerosolve](https://github.com/airbnb/aerosolve) - A machine learning package built for humans.
* [mesos/chronos](https://github.com/mesos/chronos) - Fault tolerant job scheduler for Mesos which handles dependencies and ISO8601 based schedules
* [JohnSnowLabs/spark-nlp](https://github.com/JohnSnowLabs/spark-nlp) - State of the Art Natural Language Processing
* [d2iq-archive/marathon](https://github.com/d2iq-archive/marathon) - Deploy and manage containers (including Docker) on top of Apache Mesos at scale. *(archived)*
* [twitter-archive/diffy](https://github.com/twitter-archive/diffy) - Find potential bugs in your services with Diffy *(archived)*
* [Netflix/atlas](https://github.com/Netflix/atlas) - In-memory dimensional time series database.
* [lw-lin/CoolplaySpark](https://github.com/lw-lin/CoolplaySpark) - 酷玩 Spark: Spark 源代码解析、Spark 类库等
* [twitter-archive/flockdb](https://github.com/twitter-archive/flockdb) - A distributed, fault-tolerant graph database *(archived)*
* [databricks/Spark-The-Definitive-Guide](https://github.com/databricks/Spark-The-Definitive-Guide) - Spark: The Definitive Guide's Code Repository
* [twitter-archive/kestrel](https://github.com/twitter-archive/kestrel) - simple, distributed message queue system (inactive) *(archived)*
* [aditya-grover/node2vec](https://github.com/aditya-grover/node2vec)
* [ucb-bar/chipyard](https://github.com/ucb-bar/chipyard) - An Agile RISC-V SoC Design Framework with in-order cores, out-of-order cores, accelerators, and more
* [apache/kyuubi](https://github.com/apache/kyuubi) - Apache Kyuubi is a distributed and multi-tenant gateway to provide serverless SQL on data warehouses and lakehouses.
* [twitter-archive/gizzard](https://github.com/twitter-archive/gizzard) - [Archived] A flexible sharding framework for creating eventually-consistent distributed datastores *(archived)*
* [laurilehmijoki/s3_website](https://github.com/laurilehmijoki/s3_website) - Manage an S3 website: sync, deliver via CloudFront, benefit from advanced S3 website features.
* [twitter/summingbird](https://github.com/twitter/summingbird) - Streaming MapReduce with Scalding and Storm *(archived)*
* [pocorall/scaloid](https://github.com/pocorall/scaloid) - Scaloid makes your Android code easy to understand and maintain.
* [ValeLang/Vale](https://github.com/ValeLang/Vale) - Compiler for the Vale programming language - http://vale.dev/
* [MojoJolo/textteaser](https://github.com/MojoJolo/textteaser) - TextTeaser is an automatic summarization algorithm.
* [feathr-ai/feathr](https://github.com/feathr-ai/feathr) - Feathr – A scalable, unified data and AI engineering platform for enterprise
* [byzer-org/byzer-lang](https://github.com/byzer-org/byzer-lang) - Byzer (former MLSQL): A low-code open-source programming language for data pipeline, analytics and AI.
* [Graphcool/graphcool-framework](https://github.com/Graphcool/graphcool-framework) - *(archived)*
* [OpenBankProject/OBP-API](https://github.com/OpenBankProject/OBP-API) - An open source RESTful API platform for banks that supports Open Banking, XS2A, PSD2 and Open Finance through access to accounts, transactions, counterparties, payments, entitlements and metadata - plus a host of internal banking and management APIs.
* [twitter/twitter-server](https://github.com/twitter/twitter-server) - Twitter-Server defines a template from which services at Twitter are built
* [apache/gluten](https://github.com/apache/gluten) - Gluten is a middle layer responsible for offloading JVM-based SQL engines' execution to native engines.
* [holdenk/spark-testing-base](https://github.com/holdenk/spark-testing-base) - Base classes to use when writing tests with Spark
* [OSCPU/NutShell](https://github.com/OSCPU/NutShell) - RISC-V SoC designed by students in UCAS
* [GravityLabs/goose](https://github.com/GravityLabs/goose) - Html Content / Article Extractor in Scala - open sourced from Gravity Labs *(archived)*
* [sryza/aas](https://github.com/sryza/aas) - Code to accompany Advanced Analytics with Spark from O'Reilly Media
* [smallnest/C1000K-Servers](https://github.com/smallnest/C1000K-Servers) - :zap: High performance websocket servers implemented by Spray-can, Netty, undertow, jetty, Vert.x, Grizzly, node.js and Go. It supports 1,200,000 active websocket connections *(archived)*
* [locationtech/geomesa](https://github.com/locationtech/geomesa) - GeoMesa is a suite of tools for working with big geo-spatial data in a distributed fashion.
* [guardian/grid](https://github.com/guardian/grid) - The Guardian’s image management system
* [ucb-bar/gemmini](https://github.com/ucb-bar/gemmini) - Berkeley's Spatial Array Generator
* [paypal/squbs](https://github.com/paypal/squbs) - Akka Streams & Akka HTTP for Large-Scale Production Deployments
* [databricks/LearningSparkV2](https://github.com/databricks/LearningSparkV2) - This is the github repo for Learning Spark: Lightning-Fast Data Analytics [2nd Edition]
* [tensorflow/ecosystem](https://github.com/tensorflow/ecosystem) - Integration of TensorFlow with other open-source frameworks *(archived)*
* [locationtech/geotrellis](https://github.com/locationtech/geotrellis) - GeoTrellis is a geographic data processing engine for high performance applications.
* [akka/akka-http](https://github.com/akka/akka-http) - The Streaming-first HTTP server/module of Akka
* [twitter-archive/iago](https://github.com/twitter-archive/iago) - A load generator, built for engineers *(archived)*
* [rikvdkleij/intellij-haskell](https://github.com/rikvdkleij/intellij-haskell) - IntelliJ plugin for Haskell *(archived)*
* [apache/datafusion-comet](https://github.com/apache/datafusion-comet) - Apache DataFusion Comet Spark Accelerator
* [graphframes/graphframes](https://github.com/graphframes/graphframes) - GraphFrames is a package for Apache Spark which provides DataFrame-based Graphs
* [sryza/spark-timeseries](https://github.com/sryza/spark-timeseries) - A library for time series analysis on Apache Spark
* [jaliss/securesocial](https://github.com/jaliss/securesocial) - A module that provides OAuth, OAuth2 and OpenID authentication for Play Framework applications
* [NetLogo/NetLogo](https://github.com/NetLogo/NetLogo) - turtles, patches, and links for kids, teachers, and scientists
* [twosigma/flint](https://github.com/twosigma/flint) - A Time Series Library for Apache Spark
* [killrweather/killrweather](https://github.com/killrweather/killrweather) - KillrWeather is a reference application (work in progress) showing how to easily integrate streaming and batch data processing with Apache Spark Streaming, Apache Cassandra, Apache Kafka and Akka for fast, streaming computations on time series data in asynchronous event-driven environments.
* [apache/griffin](https://github.com/apache/griffin) - Mirror of Apache griffin *(archived)*
* [sifive/freedom](https://github.com/sifive/freedom) - Source files for SiFive's Freedom platforms *(archived)*
* [lensesio/stream-reactor](https://github.com/lensesio/stream-reactor) - A collection of Kafka Connect sinks and sources maintained by Lenses.io.
* [mpeltonen/sbt-idea](https://github.com/mpeltonen/sbt-idea) - A simple-build-tool (sbt) plugin/processor for creating IntelliJ IDEA project files
* [databricks/spark-csv](https://github.com/databricks/spark-csv) - CSV Data Source for Apache Spark 1.x *(archived)*
* [twitter/cassovary](https://github.com/twitter/cassovary) - Cassovary is a simple big graph processing library for the JVM
* [airbnb/chronon](https://github.com/airbnb/chronon) - Chronon is a data platform for serving for AI/ML applications.
* [firesim/firesim](https://github.com/firesim/firesim) - FireSim: Fast and Effortless FPGA-accelerated Hardware Simulation with On-Prem and Cloud Flexibility
* [TIBCOSoftware/snappydata](https://github.com/TIBCOSoftware/snappydata) - Project SnappyData - memory optimized analytics database, based on Apache Spark™ and Apache Geode™. Stream, Transact, Analyze, Predict in one cluster
* [cloudera/livy](https://github.com/cloudera/livy) - Livy is an open source REST interface for interacting with Apache Spark from anywhere
* [NVIDIA/cudf-spark](https://github.com/NVIDIA/cudf-spark) - NVIDIA cuDF for Apache Spark plugin - accelerate Apache Spark with GPUs
* [amplab/shark](https://github.com/amplab/shark) - Development in Shark has been ended.
* [apache/livy](https://github.com/apache/livy) - Apache Livy is an open source REST interface for interacting with Apache Spark from anywhere.
* [delta-io/delta-sharing](https://github.com/delta-io/delta-sharing) - An open protocol for secure data sharing
* [sscarduzio/elasticsearch-readonlyrest-plugin](https://github.com/sscarduzio/elasticsearch-readonlyrest-plugin) - Free Elasticsearch security plugin and Kibana security plugin: super-easy Kibana multi-tenancy, Encryption, Authentication, Authorization, Auditing
* [RedisLabs/spark-redis](https://github.com/RedisLabs/spark-redis) - A connector for Spark that allows reading and writing to/from Redis cluster
* [dbpedia/extraction-framework](https://github.com/dbpedia/extraction-framework) - The software used to extract structured data from Wikipedia
* [THU-DSP-LAB/ventus-gpgpu](https://github.com/THU-DSP-LAB/ventus-gpgpu) - GPGPU processor supporting RISCV-V extension, developed with Chisel HDL
* [elipsitz/gamebub](https://github.com/elipsitz/gamebub) - Open-source FPGA retro emulation handheld
* [typelevel/kind-projector](https://github.com/typelevel/kind-projector) - Compiler plugin for making type lambdas (type projections) easier to write
* [BIDData/BIDMach](https://github.com/BIDData/BIDMach) - CPU and GPU-accelerated Machine Learning Library
* [twitter/twitter-korean-text](https://github.com/twitter/twitter-korean-text) - Korean tokenizer
* [pingcap/tispark](https://github.com/pingcap/tispark) - TiSpark is built for running Apache Spark on top of TiDB/TiKV
* [LucaCanali/sparkMeasure](https://github.com/LucaCanali/sparkMeasure) - This repository contains the development code for sparkMeasure, an Apache Spark performance analysis and troubleshooting library. It simplifies collecting, aggregating, and exporting Spark task/stage metrics, and is designed for practical use by developers and data engineers in interactive analysis, testing, and production monitoring workflows.
* [XiaoMi/MiNLP](https://github.com/XiaoMi/MiNLP) - XiaoMi Natural Language Processing Toolkits
* [akka/akka-samples](https://github.com/akka/akka-samples) - Akka Sample Projects *(archived)*
* [fehmicansaglam/progressed.io](https://github.com/fehmicansaglam/progressed.io) - progressbar microservice *(archived)*
* [mrpowers-io/spark-daria](https://github.com/mrpowers-io/spark-daria) - Essential Spark extensions and helper methods ✨😲
* [cloudstateio/cloudstate](https://github.com/cloudstateio/cloudstate) - Distributed State Management for Serverless *(archived)*
* [dbpedia-spotlight/dbpedia-spotlight](https://github.com/dbpedia-spotlight/dbpedia-spotlight) - DBpedia Spotlight is a tool for automatically annotating mentions of DBpedia resources in text. *(archived)*
* [ucb-bar/chisel-tutorial](https://github.com/ucb-bar/chisel-tutorial) - chisel tutorial exercises and answers
* [allenai/pdffigures2](https://github.com/allenai/pdffigures2) - Given a scholarly PDF, extract figures, tables, captions, and section titles.
* [ucb-bar/riscv-sodor](https://github.com/ucb-bar/riscv-sodor) - educational microarchitectures for risc-v isa
* [apache/incubator-toree](https://github.com/apache/incubator-toree) - Mirror of Apache Toree (Incubating)
* [chipsalliance/firrtl](https://github.com/chipsalliance/firrtl) - Flexible Intermediate Representation for RTL *(archived)*
* [RayRoestenburg/akka-in-action](https://github.com/RayRoestenburg/akka-in-action) - Accompanying source code for akka in action
* [ezhulenev/orderbook-dynamics](https://github.com/ezhulenev/orderbook-dynamics) - Modeling high-frequency limit order book dynamics with support vector machines
* [gregdurrett/berkeley-doc-summarizer](https://github.com/gregdurrett/berkeley-doc-summarizer) - The Berkeley Document Summarizer is a learning-based, single-document summarization system that extracts source document content, exploits syntactic information to compress it, and uses coreference constraints to ensure clarity.
* [databricks/tensorframes](https://github.com/databricks/tensorframes) - [DEPRECATED] Tensorflow wrapper for DataFrames on Apache Spark
* [ruippeixotog/scala-scraper](https://github.com/ruippeixotog/scala-scraper) - A Scala library for scraping content from HTML pages
* [sbt/sbt-eclipse](https://github.com/sbt/sbt-eclipse) - Plugin for sbt to create Eclipse project definitions
* [Normation/rudder](https://github.com/Normation/rudder) - Rudder is a configuration and security automation platform. Manage your Cloud, hybrid or on-premises infrastructure in a simple, scalable and dynamic way.
* [RBMHTechnology/eventuate](https://github.com/RBMHTechnology/eventuate) - Global-scale event sourcing and event collaboration with causal consistency (This project is in maintenance mode. Only critical bugs will be fixed, but there is no more feature development.). *(archived)*
* [scalafx/scalafx](https://github.com/scalafx/scalafx) - ScalaFX simplifies creation of JavaFX-based user interfaces in Scala
* [CSUG/HouseMD](https://github.com/CSUG/HouseMD) - HouseMD is an awesome diagnosing tool better than BTrace *(archived)*
* [rchain/rchain](https://github.com/rchain/rchain) - Blockchain (smart contract) platform using CBC-Casper proof of stake + Rholang for concurrent execution.
* [TalkingData/Fregata](https://github.com/TalkingData/Fregata) - A light weight, super fast, large scale machine learning library on spark .
* [actionml/universal-recommender](https://github.com/actionml/universal-recommender) - Highly configurable recommender based on PredictionIO and Mahout's Correlated Cross-Occurrence algorithm
* [open-korean-text/open-korean-text](https://github.com/open-korean-text/open-korean-text) - Open Korean Text Processor - An Open-source Korean Text Processor
* [seglo/kafka-lag-exporter](https://github.com/seglo/kafka-lag-exporter) - Monitor Kafka Consumer Group Latency with Kafka Lag Exporter *(archived)*
* [sameeragarwal/blinkdb](https://github.com/sameeragarwal/blinkdb) - BlinkDB: Sub-Second Approximate Queries on Very Large Data.
* [twitter/bijection](https://github.com/twitter/bijection) - Reversible conversions between types
* [scoverage/sbt-scoverage](https://github.com/scoverage/sbt-scoverage) - sbt plugin for scoverage
* [databricks/reference-apps](https://github.com/databricks/reference-apps) - Spark reference applications
* [softwaremill/codebrag](https://github.com/softwaremill/codebrag) - Your daily code review tool *(archived)*
* [chandu0101/sri](https://github.com/chandu0101/sri) - Build truly native cross platform (web,ios,android) apps using scalajs and react, react-native
* [CircleCI-Archived/vamp](https://github.com/CircleCI-Archived/vamp) - Vamp - canary releasing and autoscaling for microservice systems *(archived)*
* [ucb-bar/riscv-mini](https://github.com/ucb-bar/riscv-mini) - Simple RISC-V 3-stage Pipeline in Chisel *(archived)*
* [nixiesearch/nixiesearch](https://github.com/nixiesearch/nixiesearch) - Hybrid search engine, combining best features of text and semantic search worlds
* [amplab/SparkNet](https://github.com/amplab/SparkNet) - Distributed Neural Networks for Spark
* [MethodJiao/PkpmSpark](https://github.com/MethodJiao/PkpmSpark) - awesome 三维数据挖掘 数据分析 & 推荐
* [databricks/spark-redshift](https://github.com/databricks/spark-redshift) - Redshift data source for Apache Spark
* [t2v/play2-auth](https://github.com/t2v/play2-auth) - Play2.x Authentication and Authorization module
* [ge0rg/aprsdroid](https://github.com/ge0rg/aprsdroid) - APRSdroid - Geo-Location for Radio Amateurs
* [apalache-mc/apalache](https://github.com/apalache-mc/apalache) - APALACHE: symbolic model checker for TLA+ and Quint
* [ShiftLeftSecurity/codepropertygraph](https://github.com/ShiftLeftSecurity/codepropertygraph) - Code Property Graph: specification, query language, and utilities
* [xubo245/SparkLearning](https://github.com/xubo245/SparkLearning) - Learning Apache spark,including code and data .Most part can run local.
* [qubole/sparklens](https://github.com/qubole/sparklens) - Qubole Sparklens tool for performance tuning Apache Spark
* [stanch/reftree](https://github.com/stanch/reftree) - Automatically generated diagrams and animations for Scala data structures
* [tumblr/collins](https://github.com/tumblr/collins) - groovy kind of love
* [apicollective/apibuilder](https://github.com/apicollective/apibuilder) - Simple, Comprehensive Tooling for Modern APIs
* [Netflix/edda](https://github.com/Netflix/edda) - AWS API Read Cache
* [Yubico/java-webauthn-server](https://github.com/Yubico/java-webauthn-server) - Server-side Web Authentication library for Java https://www.w3.org/TR/webauthn/#rp-operations
* [enragedginger/akka-quartz-scheduler](https://github.com/enragedginger/akka-quartz-scheduler) - Quartz Extension and utilities for cron-style scheduling in Akka
* [sbt/sbt-buildinfo](https://github.com/sbt/sbt-buildinfo) - I know this because build.sbt knows this.
* [Interana/eventsim](https://github.com/Interana/eventsim) - Event data simulator. Generates a stream of pseudo-random events from a set of users, designed to simulate web traffic.
* [WhatsApp/eqwalizer](https://github.com/WhatsApp/eqwalizer) - A type-checker for Erlang *(archived)*
* [hortonworks-spark/shc](https://github.com/hortonworks-spark/shc) - The Apache Spark - Apache HBase Connector is a library to support Spark accessing HBase table as external data source or sink.
* [orbeon/orbeon-forms](https://github.com/orbeon/orbeon-forms) - Orbeon Forms - Build, run, and manage web forms on-premises or in the cloud.
* [typelevel/kittens](https://github.com/typelevel/kittens) - Automatic type class derivation for Cats
* [tofu-tf/tofu](https://github.com/tofu-tf/tofu) - Functional programming toolbox
* [databricks/spark-avro](https://github.com/databricks/spark-avro) - Avro Data Source for Apache Spark *(archived)*
* [high-performance-spark/high-performance-spark-examples](https://github.com/high-performance-spark/high-performance-spark-examples) - Examples for High Performance Spark
* [harsha2010/magellan](https://github.com/harsha2010/magellan) - Geo Spatial Data Analytics on Spark
* [struppigel/PortEx](https://github.com/struppigel/PortEx) - Java library to analyse Portable Executable files with a special focus on malware analysis and PE malformation robustness
* [xebia-functional/macroid](https://github.com/xebia-functional/macroid) - A modular functional UI language for Android *(archived)*
* [ergoplatform/ergo](https://github.com/ergoplatform/ergo) - Ergo protocol description & reference client implementation
* [druid-io/tranquility](https://github.com/druid-io/tranquility) - Tranquility helps you send real-time event streams to Druid and handles partitioning, replication, service discovery, and schema rollover, seamlessly and without downtime.
* [databricks/spark-xml](https://github.com/databricks/spark-xml) - XML data source for Spark SQL and DataFrames *(archived)*
* [mongodb/casbah](https://github.com/mongodb/casbah) - Casbah is now officially end-of-life (EOL). *(archived)*
* [stephenmcd/curiodb](https://github.com/stephenmcd/curiodb) - Distributed NoSQL Database
* [shafiab/HashtagCashtag](https://github.com/shafiab/HashtagCashtag) - My Insight Data Engineering Fellowship project. I implemented a big data processing pipeline based on ​lambda architecture​, that aggregates Twitter and US stock market data for user sentiment analysis using open source tools - ​Apache Kafka ​for data ingestions, Apache Spark ​& ​Spark Streaming ​for batch & real-time processing, ​Apache Cassandra f​ or storage, ​Flask​, ​Bootstrap and ​HighCharts f​ or frontend.
* [huawei-noah/streamDM](https://github.com/huawei-noah/streamDM) - Stream Data Mining Library for Spark Streaming
* [Alkaar/resy-booking-bot](https://github.com/Alkaar/resy-booking-bot) - 🔫 Helps to snipe hard to get reservations at restaurants that use resy
* [foursquare/rogue](https://github.com/foursquare/rogue) - MOVED - The project is still under development but this page is deprecated.
* [salat/salat](https://github.com/salat/salat) - Salat is a simple serialization library for case classes. *(archived)*
* [topshell-language/topshell](https://github.com/topshell-language/topshell) - TopShell - a purely functional, reactive scripting language
* [amplab/keystone](https://github.com/amplab/keystone) - Simplifying robust end-to-end machine learning on Apache Spark.
* [dlwh/epic](https://github.com/dlwh/epic) - **Archived** Epic is a high performance statistical parser written in Scala, along with a framework for building complex structured prediction models. *(archived)*
* [knowitall/openie](https://github.com/knowitall/openie) - Quality information extraction at web scale.
* [debasishg/frdomain](https://github.com/debasishg/frdomain) - Code repo for Functional and Reactive Domain Modeling
* [twitter/storehaus](https://github.com/twitter/storehaus) - Storehaus is a library that makes it easy to work with asynchronous key value stores
* [effekt-lang/effekt](https://github.com/effekt-lang/effekt) - A language with lexical effect handlers and lightweight effect polymorphism
* [spring-attic/spring-scala](https://github.com/spring-attic/spring-scala) - *(archived)*
* [mrpowers-io/spark-fast-tests](https://github.com/mrpowers-io/spark-fast-tests) - Apache Spark testing helpers (dependency free & works with Scalatest, uTest, and MUnit)
* [Centaur/repox](https://github.com/Centaur/repox) - Make sbt more responsive
* [lucidworks/spark-solr](https://github.com/lucidworks/spark-solr) - Tools for reading data from Solr as a Spark RDD and indexing objects from Spark into Solr using SolrJ.
* [play2war/play2-war-plugin](https://github.com/play2war/play2-war-plugin) - WAR Plugin for Play framework 2.x *(archived)*
* [foursquare/twofishes](https://github.com/foursquare/twofishes) - MOVED - The project is still under development but this page is deprecated.
* [librecaptcha/lc-core](https://github.com/librecaptcha/lc-core) - The LibreCaptcha framework, for self-hosted, privacy respecting CAPTCHAs
* [microsoft/hyperspace](https://github.com/microsoft/hyperspace) - An open source indexing subsystem that brings index-based query acceleration to Apache Spark™ and big data workloads. *(archived)*
* [mardambey/mypipe](https://github.com/mardambey/mypipe) - MySQL binary log consumer with the ability to act on changed rows and publish changes to different systems with emphasis on Apache Kafka.
* [embeddedkafka/embedded-kafka](https://github.com/embeddedkafka/embedded-kafka) - A library that provides an in-memory Kafka instance to run your tests against.
* [typelevel/log4cats](https://github.com/typelevel/log4cats) - Logging Tools For Interaction with cats-effect
* [IRS-Public/fact-graph](https://github.com/IRS-Public/fact-graph) - Fact Graph
* [mesos/kafka](https://github.com/mesos/kafka) - Apache Kafka on Apache Mesos
* [spray/spray-template](https://github.com/spray/spray-template) - SBT template project for quickly getting started with spray-server
* [philwantsfish/shard](https://github.com/philwantsfish/shard) - A command line tool to detect shared passwords
* [precog/platform](https://github.com/precog/platform) - Advanced Analytics Engine for NoSQL Data *(archived)*
* [pierre94/flink-notes](https://github.com/pierre94/flink-notes) - flink学习笔记
* [uber-archive/sql-differential-privacy](https://github.com/uber-archive/sql-differential-privacy) - Dataflow analysis & differential privacy for SQL queries. This project is deprecated and not maintained. *(archived)*
* [databricks/spark-training](https://github.com/databricks/spark-training) - Apache Spark training material *(archived)*
* [alexklibisz/elastiknn](https://github.com/alexklibisz/elastiknn) - Elasticsearch plugin for nearest neighbor search. Store vectors and run similarity search using exact and approximate algorithms.
* [gtache/intellij-lsp](https://github.com/gtache/intellij-lsp) - Plugin adding Language Server Protocol support for IntelliJ *(archived)*
* [findify/s3mock](https://github.com/findify/s3mock) - Embedded S3 server for easy mocking *(archived)*
* [ucb-bar/berkeley-hardfloat](https://github.com/ucb-bar/berkeley-hardfloat)
* [broadinstitute/pilon](https://github.com/broadinstitute/pilon) - Pilon is an automated genome assembly improvement and variant detection tool
* [rhavyn/norbert](https://github.com/rhavyn/norbert) - Norbert is a cluster manager and networking layer built on top of Zookeeper.
* [ucb-bar/chisel2-deprecated](https://github.com/ucb-bar/chisel2-deprecated)
* [allenai/ScienceWorld](https://github.com/allenai/ScienceWorld) - ScienceWorld is a text-based virtual environment centered around accomplishing tasks from the standardized elementary science curriculum.
* [luochana/News_recommend](https://github.com/luochana/News_recommend) - 基于Spark的新闻推荐系统，包含爬虫项目、web网站以及spark推荐系统
* [webjars/webjars](https://github.com/webjars/webjars) - Client-side web libraries packaged into JARs
* [velvia/links](https://github.com/velvia/links) - Just a bunch of useful links
* [earldouglas/sbt-war](https://github.com/earldouglas/sbt-war) - Package and run WAR files from sbt
* [Netflix/osstracker](https://github.com/Netflix/osstracker) - Github organization OSS metrics collector and metrics dashboard
* [pawelkaczor/ddd-leaven-akka-v2](https://github.com/pawelkaczor/ddd-leaven-akka-v2) - Sample e-commerce system #Microservices #Akka #Reactive-DDD #CQRS
* [ray-project/raydp](https://github.com/ray-project/raydp) - RayDP provides simple APIs for running Spark on Ray and integrating Spark with AI libraries.
* [sbt/sbt-web](https://github.com/sbt/sbt-web) - Library for building sbt plugins for the web
* [conduktor/kafka-security-manager](https://github.com/conduktor/kafka-security-manager) - Manage your Kafka ACL at scale
* [http4s/blaze](https://github.com/http4s/blaze) - Blazing fast NIO microframework and Http Parser
* [suzaku-io/boopickle](https://github.com/suzaku-io/boopickle) - Binary serialization library for efficient network communication
* [zio/zio-kafka](https://github.com/zio/zio-kafka) - A fast Kafka client for ZIO and ZIO Streams
* [nylonee/watchlistarr](https://github.com/nylonee/watchlistarr) - Customizable sync of Plex Watchlist to Sonarr/Radarr
* [nymanjens/facto](https://github.com/nymanjens/facto) - Family Accounting Tool
* [apache/tvm-vta](https://github.com/apache/tvm-vta) - Open, Modular, Deep Learning Accelerator
* [peregin/gps-overlay-on-video](https://github.com/peregin/gps-overlay-on-video) - Telemetry (GPS) data overlay on videos
* [pawelkaczor/akka-ddd](https://github.com/pawelkaczor/akka-ddd) - Akka CQRS/ES framework
* [amplab/graphx](https://github.com/amplab/graphx) - Former GraphX development repository. GraphX has been merged into Apache Spark; please submit pull requests there.
* [arhelmus/akka-http-rest](https://github.com/arhelmus/akka-http-rest) - Example of reactive REST service written on akka-http with slick
* [inanna-malick/akka-streams-example](https://github.com/inanna-malick/akka-streams-example)
* [sbt/sbt-git](https://github.com/sbt/sbt-git) - A git plugin for sbt
* [vinyldns/vinyldns](https://github.com/vinyldns/vinyldns) - DNS automation and governance for streamlining DNS operations and enabling safe and secure DNS self-service
* [jmcardon/tsec](https://github.com/jmcardon/tsec) - Type-safe general-cryptography library - https://jmcardon.github.io/tsec/ *(archived)*
* [creativescala/doodle](https://github.com/creativescala/doodle) - Compositional vector graphics in Scala / Scala.JS
* [baolibin/Bigdata](https://github.com/baolibin/Bigdata) - 大数据处理相关技术学习之路(持续更新中...)。 Bigdata整理 --> 慢慢滴~ 大数据相关技术包括离线处理，实时处理，OLAP等，如hadoop、spark、flink、hive、hbase、oozie...以及大数据项目，如用户画像、数据仓库等，欢迎感兴趣的小伙伴一起来开发...
* [datamechanics/delight](https://github.com/datamechanics/delight) - A Spark UI and Spark History Server alternative with CPU and Memory metrics! Delight is free, cross-platform, and open-source. *(archived)*
* [boundary/ordasity](https://github.com/boundary/ordasity) - Ordasity is Boundary's library for building stateful clustered services on the JVM.
* [derrickburns/generalized-kmeans-clustering](https://github.com/derrickburns/generalized-kmeans-clustering) - Production-ready K-Means clustering for Apache Spark with pluggable Bregman divergences (KL, Itakura-Saito, L1, etc). 6 algorithms, 740 tests, cross-version persistence. Drop-in replacement for MLlib with mathematically correct distance functions for probability distributions, spectral data, and count data.
* [scalanlp/nak](https://github.com/scalanlp/nak) - The Nak Machine Learning Library
* [Ldpe2G/DeepLearningForFun](https://github.com/Ldpe2G/DeepLearningForFun) - Implementation of some interesting ideas of deeplearning.
* [apache/bahir](https://github.com/apache/bahir) - Mirror of Apache Bahir *(archived)*
* [jamesward/koober](https://github.com/jamesward/koober)
* [TiarkRompf/virtualization-lms-core](https://github.com/TiarkRompf/virtualization-lms-core) - A Framework for Runtime Code Generation and Compiled DSLs
* [allenai/openie-standalone](https://github.com/allenai/openie-standalone) - Quality information extraction at web scale. Edit
* [EcZachly/little-book-of-pipelines](https://github.com/EcZachly/little-book-of-pipelines) - This repository goes over how to handle massive variety in data engineering
* [lightbend/cloudflow](https://github.com/lightbend/cloudflow) - Cloudflow enables users to quickly develop, orchestrate, and operate distributed streaming applications on Kubernetes. *(archived)*
* [cvrebert/lmvtfy](https://github.com/cvrebert/lmvtfy) - LMVTFY: Let Me Validate That For You
* [rpgboss/rpgboss](https://github.com/rpgboss/rpgboss) - point and click rpg game editor and engine
* [akka/akka-persistence-cassandra](https://github.com/akka/akka-persistence-cassandra) - A replicated Akka Persistence journal backed by Apache Cassandra
* [Hydrospheredata/mist](https://github.com/Hydrospheredata/mist) - Serverless proxy for Spark cluster
* [nymanjens/quizmaster](https://github.com/nymanjens/quizmaster) - A web-app for conducting a quiz over the internet
* [SpinalHDL/NaxRiscv](https://github.com/SpinalHDL/NaxRiscv)
* [neo4j/neo4j-spark-connector](https://github.com/neo4j/neo4j-spark-connector) - Neo4j Connector for Apache Spark, which provides bi-directional read/write access to Neo4j from Spark, using the Spark DataSource APIs
* [cs-au-dk/TIP](https://github.com/cs-au-dk/TIP) - Static program analysis for TIP
* [chipsalliance/t1](https://github.com/chipsalliance/t1)
* [sbt/sbt-dynver](https://github.com/sbt/sbt-dynver) - An sbt plugin to dynamically set your version from git
* [dcaoyuan/chana](https://github.com/dcaoyuan/chana) - Realtime Data Store Based on Akka
* [Sotera/spark-distributed-louvain-modularity](https://github.com/Sotera/spark-distributed-louvain-modularity) - Spark / graphX implementation of the distributed louvain modularity algorithm
* [Huawei-Spark/Spark-SQL-on-HBase](https://github.com/Huawei-Spark/Spark-SQL-on-HBase) - Native, optimized access to HBase Data through Spark SQL/Dataframe Interfaces
* [eBay/Neutrino](https://github.com/eBay/Neutrino) - Neutrino is a software load balancer(SLB)
* [djspiewak/gll-combinators](https://github.com/djspiewak/gll-combinators) - A parser combinator library based on the GLL algorithm
* [cb372/cats-retry](https://github.com/cb372/cats-retry)
* [Verizon/remotely](https://github.com/Verizon/remotely) - An elegant RPC system for reasonable people *(archived)*
* [projectglow/glow](https://github.com/projectglow/glow) - An open-source toolkit for large-scale genomic analysis
* [sbt/sbt-ci-release](https://github.com/sbt/sbt-ci-release) - sbt plugin to automate Sonatype releases from GitHub Actions
* [typelevel/cats-mtl](https://github.com/typelevel/cats-mtl) - cats transformer type classes.
* [levkhomich/akka-tracing](https://github.com/levkhomich/akka-tracing) - A distributed tracing extension for Akka. Provides integration with Play framework, Spray and Akka HTTP.
* [Stratio/Spark-MongoDB](https://github.com/Stratio/Spark-MongoDB) - Spark library for easy MongoDB access *(archived)*
* [Vyxal/Vyxal](https://github.com/Vyxal/Vyxal) - A code-golfing language experience that has aspects of traditional programming languages - terse yet convenient.
* [linkedin/spark-tfrecord](https://github.com/linkedin/spark-tfrecord) - Read and write Tensorflow TFRecord data from Apache Spark.
* [databricks/dicer](https://github.com/databricks/dicer) - Dicer auto-sharder: Infrastructure for building sharded services
* [banana-rdf/banana-rdf](https://github.com/banana-rdf/banana-rdf) - Banana RDF
* [apache/incubator-retired-gearpump](https://github.com/apache/incubator-retired-gearpump) - Mirror of Apache Gearpump (Incubating) *(archived)*
* [Comcast/sirius](https://github.com/Comcast/sirius) - A distributed system library for managing application reference data
* [nerdammer/spark-hbase-connector](https://github.com/nerdammer/spark-hbase-connector) - Connect Spark to HBase for reading and writing data with ease
* [http4s/rho](https://github.com/http4s/rho) - A self documenting DSL built on http4s
* [actionml/harness](https://github.com/actionml/harness) - Harness is a Machine Learning/AI Server with plugins for many algorithms including the Universal Recommender
* [cb372/sbt-explicit-dependencies](https://github.com/cb372/sbt-explicit-dependencies)
* [rockthejvm/udemy-scala-beginners](https://github.com/rockthejvm/udemy-scala-beginners)
* [stanford-ppl/spatial](https://github.com/stanford-ppl/spatial) - Spatial: "Specify Parameterized Accelerators Through Inordinately Abstract Language"
* [fix-macosx/net-monitor](https://github.com/fix-macosx/net-monitor) - Toolkit for auditing "phone home" behavior on Mac OS X Yosemite.
* [microsoft/sql-spark-connector](https://github.com/microsoft/sql-spark-connector) - Apache Spark Connector for SQL Server and Azure SQL *(archived)*
* [typelevel/fs2-grpc](https://github.com/typelevel/fs2-grpc) - gRPC implementation for FS2/cats-effect
* [ktoso/akka-raft](https://github.com/ktoso/akka-raft) - A toy project implementing RAFT on top of Akka Cluster (not prod ready) *(archived)*
* [hbutani/spark-druid-olap](https://github.com/hbutani/spark-druid-olap) - Sparkline BI Accelerator provides fast ad-hoc query capability over Logical Cubes. This has been folded into our SNAP Platform(http://bit.ly/2oBJSpP) an Integrated BI platform on Apache Spark. *(archived)*
* [xebia-functional/translate-bubble-android](https://github.com/xebia-functional/translate-bubble-android) - Translations without interruptions *(archived)*
* [cloudera-labs/SparkOnHBase](https://github.com/cloudera-labs/SparkOnHBase) - SparkOnHBase *(archived)*
* [KarolS/millfork](https://github.com/KarolS/millfork) - Millfork: a middle-level programming language targeting 6502- and Z80-based microcomputers and home consoles
* [guardian/typerighter](https://github.com/guardian/typerighter) - Even if you’re the right typer, couldn’t hurt to use Typerighter!
* [MoeOrganization/moe](https://github.com/MoeOrganization/moe) - An -OFun prototype of an Ultra Modern Perl 5
* [apache/texera](https://github.com/apache/texera) - Human-AI Collaborative Data Science Using Visual Workflows
* [scalapb/zio-grpc](https://github.com/scalapb/zio-grpc) - ScalaPB meets ZIO: write purely functional gRPC services and clients using ZIO
* [guardian/riff-raff](https://github.com/guardian/riff-raff) - The Guardian's deployment platform
* [krasserm/akka-analytics](https://github.com/krasserm/akka-analytics) - Large-scale event processing with Akka Persistence and Apache Spark
* [overview/overview-server](https://github.com/overview/overview-server) - Open source large document set visualization platform
* [spark-in-action/first-edition](https://github.com/spark-in-action/first-edition) - The book's repo
* [apache/incubator-s2graph](https://github.com/apache/incubator-s2graph) - Mirror of Apache S2Graph (Incubating) *(archived)*
* [BIDData/BIDMat](https://github.com/BIDData/BIDMat) - A CPU and GPU-accelerated matrix library for data mining
* [hortonworks-spark/spark-atlas-connector](https://github.com/hortonworks-spark/spark-atlas-connector) - A Spark Atlas connector to track data lineage in Apache Atlas
* [unibas-gravis/scalismo](https://github.com/unibas-gravis/scalismo) - Scalable Image Analysis and Shape Modelling
* [sbt/sbt-onejar](https://github.com/sbt/sbt-onejar) - Packages your project using One-JAR™
* [es-meta/esmeta](https://github.com/es-meta/esmeta) - ECMAScript Specification (ECMA-262) Metalanguage
* [waps101/AlbedoMM](https://github.com/waps101/AlbedoMM) - Albedo Morphable Model
* [LinkedInAttic/scanns](https://github.com/LinkedInAttic/scanns) - A scalable nearest neighbor search library in Apache Spark
* [jliszka/probability-monad](https://github.com/jliszka/probability-monad)
* [MichalStrehovsky/sizegame](https://github.com/MichalStrehovsky/sizegame) - Compare binary sizes of canonical Hello World in 18 different languages
* [scalanlp/chalk](https://github.com/scalanlp/chalk) - Chalk is a natural language processing library. *(archived)*
* [QianmiOpen/bugatti](https://github.com/QianmiOpen/bugatti) - 运维自动化部署监控平台
* [reactors-io/reactors](https://github.com/reactors-io/reactors) - A foundational framework for distributed programming.
* [dcaoyuan/spray-socketio](https://github.com/dcaoyuan/spray-socketio) - socket.io for spray
* [foursquare/fsqio](https://github.com/foursquare/fsqio) - A monorepo that holds all of Foursquare's opensource projects
* [mbknor/mbknor-jackson-jsonSchema](https://github.com/mbknor/mbknor-jackson-jsonSchema) - Generate JSON Schema with Polymorphism using Jackson annotations
* [amplab/spark-indexedrdd](https://github.com/amplab/spark-indexedrdd) - An efficient updatable key-value store for Apache Spark
* [bazeltools/bazel-deps](https://github.com/bazeltools/bazel-deps) - Generate bazel dependencies for maven artifacts
* [llm4s/llm4s](https://github.com/llm4s/llm4s) - Agentic and LLM Programming in Scala
* [oap-project/gazelle_plugin](https://github.com/oap-project/gazelle_plugin) - Native SQL Engine plugin for Spark SQL with vectorized SIMD optimizations. *(archived)*
* [getclump/clump](https://github.com/getclump/clump) - A library for expressive and efficient service composition
* [kitlangton/zio-magic](https://github.com/kitlangton/zio-magic) - Construct ZLayers automagically (w/ helpful compile-time errors) *(archived)*
* [akka/akka-management](https://github.com/akka/akka-management) - Akka Management is a suite of tools for operating Akka Clusters.
* [dlwh/puck](https://github.com/dlwh/puck) - Puck is a lightning-fast parser for natural languages using GPUs
* [knowitall/ollie](https://github.com/knowitall/ollie) - Ollie is a open information extractor that uses bootstrapped dependency paths.
* [mschuwalow/zio-todo-backend](https://github.com/mschuwalow/zio-todo-backend) - Todo-Backend (https://www.todobackend.com/) implementation using ZIO, http4s, doobie and circe
* [lightbend/paradox](https://github.com/lightbend/paradox) - Markdown documentation
* [lomigmegard/akka-http-cors](https://github.com/lomigmegard/akka-http-cors) - Akka Http directives implementing the CORS specifications defined by W3C
* [dragos/dragos-vscode-scala](https://github.com/dragos/dragos-vscode-scala) - *(archived)*
* [LeechanX/Netflix-Recommender-with-Spark](https://github.com/LeechanX/Netflix-Recommender-with-Spark) - 基于Apache Spark的Netflix电影的离线与实时推荐系统
* [silk-framework/silk](https://github.com/silk-framework/silk) - Silk Linked Data Integration Framework
* [ucb-bar/dsptools](https://github.com/ucb-bar/dsptools) - A Library of Chisel3 Tools for Digital Signal Processing
* [zhengruifeng/spark-libFM](https://github.com/zhengruifeng/spark-libFM) - An implement of Factorization Machines (LibFM)
* [SpinalHDL/VexiiRiscv](https://github.com/SpinalHDL/VexiiRiscv) - Like VexRiscv, but, Harder, Better, Faster, Stronger
* [cequence-io/openai-scala-client](https://github.com/cequence-io/openai-scala-client) - Scala client for OpenAI API and other major LLM providers
* [kakao/s2graph](https://github.com/kakao/s2graph) - This code base is retained for historical interest only, please visit Apache Incubator Repo for latest one *(archived)*
* [apache/hbase-connectors](https://github.com/apache/hbase-connectors) - Apache HBase Connectors
* [vaquarkhan/Apache-Kafka-poc-and-notes](https://github.com/vaquarkhan/Apache-Kafka-poc-and-notes)
* [typelevel/cats-parse](https://github.com/typelevel/cats-parse) - A parsing library for the cats ecosystem
* [unibas-gravis/parametric-face-image-generator](https://github.com/unibas-gravis/parametric-face-image-generator) - Generate fully parametric face images from the Basel Face Model 2017
* [tototoshi/slick-joda-mapper](https://github.com/tototoshi/slick-joda-mapper) - Slick with JodaTime
* [Tactical-Advantage-Trading/wallet](https://github.com/Tactical-Advantage-Trading/wallet) - ECX and BTC wallet for Android. Account control tool for Tactical Advantage clients.
* [AbsaOSS/ABRiS](https://github.com/AbsaOSS/ABRiS) - Avro SerDe for Apache Spark structured APIs.
* [CODAIT/spark-bench](https://github.com/CODAIT/spark-bench) - Benchmark Suite for Apache Spark
* [koeninger/kafka-exactly-once](https://github.com/koeninger/kafka-exactly-once)
* [midonet/midonet](https://github.com/midonet/midonet) - MidoNet is an Open Source network virtualization system for Openstack clouds
* [sangria-graphql/sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) - An example GraphQL server written with akka-http, circe and sangria
* [saurfang/spark-knn](https://github.com/saurfang/spark-knn) - k-Nearest Neighbors algorithm on Spark
* [jdegoes/functional-design](https://github.com/jdegoes/functional-design) - Exercises for the course 'Functional Design by John A. De Goes
* [chadyuu/riscv-chisel-book](https://github.com/chadyuu/riscv-chisel-book)
* [dataArtisans/flink-streaming-demo](https://github.com/dataArtisans/flink-streaming-demo)
* [scalacenter/scalajs-bundler](https://github.com/scalacenter/scalajs-bundler)
* [schoeberl/chisel-lab](https://github.com/schoeberl/chisel-lab) - Lab exercises for Chisel in the digital electronics 2 course at DTU
* [titicaca/spark-iforest](https://github.com/titicaca/spark-iforest) - Isolation Forest on Spark
* [VaughnVernon/ReactiveMessagingPatterns_ActorModel](https://github.com/VaughnVernon/ReactiveMessagingPatterns_ActorModel) - The examples for the book "Reactive Messaging Patterns with the Actor Model"
* [muuki88/sbt-native-packager-examples](https://github.com/muuki88/sbt-native-packager-examples) - A set of sbt-native-pakager examples
* [khronus/khronus](https://github.com/khronus/khronus) - A reactive time series database
* [ucb-bar/chiseltest](https://github.com/ucb-bar/chiseltest) - The batteries-included testing and formal verification library for Chisel-based RTL designs. *(archived)*
* [ucb-bar/constellation](https://github.com/ucb-bar/constellation) - A Chisel RTL generator for network-on-chip interconnects
* [unibas-gravis/basel-face-pipeline](https://github.com/unibas-gravis/basel-face-pipeline)
* [johnynek/bosatsu](https://github.com/johnynek/bosatsu) - A python-ish pure and total functional programming language
* [smallnest/douban-recommender](https://github.com/smallnest/douban-recommender) - 基于Spark ML实现的豆瓣电影推荐系统 *(archived)*
* [snowflakedb/spark-snowflake](https://github.com/snowflakedb/spark-snowflake) - Snowflake Data Source for Apache Spark.
* [databrickslabs/overwatch](https://github.com/databrickslabs/overwatch) - THIS PROJECT IS DEPRECATED. Capture deep metrics on one or all assets within a Databricks workspace *(archived)*
* [iron-io/dockerworker](https://github.com/iron-io/dockerworker) - The new IronWorker workflow examples. Test locally, then upload and start queuing jobs!
* [wix-incubator/exodus](https://github.com/wix-incubator/exodus) - Easily migrate your JVM code from Maven to Bazel
* [jboner/akka-crdt](https://github.com/jboner/akka-crdt) - Server-managed CRDTs based on Akka
* [hkust-taco/mlscript](https://github.com/hkust-taco/mlscript) - The MLscript programming language. Functional and object-oriented; structurally typed and sound; with powerful type inference. Soon to have full interop with TypeScript!
* [digital-preservation/csv-validator](https://github.com/digital-preservation/csv-validator) - CSV Validation Tool and API (CSV Schema RI)
* [bu-icsg/dana](https://github.com/bu-icsg/dana) - Dynamically Allocated Neural Network Accelerator for the RISC-V Rocket Microprocessor in Chisel
* [guardian/gu-who](https://github.com/guardian/gu-who) - answering: who are all these users in my GitHub org? *(archived)*
* [krasserm/akka-persistence-cassandra](https://github.com/krasserm/akka-persistence-cassandra) - A replicated Akka Persistence journal backed by Apache Cassandra
* [ucb-bar/riscv-torture](https://github.com/ucb-bar/riscv-torture) - RISC-V Torture Test
* [kurrent-io/EventStore.JVM](https://github.com/kurrent-io/EventStore.JVM) - Event Store JVM Client *(archived)*
* [lancewalton/treelog](https://github.com/lancewalton/treelog) - Allows logging in a tree structure so that comprehensive logging does not become incomprehensible
* [FRosner/drunken-data-quality](https://github.com/FRosner/drunken-data-quality) - Spark package for checking data quality
* [ReactiveDesignPatterns/CodeSamples](https://github.com/ReactiveDesignPatterns/CodeSamples) - Code snippets appearing in the book are excerpts from these complete and tested samples.
* [dcaoyuan/spray-websocket](https://github.com/dcaoyuan/spray-websocket) - WebSocket for spray-can
* [stanford-ppl/Delite](https://github.com/stanford-ppl/Delite) - The Delite Git Repo
* [ClickHouse/spark-clickhouse-connector](https://github.com/ClickHouse/spark-clickhouse-connector) - Spark ClickHouse Connector build on DataSourceV2 API
* [FlinkML/flink-tensorflow](https://github.com/FlinkML/flink-tensorflow) - flink-tensorflow - TensorFlow support for Apache Flink *(archived)*
* [ldaniels528/trifecta](https://github.com/ldaniels528/trifecta) - Trifecta is a web-based and CLI tool that simplifies inspecting Kafka messages and Zookeeper data. Additionally, the CLI tool provides the capability to import/export data to/from ElasticSearch and MongoDB.
* [nafg/reactive](https://github.com/nafg/reactive) - A simple FRP library and a web UI framework built on it *(archived)*
* [nkallen/querulous](https://github.com/nkallen/querulous) - An agreeable way to talk to your database.
* [lift-project/lift](https://github.com/lift-project/lift) - The Lift programming language and compiler
* [maxcom/lorsource](https://github.com/maxcom/lorsource) - Linux.org.ru website engine
* [mkuthan/example-spark](https://github.com/mkuthan/example-spark) - Spark, Spark Streaming and Spark SQL unit testing strategies
* [patriknw/akka-data-replication](https://github.com/patriknw/akka-data-replication) - Replication of CRDTs in Akka Cluster
* [jamesward/play-auto-refresh](https://github.com/jamesward/play-auto-refresh)
* [joa/apparat](https://github.com/joa/apparat) - A framework to optmize ABC, SWC and SWF files.
* [phatak-dev/spark2.0-examples](https://github.com/phatak-dev/spark2.0-examples) - Examples of Spark 2.0
* [strongtyped/active-slick](https://github.com/strongtyped/active-slick) - Slick extensions for record lifecycle management *(archived)*
* [skrusche63/spark-elastic](https://github.com/skrusche63/spark-elastic) - This project combines Apache Spark and Elasticsearch to enable mining & prediction for Elasticsearch.
* [starlake-ai/starflow](https://github.com/starlake-ai/starflow) - Declarative text based tool for data analysts and engineers to extract, load, transform and orchestrate their data pipelines.
* [pawelkaczor/ddd-leaven-akka](https://github.com/pawelkaczor/ddd-leaven-akka) - Reactive DDD with Akka
* [Qihoo360/XSQL](https://github.com/Qihoo360/XSQL) - Unified SQL Analytics Engine Based on SparkSQL
* [SingularityKChen/dl_accelerator](https://github.com/SingularityKChen/dl_accelerator) - Deep Learning Accelerator Based on Eyeriss V2 Architecture with custom RISC-V extended instructions
* [AbsaOSS/spline-spark-agent](https://github.com/AbsaOSS/spline-spark-agent) - Spline agent for Apache Spark
* [Stratio/spark-rabbitmq](https://github.com/Stratio/spark-rabbitmq) - RabbitMQ Spark Streaming receiver *(archived)*
* [hseeberger/constructr](https://github.com/hseeberger/constructr) - Coordinated (etcd, ...) cluster construction for dynamic (cloud, containers) environments *(archived)*
* [sunbow1/SparkMLlibDeepLearn](https://github.com/sunbow1/SparkMLlibDeepLearn) - SparkMLlibDeepLearn深度学习
* [lightbend/kafka-with-akka-streams-kafka-streams-tutorial](https://github.com/lightbend/kafka-with-akka-streams-kafka-streams-tutorial) - Code samples for the Lightbend tutorial on writing microservices with Akka Streams, Kafka Streams, and Kafka
* [neoremind/kraps-rpc](https://github.com/neoremind/kraps-rpc) - A RPC framework leveraging Spark RPC module
* [headinthebox/CourseraCodeSamplesReactiveProgramming](https://github.com/headinthebox/CourseraCodeSamplesReactiveProgramming)
* [cld378632668/A-community-detect-System-based-on-GraphX](https://github.com/cld378632668/A-community-detect-System-based-on-GraphX) - 图计算和图存储在国内兴起于2012年，此项目为我的本科毕业设计，本人现在TOP厂商工作，工作要求不方便公开透露公司，曾研究图数据库2年，实验室数据库技术从2000年以前开始积累，对外低调，如有工作需要可以推荐！
* [laserdisc-io/fs2-aws](https://github.com/laserdisc-io/fs2-aws) - fs2 utilities to interact with AWS
* [djspiewak/emm](https://github.com/djspiewak/emm) - A general monad for managing stacking effects *(archived)*
* [echen/link-prediction](https://github.com/echen/link-prediction) - Solution to Facebook's link prediction contest on Kaggle.
* [walfie/gbf-raidfinder](https://github.com/walfie/gbf-raidfinder) - Granblue Raid Finder (Archived: Granblue no longer has raid tweets) *(archived)*
* [deng0515001/lnglat2Geo](https://github.com/deng0515001/lnglat2Geo) - 经纬度转省市区县乡镇离线包，采用空间查询算法，速度快(单线程5w次/s)，省市区县100%准确率。
* [input-output-hk/scrypto](https://github.com/input-output-hk/scrypto) - Cryptographic primitives for Scala
* [Adi23041999/UpstateLiberty](https://github.com/Adi23041999/UpstateLiberty)
* [cookeem/CookIM](https://github.com/cookeem/CookIM) - Distributed web chat application base websocket built on akka.
* [Duhemm/sbt-errors-summary](https://github.com/Duhemm/sbt-errors-summary) - sbt plugin to show a summary of compilation messages.
* [krasserm/akka-persistence-kafka](https://github.com/krasserm/akka-persistence-kafka) - A replicated Akka Persistence journal backed by Apache Kafka
* [leon/play-salat](https://github.com/leon/play-salat) - MongoDB / Salat plugin for Play 2 [MOVED] *(archived)*
* [non/antimirov](https://github.com/non/antimirov) - algebraic manipulation of regular expressions
* [wuhx/shelldroid](https://github.com/wuhx/shelldroid) - Create Virtual Environment for your Android Apps
* [nadimbahadoor/allaboutscala](https://github.com/nadimbahadoor/allaboutscala) - Source code for www.allaboutscala.com tutorials
* [arguslab/Argus-SAF](https://github.com/arguslab/Argus-SAF) - Argus static analysis framework
* [jflanigan/jamr](https://github.com/jflanigan/jamr) - JAMR Parser and Generator
* [sbt/sbt-github-actions](https://github.com/sbt/sbt-github-actions) - An sbt plugin which makes it easier to build with GitHub Actions
* [CrestOfWave/Spark-2.3.1](https://github.com/CrestOfWave/Spark-2.3.1) - Spark-2.3.1源码解读
* [lagom/online-auction-scala](https://github.com/lagom/online-auction-scala) - *(archived)*
* [mrsqueeze/spark-hash](https://github.com/mrsqueeze/spark-hash) - Locality Sensitive Hashing for Apache Spark
* [bizzabo/play-json-extensions](https://github.com/bizzabo/play-json-extensions) - +22 field case class formatter and more for play-json
* [ProjectSeptemberInc/freek](https://github.com/ProjectSeptemberInc/freek) - Freek, a freaky simple Free to combine your DSL seamlessly
* [apache/pekko-http](https://github.com/apache/pekko-http) - The Streaming-first HTTP server/module of Apache Pekko
* [VCA-EPFL/FSA](https://github.com/VCA-EPFL/FSA) - FSA: Fusing FlashAttention within a Single Systolic Array
* [jdegoes/zio-workshop](https://github.com/jdegoes/zio-workshop) - Real World Functional Programming with ZIO
* [to-ithaca/libra](https://github.com/to-ithaca/libra) - A dimensional analysis library based on dependent types
* [typelevel/feral](https://github.com/typelevel/feral) - Feral cats are homeless, feral functions are serverless
* [dbpedia/lookup](https://github.com/dbpedia/lookup) - Outputs a list of ranked DBpedia resources for a search string.
* [jdegoes/functional-effects](https://github.com/jdegoes/functional-effects) - The exercises for the Functional Effects workshop
* [sifive/sifive-blocks](https://github.com/sifive/sifive-blocks) - Common RTL blocks used in SiFive's projects
* [julienrf/play-json-derived-codecs](https://github.com/julienrf/play-json-derived-codecs)
* [Y1ran/Spark-The-Definitive-Guide-Chinese-Traslation-2019](https://github.com/Y1ran/Spark-The-Definitive-Guide-Chinese-Traslation-2019) - Spark权威指南( Spark The Definitive Guide) -中文版翻译项目
* [mc2-project/opaque-sql](https://github.com/mc2-project/opaque-sql) - An encrypted data analytics platform
* [ShapeNet/shapenet-viewer](https://github.com/ShapeNet/shapenet-viewer) - ShapeNet Viewer
* [ScalaConsultants/reactive-rabbit](https://github.com/ScalaConsultants/reactive-rabbit) - Reactive Streams driver for AMQP protocol. Powered by RabbitMQ library.
* [typelevel/grackle](https://github.com/typelevel/grackle) - Grackle: Functional GraphQL for the Typelevel stack
* [cb372/scala-typed-holes](https://github.com/cb372/scala-typed-holes)
* [gregdurrett/berkeley-entity](https://github.com/gregdurrett/berkeley-entity) - The Berkeley Entity Resolution System jointly solves the problems of named entity recognition, coreference resolution, and entity linking with a feature-rich discriminative model.
* [Nycto/Hasher](https://github.com/Nycto/Hasher) - A small Scala library for easily generating hashes (md5, sha1, sha256, sha512, crc32, bcrypt, hmacs, pbkdf2)
* [typelevel/machinist](https://github.com/typelevel/machinist) - Spire's macros for zero-cost operator enrichment *(archived)*
* [mdr/ascii-graphs](https://github.com/mdr/ascii-graphs) - Parse ASCII art diagrams of graphs (nodes and edges)
* [banzaicloud/spark-metrics](https://github.com/banzaicloud/spark-metrics) - Spark metrics related custom classes and sinks (e.g. Prometheus)
* [polomarcus/Spark-Structured-Streaming-Examples](https://github.com/polomarcus/Spark-Structured-Streaming-Examples) - Spark Structured Streaming / Kafka / Cassandra / Elastic
* [twitter/twemoji-parser](https://github.com/twitter/twemoji-parser) - A simple library for identifying emoji entities within a string in order to render them as Twemoji.
* [txbits/txbits](https://github.com/txbits/txbits) - DISCLAIMER: TxBits is not affiliated with any active exchanges. Use them at your own risk and beware of any that violate the AGPL license terms by not releasing their source code as required.
* [xebia-functional/nine-cards-v2](https://github.com/xebia-functional/nine-cards-v2) - An Open Source Android Launcher built with Scala on Android *(archived)*
* [dbpedia-spotlight/dbpedia-spotlight-model](https://github.com/dbpedia-spotlight/dbpedia-spotlight-model) - DBpedia Spotlight is a tool for automatically annotating mentions of DBpedia resources in text. Improving Efficiency and Accuracy in Multilingual Entity Extraction approach
* [tofu-tf/derevo](https://github.com/tofu-tf/derevo) - Multiple instance derivations inside a single macro annotation
* [unibas-gravis/basel-face-model-viewer](https://github.com/unibas-gravis/basel-face-model-viewer) - Simple Viewer for the Basel Face Model 2017
* [viperproject/gobra](https://github.com/viperproject/gobra) - Gobra is an automated, modular verifier for Go programs, based on the Viper verification infrastructure.
* [CM-Well/CM-Well](https://github.com/CM-Well/CM-Well) - CM-Well - a data warehouse for your knowledge graph
* [sclasen/akka-kafka](https://github.com/sclasen/akka-kafka)
* [yaooqinn/spark-authorizer](https://github.com/yaooqinn/spark-authorizer) - A Spark SQL extension which provides SQL Standard Authorization for Apache Spark | This repo is contributed to Apache Kyuubi | 项目已迁移至 Apache Kyuubi
* [t3hnar/scala-bcrypt](https://github.com/t3hnar/scala-bcrypt) - Scala wrapper for jBcrypt + pom.xml inside
* [bplawler/crawler](https://github.com/bplawler/crawler) - Scala DSL for web crawling
* [P7h/Spark-MLlib-Twitter-Sentiment-Analysis](https://github.com/P7h/Spark-MLlib-Twitter-Sentiment-Analysis) - :star2: :sparkles: Analyze and visualize Twitter Sentiment on a world map using Spark MLlib
* [scala/scala-swing](https://github.com/scala/scala-swing) - Scala wrappers for Java's Swing API for desktop GUIs
* [STHSF/TextRank](https://github.com/STHSF/TextRank) - 基于PageRank的TextRank方法, 可以应用于中文关键词、短语、摘要提取程序，代码使用Scala编写。
* [scalacenter/scalac-profiling](https://github.com/scalacenter/scalac-profiling) - Compilation profiling tool for Scala 2 projects
* [JohnReedLOL/scala-trace-debug](https://github.com/JohnReedLOL/scala-trace-debug) - Macro based print debugging. Locates log statements in your IDE.
* [dyweb/scrala](https://github.com/dyweb/scrala) - Unmaintained :whale: :coffee: :spider: Scala crawler(spider) framework, inspired by scrapy, created by @gaocegege
* [roboscala/sbt-robovm](https://github.com/roboscala/sbt-robovm) - An sbt plugin for iOS development in Scala
* [scalacenter/advisoryboard](https://github.com/scalacenter/advisoryboard) - Scala Center Advisory Board planning
* [mikolak-net/travesty](https://github.com/mikolak-net/travesty) - Diagram- and graph-generating library for Akka Streams
