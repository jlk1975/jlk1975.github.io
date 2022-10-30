+++
author = "JLK"
title = "Prometheus Overview"
date = "2022-10-29"
description = "Prometheus Overview"
tags = [
    "observability",
]
featuredImage = "images/beam80.avif"
+++

* Prometheus scrapes HTTP endpoints to get it’s data.  
* Mostly written in “Go”.   
* Timeseries data identified by metric name and key/value pair.
* Ex: http_requests_total {method=”get”]   
* <metric> key/value   
* PromQL - Prometheus’s query language   
* Read-only query language  
*  Allows aggregation across any of the labels stored in it’s time series data.  
* Stores metrics on memory and local disk, runs on single server nodes, not a cluster.  
* Has it's own alert manager.  
* 
