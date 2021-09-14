Programming Background
================
Samantha Hunter
9/13/2021

    ## [1] "C:/Users/jolop/OneDrive/Desktop/Fall21/ST558/sammhunter.github.io/_Rmd"

## Programming Experience - Learning

Prior to taking NCSU’s ST558 course, Data Science for Statisticians, I
have had some experience with R and am confident working in SAS. I was
first introduced to R very poorly in my undergraduate degree at the
University of Colorado to perform some very basic hypothesis tests and
graphs for biology labs. I don’t remember what exactly we did, but I do
remember needing a TA walk me through the programming and feeling like
the process was very mystical. Back then, I had absolutely no experience
programming so it was really like jumping in the deep end. Then, like
half a decade after graduating and doing no programming in the interim,
the first class I took at NCSU was their SAS class and I really enjoyed
programming. Programming is the type of problem solving that I love.

R and SAS both have pros and cons, and the more I learn about R, the
more I prefer it. Although, I have a major soft spot for SAS because it
was my first programming language and its a source of school pride. I am
really glad I learned SAS first because almost every procedure, or PROC
step, has the same structure and layout, where as R has so much
flexibility that it’s a bit overwhelming as a beginner. While there
isn’t necessarily less to learn in SAS, it is so structured that
learning the basics of the language is easier than the basics of R. At
the same time though, once you do know the basics in R, you can do so
much more in an easier fashion than in SAS. I find the log in SAS to be
much more helpful than the log in R. The SAS log makes trouble shooting
so easy because SAS will print the input buffer so I can see exactly
where the programming breaks down and what is causing the issue, but I
don’t know if that’s possible in R. A lot of what I learned in SAS about
structure and how a function or program works, still applies to R, but I
think the introduction to SAS is easier than the introduction to R. SAS
feels like it has fewer weird inconsistencies as well, which makes it
much easier to work with in terms of analysis. For example, I just had
to un-install and re-install R and RStudio because there is a new
version out, but plenty of my packages haven’t updated so every time I
reference them, I get a warning. Or sometimes just closing and
re-opening RStudio fixes a problem, which doesn’t sit right with me
because I want to know what is going wrong! All of these things make SAS
preferable for learning a language, but I don’t actually like it more
than R.

RStudio, specifically, is so much more fun to work in than any version
of SAS. Now that I feel like I know enough to trouble shoot my own
program, R is just easy to use. From the auto-suggestions to the way
that a lot of the packages use a really intuitive layering style, the
ease of using RStudio is a major draw. The flexibility, although
frustrating when learning, is really engaging once you start to get the
hang of the language style. And when I do hit a road block in coding it
also feels like there an answer for every R question I have. Between
CRAN, R Documentation, StackExchange, the R cookbooks, and the RStudio
cheatsheets, R feels like it has more resources for mastery than SAS,
which only has SAS documentation and forums for this quick
troubleshooting. Even finding data sets to work or practice with is so
much easier in R because people make packages to scrape data from the
web. That is *so* interesting to me. Finally, and maybe best of all, R
is *free* so it’s incredibly accessable. Not only is the R program free,
but learning R can be free. Last winter, I worked most of the way
through [R for Data Science](https://r4ds.had.co.nz/) and it is free to
access, although you can donate to the Kakapo conservation. I reference
this book all the time and am looking for some free time until I can
tackle [Advanced R for Data Science](https://adv-r.hadley.nz/). SAS
costs a bunch of money to even license so not everyone can use it
easily. SAS does have a free [University
Edition](https://www.sas.com/en_au/offers/why-learn-sas-lp/thank-you/thky-banner.html),
but I struggled to use it even though I am ceritifed in Base SAS. SAS
doesn’t have to be free because it does perform in different industries
that require support and a strong reputation. SAS isn’t open source like
R is so it is considered more trustworthy and is used in sectors like
public health or finance. That is not a priority to me, so I am more
than happy to be using R for my personal work.

Overall, I think both programs have their place in this world. I would
say SAS is easier to learn because of the rigidity, but I think R is
easier to use. I don’t think I would be as successful or have this much
fun using R without knowing another programming language first.

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

![](C:/Users/jolop/OneDrive/Desktop/Fall21/ST558/sammhunter.github.io/images/plot-1.png)<!-- -->

![SwissPlot](https://raw.githubusercontent.com/sammhunter/sammhunter.github.io/master/images/plot-1.png)
