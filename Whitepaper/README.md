Co(re)creation: designing the next civic hack
---

/ dribdat collective // v.2.4 /// 1.2022


This paper describes **dribdat**: an open source tool for hackathons and other time-limited sprints and workshops. In a simple user interface, it allows managing challenges, resources, bootstraps, while augmenting diversity and fair conditions. Learn how we use it to track teams and their progress, collect relevant design notes, documentation, data, and code, and enhance the experience of exploring civic tech problems together, hands-on.

This document is accessible at dribdat.cc/whitepaper

![](images/logo_3.png)

1. [Executive summary](#summary)
2. [Co-creation and collaboration](#collaboration)
3. [An open platform](#results)
4. [Reducing friction](#friction)
5. [Assuring interoperability](#interoperability)
6. [Being excellent to each other](#excellent)
7. [Not being all the things](#things)
8. [Always be closing](#closing)
9. [References](#references)

---
<a name="summary"></a>

# ➀ executive summary

Using dribdat, we develop and showcase projects at collaborative workshops, most commonly at hackathons: a popular event format for tinkering and innovation in small teams. Emerging from the civic tech movement, where open access to data and knowledge is applied to hold public institutions accountable, this was created as a tool for organisers and participants. We designed dribdat to ensure that people's contributions are verifiable, and that the executive summaries, or pitches, of our projects get published using modern web standards. This helps to make workshops more sustainable, and the knowledge gained in them to be more easily discoverable, readable, and reproducible.

Hackathons may be considered as a type of focus group, where platforms are evaluated, skills transferred, and horizontal insights accelerated by an open exchange of knowledge. This is an established venue to network, explore potential career paths while keenly evaluating prospective candidates or partners. Enabling better time management and coordination, such teamwork supported by dribdat should help to build a community of practice - lowering the barriers to entry for contributing creatively to NGOs, research, government, tech platforms and startups.

![](images/data_hackdays_be.png)

When citizens engage to hack on projects, such as monitoring the environment or validating public accounts, digital civil society initiatives emerge. The shared premise is that open source code and openly designed hardware can be used to rapidly prototype the real-world potential and impact of ideas or "challenges". Such events are then more than just a trendy way to find a job: they become venues for energetic collaboration, channelling civic engagement and technical experiments within an open, socialised setting. In contributing to such events, the participants engage to intensively generate data, take opportunities to be active for diverse causes in pragmatic ways. It is important that the platform they use reflects these purposes in its construction and philosophy.

With the experience of organising many meetings with wikis, cloud-editors, and other [awesome hackathon](https://github.com/dribdat/awesome-hackathon) tools, we are using dribdat today to streamline efforts across several civic tech communities. Compared to other hackathon applications, dribdat puts more emphasis on cooperation and impact-making than competition. Users can join and contribute to multiple projects, where every contribution counts: every bit of data, line of code, design sketch, is part of your overall contribution to the community. Further in this paper, you can learn why dribdat is an open platform, a gateway to other collaboration tools, and a learning instrument for digital co-creation.

The name of dribdat is inspired by *dribbling* in basketball and other sports, with a hat tip to [Dribbble](https://dribbble.com/), an online community for graphic design, and the [Dat protocol](https://datproject.org/) for peer-to-peer data sharing. In the following sections we dive deeper into what exactly makes dribdat tick.

![](images/commitlog.png)

_Graph of contributions to the dribdat code base, via GitHub_

---
<a name="collaboration"></a>

 # ➁ co-creation and collaboration
 
Designed to help participants and organisers to have a great time and focus on the essentials, dribdat features timekeeping and progress tracking dashboards to make it easier to form teams, sustain the energy in the room or online event,  and keep the focus on driving creative ideas forward.

The open source code of dribdat is accessible for free (under the MIT license), with instructions for self-hosting the platform anywhere that Python runs - which is, basically, anywhere. We are making it easier to deploy on popular platforms using package management and containers. With a running application, you can set up your first hackathon. Future events can run on the same site.

On the front page you can see the featured upcoming event, as well as any future and past events. A short description is followed by a link to the event home page, as well as a second-by-second countdown of time remaining until the start or the finish line (once started). *Projects*, *Challenges* and *Resources* are shown in the event screen. Here you can learn about topics, find datasets, get schedules or directions, and any other vital information that the organisers have provided.

Before the event begins it is possible to *Share a challenge*, which can be organised by *Category*. People who are interested in it can approach the initiator in person, via contact channels, or just *Follow* the challenge. Once the event has started, you can form a team by clicking the *Join* button, taking over a challenge and boosting it, or selecting *Start project* to begin afresh when open challenges are permitted. The dribdat dashboard helps to keep track of remaining time for your all your registered teams.

Challenges, and the projects that result from them, feature a large embedded frame at the top which can be connected to any Web-based tool. These are typically used to place a form for collecting data, a prototyping tool for iterating on designs, a data science notebook, or slide presentation. 

Only one tool can be in focus at a time, keeping participants on board as their projects pass through stages. When setting up an event, it is possible to recommend and preset a range of tools, making it easy to guide all your teams through a process of collecting ideas, refining designs, etc. This is something that we have found particularly helpful in a classroom setting. We hope that dribdat can also boost your sessions, by making the most of co-creation with the right toolbox. Join our community to share tips and workflows.

![](images/start_event.png)

---
<a name="results"></a>

# ③ an open platform

Web technologies and open data standards are at the core of dribdat. Typically, hackathons need some kind of publishing workflow that collects data from the team in a series of forms. We have often encountered this to be a laborious process that steals valuable time from teams and organisers while introducing bias and latency. Project aggregation is facilitated by the ability to start a project on the basis of data from a coding platform, a chat channel, or an open web resource.

In practice, the teams using dribdat are free to work as they please: keeping up with every twist and turn in the online collaboration landscape, we try to nurture supportive communities sharing the best brainstorming, prototyping and code sharing tools, helping to ensure we can plug in and generate data from any preferred platforms.

Ideators who would like to get help with their challenge-writing or research can easily connect this with dribdat. Just embed your favorite cloud wiki or document editor and set open permissions. We are fans of [CodiMD / HackMD](https://github.com/hackmdio/codimd) which can be used to embed a collaborative document with commenting functionality, that can easily be turned into a pitch deck.

Designers can use their favorite prototyping tools, either uploading screenshots or sketches into the Pitch area, or - if they are web-accessible - embedding the tool directly into the top area of the project. For example, we have seen successful co-creation happen around an embedded [Excalidraw](https://excalidraw.com/) canvas or [Miro](https://miro.com/app/) board.

No 'copypasta' needed here, coders! Projects created in a compatible repository - such as [GitHub](http://github.com/), [GitLab](http://gitlab.com/),[Bitbucket](http://bitbucket.com/) - or supported wikis, such as [Etherpad](http://etherpad.org/), [DokuWiki](https://www.dokuwiki.org/), [Google Docs](https://www.google.com/docs/about/), ... - can be synchronised so that documentation can take place, and *continue to happen in a distributed way*, using standard formats, such as the *README* files preferred in open source.

![](images/swihack_2.png)\
Swiss BroadcastingCorporation / [#swihack 2020](https://swihack.ch/)

This set-up both teaches your participants about key concepts of how publishing and integration on the Internet works today, and promotes a Web of Data approach to the collaboration setting. The less friction there is between one tool and the next, the more effectively and flexibly our teams can iterate their designs. With dribdat we can visualize and put into practice the data streams connecting our platforms. Where there are hitches and barriers along the way, the open community around dribdat is well positioned to investigate and suggest improvements.

**💡** Users may also use short Twitter-like posts with [Markdown](https://en.wikipedia.org/wiki/Markdown) formatting, assisted by a rich text editor, to document their project, and we are working on simpler, more direct ways to capture insight into participant activity. This includes [dridbot](https://github.com/hackathons-ftw/dridbot#dridbot), a chat-mode integration (for example for Slack or RocketChat) that allows updating projects directly within a team channel.

![](images/openfarming_1.jpg)\
Opendata.ch / [Open Farming Hackdays 2021](https://hack.farming.opendata.ch/event/1)

---
<a name="friction"></a>

# ④ reducing friction

Project presentations and demos made easily and efficiently available for evaluation when each team can update their own progress level, generating an automatic metric for profile completeness and activity levels, and giving each project a meaningful progress score.

Participants can subscribe to a challenge or join a project once someone has started it, and immediately gain access to improving the content. Their public profile gets linked to the project, and their activities -- posted messages (also known as "dribs"), progress reports, code commits, etc. -- can all be tracked alongside those of their team-members in the project's log. Only be engaging in this way can their team climb through the normalizing progress stages of the event.

![](images/tips_posting.png)

We are working to build dribdat into a powerful tool for tracking performance and recognising contribution -- for example, by supporting real-time collaboration in [CodiMD](https://github.com/hackmdio/codimd) and [Jupyter](https://jupyter.org/) notebooks embedded directly in the project, to minimise the friction of on-boarding contributors.

The data exports, APIs, and dashboards of dribdat allow organisers to at a glance see how all their teams rank both during and after the event. Fundamental to this is the experience of the hackathon participant, their ability to represent their team, to be aware of what's happening in the wider event, document their efforts, and present the results on time.

This kind of tooling has potential to be used in a variety of formats - from Agile Scrum sprints, to Design Thinking workshops and Rapid Prototyping: everywhere that time is of the essence, and a scrappy, "can-do" attitude reflective of the hacker ethic encourages better results, while enabling more venues for civic hacking and open data sharing. 

**💡** We support several ways of extracting real-time statistics for insight on the pulse of the hackathon, pointing to improvements and providing motivational data-points as content. Check the admin dashboard for links and documentation.

![](images/energydata_1.png)\
Opendata.ch / [Energy Data Hackdays 2020](https://hack.opendata.ch/project/463)

---
<a name="interoperability"></a>

# ⑤ assuring interoperability

Not just a metaphor: dribdat aims to be a digital glue between a plethora of tools and processes that are being deployed in the civic tech community, enabling quick and painless deployment - ideal for hackathons, but a need that is common throughout the IT and public sector. Tools like dribdat are important instruments in facilitating concentrated social change-making that is digitally sustainable.

Baked into the core of dribdat is support for Frictionless Data, the "open-source toolkit that brings simplicity and gracefulness to the data experience" ([frictionlessdata.io](https://frictionlessdata.io/)) which we use to accelerate the process of unpacking and exploring open information sources in the crucial early research & experimentation phases of a hackathon.

We have created and promoted an open schema for publishing event results: `hackathon.json` - a simple, readable text file at the root of any dribdat instance. Along with Data Package export, and compliance for [Schema.org](https://schema.org/Hackathon) and [Open Graph](https://ogp.me/) standards, we strive to ensure that our publications are picked up by search crawlers and easily federated.

For event organizers, the backend allows quick browsing and export of project data: in document form for evaluation by jury, or in `CSV` or `JSON` formats for external workflow. Spammy or invalid entries can be easily hidden or cleaned up. With `OAuth` support, user profile administration can go through an external, enterprise-scale provider such as GitHub or Slack. 

**💡** We can generally support integration with any kind of data platform or collaboration tool through embedding or APIs. We can work with event management software, even other hackathon platforms, if you need to mix and match features: dribdat is intended to be part of an ecosystem of compatible Internet tools.

![](images/inspired_by_data.png)\
Forum Helveticum / [Plurilingualism Hackathon 2018](https://hack.opendata.ch/event/22)

---
<a name="excellent"></a>

# ⑥ being excellent to each other

The dribdat initiative is grounded in the tradition of creative and ethical hacking. We have combined best practices in using wikis, issue tracking, and content management systems, creating the basic framework of the application at a hackathon in 2015. Since then, we have battle-tested it at many events with thousands of people - and the people have spoken to us about what they want from the experience.

In the first years of service, dribdat has supported dozens of events around Switzerland, becoming the official hackathon platform of [Opendata.ch](https://opendata.ch) - Swiss chapter of Open Knowledge and its working groups, the [Open Network Infrastructure Association](https://opennetworkinfrastructure.org/), [DINAcon](https://dinacon.ch) - the largest annual Swiss conference for digital sustainability, [DayOne](https://dayone.swiss) - an association that runs patient-centric hackathons, and other pioneers listed in the Showcase futher on.

One of the most important areas of feedback from our participants has been to understand what information should be made as visible as possible, to benefit our users despite the time pressure: these are a clear and readable Code of Conduct, Terms of Participation, and starter guides. Right out of the box, dribdat comes with support for the [Hack Code of Conduct](https://hackcodeofconduct.org/) and [Creative Commons](http://creativecommons.org/) licenses. 

![](images/disclaimer.png)\
The standard footer deployed with a dribdat instance.

Independently developed at the grassroots, behind the scenes of this project are compacted qualities of what we believe entails good collaboration: a supportive atmosphere that proliferates diversity and tolerance, clearly stated goals, community support and progressive guidelines. Inclusive co-creation  with better design and algorithms is an area of active development, currently the focus of research collaborations, upcoming publications, and development proposals.

**💡** We have built in a 7-step process inspired by the [School of Data Pipeline](https://schoolofdata.org/methodology/), that we recommend for attractive and efficient data expeditions and hackathons. Around these it is possible to set up a Resource area with recommended tools, datasets, or brainstorming instruments, and all the content can be customized to fit other patterns and methods.

![](images/makezurich_1.jpg)\
Open Network Infrastructure Association / [MakeZurich](https://makezurich.ch/)

---
<a name="things"></a>

# ⑦ not being all the things

This is a niche product with unique features and clear limitations. While you will find a variety of enhancements being worked on in our Issue Tracker, here are a couple of major areas where we are lagging. Visit [awesome-hackathons](https://github.com/dribdat/awesome-hackathon) for links to similar products that you may wish to consider for your needs, and our [Open Collective](https://opencollective.com/dribdat) to discover a number of ways to support our project.

Dribdat has built-in user profiles, but minimal user management features. Collecting personally identifiable information is not the goal of the project: facilitating recognition in a privacy-protecting way is. We allow the use of an anonymous username and disposable e-mail address to log in, but strongly suggest using OAuth for authenticating users through an external provider like Slack, as pictured here:

![](images/slack_login.png)

We suggest encouraging users to create profiles in a community platform that you integrate with dribdat - such as the open source [Discourse](https://www.discourse.org/) forum software, or at least to connect their social media profiles. You could also recommend "CV builder" platforms (e.g. [Stack Overflow](https://stackoverflow.blog/2016/10/11/bye-bye-bullets-the-stack-overflow-developer-story-is-the-new-technical-resume/)) to conveniently promote everyone's hackathon experiences. The ability to display participant accomplishments in an interesting way remains an area of improvement.

Currently dribdat does not include a form builder, though you are welcome to fork and make changes to the data schema in Python code. We have left the project structure open ended, allowing operators and teams to define how people can engage as contributors or testers. This is certainly part of the challenge of succeeding with promoting a hackathon idea, but also a major area of improvement to assist beginners and encourage active participation through questionnaires and templates. While it is possible to include this in the "Getting Started" guide shown to teams, we are working on designs for enhancing this, as we see many organisers set up separate online forms for registration, collecting feedback, or asking specific questions to the teams.

**💡** At some hackathons, like the [hacknight challenge](https://hacknight.dinacon.ch/project/10) pictured here, we follow an easy-moderate-advanced structure ("ski pistes") in their task descriptions. Other events set up a template which forces project teams to think about this issue.

![](images/start_tip.png)

While featuring a robust and mobile-ready user interface, the overall User Experience is currently underwhelming. Our project has not yet the benefit of a dedicated effort in UX engineering, and at the moment caters perhaps more to the needs of grassroots communities who prefer a simple, familiar interface. If it is to be desired that an application is more in the foreground and engaged with by users, check out the [backboard](https://github.com/dribdat/backboard) project which we started in response to requests for a smoother user interface for participants. It is based on a mobile-first client/server [architecture](https://github.com/dribdat/design/blob/master/Technical%20guide%20final.pdf), and as a custom app, allows completely flexible customization and branding.

In running hackathons, we are used to relying on a bunch of complementary tools. The organizing teams often use cloud tools, spreadsheets and calendars to make drafts and detailed plans. Clearly, the goal should not be to replace all of this with a new "[15th competing standard](https://xkcd.com/927/)". Integration with Web tools like wikis and docs is already at the core, so it's easy to make dribdat a part of the workflow. For example, we have run events where all the content is maintained in Google Docs and Google Calendar, and just imported automatically into dribdat.

At this time, commercial support is limited. The code base has developed organically using crowdsourced requirements. At time of writing, there is no broadly available Platform as a Service or a service provider running instances on demand. We believe there is a need for this and are taking steps in this direction. We are also involved in wider attempts to build scalable "operating systems" for hackathons. 

While setting up a small dribdat instance is easy and should be enough for a few teams to get started, the organizers of large events typically rely on more advanced support. Vendors who want to fully support dribdat should have experience with Python, OAuth and Web APIs, and be able to provide advice on how best to plug dribdat into your collaboration infrastructure and software architecture.

**💡** Visit the dribdat [Design repository](https://github.com/dribdat/design) to get supplementary documentation and wireframes of our designs. This is also where the Whitepaper you are reading now lives!

![](images/design_sketch.png)

----
<a name="closing"></a>

# ⑧ always be closing

The development of dribdat has so far involved significant efforts in code development, standardization, enterprise software integration, and even academic research. Alternative versions and new designs are being promoted through fully open platforms, and it is possible to follow and support the work through an [OpenCollective](https://opencollective.com/dribdat/).

A project rooted in open data standards and emerging technologies for open networks, dribdat can run as a cloud service, as an on-premises self-hosted solution, or even on a dedicated hardware device for ease of deployment. At the same time, we are committed to stay close to our roots: dribdat itself will always be hacky, experimental, and open to tinkerers around the world. A project like this is never "finished", and we are always on the look-out for fresh ideas that turn our world view upside-down.

The easiest way to try dribdat is to sign up for an upcoming event, and to use our platforms as participant. You can visit the home page to get links to example deployments, instructions on how to set up your own server and start your own events. If you need help or advice with any of this, or would like to contribute to the project in some way, please get in touch on our home page [dribdat.cc](https://dribdat.cc), or through any of these links below.

Thank you for reading! Your feedback is very welcome: the latest version of this document can be found on GitHub. Discussion threads are open in various community channels.

- Homepage: [dribdat.cc](https://datalets.ch/dribdat)
- Funding: [opencollective.com/dribdat](https://opencollective.com/dribdat)
- Blog: [opencollective.com/dribdat/updates](https://opencollective.com/dribdat/updates/)
- Twitter: [@dribdat](https://twitter.com/dribdat)
- Sources: [github.com/dribdat](https://github.com/dribdat)
- Bug tracker: [github.com/issues](https://github.com/dribdat/dribdat/issues)

### In a nutshell, dribdat...

-   ... has had [1'182 commits](https://www.openhub.net/p/dribdat/commits/summary) made by [9 contributors](https://www.openhub.net/p/dribdat/contributors/summary) representing [8'596 lines of code](https://www.openhub.net/p/dribdat/analyses/latest/languages_summary)
-   ... is [mostly written in Python](https://www.openhub.net/p/dribdat/analyses/latest/languages_summary) with [a low number of source code comments](https://www.openhub.net/p/dribdat/factoids#FactoidCommentsLow)
-   ... has [a well established, mature codebase](https://www.openhub.net/p/dribdat/factoids#FactoidAgeOld) maintained by [a small development team](https://www.openhub.net/p/dribdat/factoids#FactoidTeamSizeSmall) with [increasing Y-O-Y commits](https://www.openhub.net/p/dribdat/factoids#FactoidActivityIncreasing)
-   ... took an estimated [2](https://www.openhub.net/p/dribdat/estimated_cost) [years of effort](https://www.openhub.net/p/dribdat/estimated_cost) (COCOMO model) starting with its [first commit in September, 2015](https://www.openhub.net/p/dribdat/commits?sort=oldest)\
    ending with its [most recent commit](https://www.openhub.net/p/dribdat/commits) [1 day](https://www.openhub.net/p/dribdat/commits) ago.

*Generated at [openhub.net/p/dribdat](https://www.openhub.net/p/dribdat)*

---
<a name="references"></a>

# References

**2015 -- 2021**

On the following pages are reference deployments with background details. Visit our [OpenCollective](https://opencollective.com/dribdat/events) and Opendata.ch Forum for more.

![](images/dribdat_outline.png) 

---

![](images/energyhack_2.png)  

### Energy & Climate Hack

**User:** Swisspower, Opendata.ch

**Application:** https://hack.opendata.ch/event/36

**Discussion:** https://forum.opendata.ch/t/31-8-1-9-energy-climate-hack/783

**Integrations:** Slack, Google Drive, GitHub

---

![](images/covid19mon.jpg)

*The open data community at the front-lines of a digital response to the COVID-19 pandemic.*

### #covid19mon

**User**: Canton of Zürich

**Application:** <https://db.schoolofdata.ch/event/7>

**Discussion:** <https://forum.opendata.ch/t/18-3-1-year-of-covid19mon/757>

**Integrations:** Mattermost, GitHub

---

[![Now.Makezurich.ch](images/makezurich_2.jpg)](http://now.makezurich.ch/)

*An interest to accelerate hackathons using the Internet of Things is at the heart of dribdat.*

### MakeZurich

**User**: Open Network Infrastructure Association

**Application:** http://now.makezurich.ch/

**Discussion:** https://forum.schoolofdata.ch/t/22-30-6-makezurich-2018

**Integrations:** Slack, GitHub, The Things Network

---

![](images/foodopendata_grabfast.png)

*Since 2016, dribdat is the official platform of Opendata.ch Hackdays.*

### Open Data Hackdays

**User:** Opendata.ch - Swiss Chapter of Open Knowledge

**Application:** [http://hack.opendata.ch/](http://hack.opendata.ch/event/18)

**Discussion:** https://blog.datalets.ch/039/

**Integrations:** Datacentral, CKAN, Discourse, GitHub, Slack

---

![](images/ipdet_evalhack.png)

### Evaluation Hackathon

**User:** International Program for Development Evaluation Training

**Application:** https://evalhack.org/

**Discussion:** https://opencollective.com/dribdat/updates/a-season-of-hackathons

**Integrations:** Slack, Disqus, YouTube

---

![](images/swihack.png)

### Multilingual Media Hackathon

**User:** Swissinfo

**Application:** https://db.schoolofdata.ch/project/58

**Discussion:** https://blog.datalets.ch/065/

**Integrations:** CodiMD, GitHub, YouTube

---

[![Climathon Zürich](images/climathon.jpg)](https://hack.opendata.ch/event/4)

### Climathon Zurich

**User:** City of Zürich

**Application:** http://hack.opendata.ch/event/4

**Discussion:** https://blog.datalets.ch/023/

**Integrations:** Slack, Hubot (sodabot), GitHub

---

![](images/swisscom_iot.png)

*The first release of dribdat was designed in cooperation with Swisscom. Image courtesy of [Impact Hub Zürich](https://zurich.impacthub.ch/de/cross-sector-innovation/).*

### Internet of Things Hackathon

**User:** IoT Zürich Community

**Application:** https://datalets.ch/dribdat/iot-2015/

**Discussion:** https://blog.datalets.ch/an-internet-of-open-things-to-tell-stories/

**Integrations:** Slack, GitHub, Twitter, Instagram, Heroku, custom hardware

---

![](images/thumbs.png)

EOF