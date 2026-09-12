---
title: "Accelerated AI & Analytics workload on Azure Blob Storage: Up to 25x faster List Blobs operations"
url: "https://techcommunity.microsoft.com/t5/azure-storage-blog/accelerated-ai-analytics-workload-on-azure-blob-storage-up-to/ba-p/4551857"
date: "2026-09-03"
author: "wolfgangdesalvador"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureStorageBlog"
---
Today Azure Storage introduces in preview a new List Blobs optimization that accelerates listing operations by up to 25x with up to 15x lower client-side CPU utilization allowing customers to return millions of objects per second in List Blobs results. The list results are now returned in Apache Arrow format, a highly optimized and compact columnar response format that allows more efficient parsing and reduced client-side CPU utilization. Clients can now parallelize object list operations efficiently across multiple concurrent requests, while maintaining the same strong consistency of listing 
