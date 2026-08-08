---
title: "Building a CCF Nested API Pull Connector: A Technical Lab Walkthrough"
url: "https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/building-a-ccf-nested-api-pull-connector-a-technical-lab/ba-p/4537027"
date: "2026-08-05"
author: "Robert_Moriarty"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=MicrosoftSentinelBlog"
---
This post walks through building a Microsoft Sentinel Codeless Connector Framework (CCF) RestApiPoller connector that uses the nested API polling pattern. The nested pattern exists for a specific reason: many enterprise APIs do not return enriched records from a single call. Instead, they use a two-step model: a list endpoint that returns identifiers, followed by a detail endpoint that accepts one identifier and returns the full record.
