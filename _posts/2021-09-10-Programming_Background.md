My Programming Background
================
Samantha Hunter
9/9/2021

    ## -- Attaching packages -------------------------------------------------------------- tidyverse 1.3.1 --

    ## v ggplot2 3.3.5     v purrr   0.3.4
    ## v tibble  3.1.3     v dplyr   1.0.7
    ## v tidyr   1.1.3     v stringr 1.4.0
    ## v readr   2.0.1     v forcats 0.5.1

    ## -- Conflicts ----------------------------------------------------------------- tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

## Programming Experience - Learning

Prior to taking NCSU’s ST558 course, Data Science for Statisticians, I
had some experience with R and I have been certified in Base SAS. I was
first introduced to R very poorly in my undergraduate degree at
University of Colorado to produce some very basic hypothesis tests and
graphs for biology labs. I don’t remember what exactly we did, but I do
remember just going having a TA walk me through it and feeling like he
was a bit mystical. I also have a very specific memory of them trying to
make their graphs rainbow themed. That was heated discussion in our
meeting room between the TAs. Back then, I had done absolutely no
experience programming so it was really like jumping in the deep end and
promptly drowning. Then, the first class I took at NCSU was their SAS
class, which I loved and really feel comfortable with now.

R and SAS both certainly have pros and cons, and the more I learn about
R, the more I prefer it. I love that R has so much flexibility and
functionality in such an easy format to learn, but at some point there
is something to say that SAS is more straight forward. I am really glad
I learned SAS first because every procedure, or PROC step, has the same
structure and layout. While there isn’t necessarily less to learn in
SAS, it so structured that learning the basics of the language is easier
than the basics of R. The log in SAS is much more helpful than the
console in R in my opinion. The SAS log makes trouble shooting so easy
because SAS will print the input buffer so I can see exactly what is
going on. A lot of what I learned in SAS about structure and how a
function or program works, still applies to R, but I think the
introduction to SAS is easier than the introduction to R. SAS feels like
it has fewer kinks as well, which makes it much easier to work with in
terms of analysis. For example, I just had to un-install and re-install
R and RStudio because there is a new version out, but plenty of my
packages haven’t updated so every time I reference them, I get a
warning. All of these things make SAS easier to learn than R so far.

SAS is also safer to use because it isn’t open source; there’s a much
smaller risk of downloading a package that doesn’t work like it says it
will and I’m pretty sure there no risk of [downloading
malware](https://support.rstudio.com/hc/en-us/articles/360042593974-R-and-R-Package-Security).
I don’t think R will ever be used instead of SAS in highly regulated
industry like health care or insurance because it is open source. The
less important things that I prefer about SAS over R is that SAS isn’t
case sensitive, which I acknowledge is a kind of petty reason to dislike
R. I also have a soft spot for SAS because it is so tightly related to
NCSU.

R, on the other hand, is more frustrating to learn, but is much more fun
to use. The flexibility in R means there’s tons of different ways to do
something so you’re really only limited by your own knowledge. I enjoy
the layout of RStudio, although I also love my ATOM text editor for when
I use SAS. I find R to be superior computationally because there are so
many packages available. I find R to be superior when creating outputs
because the way you layer plots is very intuitive once you get over the
initial hurdle of ‘where do you start?’ This week we also covered how
easy collaboration is in R. I can link R to github for sharing, and
while I know version control exists for SAS, you can’t make it built in
like we can for R. Where I work, the version control is a completely
separate program. It also feels like there an answer for every R
question I have. Between StackExchange, the R cookbooks, the RStudio
cheatsheets, R is much more approachable than SAS once we get the basics
down. Even finding datasets to work with is so much easier in R because
people make packages to scrape data from the web. That is *so*
interesting to me. Finally, R is free, which I think is so important
these days. Even learning R can be free. Last winter, I worked most of
the way through [R for Data Science](https://r4ds.had.co.nz/) and it was
**free**. I reference this book all the time and just am looking for
some free time until I can tackle [Advanced R for Data
Science](https://adv-r.hadley.nz/). SAS costs a bunch of money so not
everyone can use it easily. I think R is only going to continue to grow
for the better.

Overall, I think both programs have their place in this world. I would
say SAS is easier to learn because of the rigidity, but R is cooler. I
don’t think I would be as successful or had this much ease of learning R
without knowing another programming language first. I can get a bit
overwhelmed with how many way we can do one thing in R.

## R Markdown Output

``` r
#moving where the plot prints to the images folder

# Seeing what data sets are available
# data()

#?swiss

ggplot(data = swiss) +
  geom_point(mapping = aes(x = Education, y = Fertility, color = Catholic)) +
  ggtitle("Fertility of Swiss Women") +
  theme(plot.title = element_text(lineheight = 1.5, face = "bold"))
```

![](C:/Users/jolop/OneDrive/Desktop/Fall21/ST558/sammhunter.github.io/plot-1.png)<!-- -->
