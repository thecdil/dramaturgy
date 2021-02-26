---
title: About
layout: about
permalink: /about.html
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html %}

{% include feature/nav-menu.html sections="Writing With the Collection;About the Collection;About the About Page" %}

## Writing with the Collection

Let's link back to [Act 2](/dramaturgy/midsummer/act2_scene1.html), just for fun.
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris at iaculis ipsum, id posuere libero. 
Vivamus felis orci, accumsan a malesuada varius, vestibulum a nisi. 
Nunc sodales purus in felis facilisis, at sagittis risus aliquam. 
Donec eget consectetur est. 
In mi mauris, posuere sit amet felis non, sollicitudin aliquam est. 
Nullam posuere eu nisl vitae semper. 

{% include feature/item-figure.html objectid="midsummer01" width="50" %}

Cras vestibulum gravida nunc, a venenatis metus. 
Sed ullamcorper, metus non hendrerit convallis, felis urna maximus sem, ut interdum massa elit a est. 
Nullam fringilla facilisis nulla sit amet facilisis. 
Etiam vehicula sodales dolor, sed iaculis libero ultrices sed. 
Sed dictum ipsum et faucibus vulputate.

{% include feature/item-pdf-embed.html objectid="midsummer07" width="50" %}

Ut tincidunt gravida mauris, sit amet hendrerit nulla molestie nec. 
Sed aliquet in purus nec elementum. 
Vestibulum pellentesque malesuada ipsum, eget auctor ex.

{% include feature/item-video-embed.html objectid="midsummer02" %}

Vivamus vel laoreet ipsum. Nulla massa mi, accumsan eget viverra ut, elementum ac lacus. 
Curabitur porta, urna vel pharetra consequat, ante nisi auctor leo, eget tempor odio enim a odio. 
Suspendisse euismod non est eu viverra.

{% include feature/button.html text="Back to transcript" link="/dramaturgy/midsummer/act1_scene1.html" color="success" centered=true %}

## About the Collection

This site is generated using [`collectionbuilder-gh`](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPEG images or PDF documents

The base site features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

## About the About Page

We want to make About pages exciting, and easy to build. 

The CollectionBuilder about page features a narrowed column with its own (optional) menu, featured content, and some technical information. 

To build one, a user writes in [Markdown](https://guides.github.com/features/mastering-markdown/) and includes  content from the site, as well as typical [Bootstrap](https://getbootstrap.com/) features like cards and modals, using code snippets like those detailed below. 

(Each included file has several options, which are documented in the files themselves. I've given the content widths of 25% and 50% to save space, but you can feature the entire image or document.) 

- Image --> `{% raw %}{% include feature/item-figure.html objectid="demo_001" width="25" %}{% endraw %}`

{% include feature/item-figure.html objectid="demo_001" width="25" %}

- PDF -- > `{% raw %}{% include feature/item-pdf-embed.html objectid="demo_002"  width="25" %}{% endraw %}`

{% include feature/item-pdf-embed.html objectid="demo_002" width="25" %}

- Video: `{% raw %}{% include feature/item-video-embed.html objectid="demo_004" %}{% endraw %}`

{% include feature/item-video-embed.html objectid="demo_004" %}

- Card -- > `{% raw %}{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered=true %}{% endraw %}`

{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered=true %}

- Buttons -- > `{% raw %}{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" %}{% endraw %}`

{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" centered=true %}
  
- Alerts -- > `{% raw %}{% include feature/alert.html text="this is an *alert* that 'warns' a user" color="warning" align="center" %}{% endraw %}`

{% include feature/alert.html text="This is an *alert* that 'warns' a user with centrally aligned text." color="warning" align="center"  %}

- Modals -- > `{% raw %}{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}{% endraw %}`

{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="When clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}

We hope this makes it easier for site builders to develop the collection AND add interesting and engaging contextual information.  
