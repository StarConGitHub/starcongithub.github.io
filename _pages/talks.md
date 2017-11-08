---
layout: page
title: Talks
permalink: /talks/
---

<div class="pretty-links">

# StarCon Talk Lineup

### Notworking with a Whale: A Tale of Dockers, Networks, and Problem Solving

[Fatema Boxwala](/speakers#fatema-boxwala)

<p class="abstract">
Docker has become an extremely popular tool in the tech industry. Docker containers can be found playing a hugely important role in the infrastructure of companies from the tiniest startup to the giantest of the giants. Despite it's ubiquity, much of the inner-workings of Docker remain shrouded in mystery for developers, even for some people that work with the application regularly.  And a lot of the times, the only way to figure out what's going on is by experimenting and testing yourself. One particularly confusing aspect of Docker, and linux containers in general, is how exactly the networking inside the container works. In my talk: Notworking with a Whale: A Tale of Dockers, Networks, and Problem Solving, I will be giving a short but practical introduction to networking inside Docker and linux containers. The audience will first be introduced to the idea of network namespaces inside linux systems, and how these apply to containers and Docker. They will then be exposed to tools that can be used to interact with and troubleshoot networking issues inside a container. I will introduce these tools by sharing my own, very frustrating, experience with networking and Docker, in a problem-strategy-solution narrative. My talk will present information that will teach listeners information about linux containers, and offer some personal strategies and tools that have worked well for me.
</p>


### Gloom, Doom, and the Internet

[Keefer Rourke](/speakers#keefer-rourke)

<p class="abstract">
Since the advent of the internet, technology has undergone a revolution like no other. It has enabled connectivity on a scale that has never been seen before, enabling free distribution of information, ideas, and independent content. However, in recent years we've seen a turn of events. What was once primarily a mechanism for free expression has given way to multitudes of surveillance machines designed to track your every move. In my talk ""Gloom, Doom, and the Internet,"" I will discuss some of the privacy and security issues with technology today, and explain how you can defend the users of your Next Big Thing(tm). Attendees will be encouraged to rethink how they view internet-enabled technology, with a focus on the importance of privacy, accessibility, and security oriented designs from day one, and they will be shown how new platforms can be made successful simply by respecting their users.
</p>

### Why I Prefer Good Testing Over Excellent Testing

[Tina Fletcher](/speakers#tina-fletcher)

<p class="abstract">
I often used to feel that if we only had more time for testing, we’d find all the bugs and everything would be awesome. But the longer I’ve been working on software projects, the more times I’ve seen that this might not be true. Most of the escaped defects in my recent memory were hiding in the areas I didn’t even know to ask about, in the small differences between our test and production environments, and in the things we depend on but don’t have full control over. So lately, while I will always value doing good testing, it doesn’t feel as useful to spend a lot of time striving for truly excellent coverage. Instead, I prefer to invest in planning for phased roll outs, and gaining confidence in our ability to quickly detect and resolve problems in production. I’d like to share a few stories about defects I missed that I wouldn’t have found with all the time in the world, and about times I have been saved by solid monitoring and roll-back strategies.
</p>

### Formal Methods for Everyone: Practical Tools for Computer-Aided Reasoning

[Murphy Berzish](/speakers#murphy-berzish)

<p class="abstract">
Do you want to write code you can be confident in, and test your programs thoroughly? Formal methods is a powerful discipline of software engineering that uses logic and automated reasoning to prove correctness of programs or find counterexamples to assertions.
<br/><br/>
In this talk, I will describe two useful open source tools that you can start using to help you write better code and find more bugs in your software. I will teach you about the Z3 theorem prover, from Microsoft Research, which can assist you in reasoning about logical formulas and finding test cases to catch bugs. Then, I will talk about the KLEE symbolic execution engine, which is an automated software testing tool that uses principles from formal methods to explore the effects that different inputs have on the flow of your program.
<br/><br/>
This talk will be very applied, with an emphasis on the practical rather than the theoretical. I want this talk, as well as these tools, to be accessible to anyone, even with no background in formal logic.
</p>

### How to make a real-time collaborative text editor in 5 easy steps!

[Rudi Chen](/speakers#rudi-chen)

<p class="abstract">
With the rise of cloud applications, more and more software is becoming collaborative. That is, multiple people can be viewing and editing the same document or information at the same time. This can lead to tricky issues figuring out what the end result should be when two users simultaneously do conflicting operations (e.g. in Google Docs, two users typing in the same place). The conflict-resolution algorithms so solve these problems are increasingly important, but selfdom mentioned in any curriculum. This talk will present a newer approach to build a collaborative text editor easier to understand than common techniques found on the Internet. The technique will be presented one small layer of complexity at the time, such that at every step, the audience can get an intuition for the nature of the solution and be easily be convinced that it works. I’ll also make sure to un-dry the technical aspects talk by using humor and analogies to kiwis and water buffalos.
</p>


### I'm a scientist!

[Omayeli Arenyeka](/speakers#omayeli-arenyeka)

<p class="abstract">
In the 6th grade we were taught the Scientific method. We would ask a question, form a hypothesis, conduct an experiment and then analyze the results and come up with a conclusion. The results, if unambiguous, proved us right or wrong. After I took my last science class in high school, I stopped conducting experiments. If I got curious about something or had a question, I would do research. However, some of the questions I had couldn’t be answered by googling or buying a book. 2 years ago I discovered how I could be a “scientist” without literally being one. In my talk, “I’m a scientist!” I’m going to talk about answering our own questions through data exploration and visualization. I will take the audience through one of my visualization projects at each step of the scientific method. They will be introduced to methods of obtaining data, techniques for data analysis and a brief introduction to data visualization. I believe that everyone should be able to analyze and do basic visualizations of data so we don’t always rely on outside sources (which often are biased) to make conclusions about the world we live in.
</p>


### Dealing with Bad Architecture Decisions: A Case Study

[Claire Janke](/speakers#claire-janke)

<p class="abstract">
Have you ever worked on a project for several months, only to realize right before the end date that there’s a fundamental flaw in your approach? In this talk I’ll tell the story of how our team built a new data management system which started as a fairly straightforward Elasticsearch index but then at the last minute evolved into a Frankenstein-esque database + search index hybrid that is still in use today. I'll also point out where it all went wrong to hopefully help others avoid the same mistakes in the future.
</p>



### Why Lossless Data Compression Is Both Important and Fun

[Alex Rhatushnyak](/speakers#alex-rhatushnyak)

<p class="abstract">
Data compression is highly important for reducing storage costs and transmission times. More than 70% of global Internet traffic is video, and it's compressed video as a rule. Similarly, audio and images more often travel in compressed form. Lossless data compression (LDC) is an important part of a data compression system. Advanced LDC is an application of Data Science and Machine Learning, but basic LDC methods are so simple that you can implement them with zero or little knowledge of ML, DS and even Computer Science. The audience of my talk "Why Lossless Data Compression Is Both Important and Fun" will be introduced to the topic and learn several of the most vital principles. LDC competitions and benchmarks will be pictured as well, with practical advices on how to win thousands of dollars in such competitions. LDC is closely related to the notions of descriptive complexity and entropy. LDC methods can be applied for estimating descriptive complexity, for measuring similarity between files, and so on. At the end of the talk a couple of next big things (supposedly related to descriptive complexity and LDC) will be briefly discussed.
</p>


### Imagining a world with Ethereum

[Anastasia Santasheva](/speakers#anastasia-santasheva)

<p class="abstract">
Cryptocurrencies such as Bitcoin, Ethereum, and others have recently gotten a lot of attention in the tech community and in news! This is a fascinating technology with a lot of potential, but many are just starting to see why! With this talk, I will get you excited and empowered by an understanding of cryptocurrency, particularly Ethereum.
<br/><br/>
To do this, first I will explore the motivations of cryptocurrency, or why people are interested in decentralized money and networks. I will briefly talk about the first 'fair' peer-to-peer decentralized network, Bitcoin, and what ideas it contributed to the cryptocurrency world. Then I will talk about how Ethereum differs from Bitcoin - I find that comparing the two helps understanding. I will highlight that:
- Bitcoin can be described as digital money
- Ethereum is different from Bitcoin because it allows for smart contracts, that is, highly programmable digital money.
<br/><br/>
This will set up the grounds to discuss the impact of three key ideas: 1) Ethereum smart contracts - money with logic, imagine automatically sending money from one person to another but only when a certain set of conditions are met. 2) Ethereum tokens - allow decentralized protocols to capture the value of the network. 3) Initial coin offerings (ICOs) for Ethereum tokens - like an IPO for a startup, with some differences. Then I will discuss how these concepts come together to form a new way to allocate and get compensated for the work people do and the resources they have, and why this decentralized system is very exciting to me!
</p>


### Taking the Fun Out of Everything: Automating Neopets

[Kelly McBride](/speakers#kelly-mcbride)

<p class="abstract">
Neopets is probably one of the Web 1.0’s greatest achievements. The fact that it was created during that time means that its original features rely on older technology that’s more commonly understood now, making it a prime target for automation at the hands of junior programmers. Neopets is a browser game about taking care of virtual pets. Fortunately, it’s comprised of php activities that you interact with by making HTTP requests - something that scripts are great at doing as well as browsers. In my talk, “Taking the Fun Out of Everything: Automating Neopets,” I’ll talk about collaborating with the ghosts of people with similar ideas by forking their abandoned repos, building on frameworks with the aim of applying more technical ideas later, and banging your head against the wall when “they could have just made the game do this.” I’ll close by mentioning some similar games that the audience can take the fun out of for themselves.
</p>
