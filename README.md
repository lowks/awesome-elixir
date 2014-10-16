# Awesome Elixir [![Build Status](https://travis-ci.org/h4cc/awesome-elixir.svg?branch=master)](https://travis-ci.org/h4cc/awesome-elixir)
A curated list of amazingly awesome Elixir libraries, resources and shiny thing inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

- [Awesome Elixir](#awesome-elixir)
    - [Actors](#actors)
    - [Algorithms and Datastructures](#algorithms-and-datastructures)
    - [Authentication](#authentication)
    - [Build Tools](#build-tools)
    - [Caching](#caching)
    - [Code Analysis](#code-analysis)
    - [Configuration](#configuration)
    - [CSV](#csv)
    - [Date and Time](#date-and-time)
    - [Debugging](#debugging)
    - [Files and Directories](#files-and-directories)
    - [Framework Components](#framework-components)
    - [Frameworks](#frameworks)
    - [Geolocation](#geolocation)
    - [Hardware](#hardware)
    - [HTTP](#http)
    - [Images](#images)
    - [JSON](#json)
    - [Markdown](#markdown)
    - [Miscellaneous](#miscellaneous)
    - [Networking](#networking)
    - [ORM and Datamapping](#orm-and-datamapping)
    - [OTP](#otp)
    - [Package Management](#package-management)
    - [Protocols](#protocols)
    - [Queue](#queue)
    - [Release Management](#release-management)
    - [REST and API](#rest-and-api)
    - [Static Page Generation](#static-page-generation)
    - [Statistics](#statistics)
    - [Testing](#testing)
    - [Text and Numbers](#text-and-numbers)
    - [Third Party APIs](#third-party-apis)
    - [Translations and Internationalizations](#translations-and-internationalizations)
    - [Validations](#validations)
    - [XML](#xml)
- [Resources](#resources)
    - [Books](#books)
    - [Other Awesome Lists](#other-awesome-lists)
    - [Reading](#reading)
    - [Screencasts](#screencasts)
    - [Websites](#websites)
- [Contributing](#contributing)

## Actors
*Libraries and tools for working with actors and such.*

* [exactor](https://github.com/sasa1977/exactor) - Helpers for easier implementation of actors in Elixir.
* [poolboy](https://github.com/devinus/poolboy) - A hunky Erlang worker pool factory.
* [workex](https://github.com/sasa1977/workex) - Backpressure and flow control in EVM processes.

## Algorithms and Datastructures
*Libraries and implementations of algorithms and datastructures.*

* [array](https://github.com/takscape/elixir-array) - An Elixir wrapper library for Erlang's array.
* [hash_ring_ex](https://github.com/reset/hash-ring-ex) - A consistent hash ring implemention for Elixir.
* [lfsr](https://github.com/pma/lfsr) - Elixir implementation of a binary Galois Linear Feedback Shift Register.
* [fsm](https://github.com/sasa1977/fsm) - Finite state machine as a functional data structure.

## Authentication
*Libraries for implementing authentications schemes.*

* [oauther](https://github.com/lexmag/oauther) - An OAuth 1.0 implementation for Elixir.

## Build Tools
*Project build and automation tools.*

* [ExMake](https://github.com/lycus/exmake) - A modern, scriptable, dependency-based build tool loosely based on Make principles.
* [rotor](https://github.com/HashNuke/rotor) - Super-simple build system for Elixir.
* [coffee_rotor](https://github.com/HashNuke/coffee_rotor) - Rotor plugin to compile CoffeeScript files.

## Caching
*Libraries for caching data.*

* [con_cache](https://github.com/sasa1977/con_cache) - ConCache is an ETS based key/value storage.

## Code Analysis
*Libraries and tools for analysing, parsing and manipulation codebases.*

* [coverex](https://github.com/alfert/coverex) - Coverage Reports for Elixir.
* [excoveralls](https://github.com/parroty/excoveralls) - Coverage report tool for Elixir with coveralls.io integration.
* [exprof](https://github.com/parroty/exprof) - A simple code profiler for Elixir using eprof.
* [dialyxir](https://github.com/jeremyjh/dialyxir) - Mix tasks to simplify use of Dialyzer in Elixir projects.

## Configuration
*Libraries and tools working with configurations*

* [figaro](https://github.com/trestrantham/ex_figaro) - Simple Elixir project configuration.
* [conform](https://github.com/bitwalker/conform) - Easy release configuration for Elixir apps.
* [ex_conf](https://github.com/phoenixframework/ex_conf) - Simple Elixir Configuration Management.

## CSV
*Libraries and implementations working with CSV.*

* [cesso](https://github.com/meh/cesso) - CSV handling library for Elixir.
* [csvlixir](https://github.com/jimm/csvlixir) - A CSV reading/writing application for Elixir.
* [ex_csv](https://github.com/CargoSense/ex_csv) - CSV for Elixir.

## Date and Time
*Libraries for working with dates and times.*

* [chronos](https://github.com/nurugger07/chronos) - An elixir date/time library.
* [timex](https://github.com/bitwalker/timex) - Easy to use Date and Time modules for Elixir.
* [timex_interval](https://github.com/atabary/timex-interval) - A date/time interval library for Elixir projects, based on Timex.
* [moment](https://github.com/atabary/moment) - Parse, validate, manipulate, and display dates in Elixir.

## Debugging
*Libraries and tools for debugging code and applications.*

* [dbg](https://github.com/fishcakez/dbg) - Distributed tracing for Elixir.
* [booter](https://github.com/eraserewind/booter) - Boot an Elixir application step by step.

## Files and Directories
*Libraries and implementations for working with files and directories.*

* [dir_walker](https://github.com/pragdave/dir_walker) - DirWalker lazily traverses one or more directory trees, depth first, returning successive file names.
* [radpath](https://github.com/lowks/Radpath) - A path library for Elixir inspired by Python path libraries.

## Framework Components
*Standalone component from web development frameworks.*

* [flinch](https://github.com/rozap/finch) - Resource layer for Phoenix and Ecto projects for auto-generated RESTful CRUD APIs.
* [plug](https://github.com/elixir-lang/plug) - A specification and conveniences for composable modules in between web applications.
* [webassembly](https://github.com/herenowcoder/webassembly) - Web DSL for Elixir.

## Frameworks
*Web development frameworks.*

* [dynamo](https://github.com/dynamo/dynamo) - Dynamo is an experimental web framework that runs on Elixir.
* [phoenix](https://github.com/phoenixframework/phoenix) - Elixir Web Framework targeting full-featured, fault tolerant applications with realtime functionality.
* [placid](https://github.com/slogsdon/placid) - A REST toolkit for building highly-scalable and fault-tolerant HTTP APIs with Elixir.
* [sugar](https://github.com/sugar-framework/sugar) - Modular web framework for Elixir.
* [weber](https://github.com/elixir-web/weber) - Web framework for Elixir inspired by Rails.

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [geo](https://github.com/bryanjos/geo) - A collection of GIS functions for Elixir.

## Hardware
*Hardware related things like I/O interfaces and such.*

* [elixir_ale](https://github.com/fhunleth/elixir_ale) - Elixir access to hardware I/O interfaces such as GPIO, I2C, and SPI.

## HTTP
*Libraries for working with HTTP and scraping websites.*

* [cauldron](https://github.com/meh/cauldron) - An HTTP/SPDY server as a library.
* [exvcr](https://github.com/parroty/exvcr) - HTTP request/response recording library for elixir, inspired by VCR.
* [httpoison](https://github.com/edgurgel/httpoison) - Yet Another HTTP client for Elixir powered by hackney.
* [httpotion](https://github.com/myfreeweb/httpotion) - Fancy HTTP client for Elixir, based on ibrowse.
* [httprot](https://github.com/meh/httprot) - HTTP client library.

## Images
*Libraries for working with and manipulating images.*

* [exexif](https://github.com/pragdave/exexif) - Pure elixir library to extract tiff and exif metadata from jpeg files.

## JSON
*Libraries and implementations working with JSON.*

* [exjson](https://github.com/guedes/exjson) - JSON parser and genarator in Elixir.
* [jazz](https://github.com/meh/jazz) - Yet another library to handle JSON in Elixir.
* [joken](https://github.com/bryanjos/joken) - Encodes and decodes JSON Web Tokens.
* [jsex](https://github.com/talentdeficit/jsex) - json for elixir.
* [jsx](https://github.com/talentdeficit/jsx) - an erlang application for consuming, producing and manipulating json.
* [jsxn](https://github.com/talentdeficit/jsxn) - jsx but with maps.

## Markdown
*Libraries and tools working with Markdown and such.*

* [discount](https://github.com/asaaki/discount.ex) - Elixir NIF for discount, a Markdown parser.
* [earmark](https://github.com/pragdave/earmark) - Markdown parser for Elixir.

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

* [Apex](https://github.com/bjro/apex) - Awesome Print for Elixir.
* [ex2ms](https://github.com/ericmj/ex2ms) - Translates Elixir functions to match specifications for use with `ets`.
* [exprint](https://github.com/parroty/exprintf) - A printf / sprintf library for Elixir. It works as a wrapper for :io.format.
* [exquisite](https://github.com/meh/exquisite) - LINQ-like match_spec generation for Elixir.
* [ex_rated](https://github.com/grempe/ex_rated) - Simple and flexible rate-limiting for API's or anything.
* [funnel](https://github.com/AF83/funnel) - Streaming Elixir API built upon ElasticSearch's percolation.
* [mdef](https://github.com/pragdave/mdef) - Easily define multiple function heads in elixir.
* [porcelain](https://github.com/alco/porcelain) - Porcelain implements a saner approach to launching and communicating with external OS processes from Elixir.
* [reprise](https://github.com/herenowcoder/reprise) - Simplified module reloader for Elixir.
* [spawndir](https://github.com/jtmoulia/spawndir) - Spawns processes from the file system.

## Networking
*Libraries and tools for using network related stuff.*

* [chatty](https://github.com/alco/chatty) - A basic IRC client that is most useful for writing a bot.
* [ExIrc](https://github.com/bitwalker/exirc) - IRC client adapter for Elixir projects.
* [reagent](https://github.com/meh/reagent) - reagent is a socket acceptor pool for Elixir.
* [socket](https://github.com/meh/elixir-socket) - Socket wrapping for Elixir.
* [wpa_supplicant](https://github.com/fhunleth/wpa_supplicant.ex) - Elixir interface to the wpa_supplicant.

## ORM and Datamapping
*Libraries that implement object-relational mapping or datamapping techniques.*

* [atlas](https://github.com/chrismccord/atlas) - Object Relational Mapper for Elixir.
* [dexts](https://github.com/meh/dexts) - Disk Elixir Terms Storage, dest wrapper.
* [ecto](https://github.com/elixir-lang/ecto) - A database wrapper and language integrated query for Elixir.
* [exredis](https://github.com/artemeff/exredis) - Redis client for Elixir.
* [exts](https://github.com/meh/exts) - Elixir Terms Storage, ets wrapper.
* [postgrex](https://github.com/ericmj/postgrex) - PostgreSQL driver for Elixir.
* [ssdb_elixir](https://github.com/lidashuang/ssdb_elixir) - ssdb client for Elixir with focus on performance.

## OTP
*Libraries for working with OTP related things.*

* [core](https://github.com/fishcakez/core) - Library for selective receive OTP processes.
* [libex_config](https://github.com/reset/libex-config) - Helpers for accessing OTP application configuration.

## Package Management
*Libraries and tools for package and dependency management.*

* [Hex](https://hex.pm/) - A package manager for the Erlang ecosystem.

## Protocols
*Special protocol and format libraries.*

* [message_pack](https://github.com/mururu/msgpack-elixir) - MessagePack Implementation for Elixir.
* [exprotobuf](https://github.com/bitwalker/exprotobuf) - Protocol Buffers in Elixir made easy.

## Queue
*Libraries for working with event and task queues.*

* [exrabbit](https://github.com/d0rc/exrabbit) - RabbitMQ bindings and DSL for Elixir.

## Release Management
*Libraries and tools for release management.*

* [exrm](https://github.com/bitwalker/exrm) - Automatically generate a release for your Elixir project.
* [exrm_rpm](https://github.com/smpallen99/exrm-rpm) - Create a rpm for your elixir release with ease.

## REST and API
*Libraries and web tools for developing REST-ful APIs.*

* [lazymaru](https://github.com/falood/lazymaru) - Elixir copy of grape for creating REST-like APIs.
* [signaturex](https://github.com/edgurgel/signaturex) - Simple key/secret based authentication for APIs.
* [urna](https://github.com/meh/urna) - Urna is a simple DSL around cauldron to implement REST services.

## Static Page Generation
*Tools and libraries for generating static websites and content.*

* [coil](https://github.com/badosu/coil) - Minimalistic static content engine.

## Statistics
*Libraries around the topic statistics.*

* [statistics](https://github.com/msharp/elixir-statistics) - Some basic statistical functions for Elixir.
* [descriptive_statistics](https://github.com/pusewicz/descriptive_statistics) - Descriptive Statistics for Elixir.

## Testing
*Libraries for testing codebases and generating test data.*

* [amrita](https://github.com/josephwilk/amrita) - A polite, well mannered and thoroughly upstanding testing framework for Elixir.
* [excheck](https://github.com/parroty/excheck) - Property-based testing library for Elixir (QuickCheck style).
* [faker](https://github.com/igas/faker) - Faker is pure Elixir library for generating fake data.
* [hound](https://github.com/HashNuke/hound) - Elixir library for writing integration tests and browser automation.

## Text and Numbers
*Libraries for parsing and manipulating text and numbers.*

* [calliope](https://github.com/nurugger07/calliope) - An elixir haml parser.
* [cldr](https://github.com/magicienap/cldr) - cldr is a library to use information from CLDR data.
* [colorful](https://github.com/Joe-noh/colorful) - Elixir macros to decorate characters on CUI.
* [colors](https://github.com/lidashuang/colors) - Colors util written in Elixir.
* [decimal](https://github.com/ericmj/decimal) - Arbitrary precision decimal arithmetic for Elixir.
* [event_source_encoder](https://github.com/chatgris/event_source_encoder) - Encode data into EventSource compliant data.
* [inflex](https://github.com/nurugger07/inflex) - An Inflector library for Elixir.
* [pinyin](https://github.com/lidashuang/pinyin) - chinese pinyin lib for elixir.
* [saltie](https://github.com/alco/saltie) - Saltie is a pseudo-encryption library primarily used for obfuscating numerical identifiers to opaque strings.
* [uuid](https://github.com/zyro/elixir-uuid) - UUID generator and utilities for Elixir.
* [exmoji](https://github.com/mroth/exmoji) - Emoji encoding swiss army knife for Elixir/Erlang.

## Third Party APIs
*Libraries for accessing third party APIs.*

* [balanced](https://github.com/bryanjos/balanced-elixir) - Balanced Api Client for Elixir.
* [currently](https://github.com/chatgris/currently) - A tool to display cards currently assigns on Trello.
* [dpd_client](https://github.com/knewter/dpd_client) - An API client for the DPD service.
* [dropbox](https://github.com/ammmir/elixir-dropbox) - Dropbox Core API client for Elixir.
* [exgravatar](https://github.com/scrogson/exgravatar) - An Elixir module for generating Gravatar urls.
* [extwitter](https://github.com/parroty/extwitter) - Twitter client library for elixir.
* [ex_omegle](https://github.com/xtagon/ex_omegle) - A minimal Omegle chat client library for Elixir.
* [facebook](https://github.com/mweibel/facebook.ex) - Facebook Graph API Wrapper written in Elixir.
* [parsex](https://github.com/maarek/ParsEx) - ParsEx is an Elixir HTTP Client for communicating with Parse.com's Restful API.
* [parse_client](https://github.com/elixircnx/parse_elixir_client) - Elixir client for the parse.com REST API.
* [reap](https://github.com/Raynes/reap) - Reap is a simple Elixir library for working with the refheap API.
* [simplex](https://github.com/adamkittelson/simplex) - An Elixir library for interacting with the Amazon SimpleDB API.

## Translations and Internationalizations
*Libraries providing translations or internationalizations.*

* [linguist](https://github.com/chrismccord/linguist) - Elixir Internationalization library.

## Validations
*Libraries and implementations for validation of data.*

* [vex](https://github.com/CargoSense/vex) - An extensible data validation library for Elixir.

## XML
*Libraries and implementations working with XML.*

* [quinn](https://github.com/nhu313/Quinn) - XML parser for Elixir.
* [xml_builder](https://github.com/joshnuss/xml_builder) - Elixir library for generating xml.
* [exmerl](https://github.com/pwoolcoc/exmerl) - Elixir wrapper for xmerl.

# Resources
Various resources, such as books, websites and articles, for improving your Elixir development skills and knowledge.

## Books
*Fantastic books and e-books.*

* [Programming Elixir](http://pragprog.com/book/elixir/programming-elixir) - The book provides introduction to functional and concurrent programming with Elixir by Dave Thomas (2014).
* [Elixir in Action](http://www.manning.com/juric/) - A brief intro to the language followed by a more detailed look at building production-ready systems in Elixir by Saša Jurić (2014).
* [The Little Elixir & OTP Guidebook](http://www.exotpbook.com/) - A book for learning Elixir and OTP through small to medium-sized projects by Benjamin Tan Wei Hao (2014).
* [Études for Elixir](http://chimera.labs.oreilly.com/books/1234000001642) - A collection of exercises to program in Elixir by J. David Eisenberg (2013).
* [Introducing Elixir ](http://shop.oreilly.com/product/0636920030584.do) - A gentle introduction to the language, with lots of code examples and exercises by Simon St. Laurent and J. David Eisenberg (2013).
* [Elixir for the functional Rubyist](http://elixir-for-rubyists.com/) - Not yet released. By Johnny Winn.
* [Erlang in Anger](http://www.erlang-in-anger.com/) - This book intends to be a little guide about how to be the Erlang medic in a time of war by Fred Hebert (2014).

## Other Awesome Lists
*Other amazingly awesome lists can be found at [jnv/lists](https://github.com/jnv/lists#lists-of-lists).*

* [Awesome Erlang](https://github.com/drobakowski/awesome-erlang) - A curated list of awesome Erlang libraries, resources and shiny things.

## Reading
*Elixir-releated reading materials.*

* [Elixir Cheat-Sheet](http://media.pragprog.com/titles/elixir/ElixirCheat.pdf) - A Elixir cheat sheet by Andy Hunt & Dave Thomas.

## Screencasts
*Cool video tutorials.*

* [Elixir Sips](http://elixirsips.com) - Tiny screencasts for learning Elixir.

## Websites
*Useful web and Elixir-related websites and newsletters.*

* [Elixir Github Repository](https://github.com/elixir-lang/elixir) - The project repository.
* [Elixir Github Wiki](https://github.com/elixir-lang/elixir/wiki) - The projects wiki, containing many usefull information.
* [How i start - Elixir](http://howistart.org/posts/elixir/1) - Explanation and intro to Elixir by José Valim.
* [Elixir Quiz](http://elixirquiz.github.io/) - Weekly programming problems to help you learn Elixir.

# Contributing
Please see [CONTRIBUTING](https://github.com/h4cc/awesome-elixir/blob/master/CONTRIBUTING.md) for details.
