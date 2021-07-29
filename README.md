# Cuetian Coders
A community for cuetian coders to grow together with maximum problem solving capacity and efficiency in shortest possible time.

## Philosophy
There's a philosophy behind this community which is described below:

- Not wasting anybody's time
- Providing a dynamic way to learn and share and help each other
- Create confidence in innerself and learn to respect each other
- Grow together


## A Framework for interaction
A `discord` channel is being used to interact with each other. The goal is to learn, help and share. To achieve each of them a framework has been proposed.

### Architecture of the framework

- The basic building block of the framework is an abstraction, we call it `topic`. Some examples of topics are `c++`, `microservices`, `system-design`, `competitive-programming`, `machine-learning`, `interview-prep`, `job-circular` etc.

- Each topic is divided into necessary components, such as `resources`, `announcements` etc. Note: it's possible that a topic may not be divided into any components.

- Topics are grouped together based on their cohesive nature to be discussed together, an exmaple could be `c++`, `python`, `java`, `haskell`, `lisp` all are programming languages. So, we categorize them into `Programming Languages` category.


### Implementing the framework using discord
Discord has several features those helped us implement the desired framework most flexibly. Here, I've described how we can achieve the framework that we want to implement. But first we must familiar with some simple discord features.

#### Discord features
- **Category:** Category helps to organize channel
- **Channel:** Channel is used for discussion/conversation. There're 2 types of channel:
  - text channel
  - voice channel
- **Thread:** From a conversation inside a `text channel`, we can create thread. Two types of thread
  - active: it helps maintain active conversations
  - archived: it helps maintain inactive conversations
[Note: An archived channel can be revived later by sending a message, which will be used to keep `resources` channel always active.]


#### Mapping the framework into discord features
We use `channel` for `each topic` and use `active(long lived) thread` to maintain `components(such as "resources")` of a topic. And the `category feature` is used to bundle relative topics into a `category`.

The following picture will help it clear for you:
- Programming languages [category -> category]
  - c++ [topic -> channel]
    - resources [component -> thread(active)]
    - announcements [component -> thread(24hrs, then archived)]
    - small conversation on pointer [smalltalk -> thread(shortlived, 1hr, archived)]
  - java [category -> category]
    - resources [component -> thread(active)]
    - announcements [component -> thread(24hrs, then archived)]
  - python
    - resources [component -> thread(active)]
    - announcements [component -> thread(24hrs, then archived)]

- Web Framework [category -> category]
  - Ruby on Rails [topic -> channel]
    - resources [component -> thread(active)]
    - announcements [component -> thread(24hrs, then archived)]
    - small conversation on templating [smalltalk -> thread(shortlived, 1hr, archived)]
  - Django [category -> category]
    - resources [component -> thread(active)]
    - announcements [component -> thread(24hrs, then archived)]
  - Express.js
    - resources [component -> thread(active)]
    - announcements [component -> thread(24hrs, then archived)]

- Software Engineering [category -> category]
  - Microservices [topic -> channel]
    - resources [component -> thread(active)]
    - announcements [component -> thread(24hrs, then archived)]
    - small conversation on service discovery [smalltalk -> thread(shortlived, 1hr, archived)]
  - Clean Code [category -> category]
    - resources [component -> thread(active)]
    - announcements [component -> thread(24hrs, then archived)]
  - System Design
    - resources [component -> thread(active)]
    - announcements [component -> thread(24hrs, then archived)]


## How to get the most out of the community
We've also sum up the ways that how the community users can get the most out of the interaction framework. The interaction style is setup in a way that it helps in both centralized and distributive learning style.

### The ways of interaction:

- Stay focused
  - Learn and share only a few topics at a time
  - Don't get distracted by new buzzwords/jargons
- Share what you're learning everyday regardless of what other's are doing
  - Don't stop sharing
  - Don't wait for others
  - Don't be confused about sharing, just share it.
- Ask questions and share problems
  - Never hesitate to ask for help
  - Even when nobody helps/gives replies, just ask it. May be later at somepoint, you'll be able to answer your own questions and thus, help others.
- Always Help
  - If you can, then helps others directly by:
    - answering questions
    - solving problems
  - If you can, then help others indirectly by:
    - help by pointing to right direction
    - by tagging a person/persons who can help

### How the above ways of interaction helps
- **Finding out people of same interest:** The above approach helps finding out people of same interest, cause they will be sharing/asking questions in the same topic channel, thus will be able to help each other out.

- **Expert-Beginner interaction:** No matter what we say, we're always a beginner in something. Maybe one person is beginner in `machine-learning`, but very good in `system-design`, but another person very good at `machine-learning` but no good in `system-design`, they can help each other out in respective fields.


## The final advice
Just do it. Never stop, never sit idle. Always act/interact/react.
