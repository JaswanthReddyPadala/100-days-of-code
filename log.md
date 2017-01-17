# 100 Days Of Code - Log

### Day 19: January 17, 2017

**Today's Progress**: Worked through some intermediate coding challenges on FreeCodeCamp.

**Thoughts**: Since I didn't want to set out on a full project today, I decided to start working through some of the Intermediate Algorithm challenges on FreeCodeCamp. Finished two, started working on the Roman Numeral challenge. Also did some more code-along with Adam Wathan.

**Link(s) to work**: [TicketBeast](https://github.com/maxveldink/ticketbeast)

### Day 18: January 16, 2017

**Today's Progress**: Today was a hectic day, so I only worked on my TicketBeast app with Adam Wathan.

**Thoughts**: It is very cool to see pure Test Driven development being exemplified by Adam Wathan. Can't wait to watch more of his stuff. I also got halfway through Jeffrey Way's What's New in Laravel 5.3 Series.

**Link(s) to work**: [TicketBeast](https://github.com/maxveldink/ticketbeast)

### Day 17: January 15, 2017

**Today's Progress**: Redid the 100 Days of Code Log

**Thoughts**: In addition to watching a ton of Test Driven Laravel by Adam Wathan, I redid the 100 Days of Code Log and published it to GitHub pages.

**Link(s) to work**: [100 Days of Code Log](https://github.com/maxveldink/100-days-of-code)

### Day 16: January 14, 2017

**Today's Progress**: Finishing touches to the URL shortener api.

**Thoughts**: I cleaned up the code quite a bit for my URL shortener app. I might come back to it later to implement a few more safeguard to prevent duplicate URLs. I spent most of the day in the weeds trying to make the asynchronous callbacks play nice, and I decided to move on to a different project tomorrow. I'm going to start building the random quote machine on FCC.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 15: January 13, 2017

**Today's Progress**: Fixed the redirection issue. Added more content to the root to detail how to use the app.

**Thoughts**: The redirection issue turned out to be just a type error. Note to self: when you pull props from the req.params object, they come off as strings and need to be converted to numbers if you want to use them as such. That took longer than it should have. To finish the day, I just polished the index.html.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 14: January 12, 2017

**Today's Progress**: Started to modularize the Yummy URLs app. Broke redirection.

**Thoughts**: I started by trying to modularize the code. After I figured out how to do that, created a helper file to handle most of my interactions with Mongo. Saving to DB now occurs through this. I still need to implement my check to see if the original URL exists or if the short code already exists. Redirection stopped working before I moved it, so tomorrow will be troubleshooting that.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 13: January 11, 2017

**Today's Progress**: Implemented the redirection request for Yummy URLs.

**Thoughts**: Implemented a redirection handler when someone enters a short code to the Yummy URL service. I don't think I have done it in the most efficient manner but it works. Tomorrow I want to work on edge cases. First, I want to check to make sure the user URL exists before adding it to the database. Then I want to handle situations when a shortcode is generated that already exists in the db.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 12: January 10, 2017

**Today's Progress**: Hooked MongoDB up for the URL shortener, as well as made the intial pass at trying to create the short URL.

**Thoughts**: I have successfully hooked up a dev DB and a prod DB for my URL Shortening app. I also made a rudimentary shortener. I want to try again tomorrow at making it simpler, using only numbers, and to check to make sure that the short URL has not been used before. I also need to work on the root page usage examples, as well as restructure the code to use a single DB pool.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 11: January 9, 2017

**Today's Progress**: Made forward progress on the URL shortner. Went down the Firebase rabbit hole, but ultimately decided to stick with MongoDB.

**Thoughts**: I have everything scaffolded out so now all that is left is to wire up the different parts. I will work on implementing Mongo tomorrow, and once that's rolling I think it'll be completed soon.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 10: January 8, 2017

**Today's Progress**: Finished Wes Bos' Redux series. Spent the entire hour figuring out why ESLint kept crashing in my project. Again.

**Thoughts**: I spent more of the same our trying to figure out ESLint without much progress to show. I finally got to a place where I'm going to leave it for now and try again later. Tomorrow will be real progress!

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 9: January 7, 2017

**Today's Progress**: Finished Wes Bos' React for Beginners, and started in on the first few videos of his Redux series. Spent the entire hour figuring out why ESLint kept crashing in my project.

**Thoughts**: Killer tutorials again by Wes Bos. I spent a frustrating hour trying to figure out why ESLint was not pulling in the HTML plugin correctly. Still don't have a clear solution, but I did get a nice exercise in googling around and following different troubleshooting methods. I guess you need a few days like that.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 8: January 6, 2017

**Today's Progress**: Worked more on Wes Bos' React for Beginners course and worked through some Video Challenges at FreeCodeCamp.com.

**Thoughts**: An addendum I'm adding to the rules, while I work through these tutorials (I work better when I don't have large gaps in completing tutorials), is to allow them in my hour of code. Most of my time was spent researching and Firebase vs Mongo.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 7: January 5, 2017

**Today's Progress**: Worked more on Wes Bos' React for Beginners course and worked through some Video Challenges at FreeCodeCamp.com.

**Thoughts**: I was so caught up in finishing tutorials today, but ran out of free time to actually write code. Tomorrow morning, I'll start working on the URL Shortener once more!

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 6: January 4, 2017

**Today's Progress**: Worked more on Wes Bos' React for Beginners course. Applied the Firebase learning to the URL shortener.

**Thoughts**: I wanted to compare implementation of Firebase and MongoDB to see which I would like better.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 5: January 3, 2017

**Today's Progress**: I spent all of my time figuring out how to use MongoDB from within an Express JS app.

**Thoughts**: It took a while, but I finally figured out some basics for working with MongoDB on my URL Shortener. MLab is a lifesaver. Tomorrow I'm going to be shooting for starting on the actual user stories for the challenge.

**Link(s) to work**: [Yummy URL](https://yummy-urls.herokuapp.com/)
[Yummy URL GitHub Repo](https://github.com/maxveldink/fcc-url-shortener)

### Day 4: January 2, 2017

**Today's Progress**: Finished up the Request Headers FCC challenge and started working on the next FCC challenge, a URL Shortener. Tomorrow looks like a dive into Mongo.

**Thoughts**: Did some good work with Request Headers today. Because there's so many different types, I had always been reticient about using them. This challenge helped quell some of that fear. I also started working on using MongoDB with my next FCC challenge, a URL Shortener. I'm looking forward to working with DBs more.

**Link(s) to work**: [Yummy Request Headers](https://yummy-request-headers.herokuapp.com/) Request Header Parser Microservice for FreeCodeCamp

### Day 3: January 1, 2017

**Today's Progress**: Finished the front end of Yummy Timestamps, and marked that project complete in Free Code Camp! Also watched more of Wes Bos' React for Beginner series.

**Thoughts**: I got to implement some Flexbox, very little but it's the first time I've really worked with it. Pretty slow day, CSS definitely isn't my strong suit. But that's the point of these exercises!

**Link(s) to work**: [Yummy Timestamps](https://yummy-timestamps.herokuapp.com/) Timestamp Microservice for FreeCodeCamp
[Yummy Timestamps GitHub Repo](https://github.com/maxveldink/fcc-timestamp-microservice)

### Day 2: December 31, 2016

**Today's Progress**: Finished the functional code part for Yummy Timestamps. Works like a dream 👍

**Thoughts**: It took a little over an hour to get the Timestamp microservice up and running. I feel weird about doing so much logic inside the Route closure, and if this was a larger project I'd probably separate that from the server.js file. I don't like working with dates, but I'm glad I figured this one out. Shout out to the dateformat library on NPM, that's a lifesaver.

**Link(s) to work**: [Yummy Timestamps](https://yummy-timestamps.herokuapp.com/) Timestamp Microservice for FreeCodeCamp
[Yummy Timestamps GitHub Repo](https://github.com/maxveldink/fcc-timestamp-microservice)

### Day 1: December 30, 2016

**Today's Progress**: Finished up Wes Bos' ES6 for Everyone. Set up the environment for using ExpressJS on my local machine and did more work on YT, hoping to get it finished up tomorrow.

**Thoughts**: I have learned a ton from ES6 for Everyone, I highly recommend it. Understanding the tooling for getting ExpressJS up and running, and getting a nice build/commit process and a deployment to Heroky set up for Yummy Timestamps took a large majority of my time, since I have never done that before. But I feel more confident in handling that and will be able to easily add services in the future.

**Link(s) to work**: [Yummy Timestamps](https://yummy-timestamps.herokuapp.com/) Timestamp Microservice for FreeCodeCamp
[Yummy Timestamps GitHub Repo](https://github.com/maxveldink/fcc-timestamp-microservice)

### Day 0: December 29, 2016

**Today's Progress**: Finished up FCC tutorials on NodeJS and ExpressJS. Watched more of Wes Bos' ES6 for Everyone. Started yummy-timestamps on Cloud9.

**Thoughts**: After committing to the 100 days of code challenege, I decided to think of some projects I wanted to do. I have been using FreeCodeCamp to fill in knowledge gaps. I will also be recording the tutorials I watch since I want to keep a record of those, but they will not count toward my one hour each day. I have decided to focus on a lot of their projects to help build real things, starting with the Backend Service projects. I will also be working along with Adam Watham's Test-Driven Laravel. The larger projects I want to work on are Servant Heart (a service ministry management platform for churches) and a lightweight meal planning web app.

**Link(s) to work**: [Yummy Timestamps](https://yummy-timestamps.herokuapp.com/) Timestamp Microservice for FreeCodeCamp
[Yummy Timestamps GitHub Repo](https://github.com/maxveldink/fcc-timestamp-microservice)