---
title: "Minor Frankfurt Node Outage"
date: 2026-10-24
draft: false
tags: ["hosting"]
summary: "A single Frankfurt node experienced an eight-minute outage due to a disk removal issue, but no data was lost."
---

## Minor Frankfurt Node Outage 

Earlier today, the ffm1-prod-web-0001 node experienced a brief outage.  The node went offline due to a disk mounting issue caused by the removal of an unused disk. While this disk did not contain any critical data and no data was lost, the outage resulted in an eight-minute disruption of services hosted on that node. These services include:
- GoTrain
- Umami
- k-nunes.com
- inky.knijn.space
- rtdsx.knijn.space

I quickly identified and resolved the issue, restoring full service. I apologize for any inconvenience this may have caused. 