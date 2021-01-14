# 66DaysofData
*Documenting my journey through Ken Jee's #66DaysofData (Round 2).*

> *<ins>A bit of a preamble</ins>: Since starting my data journey late last year, frankly, I did not do a great job of planning. I was so excited to jump in that I dove headfirst into Python, simply because it's what I was seeing the most of on YouTube and in the 66DaysofData discord server. Now that I've gotten a little bit over the kid-in-a-candy-store adrenaline rush, I've taken a step back and realized (with the help of a few role models and looking through a lot of job postings) that my time and effort would likely be much better invested in other (ostensibly less "sexy") things right now. While I am so happy with all the things I've gained exposure to until now, I've decided to focus mainly on getting comfortable with SQL, building a good stats foundation - and just understanding this whole data science ecosystem!*

### Day 1 (01/06/2021): SQL fun
Having already completed most of the SQL questions on hackerrank, I've branched out to both LeetCode and Codewars for my daily SQL querying practice. Of the handful of problems I solved today, [my favourite today](https://www.codewars.com/kata/581fb63e70ca28d92500000d) involved improving the performance of a working query. I *know* my queries are hacky and inefficient so it was a good change of pace to think about making queries more scalable. Starting tomorrow, I also plan on checking out [Learning SQL](https://www.oreilly.com/library/view/learning-sql-3rd/9781492057604/) and [The Art of SQL](https://www.oreilly.com/library/view/the-art-of/0596008945/) to hopefully build a better theoretical understanding of databases and a more structured approach to querying.

### Day 2 (01/07/2021): A bit more SQL fun
Didn't do as much as I would've liked, with a longer work day and evening commitments. Fortunately, I did a few more SQL problems on LeetCode to start my morning. I love starting off the day with some personal development to build momentum for the rest of the day. [Today's favourite question](https://leetcode.com/problems/nth-highest-salary/) allowed me to practice creating a function, using a window function and using a CTE.

<p align="center"><img width="600" height="200" src="https://i.imgur.com/jZ2wjR2.png"></p>

Window functions were one of those concepts that seemed so intimidating before I learned the syntax. Now, I find them approachable and intuitive syntactically (for the most part) even though I've obviously only scratched the surface of their potential.

I am curious though: How much are CTEs used in practice? Since they're still a relatively new toy for me, I'm almost positive I use them unnecessarily. Right now, CTEs are my hammer and every problem sure looks like a nail to me!

### Day 3 (01/08/2021): Be Better Than Me (SQL Edition)
[Today's favourite question](https://leetcode.com/problems/consecutive-numbers/) (I'm sensing a trend) led me down a bit of a rabbit hole in comparing self joins vs lead/lag window functions. I needed to find consecutive rows with the same value and naturally thought of using [lead/lag](https://i.imgur.com/WTtkEvr.png). This probably has to do with my excess enthusiasm for recently learned tools, as I mentioned yesterday. I felt a bit silly because I could've easily done the same with [a pair of self joins](https://i.imgur.com/ynLrlBc.png). However, I submitted both solutions... and to my surprise, the run time was virtually the same. Of course, I'm not sure how much of this is due to the super simple table but I thought that was interesting.

Digging deeper, I found [this forum post](https://dba.stackexchange.com/questions/158374/performance-comparison-between-using-join-and-window-function-to-get-lead-and-la) asking the exact same thing and it seems that may not have been just for me. I originally thought I had just overcomplicated the solution for little reason but I may have accidentally stumbled upon the "better" answer.

Be better than me though. Be right on purpose; consider all your options and possible solutions *first*!

### Day 4 (01/09/2021): Sometimes you don't even realize you're getting better until you do
No favourite question for today but while exploring a different SQL resource ([StrataScratch](https://www.stratascratch.com/)), it just kind of hit me. Either I'm getting better at this SQL thing or the problems are just easier there. Fingers crossed it's the former and if it is, for anybody else struggling down this path too... *sometimes you don't even realize you're getting better until you do*. It's so easy to miss all the subtle ways you're consistently adding new skills, clarifying the actual problem you're solving, or writing cleaner syntax. Until one day, you realize the things you distinctly remember struggling with for the longest time become less of a struggle, then eventually just become things you can solve in your sleep.

You never get there as quickly as you want (believe me, I know) but if you keep going, you *do* get there.

Unless the problems are just easier on StrataScratch.

### Day 5 (01/10/2021): Learning SQL (The Book)
I guess I binge solve SQL practice problems the way some people binge watch TV shows. I have now completed virtually every free question on StrataScratch this weekend and quite enjoyed it. I may talk more in depth about my experience with a few different platforms I've used in a later post, but I liked how there was some continuity between different questions on StrataScratch. (Presumably because they came from the same technical interview.) It was nice to see the same data structure used to solve questions of varying difficulties.

I finally started reading through [Learning SQL](https://www.oreilly.com/library/view/learning-sql-3rd/9781492057604/) by Alan Beaulieu to get a more structured view of SQL, now that I've had some exposure. While I learned many concepts and techniques by focusing on solving real questions and consuming good SQL content from the LinkedIn data community, my goal now is to take a step back and build a broader base of knowledge. Struggling through things on my own first gives me a better context for the material and helps me better connect theory to specific personal examples.

Fun fact: ANSI published their first standard for SQL in 1986... so SQL is officially 3 years older than me?

### Day 6 (01/11/2021): Schema, Data and Transaction Statements
I only had a bit of time today to read [Learning SQL](https://www.oreilly.com/library/view/learning-sql-3rd/9781492057604/) and I'm encouraged by the author's writing style and the organization of the book.

So far, 99% of my time working with SQL has been spent on data statements. I've only worked on learning the query side. And it makes sense; it does seem like it'd be way simpler to work with premade data structures that other people have built. However, I always knew I'd probably also need to explore more of the schema side to get a better understanding of SQL. Of course, you learn about primary keys and foreign keys naturally, just by joining tables together but I'm excited to learning more about data types, constraints, data dictionaries and a million other things I don't even know exist yet. (The author talks about transaction statements and I have literally no clue what they are.)

### Day 7 (01/12/2021): Chess Visualizations!
I took quite the detour today. I scanned through a dataset of just over 20,000 chess games, played online at lichess.org. Why? Because it was curated by Maven Analytics for their [new data visualization challenge](https://www.mavenanalytics.io/blog/queens-gambit-challenge)!

As a recreational chess player who actually plays mostly on lichess these days, I'm so excited to dig into this dataset and see what I can put together. (I must admit... I scanned through their dataset to see if any of my own games made it in and sadly they did not.) My tool of choice for this challenge will be Tableau. I've already started doing a bit of feature engineering with a few calculated fields and I have a few more in mind already that I need to create.

If you're into data visualization, please join me in this challenge! Thanks for hosting this, Maven Analytics.

### Day 8 (01/13/2021): Thank goodness for five minutes a day
Haven't had as much time for extracurriculars as I would like lately but we have to keep that streak alive, hah! Today's focus was on doing more feature engineering in Tableau, with [Maven Analytics'](https://www.mavenanalytics.io/) chess dataset. It feels like this dataset is deceptively rich, which just adds to the fun. (Or more likely I'm just not good enough yet to have properly assessed the dataset in the first place. Who knows? :D)

Is there anything you are curious about and would like for me to take a look at?

Still not too late to [join the challenge](https://www.mavenanalytics.io/blog/queens-gambit-challenge)!
