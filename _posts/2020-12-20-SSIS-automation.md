---
layout: post
title: 'Automating SSIS package creation: ManagedDTS vs. EzAPI vs. BIML vs. ETLGen'
published: true
date: '2020-12-20'
image: /assets/img/posts/ssislogo.jpg
external_url: 'https://medium.com/munchy-bytes/automating-ssis-package-creation-manageddts-vs-ezapi-vs-biml-vs-etlgen-d0dca92bf416'
tags:
  - ssis
  - data integration
  - ezapi
  - biml
  - sql server
subtitle: Munchy Bytes
---
Even after the rise of Big Data technologies, Microsoft SQL Server Integration Services still one of the most popular data integration tools. Mainly, SSIS developers use Visual Studio to develop their data integration packages. One of the main challenges that face the SSIS developers is that they design tens of hundreds of similar packages, where they need to recreate the package from scratch each time. Even if in SQL Server 2016 SSIS package parts were introduced to increase the reusability, many scenarios still require a higher level.
This article will mention four approaches that I have tried while working as an ETL developer to automate building SSIS packages.
