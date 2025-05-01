---
layout: post
title: Removing blockers using your own skills
date: 2025-04-30 09:24:00
description: This is what the LinkedIn post should look like
tags: formatting charts
categories: sample-posts
chart:
  echarts: true
---

We rely heavily on complex systems to do things we could often do ourselves.

🚨 On April 28th, a massive power outage in Spain and Portugal reminded me just how fragile our dependencies are. No access to online tools, platforms, TV, or phones, **but the radio was still on**; long substituted by social media and, before that, by online news portals.

![Line chart of the search term radio with a peak on April 28th 2PM](/assets/img/google-trends-radio-search-term.svg)

So, with this image of people on the streets swarming around a radio to listen to stay informed in my mind, I decided to go back to a time when I was creating content differently: No CMS, just coding it in a mix of Markdown and HTML and merging pull requests in GitHub.

From now on, I’m doing the same. I forked a website template from GitHub (I personally use a Jekyll theme, maintained by a community of volunteers and a good level of #accessibility) and started making it my own.

🔧 You don't need a CMS or a dev team. Go to GitHub, find a template that fits your needs, tweak it to your liking, and you’ve got something that’s yours. You own it, you can customise it as you please without depending on plugins, you get better performance, and an easy rollback if needed.

🎨 And for graphics? Normally, I’ve always made my own. Back in the day, I used to create them in Photoshop or Illustrator; a free alternative was Photopea. But today I use Figma in its free version.

You don’t have to be an accomplished graphic designer; think of the story you want to tell and simplify it. Images are not beautifiers but supporters of content. Clean shapes, and start designing. If your needs are simple, your solutions can be, too. You get more customisation, consistency, no dependencies, and only easy-to-correct mistakes.

The main issue I see is the need to make your website or your graphics look like the ones done by a million-dollar creative agency.
Learn just enough, make things simpler and take back control.

I wanted to thank Daniel, Jonathan, Iza, and Whitney, who taught me how to create content this way and guided me when things didn’t deploy back when I was working at Debitoor / SumUp. I learned that I didn’t have to be as good at coding as they were, but to go back to the basics and have enough knowledge to make simple things that I can control.

Also, a special shoutout to Mimi, who recently reminded me of the power of Markdown to create content, and to Adela, whose ability to simplify the most complex graphics and her trust in my abilities pushed me to use Figma more often.
#DIYDigital #Figma #GitHub #PowerOutage #DigitalTools #BuildYourOwn


## [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/)

<a href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/1/img-2500.jpg" data-lightbox="roadtrip"><img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/1/img-200.jpg" /></a>
<a href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-2500.jpg" data-lightbox="roadtrip"><img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/2/img-200.jpg" /></a>
<a href="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-2500.jpg" data-lightbox="roadtrip"><img src="https://cdn.photoswipe.com/photoswipe-demo-images/photos/3/img-200.jpg" /></a>

---

So, with this image of people on the streets swarming around a radio to listen to stay informed in my mind, I decided to go back to a time when I was creating content differently: No CMS, just coding it in a mix of markdown and HTML and committing pull requests to GitHub.

You don't need a CMS or a dev team. Go to GitHub, find a template that fits your needs, tweak it to your liking, and you’ve got something that’s *yours*. You own it, you understand it.

This is an example post with some [plotly](https://plotly.com/javascript/) code.

````markdown
```plotly
{
  "data": [
    {
      "x": [1, 2, 3, 4],
      "y": [10, 15, 13, 17],
      "type": "scatter"
    },
    {
      "x": [1, 2, 3, 4],
      "y": [16, 5, 11, 9],
      "type": "scatter"
    }
  ]
}
```
````

Which generates:

```plotly
{
  "data": [
    {
      "x": [1, 2, 3, 4],
      "y": [10, 15, 13, 17],
      "type": "scatter"
    },
    {
      "x": [1, 2, 3, 4],
      "y": [16, 5, 11, 9],
      "type": "scatter"
    }
  ]
}
```

Also another example chart.

````markdown
```plotly
{
  "data": [
    {
      "x": [1, 2, 3, 4],
      "y": [10, 15, 13, 17],
      "mode": "markers"
    },
    {
      "x": [2, 3, 4, 5],
      "y": [16, 5, 11, 9],
      "mode": "lines"
    },
    {
      "x": [1, 2, 3, 4],
      "y": [12, 9, 15, 12],
      "mode": "lines+markers"
    }
  ],
  "layout": {
    "title": {
      "text": "Line and Scatter Plot"
    }
  }
}
```
````

This is how it looks like:

```plotly
{
  "data": [
    {
      "x": [1, 2, 3, 4],
      "y": [10, 15, 13, 17],
      "mode": "markers"
    },
    {
      "x": [2, 3, 4, 5],
      "y": [16, 5, 11, 9],
      "mode": "lines"
    },
    {
      "x": [1, 2, 3, 4],
      "y": [12, 9, 15, 12],
      "mode": "lines+markers"
    }
  ],
  "layout": {
    "title": {
      "text": "Line and Scatter Plot"
    }
  }
}
```
