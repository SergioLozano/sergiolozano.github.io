---
layout: page
title: project 11
description: with background image
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
chart:
  echarts: true
---

Remember Debitoor? Many dont't but for a few years, it was a trusted name for simple invoicing and accounting across Europe, tailored for freelancers and small businesses. But the Debitoor story is part of a larger narrative involving some of the big names in Nordic business software, culminating in its integration into the SumUp ecosystem---a project in which I participated.

## TL;DR

Learn how I contributed to a strategic content migration from Debitoor former domains to SumUp Invoices microsites. part of strategic content migration. This wasn't just about moving content; it was a deliberate **lead-generation tactic** designed to foster growth for SumUp Invoices, successfully scaling sign-ups through these channels from effectively zero at launch to hundreds per month. See the results below:

```echarts
{
  "title": {
    "text": "SumUp Invoices Organic Lead Generation",
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
    "data": ["sumup.co.uk/invoices", "sumup.es/facturas", "sumup.dk/fakturaer", "sumup.it/fatture"],
    "top": "10%"
  },
  "xAxis": {
    "type": "category",
    "data": ["Jan21", "Feb21", "Mar21", "Apr21", "May21", "Jun21", "Jul21", "Aug21", "Sep21", "Oct21", "Nov21", "Dec21", "Jan22", "Feb22", "Mar22", "Apr22", "May22"],
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
      "name": "sumup.co.uk/invoices",
      "type": "line",
      "smooth": true,
      "data": [0, 0, 0, 70, 76, 70, 114, 209, 266, 276, 274, 140, 167, 166, 183, 172, 201],
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
      "name": "sumup.es/facturas",
      "type": "line",
      "smooth": true,
      "data": [0, 0, 0, 7, 12, 15, 24, 19, 106, 207, 202, 107, 118, 116, 160, 134, 147],
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
    },
    {
      "name": "sumup.dk/fakturaer",
      "type": "line",
      "smooth": true,
      "data": [0, 0, 0, 0, 0, 0, 27, 42, 51, 28, 35, 14, 15, 12, 13, 11, 17],
      "itemStyle": {
        "color": "#6E338A"
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
            { "offset": 0, "color": "rgba(110, 51, 138, 0.5)" },
            { "offset": 1, "color": "rgba(110, 51, 138, 0)" }
          ]
        }
      },
      "emphasis": {
        "focus": "series"
      }
    },
     {
      "name": "sumup.it/fatture",
      "type": "line",
      "smooth": true,
      "data": [0, 0, 0, 0, 25, 87, 144, 163, 157, 206, 201, 150, 154, 128, 142, 119, 145],
      "itemStyle": {
        "color": "#AB8F39"
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
            { "offset": 0, "color": "rgba(171, 143, 57, 0.5)" },
            { "offset": 1, "color": "rgba(171, 143, 57, 0)" }
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

## Intro

Originating from Denmark's e-conomic around 2012, Debitoor established as its own company following Visma's 2015 acquisition of e-conomic, and its independent lifecycle concluded following its acquisition by SumUp.

This acquisition was not merely a portfolio addition; it initiated a deliberate process of operational consolidation. SumUp's strategic objective was clear: integrate Debitoor's functionalities to create a unified financial services platform, moving beyond payment processing to encompass essential business management tools like invoicing and accounting.


## Intro

If you've been wondering what happened to Debitoor (whether you used debitoor.dk, debitoor.com, debitoor.es, debitoor.it, or any other domain), let's trace its journey. 

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

From June 2020, we started working on gradually migrating Debitoor to SumUp Invoices. While I was working together with Product and Engineering on the user migration, I led the marketing team towards the content mmigration.

**But why migrate the content?** Most of Debitoor's success lies on organic traffic, achieved through thought leadership, and accounting dictionary, and a blog designed to not only capture traffic but convert it into qualified leads.

Below, you can see 2029 and 2020 Debitoor's organic traffic in those domains where I manage the marketing team: debitoor.com, debitoor.es, debitoor.it, and debitoor.dk. 

Analytics screenshot. 

The content migration was iterated and planned in stages, and it went as follows:

Having in mind the agile methodology, we decided that we will perform it by batches, allowing us to accelerate the migration, but most importantly to ensure it was safe and we could learn from each iteration.

We first audited all the content in the Debitoor's domains, categorized it and decided what we could migrate based on market-fit, product-fit, what could be merged, and what was still relevant.

Once audited, we then proceed to copy the content and migrate to SumUp CMS. From there, we would update links,change images, and rewrite the content where needed,updating call to actions, feature names, and other naming conventions (for example, SumUp uses the word merchant to talk about its customers).

With the content ready, we would deploy and create redirects from Debitoor to SumUp to avoid duplicates and 404 errors. Finally, we implemented tracking for those signups specific to SumUp Invoices.


The result was a huge increase in number of signups.

Below, you can see how Debitoor's traffic decline as SumUp Invoices grow throughout 2021.
