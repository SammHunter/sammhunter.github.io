Samantha Hunter
10/7/2021

# PokeAPI Vignette

Link: [Pokemon API Vignette](https://sammhunter.github.io/558_Project1/)
Link: [Repository for Vignette]()

My vignette alllows someone to query the PokeAPI and get various
information about the Pokemon video games. To do so, I created six
different functions. One of the functions is to get information about
the berries that were introduced in the Generation II games, but the
berry information is from Generation III games. In Generation III, a
player was able to plant and harvest berries, so my function will return
the germination period and how many berries can grow on a single plant.

The other five functions exclusively return data about each Pokemon
species and sub-species of the Pokemon from the endpoints. I queried the
Generation endpoint, which will tell you when the Pokemon species was
first introduced to game-canon. I queried Habitat, which will tell you
where a Pokemon can be found. Pokemon Type is another endpoint that will
return all the Pokemon of the type you specified. Ability is an endpoint
that you can query the name of the desired ability and will return all
the Pokemon that can have that ability. Finally, I queried the Pokemon
endpoint and you will get out the base stats for that wild-caught
Pokemon.

Using these endpoints, I explored the data quite a bit before deciding
to investigate whether or not Pokemon became stronger with each
generation. I know most of my favorite Pokemon come from the first few
generations of the game and I wondered how they would fare against their
newer counterparts. I decided the easiest way to do this was to sum all
of the base stats and compare those. I didn’t end up finding any
evidence that there was a *consistent* power creep along generational
lines, but I didn’t run any hypothesis tests or go about analyzation in
a strict mathematical way. I could see an argument that the developers
of Pokemon did make Pokemon stronger up to Generation IV before scaling
power back. There also aren’t the same amount of Pokemon introduced in
each Generation, which can obscure and skew the results. I did find that
there were roughly the same amount of very strong Pokemon in each
generation, but some of the Generations introduced 151 Pokemon
(Generation I), while others introduced half of that (Generation VI).

Because there was no evidence of a power creep. I looked at the overall
population of each generation and got a feel for the rate of occurance
of where Pokemon could be caught and what type they were. I also created
scatterplots for the three stats that I care about the most - HP,
Attack, and Defense. The way I play Pokemon is that I try to leverage
the Pokemon type strengths and weaknesses so I don’t have to worry about
Special Attack, Special Defense, and Speed. I should hold the upperhand
in Special Attack and Special Defense as long as I choose my Pokemon
wisely. I wanted to see if there was any relationship between HP,
Attack, and Defense. I thought that these might be inversely related,
but I surprisingly found that these three were generally positively
correlated. Pokemon tend to be well-rounded in regards to these three
stats.

# Reflecting on Vignette Creation

I thought this project was pretty hard, but I am happy that I was able
to accomplish what I did. I spent nearly all of my time on the getting
the functions to produce a nice tibble, althought I did I scale back
from my original plan. For example, I originally wanted to make a table
of Pokemon-types and what they were weak against and strong against, but
because a Pokemon-type may be weak or strong against more than one other
type, unlisting that into a tibble was super hard. I definitely had
trouble knowing when I needed to use ‘\[’ and ‘\[\[’ for unlisting or
listing an output. I know next time I will write out what I need to be a
list vs an element and that will save me a ton of time trouble shooting.
I didn’t know how to navigate that some lists would be empty and some
would have two types so I just abandoned that idea as well, but this is
something I think I can take care of at a later date with a little more
time. I do want to come back to this project when I have the time to
figure that out. I also had trouble with getting my graphs to print in
the GitHub pages due to specifying an output, but I like to be clear.

I also want to come back and play around with the formatting and
analyzations of the project. I may try running actual mathematical
statistical analyses to further explore whether Pokemon from different
generations have significantly different stast. For now, I am just happy
to draw some tentative conclusions from graphas.