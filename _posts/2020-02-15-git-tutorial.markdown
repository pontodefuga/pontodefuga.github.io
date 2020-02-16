---
layout: post
title:  "Git + Latex"
date:   2020-02-15 21:34:00 -0300
categories: tutorial
mathjax: true
---


You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated. Referencing the Equation \ref{eq:1}

$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}\label{eq:1}$$

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

<figure>
  <img src="{{site.url}}/assets/images/teste.jpg" alt="my alt text" style="width: 750px" class="center"/>
  <figcaption>This is my caption text </figcaption>
</figure>

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
