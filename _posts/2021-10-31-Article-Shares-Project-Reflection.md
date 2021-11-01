Samantha Hunter
10/30/2021

# Predicting Shares of Web Articles"

[Website](https://sammhunter.github.io/558_Project2/)

[Article Shares Repository](https://github.com/SammHunter/558_Project2)

In this project, we looked at our ability to predict the number of
shares an article could get by some attributes of that article. To
choose a best model for each topic, we compared the root mean square
error of each model.

The hardest part of this project for me was certainly data exploration.
The data had a ton of predictors and it wasn’t totally clear what each
predictor meant. I certainly felt lucky that we strictly cared about
modeling and prediction and not interpretability. The data itself was
unwieldy and hard to visualize. I still have questions about why there
were articles that you could visit that were recorded as having no
content. I also tried using forward and backwards subset selection to
narrow down the 49 predictors that were available to us. It was
ultimately a fruitless endeavor. I kept getting an error like
`31 instances of multicollinearity`. There were also a ton of models I
tested and just were equivalently extremely bad.

Shout out to my partner as well, who seemed to have an answer to nearly
every question I asked. I am sure I would have found automating the
render much more difficult. Evan also did some really interesting things
using the kable function and in-line referencing in R markdown.

My big takeaway from this project is that variable selection is really
hard. I spent a lot of time thinking those things through. I also found
working through Github surprisingly easy. I was constantly worried that
I was going to push something up that would overwrite what Evan had
worked on, but that never happened. I’m not positive that I am always
doing it correctly, though.

Next time I do a project like this, I would really like to get some sort
of subset selection through a mathematical method. Like I mentioned, the
number of variables that are mostly on vastly different scales in this
data set just made the data set hard to work with. For prediction, I
think we definitely would improve the modeling a lot by taking out some
of the noise in the models that comes with having so many predictors. I
would always like to find the article that was originally published with
this data set as well. I would like see what the researchers who took
this data could fill in some knowledge gaps. Overall though, I don’t
think we can improve the model much with a data set like this and the
methods that we used.
