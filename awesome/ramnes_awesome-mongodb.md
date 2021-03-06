# Info come from [ramnes/awesome-mongodb](https://github.com/ramnes/awesome-mongodb)
![Awesome MongoDB](logo.png)

# Awesome MongoDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome MongoDB resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list by [contributing](CONTRIBUTING.md)!

## Table of Contents
 - [Resources](#resources)
   - [Documentation](#documentation)
   - [Articles](#articles)
   - [Books](#books)
   - [Talks](#talks)
   - [Tutorials](#tutorials)
   - [More](#more)
 - [Libraries](#libraries)
   - [C](#c)
   - [C++](#c-1)
   - [C#/.NET](#cnet)
   - [Delphi](#delphi)
   - [Elixir](#elixir)
   - [Erlang](#erlang)
   - [Go](#go)
   - [Haskell](#haskell)
   - [Java](#java)
   - [JavaScript](#javascript)
   - [Julia](#julia)
   - [Lisp](#lisp)
   - [Mathematica](#mathematica)
   - [Perl](#perl)
   - [PHP](#php)
   - [Python](#python)
   - [R](#r)
   - [Ruby](#ruby)
   - [Rust](#rust)
   - [Scala](#scala)
 - [Tools](#tools)
   - [Administration](#administration)
   - [Big Data](#big-data)
   - [Deployment](#deployment)
   - [Desktop](#desktop)
   - [Monitoring](#monitoring)
   - [Shell](#shell)
   - [Web](#web)
 - [Applications](#applications)

## Resources
### Documentation
 - [MongoDB introduction](https://docs.mongodb.org/manual/core/introduction/)
 - [MongoDB documentation](https://docs.mongodb.org/manual/)
 - [MongoDB tutorials](https://docs.mongodb.org/manual/tutorial/)

### Articles
 - [Five Things About Scaling MongoDB (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/five-things/) - Scale 101
 - [Optimizing MongoDB Compound Indexes (A. Jesse Jiryu Davis, MongoDB Inc.)](http://emptysqua.re/blog/optimizing-mongodb-compound-indexes/) - Everything you need/have to know about indexes
 - [Server Discovery And Monitoring In PyMongo, Perl, And C (A. Jesse Jiryu Davis, MongoDB Inc.) ](https://emptysqua.re/blog/server-discovery-and-monitoring-in-pymongo-perl-and-c/)
 - [Monitoring MongoDB performance metrics (Jean-Mathieu Saponaro, Datadog)](https://www.datadoghq.com/blog/monitoring-mongodb-performance-metrics-wiredtiger/)

### Books
 - [MongoDB Applied Design Patterns (Rick Copeland)](http://shop.oreilly.com/product/0636920027041.do)
 - [The Little MongoDB Book](http://openmymind.net/2011/3/28/The-Little-MongoDB-Book/) - Basic introduction to MongoDB

### Talks
 - [MongoDB Schema Design (Tugdual Grall, MongoDB Inc.)](https://www.youtube.com/watch?v=csKBT8zkRf0) [47']
 - [Partial and Fuzzy Matching with MongoDB (John Page, MongoDB Inc.)](https://www.youtube.com/watch?v=hXbLHInH5qU) [35']
 - [Scaling MongoDB on Amazon Web Services (Michael Saffitz, Apptentive)](https://www.youtube.com/watch?v=bkjVhEQocFI) [50']

### Tutorials
 - [Create a TV Show Tracker Using AngularJS, Node.js, and MongoDB](http://sahatyalkabov.com/create-a-tv-show-tracker-using-angularjs-nodejs-and-mongodb/) - Build a REST API using Mongoose to create and retrieve data from MongoDB
 - [Write a Tumblelog Application with Flask and MongoEngine](https://docs.mongodb.org/ecosystem/tutorial/write-a-tumblelog-application-with-flask-mongoengine/) - Nice Python tutorial hidden into the official Python driver documentation
 - [Kubernetes examples](https://github.com/kubernetes/kubernetes/tree/master/examples/nodesjs-mongodb) - Deployment tutorial of a basic Node.js and MongoDB web stack on [Kubernetes](https://kubernetes.io/docs/whatisk8s/)

### More
 - [MongoDB source code](https://github.com/mongodb/mongo) :star:12917
 - [MongoDB University](https://university.mongodb.com/) - Certifications and free online courses
 - [MongoDB Cloud Manager](https://www.mongodb.com/cloud/) - MongoDB Inc. cloud offer
 - [MongoLab](https://mongolab.com/) - Fully managed MongoDB-as-a-Service
 - [Scalegrid](https://scalegrid.io) - Fully managed MongoDB-as-a-Service (with option to bring your own Azure/AWS account)

## Libraries
### C
 - [mongo-c-driver](https://github.com/mongodb/mongo-c-driver) - Official C driver :star:374

### C++
 - [mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - Official C++ driver :star:431

### C#/.NET ###
 - [mongo-csharp-driver](https://github.com/mongodb/mongo-csharp-driver) - Official C# driver :star:1764
 - [mongo-queue-csharp](https://github.com/dominionenterprises/mongo-queue-csharp) - C# message queue backed by MongoDB
 - [MongoDB Messaging](https://github.com/loresoft/MongoDB.Messaging) - Lightweight queue pub/sub processing library :star:38
 - [MongoRepository](https://github.com/RobThree/MongoRepository) - Repository abstraction layer on top of the C# driver :star:200

### Delphi
 - [TMongoWire](https://github.com/stijnsanders/TMongoWire) - Minimal community Delphi driver :star:69

### Elixir
 - [mongodb](https://github.com/ankhers/mongodb) - Community Elixir driver :star:234
 - [mongodb_ecto](https://github.com/ankhers/mongodb_ecto) - Adapter for the Ecto database wrapper :star:246

### Erlang
 - [mongodb-erlang](https://github.com/comtihon/mongodb-erlang) - Community Erlang driver :star:262

### Go
 - [mgo](https://github.com/go-mgo/mgo) - Community Go driver :star:1918

### Haskell
 - [mongodb](https://github.com/mongodb-haskell/mongodb/) - Community Haskell driver

### Java
 - [Jongo](https://github.com/bguerout/jongo) - Query in Java as in Mongo shell :star:479
 - [Hibernate OGM](https://github.com/hibernate/hibernate-ogm) - The power and simplicity of JPA for NoSQL datastores :star:243
 - [mongo-java-driver](https://github.com/mongodb/mongo-java-driver) - Official Java driver :star:1915
 - [mongo-queue-java](https://github.com/gaillard/mongo-queue-java) - Java message queue backed by MongoDB :star:28
 - [mongoFS](https://github.com/dbuschman7/mongoFS) - An enhancement of MongoDB's GridFS to allow for more features and capabilities :star:18
 - [Mongojack](https://github.com/mongojack/mongojack) - Based on Jackson, allows you to easily handle your mongo objects as POJOs :star:190
 - [Morphia](https://github.com/mongodb/morphia) - Official Java ODM :star:1231
 - [Morphium](https://github.com/sboesebeck/morphium) - Java ODM and caching layer :star:44
 - [Mungbean](https://github.com/jannehietamaki/mungbean) - Community driver for languages running on the JVM :star:20
 - [Spring Data MongoDB](https://github.com/spring-projects/spring-data-mongodb) - Spring based, object-document support and repositories for MongoDB :star:793

### JavaScript
 - [Camo](https://github.com/scottwrobinson/camo) - Class-based ES6 ODM for Mongo-like databases :star:389
 - [MEAN.JS](https://github.com/meanjs/mean) - Full-Stack based on MongoDB, Express, AngularJS, and Node.js :star:4457
 - [MERN (mern-starter)](https://github.com/Hashnode/mern-starter) - Full-Stack based on MongoDB, Express, React and Node.js :star:4327
 - [Mongoose](https://github.com/Automattic/mongoose) - Node.js asynchronous ODM :star:14507
 - [mongration](https://github.com/eberhara/mongration) - Node.js migration framework :star:46
 - [Moonridge](https://github.com/capaj/Moonridge) - Framework with live querying on top of Mongoose and socket.io :star:55
 - [node-mongodb-native](https://github.com/mongodb/node-mongodb-native) - Official Node.js driver :star:6417

### Julia
 - [Mongo.jl](https://github.com/Lytol/Mongo.jl) - Bindings on MongoDB official C driver :star:27

### Lisp
 - [cl-mongo](https://github.com/fons/cl-mongo) - Community Common Lisp interface :star:111
 - [mongo-cl-driver](https://github.com/archimag/mongo-cl-driver) Community Common Lisp driver
 - [mongo-el](https://github.com/m2ym/mongo-el) - Community Emacs Lisp driver :star:42

### Mathematica
 - [MongoDBLink](https://github.com/zbjornson/MongoDBLink) - Community Mathematica driver :star:14

### Perl
 - [mongo-perl-driver](https://github.com/mongodb/mongo-perl-driver) - Official Perl driver :star:189

### PHP
 - [Doctrine MongoDB](https://github.com/doctrine/mongodb) - Wrapper around the native PHP Mongo PECL extension to provide additional functionality :star:323
 - [eloquent-mongodb-repository](https://github.com/PHPRepository/php-eloquent-mongodb-repository) - Repository implementation built on top of laravel-mongodb :star:11
 - [laravel-mongodb](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder for Laravel :star:3050
 - [mongodb-repository](https://github.com/PHPRepository/php-mongodb-repository) - Repository implementation :star:5
 - [pecl/mongodb](https://github.com/mongodb/mongo-php-driver) - Official PHP driver :star:450

### Python
 - [Flask-PyMongo](https://github.com/dcrosta/flask-pymongo) - PyMongo support for Flask applications :star:374
 - [MongoEngine](https://github.com/MongoEngine/mongoengine) - Python ODM on top of PyMongo :star:2053
 - [MongoLog](https://github.com/puentesarrin/mongodb-log) - MongoDB logging handler :star:106
 - [Mongo-Thingy](https://github.com/numberly/mongo-thingy) - The most Pythonic and friendly-yet-powerful way to use MongoDB :star:10
 - [Motor](https://github.com/mongodb/motor) - Non-blocking Python driver for Tornado applications :star:901
 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - Official (and recommended) Python driver :star:2213
 - [minimongo](https://github.com/slacy/minimongo) - A lightweight, schemaless, Pythonic Object-Oriented interface :star:302
 - [scrapy-mongodb](https://github.com/sebdah/scrapy-mongodb) - MongoDB pipeline for Scrapy :star:239
 - [μMongo](https://github.com/Scille/umongo) - Driver-independent (async/sync) ODM based on marshmallow :star:68

### R
 - [mongolite](https://github.com/jeroenooms/mongolite) - Fast and Simple MongoDB Client for R :star:152

### Ruby
 - [mongo-ruby-driver](https://github.com/mongodb/mongo-ruby-driver) - Official Ruby driver :star:1326
 - [Mongoid](https://github.com/mongodb/mongoid) - Ruby ODM framework :star:3579

### Rust
 - [mongo-rust-driver-prototype](https://github.com/mongodb-labs/mongo-rust-driver-prototype) - Prototype driver written for Rust 1.x and MongoDB 3.0.x :star:225

### Scala
 - [mongo-scala-driver](https://github.com/mongodb/mongo-scala-driver) - Official Scala driver :star:189
 - [ReactiveMongo](https://github.com/ReactiveMongo/ReactiveMongo) - Non-blocking Scala driver :star:742
 - [Spark-MongoDB](https://github.com/Stratio/Spark-MongoDB) - Read/write data with Spark SQL :star:291

## Tools
### Administration
 - [mgodatagen](https://github.com/feliixx/mgodatagen) - Random data generator for MongoDB :star:16
 - [mongo_fdw](https://github.com/EnterpriseDB/mongo_fdw) - PostgreSQL foreign data wrapper for MongoDB :star:123
 - [mongoctl](https://github.com/mongolab/mongoctl) - Manage MongoDB servers and replica sets using JSON configurations :star:167
 - [MongoDB Smasher](https://github.com/duckie/mongo_smasher) - Generate randomized datasets and benchmark your MongoDB setup :star:19
 - [mongodb-tools](https://github.com/jwilder/mongodb-tools) - Three neat Python scripts to work with collections and indexes :star:248
 - [Mongoeye](https://github.com/mongoeye/mongoeye) - Schema and data analyzer: explore data in your collections :star:17
 - [Mongolastic](https://github.com/ozlerhakan/mongolastic) - A dataset migration tool from MongoDB to Elasticsearch and vice versa :star:67
 - [MongoMultiMaster](https://github.com/rick446/mmm) - Multi-Master MongoDB replication :star:54
 - [MoSQL](https://github.com/stripe/mosql) - MongoDB to PostgreSQL streaming replication :star:1418
 - [mtools](https://github.com/rueckstiess/mtools) - Collection of scripts to set up MongoDB test environments and parse and visualize MongoDB log files :star:1037
 - [nginx-gridfs](https://github.com/mdirolf/nginx-gridfs) - Nginx module for serving files from MongoDB's GridFS :star:764
 - [nginx-mongodb-rest](https://github.com/minhajuddin/nginx-mongodb-rest) - MongoDB REST client written as an Nginx module :star:31
 - [Variety](https://github.com/variety/variety) - Schema analyzer: see what fields are in your collection and what's their content :star:1089

### Big Data
 - [mongo-hadoop](https://github.com/mongodb/mongo-hadoop) - MongoDB connector for Hadoop :star:1315

### Deployment
 - [ansible-role-mongodb](https://github.com/UnderGreen/ansible-role-mongodb) - Ansible role :star:124
 - [chef-mongodb](https://github.com/edelight/chef-mongodb) - Chef cookbook :star:384
 - [Dockerfile](https://github.com/dockerfile/mongodb) :star:233
 - [Helm Chart](https://github.com/kubernetes/charts/tree/master/stable/mongodb) - Bootstraps a MongoDB deployment on a [Kubernetes](https://kubernetes.io/docs/whatisk8s/) cluster using the [Helm](https://github.com/kubernetes/helm) package manager.
 - [puppetlabs-mongodb](https://github.com/puppetlabs/puppetlabs-mongodb) - Puppet module :star:83

### Desktop
 - [MongoChef](http://3t.io/mongochef) - Cross-platform MongoDB manager, stable and powerful
 - [MongoBooster](http://www.mongobooster.com) - Feature-rich but easy-to-use cross-platform MongoDB manager
 - [MongoHub](https://github.com/jeromelebel/MongoHub-Mac) - Mac native client :star:2246
 - [Mongotron](http://mongotron.io/) - Cross-platform, open-source MongoDB client built with Electron
 - [Robomongo](https://github.com/paralect/robomongo) - Native and cross-platform MongoDB manager :star:6392

### Monitoring
 - [check_mongodb](https://github.com/dalenys/check_mongodb) - Nagios plugin (in Bash)
 - [Datadog](https://www.datadoghq.com/blog/monitor-mongodb-performance-with-datadog?ref=awesome) - SaaS-based MongoDB monitoring
 - [Mongoop](https://github.com/Lujeni/mongoop) - Long operations monitoring and alerting :star:32
 - [Motop](https://github.com/tart/motop) - MongoDB top clone :star:62
 - [mtop](https://github.com/beaufour/mtop) - Another top clone :star:50
 - [mongo-munin](https://github.com/erh/mongo-munin) - Collection of Munin plugins :star:148
 - [mongomon](https://github.com/pcdummy/mongomon) - More Munin plugins :star:25
 - [nagios-plugin-mongodb](https://github.com/mzupan/nagios-plugin-mongodb) - Nagios plugin (in Python)

### Shell
 - [mongo-hacker](https://github.com/TylerBrock/mongo-hacker) - MongoDB shell enhancements :star:1342

### Web
 - [adminMongo](https://github.com/mrvautin/adminMongo) - Web-based user interface to handle connections and databases needs :star:1228
 - [Compass](https://www.mongodb.com/products/compass) - MongoDB Inc. commercial online GUI and data-visualization platform
 - [HumongouS.io](https://www.humongous.io) - Easy online GUI and data-visualization dashboards
 - [mongo-express](https://github.com/mongo-express/mongo-express) - Web-based admin interface written with Node.js, Express and Bootstrap3 :star:2502
 - [mongoadmin](https://github.com/thomasst/mongoadmin) - Admin interface for MongoDB built using Django and Bootstrap :star:259
 - [mongri](https://github.com/dongri/mongri) - Web-based user interface for MongoDB (written in JavaScript)
 - [Rockmongo](https://github.com/iwind/rockmongo) - PHPMyAdmin for MongoDB, sort of :star:806

## Applications
 - [Leanote](https://github.com/leanote/leanote) - Evernote clone built with Go and MongoDB :star:6530
 - [Quokka](https://github.com/quokkaproject/quokka) - Python CMS built on top of Flask and MongoDB :star:1768
 - [uptime](https://github.com/fzaninotto/uptime) - Remote monitoring application using Node.js, MongoDB, and Bootstrap :star:3382

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Guillaume Gelin](https://github.com/ramnes) has waived all copyright and related or neighboring rights to this work.

