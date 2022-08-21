# Boiba: Tinder for Friends

**What does it do?**
Boiba is an app similar to dating apps, but intended solely to meet new friends in college. This was completed as a final project for CS 296, and this repo contains the only the backend portion, which decides which profiles to recommend to the user. 

**How does it work?**
The recommendation algorithm uses a snowflake database which contains fake data designed to mimic the actual patterns found in student surveys. Our hope is that the data is realistic enough to give us a good replica of the real data without having to deal with the confidentiality issues of using real data. The final product uses a decision tree to pick a compatibility score from 1-10 based on the input profile and the profile of the user being recommended to. We also experiemented with using a neural net to do the same thing. After extensive tuning and analysis, we determined the decision tree worked better due to it's accuracy and transparency.

**Project Goals, Skills, and Tools**
* This project allowed me to work with a SQL database for the first time, which I hadn't done much before but wanted experience with. We hit quite a few snags trying to get the connector to work and queries to run, but eventually did succeed.

* I also got to work with neural nets extensively, which I have only ever done in classes on toy problems. Building and tuning a net is much more difficult than it seems. We did our best, and got okay performance, but ultimately it wasn't good enough to beat the much simpler and intuitive trees.


**Reflection**
This project gave me a much better feel for how to do machine learning in industry. Since it was a group project, I had to coordinate with others and make sure we were on track to finish. It was also a semester long project, which means we put much more effort and time into it than most of the short assignments we do in school. The project itself was also much more challenging but also more freeing, since we could do whatever we want and use whatever we want, provided we could get it to work. Projects like this are much different than what is usually presented in class, but I find them much more educational and seem to better reflect how work actually gets done.
