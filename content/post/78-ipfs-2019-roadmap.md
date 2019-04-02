---
date: 2019-04-04
url: 78-ipfs-2019-roadmap
title: IPFS 2019 Roadmap
author: Molly Mackinlay
---

In Q4 2018, we undertook a new planning process for the IPFS project to more clearly define our vision, goals, and plans for the year. Our motivation was to improve coordination between our expanding working groups and to focus our efforts for the year on some larger-scale improvements to the IPFS network around scalability, performance, and usability to unlock the next tiers of adoption and usage. 

To ground our thinking about the next year, we first had to zoom out to the core mission and goals for the IPFS project in the long-term. We take on many efforts and support many others in our open source community, but it is all driven by the aim to make the internet more accessible, empowering, and useful for many years to come. 

This mission is reflected in our goals for IPFS - what we hope to tangibly achieve in the world. So far, we've identified **SIXTEEN** ranging over the next 5-10 years of work. These include launching the [Interplanetary Web](https://github.com/ipfs/roadmap#-interplanetary-web---mars-2024-d3-e3-i4), making the memx a reality with the [Personal Web](https://github.com/ipfs/roadmap#-personal-web-d3-e4-i2), shapshotting all human knowledge with the [Self-Archiving Web](https://github.com/ipfs/roadmap#-self-archiving-web-d4-e4-i4), and even merging the web and the OS with [WebOS](https://github.com/ipfs/roadmap#-webos-d5-e2-i3). While there are assuredly many that we haven’t explored yet, 16 is a good start - and far more than we could possibly work on this year. 
<image of goals>

To narrow in on where we should begin, we ranked the goals on a number of factors to create an ordered list. We sorted first in terms of low difficulty or "delta" (i.e. minimal additional requirements and fewer dependencies from the capabilities IPFS has now), then high ecosystem growth (growing our community and resources to help us gravity assist and accelerate our progress), and finally high importance (to ensure IPFS has a strong, positive impact on the world). This [sorting function](https://github.com/ipfs/roadmap#2019-priority) gave us a ranked list of goals to work towards to achieve our mission - where completing earlier goals brought us closer to the technical requirements and resources to achieve later goals. 
<image of sorting function>

Our [top-ranked goal](https://github.com/ipfs/roadmap#2019-goal-expanded) in this list is supporting the needs of package manager communities to bring the content-addressing, peer-to-peer, decentralized, and offline capabilities of IPFS to these critical components of the computing ecosystem. This goal in particular is close from a delta perspective, given there are already working demos experimenting with IPFS for package distribution like npm-on-ipfs. The package manager community is also a strategic community to learn from and build bridges with as we continue to grow our ecosystem and contributor base. Package managers play an immensely important role in the development of new game-changing technologies, so augmenting their tooling, sustainability, and support can unlock huge benefits for both the IPFS community and the world. 

Improving IPFS for package managers also has the added benefit of diagnosing and driving resolution of pain-points felt by many other IPFS users. IPFS aims to achieve internet-scale adoption - and beyond! To reach that goal, we need to support communities with significant scalability, performance, and reliability needs to stress-test and drive critical improvements to our core protocols and infrastructure. It also gives us the targeted feedback-loops to improve our usability and documentation for a specific use case - creating good habits about landing our protocol improvements end-to-end.

Identifying our top priority for the year was an important achievement, but it was still just the beginning. Next, we needed to break that goal down into milestones so we could incrementally add features, performance improvements, and educational guides to make “IPFS for package managers” a reality. We did this in two stages. First, individual IPFS working groups drafted feature and performance milestones of the work they saw as most important to achieve our goal. After a quick cross-working group feedback loop for asks and alignment, we “merged” across all working group roadmaps to create a unified project-level roadmap. You can see the results of this in our 2019 Epics. 

When taking on Package Managers as a top use case and priority, we realized there was still much we didn’t know about the needs and requirements to support this community - so learning more was our first step. We spun up a new [Package Managers Working Group](https://github.com/ipfs/package-managers) in early Q1, which has been focused on research, knowledge-sharing, and stress-testing the protocol with demos and experiments to target our efforts for the rest of the year. They’ve already identified a bunch of low hanging fruit around usability and performance. Want to get involved? [Check out this list of known issues and feature requests!](https://github.com/ipfs/package-managers/blob/master/blockers.md) _(and add more!)_

When we started out with 2019 planning, we actually took on **THREE** top-level priorities instead of one - so you may notice that [working group roadmaps](https://github.com/ipfs/roadmap) are a little out of date. It became clear shortly into Q1 that _three_ goals were far too many to focus on. There was lots of overlap between the needs of package managers and large files, but where the goals didn’t overlap it was bifurcating our focus and resources. Our “decentralized web” goal was also a year (or more) of work in itself - and largely dependent on all the underlying work we were doing to support package managers. Our initial roadmap was far too optimistic to achieve in a single year! 

Given this realization, we made the hard choice to descope those goals for 2019 and focus our energies on supporting package managers. However, we’d already finalized our Q1 OKRs and much of the prioritized work was still aligned and valuable for our narrowed priority. Therefore, we decided to pause any additional re-planning until the end-of-quarter mark. Not to fear, Q2 brings lots of fresh package-manager-focused improvements built on all of our great Q1 learnings. Curious what the working groups are picking up and how you can help out? Check out the IPFS Q2 OKRs and associated planning issues here.

Since the [IPFS Alpha release](https://github.com/ipfs/ipfs/blob/master/README.md#alpha-distribution) in February 2015, the IPFS project has grown significantly - including releasing our [Data Model (IPLD)](http://ipld.io/) and [Networking Stack (libp2p)](https://libp2p.io/) as standalone projects, amongst many other [exciting updates more recently](https://filecoin.io/blog/update-2018-q3-q4/#9-ipfs-update-for-filecoin). The past 4 years have brought huge improvements to the protocol, but we’re most excited about the path to come and all the awesome new capabilities described in our working group roadmaps. We hope you’ll join us on that quest - whether it’s suggesting usability improvements, writing performance benchmarks, helping optimize our [new apt-on-ipfs experiment](https://github.com/ipfs/package-managers/issues/18), or other new endeavors you propose.
