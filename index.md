---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /images/bridge.jpeg
intro: 
  - excerpt: 'A place where I *wax eloquent* on people, vehicles, gadgets or whatever catches my fancy. It generally takes a long time for the thoughts to travel from mind to here; ergo the title of this site'
feature_row:
  - image_path: /images/blog.jpeg
    alt: "Blog Image"
    title: "Blog"
    excerpt: "My thoughts, much procrastinated as they were."
    url: "/blog"
    btn_label: "Take Me To The Blog"
    btn_class: "btn--primary"
  - image_path: /images/poems.png
    alt: "Poems Image"
    title: "Poems"
    excerpt: "Are you brave enough to suffer my poems?"
    url: "/poems"
    btn_label: "Yes, Give Me Poems"
    btn_class: "btn--primary"
  - image_path: /images/books.png
    alt: "Books Image"
    title: "Books"
    excerpt: "Books that I've read and my ratings for them with a succinct summary description."
    url: "/books"
    btn_label: "Show Me Books"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}