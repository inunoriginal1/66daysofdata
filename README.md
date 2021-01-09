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
