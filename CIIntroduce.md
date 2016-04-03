# Continuous Integration

Have you ever heard Continuous Integration or CI? 
CI is a good tool for development, and if you never used such tool, you might be OUT.
So let us talk about Continuous Integration(CI) today. 

Before we talk about CI, let me tell you a mistake I have made.
Months ago, when using Travis-CI, I wrote a script for CI to let CI download something to my GitHub repo, when I push something to repo .
But I made a mistake: After CI downloaded files, CI will push these file to my repo which will made CI start again. 
So what you guess is right, CI does what I wrote in the script again and again.

So you see, an important function is that you can write a script to test your project.

CI is the practice, in practice, in software engineering, of merging all developer working copies to a shared mainline several times a day,
and CI was first named and proposed by Grady Booch in his 1991 method [1][2].
Em.. those are just copied from wikipedia. We can know that CI is not only aimed to test one application, but it is also about sharing even more than test.
In short, CI is that some one give you a temporary enviroment or just you own one where you write a script, set the environment, and test applications.
If you just want to execute your script, that is ok. Remember that CI is an important part of development, and the tools is what made human human.

If you want to ask me what can CI do, I just can say that I have no idears.


## Bibliography & References

1. [Wikipedia](https://en.wikipedia.org/wiki/Main_Page), April 2016, Article, [**Continuous integration** en.wikipedia.org/wiki/Continuous_integration](https://en.wikipedia.org/wiki/Continuous_integration)
2. Booch, Grady(1991). **Object Oriented Design: With Applications**. Benjamin Cummings. p.203 ISBN 9780805300918. Retrieved 2014-08-18. (copied from Wikipedia)