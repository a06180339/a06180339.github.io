---
layout: post
title: "CF1706E Qpwoeirut and Vertices 题解"
date: 2025-9-2
tags: ["图论", "kruskal 重构树", "3.2"]
comments: true
author: a06180339
---

设每条边的边权是边的编号。按照边权从大到小建出 kruskal 重构树。让区间联通相当于求出区间所有点在重构树上的 lca 的点权。求一下即可。
