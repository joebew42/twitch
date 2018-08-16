---
layout: post
comments: true
title: 7 months of live coding
subtitle: What happened after 7 more months of live coding on Twitch? I tried to share some of my own considerations and feedback!
image: https://images.pexels.com/photos/1188214/pexels-photo-1188214.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260
bigimg: https://images.pexels.com/photos/1188214/pexels-photo-1188214.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260
---

# Lack of Daily Journals

Blame on me if I didn't have enough time and discipline to keep this journal constantly updated. The last post was written on the [9th of January]({{ site.baseurl }}{% post_url 2018-01-19-it-is-hard-but-it-is-also-satisfying %}), almost 7 months ago (What!?).

I know you can easily think _"no matter if you didn't wrote any post until now, go on"_. The problem I see here, since I am used to the practice of _"Daily Journal"_, is that if I don't write any post, I feel like I haven't done anything so far, I have no sense of progress (hey, this could be the next mood for the [Happy & Shitty coder](http://shittysomething.com/)...).

Trying to spend [one pomodoro](https://en.wikipedia.org/wiki/Pomodoro_Technique) at the end of each Live coding session to take notes about:

- What I have done today?
- What is missing to complete the coding session?
- What difficulties I found?
- What did I learn?
- Personal feedback about the session

It is of a great value to me because I can easily go back in time and look at the path I have made to get here. Now, without these information it is very difficult to write about the state of the art of the channel. Sigh!

So, I will try to summarize in this post my last 7 months on Twitch (good luck Joe), let's start!

# What I have done until today?

### On CodeStats.net

Contribute to [Code-Stats](https://codestats.net/). Worked on a feature in order to [expose an API for CSV data export](https://gitlab.com/code-stats/code-stats/merge_requests/50)! This was a great experience, I learned something new of Elixir, and of course, meet new people. And, ok, I win a face in [_contributors_](https://codestats.net/changes), I really appreciate and thanks again folks! Hope to back again on this project, soon!

### On Changelog.com

I met the community behind [Changelog.com](http://changelog.com). A lot of nice stuff there! The first issue I worked on was to [support the image upload by URL](https://github.com/thechangelog/changelog.com/pull/192). This was interesting because brings us to contribute to another open source project [arc_ecto: allow_urls feature](https://github.com/stavro/arc_ecto/pull/90), awesome!

The journey didn't finished here, I have been involved in other two contributions for Changelog:

- [Expose a JSON feed endpoint](https://github.com/thechangelog/changelog.com/pull/201) and,
- [Integration between the Admin UI and external Calendar service](https://github.com/thechangelog/changelog.com/pull/222).

I really liked this journey... A lot of new knowledge on [Phoenix](https://phoenixframework.org/), I met an [awesome community](http://changelog.slack.com), and I have to thank you [Jerod Santo](https://twitter.com/jerodsanto) for giving me all the support I needed, and hey, I had a shout during [one of their interviews](https://changelog.com/podcast/288) (at 1:16:40, woaaah!). And, I win a face in their [_contributors_](https://github.com/thechangelog/changelog.com#contributors) section!

Don't forget to check out the [Changelog.com Twitch Channel](https://www.twitch.tv/changelog_), also :)

### On Elixir/GraphQL

A learning journey about [GraphQL](https://graphql.org/learn/) and Elixir. We created a new [playground project](https://github.com/joebew42/elixir_absinthe_playground) and we tried to expose a [GraphQL API for an existing application](https://github.com/joebew42/elixir_bank_account)!

### On the new Twitch API

Another learning live coding session about _"How to create a client implementation for an API"_ brought us to create a _first_ [Elixir client implementation for the new Twitch API](https://github.com/joebew42/ex_twitch). The code is there and if you want to continue to play with it, you are welcome!

### On a Chat System and Websockets

We wanted to learn more about Elixir, Plug and Websockets and here we go, we started [this project](https://github.com/joebew42/ex_chat) as an example of Websocket usage in Elixir. Now, it is something more than an _"example"_, it is a fully working chat system, with users and rooms, and I hope to continue to work on it in one of the next live coding session. There are a plenty of interesting topics there to deal with, like data persistence and distributed application.

So, stay tuned because I am pretty sure we will come back on this project.

### On Wallaby

Another little contribution to an [open source project](https://github.com/keathley/wallaby) that is used to do _Browser testing_. I worked on a new feature that allows client to [lookup HTML element by their value or by their attribute and attribute value pair](https://github.com/keathley/wallaby/pull/384)! Here I have to say a big thank you to [Gena. M](https://twitter.com/gena_online) that gave me a lot of useful suggestion during the live coding session.

### But maybe there is more ...

... There is a high chance that we did more than this, but this is what I was able to build by taking a look at our [public feedback box](https://github.com/joebew42/twitch/issues). Basically it is the place to look at when do you want to propose a content for the next live coding session, or when do you want to leave a feedback about the channel.

If we try to look beyond the final artefact we have at the end of the process (a new playground project, a fresh new feature on a projects, a new contribution, or other), I think there is more here, and I think I understand that the value on doing a live coding session is to allow others to see what tools I tend to use and how I am used to use it. Tools like operating systems, window managers, shell configuration, editors (emacs, sublime text and visual code) and others!

I think that the whole process matters more than the final result. Here, I would like to read more from your feedback, write a comment if you want to add more about this topic!

# What difficulties I found?

I think the hardest part of doing Live coding session as a Twitch Streamer is in the commitment to maintain a straight schedule. I tend to go live at least three times a week (every mondays, wednesdays and fridays, 2 hours each). Being a Twitch Streamer is not my work, and it is not my main activity, I tend to go live after a work day, some times I feel tired.

I am thinking to try out new schedules, maybe on the weekend? I don't know yet ...

# What did I learn?

I think I learned two simple lessons about the world of the streaming, and here we go, I wanted to share it with you. _(as I said, I am not a professional streamer)_.

### Lesson #1: Only if you like!

Go live only if you think you will enjoy the streaming session. Don't force yourself to go live only because of the schedule, especially if doing streaming is not about making money for living. If you feel tired, think to postpone or cancel the session, some time is better to say NO.

**So, at the end, go live _only and only if_ you feel you will enjoy the session!**

### Lesson #2: Growing takes time!

_"I am a little brand new kid in town. I am not a professional Twitch Streamer, I am not a famous person. But I want to build a community."_

I think I learned this: If you want to build and grow a community around your Twitch Channel, you have to offer something of value for who is watching you. You are your Channel, and also, its contents. Choose a content where you think you have something to share with others and perform the stream around this. Ask for feedback and engage your viewers.

And, of course, because of the Rule#1, don't look at numbers (number of followers, numbers of live viewers, etc ...)

**You are the Channel, and you are the contents.**

# Feedback about these last 7 months

I really enjoyed this experience, I think also other developers should think to do live coding and show others how they are used to work, share their processes and their practices. I think the [live coding](https://www.twitch.tv/communities/programming) can be very helpful for who wants to learn more about computer programming, or contribute to the open source, and also an excellent opportunity to get a rapid feedback on what we are doing!

And of course, I think one of the best things there, is the opportunity to meet people from all over the world, build and grow a little community and continue to learn and share with others!

# What next?

As I announced during my last live coding session and also on [Discord](https://discord.gg/B7HS2AT) **I will be off-line for the next two or three months**, this means I hopefully will be on-line again on Twitch by the month of November or December. BTW, during this off-line period I will be available on the Discord channel, so you can easily reach me out there if you want to talk with me.

This period will be a _"renewal-opportuniy"_ for the Channel. I asked for feedback, and I think I will continue to do so in order to try to get our Twitch Channel better. We will try to spot issues and opportunities related on the schedule and the contents.

So folks, as always, I would like to say thanks to all, and I hope to come back soon on Twitch! See you on November or December ...

Stay tuned!
