---
autogenerated: true
title: KymographBuilder  › Yet Another Kymograph Fiji plugin
breadcrumb: KymographBuilder   Yet Another Kymograph Fiji plugin
layout: page
author: test author
categories: 
description: test description
---


{% capture author%}
{% include person content='Hadim' %}
{% endcapture %}

{% capture maintainer%}
{% include person content='Hadim' %}
{% endcapture %}

{% capture source%}
{% include github org='fiji ' repo='KymographBuilder ' %}
{% endcapture %}
{% include info-box name='KymographBuilder ' logo=' ' software='Fiji ' author=author maintainer=maintainer source=source released='24/04/2016 ' status='v1.2.2, stable ' category=' ' %}

## Presentation

*KymographBuilder is Yet Another Kymograph Fiji plugin.*

Features are :

  - Build kymograph from a straight or segmented line (a polyline).
  - Build kymograph for images with multiple channels.
  - Take into account the width of the line using maximum projection along its thickness.
  - Built from scratch and use the ImageJ2 Ecosystem.
  - Fast and easy to use.

How to use :

  - Draw a line: it can be a polyline and you can also set the thickness that will be taken into account by the plugin.
  - Launch KymographBuilder : {% include bc content='Plugins|Kymograph|KymographBuilder'%}
  - You're done.

![](Kymograph_Construction.png)

## Scripting

You can script the plugin. Here is an example _

{% include github-embed org='fiji ' repo='KymographBuilder ' path='src/main/resources/script\_templates/Examples/MultiKymographBuilder.py ' label='MultiKymographBuilder.py ' %}

## Related links

  - [Multi\_Kymograph](Multi_Kymograph "wikilink") : The first kymograph bundled with Fiji, with support for multiple Line ROIs
  - Source code on GitHub : https://github.com/fiji/KymographBuilder
  - Maven : https://maven.scijava.org/#nexus-search;quick~kymographbuilder
  - Travis CI : https://travis-ci.org/fiji/KymographBuilder

## Authors

KymographBuilder has been created by Hadrien Mary.

This work started in 2016 at the Gary Brouhard laboratory (http://brouhardlab.mcgill.ca) at McGill University.