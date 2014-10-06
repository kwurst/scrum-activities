# The Team Estimation Game
The **Team Estimation Game,** as explained here, is from *The Elements of Scrum* by Chris Sims and Hillary Louise Johnson (Dymaxicon, 2011) from the chapter "Estimating the Work With Story Sizes".

The point of this game is to allow the Scrum Team to estimate the effort involved in implementing each user story, so that the team can determine how many stories to commit itself to during a sprint.

The game consists of two parts: putting the stories in relative order by effort required (The Big Line-Up), and then grouping the stories by similar amounts of effort (What's Your Number?) The game is played during the Story Time meeting (also called Backlog Grooming), where the Scrum Team assigns sizes to stories, and breaks larger stories down into smaller, more well-understood stories.

With a sufficient number of stories that are well-understood and appropriately sized, the Product Owner can prioritize the stories on the Product Backlog before the Sprint Planning Meeting. At the Sprint Planning Meeting, the team will move stories off the Product Backlog, *in priority order*, to the Sprint Backlog until they have reached the number of Story Points that the team can complete in a single sprint.

## Part I: The Big Line-Up

In the first part, the Product Owner provides a stack of user stories from the product backlog (the example in *The Elements of Scrum* mentions 30 user stories,) which the Team Members arrange in order of effort required to complete each story, following the rules below: 

>### Part I: The Big Line-Up[^1]

>Each player takes a turn, in which they may do any **one** of the following actions:
>
* **Place a new story card on the wall.**
* **Move a previously placed story card.** It is perfectly OK to slide cards down to make room for a repositioned card, so long as the ordering of the other cards is preserved.
* **Pass their turn to the next player.**

>Cards are placed left to right, smallest to largest. It pays to space them widely so you can easily change the order later. Play continues until every player passes.

The team has now agreed upon the relative effort required to complete each story, and ordered the stories by required effort.

## Part II: What's Your Number?

In the second part, the Team Members must assign Story Points to each story, as a numerical representation of the effort required to complete it. Because of the difficulty of distinguishing between small differences in effort required, *The Elements of Scrum* suggests that story points be assigned using the Fibonacci numbers. The Team Members are essentially grouping the stories into equivalence classes by effort required, i.e. all stories with a required effort between 13 and 21  are assigned a value of 13.

To do this, the Scrum Master provides a set of cards with the Fibonacci numbers (one per card): *1*, *2*, *3*, *5*, *8*, *13*, *21*, *34*, *55*, *89*, *144*, and *?*. (The *?* card stands for "We just don't know." You may find yourself in this situation when some bit of vital information is missing. In that case, you would first try to identify the missing piece, by asking yourself, "What question do we need to answer, so that we can give this item a size?" You would then create a special kind of story called a "research spike" and mark the original, indeterminire story with a question mark. The research spike could be something as simple as, "Ask the customer for more information," or as involved as writing a bit of code to learn more about an unfamiliar technology.")[^1]

With the ordered stories from Part I, and the Fibonacci cards, the Team Members group the stories following the rules below:

>### Part II: What's Your Number?[^1]

>Each player takes a turn, in which they may do any **one** of the following actions:
>
* **Place the next Fibonacci card above a story card, indicating where the next increase in story size occurs.**
* **Move a Fibonacci card to a different story.** The move must preserve the order of the number cards, that is, one must come before two, 13 before 21.
* **Move a story card, just as in Part I.**
* **Pass their turn to the next player.**

>Play continues until every player passes, indicting that there are no more adjustments needed to the order of the stories, or the size assignments.

At the completion of Part II, the Product Owner can begin the work of prioritizing the Product Backlog for the next Sprint Meeting.

[^1]: Sims, Chris and Hillary Louise Johnson, *The Elements of Scrum*, Dymaxicon, 2011. From the chapter "Estimating the Work With Story Sizes".

##Copyright and License
####&copy; 2014 Karl R. Wurst, Worcester State University

<img src="http://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-sa.png" width=100px/>This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit [http://creativecommons.org/licenses/by-sa/4.0/]() or send a letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View, California, 94041, USA.
