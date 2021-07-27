# Server and Web tech in Julia

> Interface for generic external servers, web framework, ...

**Organization**

- [Julia Web](https://github.com/JuliaWeb)

## Server backends

- [Discord.jl](https://github.com/PurgePJ/Discord.jl) : Julia Discord wrapper.
- [Joseki.jl](https://github.com/amellnik/Joseki.jl) : Suggested opening moves for building APIs in Julia.
- [NewsAPI.jl](https://github.com/joshday/NewsAPI.jl) : Helper functions for using [newsapi.org](https://newsapi.org)
- [Twitter.jl](https://github.com/randyzwitch/Twitter.jl) : Julia package to access the Twitter API.

---

- 🏚️ [DandelionSlack.jl](https://github.com/dandeliondeathray/DandelionSlack.jl) : Slack API in Julia.
- 🏚️ [FFIExamples.jl](https://github.com/johnmyleswhite/FFIExamples.jl) : Many small examples that demonstrate how Julia's [FFI](http://en.wikipedia.org/wiki/Foreign_function_interface) works as of v0.4.
- 🏚️ [Hydna.jl](https://github.com/jfd/Hydna.jl) : Hydna Julia Client Library implements support for the Hydna Push API.
- 🏚️ [MakiBot.jl](https://github.com/SimonDanisch/MakiBot.jl) : A Telegram plot bot for MakiE.jl.
- 🏚️ [MapLight.jl](https://github.com/WestleyArgentum/MapLight.jl) : A Julia package for using the MapLight API.
- 🏚️ [OpenSecrets.jl](https://github.com/WestleyArgentum/OpenSecrets.jl) : An API package for working with [OpenSecrets data](http://opensecrets.org/resources/create/)
- 🏚️ [Slackbot.jl](https://github.com/jiahao/Slackbot.jl) : A Julia REPL that interacts with Slack.com's webhook integration.
- 🏚️ [Sunlight.jl](https://github.com/WestleyArgentum/Sunlight.jl) : A Julia package for interfacing with the [Sunlight Foundation's API's](http://sunlightfoundation.com/api).
- 🏚️ [Toxcore.jl](https://github.com/SimonDanisch/Toxcore.jl) : A Julia wrapper for [Tox](http://en.wikipedia.org/wiki/Tox_%28software%29).
- 🏚️ [Twilert.jl](https://github.com/glesica/Twilert.jl) : A small SMS alert library for Julia.

## Web frameworks

- [Bukdu.jl](https://github.com/wookay/Bukdu.jl) : A web development framework for Julia, influenced by [Phoenix framework](http://phoenixframework.org).
- [Genie.jl](https://github.com/GenieFramework/Genie.jl) : The highly productive Julia web framework.
- [Merly.jl](https://github.com/codeneomatrix/Merly.jl) : A micro framework for web programming in Julia.

---

- 🏚️ [mvc-skeleton.jl](https://github.com/halla/mvc-skeleton.jl)
- 🏚️ [OpenFiscaWebApi.jl](https://github.com/openfisca/OpenFiscaWebApi.jl) : A port of OpenFisca-Web-API to Julia. This is the web API for the OpenFisca website.
- 🏚️ [Pythia.jl](https://github.com/Keno/Pythia.jl) : Julia wrappers for the Pythia event generator.
- 🏚️ [RoR_julia_eg](https://github.com/Ken-B/RoR_julia_eg) : An example of Ruby on Rails (RoR) web app with Julia link through ZMQ.

## Middleware

- [JuliaWebAPI.jl](https://github.com/JuliaWeb/JuliaWebAPI.jl) : Julia package for deploying APIs on JuliaBox to facilitat wrapping Julia functions into a remote callable API via ZMQ and HTTP.
- [Mux.jl](https://github.com/JuliaWeb/Mux.jl) : Middleware for Julia.
- [ParallelDataTransfer.jl](https://github.com/ChrisRackauckas/ParallelDataTransfer.jl) : A bunch of helper functions for transferring data between worker processes.
- [ZMQ.jl](https://github.com/JuliaLang/ZMQ.jl) : Julia interface to ZeroMQ. Thread on building a [web app for enterprise risk management](https://groups.google.com/forum/#!topic/julia-users/umHiBwVLQ4g).

---

- 🏚️ [Mongrel2.jl](https://github.com/aviks/Mongrel2.jl) : Mongrel2 handlers in Julia.
- 🏚️ [Nanomsg.jl](https://github.com/quinnj/Nanomsg.jl) : a middleware, nanomsg wrapper for the Julia programming language - [Nanomsg](http://nanomsg.org) is a reboot of the ØMQ socket library, providing several common communication patterns that make the networking layer fast, scalable, and easy to use.

## Networking

- [DandelionWebSockets.jl](https://github.com/dandeliondeathray/DandelionWebSockets.jl) : A Julia package for client side WebSockets.
- [IPNets.jl](https://github.com/JuliaWeb/IPNets.jl) : IPv4 / IPv6 network abstractions for Julia.
- [LogParser.jl](https://github.com/randyzwitch/LogParser.jl) : A package for parsing server logs. Currently, only server logs having the Apache Combined format are supported (although Apache Common may parse as well).
- [Rate Limiter.jl](https://github.com/chipkent/RateLimiter.jl) : Julia package for limiting the rate at which events occur.
- [TimeZones.jl](https://github.com/JuliaTime/TimeZones.jl) : Olsen Timezone Database Access for the Julia Programming Language.

---

- 🏚️ [Dates.jl](https://github.com/quinnj/Dates.jl) : A Date and DateTime implementation for Julia. Merged into the Base Standard Library
- 🏚️ [Juliaflow](https://github.com/pchronz/juliaflow) : A controller for software-defined networking (SDN) that implements the OpenFlow Controller Specification 1.0.0
- 🏚️ [MsgPackRpcServer.jl](https://github.com/remore/MsgPackRpcServer.jl) : A Julia implementation of MessagePack-RPC Server Library.
- 🏚️ [Pcap.jl](https://github.com/JuliaIO/Pcap.jl) : Libpcap implementation for Julia language. (No `Project.toml`)
- 🏚️ [StatsdClient.jl](https://github.com/forio/StatsdClient.jl) : A simple Julia implementation of a statsd client.
- 🏚️ [UUID.jl](https://github.com/forio/UUID.jl) : A universally unique identifier (UUID) is an identifier standard, are 128 bits long, and require no central registration process. UUID functionality has been merged into Julia 0.4.


## Security

- [GnuTLS.jl](https://github.com/JuliaWeb/GnuTLS.jl) : Transport Level Security for Julia Streams provided by GnuTLS.
- [MbedTLS](https://github.com/JuliaLang/MbedTLS.jl) : Wrapper around mbedtls.
- [OAuth.jl](https://github.com/randyzwitch/OAuth.jl) : Pure Julia implementation of OAuth v1.0a.

---

- 🏚️ [Etcd.jl](https://github.com/forio/Etcd.jl) : A Julia Etcd client implementation.
- 🏚️ [SecureSessions.jl](https://github.com/JockLawrie/SecureSessions.jl) : Secure sessions for web apps written in Julia.
- 🏚️ [SSH.jl](https://github.com/Keno/SSH.jl) : An SSH implementation.

## Web

- [Blink.jl](https://github.com/JuliaGizmos/Blink.jl) : Web-based GUIs for Julia.
- [CSSUtil](https://github.com/JuliaGizmos/CSSUtil) : utilities to create and align various web elements on the DOM.
- [CutShortURL.jl](https://github.com/rahulkp220/CutShortURL.jl) : The simplest URL Shortener for Julia. A Julia wrapper around https://tinyurl.com/
- [DandelionWebSockets.jl](https://github.com/dandeliondeathray/DandelionWebSockets.jl) : A Julia package for client side WebSockets.
- [Diana.jl](https://github.com/codeneomatrix/Diana.jl) : GraphQL for Julia.
- [Escher.jl](https://github.com/shashi/Escher.jl) : Composable Web UIs in pure Julia. [Website](http://escher-jl.org).
- [Gumbo.jl](https://github.com/JuliaWeb/Gumbo.jl) : Julia wrapper around google's [gumbo](https://github.com/google/gumbo-parser) library for parsing HTML.
- [HTTP.jl](https://github.com/JuliaWeb/HTTP.jl) : HTTP for Julia.
- [HTTP2.jl](https://github.com/sorpaas/HTTP2.jl) : A HTTP2 support library for Julia. You only use this library directly if you need low-level functionality.
- [HttpCommon.jl](https://github.com/JuliaWeb/HttpCommon.jl) : Provides types and helper functions for dealing with the HTTP protocol in Julia.
- [Hyperscript.jl](https://github.com/yurivish/Hyperscript.jl) : A lightweight DOM representation for working with HTML, SVG, and CSS in Julia.
- [LibCURL.jl](https://github.com/JuliaWeb/LibCURL.jl) : Thin Julia wrapper of libCURL
- [Pages.jl](https://github.com/EricForgy/Pages.jl) : A simple way to create and interact with web pages.
- [UAParser.jl](https://github.com/JuliaWeb/UAParser.jl) : UAParser is a Julia port of ua-parser, which itself is a multi-language port of BrowserScope's user agent string parser.
- [URITemplate.jl](https://github.com/JuliaWeb/URITemplate.jl) : This package provides URI Template interpolation by implementing (RFC 6570).
- [WebIO.jl](https://github.com/JuliaGizmos/WebIO.jl) : WebIO provides a simple abstraction for displaying and interacting with web content.
- [WebSockets.jl](https://github.com/JuliaWeb/WebSockets.jl) : A WebSockets server library for Julia.

---

- 🏚️ [Biryani.jl](https://github.com/eraviart/Biryani.jl) : A conversion and validation toolbox.
- 🏚️ [Curl.jl](https://github.com/forio/Curl.jl) : A Julia HTTP curl library.
- 🏚️ [Fuji.jl](https://github.com/jackcook/Fuji.jl) : A lightweight web server written in Julia.
- 🏚️ [HTTPClient.jl](https://github.com/JuliaWeb/HTTPClient.jl): Currently provides an HTTP Client based on libcurl. See `HTTP.jl`.
- 🏚️ [HttpParser.jl](https://github.com/JuliaWeb/HttpParser.jl) : Julia wrapper for Joyent's http-parser. See `HTTP.jl`.
- 🏚️ [HttpServer.jl](https://github.com/JuliaLang/HttpServer.jl) : a basic, non-blocking HTTP server in Julia.
- 🏚️ [JuliaWebServer](https://github.com/chzyer/JuliaWebServer) : a webserver for julia.
- 🏚️ [Meddle.jl](https://github.com/JuliaWeb/Meddle.jl) : is the middleware stack for use with HttpServer.jl.
- 🏚️ [Morsel.jl](https://github.com/JuliaLang/Morsel.jl) : A Sintra-like micro framework for declaring routes and handling requests, built over HttpServer.jl and Meddle.jl.
- 🏚️ [Requests.jl](https://github.com/JuliaWeb/Requests.jl) : HTTP client written in julia (depends on joyent/http-parser) for HTTP parsing.
- 🏚️ [URIParser.jl](https://github.com/JuliaWeb/URIParser.jl) : Pure julia URI parser. (No `Project.toml`)

## HTML-CSS

- [Cascadia.jl](https://github.com/Algocircle/Cascadia.jl) : A CSS Selector library in Julia.
- [DisplayAs.jl](https://github.com/tkf/DisplayAs.jl) : It provides functions to show objects in a chosen MIME type.

## Email

- [SMTPClient.jl](https://github.com/JuliaWeb/SMTPClient.jl) : An SMTP client to send emails from Julia.
- 🏚️ [Mandrill.jl](https://github.com/aviks/Mandrill.jl) : Mandrill API in Julia.

## Static site generators

- [Franklin.jl](https://github.com/tlienart/Franklin.jl) for static site generation with live Julia code evaulation.
  - [Examples](https://github.com/tlienart/Franklin.jl#docs)
  - [Templates](https://github.com/tlienart/FranklinTemplates.jl)
- [PkgPage.jl](https://tlienart.github.io/PkgPage.jl/) for (package) front-pages, powered by `Franklin.jl`.
