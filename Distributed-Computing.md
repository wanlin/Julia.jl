Distributed (Cloud/ Cluster/ Grid) computing, Parallel computing, GIS, Networking, frameworks and other Web related things go here:

* [DISTRIBUTED-PARALLEL](#distributed-parallel) 
* [INTERNET](#internet)
   * [Template Engines](#template-engines)
   * [WIDE](#wide)
   * [WWW](#www)
* [NETWORKING](#networking)


# DISTRIBUTED-PARALLEL
**Cloud/ Cluster**
* AWS.jl :: [supports the EC2 and S3 API's, letting you start and stop EC2 instances dynamically](https://github.com/amitmurthy/AWS.jl)
* ChainedVectors.jl :: [Few utility types over Julia Vector type](https://github.com/tanmaykm/ChainedVectors.jl)
* ClusterManagers.jl :: [Support for different clustering technologies](https://github.com/nlhepler/ClusterManagers.jl)
* HDFS.jl :: [HDFS interface for Julia as a wrapper over Hadoop HDFS library.](https://github.com/tanmaykm/HDFS.jl)
* LCJC.jl :: [Loosely Coupled Julia Clusters](https://github.com/amitmurthy/LCJC.jl)
* PTools.jl :: [A collection of utilities for parallel computing in Julia](https://github.com/amitmurthy/PTools.jl)
* SGEArrays.jl :: [SGEArray implements a simple iterator in Julia to efficiently handle Sun Grid Engine task arrays](https://github.com/davidavdav/SGEArrays.jl)

##### DOCS
* [Parallel Computing](http://docs.julialang.org/en/latest/manual/parallel-computing/)
* [How to use AWS EC2 machines via addprocs for parallel computing](http://docs.julialang.org/en/latest/stdlib/base/#parallel-computing).



# INTERNET
## Template Engines
* Mustache.jl: [Port of mustache.js to julia]](https://github.com/jverzani/Mustache.jl)

## WIDE
* JuliaWebRepl.jl :: https://github.com/vtjnash/JuliaWebRepl.jl

## WWW
* ConfParser.jl :: [Julia package for parsing configuration files](https://github.com/dotslashb/ConfParser.jl) utilizing ini, http, and simple configuration syntaxes.
* JuliaWebServer :: [a webserver for julia](https://github.com/chzyer/JuliaWebServer)
* Laurence.jl :: https://github.com/mneudert/Laurence.jl
* LibCURL.jl :: A thin [wrapper of libCURL](https://github.com/amitmurthy/LibCURL.jl) in Julia.
* PkgGithubRepo.jl :: [Get the Github repository information for a Julia package installed in Ubuntu](https://github.com/thiruk/PkgGithubRepo.jl)
* RestClient.jl :: [A simple REST client for Julia](https://github.com/analyzere/RestClient.jl)
* Requests.jl:: [Http client written in julia (depends on joyent/http-parser) for HTTP parsing](https://github.com/loladiro/Requests.jl). 
* Romeo.jl :: [Another HTTP server to log requests, events, responses](https://github.com/mneudert/Romeo.jl)
* SimJulia.jl:: [ is a combined continuous time / discrete event process oriented simulation framework](https://github.com/BenLauwens/SimJulia.jl) written in Julia inspired by the Simula library DISCO and the Python library SimPy.
* UAParser.jl:: A package to [parse user-agent strings](https://github.com/randyzwitch/UAParser.jl) in Julia, a Julia port of a multi-language port of a parser created by Browserscope, of which a YAML file has been provided under Apache License V2.0. To install, use Pkg.clone("https://github.com/randyzwitch/UAParser.jl"), as the package is yet to be a part of the Julia package repository in METADATA.jl.
* URIParser.jl: is a [URI parser](https://github.com/loladiro/URIParser.jl) implemented in Julia.
* URITemplate.jl :: [This package provides URI Template interpolation by implementing (RFC 6570)](https://github.com/loladiro/URITemplate.jl)
* WWWClient.jl: is a [HTTP client](https://github.com/loladiro/WWWClient.jl) written in julia, and depends on "joyent/http-parser" for HTTP parsing. 
* ZMQ.jl:: [Julia interface to ZeroMQ](https://github.com/JuliaLang/ZMQ.jl)
* WEBSTACK :: The [Julia Webstack](http://juliawebstack.org) is a family of modules for building web services, hosting the documentation for Morsel, Meddle, WebSockets, HttpServer, HttpParser, and HttpCommon...
   * *DOCS* :: [TCP Sockets documentation for webstack.jl](http://blog.leahhanson.us/using-tcp-sockets-in-julia.html)
   * HttpServer.jl :: [a basic, non-blocking HTTP server](https://github.com/JuliaLang/HttpServer.jl) in Julia.
   * Meddle.jl :: is the [ middleware stack for use with HttpServer.jl](https://github.com/JuliaLang/Meddle.jl).
   * Morsel.jl :: is a Sintra-like [micro framework for declaring routes and handling requests](https://github.com/JuliaLang/Morsel.jl), built over HttpServer.jl and Meddle.jl.
   * HttpCommon.jl :: [Provides types and helper functions for dealing with the HTTP protocol](https://github.com/JuliaLang/HttpCommon.jl) in Julia.
   * HttpParser.jl :: [Julia wrapper for Joyent's http-parser](https://github.com/JuliaLang/HttpParser.jl).
   * WebSockets.jl :: [A WebSockets server library](https://github.com/JuliaLang/WebSockets.jl) for Julia.



# NETWORKING
* Dates.jl :: [A Date and DateTime implementation for Julia](https://github.com/karbarcca/Dates.jl)
* Juliaflow :: [is a controller for software-defined networking (SDN) that implements the OpenFlow Controller Specification 1.0.0](https://github.com/pchronz/juliaflow)
* [PosixCalendar.jl ::](https://github.com/dejakaymac/PosixCalendar.jl)
* SMTPClient.jl :: An [SMTP client to send emails](https://github.com/aviks/SMTPClient.jl) from Julia.
* StatsdClient.jl :: [A simple Julia implementation of a statsd client](https://github.com/forio/StatsdClient.jl)
* UUID.jl :: [A universally unique identifier (UUID) is an identifier standard, are 128 bits long, and require no central registration process](https://github.com/forio/UUID.jl)

## Security
* Etcd.jl :: [Julia client for etcd](https://github.com/rened/Etcd.jl)
* GnuTLS.jl :: [Transport Level Security for Julia Streams provided by GnuTLS](https://github.com/loladiro/GnuTLS.jl).

