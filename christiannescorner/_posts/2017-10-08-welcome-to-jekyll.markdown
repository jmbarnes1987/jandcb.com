---
layout: post
title:  "Welcome to Jekyll!"
date:   2017-10-08 12:02:45 -0500
categories: jekyll update
---
[//]: # Hopefully this is a comment. Yep, this works.
[//]: # Testing images. I need to figure out Liquid syntax. For instance, post.image / post.img do not pass in the path so the image doesn't render.'
[//]: # REFACTOR: I'd like this image on the header behind the post title, not in the post body
<img src="/assets/img/home-bg.jpg" alt="{{ post.title }}" title="{{ post.title }}">
[//]: # Ok, to use the liquid variables here, I need to use site.varname, I think. post.var name is for the loop syntax used in templates, which would pull this file's frontmatter'
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.



To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

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
