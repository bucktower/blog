---
layout: default
title: "Deployment Levels"
date: 2018-10-18 23:09:59 -0500
tags: webdev
---
## Background

There is no right way to do CI/CD. I've put a decent amount of thought in it, and have decided on the three-tiered approach: **dev**, **staging**, and **live**.

## Development Server

The goal of the development server is to be extremely easy and intuitive to set up. This is the first step in deployment to happen for a project -- the MVP. It's also the most common deployment, done whenever the developer wants, not necessarily tests are passed ("bleeding edge"). We want to use tools that make it easy for developers, not requiring anything beyond what works for localhost (no containers or tests):

- [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) (Go, Java, .NET, Node.js, PHP, Python, Ruby)
- [Google App Engine](https://cloud.google.com/appengine/) (Python, Java, Node.js, Go, Ruby, PHP, .NET)
- [Heroku](https://www.heroku.com/) (Node.js, Ruby, Python, Java, PHP, Go, Scala, Clojure, Kotlin)
- [Azure App Service](https://azure.microsoft.com/en-us/services/app-service/) (ASP.NET Core, Java, Ruby, Node.js, PHP, Python)
- [Dokku](https://github.com/dokku/dokku)

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
