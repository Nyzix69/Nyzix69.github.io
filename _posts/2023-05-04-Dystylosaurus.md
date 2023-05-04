---
title: Dystylosaurus
author: Nyzix
date: 2023-05-04
categories: []
tags: [CTF, FCSC, SAL]
permalink: /Dystylosaurus
---

# Dystylosaurus



In this chall we just had a `.sal` file. After at least 10000000000 seraches on the web, we can finally know that the `.sal` extension is for:



We find the tool [Logic](https://www.saleae.com/) that could do the trick. We download it and open our `.sal` file:



As we can see, the `Channel 3` is pretty busy. We find an analyser:




This analyser allows us to read a text that contains the flag:

