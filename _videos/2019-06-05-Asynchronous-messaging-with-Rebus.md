---
title: Azure Operations Security
youtube_id: 26w_GaiuxQs
date: 2019-06-05
category: meetup,dev
tags: [messaging,async,rebus]
---

Presented 05/06/2019 at the dotnet.Amsterdam meetup.

https://www.meetup.com/dotnet-amsterdam/events/261490238/

---

Asynchronous messaging with Rebus

There is a fairly widespread consensus, that the cool architecture for larger projects is not monolithic. Likewise, it seems most software development teams buy in to the idea, that the Bounded Context concept from Domain-Driven Design is the way to go when deciding on how to slice up the cake.

But how are your services/autonomous components/microservices/whatever-you-call-them supposed to communicate, then?

For synchronous request/response, we have HTTP, which by now has become ubiquitous – but the landscape is more varied when we need to figure out how to handle the asynchronous part of the communication.

Rebus (https://github.com/rebus-org/Rebus) is a .NET-based implementation of several asynchronous messaging patterns, which can abstract message queues and persistence mechanisms away, thus making it easier and less painful to implement the asynchronous part of an architecture. This is what we are going to talk about :)

Bio:

Mogens (https://twitter.com/mookid8000) is the owner of Rebus.FM (https://rebus.fm), the commercial complement to the open source (and completely free) .NET service bus implementation, Rebus, which he happens to be the author of.

He likes to use contemporary databases and vintage architecture principles to build distributed systems in enterprise environments, which he has done for more than 10 years now, primarily within the financial and commodity trading domains.

As a member of the core committee of "Aarhus .NET User Group" (https://www.meetup.com/anugdk/) he helps with setting up interesting meet-ups that target more than 1000 members. He is a former Microsoft MVP within the "VS & Dev Tech" Department, but Microsoft didn't think he did enough for open source, so they took that away again. He kept the blue stickers, though!

In addition to that, he likes beer a lot, so he founded The Alley Beer Company with the intention of brewing the first really good craft beer of his hometown, Horsens.