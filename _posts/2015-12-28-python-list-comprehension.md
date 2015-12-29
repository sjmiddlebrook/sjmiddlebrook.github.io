---
layout: post
title: "Python List Comprehension"
---

One cool feature in python is List Comprehensions. It took some getting used to seeing the syntax as opposed to a traditional for loop, but after getting past the initial readibility hurdle the list comprehension function is awesome.  

For instance, if you wanted to find the square of the numbers 1 through 10 in a list, you could do it as follows...

With a standard for loop you could do it as such:
{% highlight python %}
squares = []
for i in range(1, 11):
    squares.append(i**2)
print(squares)
# Output: [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
{% endhighlight %}

With list comprehensions you can tighten up the code to a single line:
{% highlight python %}
print([i**2 for i in range(1, 11)])
# Output: [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
{% endhighlight %}


