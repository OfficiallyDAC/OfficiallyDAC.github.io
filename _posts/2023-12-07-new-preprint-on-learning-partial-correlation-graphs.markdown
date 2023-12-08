<!-- ---
layout: post
title:  "Welcome to Jekyll!"
date:   2023-11-02 14:57:34 +0100
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

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
[jekyll-talk]: https://talk.jekyllrb.com/ -->

--- 
layout: post | title:  "Learning Multi-Frequency Partial Correlation Graphs: Preprint version available." | date:   2023-12-07 20:00:00 +0100 | categories: preprints

---

Check out [here](https://arxiv.org/abs/2311.15756) the preprint version of _Learning Multi-Frequency Partial Correlation Graphs_! It's a joint work with  my PhD Advisor and Professors from the signal processing research group of the Department of Information Engineering, Electronics, and Telecommunications (DIET) of Sapienza University of Rome.

* __Motivation__: In many applications it is pivotal to discriminate partial correlations occurring at different frequency bands. State-of-the-art methods fail in this discrimination.
* __Our contribution__: 
    *  Propose the learning of a multi-frequency Partial Correlation Graph, where different layers correspond to different frequency bands, and where partial correlations can possibly occur only over some frequency bands.
    * Formulate and solve two nonconvex learning problems to accomplish this task. Our methods do not rely on any specific statistical model.
    * We jointly learn the cross-spectral density matrices and their inverses.
* __Results__:
    * Outperform baseline methods in this task.
    * Successful application on financial portfolios.

Link to the __code__ in the supplemental.