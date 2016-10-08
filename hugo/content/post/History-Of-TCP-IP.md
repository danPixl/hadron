+++
date = "2016-10-07T21:56:31-06:00"
title = "The history of TCP/IP"
thumbnail = "images/introducinghedron.jpg"
+++

TCP/IP is essential to the internet as we know it today. Whether your talking to your friends or watching cat videos, all of it is made possible by it. So, why was TCP/IP developed? 

#### ARPANET

In the 60's, the ARPANET was created by the US Department of Defense for scientests to share mainframes, big, (relatively) powerful computers. You can probably guess that only letting one scientest do one thing at a time was inefficient. Of course, other people in other countries had similar ideas. When computers started getting connected, we needed a system to help manage communications. 

#### TCP

TCP was the only thing being used in the ARPANET. Someone named [Jon Postel](https://en.wikipedia.org/wiki/Jon_Postel) made a very important statement:

We are screwing up in our design of internet protocols by violating the principle of layering. Specifically we are trying to use TCP to do two things: serve as a host level end to end protocol, and to serve as an internet packaging and routing protocol. These two things should be provided in a layered and modular way. I suggest that a new distinct internetwork protocol is needed, and that TCP be used strictly as a host level end to end protocol.

What Jon was stating is that the version of TCP at that time was trying to do too much, specifically that it shouldn't be handling both transport and netork layer activities. And it was! We know today that if we kept using just TCP, we would have large problems down the road. That observation led to TCP/IP.

#### TCP/IP

It's the 70's, and ARPANET communications were generally hard to work on due to only using TCP, rather than pairing it with something else to create a layered system. TCP/IP was developed to solve this problem by [Vinton G. Cerf](https://en.wikipedia.org/wiki/Vint_Cerf) and [Robert E. Kahn](https://en.wikipedia.org/wiki/Bob_Kahn). With the nice side effect of other countries adopting TCP/IP, the advent of [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol), and computers becoming small enough to fit in homes, the Internet was born.
