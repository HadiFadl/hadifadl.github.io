---
layout: post
title: 'Implicit Conversion Concerns for SQL Server Performance'
published: true
date: '2023-07-19'
image: /assets/img/posts/mssqllogo.jpg
external_url: 'https://www.mssqltips.com/sqlservertip/7732/implicit-conversions-in-sql-affect-query-performance/?utem_source=HadiFadlallah'
tags:
  - sql server
  - sql
subtitle: MSSQLTips.com
---
Often SQL developers encounter a strange behavior of the query optimizer where an index scan is performed rather than an index seek when querying a column with a fixed value. This article explains how implicit conversions affect SQL query performance and cause the query optimizer to perform an index scan instead of index seek while searching for a specific value.
