---
layout: post
title:  "Welcome to Jekyll!"
date:   2016-08-16 21:48:44
categories: [jekyll update]
tags: [jekyll,hello]
comments: true
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve --watch`, which launches a web server and auto-regenerates your site when a file is updated.

{% highlight python %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}  
<!--more-->
To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

``` python
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

~~~ python
#!/usr/bin/python
printf("Hello World")
~~~



Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

``` js 
  //``` js
(function($) { 
  $(function() {
    if (skel.vars.os == 'ios' && window.self !== window.top) {
      var $menu = $('#menu'), $window = $(window.top), $head = $('head'), x;
      $window.on('resize orientationchange', function() {
        $menu
          .css('width', $window.width())
          .css('height', $window.height());
      }).trigger('resize');
      x = Math.max($window.width(), $window.height()) * 3;
      $head.append('<style>#menu.visible:before { top: ' + (x * -0.5) + 'px !important; right: ' + (x * -0.5) +
    ' !important; width: ' + x + 'px !important; height: ' + x + 'px !important; }</style>');
    }
  }); 
})(jQuery);
  //```
```


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
