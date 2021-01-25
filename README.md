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

### Day 9 (01/14/2021): I miss SQL (for some reason)
Work has been a little more hectic lately (just accounting things), which hasn't left me as much time or energy for after work things as I would like. As a result, I've chosen to spend all my time the last few days on this chess data visualization challenge. One, because chess. Two, I feel like I can get more accomplished (relatively speaking) here, when working in smaller chunks of time.

But I miss SQL. I miss writing queries. It feels like I missed a part of my day. Is this part of my identity now? Am I a SQL-er? That's... kind of exciting, honestly.

### Day 10 (01/15/2021): Slowest day so far
Took it super easy today. I haven't exactly been going all out the last few days but I really wanted to prioritize recovery. I had a great time listening in on the Artists of Data Science happy hour today. It was a lot of fun just listening to a group of data science people talk about data science things in real time. I hope this continues forever and I can keep showing up!

(I lied. I also did a SQL question on CodeWars too. I really, really had to scratch that itch. It'd been a few days.)

### Day 11 (01/16/2021): 
Cheesy warning: I'm grateful for LinkedIn, because of the communities you get to be a part of and the people you get to interact with. A lot of people have given me extra motivation to continue down this path and I've very grateful.

Anyway, today's data time has been spent on a couple SQL problems on CodeWars and thinking about ways to bring value through data in my day job (yes, on a Saturday). Tomorrow should be a day of minimal outside obligations so I hope to have a lot more things to share tomorrow night.

### Day 12 (01/17/2021): Chess, Tableau and SQL

For Maven Analytics' #queensgambitchallenge, I chose to [submit something](https://public.tableau.com/profile/wilson.man#!/vizhome/Lichess/Dashboard1) primarily for an audience likely not super familiar with chess and probably just scrolling through LinkedIn on their phone. With that in mind, I kept it simple with only a few (hopefully) visually appealing panels, with no interactivity.

e4 was by far the most popular first move for White, with d4 a distant second. Black loves to respond with the Sicilian defence (c5) and does so quite successfully. So much so that maaaybe it contributes to White playing d4 more and e4 less at higher ratings.

Bonus: If I'M playing black against Harmon and we play the Queen's Gambit, my second move of the game is c6. I looked through my own Lichess history and the Slav is the defence I'm most comfortable with against the Queen's Gambit. Is answering the question this way cheating? I don't think so! :D

Thanks again for putting this challenge together, Maven Analytics!

### Day 13 (01/18/2021) Reflection on the #queensgambitchallenge

I enjoyed putting my chess visualization together in Tableau. I went down many rabbit holes and did a bunch of feature engineering before taking only a small subset of it for the final product. At the end of the day, I felt the context around this visualization led very naturally to the 2x2 story format I ended up with. In a different context, I feel like there was so much more depth I could have presented.

And while reflecting on the process of participating in Maven Analytics' challenge, that was my main takeaway: *Pay attention to context and audience; your visualization is for them, not you*.

I saw a lot of beautiful visualizations that had a lot going on. I could definitely be wrong but it didn't seem like they were the best fit for how they would be presented for voting. I took inspiration from that to go the opposite way; I stuck to minimal information about one possible line of exploration. This second piece might've just been me overthinking, but I noticed the lengths that Maven Analytics went to in explaining basic information about chess. That suggested to me that the intended audience might be those unfamiliar with chess.

Understanding the 5 Ws of what you're creating is crucial.

### Day 14 (01/19/2021) Diving off the SQL deep end

Keeping today's update short and sweet: Frankly, the most exciting part of today was setting up a MySQL server on my computer and running a SQL script from the command line without blowing everything up. It's wholly irrational but the command line intimidates me like nothing else. A lot of googling (and hair pulling if I had any) but all crises were avoided. This time. I'm chalking this up as a major victory and calling it a night there.

(Although while we're at it, I never thought I'd have posted on LInkedIn for two weeks straight. I've never really been one to compare myself to anybody else but there's just something about sharing my "progress" amidst the sea of people smarter, more accomplished and further along in this journey than I that leaves me feeling somewhat vulnerable and uneasy. However, my only New Year's resolution every year for the last few years - if you can even call it one - is to get more comfortable being uncomfortable... so we're doing it anyway. Enjoy!)

### Day 15 (01/20/2021): Solve the right problem

I think I can check the box for my daily #66daysofdata effort since today's SQL lesson took more than five minutes to (re)learn. I really wish it hadn't though. It started off as a fun CodeWars SQL exercise in finding the most concurrent visits to a website and ended with a facepalm. Today's protip is: Know what your output is supposed to be. I started off solving the problem with a self join and when my output kept erroring out, I tried everything to figure out what I was missing in my logic including mapping it out using a sample dataset with pen and paper.

... It turns out my only mistake was including an extra id column! This was just a silly, low stakes example but I appreciated the reminder that the only way you can get the correct answer is by solving the right problem.

(Also, part of my where clause was redundant. Oops.)

<p align="center"><img width="600" height="150" src="https://i.imgur.com/SFQ74nY.png"></p>

### Day 16 (01/21/2021): Today I learned

I'd learned that bigint existed as a data type in SQL fairly early in my SQL journey but only just learned today that mediumtext and longtext existed too. I also had no idea that some languages require multiple bytes of storage per character, given the sheer number of possible characters. I don't know that these will ever be useful to me. However, I find these nuances that I *never* would've picked up just from practicing writing SQL queries quite fascinating.

On an unrelated note, I've also decided to participate in another challenge, this time from [Strategy Titan](https://www.strategytitan.com/blog/titanized-real-world-dataset-to-develop-your-analytics-muscle). I will probably build this one in Tableau too, after exploring and cleaning the data in Python. Hopefully I can spend a lot of time on it this weekend.

### Day 17 (01/22/2021): In the spirit of accountability

In the spirit of accountability, I'm really just making this post to say I didn't really do anything today. I had a good time listening in on The Artists of Data Science again this week though. Maybe that counts. Very fascinating conversation around long-term productivity and burnout. I also did a thing for work that I kind of want to keep secret (at least for now?). That's it though. Looking forward to the weekend and its eternal promise of more time and energy for learning things.

Further in the spirit of accountability, I plan on reading a couple chapters (at least) out of Alan Beaulieu's Learning SQL and starting on [Strategy Titan's](https://www.strategytitan.com/blog/titanized-real-world-dataset-to-develop-your-analytics-muscle) challenge that I mentioned yesterday.

### Day 18 (01/23/2021): Back to some Python too

I've had minimal exposure to the non-querying parts of SQL so while some of my reading today was review, I learned a few things I found useful. If you've been more busy running SELECT statements to your heart's content like I have, you may know a little about CREATE TABLE, INSERT INTO, UPDATE, DROP already but maybe not:

* DESC table: This statement describes the structure of a table. Before this, I always had to google the right query syntax to look in the INFORMATION_SCHEMA.COLUMNS table. This is way more intuitive!
* SHOW TABLES: This statement shows a list of all the tables available in your database. Obviously not as important when solving problems with only a couple tables.
* ENUM (data type): Generally used to restrict values for a column, but maybe it's not best practice?

I did a bit of googling on ENUM. It seems using a foreign key constraint and lookup table is considered more robust, especially if you anticipate having to update the permitted values.

(Instead of starting the analytics challenge, I spent a couple hours today writing some Python to read and clean spreadsheets. Wow, my Python is very rusty. Way too much looking at documentation to remember fairly basic syntax.)

### Day 19: (01/24/2021): SQL Tips

Read another chapter of Learning SQL today and wanted to share my two favourite tips:

* DISTINCT takes more resources than you might think. Of course, there are cases where it's necessary but if you're using it just as a blanket solution to removing duplicate values from your query, you could be significantly hurting performance. [This article](https://webbtechsolutions.com/2009/07/24/the-effects-of-distinct-in-a-sql-query/) seems to do a good job elaborating on this. In the example used, SELECTing DISTINCT on a table with just 20,000 rows was 12% slower (with 4x the subtree cost... whatever that means)!

* Evaluating logic statements with NOT operators can be more mentally taxing to humans to evaluate than one without. This one is more subtle and obviously not universally applicable but thinking about readability is often overlooked (at least by me) but super important if you're collaborating with others or just need to debug your work (or if others need to debug your work).

I am curious though! Does one of these make more sense to you than the other?

> NOT (title = 'Teller' OR start_date < '2007-01-01')

> title != 'Teller' AND start_date >= '2007-01-01'
