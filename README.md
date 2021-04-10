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

### Day 19 (01/24/2021): SQL Tips

Read another chapter of Learning SQL today and wanted to share my two favourite tips:

* DISTINCT takes more resources than you might think. Of course, there are cases where it's necessary but if you're using it just as a blanket solution to removing duplicate values from your query, you could be significantly hurting performance. [This article](https://webbtechsolutions.com/2009/07/24/the-effects-of-distinct-in-a-sql-query/) seems to do a good job elaborating on this. In the example used, SELECTing DISTINCT on a table with just 20,000 rows was 12% slower (with 4x the subtree cost... whatever that means)!

* Evaluating logic statements with NOT operators can be more mentally taxing to humans to evaluate than one without. This one is more subtle and obviously not universally applicable but thinking about readability is often overlooked (at least by me) but super important if you're collaborating with others or just need to debug your work (or if others need to debug your work).

I am curious though! Does one of these make more sense to you than the other?

> NOT (title = 'Teller' OR start_date < '2007-01-01')

> title != 'Teller' AND start_date >= '2007-01-01'

### Day 20 (01/24/2021): More SQL Tips

As I continue reading through Learning SQL, I have two more tips (mostly for me to be honest, but hopefully also useful for you 😉)

1. BETWEEN is a convenient way to combine the <= and >= operators in one conditional. I forget it all the time. In fact, I could've used it in the query I showed five days ago. Hopefully you don't also use two conditionals when one will do.

2. The correct way to check for nulls is IS NULL, not = NULL. An expression can *be* null, but it can never *equal* null. This is a very common beginner mistake that I have also made plenty of times!

### Day 21 (01/25/2021): You're (probably) better than you think

There's nothing quite like getting real-time feedback on your technical skills from somebody whose opinion you respect. I doubt my skills constantly so I was genuinely pleasantly surprised to hear in a mock interview setting that all my SQL work has been paying off. When I don't have any frame of reference for what "good" looks like in context, I default to thinking "not good enough". Maybe this happens to you too.

I've talked about this before but I think it's such a pervasive feeling for so many people that I thought it was worth discussing again. It probably won't be the last time either. Continue to push yourself... but you're (probably) better than you think!

### Day 22 (01/26/2021): Speed up your queries with this ONE trick!

Came across this gem in today's Learning SQL reading and it's super simple in hindsight. If you're writing a multi-table query, don't join all your tables together, then filter down. Filter down your tables where it makes sense, then join them together. This makes intuitive sense to me. By joining the tables together first before filtering, you've created a larger table upfront. By filtering your tables before joining, you've reduced the number of rows (and probably columns) that your query has to work with throughout its run.

I've always defaulted to the former, because it came more naturally and the syntax was cleaner. Very easy to do it and just move on when all you're doing is solving problems with tiny tables on HackerRank or LeetCode but you'll be working with tables much larger in any real world application (presumably). I feel dumb for not realizing this sooner but consider this a PSA.

I love books.

### Day 23 (01/27/2021): Reviewing SQL

Read more out of Learning SQL today, but finally a chapter where I found it was just review (querying multiple tables). As a result, I breezed through without ending up in any google rabbit holes. (Yes, I'm know there are many more things for me to learn on this topic... just not necessarily from this book, in this chapter.) I kind of just felt tired all day today anyway so it was good timing. Still, happy I made it through. Time to rest up in time to do it all over again tomorrow. (I absolutely mean that in a good way.)

That's it. Super short post today. See you tomorrow!

### Day 24 (01/30/2021): I jinxed it

Hilariously, the one time I mention "tomorrow" in a post, I fall off for a couple days. Oops.

Anyway, I've been banging my head against the wall the last couple days because I've been trying to get back into writing some Python and my incredibly subpar skills have atrophied even more. And honestly, it's been incredibly frustrating so I took a bit of a break (aside from passive consumption of youtube content). Today, I decided to jump back into it and double down on the Python. Upon reflection, my problem is an incredibly shaky foundation and so I'm going all the way back to my first real introduction to Python, [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/2e/chapter0/). I loved the premise of the book when I dabbled with Python years ago and feel I need the refresher right now.

Nobody said this was going to be a smooth and easy journey.

### Day 25 (01/31/2021): Another confession

I reviewed the first two chapters of Automate the Boring Stuff and (thankfully?) most of it was review. I'm cognizant of the fine balance between going too slow (and overstudying things) versus going too fast (and building a shaky foundation), but think I want to err on the side of going too slow this time.

Speaking of which, let's get back into this daily posting habit with an embarrassing confession. I never really learned the difference between break and continue. The flow control statements, not the English words. I use them infrequently enough that I just googled it literally every time I thought I needed one of them. In case anybody happens to be in the same boat, I think the best way for me to remember this going forward is one **breaks** out of the current loop entirely and the other **continues** on to the next iteration of the loop.

### Day 26-28 (02/01/2021-02/03/2021): SQL review and more Python basics

Binge watched Tina's whole [SQL Sundays](https://www.youtube.com/playlist?list=PLVD3APpfd1tuXrXBWAntLx4tNaONro5dA) youtube playlist today to get my daily SQL fix. It's been a while but keeping the practice is important for retention and I'm relieved to find it was all review for me. That bodes well for a fun thing happening this weekend that I'm going to keep to myself (at least for now). I've also spent the last couple days going through more chapters of Automate the Boring Stuff. I'm going to finish off tonight with some more!

### Day 29 (02/04/2021): More Automate the Boring Stuff

Long day at work so I finished my night with more from Automate the Boring Stuff. Tonight was very simply more review on loops, converting data types and try/except clauses combined together in a mini guess the number game. Something is better than nothing I guess!

### Day 30-39 (02/05/2021-02/14/2021): Long hiatus

It's been a week and a half. Oops. Laziness and procrastination reared its ugly head. It's not that I did nothing, but if I'm being completely honest, it was very scattershot and inefficient learning for the most part. However, a few of the highlights were:

* Focusing more on learning data structures and algorithms (and their Python implementations), [thanks to Jovian](https://jovian.ai/learn/data-structures-and-algorithms-in-python). I've heard a lot that it doesn't matter if your solutions aren't the most efficient, as long as they work. I can absolutely see why this might be true. I also see why a lot of people need to hear this because inaction due to perfectionism seems to be a huge barrier for many people. However, I would feel a lot more comfortable with a stronger programming foundation. The course started with a familiar topic in binary search. Check it out if you're also interested! As a corollary, the terms time and space complexity have always intimidated me (honestly, probably because the word complexity is in the name) - but that's all the more reason to attack it head on.

* Doing a mock SQL interview with Tina. I failed, and not for technical reasons. Always good to know where I stand and where I need to get better. I do have a tendency to dive right into the problem and think as I solve instead of planning a solution in English upfront, before implementing that solution in code. Speaking of perfectionism, another issue I had is simply working on one thing at a time. It sounds so obvious but even while I was writing my solution, instead of writing *a* solution before trying to make it better, I was doing both at the same time which only made the process less efficient overall. I've started solving my SQL problems out loud, walking myself through the process to force myself to work on my problem solving approach.

* Starting to have one-on-one conversations with my peers in the data space. I love engaging with the content that people have put out. However, I've been missing the real time connection and back and forth. To that end, I intend to make time for and intentionally schedule conversations with awesome people in the #66daysofdata community and I've already had a couple. This isn't just for me though. I intend to publish write-ups on a weekly basis as I reflect on these conversations to share their wisdom, their story and their accomplishments. No sense in keeping any value to be gained to myself.

### Day 40 (02/15/2021): Recurring nightmare

Jovian has exposed me to binary search trees in their [Data Structures and Algorithms course](https://jovian.ai/learn/data-structures-and-algorithms-in-python)... and I'm completely out of my depth.

Perfect.

This only helps enforce exactly how much more work I need to put in building my programming foundation. Conceptually, it wasn't that hard to understand (I think). A binary tree is a data structure that makes it faster to do basic things like find, insert and update values in that data. It does that by holding your data in such a way that every time you turn over a rock to find what you're looking for, if you've turned over the wrong rock, you are guaranteed to eliminate half the remaining search space when you go to turn over the next rock. If you have 100 million data points, you'll only have to turn over 27 rocks at most (log base 2 of 100 million is ~26.6). Looking 27 times is astronomically better than looking through all 100 million elements (er, rocks?)!

Howver, this was one long lesson in recursion and that's the main thing that blew my mind. If Inception was a confusing movie to you too, then you'll understand my bewilderment. I'm gong to review a couple more times (at least) and work it all out slowly on paper and/or in my head before I get there and that's okay.

### Day 41 (02/16/2021): More recursion

Read a bit more about recursion and wrote a couple *super* simple recursion functions (to sum a list of numbers and to calculate factorials). [RealPython.com](https://realpython.com/python-thinking-recursively/) illustrated an example with Santa and his elves, which actually helped hah. The base case that returns something is the worker elf that actually has to do the work and the recursive part is the manager elf delegating the work (to another elf delegating to another elf delegating to another elf and eventually to the worker elf). [The Little Schemer](https://mitpress.mit.edu/books/little-schemer-fourth-edition) was also recommended in multiple places to learn recursion, so I'm now working through the book.

I'm winding down tonight with Nudge: Improving Decisions About Health, Wealth, and Happiness by behavioural economists (among other things) Richard Thaler and Cass Sunstein. It came up in a conversation I had with Jack, who'll be the first write-up in the series I'll be doing on #66daysofdata members. It'll probably go up Saturday morning! I thoroughly enjoyed talking with him and hopefully others can benefit from some of the things he shared with me.

### Day 42-43 (02/17/2021-02/18/2021): SQL break

Taking a breather from the recursion and data algorithms to do more SQL. I'm exciting to have Danny Ma's Serious SQL course. I'm most excited to supplement the query practice and the more high-level knowledge from my Learning SQL book with some practical application of SQL to actual case studies with a real SQL environment. I set up my own SQL server previously, but that was mostly to work with pre-existing tables and to follow along with the book material. I've been looking for a way to integrate SQL into my personal projects so this is perfect timing. Should be fun!

Shoutout to not just a master memer, but also an incredibly generous and knowledgeable member of the data science community.

### Day 44 (02/28/2021):

As they say in audit, "if it's not documented, it's not done." I'm going to follow that here going forward: If I don't share any progress, I haven't made any.

That being said, I've spent my weekend successfully tying up the loose ends of [my EDA project](https://github.com/inunoriginal1/OpenPowerlifting), figuring out how to push it to GitHub from the terminal and creating a presentable README. I've found it much easier to start things than to finish them, so I'm incredibly glad that I've now crossed the finish line on this one. I also plan to take the time in the next couple days to reflect on the entire process and put my thoughts down on paper. Funnily enough, writing more often and [publishing articles on Medium](https://wilsonman.medium.com/) has helped me appreciate the art of writing, and the way it forces you to express yourself more clearly, whether it's just to yourself or to others.

I've always been puzzled by how to take the next step and incorporate SQL into a project so that's something I plan to add to the next one. It seems much simpler to do it all in a Jupyter notebook, but a lot less like the "real world". I've gotten (very marginally) more comfortable with databases and managing them so we'll see how this goes.

### Day 45 (03/01/2021): Does it count?

Does it count if it was for work? I'm always looking for ways to learn new skills and apply them at work so when a colleague was looking to solve a problem that we've never done in-house before, I happily volunteered to build it out myself in Python. Simulations and data visualizations (of sorts) were involved so this was absolutely a win for everybody.

(... I hope! I ended up doing a ton of research because frankly, I had never even heard of what I did before I volunteered for the task.)

### Day 46 (03/02/2021): Sliced

Real time competitive data science is the entertainment I never knew I needed. I spent a few hours tonight watching [Nick Wan's Twitch stream](https://www.twitch.tv/nickwan_datasci), featuring two brave souls subjecting themselves to Nick's twisted sense of humour and battling it out on a Kaggle dataset. (For those unaware, Nick was a data scientist with the Cincinnati Reds and is now the data science manager at KFC US.) This was fun and helped give me a sense of how other people code and troubleshoot their ML notebooks live.

If that sounds interesting to you too, stop by next Tuesday night at 8pm CST!

I also read this article from Ken Jee on the mindset shift to lifelong learner (subscribe to his newsletter, it's great!). The part that resonated with me the most was a shift I'd also made myself in the last few years: adding the word "yet" to my vocabulary.

I'm not good at this... YET. I can't do this... YET. I'm not there... YET. Just because you aren't where you want to be now doesn't mean you can't get there in due time. :D

### Day 47 (03/03/2021): Reflecting

I'd jotted down some notes on some of the things I was thinking about in the aftermath of finishing my [first data project](https://github.com/inunoriginal1/OpenPowerlifting) and spent some time tonight forming coherent sentences on the things I've learned from the entire process. I'd like to think that I learned a few things data science related. I'd alos like to think I learned a few things not-so-related to data science. Hopefully writing them down can help me internalize the lessons better. If anybody else takes something away from it too, even better.

i also spent some time tonight thinking of other areas I want to explore for my next project. I have a few in mind but haven't committed to one yet. Stay tuned?

### Day 48 (03/04/2021): Mini-project

Drawing inspiration from an ESPN article I read a couple weeks ago, I discovered the `basketball-reference-scraper` package tonight and decided to start scratching that itch. Wrote a bit of Python code tonight to get the ball rolling. Frankly, I've already stayed up later than I intended to because I got in a bit of a groove and wanted to keep digging into this new toy. Sleep is important though so I'm pulling myself away for now. Goodnight!

### Day 49 (03/06/2021): More (mini-)project

After some more work on my mini-project, I think I answered the original question I was looking into. It was a fairly simple question (I think) but for better or worse, I feel inclined to keep digging. It feels like a bit of a waste to stop here! I'm going to give myself two weeks from today to work on this and we'll see what we can come up with.

### Day 50 (03/07/2021): Mostly reading

Most of my productive time today was spent reading [Nudge](https://www.amazon.com/Nudge-Improving-Decisions-Health-Happiness/dp/014311526X) and [Tune Your Chess Tactics Antenna](https://www.amazon.com/Tune-Your-Chess-Tactics-Antenna/dp/9056914049). It was refreshing to spend some time focusing on other topics. I've always been fascinated by behaviour and economics so a collaboration between behavioural economists is perfect. As a recreational chess player with some vague goal of becoming a titled chess player some day, the latter seemed productive.

Still found some time tonight for the basketball project. I think I'm finally dipping my toes into doing some actual machine learning, which is both exciting and nerve-wracking. We'll see how this goes.

### Day 51 (03/08/2021): Feature engineering

Spent a bit of time tonight doing some more data cleaning and feature engineering on my basketball dataset. Not at all done with all the pre-processing, but ended the night by running my very first "model" (in the loosest sense of the word) with sklearn. The coefficients from this linear regression are completely nonsensical, but this was a success to me nonetheless.

### Day 52 (03/09/2021): Much trial, much error

Messed around with feature selection mostly with multicollinearity in mind (ex: dropping FG% since I already have FG and FGA), before building a super simple pipeline with a scaler and a linear regression model. (My stats knowledge is quite rusty so that may not have made any sense. Back to the drawing board on stats!) Tried a bunch of different combinations and continued to get atrocious results (albeit less atrocious than the throwaway last night). Going to have to take a step back and actually try to figure out what I'm doing before tinkering any further. Going to re-group tomorrow by looking for other basketball machine learning projects. This was very much a lot of naivete biting me in the ass tonight!

P.S. Tuesday night means tuning into Sliced on Nick Wan's Twitch channel!

### Day 53 (03/19/2021): 

*ten days later*

For reasons I'm not quite willing to share just yet, power BI is getting my (almost) full attention for now. DAX Is its own beast and #upskilling in that domain has been interesting so far.

I also dropped the ball on sharing another fun story from our #66daysofdata discord community last Saturday. Another one should be going up tomorrow and hopefully we'll be back on track with those. There are so many people working hard to improve themselves and I want to keep sharing their journeys!

### Day 54 (03/21/2021): Intro to DAX

I spent the last two days getting introduced to DAX. I finished SQLBI's Introducing DAX video course and thoroughly enjoyed their approach to teaching the language. They provided a sample data model and focused on the practical while still introducing crucial theoretical elements. It feels like some kind of hybrid of Excel and SQL to me, which I appreciate since I'm fairly familiar with both.

One of the biggest takeaways for me was the importance of understanding row context and filter context of any calculation you write. As far as I understand, row context is relevant for the back-end (calculated columns in your tables) and filter context is relevant for the front-end (visuals and dashboards). Of course, with flexibility and customizability comes complexity and I would be negligent if I didn't mention that aggregation functions ignore row context and the CALCULATE function can override filter context (among many other things).

While I've unexpectedly taken a sharp left turn in my data focus for now, I'm excited to explore new territory. I'm reminded of just how much of it there is in this data science space.

### Day 55 (03/28/2021): Normalization

Still sticking with diving into Power BI, I am a third of the way through SQLBI's Introduction to Data Modeling for Power BI and tonight, I was introduced to the concept of normalization. I've heard the word thrown around but never knew what it meant. My understanding is that to normalize your data is to take steps to reduce the redundancy of your data and improve data integrity in the process. If your business sells products, this probably involves having a product table so that you don't have to repeat the product's name and related attributes on every row of your sales table. That way, you can avoid things like accidentally showing the same product sold to two different customers with different colours, for example, if you only sell it in one colour. (Weird example, but I didn't have a better one off the top of my head.)

The interesting part to me that I hadn't considered previously is how on the scale of fully denormalized (single table) to fully normalized, there isn't one right answer for where you want to be! Data integrity is paramount but too many tables can slow you down from actually using your data and running analyses. *Unfortunately*, you have to actually consider the implications of normalization and think about what might work better.

### Day 56 (04/04/2021): Different Table Schemas

I finally started reading [Supercharge Power BI](https://www.amazon.com/Supercharge-Power-BI-Better-Learn/dp/1615470522) and got to chapter 4 (the intro chapters are very short). The most interesting part was taking a detour through learning the difference between a couple different table schemas. Of course, there is the popular star schema, but I was also exposed to the related snowflake and galaxy schemas. As always, the main consideration is a tradeoff between data integrity (and disk space) and the complexity and speed of your queries/reporting.

The main difference between a star schema and a snowflake schema is that a snowflake scheme essentially has hierarchies to its dimension tables, where your fact table links to dimension tables that can also link to further dimension tables. This can reduce data redundancy in your tables, at the cost of sometimes needing multiple table joins to get to the level of detail you're looking for. By contrast, a galaxy schema can have multiple fact tables that link to shared dimension tables. As far as I can tell, the only additional consideration in design you need with galaxy schemas is how you build out the dimension tables that are *not* shared.

Of course, the book starts off slow and I'm going to finish up my night with the current chapter's practice problems on a few of the more common and basic DAX functions.

### Day 57 (04/06/2021): Chugging Along

Chugging along with those practice problems from [Supercharge Power BI](https://www.amazon.com/Supercharge-Power-BI-Better-Learn/dp/1615470522). They're a bit basic and tedious but it's helping me build the habit in the little things (honestly, like remembering to format any new calculated columns and measures). It's also nice to get through them fairly quickly without much struggling. I'm sure that'll come later though. :D

### Day 58 (04/08/2021): Filter Context

More Power BI! I'd encountered filter context before through SQLBI's super helpful intro courses so this was mostly refresher for me. Still, it was encouraging that I understood and kept up with this chapter on filter context on first read-through. It has been thoroughly stressed everywhere that this is a fundamental concept. It helps explain why sometimes you build a visual and every row has the same number for a measure. It's also interesting that any total is not a summation of the rows above it, for example, but instead a calculation with its own filter context. I'm sure it can get much more complex but baby steps. :D

### Day 59 (04/09/2021): Excel Users Beware

Supercharge Power BI is speaking to me right now. I love that it's taken the time to address the underlying structure of your data and thinking about the data pipeline, not just what you do with the data once you have it. Sharing a few tips I've picked up from the book (and also from SQLBI's intro courses):

* Don't go overboard with it, but make your tables as narrow as you can within reason. Additional columns take up more memory than rows do. This makes sense. I compare it to using two tabs in the same Excel workbook instead of having two workbooks (where workbooks are the columns in this case). Columns come with additional overhead.

* As a seasoned Excel user, the first instinct might be to create calculated columns, but resist that urge! Create measures where possible. This goes back to the storage issue... only worse this time. Calculated columns are stored less efficiently than imported columns.

* Still on the same note: Think about any redundant data (read: columns) you may have in your data. For example, if you have a unit price and a quantity sold in your sales table, you don't need a total price too. You only need two of the three and the third can be a measure.

Onwards and upwards.
