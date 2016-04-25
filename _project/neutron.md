---
layout: project
title: "Neutron"
description: "A Sass framework created for making flexible, clear, semantic website layouts."
link: "http://neutroncss.com/"
order: 200
image: /img/neutron.png
---

![]({{site.baseurl}}/img/neutron-1.png#neutron-hero)

I created Neutron after using Bootstrap and finding that it was essentially putting styling in the markup instead of in the stylesheet. Created as an open source proof-of-concept of what a modern layout framework would look like Neutron distilled what the core information a framework needs to provide simple to use layout tools.

### Process and Contribution
Neutron was begun by breaking the idea of layout frameworks into their basic components: containers. Commonly used container and row classes in bootstrap led to redundant code in the markup, Neutron instead consolidated them into a single mixin.

![]({{site.baseurl}}/img/neutron-2.png#neutron-two)

The framework was created without an arbitrary limitation of 12 columns, allowing the user to use any number of columns that their layout requires. In addition to removing column limitations I was able to discard offset classes and other workarounds that tried to compensate for not being able to use margins in bootstrap and similar frameworks, enabling the user to use margins in their layout as one would expect with normal CSS.

In addition to matching existing functionality, I added a Sass version of the flexbox ‘order’ property. This allowed users to change the order of elements on the page without changing the order of the elements in the markup.

### Technology Used
* The framework was built using the latest version of Sass, creating a number of mixins and functions that created a complete layout framework engine output in CSS.
* The framework itself is hosted on GitHub which is used for version control and issue management.
* The Neutron documentation site was built as a static HTML and CSS website using NPM, Gulp, and Git to help manage build and deployment of the project.
* The site is hosted on its own Ubuntu VPS using Apache with Node.js behind a proxy to automatically deploy changes made to the master branch on GitHub.

