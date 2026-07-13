---
title: "Action required: Kerberos RC4 hardening may affect Azure Files Active Directory Domain Services"
url: "https://techcommunity.microsoft.com/t5/azure-storage-blog/action-required-kerberos-rc4-hardening-may-affect-azure-files/ba-p/4518577"
date: "2026-06-05"
author: "grace_kim"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AzureStorageBlog"
---
A Windows security hardening change beginning in April 2026 updates default Kerberos encryption behavior and may impact customers using Azure Files with Active Directory Domain Services (AD DS) authentication over SMB. If you created Azure Files shares prior to 2023, or chose RC4 encryption for your file shares, you will need to reconfigure to use AES-256 to avoid disruption to file share access. This is in accordance with the updated security posture and recommendation from Windows CVE-2026-20833.
