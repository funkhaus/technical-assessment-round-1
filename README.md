# Technical Assessment

A quick little one page site design used at Funkhaus as a Technical Assessment test for prospective engineers.

## Design

The XD file can be seen in browser here: https://xd.adobe.com/view/f8aeaa9a-81f3-4967-a3d2-e8fe5abce4e8-adfd/

**Notes**

1.  XD does allow you to see the specs of all the elements. Click the `</>` button in top right corner.
1.  You can download assets (images, SVGs, etc) from XD.
1.  Please use your best judgement to make this design responsive. On the smallest breakpoint, please have the list of names go to one column.
1.  Take note the hover state when hovering over the names. See the Jamie Foord example in the XD link above.
1.  Web Fonts can be found in `/fonts`.

## Requirements

Imagine this design is the home page to an entire website. So setup basic structure and any components as you would if you were going to be building out a site form this starting point.

1.  Please use the [Nuxt framework](https://nuxtjs.org/guide/installation#starting-from-scratch).
1.  Please keep SEO in mind when you build this. We want to see that you understand HTML semantics.
1.  On hover of names in the list, the image shown in the design should be a cross fading slideshow of multiple images.
1.  The hamburger should animate to a cross on click, and commit to the store that it's been clicked.
1.  No CSS frameworks please.

**Hints**

1.  Please [read this a guide](https://github.com/funkhaus/best-practices/blob/master/README.md) for our best practices.
1.  Please [see this sample component](https://github.com/funkhaus/factory/blob/master/src/components/WorkBlock/BlockWork.vue) for an expectation on quality style.

## Mock data

The included `/db.json` file should be used as your mock API, but accessed via this URL:

`https://raw.githubusercontent.com/funkhaus/technical-assessment/master/db.json`

1.  The list of names can be generated from the `pages` array.
1.  The slideshow images can be generated using the `images` array.
1.  Note the `siteMeta` and `page` objects, those can be used for SEO.
1.  Use the Nuxt fetch method to read the JSON file from GitHub.

## Deploy & Submit

Please deploy to Netlify or Vercel. The free tier is fine.

Please share a repo of your code to the GitHub user `drewbaker` (or email to drew@funkhaus.us).
