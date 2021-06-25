---
title: "Post 2 with its UNIQUE title" # Quotation marks allow colons, semicolons, etc.
description: "The UNIQUE description for Post 2." # Quotation marks allow colons, semicolons, etc.
date: 2018-10-25T07:40:00-05:00
updated: 2020-06-13T13:10:00-05:00
draft: false # Make it "true" if you don't want Hugo to "publish" yet
extra:
  subtitle: "The UNIQUE Post 2 subtitle" # Quotation marks allow colons, semicolons, etc.
  author: Your name goes here
---

**Note**: Maybe you have a note here about why you updated the post, for example. In that case, this `yellowBox` CSS/SCSS class is useful. This enhanced attributes-handling (note the `{.yellowBox}` below this paragraph in the post's Markdown) was added in Hugo v.0.81.0.
{.yellowBox}


Your opening text goes here.

## In-article heading --- it's an H2 because your title is the H1

And after another paragraph or two or three, you may want to add a subheading, which would be an H3, so it would be like the following.

### Subheading (H3)

Text here.

And here's an example of how to use the `img` shortcode in `/layouts/shortcodes` (note that the images must be in the same folder with the content, because of how Hugo bundles do image processing, so that's why the `src` references don't include a folder upfront):

{{ imgc(path="posts/2018/10/post-2/Early-Web-font-grfx-1-2018-10-16_1218x1296.jpg", alt="Image from Apple Web site in 1999 showing graphic elements as text", width=1218, height=1296) }}

Closing text. That ends Post 2!