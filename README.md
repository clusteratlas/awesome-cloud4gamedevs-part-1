# Cloud For Game Developers - Introductory

## Welcome!

> **This is Part One of our Cloud For Game Developers series.**

---

## Table Of Contents
- [x] What Is The Cloud
- [x] Cloud Myths Busted
- [ ] What Is The Cloud For **YOU** As A Game Dev
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
  <img src="http://i.imgur.com/iZ5Yg99.jpg" alt="awesome">
</p>

Cloud Computing is the general term used for delivering computer services over the Internet. 

The basic idea is that you are renting / leasing servers, storage, and networking infrastructures from major companies like Microsoft, Amazon & Google. Hence we use the terms 'The Cloud', 'Cloud Computing', or 'Virtualized Environment', because the whole amazing fiasco allows you to utilize these resources without actually touching them. <sup>[@ Mozilla](https://developer.mozilla.org/en-US/docs/Learn/Drafts/Understanding_Cloud_architectures), [@ Reddit](https://www.reddit.com/r/explainlikeimfive/comments/j62ec/eli5_cloud_computing_andor_the_cloud/)</sup>

---

## What Is **The Cloud** For **YOU** As A Game Developer

### It's meant to work with you.

As a Game Developer, you want the Cloud to initially work in your favour first:

- It should provide you more cost-efficiency when it comes to consuming resources.
- It should provide you ease & comfort in your development & deployment processes.
- It should save you from a lot of infrastructure-related headaches, allowing you to focus more on your game rather than building & configuring infrastructures.

And luckily, Cloud Providers like Microsoft Azure, Amazon Web Services (AWS) & Google Cloud Platform (GCP) are committed to that.

### It's intended initially for developers; but most importantly for end-users, too.

It is granted. Modern cloud technologies are designed to speed-up & take away the hassles in our development & deployment processes. As a Game Developer however, the best solutions that garner the best results when you're putting your end-users first, which are your players.

It works wonders when you're approaching these Cloud Technologies while asking yourself:

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

You can say that it's like a *which-comes-first-chicken-or-egg* scenario.

- A game that is not well-thought and just overall sucks will still suck, even if you plug-in cloud technologies with it.
- A game that is well-thought,  almost-works and looks-promising however might be turned into the greatest when mixed with cloud technologies.

Caveat: If you're experimenting on cloud technologies and you're looking to see how it can help you, go on! Yes you should proceed, and yes you should explore!

---

## Cloud Myths Busted

### Myth # 1: Using The Cloud IS EXPENSIVE

No, because if you weigh the advantages and the plethora of features you get from using the cloud, compared to using Bare-Metal / VPS / Dedicated Servers setups, you'll realize you're actually winning. High scalability, networking & dns-level configurability, multiple regions available for your deployments, database & cache services right at your fingertips, and hell a bunch more.. - beat that!

No, because in the cloud there are No Upfront Costs, and you are only charged by the minutes & the hours you consume their resources. This means you can switch them off (or de-allocate these resources) them whenever you're sleeping, or feel like it, then you can just switch them on (or re-allocate them) at any point in the future - and they will only charge you again at that moment!

No, because you can set spending limits. These cloud providers allow you to set an allotted budget on their platforms in order for you to avoid over-spending. If you set $25, $50, $150 or even $1,000 per month, they respect it and will never exceed it!

No, because these cloud providers even give you free damn credits & resources the moment you signed up! A year of around $300 credits from Azure, AWS & Google Cloud plus a bunch of free-tier features for you to use - you aren't out of your mind to think that you are losing, aren't ya?!

TL;DR: Yes the cloud will be expensive for you if you're careless, and you don't read them manuals & documentations on how to use them in a cost-efficient manner. This series right here aims to teach you that, so calm down and let's move to the next myth.

### Myth # 2: Using The Cloud IS COMPLICATED AS F\*CK

**No, since learning how the cloud can work for you doesn't mean you have to learn everything in the cloud.** That's the same reason on why there are guides like this, to simplify everything, to give you a concrete and concise idea of the certain things that only matters to you.

TL;DR: Just focus on the things that will be useful to you, and in no way should things get complicated.

---

## Things To Consider Before Using The Cloud

### First Things First, Do You Need It?

| Cloud Service / Feature | Description |
| ------------- | ------------- |
| File Storage | Host gigabytes to terabytes of files |
|  | *Can be used for hosting patches, updates, etc.* |
| Queues | Durable queues for large-volume cloud services |
|  | *Ideal for scalable message-processing nodes* |
| File Shares | Simple, distributed, cross-platform file storage |
|  | *For sharing files between virtual machines & applications* |
| Tables | Relational / Non-Relational database |
|  | *Can be used for hosting your game & player data* |
| Virtual Machines | Create Linux and Windows virtual machines in seconds |
|  | *Server instance that can host your game's server-side code* |
|  | Supports auto-scaling for high-availability |
|  | Easily scales vertically (increase / decrease # of Cores, RAM & Network Bandwidth |
|  | Easily scales horizontally (create / spin-up another server instance with the same specs) |
| Cloud Delivery Networks | Secure, reliable content delivery with broad global reach and rich feature set |
|  | *Ideal for global asset delivery* |
| Virtual Networks | Isolated & highl-secure environment for your virtual machines |
|  |  |

- Managed storage, tables, queues & file services
- Server instances / virtual machines that easily scales vertically & horizontally
- Highly-scalable database & cache services
- Virtual networks & managed DNS

If you see learning and using the cloud resulting into an overall improvement & polishing of your game then definitely go for it!

---

## Summary

- 'The Cloud' is simply all about renting servers, storage & networking infrastrucures online.
- Microsoft Azure, Google Cloud Platform & Amazon Web Services are currently the Top 3 Cloud Providers.
- Using their online platforms, you can host Windows & Linux servers on them.
- These server instances called 'Virtual Machines' can be exposed, or be made reachable in the internet by assigning **Public IP Addresses** on them, and furthermore **opening ports** on them.

---



---

## License

[![license](https://upload.wikimedia.org/wikipedia/commons/6/69/CC0_button.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
