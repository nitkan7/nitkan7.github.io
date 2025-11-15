---
title: Why is my log backup job skipping some runs
date: 2025-11-15 
categories: [Backups]
tags: [backup, log, Ola Hallengren]     # TAG names should always be lowercase
description: Params in the Ola Hallengren Log backup script. 
---


If you've been engaged in production environments for SQL server, There is a high possibility that you might've seen environments using the Ola Hallengren solution for Database Backups and Maintenance. And there's also a possibility that you may be currently using that as well. (Shout out to Ola Hallengren for creating such beautiful software and making it free!)

Well, If you've come across this scenario where sometimes your log backup job completes successfully and still you don't find a log file being created, Scroll below to find out why...

The Log backup job script part contains two important parameters:
- LogSizeSinceLastLogBackup
- TimeSinceLastLogBackup
  
What are these params ? 
![Explanation of Ola Hallengren](../assets/img/post_assets/post_3/ola_log.png)



