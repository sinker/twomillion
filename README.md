Two million dollars and one hour: notes to help you not shit the bed.
==========

[Notes to accompany my SRCCON session.](http://schedule.srccon.org/#_session-7)

Starting a news site is a balancing act: How can you achieve maximum editorial quality, awesome design, and kick-ass frontend apps (and the backend to support them), while having an infrastructure that doesn't go down, happy employees, an office space, and--eventually--achieve profitability?

*Spoiler alert*: We're totally not going to solve that in an hour.

But this session--like running a real business--is an exercise in managing the trade-offs, to figure out a strategy, and to achieve a balance that gets you moving towards profitability.

A few money rules
-----------------
* The Blackbeard Venture Fund has invested $2 million in your news startup. Each coin in the pirates purse you've been handed is worth $50,000.
* You have two years to get your company in the black: There is no series B round, there is no exit strategy other than simply actually making money.
* For this exercise we define "in the black" as self sufficiency, not actually paying the money back.
* That means, by the end of year two, you need to be able to generate enough money to at least cover your monthly costs.

A few ground rules
----------------
* This isn't _just_ about moving coins around. You also need to develop a site people care about: You need an editorial POV, an audience, a publishing strategy, + plans for people actually finding out about your stuff.
* Your group will need to decide on an editorial direction, how to staff it, and how to achieve profitability.
* You need to give a _TWO MINUTE PITCH_ at the end of the session. That pitch should include:
  * What the idea is
  * Who is it *for*
  * What's your staffing look like
  * How you allocated your budget
  * How you're making money


Some basic money guides
-----------------------
Hey: This is a room full of really smart people, and I bet you all have better ideas on some of this stuff (read: SERVER COSTS) than I do. But I did some basic blocking here.

* Benefits
  * fine benefits: multiply your salary lines by 30%
  * good benefits: multiply your salary lines by 40%
  * silicon valley benefits: multiply your salary lines by 50%

* Rent
  * Manhattan rent is around $65/square foot.
  * Portland, Oregon? $25/square foot.
    * Average guides say assume 100-150 sq ft per employee.
  * Going virtual instead? Slack is $7 per head per month

* Servers (A lot of this pricing depends on what you're doing, obviously.)
  * A content-heavy site, without a lot of computing bells and whistles, served smartly, runs around $100/month per million visitors.
  * If you're running EC2 instances, Rackspace Cloud services, or Heroku Dynos--which you'll want to if you're doing any real computing (running news apps, building a custom backend or dynamic frontend, etc)--your pricing will be quite a bit different.
    * Very lightweight (running a single app for an interactive or two that's well cached, for instance, or heavily flatfiled, storage-only setups): $100/month
    * Midlevel EC2 (running apps with heavier compute needs): $500/month
    * Highlevel EC2 (running basically everything off a cloud stack): $1000-$2000/month
    * You milage could vary wildly. There are calculators:
      * [Amazon AWS Calculator](http://calculator.s3.amazonaws.com/index.html)
      * [Racespace Cloud Calculator](http://www.rackspace.com/calculator/)
      * [Heroku Calculator](https://www.heroku.com/pricing)

* Content
  * Going to go freelance? Reputable rates are (broadly) $250-500 per piece.
  * Obviously, there are plenty of places on the internet that pay less.
  * Less can mean free: but have a strategy for how that keeps up (and gets started to begin with).

* Ping-pong tables, Ball Pits and Nerf Guns
  * Ima let you price this kinda thing out on your own. But remember they will require square footage.


An important staffing note for nerds.
--------------------------
* DON'T FORGET SUPPORT STAFF: Who cuts your checks, balances your books, answers the phones? Probably not you or the folks doing the reporting.
* If you're going to make money from selling ads or putting on events or some other way, there's probably staff involved in that too.

One final thing to remember
---------------------------
* Your costs reflect where you are in the process. Maybe you don't need bulletproof servers while you're in the early stage of building. Maybe your front-end dev needs grow as the site does? Maybe you don't need a ball pit... at all?
