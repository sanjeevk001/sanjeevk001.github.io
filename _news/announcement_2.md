---
layout: post
title: CVE-2020-13790
date: 2020-06-03 16:11:00-0400
inline: false
---

Heap-based buffer over-read in libjpeg-turbo 2.0.4 and mozjpeg 4.0.0.

***

Description: 

libjpeg-turbo 2.0.4 and mozjpeg 4.0.0 have a heap-based buffer over-read in get_rgb_row() in rdppm.c via a malformed PPM input file.

<a href="https://github.com/libjpeg-turbo/libjpeg-turbo/issues/433"> Reported issue </a>

<a href="https://nvd.nist.gov/vuln/detail/CVE-2020-13790"> CVE details </a>
