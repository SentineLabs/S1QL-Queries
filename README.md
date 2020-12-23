# S1QL-Queries
This is Repository of SentinelOne Deep Visibility Queries, curated by SentinelOne Research

##Queries
This is a living repository, and is released as an aid to analysts and hunters using SentinelOne Deep Visibility to provide high quality hunts for abnormalities that are not seen in normal production environments. In some cases these queries may need to have additional filters added to be useful in your environment, due to specific software or practices used in your environment. 

##Query Files
Query files are written in yaml, and document the intent of the query, version, author, and other metadata in the following schema
```
title:                  			-required
description:            			-required
author:                 			-required
version:                                        -required
operating_system:       			-required
query:                  			-required
created_date:                   	        -required
last_update:               		        -required
false_positives:        			-optional
   - 
tags:                   			-required
  - mitre.<ttp>					-required
  - other					-optional
references:             			-optional
   -
s1ql supported version:			        -required
```
