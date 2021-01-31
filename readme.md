# This repository contains code and images for the following medium post:

## Estimating future online event donation revenue for musicians and nonprofits

### Bootstrap estimation of confidence intervals with python

https://medium.com/p/cca9dc855d1b/

![Image for post](https://miro.medium.com/max/6016/0*7NQCB5sSL1c1_xpe)

Photo by [Callie Morgan](https://unsplash.com/@calliestorystreet?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com/?utm_source=medium&utm_medium=referral)

I’ve spent my career as a musician and a nonprofit administrator (of a nonprofit I started with some other musicians to help “make the world a better place one tango at a time”). Like many nonprofits we host events and accept donations. This year, because of the pandemic, we have moved to an online events model. One of the many *exciting* things about this format is our events are now more similar to each other.

Did I hear you mutter “Thats not exciting?” Le’me explain…

In my past life touring around the country we would play the same show in each city. For me the events were all exactly the same, but the population from which the audience came was unique. There was no reasonable way to infer what our revenue would be in Los Angeles based on our revenue in Chicago. We tried.

As an administrator, it is incredibly helpful to be able to reasonably estimate minimum income, especially for a donation event. Imagine being able to say something like, “for nearly all events, I expect my average donation per registered person to be between $x and $y.” Now that we have moved to the online space and our events draw from the same population as each other we can! To me thats exciting!

What we’re talking about here is confidence intervals. The confidence interval tells us exactly what we want to know: “For a large number of samples from the same distribution we can expect that some metric will fall between x and y, some percentage of the time.”

I am going to walk through what seems to me to be the most intuitive method for determining the confidence interval for similar events. To do this you will need to be able to run some code in python. Its not too hard and there is a link to all my work and data [here on github](https://github.com/benbogart/blog-2-bootstrap/blob/main/Projecting Donation Revenue.ipynb) or you can run the code on [Google’s colab here](https://colab.research.google.com/github/benbogart/blog-2-bootstrap/blob/main/Projecting Donation Revenue.ipynb) without downloading anything.

[Read the rest on medium](https://benbogart.medium.com/estimating-future-online-event-donation-revenue-for-musicians-and-nonprofits-cca9dc855d1b)

