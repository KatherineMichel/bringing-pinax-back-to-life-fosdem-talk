# Bringing Pinax Back to Life- FOSDEM

## Table of Contents

- [About](#about)
- [Slides and Script Table of Contents](#slides-and-script-table-of-contents)
- [Slides and Script](#slides-and-script)   
- [Attribution](#attribution)
- [Contact Kati](#contact-kati)
- [Copyright](#copyright)

<hr>

## About

Slides and script for a pre-recorded talk Katherine "Kati" Michel ([Twitter](https://twitter.com/KatiMichel), [GitHub](https://github.com/KatherineMichel)) gave at FOSDEM [Python DevRoom](https://fosdem.org/2021/schedule/track/python/), broadcast Sunday, February 7, 2021 at 6 am CST/1 pm Brussels, Belgium time.
 
Talk Page
* "[Bringing Pinax Back to Life](https://fosdem.org/2021/schedule/event/python_pinax/)"

Slide Deck
* [Original slide deck](https://docs.google.com/presentation/d/1hzs64yiH0J2gjtDLyzQPUTEViO4xAFcGn6_nAXVfXlY/edit?usp=sharing)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Slides and Script Table of Contents

- [Bringing Pinax Back to Life](#bringing-pinax-back-to-life)
- [About Me](#about-me)
- [In Summary](#in-summary)
- [Time Machine](#time-machine)
- [Time Machine: 2003](#time-machine-2003)
- [Time Machine: 2005](#time-machine-2005)
- [Time Machine: 2007](#time-machine-2007)
- [Time Machine: 2008](#time-machine-2008)
- [Re-Inventing the Wheel](#re-inventing-the-wheel)
- [Fast Forward: 2017](#fast-forward-2017)
- [The State of Pinax](#the-state-of-pinax)
- [How It Began](#how-it-began)
- [How It Was Going, 80 Project and Apps](#how-it-was-going-80-project-and-apps)
- [How It Was Going, GitHub Organization, Global Docs, and Slack](#how-it-was-going-github-organization-global-docs-and-slack)
- [How It Was Going, Sustainability Lacking](#how-it-was-going-sustainability-lacking)
- [Challenge and Opportunity](#challenge-and-opportunity)
- [Critical Problems](#critical-problems)
- [Solutions](#solutions)
- [Beginner Mindset](#beginner-mindset)
- [Simplified, Self-Service, and Self-Sustaining](#simplified-self-service-and-self-sustaining)
- [Setting the Wheels in Motion](#setting-the-wheels-in-motion)
- [Tribal Knowledge](#tribal-knowledge)
- [GitHub Open Source Survey](#github-open-source-survey)
- [Pinax Documentation](#pinax-documentation)
- [Documentation](#documentation)
- [One Source of Docs](#one-source-of-docs)
- [Variations in Configurations](#variations-in-configurations)
- [One Configuration Approach](#one-configuration-approach)
- [Reduce the Backlog](#reduce-the-backlog)
- [Engagement with Individuals](#engagement-with-individuals)
- [Communicate Better](#communicate-better)
- [Engagement with Community](#engagement-with-community)
- [Automation](#automation)
- [How It's Going](#how-its-going)
- [Biggest Lesson Learned](#biggest-lesson-learned)
- [Additional Ideas](#additional-ideas)
- [Thank You](#thank-you)
- [Q and A](#q-and-a)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Slides and Script

The script is a general outline and varies somewhat from what was said during the talk.

<table>

<tr><td width="30%">

![Slide 1](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_0.jpg)

</td><td>

### Bringing Pinax Back to Life

* Hi everyone
* It’s great to be here
* My name is Katherine Michel. I also go by Kati
* My talk is called “Bringing Pinax Back to Life”

</td></tr>


<table>

<tr><td width="30%">

![Slide 2](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_1.jpg)

</td><td>

### About Me 

* A little bit about me
* I’m currently working on a project for the Wharton School at the University of Pennsylvania
* The project is called Simpl… it’s an open-source Python/Django/React game simulation framework 
* Pinax Maintainer/Web Developer
* DEFNA (Django Events Foundation North America) Board Member 
* At DEFNA we oversee the high level details of DjangoCon US and Django outreach across North America
* DjangoCon US Website Co-Chair

</td></tr>


<table>

<tr><td width="30%">

![Slide 3](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_2.jpg)

</td><td>

### In Summary

* My talk is about Pinax
* Pinax is an open-source library of reusable Django starter projects, apps, and themes for building websites. When developers began building Pinax in 2007, they had fun adding to it, but eventually Pinax had grown to be around 80 projects and apps. 
* There was not a strategy in place to make Pinax as easy as possible to maintain. So the maintainers began to suffer burnout. 
* I was hired to work on Pinax in the fall of 2017. In my talk, I'll outline the critical problems I discovered and the solutions I've implemented to make Pinax healthier and easier to maintain so that maintainers can get more done and contributors can be more easily onboarded. 

</td></tr>


<table>

<tr><td width="30%">

![Slide 4](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_3.jpg)

</td><td>

### Time Machine

* To better understand this story, we need to go back in time to 2003

</td></tr>


<table>

<tr><td width="30%">

![Slide 5](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_4.jpg)

</td><td>

### Time Machine: 2003

* Pinax is built with Django, a Python web development framework
* The Django web development framework was created at the Lawrence Journal World, in Lawrence Kansas, in 2003
* I was actually living in Lawrence at the time
* Unfortunately, I didn’t know anything about Django
* I would even sometimes drive by the Lawrence Journal World building, where it was created
* I didn’t even know Django existed

</td></tr>


<table>

<tr><td width="30%">

![Slide 6](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_5.jpg)

</td><td>

### Time Machine: 2005

* Django was open-sourced in 2005
* If you go to the Django repo on GitHub and choose the dot 90.x branch 
* You can actually go back and see those initial commits
* People began to get excited about Django and a community began to form around it

</td></tr>


<table>

<tr><td width="30%">

![Slide 7](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_6.jpg)

</td><td>

### Time Machine: 2007

* At PyCon 2007 in Dallas, some members of the Django community formed a group called the “Hotclub of France” 
* That name came from Django Rheinhart’s band
* Django Rheinhart was a jazz musician whose name had been the inspiration for Django web framework’s name
* The members of this new “Hotclub of France” would go on to create the Pinax ecosystem

</td></tr>


<table>

<tr><td width="30%">

![Slide 8](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_7.jpg)

</td><td>

### Time Machine: 2008

* In March, at PyCon US in Chicago, “Hotclub of France” members met again and began to discuss the Pinax idea and began sprinting on it
* They had found themselves reusing some of the same code patterns while building websites with Django
* So they began to abstract these patterns into reusable Django starter projects, apps, and themes
* On Memorial Day weekend in that year, they spent the weekend hacking on Pinax
* In September, the first ever DjangoCon US took place, timed to coincide with the release of Django 1.0
* James Tauber, one of the original Pinax authors, gave a talk about Pinax there
* In the talk, he explained the goal of Pinax and the progress made in building it
* He talked about the reputation of Python and Django for reducing the time from idea to realization of the idea
* He also talked about the philosophy of reusability in Python/Django that had led to a huge ecosystem of reusable packages

</td></tr>


<table>

<tr><td width="30%">

![Slide 9](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_8.jpg)

</td><td>

### Re-Inventing the Wheel

* The “Hotclub of France” members had created Pinax to solve their own problem
* In his talk, James said, “Re-inventing the wheel makes a lot of sense if your goal is to understand wheels better”
* The members of the “Hotclub of France” were web technologists, but also website creators
* As web technologists, they wanted to create a reusable web development library on top of Django that would make choices and compromises
* This reusable web development library would enable them, as website creators, to focus on the features at the top of the stack
* That way, they could go from website idea to realization quickly, instead of re-inventing the wheel

</td></tr>


<table>

<tr><td width="30%">

![Slide 10](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_9.jpg)

</td><td>

### Fast Forward: 2017

* Let’s fast forward to 2017
* It had been around 10 years since the Pinax idea had been born
* In the meantime, I had moved to England, gotten interested in tech, and been awarded a Master’s Degree
* And it was only then, in another country, that I learned about Django
* Even though it had been created in Lawrence, where I had previously lived
* I had become a DjangoCon Organizer and DjangoCon Website Chair and Maintainer
* I’d created a talk about being a maintainer and had given it at DjangoCon US
* In the fall of 2017, based on this experience, I was hired to work on Pinax

</td></tr>


<table>

<tr><td width="30%">

![Slide 11](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_10.jpg)

</td><td>

### The State of Pinax

* So what was the state of Pinax by now?
* It’s quite common, from the very beginning until now, for people to discover Pinax and say “it’s everything they ever dreamed of”
* On this slide is one of the very early tweets about Pinax… someone says “Pinax is every idea I’ve ever had.”

</td></tr>


<table>

<tr><td width="30%">

![Slide 12](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_11.jpg)

</td><td>

### How It Began

* In his DjangoCon US 2008 talk in 2008, James talked about his own site Quisition
* Even though it was a flashcard site, much of its functionality had nothing to do with flashcards
* The “Hotclub of France” had begun to abstract this type of functionality into reusable Pinax apps
* The Pinax community had begun to self-organize and incubate these apps
* This included a Twitter clone and all sorts of other functionality, much of it the kind you might find in social media sites

</td></tr>


<table>

<tr><td width="30%">

![Slide 13](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_12.jpg)

</td><td>

### How It Was Going, 80 Project and Apps

* By 2017, Pinax had grown to be a large group of professionally-quality, interdependent Django projects and apps
* This included starter projects with Pinax apps pre-installed and a command line interface to install them
* This also includes sophisticated testing, packaging, and continuous integration configurations
* The Pinax GitHub organization alone has around 80 repos in it
* This slide includes many of the more popular ones

</td></tr>


<table>

<tr><td width="30%">

![Slide 14](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_13.jpg)

</td><td>

### How It Was Going, GitHub Organization, Global Docs, and Slack

* In addition to the GitHub organization
* Pinax now had a global docs site and a Pinax Slack channel for community and support
* There were also app-specific docs in individual repos

</td></tr>


<table>

<tr><td width="30%">

![Slide 15](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_14.jpg)

</td><td>

### How It Was Going, Sustainability Lacking

* But… sustainability was lacking
* By now, many of the original authors had moved on
* Without a strategy in place to make Pinax as easy as possible to maintain, the maintainers began to suffer burnout. 

</td></tr>


<table>

<tr><td width="30%">

![Slide 16](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_15.jpg)

</td><td>

### Challenge and Opportunity

* It may sound like I’m criticizing Pinax and the people who created it, but… 
* Pinax is amazing
* The people who authored it are super-smart, highly-skilled people
* They were passionate about it and had fun working on it
* Pinax has offered a real solution to a problem
* It had been used to more quickly and easily build many successful business, non-profit, and hobbyist websites
* Many Pinax authors have also been Django core devs and the Django core project has some of the same challenges
* The Pinax authors have been very generous with their code and their time and effort; they have made really important contributions to the community
* I’m personally grateful to have found a project like this to work on
* I think it can be better to be faced with a problem that greatly challenges you than one that is boring
* In general, by having the freedom to grapple with Pinax, I’ve been able to develop professionally and improve Pinax in the process
* I’ve also been take what I’ve learned from Pinax and immediately understand other open source situations better
* And apply the lessons I’ve learned from Pinax to projects of any size

</td></tr>


<table>

<tr><td width="30%">

![Slide 17](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_16.jpg)

</td><td>

### Critical Problems

* These are the critical problems I found, which I’m going to go into greater detail about one by one
* Tribal knowledge
* Existing documentation difficult to find, duplicated, and inconsistent
* Variation in configurations
* Lack of engagement with individuals
* Lack of engagement with the community
* Tasks being done manually that could be automated

</td></tr>


<table>

<tr><td width="30%">

![Slide 18](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_17.jpg)

</td><td>

### Solutions

* Document the tribal knowledge
* Make one source of documentation, make it extremely easy to find, and use
* Choose one configuration approach and implement across projects
* Reduce the backlog of existing issues and PRs and catch up on engaging with current issues and PRs
* Write more blog posts about plans and progress, and publicize well
* Automate more tasks

</td></tr>


<table>

<tr><td width="30%">

![Slide 19](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_18.jpg)

</td><td>

### Beginner Mindset

* I had a valuable perspective as a newcomer to Pinax
* There has been a disconnect between their very high skill level of the authors and the beginner mindset that newcomers may have
* This is where I was able to begin to fill the gap
* It was said to me when I was hired that some of the authors knew so much that they couldn’t go back down to a beginner level anymore

</td></tr>


<table>

<tr><td width="30%">

![Slide 20](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_19.jpg)

</td><td>

### Simplified, Self-Service, and Self-Sustaining

* The goal in general was to work to make things simpler and self-service
* As a result, newcomers, contributors, and maintainers could help themselves
* And therefore, create a culture that could sustain itself

</td></tr>


<table>

<tr><td width="30%">

![Slide 21](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_20.jpg)

</td><td>

### Setting the Wheels in Motion

* Initially, I had a mentor. He led a release and I contributed work toward it
* But eventually, I was working on my own
* I began working on docs… I realized I needed to go back to the code
* When I think about this time, I think about machinery and wheels beginning to grind into motion
* For a long time, I was toiling away in obscurity

</td></tr>


<table>

<tr><td width="30%">

![Slide 22](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_21.jpg)

</td><td>

### Tribal Knowledge

* Problem: Tribal knowledge
* Solution: Document the tribal knowledge
* The Pinax authors knew how to do things quickly, but the knowledge remained in their heads
* In fairness, they were often busy and working quickly to meet deadlines
* But… the barrier of entry knowledge-wise was fairly high and the docs were sparse and not beginner friendly

</td></tr>


<table>

<tr><td width="30%">

![Slide 23](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_22.jpg)

</td><td>

### GitHub Open Source Survey

* GitHub did an open source survey in 2017 and they found that documentation is...
* Highly valued
* Often overlooked
* And a means for establishing inclusive and accessible communities

</td></tr>


<table>

<tr><td width="30%">

![Slide 24](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_23.jpg)

</td><td>

### Pinax Documentation

* For a while, my time was spent just figuring out how things had been done
* Then I began to document it… 
* I started by creating a release plan that explained the “Pinax way of doing things”
* Then moved on to creating a global community health file repo filled with default files
* This included a Code of Conduct
* A community plan
* Contributing and support information
* Information for Maintainers
* And issue and PR templates

</td></tr>


<table>

<tr><td width="30%">

![Slide 25](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_24.jpg)

</td><td>

### Documentation

* Problem: Existing docs difficult to find, duplicated, and inconsistent
* Solution: One source of documentation, easy to find, and use
* There was some documentation already in existence
* But it had been created ad hoc over the years
* There were bits of documentation here and there, some forgotten, some private

</td></tr>


<table>

<tr><td width="30%">

![Slide 26](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_25.jpg)

</td><td>

### One Source of Docs

* Pinax has a wiki
* I organized these historical docs, links, and new release plans in a Pinax wiki
* Then a blurb was added to the repo READMEs to make all of the docs more discoverable
* Including the global docs, wiki, community health files, app specific docs, tagged and published releases, and support, contributing, and release docs
* This goes back to the DRY (Don’t repeat yourself principle)... one source of truth

</td></tr>


<table>

<tr><td width="30%">

![Slide 27](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_26.jpg)

</td><td>

### Variations in Configurations

* Problem: Variation in configurations
* Solution: Choose one configuration approach and implement across projects
* A number of people had created and worked on different Pinax projects at different times
* Because of this, there was a lot of variation in terms of how things had been done
* I can tell you from personal experience that as a newcomer, this made the code collectively harder to understand and more difficult to maintain

</td></tr>


<table>

<tr><td width="30%">

![Slide 28](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_27.jpg)

</td><td>

### One Configuration Approach

* After some research, I chose one configuration approach and implemented it across repos 
* I also detailed it in the release plan
* The more consistent the GitHub organization is, the better

</td></tr>


<table>

<tr><td width="30%">

![Slide 29](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_28.jpg)

</td><td>

### Reduce the Backlog

* Problem: Lack of engagement with individuals
* Solution: Reduce backlog of issues and PRs and catch up with engagement

</td></tr>


<table>

<tr><td width="30%">

![Slide 30](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_29.jpg)

</td><td>

### Engagement with Individuals

* Between releases
* Over 160 issues closed
* Over 100 PRs merged
* Over 30 PRs closed
* Countless questions answered in issues and Slack
* This was quite difficult at times, because many of the issues and PRs were the more difficult ones left outstanding
* I began with resolving the lowest hanging fruit issues and PRs knowledge-wise and working my way up
* The idea was to reduce the number until the new and existing issues and PRs would be more manageable

</td></tr>


<table>

<tr><td width="30%">

![Slide 31](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_30.jpg)

</td><td>

### Communicate Better

* Lack of engagement with the community
* Write more blog posts about plans and progress, and publicize well

</td></tr>


<table>

<tr><td width="30%">

![Slide 32](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_31.jpg)

</td><td>

### Engagement with Community

* I began to write blog posts and tweet about them
* The posts might be about Pinax, or some other Django-related activity and I would mention Pinax
* People began to become interested in Pinax, telling me that they had heard about Pinax through my writing
* It makes people aware of the project and gives them social proof that it’s actively being maintained
* It can have a huge benefit to stop and take time to write about the accomplishments and progress of the project and sharing it with the community 
* Even if a handful, or even one person, becomes interested and contributes, it can make a major impact

</td></tr>


<table>

<tr><td width="30%">

![Slide 33](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_32.jpg)

</td><td>

### Automation

* Problem: Tasks being done manually
* Solution: Automate tasks
* Automating tasks lowers the risk of burnout

</td></tr>


<table>

<tr><td width="30%">

![Slide 34](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_33.jpg)

</td><td>

### How It’s Going

* Pinax is a work in progress and has a lot of room still for improvement
* Automation is still lacking
* I had the best of intentions to implement automation in the latest release, such as auto-publish to PyPI upon tagging a release, but it didn’t happen
* It was one thing too many
* The global documentation is also in need of improvement, among other things

</td></tr>


<table>

<tr><td width="30%">

![Slide 35](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_34.jpg)

</td><td>

### Biggest Lesson Learned

* In July 2020, based on what I had learned,I oversaw the completion of an important Pinax release. 
Around 28 apps were included and we notably dropped support for Python 2.7
* It was a huge milestone for me, personally and professionally. Not only did I initiate the release, but I managed the end-to-end process. I created the release plan, oversaw the work of others, updated 10 apps myself, merged all of the PRs, and tagged and published the packages. 
* The biggest lesson I’ve learned while working on Pinax is that the latest release succeeded because of my communication and teaching skills
* I learned this by accident
* My blog posts attracted contributors
* The release could not have been completed without the help of these contributors… it would have been too much work and required specialized skill
* The release documentation I had written enabled the contributors to help, to mutual benefit
* I was thrilled that they were able to use this documentation to complete a large portion of the work, with occasional support from me

</td></tr>


<table>

<tr><td width="30%">

![Slide 36](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_35.jpg)

</td><td>

### Additional Ideas

* If you want more ideas, I recommend checking out the GitHub docs for the latest features available
* A few additional ideas:
* For automation: GitHub Actions, GitHub Apps, Probot (you can do things like welcoming contributors, auto merging PRs, auto-closing issues)
* For workflow: protect branches, status checks, required review
* For reducing scope: archive repos, mark repos as deprecated, disable issues
* To bring on additional maintainers: you can give selective permissions
* Productivity: there also productivity tips and notifications management

</td></tr>


<table>

<tr><td width="30%">

![Slide 37](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_36.jpg)

</td><td>

### Thank You

* Twitter: KatiMichel
* GitHub: KatherineMichel
* Email: kthrnmichel@gmail.com

</td></tr>


<table>

<tr><td width="30%">

![Slide 38](https://speakerd.s3.amazonaws.com/presentations/75b3f1c3afcf43778751293b43bcc3c0/slide_37.jpg)

</td><td>

### Q and A

* I am now ready to take questions in the Q & A

</td></tr>

</table>

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Attribution

The style of this transcript is heavily inspired by:

* Ana Balica's ([Twitter](https://twitter.com/anabalica), [GitHub](https://github.com/ana-balica)) transcript of her [Humanizing among coders](https://ana-balica.github.io/2017/05/28/humanizing-among-coders/) keynote for [PyCon CZ 2016](https://cz.pycon.org/2016). 
* Honza Javorek's ([Twitter](https://twitter.com/honzajavorek), [GitHub](https://github.com/honzajavorek)) transcript of Anna Ossowski's ([Twitter](https://twitter.com/OssAnna16), [GitHub](https://github.com/OssAnna16)) keynote [Be(Come) A Mentor! Help Others Succeed!](https://github.com/honzajavorek/become-mentor) for [PyCon CZ 2017](https://cz.pycon.org/2017/). 

Thank you!

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Contact Kati

* Email: kthrnmichel@gmail.com
* GitHub: https://github.com/KatherineMichel
* Twitter: https://twitter.com/KatiMichel

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Copyright

© 2021 to Present Katherine Michel. All Rights Reserved.
