---
layout: essay
type: essay
title: Reflecting on Assignment 2 Technical Essay
# All dates must be YYYY-MM-DD format!
date: 2020-11-24
labels:
  - Assignment2
  - Learning
---

1. Provide a brief introduction to the assignment along with a link to this page for further details<br>
-For this <a href="https://dport96.github.io/ITM352/morea/150.Assignment2/experience-Assignment2_retrospective.html">Technical Essay</a>, I'm going to talk about <a href="https://dport96.github.io/ITM352/morea/150.Assignment2/experience-Assignment2.html">Assignment 2</a>. In Assignment 2, I had to upgrade my e-Commerce web-site that I previously designed in Assignment 1. The main requirements for this upgrade is to include a registration form through which users can register their information and a login form for users to log in, given that users' data would be saved in the system. The site also needs to be more personable and users must be able to access their invoice after logging in or registering. Aside from new requirements, any errors from Assignment 1 must also be fixed.
<br>

2. What did you learn from this assignment?<br>
-In this assignment, I learned how to incorporate the newer things I learned in the labs and apply them to my assignment. For example, how to effectively display transient data on a server and how to validate login information and registration. I had a difficult start because there are not a lot of examples from in-class labs that directly apply for MVC, so I had to adjust and modify quite a bit to integrate certain codes and get things working the way I want them to. I think I learned a lot more about debugging only because there were so many errors I had to fix, that I think I got slightly better at identifying certain errors, compared to before. I also learned about the difference between passing transient data on the server versus using a query string, thanks to the in-class workshop.
<br>

3. Did you work with a partner? Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself).<br>
-I did not work with a partner.
<br>

4. How did you get help when you needed it? What did you need help with?<br>
-I emailed Professor Port when I was really stuck about transient data. I wanted to retain a user's quantity form data from products page, to login/registration, to the invoice page. Since I was using MVC, it seemed that generating the information from the server would be better than using a query string, even though there are some security flaws with that. I ended up receiving help during an in-class workshop that I'm very appreciative of, and in the end there were only a few lines of code that I needed to change and add that I didn't think about before. Another time, I had issues with using an alert package downloaded to my node modules. It successfully displayed my alerts when I tested my application locally, but it did not work on the class server. I also emailed Professor Port for this, and I ended up changing how I displayed my alerts. Instead of using the node package, I tried another way and in the end it worked just as well, or even better than the node package. Other than these two instances, I have swapped some ideas with a classmate and gained insights that led me to solving a problem about quantity validation.
<br>

5. How was developing this assignment different than assignment #1?<br>
-I think this assignment was a lot more difficult to develop, because I had some validation issues that I needed to fix from assignment 1 that took me a while to fix before I finally started on assignment 2. This and the other problems I had were the reasons why I spent a long time on this assingment. There were a lot more testing involved, and at some points I had to completely change the way I did things. I definitely Googled things more as well, especially when it came to registration validation, which led me to useful resources that I could modify to integrate into my own code. Other things I looked up included different error messages, because I came across a few when testing on the class server. In general, this assignment felt like there were a lot more thinking, testing, debugging, and searching.
<br>

6. Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging <br>
-I spent maybe 35% of my time thinking about how to do something, 15% writing code, and 50% testing and debugging.
<br>

7. Describe what worked <b>well</b> with this project? What did <b>not work</b> well?<br>
-One thing that worked well that I'm actually really proud of is that I was able to find a way display my alerts while keeping data sticky without using the alert package that I hoped would work. I really like the way that error messages are displayed after validation and how it redirects users to the previous page. What didn't work well was a clutter of redundant code that I had and some horrible variable names that were confusing, and things were a lot easier to read once I fixed those. Aside from the alert package, I think there were some other packages that I tried but did not work, and I didn't want to spend too much time on those since they weren't required and I found different ways to approach things.
<br>

8. If you could go back in time and do things differently, what would you do differently?<br>
I would have spent a lot less time being stuck on one problem. I was really frustrated at some points trying to figure out why certain things didn't work. If I went back in time, I would just rewrite blocks of code or changed how I approached certain problems, because it would've saved me a lot more time than rapidly changing little things and testing things after every change.
