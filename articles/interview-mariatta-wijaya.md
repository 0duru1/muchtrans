---
title: Python Community Interview With Mariatta Wijaya
source-url: https://realpython.com/interview-mariatta-wijaya/
---

# Python Community Interview With Mariatta Wijaya

For this week’s community interview, I am joined by [Mariatta Wijaya](https://twitter.com/mariatta).
Mariatta is a web developer at Zapier. She also spends much of her time volunteering in the Python community: she is a core developer and contributes to conferences and Meetups.
If you ever have the pleasure of meeting her, then you can join her in an [\#icecreamselfie](https://mariatta.ca/category/icecreamselfie.html) or talk about her bots taking over GitHub. You can find Mariatta’s preferred contact links at the end of this interview.

### **Rickey:** Let’s start with an easy one. How’d you get into programming, and when did you start using Python?
**Mariatta:** I started around junior high school. We had extracurricular activities in my school, and one of them was “computer” class. At first, it was an introduction to MS-DOS and Windows. We were shown how to use WordStar and Lotus spreadsheets. (I’m really old.)
Later on, we got introduced to programming with QBASIC. Sometime later, I got introduced to “the world wide web,” and I started learning HTML and how to build web pages on my own. After I finished high school, I moved to Canada and studied computer science.
Before Python, I was a developer writing Windows and embedded apps, using the .NET Framework and C#. In 2008, I worked for a startup company working on a Windows project. When that project ended, they transferred me to a different team.
This team was working on web-based apps using Python, [Django](https://realpython.com/tutorials/django/), and [Google App Engine](https://realpython.com/python-web-applications/#google-app-engine). I didn’t want to be looking for another job at the time. So I stayed around, started picking up Python, and began a new career path as a web developer.

### **Rickey:** Most might know you for your work as a Python core developer. In fact, you did a talk at this year’s PyCon titled [What is a Python Core Developer?](https://www.youtube.com/watch?v=hhj7eb6TrtI) For those who haven’t seen your talk, what’s the TL;DR version, and what is your role as a core developer?
**Mariatta:** The TL;DR version is that becoming a Python core developer comes with a lot of responsibilities, and it goes beyond just writing more code into CPython. In fact, writing code is the least we expect out of core developers nowadays. As a core dev, you’ll be expected to do more code reviews, mentoring, providing feedback, and making decisions, instead of writing more PRs yourself.
The other point that I want to highlight is that we’re all volunteers. I am not employed by any corporation or [The PSF](https://www.python.org/psf-landing/) as a Python Core Developer. A lot of people still don’t realize this. Often, people write to the bug tracker as if they’re writing to customer support, expecting an immediate response, not taking no for an answer, and blaming us for various problems. Not only are we just volunteers doing this in our limited free time, but there are really very few of us compared the hundreds and thousands of users and contributors.
As a core dev myself, I’ve been focusing more on helping with the workflow, to make it easier for core devs and contributors to contribute and collaborate. I write utility tools and bots like [cherry_picker](https://pypi.org/project/cherry-picker/), [miss-islington](https://github.com/python/miss-islington), and recently the [check_python_cla](https://check-python-cla.herokuapp.com/) website.
I also focus on reviewing PRs from first-time contributors and documentation related issues. I like to make sure our devguide is up-to-date because that’s one of the first places we point contributors to when they have questions about our workflow.
I’m also doing weekly Python office hours now, over at Zulipchat. It is every **Thursday evening at 7 PM PST**. During that office hour, I’ll be available via DM, and I can respond and help in an almost real-time manner. During other times, I usually go to Zulip only once per day.

### **Rickey:** As if you didn’t already do enough for the community, you also co-organize the PyLadies Vancouver Meetup and the PyCascades conference. Can you tell us a little bit about how you got involved with those, and what people can expect if they’re looking to attend?
**Mariatta:** The story of how [PyCascades](https://2019.pycascades.com/) was founded was unclear, even to me. All I know is, one day I got an email from Seb, introducing me to the rest of the folks (Alan, Eric, Don, and Bryan), and it seems as if there’s an email thread that says, “Let’s do a Python conference in the Pacific-Northwest.”
I replied to it almost immediately. I didn’t think too much about what the responsibilities were going to be, or even how much work I’d have to put into it. I just thought, “Why not?” Within a couple weeks, we started scouting venues in Vancouver, and everything else just fell into place.
PyCascades is a one of a kind conference. We focus on highlighting first-time speakers and speakers from the Pacific-Northwest community. CFP for PyCascades 2019 is open from August 20 to the end of October. Please do submit a talk! I’m not involved in the program committee this year. Instead, I’m going to focus on mentoring speakers, especially first-time speakers and those from an underrepresented group.
I only started helping out with [PyLadies Vancouver](http://www.pyladies.com/locations/vancouver/) about two years ago. At the time, there were two organizers—and one of them had just stepped down—and they put up a call for more organizers. By then, even though I hadn’t been attending many Meetups, I’d benefited from PyLadies enough in the form of receiving financial aid for PyCon. So I just felt like it was an opportunity for me to pay it forward and give back to the community by also actively participating and ensuring the continuity of the Vancouver PyLadies community, instead of just waiting for the next Meetup to happen.
Our community has grown bigger now. I’ve looked back at our events over the past years, and we’ve put out so many great talks and workshops. We’ve had Python core developers and international PyCon speakers at our events. I’m quite proud of that!

### **Rickey:** Looking through your Github, I can see that you seem to have an affinity for bots. You maintain two for the Python core devs Github, but you have many more on your Github. I’m intrigued to find out what you find so alluring about them?
**Mariatta:** My first introduction to GitHub bots was when I started contributing to coala two years ago. They have a GitHub bot that is very much like a personal assistant to all the maintainers. The bot was always up and running, replying and commenting. At the time, I didn’t even realize that bots could do all of those things, so I was quite impressed and fascinated with how it all worked. I always thought the bot was a very complicated system.
As I started helping to create and maintain Python’s GitHub bots, I’ve gained a better understanding of the bot’s architecture, and I was able to satisfy my initial curiosity about how GitHub bots work.
But then I started thinking differently. Now that I know how they work, and I know what GitHub APIs are available, I keep asking myself, “What else can be automated? What else can I delegate to the bots? Have we really reached peak automation?” Turns out there are a whole lot of tasks that I can automate, and all I need is Python. And now that I know which tasks can be done by bots, I get grumpy when I have to do some of those chores myself.

### **Rickey:** I can’t have this interview with you without talking about ice cream selfies. It has become somewhat of a tradition of yours. There might be a few puzzled looks from our readers about now, so why don’t you explain all about the awesome [\#icecreamselfie](https://mariatta.ca/category/icecreamselfie.html)?
**Mariatta:** The first [\#icecreamselfie](https://mariatta.ca/category/icecreamselfie.html) I did was right after DjangoCon in Philadelphia, July 2016. I had just given my first ever conference talk, and I was feeling fabulous and just wanted to celebrate. Plus, it was a hot summer day. So I went to an ice cream shop near my hotel. Somehow, I just decided to take a selfie with the ice cream. It was actually unusual for me. Normally I just take pictures of the food, not a selfie.
My next talk was for PyCaribbean, in Puerto Rico. I wasn’t even planning for ice cream, we (myself and my roommate, and fellow speaker, Kim Crayton) were enjoying ourselves at the beach, and an ice cream cart showed up.
After that, I went to Italy for DjangoCon Europe and PyCon Italy. Of course, I had to have some gelato. No trip to Italy was going to be complete without it. Even at that point, I didn’t think of the #icecreamselfie as a tradition. The selfies have been more of a coincidence.
But after my talk at PyCon US, which was a pretty emotional talk, all I could think about was that I needed to go for ice cream. So my friend Jeff took me to this place he knew in Portland. And I felt really good after that ice cream! From then on, the #icecreamselfie became an official tradition for myself, and I go to great lengths researching the best ice cream right after I get a talk accepted.

### **Rickey:** And now for my last question: what other hobbies and interests do you have, aside from Python? Any you’d like to share and/or plug?
**Mariatta:** I like doing nature walks, traveling, and going camping. I have a strange hobby of taking pictures of my food, and I post them to Instagram. My other favorite pastime is playing Mahjong. Not Mahjong solitaire (a matching game), but Hong Kong style Mahjong. I still have trouble finding people who’d play this game with me.
If people are looking for ways to support me, please do send me a [happiness packet](https://www.happinesspackets.io/), support me on [Patreon](https://www.patreon.com/Mariatta), or [just say thanks](https://saythanks.io/to/Mariatta).

----

Thank you Mariatta for the interview. You can find [Mariatta on Twitter](https://twitter.com/mariatta) or her on [her website](https://mariatta.ca/) if you would like to know more about her.