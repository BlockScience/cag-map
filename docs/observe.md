# Observe

![](img/cag-map-0.0.3-observe.png)

> Picture of the Observe section (with pictures and colors) goes here. This can prime the reader for the next section and might also help to break up an otherwise monotonous wall of text.

## Overview

Adding technology to something you don't understand is not a good idea. It is guaranteed to make things worse. Disruption without direction is just chaos. If you want to improve a system, first seek to understand how it works. Then, once you have an informed opinion, you can engage productively.

Hopefully this process will help you draft better proposals, but it will also help when analyzing systems and proposals. The most important thing is to look for evidence and facts that back statements up. If a statement is made without any supporting evidence it might just be an opinion. Both facts and opinions can be helpful as long as you can differentiate between the two. Facts are true regardless of whether or not you believe in them, but opinions are only relevant as long as people believe in them. People will often state opinions confidently and definitively as if they're facts. People will also question facts in order to better understand their provenance and application within context. This can be confusing. A scientific approach is skeptical of processes and data because they want to find out what's true or not, but media and politicians are full of conviction and emotion because they want to find out what will capture your attention (and votes). This creates cognitive dissonance. Data driven processes are logically sound, but emotionally unsatisfying. Narrative driven processes are often impossible to prove or disprove logically, but they are emotionally exciting and compelling.

The dichotomy between logic and emotion is unlikely to be resolved anytime soon. That being said, knowing the difference between facts and opinions can help establish a ground truth. Then at least we can have a few shared factual reference points to build our intersubjective narratives off of. 

## Concepts (How)

### Stakeholder Analysis

