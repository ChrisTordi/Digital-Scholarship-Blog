---
layout: post
title:  "Ethics in Internet Infrastructure"
date:   2018-11-16 19:38:07 -0500
categories: [digital ethics, ethics, web development, ethical web design, content management systems]
author: Chris Padilla
---

This term was my first term working as the Digital Scholarship Ethics intern at Carleton. After learning the ropes, I was able to dive into research in fascinating and applicable fields. This term I learned how the web works, which was an important piece of groundwork for my research into digital ethics. As part of that research, I explored topics including web accessibility, personal/consumer data privacy, and large-scale algorithmic bias.

**Web Development**

My primary technical focus this term was to learn, broadly speaking, how websites work. I wanted to learn how a website is constructed and displayed in browsers, how it is accessed and used by the public, and what infrastructure is involved in hosting websites of various levels of complexity. After ten weeks, I can say that I have built four websites from the ground up: a database driven web application, a third-party hosted static site, a Drupal site, and a dynamic LAPP stack site. Through these projects, I feel as though I have gained a thorough understanding of the different methods and layers of web development, although there is always more to learn. I created the following diagrams to illustrate the technological processes behind what I perceive to be the [two prominent models][two-models] of web development.

*Dynamic Web Server*
![dynamic web server diagram]({{site.url}}/assets/Dynamic-Web-Server-Diagram.jpg)

*Static Site Generator*
![static site generator diagram]({{site.url}}/assets/Static-Site-Generator-Diagram.jpg)

**Digital Ethics**

My research into digital ethics this term focused on two primary areas: potentially unethical behavior unintentionally baked into popular software, and data privacy and ownership. As part of a project with the other interns, I conducted a survey of four popular content management systems, and attempted to establish standards for ethical comparison amongst them. We learned that depending on which aspect of ethics a particular organization focused on, their software would manifest itself with different advantages and disadvantages. For instance, WordPress, whose mission is to make web publishing available to as many people as possible, is incredibly widespread, and user-friendly. However, while there are options available to make Wordpress accessible and secure, it takes a more advanced user to implement these changes. As such, for a more novice user, Wordpress sites can be [more vulnerable to security breaches][security-breaches] and may not be as accessible out-of-the-box as Drupal. Drupal, on the other hand, whose focus is explicitly on high quality software, [routinely rolls out patches][routine-patches] to fix bugs and security vulnerabilities. Mukurtu is concerned with the ethical sharing and publicizing of heritage objects, and as a result, they have a very sophisticated permissions management system that regulates exactly which visitors to the site can view and edit particular items. The strengths of any software turn out to be directly related to the values and priorities of the organization that creates it.
The negative end of this spectrum is what happens when companies are most concerned with developing and distributing cutting-edge technology quickly. [Fake news being surfaced][fake-news] by the search algorithms of Google and Facebook, [algorithmic bias][algorithmic-bias] in machine learning, and [racist computer vision][racist-computer-vision] are all results of development teams rushing to deploy features without thinking deeply enough about the ethical potentials of their software.
Of at least equal concern to the ethical grey areas being coded into our software is the collection and use of personal data. This term I have researched the intersection between corporations, individuals, and governments. Some corporations view personal data as a kind of currency; Individuals view it, at best, as a bargaining chip that can be exchanged for convenience, and at worst, as an aspect of our lives that we are rapidly losing control over. Governments are playing catch-up, trying to understand the best approach to business regulation that both ensures a certain level of individual privacy (which also needs to be determined) and is actually enforceable. It is fascinating to read about this [conflict][conflict] playing out in real time, as corporations try to self-regulate, governments try to figure out what to do, and individuals are all over the place in their beliefs about what should be the standards for privacy and government regulation.

**Usability Conference**

The other interns and I all attended [World Usability Day][world-usability-day] on November 8th at the University of Minnesota. Presentation topics ranged from the fundamentals of accessible web design, to analyses of algorithmic bias, to the ethics of corporate data collection. It was my first time attending a conference of this kind, and it was a great experience. Many of the presentations and discussions motivated me to continue thinking and learning about the responsibilities corporations have (or should have) to their customers in terms of privacy, data protection, and social engineering. In addition to these questions about the future of our digital world, I also left the conference with a concrete set of guidelines for designing websites with accessibility in mind.
One thing that all of us interns noticed about the conference was the difference in style from a more academic conference, or a college course. The conference was much more industry focused than we were expecting, which rendered some of the information in the talks not very useful to us for the next few years. For example, one of the talks I attended was about how to conduct user testing in the most effective way. It was interesting to hear the ethical side of this discussion, (how to avoid abusing user data) but since I will not be conducting a focus group in the immediate future, that aspect of the talk was not very relevant to me. Knowing this about professional conferences will certainly help me in the future to decide which talks to attend at my next conference.

[two-models]: http://www.spiderwriting.co.uk/static-dynamic.php
[security-breaches]: https://torquemag.io/2017/08/top-5-wordpress-security-breaches-and-how-to-rectify-them/
[routine-patches]: https://www.drupal.org/core/release-cycle-overview
[fake-news]: https://www.theatlantic.com/technology/archive/2017/10/google-and-facebook-have-failed-us/541794/
[algorithmic-bias]: https://pdfs.semanticscholar.org/b722/7cbd34766655dea10d0437ab10df3a127396.pdf
[racist-computer-vision]: https://hackernoon.com/algorithms-arent-racist-your-skin-is-just-too-dark-4ed31a7304b8
[conflict]: https://www.ted.com/talks/finn_myrstad_how_tech_companies_deceive_you_into_giving_up_your_data_and_privacy
[world-usability-day]: https://it.umn.edu/events/world-usability-day-2018
