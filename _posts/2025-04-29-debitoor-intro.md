---
layout: post
title: How we migrated Debitoor to SumUp
date: 2025-04-29 01:59:00
description: this is what included image galleries could look like if
tags: formatting images
categories: sample-posts
thumbnail: assets/img/9.jpg
images:
  lightbox2: true
  photoswipe: true
  spotlight: true
  venobox: true
chart:
  echarts: true
---

Remember Debitoor? Many dont't but for a few years, it was a trusted name for simple invoicing and accounting across Europe, tailored for freelancers and small businesses. But the Debitoor story is part of a larger narrative involving some of the bigg names in Nordic business software, culminating in its integration into the SumUp ecosystem---a project in which I participated.


## Intro

If you've been wondering what happened to Debitoor (whether you used debitoor.dk, debitoor.com, debitoor.es, debitoor.it, or any other domain), let's trace its journey.

## [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/)

<a href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/1/img-2500.jpg" data-lightbox="roadtrip"><img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/1/img-200.jpg" /></a>
<a href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-2500.jpg" data-lightbox="roadtrip"><img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-200.jpg" /></a>
<a href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-2500.jpg" data-lightbox="roadtrip"><img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-200.jpg" /></a>

---

## [PhotoSwipe](https://photoswipe.com/)

<div class="pswp-gallery pswp-gallery--single-column" id="gallery--getting-started">
  <a href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-2500.jpg"
    data-pswp-width="1669"
    data-pswp-height="2500"
    target="_blank">
    <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-200.jpg" alt="" />
  </a>
  <!-- cropped thumbnail: -->
  <a href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/7/img-2500.jpg"
    data-pswp-width="1875"
    data-pswp-height="2500"
    data-cropped="true"
    target="_blank">
    <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/7/img-200.jpg" alt="" />
  </a>
  <!-- data-pswp-src with custom URL in href -->
  <a href="https://unsplash.com"
    data-pswp-src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-2500.jpg"
    data-pswp-width="2500"
    data-pswp-height="1666"
    target="_blank">
    <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-200.jpg" alt="" />
  </a>
  <!-- wrapped with any element: -->
  <div>
    <a href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/6/img-2500.jpg"
      data-pswp-width="2500"
      data-pswp-height="1667"
      target="_blank">
      <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/6/img-200.jpg" alt="" />
    </a>
  </div>
</div>

---

## [Spotlight JS](https://nextapps-de.github.io/spotlight/)

<!-- Group 1 -->
<div class="spotlight-group">
    <a class="spotlight" href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/1/img-2500.jpg">
        <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/1/img-200.jpg" />
    </a>
    <a class="spotlight" href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-2500.jpg">
        <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-200.jpg" />
    </a>
    <a class="spotlight" href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-2500.jpg">
        <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-200.jpg" />
    </a>
</div>
<!-- Group 2 -->
<div class="spotlight-group">
    <a class="spotlight" href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/4/img-2500.jpg">
        <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/4/img-200.jpg" />
    </a>
    <a class="spotlight" href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/5/img-2500.jpg">
        <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/5/img-200.jpg" />
    </a>
    <a class="spotlight" href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/6/img-2500.jpg">
        <img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/6/img-200.jpg" />
    </a>
</div>

---

## [Venobox](https://veno.es/venobox/)

<a class="venobox" data-gall="myGallery" href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/1/img-2500.jpg"><img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/1/img-200.jpg" /></a>
<a class="venobox" data-gall="myGallery" href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-2500.jpg"><img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-200.jpg" /></a>
<a class="venobox" data-gall="myGallery" href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-2500.jpg"><img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-200.jpg" /></a>


## Simple Graph

```echarts
{
  "title": {
    "text": "Monthly Sales Comparison",
    "left": "center"
  },
  "tooltip": {
    "trigger": "axis",
    "backgroundColor": "rgba(50, 50, 50, 0.7)",
    "borderColor": "#777",
    "borderWidth": 1,
    "textStyle": {
      "color": "#fff"
    }
  },
  "legend": {
    "data": ["Product A", "Product B"],
    "top": "10%"
  },
  "xAxis": {
    "type": "category",
    "data": ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"],
    "axisLine": {
      "lineStyle": {
        "color": "#888"
      }
    }
  },
  "yAxis": {
    "type": "value",
    "axisLine": {
      "lineStyle": {
        "color": "#888"
      }
    },
    "splitLine": {
      "lineStyle": {
        "type": "dashed"
      }
    }
  },
  "series": [
    {
      "name": "Product A",
      "type": "line",
      "smooth": true,
      "data": [820, 932, 901, 934, 1290, 1330, 1320, 1400, 1450, 1500, 1600, 1650],
      "itemStyle": {
        "color": "#5470C6"
      },
      "lineStyle": {
        "width": 3
      },
      "areaStyle": {
        "color": {
          "type": "linear",
          "x": 0,
          "y": 0,
          "x2": 0,
          "y2": 1,
          "colorStops": [
            { "offset": 0, "color": "rgba(84, 112, 198, 0.5)" },
            { "offset": 1, "color": "rgba(84, 112, 198, 0)" }
          ]
        }
      },
      "emphasis": {
        "focus": "series"
      }
    },
    {
      "name": "Product B",
      "type": "line",
      "smooth": true,
      "data": [620, 732, 701, 734, 1090, 1130, 1120, 1200, 1250, 1300, 1400, 1450],
      "itemStyle": {
        "color": "#91CC75"
      },
      "lineStyle": {
        "width": 3
      },
      "areaStyle": {
        "color": {
          "type": "linear",
          "x": 0,
          "y": 0,
          "x2": 0,
          "y2": 1,
          "colorStops": [
            { "offset": 0, "color": "rgba(145, 204, 117, 0.5)" },
            { "offset": 1, "color": "rgba(145, 204, 117, 0)" }
          ]
        }
      },
      "emphasis": {
        "focus": "series"
      }
    }
  ]
}
```