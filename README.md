{% include accordion.html %}

# Hello!
It's George, or figgyc as I go by on most of the internet. Currently I'm studying at a sixth form college in the UK but in my spare time I work on various side projects for online communities I participate in and other stuff.

![](https://img.shields.io/badge/discord-figgyc%230168-7289da) [![](https://img.shields.io/badge/github-figgyc-black)](https://github.com/figgyc) [![](https://img.shields.io/badge/twitter-%40f1ggyc-1DA1F2)](https://twitter.com/f1ggyc)

# Active projects

## [`figgyc/voterjs`](https://github.com/figgyc/voterjs)
Written in vanilla client-side JavaScript, [Voter.js](https://voter.figgyc.uk) is a simple webapp designed primarily for the community of the word game [Ten Words of Wisdom](https://discord.gg/ZWPvFRv) and spinoffs (although there is nothing stopping it from being used to rank any list of items). Using a simple yet sophisticated interface combined with an optimised merge sort algorithm, it allows the user to rank a list of responses to a game's prompt by simply clicking on which of a pair they deem superior. Especially on large sets of responses, voting of which is encouraged by hosts to improve the accuracy of results, it simplifies and accelerates the process since manually sorting a list requires you to retain a rough idea of all the responses and their positions in your memory which can be quite time consuming.

Usage exceeds 1500 users a week, and it is widely regarded as a useful tool, generally succeeding the original "voter.exe" project by being cross-platform and including more features such as automatic assembly of the final vote keyword (in TWOWs, responses are mapped to letters and an entire vote can be represented by a list of the characters from best to worst). It has been continuously updated with bug fixes and with additional features, such as keyboard shortcuts, grouping similar responses into sublists to save comparison time, and more.

## [`figgyc/bracketcounter`](https://github.com/figgyc/bracketcounter)
Using TypeScript and a custom high-performance asynchronous interface to the YouTube API, [Bracketcounter](https://bfb.figgyc.uk) counts comments on a YouTube video containing a particular pattern, and presents this in a simple to digest graph format. I designed this to correspond with the video series [BFDI](https://bfdi.tv) which is a viewer voted series in which comments determine the outcome of the game. As a result there is a lot of interest in who is eliminated before the release of the next episode so I decided to fill the niche. In fact this has resulted in a boost of engagement to the original videos as knowing of close results encourages more people to voice their opinion.

---
accordion:
  - title: Historical projects
    content: |
      ## [`figgyc/seedhelper2`](https://github.com/figgyc/seedhelper2) (March-July 2018)
            Written in Go, Python, JavaScript and a small bit of C, Seedhelper was a open source tool designed for the 3DS homebrew community. Augmenting the [seedminer](https://github.com/zoogie/seedminer) exploit written by zoogie, the website replaced a complicated system of forum threads, tireless volunteers and manual labour with a simple automated process. Using a custom written on-device program, it automatically interfaced with the friends system to extract key data, which could be combined with the exploit and a Python script on volunteer computers to automatically brute force the latter part of the process. This greatly increased the efficiency and over 30000 users were served by Seedhelper during its lifetime.

            Unfortunately due to a large volume of traffic driven by YouTube tutorials among other sources, the website had an error in July 2018 and despite my efforts it never recovered. (Still haven't figured out why to this day, maybe I could do a post mortem at some point to improve my Go knowledge.) It was succeeded by [BruteforceMovable](https://bruteforcemovable.com/) which reuses a large portion of the client-side and miner automation code with a different PHP-based backend, although today the 3DS scene largely relies upon simpler exploits revealed following the system's end-of-life."
---