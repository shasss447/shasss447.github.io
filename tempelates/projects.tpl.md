---
title: "Projects"
draft: false
slug: projects
---

Here's what I'm up to right now.
[Connect with me to stay in the loop!](/about#get-in-touch)

---
title: "Projects"
draft: false
slug: projects
---

Here's what I'm up to right now.
[Connect with me to stay in the loop!](/about#get-in-touch)


## Ticket-Booker dApp

This is my first project using blockchain technology, a basic ticket booking dApp that allows users to book tickets using 'ether' as the payment option. Most of the languages, frameworks, and technologies used in this project were new to me, except for HTML and CSS.

Users can connect their [Metamask wallet](https://metamask.io/) with the dApp and easily book tickets in a few simple steps. The core algorithm is implemented as a smart contract in [Solidity](https://soliditylang.org/), while the website structure is built using [ReactJs](https://react.dev/). Currently, the smart contract can be deployed locally, and ether transfers are facilitated between the smart contract deployer and the connected dApp account. [Hardhat](https://hardhat.org/) is used for all the necessary configurations.

Reflecting on the learning outcomes of this project, I can divide them into two sections. Firstly, from a professional standpoint, I gained knowledge about blockchain technology, the Web3 ecosystem, the versatile React.js framework, the powerful Solidity programming language, the [Ethereum Virtual Machine](https://ethereum.org/en/) (EVM), and other related concepts. Secondly, I realized the importance of reverse engineering when learning any new skill or technology. Instead of solely relying on courses, YouTube videos, or blog readings, it is valuable to gain basic knowledge and start building something. Along the way, you will encounter challenges, doubts, and problems, but the learning curve will be worth plotting.

You can checkout the repo at - https://github.com/shasss447/Ticket_booker_dapp.git


## This blog website

I always had a desire to create my own website to share my thoughts and experiences, but I never got around to it. So, this vacation I was fixed on making a one and, I came across my friend's [personal blog website](https://navyanshmahla.github.io/), which inspired me greatly. The very next thing I did was message him to inquire about how he built it and started searching on my own.

I discovered that his website was a static site made with a tool called [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages. Excited by this, I researched and found [Hugo](https://gohugo.io/),another static-site generator.after hovering a little on hugo documenation I installed hugo and go and made a quicksite using the "quickstart" guide. The next step was to choose a suitable theme, which took me quite some time. Since I wanted to write blogs and showcase my "countable" number of projects, I opted for a theme that aligned with those requirements. After several hours of searching and deliberation, I finally settled on a beautiful theme called [Gruvbox](https://github.com/schnerring/hugo-theme-gruvbox.git).

Following the theme's documentation, I installed it and turned to YouTube for some beginner-friendly tutorials. Fortunately, I stumbled upon the website repository of the theme's author, which was built using the same theme. This discovery made the process somewhat easier, as I could study the repository and adapt it to my own needs. After approximately 10-12 hours of dedicated work, my website was ready.

Throughout this journey, I acquired knowledge about [Markup](https://www.markdownguide.org/) languages, YAML, the workflow of static websites, and various other web development concepts.

You can checkout the repo at - https://github.com/shasss447/shasss447.github.io.git

<!-- prettier-ignore-start -->
<!-- markdownlint-disable MD013 MD032 -->

{{ range recentPullRequests 10 }}
- [{{ .Title }}]({{ .URL }}) on [{{ .Repo.Name }}]({{ .Repo.URL }}) ({{ humanize .CreatedAt }})
{{- end }}

<!-- markdownlint-enable MD013 MD032 -->
<!-- prettier-ignore-end -->