[Stakeholder analysis](https://en.wikipedia.org/wiki/Stakeholder_analysis) explores who is part of the decision making process as well as who would be affect by a decision. In other words, who holds a stake in the outcome?

A few questions you might ask yourself to start to think about stakeholders are:

- Who has input to decisions?
- Who is affected by those decisions?
- What are the incentives of various stakeholders?
- Are incentives aligned? If not, where might there be conflict?
- Have there been any conflicts between stakeholders in the past that might recur in the future?

You don't need to have concrete answers to all of these questions right away, but they can help you build intuition about the political feasibility of any future proposals you might think of.

### Resource Management

Here [resources](https://en.wikipedia.org/wiki/Resource) refers to the thing that is being governed. Stakeholders engage in governance because they care about the management of shared resources. If they had complete control over the resource they wouldn't need to engage in governance. They could just make the decision themselves. The fact that governance is required means that resources are shared.

There are many types of resources. Some are tangible and some are intangible. Some are renewable and some are non-renewable. The type of governance process will often be correlated to the type of resource. For example, corporate governance works great for stocks, but less so for public goods. At the same time, democratic governance might be good for shared infrastructure, but less ideal for an early stage startup that needs to move fast and decisevely. One size does not fit all. The stakeholders involved and resources being shared will impact how well various types of governance might work. Understanding the types of resources that are valuable to stakeholders can help build intuition on what type of govnernace structure might be best and how to engage productively in that governance process. What types of governance structures are best for what types of resources is beyond the scope of this guide, but it's important to think about. At least make sure you're not assuming a governance process will work just because it worked for a different system in a different context.

Another thing to watch for is if there are intangible resources that are not formally accounted for in the governance process, but are important to stakeholders and a determining factor in their decision making. This is also outside the scope of this guide, but it's very important. Resources = value. Most formal processes account for tangible measurable forms of (or proxies for) value. That being said, there are often many intangible forms of value that affect decision making. One way to address this is to avoid formalizing governance and to rely on [rough consensus](https://en.wikipedia.org/wiki/Rough_consensus), using human [sensemaking](https://en.wikipedia.org/wiki/Sensemaking) to process information and drive decision making. This addresses the problem of dealing with intangible data, but creates a new problem of opaque power structures and the [tyrany of structurelessness](https://www.jofreeman.com/joreen/tyranny.htm). The balance between human subjectivity, objective rules, and tangible vs intangible value remains an unsolved challenge. That being said, being aware of these dynamics is the first step. This is also why computer *aided* governance focuses on having humans in the loop. That way you can balance objective rules with subjective human judgement.

A few questions you might ask yourself to start to think about the resources being managed:

- What are the tangible resources that are being created and/or managed by the system?
- Are there intangible resources that are also in play, and if so, how do those relate to the tangible resources?
- Are these resources renewable or non-renewable?
- Are all of the resources being managed taken into account by the governance system?
- Are there resources that are not formally considered in the governance process, but still impact the process (this often involves cultural norms, knowledge, etc..)?

### Governance Process

[Governance](https://en.wikipedia.org/wiki/Governance) is an important and vague word. It can mean a lot of things to a lot of people in an lot of contexts. Here when we say "governance," we're referring to the process of making decisions. This includes the [constitutional](https://en.wikipedia.org/wiki/Constitutional_economics) rules that constrain the power and actions available to various actors within a system as well as the [political](https://en.wikipedia.org/wiki/Politics) process that actors can engage in to change rules.

A few questions you might ask yourself to build intuition around how governance within the context of a complex socio-economic system:

- Is the governance process explicit (set rules and procedures) or implicit (rough consensus)?
- What is the process for stakeholders to advocate for their interests and collectively make decisions (aka what is the political process)?
- What is the process to make changes to the way changes are made (aka can you change constitutional rules)?
- Is there a history of stakeholders engaging in the political process to change rules or to change how rules are changed?
- What is the average speed at which changes happen? Ex: does something take a week or a year to discuss and put to a vote?

## Tools

### White Paper

A [white paper](https://en.wikipedia.org/wiki/White_paper) is a report or guide that informs readers concisely about a complex issue and presents the issuing body's philosophy on the matter. It is meant to help readers understand an issue, solve a problem, or make a decision. This will often explain the motivation, goals, and general design of a system.

Be aware that the white paper is not the system itself. It's a sketch of the system. To understand how the system works in practice you need to read the documentation and/or source code for a specific implementation.

### Docs

[Documentation](https://en.wikipedia.org/wiki/Documentation) is any communicable material that is used to describe, explain or instruct regarding some attributes of an object, system or procedure, such as its parts, assembly, installation, maintenance and use. This will be much more specific than the white paper. It should provide the information you need to use, contribute to, or integrate with a system.

Often documentation is incomplete or outdated. This is often due to the bandwidth constraints of the development team. That being said, software that is easy to understand and contribute to is likely to have less bugs. It's also more likely that stakeholders will be able to engage in governance productively if they understand how the system works. Documentation can help with both.

### Source Code

The [source code](https://en.wikipedia.org/wiki/Source_code) is the actual code that implements a system/protocol. There are various definitions of open-source and/or free software. Paraphrasing from the [GNU Foundation definition of free software](https://www.gnu.org/philosophy/free-sw.en.html), it is:

- free to use
- free to inspect
- free to modify
- free to distribute

Even if you can't read the code yourself, you can at least check that the software implementation of a system is free and open-source. This does not guarantee that it is bug free, but it does increase the probability that users who can read the code will find bugs sooner than later. This also puts more power in the hands of users. Anyone can fork the software if they disagree with a change, somewhat reducing the likelihood of contentious changes happening in the first place. 

### System maps and models

Complex systems will often use maps and models to communicate how they work. A map or model is not the system itself, but a representation of the system. They choose to exclude some information to focus on others. This way you don't have to understand every detail to understand the key points of how the system works. Many maps and models are interactive so that you can explore the system in more depth than a static document.

### Activity

Digital systems do things, and the things the do are often measured. If so, then having access to system activity can help you understand what the system is doing and if it's doing it well. For blockchain based token systems the data is on-chain and cryptographically verifiable. For server based digital systems the there may be a data you can plug into or the company running a service might publish statistics, but you have to trust the source of the data as it often has no cryptographic verifiability.

### Independent research reports

Looking at primary sources is often recommended as the first step to understanding a system. That being said, the information produced by a team building or maintaining a system might be biased (even if they're doing their best to be objective). Independent analysis is likely to also be biased, but potentially in a different way. Multiple perspectives will give you more data to help you form your own opinions about a system.

### Community Chat/Forum

Beyond looking at technical specifications or external research, you can sometimes engage with system users directly. Many open source software projects have community chats or forums where people can ask questions and share information. Be aware that accounts on forums are often not verified to see if they actually use the product/project. In addition, the team building/maintaining a product/project might also moderate content or censor information available on official community channels. Community feedback and information can be helpful to build intuition, but, as always, take everything you read with a grain of salt.

