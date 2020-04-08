---
title: History
sidebarDepth: 0
issueUrl: https://github.com/ipfs/website/issues/352
description: Learn about the history of IPFS, the InterPlanetary File System.
related:
  'Video: Juan Benet explains the IPFS alpha': https://www.youtube.com/watch?v=skMTdSEaCtA
  'IPFS draft whitepaper': https://ipfs.io/ipfs/QmR7GSQM93Cx5eAg6a6yRzNde1FQv7uL6X1o4k7zrJa3LX/ipfs.draft3.pdf
  'Video: Decentralizing the Web with the InterPlanetary File System (Epicenter Podcast)': https://www.youtube.com/watch?v=erB7i6Uc4DM
  "Article: It's time for the distributed web — September 2015 (Neocities)": https://blog.neocities.org/blog/2015/09/08/its-time-for-the-distributed-web.html
---

# History of the IPFS project

Like [Westeros](https://gameofthrones.fandom.com/wiki/Westeros), peer-to-peer (P2P) technology has experienced years-long winters and summers. There have been periods of great excitement and growth. Other times, P2P innovation has gone into hibernation.

Tim Berners-Lee first envisioned the World Wide Web with P2P concepts. The web did not evolve true to that vision. Centralized, client-server architectures dominate today’s web.

The [IPFS Project](https://github.com/ipfs/ipfs) aims to return the web to its P2P roots–making the web faster, safer, and more open.

## A P2P summer (1999~2003)

In 1999, Napster took the world by storm by offering unlimited, free music. Record labels weren't pivoting to a new business model (yet). Users could share media files freely because Napster's peer-to-peer network removed the barriers to doing so.

What followed was a period of great innovation in P2P technology. Exciting ideas and companies sprouted: Gnutella, Kazaa, MojoNation, BitTorrent, Skype, and many more.

Some of these projects appealed to hardcore technologists on ideological grounds. The ones that won mass markets did so on their merits. Like Napster, Skype and BitTorrent broke though because their P2P architectures enabled novel, valuable services.

This era ended partially under the weight of legal scrutiny. Much of the sharing done on P2P file-sharing systems was illegal. The resulting stigma suppressed P2P innovation, but competitive forces also played a role.

Client-server architectures lend themselves to centralized control and monetization. Centralized services aggregated more and more value on the web. Profits drove a flywheel of investment and hyper-scale growth for years to come.

This P2P summer proved that projects could win *with* their P2P architectures, not in spite of them. These projects demonstrated the possible. With time and technological progress, P2P would return to make an even bigger impact.

## The IPFS story

[Juan Benet](https://avatars0.githubusercontent.com/u/138401?s=400&v=4) was a child of this previous summer. He experienced the power of P2P networks first hand growing up. When he studied Computer Science at Stanford, he took special interest in distributed networks.

In 2013, Juan was working on a project aimed at a different passion–scientific innovation. Inspiration struck. The tools used for sharing and versioning large datasets were inefficient and error-prone. Worse, this type of human knowledge was too often centralized behind a paywall. With his background in software development and P2P systems, he knew there was a better way.

[Git](https://git-scm.com/) manages software versioning and collaboration through a data-linking structure known as a [Merkle tree](https://en.wikipedia.org/wiki/Merkle_tree). Git's data-linking structure is useful across many data types–not just code. Juan recognized that combining this concept with the P2P file-sharing structure of [BitTorrent](https://www.bittorrent.com/) would be powerful: functional, secure information sharing without centralized barriers. This could transform the world far beyond scientific datasets.

The IPFS project was born.

Juan went to work fleshing out his idea... Joined YC... Published the IPFS Whitepaper(https://ipfs.io/ipfs/QmR7GSQM93Cx5eAg6a6yRzNde1FQv7uL6X1o4k7zrJa3LX/ipfs.draft3.pdf)... Recruited a team... Started coding...

---

2014

* Theme = Laying Foundations
  * From Juan on [YC Podcast](https://blog.ycombinator.com/ipfs-coinlist-and-the-filecoin-ico-with-juan-benet-and-dalton-caldwell/): “Okay, great, it’s 2013, ’14, at the time. We have to go back and rewrite tons of normal peer-to-peer stuff that could have been written 10 years before, mostly because the language and tooling had changed, we wanted to do a few different things. We couldn’t reuse a whole bunch of the libraries that were out there, or the libraries made a whole bunch of assumptions about reality that were broken. Very famously, a lotta people, just from the engineering perspective, things like assuming that you are gonna be working on top of TCP and that the port that you have is a TCP port, and that it’s not UDP port or whatever, or even that you don’t have some other transport, right away can make a library completely unusable for a project years down the road.”
* May 2014 - Protocol Labs is founded to support fundamental research, development, and deployment of infrastructure for open networks (like the internet)
  * Modeled to be like an independent Bell Labs
* June 2014 - Protocol Labs enters the [Y Combinator Summer 2014 Class](https://www.ycombinator.com/companies/)
* June 2014 - [v3 Draft IPFS Whitepaper](https://github.com/ipfs/papers/raw/master/ipfs-cap2pfs/ipfs-p2p-file-system.pdf) is published
* Questions for an IPFS team member
  * When did the first contributors join Juan?
  * Did they start as PL employees or as open-source contributors?
    * https://github.com/whyrusleeping
    * https://github.com/daviddias
    * What drew them to IPFS and how did they discover it?
What were the most memorable challenges in “rewriting old p2p libraries?”
Can the required library changes be summarized in a theme (e.g. more modularity)?
What were the major assumptions that needed to be reworked?
After YC, what changed, if anything?
It appears that both the Go and JS implementations of IPFS were started in mid-2014.
Did the team explore both as potential initial releases? Was Go eventually prioritized by the core team?

2015

* Theme = Hello, World!
* February 2015 - Alpha release of go-ipfs
* September 2015 - Neocities becomes the first major site to [implement IPFS in production](https://blog.neocities.org/blog/2015/09/08/its-time-for-the-distributed-web.html)
* Questions for an IPFS team member
  * What were the lessons learned and immediate feedback from the alpha release?
  * What did the recruiting and onboarding of collaborators/power users of IPFS look like?
  * Were new users like Neocities contributing to the core with code or just feedback?
  * What did progress look like in alternative IPFS implementations?
  * Python appears to have been started in April 2015–community driven?
  * What was the release date of JS alpha implementation?

2016

* Theme = Modularization
* April 2016 - OpenBazzar integrating with IPFS (Source)
* June 2016 - libp2p becomes a spin-off project (based on Github initial commit)
* July 2016- Multiformats becomes a spin-off project (based on Github initial commit)
* October 2016 - IPLD becomes a spin-off project (based on Github initial commit)
* Questions for an IPFS team member
  * What went into the decisions to make libp2p, Multiformats, and IPLD separate projects?
  * Was this always the plan in time or were there specific events that drove the change? When?
  * What were the organizational changes made to support the split projects?
  * What did adoption and community engagement look like at this point?

2017

* Theme = Maturing technology?
* April 2017 - Snapshot of Turkish Wikipedia published to IPFS due to state censoring
* Questions for an IPFS team member
  * Did the ICO/crypto craze have a tangible effect on IPFS contributions and interest?
  * Are there any major technical initiatives started or delivered that I’m missing? Is it accurate to say that this was a time of focus on maturing the technology?

2018

* Theme = Maturing/growing team?
* Questions for an IPFS team member
  * Stories from the Rivendell house & team at this time?
  * What did the team structure look like at this point?
  * Did the success of the Filecoin ICO drive major changes/growth?
  * If not 2018, when did it feel like the small team leveled up to something else?
  * When did the management/coordination/recruiting of non-PL contributors become a "significant" effort?

2019

* Theme = Adoption
* Roadmap priority = Package Managers
* June 2019 - First IPFS Camp - Barcelona
* After IPFS Camp - Collaboration with Netflix
* x30 Network Growth!
* Questions for an IPFS team member
  * How was planning done before the 2019 Roadmap (I don’t see previous roadmap versions on Github)?
  * Was the single priority focus a lesson learned from previous years being spread too thin?
  * Stories, wins, or takeaways from IPFS camp?

2020

* Theme = Efficiency at Scale
* Roadmap priority = Content Routing
* Questions for an IPFS team member
  * What is the most exciting opportunity for IPFS growth/maturation this year?

## Stats dump (if available)

End of Year | IPFS Core Team | IPFS Contributors | IPFS Network
----------- | -------------- | ----------------- | ------------
2013 | 1 (Juan) | 0 | 0
2014 | | |
2015 | | |
2016 | | |
2017 | | |
2018 | | |
2019 | | |
