---
layout: post
title:  "Cyclic Redundancy Check (CRC)"
date:   2015-03-08 22:21:49
categories: Verilog-Practise
tags: Verilog
---
A cyclic redundancy check (CRC) is an error-detecting code commonly used in
digital networks and storage devices to detect accidental changes to raw data. Blocks of data entering these systems get a short check value attached, based on the remainder of a polynomial division of their contents; on retrieval the calculation is repeated, and corrective action can be taken against presumed data corruption if the check values do not match. <br>Detailed description of CRC can be found in:<br> 
[wiki/Cyclic_redundancy_check](http://en.wikipedia.org/wiki/Cyclic_redundancy_check).

My practice example:<br>
CRC module encoding 16 bits of message with a 3-bit CRC, with a polynomial _*_x³+x+1._*_ <br>
Three inputs (in, clk, rst) <br>
One output (out). 
“rst” is active-high synchronous reset. Print the result in “CRC.out”. <br>
Output format: (where x will be replaced by value):
{% highlight ruby %}
At time xx ns, rst=x, in=x, out=x
{% endhighlight %}

Parallel




To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
