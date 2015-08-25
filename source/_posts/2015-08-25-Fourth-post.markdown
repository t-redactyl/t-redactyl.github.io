---
layout: post
title: "Third Post"
date: 2015-08-25
comments: false
external-url:
categories:
---

This is a trial blog post testing code embedding and syntax highlighting with Stata:

{% codeblock lang:do %}
gen	cprostate = 0
forval i = 1/40 {
    replace cprostate = 1 if inlist(substr(tdiag`i', 1, 3), "C61")
}
{% endcodeblock %}



