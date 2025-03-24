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
layout: post | title:  "New preprint on relative causal knowledge." | date:   2025-03-13 9:07:00 +0100 | categories: preprints

---
Fresh off the press 📢  [_The Relativity of Causal Knowledge_](https://arxiv.org/abs/2503.11718)

Abstract: Recent advances in artificial intelligence reveal the limits of purely predictive systems and call for a shift toward causal and collaborative reasoning. Drawing inspiration from the revolution of Grothendieck in mathematics, we introduce the relativity of causal knowledge, which posits structural causal models (SCMs) are inherently imperfect, subjective representations embedded within networks of relationships. By leveraging category theory, we arrange SCMs into a functor category and show that their observational and interventional probability measures naturally form convex structures. This result allows us to encode non-intervened SCMs with convex spaces of probability measures. Next, using sheaf theory, we construct the network sheaf and cosheaf of causal knowledge. These structures enable the transfer of causal knowledge across the network while incorporating interventional consistency and the perspective of the subjects, ultimately leading to the formal, mathematical definition of relative causal knowledge.

THANK YOU to Claudio Battiloro for working side by side with me on this exciting project and making this article possible. Big thanks also to Hans Riess and Fabio Massimo Zennaro for their valuable feedback on an earlier version of the paper.

Below is why you should check out our paper.

If you're into causality, we introduce the notion of perspective into Structural Causal Models (SCMs), making them subjective. But don’t worry, we're not abandoning Pearl’s framework, we're building on it. In fact, we define a new category of SCMs that retains the expressivity, while allowing for relative causal knowledge. Plus, causal abstraction plays a key role, highlighting its importance from a fresh angle. These are all relatively unexplored areas, so there’s a lot of work to be done!

If you are into mathematics, we introduce new category-theoretic objects and network (co)sheaves. This takes us beyond the familiar Vect/Hilb categories into convex spaces of probability measures. A full cohomology theory and an algebraic description of these cellular sheaves still need to be developed, ultimately leading to a spectral theory for relative causal knowledge.

And if you're an AI/ML researcher, there's plenty for you too. Our work lays the foundation for network sheaf inference and discovery in the context of relative causal knowledge, definitely novel and nontrivial research directions. Plus, reinforcement learning looks like a promising approach given our framework.