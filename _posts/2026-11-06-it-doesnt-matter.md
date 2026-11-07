---
layout: post
title:  "It doesn't actually matter if you understand things anymore, apparently"
date:   2026-11-06 22:30:00 -0500
categories: tech
---

## What is an AI startup? Why do I work for one? A quick refresher

This section is for my non-tech friends. If you want to understand startup funding 101 and don't, keep reading this paragraph, otherwise skip to the next. A startup is a type of business where the founders have taken investment money from venture capitalists and the company has not yet "exited" - either closed down, grown and become publicly traded on the stock market, or acquired by another company. Startups go through "rounds of funding" where they first pay people a little to build something small that gets a little bit of use, and then they say to the people with money, "we can be even more successful if we can grow, which requires money. We'll trade partial ownership of our company for money, and we'll create enough value with that success that your ownership in us will be worth more than if you invested the money elsewhere", and then they build a little more with the next round, etcetera, until they either: run out of money and can't convince anyone to give more / are hugely successful and start offering ownership shares on the stock market / are medium successful and convince somewhere hugely successful to pay to acquire all the ownership in the company. The exiting is important because early employees and especially founders are paid in equity (of a similar kind to the kind they're giving investors) as well as cash, and eventually those humans want to sell that equity or otherwise turn it into real world money, which is much easier for a company traded on the stock market. 

I found Anil Dash's recent writing on this to be instructive when I was trying to figure out what exactly was going on in my industry: <https://www.anildash.com/2026/09/04/vc-didnt-use-to-work-like-this/>

I have worked as a software developer for my entire adult life. I completed my degree in computer science less than a month after turning 21, and started working full time in the industry about a month after that. I have found computers extremely compelling since I was a teenager chatting on AIM and installing Linux on my ancient-even-then ThinkPad for entertainment. I have worked for newly exited companies and overall, looking back, I found the environment there difficult for me to succeed in, for a variety of reasons: my own likely neurodivergence; my pre-existing environmentally accrued trauma; garden-variety misogyny and more recently also transphobia; the high turnover in the industry for most of my time there, and the uneven mentorship I therefore received (I had a new manager every two months for the better part of a year at one stretch in 2017-18). I eventually mostly figured out what I needed to do to succeed in that kind of environment and by then I was burned out enough that I decided I didn't really want to. But, although this is not technically the only thing I'm qualified to do, it is certainly the best aligned with my interests, and the best paid, and where I've spent years honing my craft. So if I don't want to work for a bigger tech company, and I want to work as a software developer, what remains is a smaller tech company, most likely a startup. And, as I previously blogged, when we moved to Canada in 2025 I really felt I quickly needed to find a job in my area of education and expertise that I could tolerate and that came from a Canadian employer of record. 

## The purpose of a system is what it does

I dug this out of my downloaded Twitter archive's "like.js" because opening the export's web interface for likes simply did not load my likes, and searching for "amy tech postmortem cigarette meme twitter" did not work either (you'd think it would be statistically close enough, these days?)

{
  "like" : {
    "tweetId" : "1072576388518043656",
    "fullText" : "COWORKER: we need to find the root cause asap\nME: \*takes long drag\* the root cause is that our processes are not robust enough to prevent a person from making this mistake\nCOWORKER: amy please not right now",
    "expandedUrl" : "<https://twitter.com/i/web/status/1072576388518043656>"
  }
},


One thing I am learning about working for a pre-series-A startup is that we are still experimenting with various ways of having our product work, in order to find the way that our customers (and therefore our future investors) are willing to pay the most for. I had heard about this in the abstract but in practice what it means is: the quicker we write experimental code, the more likely we are to succeed. We don't have to work as robustly as anywhere else I've ever worked - we just have to work more quickly so that we can pivot to what works best more quickly.

## What my AI usage looked like in September-October 2026

I made a Claude account with my work email, because my coworkers kept sharing "artifacts" (what Anthropic calls non-chat outputs in the Claude Code UI) and I needed to see the artifacts to do my job. I installed the Claude desktop app, because I asked for help pairing on a frontend implementation, and received from my coworker a prompt and instructions on how to set up the app to give it the prompt and screenshots, in order to complete the implementation. I sat there for maybe an hour saying yes to the machine every couple minutes and it dutifully copied the screenshots of the Claude-generated prototype into code intended for our actual web application. The content of the graphs it made was still not all that useful for data visualization, and I didn't even notice until the code was almost in front of a user. I ended up cutting about 2/3 of the graphs out by hand and keeping only what I thought was useful. I wished that I had been asked to use my professional expertise and judgment to make some useful graphs, instead of being given a Claude artifact, a Claude prompt, etc. 

Later in the month, I made a list of all the infrastructure topology work that needed doing (trying to prepare for the Kubernetes deprecation happening in December). I was exhausted and not really an expert in the specific ingress work that needed doing, but the person who initially set it up has left the company, and I'm the only one left who is willing to run Terraform commands against our AWS account. I'd previously asked, a few months before I was to start work, if we could hire a contractor to help and we don't have the time or money. So I have to muddle through it. I asked Claude Code to draft a migration plan and code. I read the plan myself and asked it a lot of questions about each step of the migration that I didn't already fully understand, to grow my understanding so that I could be prepared if it broke something when I tried to follow the plan, and so that if it gave a different answer later at least I'd have both answers. I'm not fully new to this kind of work so I did some manual vetting too - for example, that the commands it asked me to run would not be destructive and would accomplish something similar to what I was asking. 

## What I think AI is good for in software development, right now

* English language transcription, some of the time
* "Fuzzing", extremely broadly speaking / matching new things that are similar to existing things it previously saw
* Since it is trained on most of the internet and a lot of pre-existing working code, you can get most of your way to working code, and if it doesn't work maybe you can ask it some more and then it'll work. 
* When you don't care about your job, you can just ask Claude to do something, and then say you've done most of something
* It's also good at saying "you're absolutely right" even when you are absolutely wrong

Nevertheless, I continue to use it nearly every day.

## The future of the software development industry

I have read several articles saying that the future of software development is for AI agents to write and read the code, and humans to work at a higher and faster level directing the agents on how to change the product. I think this is meant to address or relate to Cory Doctorow's reverse centaur critique about autonomy. I do broadly agree that the work of being a software developer is to "create business value" and the means by which we do that is not necessarily just writing code. This does raise an obvious question of, what is the human doing to derive value that the text processing machine is not also capable of doing, given enough text examples? It would be shortsighted to not consider this, and also: I don't actually even think the machine can create quality work. The deep understanding I have is important to my craft and is why software development is expensive. Unfortunately it remains to be seen whether quality matters in and after 2026.

I have a friend who works as an artist and author on children's books, and she's said that she cannot use AI because she cannot choose to work directly with this machine that explains to children how to kill themselves. I think about this thing she said to me in passing every week. I related this anecdote to a friend that uses AI recently, and she was like "I mean, a quick review pass would prevent that from influencing the book", and I was like, I think it's more of an ethical choice thing? Like the point is not whether her books tell kids about suicide, the point is that it props up the legitimacy of the harmful system?

It feels awful for me to say that my fancy statistical autocomplete, that I use on days I don't have the time or energy for doing the work I used to do primarily with my own brain, is the same machine that kills children. I hate that I feel that using the child killing machine is something I feel I have to get OK with, because for all that I don't like it when children die, I don't want to leave this industry that I have invested so much of myself in. I want to wait it out and see what happens. In order to do that I have to make it through the present. And although it scares me to admit this, I don't hate using it as much as I used to. It is useful for some things. And if nobody else cares, and I can't channel my care into something that makes a difference, is it really doing anything useful for me to care, or is it just destroying my peace of mind to keep fighting over the risks I am choosing to radically accept?
