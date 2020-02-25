# Awesome Elasticsearch

#### ← [Awesome TypeScript](https://github.com/dzharii/awesome-typescript) -= Awesome Elasticsearch =- 
[![](https://raw.githubusercontent.com/dzharii/awesome-elasticsearch/master/awesome-elastic-logo.png)](https://github.com/dzharii/awesome-elasticsearch)

# General
## Elastic Stack
* [Elasticsearch](https://www.elastic.co/) official website 
* [Logstash](https://www.elastic.co/products/logstash) is a data pipeline that helps you process logs and other event data from a variety of systems
* [Kibana](https://www.elastic.co/products/kibana) is a data analysis tool that helps to visualize your data; [Kibana Manual docs](https://www.elastic.co/guide/en/kibana/current/discover.html)
* [beats](https://www.elastic.co/products/beats) is the platform for building lightweight, open source data shippers for many types of data you want to enrich with Logstash, search and analyze in Elasticsearch, and visualize in Kibana. 

## Books
* [Deep Learning for Search](https://www.manning.com/books/deep-learning-for-search) - teaches you how to leverage neural networks, NLP, and deep learning techniques to improve search performance. (2019)
* [Relevant Search: with applications for Solr and Elasticsearch](https://www.manning.com/books/relevant-search) - demystifies relevance work. Using Elasticsearch, it teaches you how to return engaging search results to your users, helping you understand and leverage the internals of Lucene-based search engines. (2016) 
* [Elasticsearch in Action](https://www.manning.com/books/elasticsearch-in-action) - teaches you how to build scalable search applications using Elasticsearch (2015)

## Related (awesome) lists
* [frutik/awesome-search](https://github.com/frutik/awesome-search) I am building e-commerce search now. Below are listed some of my build blocks

## Open-source and free products, based on Elasticsearch 
* [Yelp/elastalert](https://github.com/yelp/elastalert) is a modular flexible rules based alerting system written in Python
* [etsy/411](https://github.com/etsy/411) - an Alert Management Web Application https://demo.fouroneone.io (credentials: user/user)
* [appbaseio/mirage](https://github.com/appbaseio/mirage) is a 🔎 GUI for composing Elasticsearch queries
* [exceptionless/Exceptionless](https://github.com/exceptionless/Exceptionless) is an error (exceptions) collecting and reporting server with client bindings for a various programming languages
* [searchkit/searchkit](https://github.com/searchkit/searchkit) is a UI framework based on React to build awesome search experiences with Elasticsearch
* [appbaseio/reactivemaps](https://opensource.appbase.io/reactivemaps) is a React based UI components library for building Airbnb / Foursquare like Maps
* [appbaseio/reactivesearch](https://opensource.appbase.io/reactivesearch) is a library of beautiful React UI components for Elasticsearch
* [appbaseio/dejavu](https://github.com/appbaseio/dejavu/) The missing UI for Elasticsearch; [landing page](https://opensource.appbase.io/dejavu/)
* [Simple File Server](https://github.com/pitchpoint-solutions/sfs) is an Openstack Swift compatible distributed object store that can serve and securely store billions of large and small files using minimal resources.
* [logagent](https://www.npmjs.com/package/@sematext/logagent) a log shipper to parse and ship logs to Elasticsearch including bulk indexing, disk buffers and log format detection. 
* [ItemsAPI](https://github.com/itemsapi/itemsapi) simplified search API for web and mobile (based on Elasticsearch and Express.js)
* [Kuzzle](https://github.com/kuzzleio/kuzzle) - An open-source backend with advanced real-time features for Web, Mobile and IoT that uses ElasticSearch as a database. ([Website](https://kuzzle.io/))
* [SIAC](https://github.com/citybasebrooks/SIAC) - SIAC is an enterprise SIEM built on the ELK stack and other open-source components.
* [Sentinl](https://github.com/sirensolutions/sentinl) - Sentinl is a Kibana alerting and reporting app.
* [Praeco](https://github.com/ServerCentral/praeco/) - Elasticsearch alerting made simple


## Elasticsearch developer tools and utilities
 
### Development and debugging
* [Sense (from Elastic)](https://github.com/elastic/sense/#sense) A JSON aware developer console to Elasticsearch; official and very powerful
* [ES-mode](https://github.com/dakrone/es-mode) An Emacs major mode for interacting with Elasticsearch (similar to Sense)
* [Elasticsearch Cheatsheet](http://elasticsearch-cheatsheet.jolicode.com/) Examples for the most used queries, API and settings for all major version of Elasticsearch
* [Elasticstat](https://github.com/objectrocket/elasticstat) CLI tool displaying monitoring informations like htop
* [Elastic for Visual Studio Code](https://github.com/hsen-dev/vscode-elastic) An extension for developing Elasticsearch queries like Kibana and Sense extention in Visual Studio Code
* [Elastic Builder](https://github.com/sudo-suhas/elastic-builder) A Node.js implementation of the Elasticsearch DSL
* [Bodybuilder](https://github.com/danpaz/bodybuilder) A Node.js elasticsearch query body builder
* [enju](https://github.com/kelp404/enju) A Node.js elasticsearch ORM

### Import and Export
* [Knapsack plugin](https://github.com/jprante/elasticsearch-knapsack)  is an "swiss knife" export/import plugin for Elasticsearch
* [Elasticsearch-Exporter](https://github.com/mallocator/Elasticsearch-Exporter) is a command line script to import/export data from Elasticsearch to various other storage systems
* [esbulk](https://github.com/miku/esbulk) Parallel elasticsearch bulk indexing utility for the command line.
* [elasticdump](https://github.com/taskrabbit/elasticsearch-dump) - tools for moving and saving indices
* [elasticsearch-loader](https://github.com/moshe/elasticsearch_loader) - Tool for loading common file types to elasticsearch including csv, json, and parquet

### Management
* [Vulcanizer](https://github.com/github/vulcanizer) - Github's open sourced cluster management library based on Elasticsearch's REST API. Comes with a high level CLI tool

## Elasticsearch plugins
### Cluster
* [sscarduzio/elasticsearch-readonlyrest-plugin](https://github.com/sscarduzio/elasticsearch-readonlyrest-plugin) Safely expose Elasticsearch REST API directly to the public
* [mobz/elasticsearch-head](https://github.com/mobz/elasticsearch-head) is a powerful and essential plugin for managing your cluster, indices and mapping
* [Bigdesk](http://bigdesk.org/) - Live charts and statistics for elasticsearch cluster
* [Elastic HQ](http://www.elastichq.org/) - Elasticsearch cluster management console with live monitoring and beautiful UI
* [Cerebro](https://github.com/lmenezes/cerebro) is an open source(MIT License) elasticsearch web admin tool. Supports ES 5.x
* [Kopf](https://github.com/lmenezes/elasticsearch-kopf) - Another management plugin that have REST console and *manual* shard allocation
* [Search Guard](https://github.com/floragunncom/search-guard) - Elasticsearch and elastic stack security and alerting for free
* [ee-outliers](https://github.com/NVISO-BE/ee-outliers) - ee-outliers is a framework to detect outliers in events stored in an Elasticsearch cluster.
* [Elasticsearch Comrade](https://github.com/moshe/elasticsearch-comrade) - Elasticsearch admin panel built for ops and monitoring

### Other
* [SIREn Join Plugin for Elasticsearch](https://github.com/sirensolutions/siren-join) This plugin extends Elasticsearch with new search actions and a filter query parser that enables to perform a "Filter Join" between two set of documents (in the same index or in different indexes).

### Integrations and SQL support
* [NLPchina/elasticsearch-sql](https://github.com/NLPchina/elasticsearch-sql/) - Query elasticsearch using familiar SQL syntax. You can also use ES functions in SQL.
* [elastic/elasticsearch-hadoop](https://github.com/elastic/elasticsearch-hadoop) - Elasticsearch real-time search and analytics natively integrated with Hadoop (and Hive)
* [jprante/elasticsearch-jdbc](https://github.com/jprante/elasticsearch-jdbc) - JDBC importer for Elasticsearch
* [pandasticsearch](https://github.com/onesuper/pandasticsearch) - An Elasticsearch client exposing DataFrame API
* [monstache](https://github.com/rwynn/monstache) - Go daemon that syncs MongoDB to Elasticsearch in near realtime

### You know, for search 
* [jprante/elasticsearch-plugin-bundle](https://github.com/jprante/elasticsearch-plugin-bundle) A plugin that consists of a compilation of useful Elasticsearch plugins related to indexing and searching documents

## Kibana plugins and applications
* [elastic/timelion](https://github.com/elastic/timelion) time-series analyses application. Overview and installation guide: Timelion: [The time series composer for Kibana](https://www.elastic.co/blog/timelion-timeline)
* [Kibana Alert App for Elasticsearch](https://github.com/elasticfence/kaae) - Kibana plugin with monitoring, alerting and reporting capabilities
* [VulnWhisperer](https://github.com/austin-taylor/VulnWhisperer) - VulnWhisperer is a vulnerability data and report aggregator.
* [Wazuh Kibana App](https://github.com/wazuh/wazuh-kibana-app) - A Kibana app for working with data generated by [Wazuh](https://wazuh.com/).
* [Datasweet Formula](https://github.com/datasweet-fr/kibana-datasweet-formula) - A real time calculated metric plugin [Datasweet Formula](http://www.datasweet.fr/datasweet-formula/).

### Kibana Visualization plugins
* [nbs-system/mapster](https://github.com/nbs-system/mapster) - a visualization which allows to create live event 3d maps in Kibana
* [Kibana Tag Cloud Plugin](https://github.com/stormpython/tagcloud) - tag cloud visualization plugin based on d3-cloud plugin
* [LogTrail](https://github.com/sivasamyk/logtrail) - a plugin for Kibana to view, analyze, search and tail log events from multiple hosts in realtime with devops friendly interface inspired by Papertrail
* [Analyze API](https://github.com/johtani/analyze-api-ui-plugin) - Kibana 6 application to manipulate the `_analyze` API graphically
* [kbn_network](https://github.com/dlumbrer/kbn_network) - This is a plugin developed for Kibana that displays a network node that link two fields that have been previously selected.

## Discussions and social media
* [/r/elasticsearch](https://www.reddit.com/r/elasticsearch)
* [Elasticsearch forum](https://discuss.elastic.co/)
* [Stackoverflow](http://stackoverflow.com/tags/elasticsearch/hot)
* [Books on Amazon](http://www.amazon.com/s/ref=nb_sb_noss_1?url=search-alias%3Daps&field-keywords=elasticsearch) does not fit well into this category, but worth checking out!
* TODO: Put some good twitter accounts

## Tutorials
* [Centralized Logging with Logstash and Kibana On Ubuntu 14.04](https://www.digitalocean.com/community/tutorial_series/centralized-logging-with-logstash-and-kibana-on-ubuntu-14-04) everything you need to now when you are creating your first Elasticsearch+Logstash+Kibana instance
* [dwyl/learn-elasticsearch](https://github.com/dwyl/learn-elasticsearch) a getting started tutorial with a pack of valuable references
* [Make Sense of your Logs: From Zero to Hero in less than an Hour! by Britta Weber](https://www.youtube.com/watch?v=8vgTBIoF8zs) demonstrates how you can build Elasticsearch + Logstash + Kibana stack to collect and discover your data

## Articles
## System configuration
* [A Useful Elasticsearch Cheat Sheet in Times of Trouble](http://logz.io/blog/elasticsearch-cheat-sheet/)
* [The definitive guide for Elasticsearch on Windows Azure](http://code972.com/blog/2014/07/74-the-definitive-guide-for-elasticsearch-on-windows-azure)
* [Elasticsearch pre-flight checklist](https://asquera.de/blog/2012-11-25/elasticsearch-pre-flight-checklist/)
* [9 Tips on Elasticsearch Configuration for High Performance](https://www.loggly.com/blog/nine-tips-configuring-elasticsearch-for-high-performance/)
* [Best Practices in AWS](https://www.elastic.co/guide/en/elasticsearch/plugins/master/cloud-aws-best-practices.html)
* [How to Secure Elasticsearch and Kibana](https://www.mapr.com/blog/how-secure-elasticsearch-and-kibana) with NGINX, LDAP and SSL :lock:
* [Elasticsearch server on Webfaction using NGINX with basic authorization and HTTPS protocol](http://joanswork.com/webfaction-elasticsearch-server-tutorial/)

### Docker and Elasticsearch
* [Running an Elasticsearch cluster with Docker](https://stefanprodan.com/2016/elasticsearch-cluster-with-docker/)

## Java tuning
* [Elasticsearch Java Virtual Machine settings explained](http://jprante.github.io/2012/11/28/Elasticsearch-Java-Virtual-Machine-settings-explained.html)
* [Tuning Garbage Collection for Mission-Critical Java Applications](https://live.mgm-tp.com/en/tuning-garbage-collection-for-mission-critical-java-applications-tuning-guidelines-for-java-garbage-collection-part-1/)
* [G1: One Garbage Collector To Rule Them All](http://www.infoq.com/articles/G1-One-Garbage-Collector-To-Rule-Them-All)
* [Use Lucene’s MMapDirectory on 64bit platforms, please!](http://blog.thetaphi.de/)
* [Black Magic cookbook](http://product.hubspot.com/blog/g1gc-tuning-your-hbase-cluster)
* [G1GC Fundamentals: Lessons from Taming Garbage Collection](http://product.hubspot.com/blog/g1gc-fundamentals-lessons-from-taming-garbage-collection)
* [JVM Garbage Collector settings
investigation](https://tigase.tech/attachments/download/4808/GC-result.pdf) PDF Comparison of JVM GC    
* [Garbage Collection Settings for Elasticsearch Master Nodes](https://dzone.com/articles/garbage-collection-settings-for-elasticsearch-mast) Fine tunine your garbage collector    
* [Understanding G1 GC Log Format](https://dzone.com/articles/understanding-g1-gc-log-format) To tune and troubleshoot G1 GC enabled JVMs, one must have a proper understanding of G1 GC log format. This article walks through key things that one should know about the G1 GC log format.

How to start using G1
```
#ES_JAVA_OPTS=""
ES_JAVA_OPTS="-XX:-UseParNewGC -XX:-UseConcMarkSweepGC -XX:+UseG1GC"

```

## Scalable Infrastructure and performance
* [The Authoritative Guide to Elasticsearch Performance Tuning (Part 1)](https://qbox.io/blog/authoritative-guide-elasticsearch-performance-tuning-part-1) [Part 2](https://qbox.io/blog/elasticsearch-performance-tuning-part-2-zen) [Part 3](https://qbox.io/index.php?p=blog/authoritative-guide-elasticsearch-performance-tuning-part-3) 
* [Tuning data ingestion performance for Elasticsearch on Azure](https://azure.microsoft.com/en-us/documentation/articles/guidance-elasticsearch-tuning-data-ingestion-performance/) - and not only for Azure. That's a great article about Elasticsearch Performance testing by example
* [Elasticsearch Indexing Performance Cheatsheet](https://blog.codecentric.de/en/2014/05/elasticsearch-indexing-performance-cheatsheet/) - when you plan to index large amounts of data in Elasticsearch (by Patrick Peschlow)
* [Elasticsearch for Logging](http://edgeofsanity.net/article/2012/12/26/elasticsearch-for-logging.html) Elasticsearch configuration tips and tricks from Sanity
* [Scaling Elasticsearch to Hundreds of Developers](http://engineeringblog.yelp.com/2014/11/scaling-elasticsearch-to-hundreds-of-developers.html) by Joseph Lynch @yelp 
* [10 Elasticsearch metrics to watch](http://radar.oreilly.com/2015/04/10-elasticsearch-metrics-to-watch.html)
* [Understanding Elasticsearch Performance](https://joshrendek.com/2015/11/understanding-elasticsearch-performance/)
* [Our Experience of Creating Large Scale Log Search System Using Elasticsearch](http://www.cubrid.org/blog/dev-platform/our-experience-creating-large-scale-log-search-system-using-elasticsearch/) - topology, separate master, data and search balancers nodes
* :open_file_folder: [Elasticsearch on Azure Guidance](https://github.com/Azure/azure-content/blob/master/articles/guidance/guidance-elasticsearch.md) it is 10% on Azure and 90% of a very valuable general information, tips and tricks about Elasticsearch
* [How to avoid the split-brain problem in Elasticsearch](http://blog.trifork.com/2013/10/24/how-to-avoid-the-split-brain-problem-in-elasticsearch/)
* Datadog's series about monitoring Elasticsearch performance:
  * [How to monitor Elasticsearch performance](https://www.datadoghq.com/blog/monitor-elasticsearch-performance-metrics/)
  * [How to collect Elasticsearch metrics](https://www.datadoghq.com/blog/collect-elasticsearch-metrics/)
  * [How to monitor Elasticsearch with Datadog](https://www.datadoghq.com/blog/monitor-elasticsearch-datadog/)
  * [How to solve 5 Elasticsearch performance and scaling problems](https://www.datadoghq.com/blog/elasticsearch-performance-scaling-problems/)
* [Performance Monitoring Essentials - Elasticsearch Edition](https://sematext.com/publications/performance-monitoring-essentials-elasticsearch-edition.pdf)
* [Operator for running Elasticsearch in Kubernetes](https://github.com/zalando-incubator/es-operator)
 
### Integrations
* [Apache Hive integration](https://www.elastic.co/guide/en/elasticsearch/hadoop/current/hive.html)
* [Connecting Tableau to Elasticsearch (READ: How to query Elasticsearch with Hive SQL and Hadoop)](http://ryrobes.com/systems/connecting-tableau-to-elasticsearch-read-how-to-query-elasticsearch-with-hive-sql-and-hadoop/)
* [mradamlacey/elasticsearch-tableau-connector](https://github.com/mradamlacey/elasticsearch-tableau-connector)

### Logging
* [5 Logstash Alternatives](https://sematext.com/blog/2016/09/13/logstash-alternatives/) and typical use cases

### Alerts
* [ElastAlert: Alerting At Scale With Elasticsearch, Part 1](http://engineeringblog.yelp.com/2015/10/elastalert-alerting-at-scale-with-elasticsearch.html) by engineeringblog.yelp.com
* [ElastAlert: Alerting At Scale With Elasticsearch, Part 2](http://engineeringblog.yelp.com/2016/03/elastalert-part-two.html) by engineeringblog.yelp.com
* [Elastalert: implementing rich monitoring with Elasticsearch](https://alexandreesl.com/2016/04/15/elastalert-implementing-rich-monitoring-with-elasticsearch/)

### Time series
* [Elasticsearch as a Time Series Data Store](https://www.elastic.co/blog/elasticsearch-as-a-time-series-data-store) by Felix Barnsteiner
* [Running derivatives on Voyager velocity data](https://www.elastic.co/blog/out-of-this-world-aggregations) By Colin Goodheart-Smithe
* Shewhart Control Charts via Moving Averages: [Part 1](https://www.elastic.co/blog/staying-in-control-with-moving-averages-part-1) - [Part 2](https://www.elastic.co/blog/staying-in-control-with-moving-averages-part-2) by Zachary Tong
* Implementing a Statistical Anomaly Detector: [Part 1](https://www.elastic.co/blog/implementing-a-statistical-anomaly-detector-part-1) - [Part 2](https://www.elastic.co/blog/implementing-a-statistical-anomaly-detector-part-2) - [Part 3](https://www.elastic.co/blog/implementing-a-statistical-anomaly-detector-part-3) by Zachary Tong
 
### Machine Learning
* [Classifying images into Elasticsearch with DeepDetect](http://www.deepdetect.com/tutorials/es-image-classifier/) ([forum thread with discussion](https://discuss.elastic.co/t/categorizing-images-with-deep-learning-into-elasticsearch/33217)) by Emmanuel Benazera
* [Elasticsearch with Machine Learning](https://medium.com/hello-elasticsearch/elasticsearch-amazon-machine-learning-7d7b979c328d#.s50a6d5mn) ([English translation](https://translate.googleusercontent.com/translate_c?depth=1&hl=en&prev=search&rurl=translate.google.com&sl=ja&u=https://medium.com/hello-elasticsearch/elasticsearch-amazon-machine-learning-7d7b979c328d&usg=ALkJrhioEPGsVRglGPFTa6w2ZfM-ydSoeg)) by Kunihiko Kido
* [Recommender System with Mahout and Elasticsearch](https://www.mapr.com/products/mapr-sandbox-hadoop/tutorials/recommender-tutorial)


### Use cases for Elasticsearch
* [Data Infrastructure at IFTTT](http://engineering.ifttt.com/data/2015/10/14/data-infrastructure/) Elasticsearch, Kafka, Apache Spark, Redhsift, other AWS services 
* [OFAC compliance with Elasticsearch](https://israelwebdev.wordpress.com/2015/01/19/ofac-compliance-with-elasticsearch/) using AWS
* [Building a Streaming Search Platform](https://blog.insightdatascience.com/building-a-streaming-search-platform-61a0d5a323a8#.f4b0rvae5) - 
Streaming Search on Tweets: Storm, Elasticsearch, and Redis

## Other
* [LogZoom, a fast and lightweight substitute for Logstash](https://packetzoom.com/blog/logzoom-a-fast-and-lightweight-substitute-for-logstash.html)
* [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) - Free and open source log management (based on ES)
* [Fluentd vs. Logstash for OpenStack Log Management](http://www.slideshare.net/td-nttcom/fluentd-vs-logstash-for-openstack-log-management)
* [Building a Directory Map With ELK](http://david.pilato.fr/blog/2015/12/10/building-a-directory-map-with-elk/)
* [Structured logging with ELK - part 1](http://engineering.laterooms.com/structured-logging-with-elk-part-1/)
* [Search for :yum: Emoji with Elasticsearch :mag_right:](http://jolicode.com/blog/search-for-emoji-with-elasticsearch)
* [Complete Guide to the ELK Stack](http://logz.io/learn/complete-guide-elk-stack/)
* [logiq](https://github.com/sloniki/logiq) - Simple WebUI Monitoring Tool for Logstash ver. 5.0 and up
* [ElasticSearch Report Engine](https://malike.github.io/elasticsearch-report-engine/) - An ElasticSearch plugin to return    query results as either PDF,HTML or CSV. 

## Videos
### Overviews
* [Elasticsearch for logs and metrics: A deep dive – Velocity 2016](https://www.youtube.com/watch?v=44QQEI9CJQQ) by Sematext Developers
* [Elasticsearch in action Thijs Feryn](https://www.youtube.com/watch?v=oPObRc8tHgQ) a beginner overview
* [Getting Down and Dirty with ElasticSearch by Clinton Gormley ](https://www.youtube.com/watch?v=7FLXjgB0PQI)
* [How we scaled Raygun](https://raygun.io/blog/2014/05/talk-how-we-scaled-raygun-using-technologies-like-elastic-search-featuring-iron-man/)
* [Getting started with Elasticsearch](https://www.youtube.com/watch?v=60UsHHsKyN4&list=PLw5h0DiJ-9PDStvJYc1LOZiEm1ehlEKLP)
* [Speed is a Key: Elasticsearch under the Hood](https://www.youtube.com/watch?v=vruklYSW4jg) introduction + basic performance optimization
* [$$ Pluralsight: Getting Started With Elasticsearch for .NET Developers](http://www.pluralsight.com/courses/elasticsearch-for-dotnet-developers) this course will introduce users to Elasticsearch, how it works, and how to use it with .NET projects. 
* [$$ Complete Guide to Elasticsearch](https://www.udemy.com/elasticsearch-complete-guide/) Comprehensive guide to Elasticsearch, the popular search engine built on Apache Lucene
* [How Elasticsearch powers the Guardian's newsroom](http://www.infoq.com/presentations/elasticsearch-guardian)
* [Elasticsearch Query Editor in Grafana](https://www.youtube.com/watch?v=hEztaMtobXw)
* [Scale Your Metrics with Elasticsearch](https://www.youtube.com/watch?v=pZJLlOCuPpg) 2019 by Philipp Krenn (Elastic) optimization tips and tricks

### Advanced
* [#bbuzz 2015: Adrien Grand – Algorithms and data-structures that power Lucene and Elasticsearch](https://www.youtube.com/watch?v=eQ-rXP-D80U)
* [Rafał Kuć - Running High Performance Fault-tolerant Elasticsearch Clusters on Docker](https://www.youtube.com/watch?list=PLq-odUc2x7i_-qsarQo7MNsrYz3rlXGMu&v=D2zR-6Tke8o) and [slides](https://sematext.com/blog/2016/06/08/elasticsearch-in-docker/)
* [Working with Elasticsearch - Search, Aggregate, Analyze, and Scale Large Volume Datastores](http://shop.oreilly.com/product/0636920043898.do) -  O'Reilly Media
* [End-to-end Recommender System with Spark and Elasticsearch](https://www.youtube.com/watch?v=sa_Y488vj0M) by Nick Pentreath & Jean-François Puget. [Slide deck](http://www.slideshare.net/sparktc/spark-ml-meedup-pentreath-puget)

### Code, configuration file samples and other gists
* [Elasticsearch config for a write-heavy cluster](https://gist.github.com/reyjrar/4364063) - reyjrar/elasticsearch.yml
* [chenryn/ESPL - Elastic Search Processing Language](https://github.com/chenryn/ESPL) PEG parser sample for SPL to Elasticsearch DSL
* [thomaspatzke/EQUEL](https://github.com/thomaspatzke/EQUEL) an Elasticsearch QUEry Language, based on G4 grammar parser

## Who is using elasticsearch?
[Yelp](http://engineeringblog.yelp.com/2015/10/how-we-use-deep-learning-to-classify-business-photos-at-yelp.html),
[IFTTT](http://engineering.ifttt.com/data/2015/10/14/data-infrastructure/),
[StackExchange](http://stackexchange.com/performance),
[Raygun](https://raygun.io/blog/2014/02/search-improvements-at-raygun/),
[Mozilla](https://www.youtube.com/watch?v=lWKEphKIG8U),
[Spotify](https://labs.spotify.com/2015/11/17/monitoring-at-spotify-introducing-heroic/),
[CERN](https://medium.com/@ghoranyi/needle-in-a-haystack-873c97a99983),
[NASA](https://www.elastic.co/elasticon/2015/sf/unlocking-interplanetary-datasets-with-real-time-search)
[Zalando](https://www.elastic.co/fr/videos/creating-the-fashion-experience-of-the-future-with-elasticsearch-at-zalando)

## I want more! (Elasticsearch related resources)
* [Technology Explained Blog](https://alexandreesl.com/)
* [EagerElk](http://blog.eagerelk.com/)
* [Tim Roes Blog](https://www.timroes.de/)

# Contributing
* Make sure you are about to post a valuable resource that belongs to this list
* Do NOT group ++Add and --Remove changes in same PR. Make them separate pull requests
* Use spellchecker
* All spelling and grammar corrections are welcome (except for the rule above)
* Fork this repo, do your edits, send the pull request
* Feel free to create any new sections
* Do not even try to add this repo to any awesome-awesome-* lists 
 
#### ← [Awesome TypeScript](https://github.com/dzharii/awesome-typescript) -= Awesome Elasticsearch =- 


