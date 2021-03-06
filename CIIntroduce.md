# Continuous Integration

Have you ever heard Continuous Integration or CI? 
CI is a good tool for development, and if you never used such a tool, you might be OUT.
So let us talk about Continuous Integration(CI) today. 

Before we talk about CI, let me tell you a mistake I have made.
Months ago, when using Travis-CI, I wrote a script for CI to let CI download something to my GitHub repo, when I push something to repo .
But I made a mistake: After CI downloaded files, CI will push these files to my repo which will make CI start again. 
So what you guess is right, CI does what I wrote in the script again and again.

So you see, an important function is that you can write a script to test your project.

CI is the practice, in practice, in software engineering, of merging all developer working copies to a shared mainline several times a day,
and CI was first named and proposed by Grady Booch in his 1991 method [1][2].
Em... those are just copied from Wikipedia. We can know that CI is not only aimed at test one application, but it is also about sharing even more than testing.
In short, CI is that somebody gives you a temporary enviroment or just you own one where you write a script, set the environment, and test applications.
If you just want to run your script, that is ok. Remember that CI is an important part of development, and the tools are what made human human.

If you want to ask me what can CI do, I just can say that I have no idea.
You can do many things with CI.However, stop talking about what can CI do,and I will talk about some CI-service supporters.

First one is Travis-CI. Travis is the most popular CI in the world, well I guest, but it is true that there are more than 300,000 open source projects on the Travis.
More, 250,000 users trust Travis, and at the same time Travis provides Travis-pro, which provides an advanced CI. 
And you can test Ruby, Node.js, PHP, Python, Docker, Mac, Haskell, and more.

And DaoCloud provides CI, too. Thought DaoCloud's CI is not good as well as Travis. But it is more stable in China. And it is hooked with DaoCloud's mirror building service.

For more informations:

* Travis-CI's official website: [travis-ci.org](https://travis-ci.org)
* DaoCloud's official website: [daocloud.io](https://www.daocloud.io)
* (I) Known CI service provider:
  1. Travis-CI
  2. DaoCloud
  3. Codeship
  4. CircleCI
  5. Snap CI
  6. Solano CI
  7. Side CI
  8. ...
  
  You can just find these providers via search engine.
  
  
That is all we talked about, have a good day. Written by Qinka, in XDU, Xi`an, China.

勤恪在西安，祝您晚安。 

## Bibliography & References

1. [Wikipedia](https://en.wikipedia.org/wiki/Main_Page), April 2016, Article, [**Continuous integration** en.wikipedia.org/wiki/Continuous_integration](https://en.wikipedia.org/wiki/Continuous_integration)
2. Booch, Grady(1991). **Object Oriented Design: With Applications**. Benjamin Cummings. p.203 ISBN 9780805300918. Retrieved 2014-08-18. (copied from Wikipedia)