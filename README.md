# Cloud For Game Developers - Introductory

## Welcome!

> **This is Part One of our Cloud For Game Developers series.**

---

## Table Of Contents
- [x] What Is The Cloud
- [x] What Is It For **YOU** As A Game Developer
- [x] Cloud Myths Busted
- [ ] Things To Consider Before Using The Cloud
  - [ ] First Things First, Do You Need It?
  - [ ] Identifying Your Game Type
  - [ ] Your Programming Language
  - [ ] Your Target Platforms
  - [ ] Local Area Network (LAN) Games
  - [ ] Over-The-Internet Games
  - [ ] Things That Matter

---

## What Is Cloud Computing a.k.a. The Cloud?

<p align="center">
  <img src="http://i.imgur.com/iZ5Yg99.jpg" alt="img">
</p>

Cloud computing means you have a "pool" of computing resources (like memory, processor power & data storage) somewhere, served by tons of real-life computers.

The basic idea is in this day and age, we now have these "Cloud Providers" - which are mostly BIG companies with massive resources - that now allow us to rent / lease computing resources on-demand.

They can vary from:

- Virtual Machines (w/ varying # of CPU cores, amount of RAM & disk types), which enables running of linux / windows servers online
- Data Storage Services, which allows storage of massive amounts of data
- Network Infrastructures, which makes virtualized networking painless & effortless
- Database & Cache Services, for your data-centric needs
- And so much more!

They serve these resources to us from their **data centers**, which are large facilities of highly-optimized and highly-organized computers, network & storage systems. These data centers are designed & engineered by experts such that practices like use of cooling systems & power-consumption management allow them to serve these services to us at low competitive rates, while still being highly-performant & having minimal downtime.

Each Cloud Provider have their own data centers in various regions around the globe.

- [Microsoft Azure](https://azure.microsoft.com/en-us/regions/) is currently generally available in 34 regions around the world, with plans announced for 4 additional regions. 
- [Amazon Web Services / AWS Cloud](https://aws.amazon.com/about-aws/global-infrastructure/) on the other hand operates 42 Availability Zones within 16 geographic Regions around the world, with announced plans for eight more Availability Zones and three more Regions.
- [Google Cloud Platform / GCP](https://cloud.google.com/about/locations/) has 7 regions, 20 zones, over 100 points of presence, and a well-provisioned global network comprised of hundreds of thousands of miles of fiber optic cable.

Now, when you need these resources for say, a website or a game server, instead of using a single machine, you just lease them instead from a Cloud Provider.

This method has the advantage of being scalable, meaning, it doesn't matter if you want 1GB of RAM or 128GB of RAM, you can just take it from their pool of resources, instead of configuring a single local computer to do the job. Spinning up another server instance (ie. for distributing workload, or high-availability purposes) is also possible since these Cloud Providers have these resources on stand-by, available for your use anytime you'd like.

References:

  - [SCAtomika @ Reddit](https://www.reddit.com/r/explainlikeimfive/comments/j2r46/cloud_computing_explain_it_like_im_five/c28nl84/)

## How is it compare to Regular Hosting Providers?

Below is a bird's eyeview on how Regular Hosting Providers & Modern Cloud Providers greatly differentiate when compared with each other:

| ~ | Regular Hosting Providers | Cloud Providers |
| :-------------: | :-------------: | :-------------: |
| EXAMPLES | Namecheap, GoDaddy, Hostgator, Etc. | Azure, AWS, GCP, etc. |
| Charged monthly, pay-before-you-use | ✔ | ✘ |
| Charged by minutes / hours of use, pay-after-you-use | ✘ | ✔ |
| You can set spending limits / alotted monthly budget | ✘ | ✔ |
| Designed for scale | ✘ | ✔ |
| Got massive resources & robust infrastructures | ✘ | ✔ |
| Data-centers in multiple regions & continents | ✘ | ✔ |
| Great front-end platforms (for resource management) | ✔ | ✔✔✔ |
| Plethora of features & configurability | ✔ | ✔✔✔ |
| Competitive sales & technical support | ✔ | ✔✔✔ |

Now if it seems convincing enough for you, we should better focus now on how Cloud Computing can help you as a Game Developer.

---

## What Is It For **YOU** As A Game Developer

<p align="center">
  <img src="http://i.imgur.com/GymOzpJ.jpg" width="320" alt="img">
</p>

### It's meant to work with you.

As a Game Developer, you want the Cloud to initially work in your favour first:

- It should provide you more cost-efficient options when it comes to consuming resources.
- It should provide you ease, comfort & massive improvements in your development & deployment processes.
- It should save you from a lot of infrastructure-related headaches, allowing you to focus more on your game rather than building & configuring infrastructures.

And luckily, Cloud Providers like Microsoft Azure, Amazon Web Services (AWS) & Google Cloud Platform (GCP) are committed to that.

### It's intended initially for developers; but most importantly for end-users, too.

It is granted. Modern cloud technologies are designed to speed-up & take away the hassles in our development & deployment processes. As a Game Developer however, the best solutions (that garner the best results) come out when you're putting your end-users first, which are your players.

It works wonders when we're approaching these Cloud Technologies while asking ourselves the following:

- Which of these things can help me reduce the lag and/or the latency?
- Which of these things can help me provide players in another continent a better gaming experience?
- Which of these things can help me in handling large amount of player data?
- Which of these things can help me process large amount of incoming & outgoing data when I encounter massive player traffic?
- Which of these things can help me do game analytics without affecting their gaming experience?
- Which of these things can provide me a failover solution during bad times, like unwanter server crashes and such?
- Finally, which of these things can help me in implementing all of these things without breaking the bank?

### It's just another tool, in your awesome set of tools.

The Cloud isn't a be-all end-all type of thing that can solve all of your game-dev problems.

- What other things can I put more effort for us to improve the gaming experience?
- Maybe more work in GFX & Animation?
- Maybe more work in SFX / Music?
- Maybe more work in overall [gameplay](https://en.wikipedia.org/wiki/Gameplay), [game mechanics](https://en.wikipedia.org/wiki/Game_mechanics) & [game design](https://en.wikipedia.org/wiki/Game_design)?
- Maybe more work in compatibility with other platforms?
- Maybe more frequent developer-to-player updates, and showcasing of your game in social media?

You should never lose sight of all these front-end part of things while you work on your back-end!

### Finally, it's useless if you ain't got no players.

You can say that it's like a [*zero-sum*](https://www.merriam-webster.com/dictionary/zero-sum) scenario.

- A game that is not well-thought and just overall sucks will still suck, even if you plug-in cloud technologies with it.
- A game that is well-thought,  almost-works and looks-promising however might be turned into the greatest when mixed with cloud technologies.

Caveat: If you're experimenting on cloud technologies and you're looking to see how it can help you, go on! Yes you should proceed, and yes you should explore!

---

## Cloud Myths Busted

<p align="center">
  <img src="http://i.imgur.com/g3Al7jl.jpg" width="320" alt="img">
</p>

### Myth # 1: Using The Cloud IS EXPENSIVE

No, because if you weigh the advantages and the plethora of features you get from using the cloud, compared to using Bare-Metal / VPS / Dedicated Servers setups, you'll realize you're actually winning. High scalability, networking & dns-level configurability, multiple regions available for your deployments, database & cache services right at your fingertips, and hell a bunch more.. - beat that!

No, because in the cloud there are No Upfront Costs, and you are only charged by the minutes & the hours you consume their resources. This means you can switch them off (or de-allocate these resources) whenever you're sleeping, or feel like it, then you can just switch them on (or re-allocate them) at any point in the future - and they will only charge you again at that moment!

No, because you can set spending limits. These cloud providers allow you to set an allotted budget on their platforms in order for you to avoid over-spending. If you set $25, $50, $150 or even $1,000 per month, they respect it and will never exceed it!

No, because these cloud providers even give you free damn credits & resources the moment you signed up! A year of around $300 credits from Azure, AWS & Google Cloud plus a bunch of free-tier features for you to use - you aren't out of your mind to think that you are losing, aren't ya?!

TL;DR: Yes the cloud will be expensive for you if you're careless, and you don't read them manuals & documentations on how to use them in a cost-efficient manner. This series right here aims to teach you that, so calm down and let's move to the next myth.

### Myth # 2: Using The Cloud IS COMPLICATED AS F\*CK

**No, since learning how the cloud can work for you doesn't mean you have to learn everything in the cloud.** That's the same reason on why there are guides like this, to simplify everything, to give you a concrete and concise idea of the certain things that only matters to you.

TL;DR: Just focus on the things that will be useful to you, and in no way should things get complicated.

---

## Things To Consider Before Using The Cloud

<p align="center">
  <img src="http://i.imgur.com/ys1uFGv.jpg" width="320" alt="img">
</p>

### First Things First, Do You Need It?

It's a waste of time learning its ins & outs if you initially don't need it, correct?

Hereunder is an overview of mostly-used Cloud Technologies, and their use-cases.

| Cloud Technology | Description | Use-Cases |
| ------------- | ------------- | ------------- |
| **File Storage** | Host gigabytes to terabytes of files | Hosting patches, updates, small & large files, etc. |
| **Queues** | Durable queues for large-volume cloud services | Processing global events, messages, etc. |
| **File Shares** | Simple, distributed, cross-platform file storage | As a shared file-system |
|  |  | Between your server instances |
|  |  | Or w/ your on-premises workstation (ie: local Windows 10/Linux) |
| **Tables** | Relational / Non-Relational database | Hosting your in-game data |
| **Virtual Machines** | Create Linux and Windows virtual machines in seconds | Host your game's server-side code |
|  |  | Host your game's static website |
|  |  | Host your game's online platform |
| **Virtual Machine Auto-Scaling** | Vertical / Horizontal scaling for High-Availability | Increase / decrease # of Cores, RAM & Network Bandwidth |
|  |  | Create / spin-up another server instance with the same specs on high player traffic |
| **Load Balancers** | Delivery of high availability & network performance. | Distributing massive player traffic into multiple server instances |
|  |  | Automatic failover to healthy instances, in-case of a server instance failure |
| **Virtual Networks** | Isolated & highly-secure environment for your virtual machines | Inter-connectivity between server instances |
| **Cloud Delivery Networks** | Secure, reliable content delivery with broad global reach | Better global file / asset delivery |
|  |  | Speeding up your static websites & online platforms |
| **Managed DNS** | DNS management w/ outstanding performance & availability | Quick updates to DNS records |
|  |  | Easy domain & sub-domain management |

If you see any of these technologies working in your favour, then yes you need the cloud! And yes, proceeding with this series will definitely be helpful for you!

### Your Game Type

Your cloud needs will absolutely vary by the type of your game:

- **Turn-based**, like card-games & board-games
- **Slow-action**, like casual action games
- **Real-time**, like racing, action-rpg's, & shooters
- **Fast-action**, which are demanding real-time games

Now look, try to answer the following questions:

- How much do you think will be your monthly active players?
  - *1,000? 5,000? 50,000? 100,000?, 500,000?*
- How many concurrent players do you see to serve at a time?
  - *100? 500? 5,000? 10,000? 50,000?*
- How often do you send & receive packets with each player?
  - *10-50x / minute? 10x / second? 30x / second? 60x / second?*
- How much bandwidth per-second per-player should you handle?
  - *50 B/s? 500B/s? 1KB/s? 10KB/s?*
- Which things should ideally be sent w/ TCP or UDP?
  - *All sensitive data across TCP?*
  - *All realtime / time-sensitive data across UDP?*

### Your Programming Language



### Your Target Platforms

---

## Summary

- 'The Cloud' is simply all about renting servers, storage & networking infrastrucures online.
- Microsoft Azure, Google Cloud Platform & Amazon Web Services are currently the Top 3 Cloud Providers.
- Using their online platforms, you can host Windows & Linux servers on them.
- These server instances called 'Virtual Machines' can be exposed, or be made reachable in the internet by assigning **Public IP Addresses** on them, and furthermore **opening ports** on them.

---

## License

[![license](https://upload.wikimedia.org/wikipedia/commons/6/69/CC0_button.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
