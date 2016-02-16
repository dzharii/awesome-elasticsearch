# Awesome Elasticsearch

#### ← [Awesome TypeScript](https://github.com/dzharii/awesome-typescript) -= Awesome Elasticsearch =- 
[![](https://raw.githubusercontent.com/dzharii/awesome-elasticsearch/master/awesome-elastic-logo.png)](https://github.com/dzharii/awesome-elasticsearch)


# RSS Updates
Don't miss new commits! Subscribe via RSS / Atom channel.  
Or use IFTTT to forward the RSS updates into your favourite reader.    
* [RSS feed -- Feedburner](http://feeds.feedburner.com/RecentCommitsToAwesome-elasticsearchmaster)
* [Github's raw Atom feed](https://github.com/dzharii/awesome-elasticsearch/commits/master.atom)


# General
## ELK Stack
* [Elasticsearch](https://www.elastic.co/) official website 
* [Logstash](https://www.elastic.co/products/logstash) is a data pipeline that helps you process logs and other event data from a variety of systems
* [Kibana](https://www.elastic.co/products/kibana) is a data analysis tool that helps to visualize your data 

## Open-source and free products, based on Elasticsearch 
* [Yelp/elastalert](https://github.com/yelp/elastalert) is a modular flexible rules based alerting system written in Python
* [exceptionless/Exceptionless](https://github.com/exceptionless/Exceptionless) is an error (exceptions) collecting and reporting server with client bindings for a various programming languages
* [searchkit/searchkit](https://github.com/searchkit/searchkit) is a UI framework based on React to build awesome search experiences with Elasticsearch

## Elasticsearch developer tools and utilities
 
### Development and debugging
* [Sense (from Elastic)](https://github.com/elastic/sense/#sense) A JSON aware developer console to ElasticSearch; official and very powerful
* [Sense (Google Chrome extension)](https://chrome.google.com/webstore/detail/sense-beta/lhjgkmllcaadmopgmanpapmpjgmfcfig?hl=en) A JSON aware developer console to ElasticSearch; unofficial but very powerful
* [ES-mode](https://github.com/dakrone/es-mode) An Emacs major mode for interacting with Elasticsearch (similar to Sense)

### Import and Export
* [Knapsack plugin](https://github.com/jprante/elasticsearch-knapsack)  is an "swiss knife" export/import plugin for Elasticsearch
* [Elasticsearch-Exporter](https://github.com/mallocator/Elasticsearch-Exporter) is a command line script to import/export data from ElasticSearch to various other storage systems
* [esbulk](https://github.com/miku/esbulk) Parallel elasticsearch bulk indexing utility for the command line.
* [elasticdump](https://github.com/taskrabbit/elasticsearch-dump) - tools for moving and saving indicies

## Elasticsearch plugins
### Cluster
* [mobz/elasticsearch-head](https://github.com/mobz/elasticsearch-head) is a powerful and essential plugin for managing your cluster, indices and mapping
* [Bigdesk](http://bigdesk.org/) - Live charts and statistics for elasticsearch cluster
* [Elastic HQ](http://www.elastichq.org/) - Elasticsearch cluster management console with live monitoring and beautiful UI

### Integrations and SQL support
* [NLPchina/elasticsearch-sql](https://github.com/NLPchina/elasticsearch-sql/) - Query elasticsearch using familiar SQL syntax. You can also use ES functions in SQL.
* [elastic/elasticsearch-hadoop](https://github.com/elastic/elasticsearch-hadoop) - Elasticsearch real-time search and analytics natively integrated with Hadoop (and Hive)

### You know, for search 
* [jprante/elasticsearch-plugin-bundle](https://github.com/jprante/elasticsearch-plugin-bundle) A plugin that consists of a compilation of useful Elasticsearch plugins related to indexing and searching documents

## Kibana plugins and applications
* [elastic/timelion](https://github.com/elastic/timelion) time-series analyses application. Overview and installation guide: Timelion: [The time series composer for Kibana](https://www.elastic.co/blog/timelion-timeline)

## Discussions and social media
* [/r/elasticsearch](https://www.reddit.com/r/elasticsearch)
* [Elasticsearch forum](https://discuss.elastic.co/)
* [Stackoverflow](http://stackoverflow.com/tags/elasticsearch/hot)
* [Books on Amazon](http://www.amazon.com/s/ref=nb_sb_noss_1?url=search-alias%3Daps&field-keywords=elasticsearch) does not fit well into this category, but worth to check this out!
* TODO: Put some good twitter accounts

## Tutorials
* [Centralized Logging with Logstash and Kibana On Ubuntu 14.04](https://www.digitalocean.com/community/tutorial_series/centralized-logging-with-logstash-and-kibana-on-ubuntu-14-04) everything you need to now when you are creating your first Elasticsearch+Logstash+Kibana instance
* [dwyl/learn-elasticsearch](https://github.com/dwyl/learn-elasticsearch) a getting started tutorial with a pack of valuable references
* [Make Sense of your Logs: From Zero to Hero in less than an Hour! by Britta Weber](https://www.youtube.com/watch?v=8vgTBIoF8zs) demonstrates how you can build Elasticsearch + Logstash + Kibana stack to collect and discover your data

## Articles
## System configuration
* [The definitive guide for Elasticsearch on Windows Azure](http://code972.com/blog/2014/07/74-the-definitive-guide-for-elasticsearch-on-windows-azure)
* [ElasticSearch pre-flight checklist](http://asquera.de/opensource/2012/11/25/elasticsearch-pre-flight-checklist/)
* [9 Tips on ElasticSearch Configuration for High Performance](https://www.loggly.com/blog/nine-tips-configuring-elasticsearch-for-high-performance/)

## Scalable Infrastructure and performance
* [Maximizing Data Ingestion Performance with Elasticsearch on Azure](https://azure.microsoft.com/nb-no/documentation/articles/guidance-elasticsearch-data-ingestion/) - and not only for Azure. That's a great article about Elasticsearch Performance testing by example
* [Elasticsearch Indexing Performance Cheatsheet](https://blog.codecentric.de/en/2014/05/elasticsearch-indexing-performance-cheatsheet/) - when you plan to index large amounts of data in Elasticsearch (by Patrick Peschlow)
* [ElasticSearch for Logging](http://edgeofsanity.net/article/2012/12/26/elasticsearch-for-logging.html) Elasticsearch configuration tips and tricks from Sanity
* [Scaling Elasticsearch to Hundreds of Developers](http://engineeringblog.yelp.com/2014/11/scaling-elasticsearch-to-hundreds-of-developers.html) by Joseph Lynch @yelp 
* [10 Elasticsearch metrics to watch](http://radar.oreilly.com/2015/04/10-elasticsearch-metrics-to-watch.html)
* [Understanding ElasticSearch Performance](https://joshrendek.com/2015/11/understanding-elasticsearch-performance/)
* [Our Experience of Creating Large Scale Log Search System Using ElasticSearch](http://www.cubrid.org/blog/dev-platform/our-experience-creating-large-scale-log-search-system-using-elasticsearch/) - topology, separate master, data and search balancers nodes
 
### Integrations
* [Apache Hive integration](https://www.elastic.co/guide/en/elasticsearch/hadoop/current/hive.html)
* [Connecting Tableau to ElasticSearch (READ: How to query ElasticSearch with Hive SQL and Hadoop)](http://ryrobes.com/systems/connecting-tableau-to-elasticsearch-read-how-to-query-elasticsearch-with-hive-sql-and-hadoop/)
* [mradamlacey/elasticsearch-tableau-connector](https://github.com/mradamlacey/elasticsearch-tableau-connector)

### Alerts
* [ElastAlert: Alerting At Scale With Elasticsearch, Part 1](http://engineeringblog.yelp.com/2015/10/elastalert-alerting-at-scale-with-elasticsearch.html) by engineeringblog.yelp.com

### Time series
* [Elasticsearch as a Time Series Data Store](https://www.elastic.co/blog/elasticsearch-as-a-time-series-data-store) by Felix Barnsteiner
* [Running derivatives on Voyager velocity data](https://www.elastic.co/blog/out-of-this-world-aggregations) By Colin Goodheart-Smithe
* Shewhart Control Charts via Moving Averages: [Part 1](https://www.elastic.co/blog/staying-in-control-with-moving-averages-part-1) - [Part 2](https://www.elastic.co/blog/staying-in-control-with-moving-averages-part-2) by Zachary Tong
* Implementing a Statistical Anomaly Detector: [Part 1](https://www.elastic.co/blog/implementing-a-statistical-anomaly-detector-part-1) - [Part 2](https://www.elastic.co/blog/implementing-a-statistical-anomaly-detector-part-2) - [Part 3](https://www.elastic.co/blog/implementing-a-statistical-anomaly-detector-part-3) by Zachary Tong
 
### Machine Learning
* [Classifying images into Elasticsearch with DeepDetect](http://www.deepdetect.com/tutorials/es-image-classifier/) ([forum thread with discussion](https://discuss.elastic.co/t/categorizing-images-with-deep-learning-into-elasticsearch/33217)) by Emmanuel Benazera
* [Elasticsearch with Machine Learning](https://medium.com/hello-elasticsearch/elasticsearch-amazon-machine-learning-7d7b979c328d#.s50a6d5mn) ([English translation](https://translate.googleusercontent.com/translate_c?depth=1&hl=en&prev=search&rurl=translate.google.com&sl=ja&u=https://medium.com/hello-elasticsearch/elasticsearch-amazon-machine-learning-7d7b979c328d&usg=ALkJrhioEPGsVRglGPFTa6w2ZfM-ydSoeg)) by Kunihiko Kido
* [Recommender System with Mahout and Elasticsearch](https://www.mapr.com/products/mapr-sandbox-hadoop/tutorials/recommender-tutorial)


### Use cases for elastic search
* [Data Infrastructure at IFTTT](http://engineering.ifttt.com/data/2015/10/14/data-infrastructure/) Elasticsearch, Kafka, Apache Spark, Redhsift, other AWS services 
* [OFAC compliance with ElasticSearch](https://israelwebdev.wordpress.com/2015/01/19/ofac-compliance-with-elasticsearch/) using AWS

## Other
* [Fluentd vs. Logstash for OpenStack Log Management](http://www.slideshare.net/td-nttcom/fluentd-vs-logstash-for-openstack-log-management)
* [Building a Directory Map With ELK](http://david.pilato.fr/blog/2015/12/10/building-a-directory-map-with-elk/)
* [Structured logging with ELK - part 1](http://engineering.laterooms.com/structured-logging-with-elk-part-1/)

## Videos
### Overviews
* [How we scaled Raygun](https://raygun.io/blog/2014/05/talk-how-we-scaled-raygun-using-technologies-like-elastic-search-featuring-iron-man/)
* [Getting started with ElasticSearch](https://www.youtube.com/watch?v=60UsHHsKyN4&list=PLw5h0DiJ-9PDStvJYc1LOZiEm1ehlEKLP)
* [Speed is a Key: Elasticsearch under the Hood](https://www.youtube.com/watch?v=vruklYSW4jg) introduction + basic performance optimization
* [$$ Pluralsight: Getting Started With Elasticsearch for .NET Developers](http://www.pluralsight.com/courses/elasticsearch-for-dotnet-developers) this course will introduce users to Elasticsearch, how it works, and how to use it with .NET projects. 
* [How Elasticsearch powers the Guardian's newsroom](http://www.infoq.com/presentations/elasticsearch-guardian)

### Advanced
* [#bbuzz 2015: Adrien Grand – Algorithms and data-structures that power Lucene and Elasticsearch](https://www.youtube.com/watch?v=eQ-rXP-D80U)

### Configuration file samples and other gists
* [ElasticSearch config for a write-heavy cluster](https://gist.github.com/reyjrar/4364063) - reyjrar/elasticsearch.yml

## Who is using elasticsearch?
[Yelp](http://engineeringblog.yelp.com/2015/10/how-we-use-deep-learning-to-classify-business-photos-at-yelp.html),
[IFTTT](http://engineering.ifttt.com/data/2015/10/14/data-infrastructure/),
[StackExchange](http://stackexchange.com/performance),
[Raygun](https://raygun.io/blog/2014/02/search-improvements-at-raygun/),
[Mozilla](https://www.youtube.com/watch?v=lWKEphKIG8U),
[Spotify](https://labs.spotify.com/2015/11/17/monitoring-at-spotify-introducing-heroic/),
[CERN](https://medium.com/@ghoranyi/needle-in-a-haystack-873c97a99983),
[NASA](https://www.elastic.co/elasticon/2015/sf/unlocking-interplanetary-datasets-with-real-time-search)

# Contributing
* Make sure you are about to post a valuable resource that belongs to this list
* Use spellchiker
* All spelling and grammar corrections are welcome
* Fork this repo, do your edits, send the pull request
* Feel free to create any new sections
* Add yourself to the "Contributors" section if you will
* Do not even try to add this repo to any awesome-awesome-* lists 

# Contributors
@dzharii, @...
 
#### ← [Awesome TypeScript](https://github.com/dzharii/awesome-typescript) -= Awesome Elasticsearch =- 


