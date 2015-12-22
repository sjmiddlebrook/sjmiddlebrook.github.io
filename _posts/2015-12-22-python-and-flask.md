---
layout: post
title: "Python and Flask"
---
Recently I've been learning to use Flask, a python web framework. One of the coolest things about Flask is the simplicity of getting started and launching a web application.

To start a simple Hello World web application, all you need is one python file with the following.

{% highlight python %}
from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello World!"

if __name__ == "__main__":
    app.run()
{% endhighlight %}

While it is so simple to get up and running, Flask is powerful enough to be extended and tailored for use at large web applications as well. Some big companies that use Flask as part of their internal stack include Linkedin and Pinterest. 

I came across a video from PyCon2014 by Rachel Sanders talking about using Python and Flask at LinkedIn. Her talk focuses on extending Flask and is worth checking out if you want to learn more:

<iframe width="560" height="315" src="https://www.youtube.com/embed/OXN3wuHUBP0" frameborder="0" allowfullscreen></iframe>

