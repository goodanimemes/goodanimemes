## Hey! And welcome to goodanimemes

Im luna! The primary™ bot dev for the goodanimemes subreddit, nice to meet you!

So, i see you asking _"what bots are active in GAM, and what do they actually do?"_

### Post limiter

This is one of the mini™ scripts that is designed to enforce rule 12, 

**How it works?**

This script works by saving all the posts in a particular day to an SQL database
From here, it is quite simpile to see if a user has done a certain amount of posts that day
There is a few cute extras, for example, in the removal message it will tell the user about there last 5 posts and how long they have to wait before posting agian (to the second!)

**Feedback?**

Ah yes! Feedback, i love that, [you can contact me here](https://www.reddit.com/message/compose/?to=LunaLaTuna&subject=Feedback%20on%20the%20post%20limiter%3F), or DM me on discord! 

### Vote System 

The vote system consists of two scripts, to save recorses, i will be disscussing both 

**Scrape side**

This script is designed to use the reddit API (praw) and SQL to get the vote responses and do some basic analysis
This script checks if the user has voted already and checks if the vote has expired, after this it prodivdes a defualt response 

**Deep Dive side**

Due to the volume of votes we get, to maximise effecency, we check the users in a seperate script

Here we will check how often a user uses subs that commonly brigades us and compare it to there interaction within goodanimemes
I also factor in user infractions within goodanimemes 

**Web side**

This is currently bieng made by DJ, u/shitlordstu




<!--
**goodanimemes/goodanimemes** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
