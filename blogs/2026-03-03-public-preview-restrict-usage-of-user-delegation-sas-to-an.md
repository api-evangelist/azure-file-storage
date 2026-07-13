---
title: "Public Preview: Restrict usage of user delegation SAS to an Entra ID identity"
url: "https://techcommunity.microsoft.com/t5/azure-storage-blog/public-preview-restrict-usage-of-user-delegation-sas-to-an-entra/ba-p/4497196"
date: "2026-03-03"
author: "ellievail"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureStorageBlog"
---
Shared access signatures (SAS) grant time-bound, scoped access to Azure Storage resources without sharing account keys. Over time, Azure Storage has continued to strengthen SAS security, moving from account keys to user delegation (UD) SAS secured by Microsoft Entra ID. Today, we’re taking the next step forward by announcing public preview for user-bound user delegation SAS , an extension of UD SAS that ensures a SAS token can only be used by a specific Entra ID identity.
