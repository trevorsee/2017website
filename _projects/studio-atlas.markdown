---
title: Studio Atlas
date: 2016-12-14 05:31:00 Z
photo: "/uploads/trevorcarr-dot-info-studioatlas1.png"
publish: true
position: 4
time: Spring 2017 
---

![a](/uploads/trevorcarr-dot-info-studioatlas1.png)

An index of graphic design studios and how they describe themselves.
{: .measure-wide }

We collected data about studios and their descriptions in to a spreadsheet that could be accessed by API through Sheetlabs. That data is piped into a python script that uses [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) and [t-SNE](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) algorithms to sort the studios. Studios that use similar words or write in a similar way are grouped together.
{: .measure-wide }

The resulting simple React app plots the studios according to their coordinates creating a field of studio homepages that the user can explore at their own pace. We hope that this encourages a user to find relationships between grouped studios in both aesthetic and linguistic terms.
{: .measure-wide }

— in collaboration with [Default Value](http://defaultvalue.info/).
{: .measure-wide .pb1 }

![a](/uploads/trevorcarr-dot-info-studioatlas3.gif)
![a](/uploads/trevorcarr-dot-info-studioatlas2.png)
![a](/uploads/trevorcarr-dot-info-studioatlas4.png)