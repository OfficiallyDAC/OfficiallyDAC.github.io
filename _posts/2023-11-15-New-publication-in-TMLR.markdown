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
layout: post
title:  "New publication in TMLR."
date:   2023-11-15 9:54:00 +0100 | categories: publications
---

Super happy to share that the paper [_Learning Multiscale Non-stationary Causal Structures_](https://openreview.net/pdf?id=SQnPE63jtA) has been published in Transactions on Machine Learning Research. This article, branded CENTAI, results from an exciting collaboration with Gianmarco De Francisci Morales, Paolo Bajardi, and my PhD advisor Francesco Bonchi.

The work builds on my recent publication concerning [multiscale causal structure learning](https://openreview.net/pdf?id=Ub6XILEF9x). Here, we introduce the multiscale non-stationary directed acyclic graph (MN-DAG), a framework for modeling multivariate time series driven by causal relationships that evolve over time and spread over different temporal resolutions.

Our contribution is twofold. Firstly, we expose a probabilistic generative model by leveraging results from spectral and causality theories. Our model allows sampling an MN-DAG according to user-specified priors on the time dependence and multiscale properties of the causal graph.

Secondly, we devise a Bayesian method named Multiscale Non-stationary Causal Structure Learner (MN-CASTLE) that uses stochastic variational inference to estimate MN-DAGs from observational data. The method also exploits information
from the local partial correlation between time series over different time resolutions.

The data generated from an MN-DAG reproduces well-known features of time series in different domains, such as volatility clustering and serial correlation. Additionally, we show the superior performance of MN-CASTLE on synthetic data with different multiscale and non-stationary properties compared to baseline models. 

Finally, we apply MN-CASTLE to identify the drivers of the natural gas prices in the US market. Causal relationships have strengthened during the COVID-19 outbreak and the Russian invasion of Ukraine, a fact that baseline methods fail to capture. MN-CASTLE identifies the causal impact of critical economic drivers on natural gas prices, such as seasonal factors, economic uncertainty, oil prices, and gas storage deviations.