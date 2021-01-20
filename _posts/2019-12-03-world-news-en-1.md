---
title: World News ep 14
layout: post
categories: [WorldNews]
type: main # I use this to split main episodes to extra ones
description: Description goes here
file: https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_700KB.mp3 #Link to your .mp3 file
length: "52:14" # mm:ss
# videoid: dQw4w9WgXcQ #Copy here only the id of your YouTube video. Optional
tags: [news,local]
show: local-news
excerpt_separator: <!--more-->
cover: assets/img/portfolio/safe.png
feature-img: "assets/img/feature-img/story.jpeg"
thumbnail: "assets/img/thumbnails/feature-img/story.jpeg"
---

Here comes: more
<!--more-->
Jekyll supports the use of [Markdown](http://daringfireball.net/projects/markdown/syntax) with inline HTML tags which makes it easier to quickly write posts with Jekyll, without having to worry too much about text formatting. A sample of the formatting follows.

## Title

### Sub title

Tables have also been extended from Markdown:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Here's an example of an image, which is included using Markdown:

![Image of a glass on a book]({{ "/assets/img/pexels/book-glass.jpeg" | relative_url }})

This is another example of list:
 
 - list of things
   1. Sub list
   2. of Other things
   3. with numbers
 - And many more
   - Sub sub list
     - can go on ...
       - and on ...
         - and on !
   - That's it.
   
### Other subtitle

Highlighting for code in Jekyll is done using Base16 or Rouge. This theme makes use of Rouge by default.

{% highlight js %}
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}

// count to twenty
var j = 0;
while (j < 20) {
    j++;
    console.log(j);
}
{% endhighlight %}

### Math

Type on Strap uses KaTeX to display maths. Equations such as $$S_n = a \times \frac{1-r^n}{1-r}$$ can be displayed inline.

Alternatively, they can be shown on a new line:

$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$