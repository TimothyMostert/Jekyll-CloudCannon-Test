---
name: Water Feature Mosaic
subtitle: example collections content
external_url: 'https://github.com/CloudCannon/frisco-jekyll-template'
image_path: /uploads/landscape-beach-couple.jpg
_options:
  image_path:
    width: 90
    height: 120
    resize_style: contain
    mime_type: /images/waterfeature.jpg
    expandable: true
  content:
    width: 90
    height: 120
    resize_style: cover
    mime_type: image/png
---


App promotion themed template for Jekyll. Browse through a [live demo](https://brave-submarine.cloudvent.net/).Increase the web presence of a App with this configurable theme.

Frisco was made by [CloudCannon](http://cloudcannon.com/), the Cloud CMS for Jekyll.Find more templates and themes at [Jekyll Tips](http://jekyll.tips/templates/).

Learn Jekyll with step-by-step tutorials and videos at [Jekyll Tips](http://jekyll.tips/).

## Features

* Contact form
* Pre-built pages
* Pre-styled components
* Blog with pagination
* Post category pages
* Disqus comments for posts
* Staff and author system
* Configurable footer
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* RSS/Atom feed
* SEO tags
* Google Analytics

## Setup

1. Add your site and author details in `_config.yml`{: .highlighter-rouge}.
2. Add your Google Analytics and Disqus keys to `_config.yml`{: .highlighter-rouge}.
3. Get a workflow going to see your site’s output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

Frisco was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

<div class="language-bash highlighter-rouge"><pre class="highlight"><code><span class="gp">$ </span>bundle install
</code></pre>
</div>

Run `jekyll`{: .highlighter-rouge} commands through Bundler to ensure you’re using the right versions:

<div class="language-bash highlighter-rouge"><pre class="highlight"><code><span class="gp">$ </span>bundle <span class="nb">exec </span>jekyll serve
</code></pre>
</div>

## Editing

Frisco is already optimised for adding, updating and removing pages, staff, advice, company details and footer elements in CloudCannon.

### Posts

* Add, update or remove a post in the *Posts* collection.
* The **Staff Author** field links to members in the **Staff Members** collection.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs`{: .highlighter-rouge} folder.
* Change the defaults when new posts are created in `_posts/_defaults.md`{: .highlighter-rouge}.

### Contact Form

* Preconfigured to work with CloudCannon, but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).

### Staff

* Reused around the site to save multiple editing locations.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Navigation* section.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Footer* section.