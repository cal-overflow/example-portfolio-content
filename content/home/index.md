---
title: Home
description: This is the home page section.
primary-view: custom-view # What is shown on /
secondary-view: custom-view # What is shown on /{slug} (doesn't matter for this one since there is only a `index.md` item)
---


<person-card headshot="~assets/images/headshot.png">

  ## Hi. I'm Christian. <span class="motion-safe:animate-hand-wave animation-inline">👋</span>

  Enter your bio here. See [cal-overflow's bio](https://github.com/cal-overflow/site/blob/master/src/content/home/about.md?plain=1) as a reference.

</person-card>

<page-preview>

  **Portfolio**
  <divider width="w-1/3" />

  Enter a description of your blog here. \
  See an example description [here](https://github.com/cal-overflow/site/blob/master/src/content/home/portfolio-preview.md?plain=1).

  <nuxt-link to="/portfolio" class="text-primary-light dark:text-primary-dark underline hover:no-underline transition">
    View my work
  </nxut-link>

</page-preview>


<page-preview>

  **Blog**
  <divider width="w-1/3" />

  Enter a description of your blog here. \
  See an example description [here](https://github.com/cal-overflow/site/blob/master/src/content/home/blog-preview.md?plain=1).

  <nuxt-link to="/blog" class="text-primary-light dark:text-primary-dark underline hover:no-underline transition">
    View my blog
  </nxut-link>

</page-preview>

