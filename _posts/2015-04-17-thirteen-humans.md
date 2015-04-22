---
title: Thirteen humans
layout: post
author: Scott Forman
image: scott.png
---

Here at OneRoom we've been scrambling for the last few weeks to get ready for our first for-real classes, which we're conducting in partnership with [Hugo House](http://hugohouse.org/) in Seattle. ([Anca's class](http://hugohouse.org/store/class/intro-to-fiction-writing-the-short-story-anca-szilagyi/) is full but there are still a few spots left in Bill Carty’s: [Intro to Poetry: Poems from the Everyday](http://hugohouse.org/store/class/intro-to-poetry-poems-from-the-everyday-bill-carty/)". Check it out! We think it’s going to be awesome).

As we prepare, we're dividing our time between building software features - things like registering for accounts, sharing and commenting on creative work, etc. - and testing and optimizing the live video experience itself - dealing with slow networks, troubleshooting connectivity problems. Generally plumbing the mysteries of [WebRTC](http://en.wikipedia.org/wiki/WebRTC). 

We reached an important milestone this week and we wanted to share our excitement about it: we did our first full-attendance realistic test of 13 people in one OneRoom room (kind of a mouthful, isn’t it?) together. It was a mix of us, and 7 obliging folks we found through Craigslist, all joining from home for more realistic internet connections. (Thanks for your help and thoughtful feedback, obliging Craigslist folks!). 

We were nervous. We weren't sure if it would work - this is the hard part. But guess what? It did! Of course, it wasn't perfect - but it basically held together. Here’s what it looked like:

![Craigslist test screenshot 1](/img/blog/craigslist-test-screenshot-1.png)

Some things that went well:

### Everyone got connected to everyone else. 

This might seem like a low bar, but trust me - it wasn't easy to achieve. There were several months where, in our simulations with "bots" - remote-controlled browsers with faked-out webcams streaming video of Bill Murray - we couldn't reliably get everyone connected.

### Everyone could see and hear reasonably well. 

One participant wrote, afterwards, that the video “overall was significantly better than most services I've used in terms of video quality, especially with 12 people as most services have pretty terrible video quality and lag”. 

### Our make-believe classroom exercises worked well and smoothly. 

We took turns reading paragraphs aloud from the first version of the Jack London story “To Build A Fire”, and read parts from a ridiculous dialogue for ESL practice we found called “3 people having lunch at a restaurant”, with snappy repartee like “Jane, could you pass the salt, please?” (spoiler alert: she passes the salt). 

### Interrupting is possible. 

We made a point of interrupting people as they were reading, to make sure the audio latency wouldn’t make that kind of fast back-and-forth impossible. It worked! Although I felt bad about interrupting, and had to reassure the guy who was reading that there wasn’t anything wrong with they way he said “Please pass the salt.” 

### Mode transitions work smoothly.

Acting as the teacher, I was able to transition between the different “modes”, which we call “Brady Bunch”, for open discussion, where the sizes of the videos are maximized, and “Workshop,” where a particular document is brought into focus for discussion. We think that arming teachers with the ability to do this kind of “stage management” is a subtle but important innovation. 

---

We also found a bunch of things we want to fix and improve: 

* The name badges and mute buttons obscured the faces in “Workshop” mode, when the video frames are small. It felt a bit like talking with a room full of people covering their faces with their hands - unsettling. We probably should have anticipated this, but it looked fine in the mockups. It’s the kind of thing you really only figure out by testing. 
* The “speaking indicators” were too subtle. We all noticed this. One of the participants wrote: “when the teacher would ask a general question sometimes there was no way of knowing who was talking unless that person pointed it out.” In general, as I’ll explain more in a future post, we try to take our cues from reality. There are no flashing lights over your head in a physical space to let everyone else know you’re talking. So I had hoped we wouldn’t need this in OneRoom, either. Turns out, we do.

We also gained some important insights about how to make this all work smoothly. It didn’t prevent me from fulfilling my role as the facilitator, but for me, for much of the time, it looked like this: 

![Craigslist test screenshot 2](/img/blog/craigslist-test-screenshot-2.png)

The red “x’s” mean “we can’t show you video for this person right now.” I could still hear them, I just couldn’t see them. 

A few months ago, there wouldn’t have been much we could do to figure out why this happened. But since then, we’ve developed some very useful instruments. 

Looking at the data afterwards, we’re confident that it was a problem of computer resources. I was using a mid-2011 MacBook Air, and it just didn’t have enough computational power to render all that video. Probably because I had too many tabs in Chrome, and a bunch of other programs open. So we have some new entries in the handbook for users - quit programs, close browser tabs, don’t watch Game of Thrones or mine Bitcoin in the background.

Overall, this was a lot of fun and very encouraging, and gave us a boost of confidence that the system will work for our first classes, and for many more teachers and students in the coming months. I was looking at some old screenshots today, and we’ve come a long way since this: 

![Early screenshot](/img/blog/early-screenshot.png)

We still have a lot of work to do between now and the 29th, though, so I’m going to get back to it. 

Have a great day. 
