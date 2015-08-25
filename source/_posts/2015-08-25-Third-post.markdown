---
layout: post
title: "Third Post"
date: 2015-08-25
comments: false
external-url:
categories:
---

This is a trial blog post testing code embedding and syntax highlighting with both R and Python:

In **R**:

{% codeblock lang:R %}
rm(list = ls())
set.seed(1)
mean_vector <- NULL
for (i in 1 : 1000) {
    mean_vector <- c(mean_vector, 
    mean(rexp(40, rate = 0.2)))
}
{% endcodeblock %}

In **Python**:
{% codeblock lang:py %}
#More printing

days = "Mon Tue Wed Thu Fri Sat Sun"
months = "Jan\nFeb\nMar\nApr\nMay\nJun\nJul\nAug"

print "Here are the days: ", days
print "Here are the months: ", months

print """
There's something going on here.
With the three double-quotes.
We'll be able to type as much as we like.
Even 4 lines if we want, or 5, or 6.
"""
{% endcodeblock %}


