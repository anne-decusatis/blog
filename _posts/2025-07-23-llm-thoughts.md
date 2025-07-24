---
layout: post
title:  "Two months (ish) of using LLMs regularly"
date:   2025-07-23 22:00:00 -0400
categories: tech
---

Sumana, after my last post, asked me <https://social.coop/@brainwane/114874727281951108>: 
> what effects *on you* have you noticed over the period that you have been using LLMs in your day-to-day work? Emotionally, cognitively, on the job while interacting with them, during other parts of the job, outside the job? Unexpected, predicted, welcome and unwelcome?

## Why it's not exactly accurate to call it only two months

I'd previously used an LLM tool for maybe six months at work that was cleared to look at some of our confidential-but-not-health-PHI documents. I wanted to use that tool in order to evaluate whether I could trust the people who were already using it around me to share accurate information. It was being pretty heavily pushed by the VP of Engineering, and it gave automatic responses to sociotechnical questions in several channels I was in that were frequently incomplete, if not fully incorrect. I especially disliked when it told me to ask the question I had just asked in the Slack channel I was currently asking in, in order for my team (me) to provide additional support. I thought that I could get credit for looking to the VP like I was engaging productively with the next generation technology, if I could find some way to use it that was less annoying than simply downvoting the incorrect answers it gave. I didn't find it significantly better than searching Slack directly myself, so I stopped using it, but I am more of a Slack power user than most of the people I encounter. (As an aside, the software developer who seemed to use AI the most effectively in that job basically used it to brush off people who would repeatedly ask her questions that they could've answered themselves, that she didn't want to deal with. There were some dysfunctions in that organization, which I found out only after joining.)

### An example: the first time I chose to use ChatGPT

The first time I used ChatGPT directly was mid-November 2024. Trump had just been elected in the US, and when the election results were final the second week of November, I dusted off the list of Canadian PhD programs in computer science that I'd previously made when Biden dropped out of the race, and then ignored entirely for several months. The first application deadline was December 1 and so I decided that I would act as-if I was definitely going back to grad school until December 1, and deal with deciding if I really was committed to going if I got accepted. (spoiler from the future: I did not get accepted.) I'd already decided that if I was going to commit five years more to academia, it would be on evaluating and building more-ethical AI, because I think it's the most important issue that I can become qualified to address in five years. I knew that my non-traditional background for PhD programs (a decade of software work experience, an undergraduate degree in CS from a no-name state school, and a fully online "terminal master's" from another no-name school, which didn't grant me a GPA, for which I did a capstone project rather than publishable research) meant that I would have to be extremely persuasive and also fairly lucky to have a chance of getting an interview. I was panicked and put myself under a lot of pressure.

I asked ChatGPT to evaluate a draft of my personal statement and rate it, along with making suggestions for areas that needed improvement. I had already worked with a friend of mine who is a professor in a different field, who has a PhD, on several drafts. The first time I used it, it rated me fairly highly, and gave suggestions for a few points at which it could be strengthened. I made those changes and asked again. The second time I used it, it rated me lower than the first, and identified mainly that my background was not directly relevant and I should write about directly relevant research experience. That wasn't helpful because I didn't/don't have that experience. I came away with a sour feeling about it, I don't want to be negged by a computer, although I guess it was right? When I talk to people about PhD programs in AI research, they also say that I should find a way to do some publishable research, likely on my own time after my full workday ends and unpaid, to get my name out there.

I also read a bunch of papers from the research labs I was applying to join, analyzing the outputs of human-in-the-loop AI. It's perhaps worth noting that many of these papers come from skeptics who use AI heavily in their research in order to prove its negative impact, and this helps me believe that it is possible to meaningfully engage with AI without being entirely swept away by its hype. 

## What I do and don't do with LLMs in my current job, from most to least AI-intensive

One portion of my job is to write/edit LLM prompts. I am not the primary person who does this and addresses bugs with the prompt input and output, but part of owning feature improvements end to end on the features I work on is that when the feature involves LLMs, I copy an older prompt, edit it into something that I think looks right, run it, and then ask that primary person how I can improve it. I usually do this in a Jupyter notebook.

Another much larger portion of my job is that I wrote (and am, as far as I can tell, currently the only person at the 15 person startup to successfully use) a mini integration between our Django instance and PydanticAI's data modeling systems. This enables us to save prompts and contexts in the Django admin UI that is already in use. I plan to extend it soon to validate prompts on the way into the database as well as when they are used. This is useful in the way that experienced backend software engineers are generally useful - the system design has a better separation of concerns than we previously had.

I am careful to let into most of my work video calls the AI notetaker/assistant that forms much of our product. This felt weird and bad at first but I believe it to be an expectation of my employment that we all accept it, and it doesn't feel as weird as it first did now that I keep doing it. Sometimes we kick the notetaker out if it's just a social call or if topics diverge and get too personal for someone. I sometimes refer to the transcript or summary that it generates as I continue work after the meeting. I don't like to look at the transcripts if I'm in them - I feel similarly to the way I do when I have to listen to recordings of myself (a negative feeling). Though, once I came five minutes late to a standup and realized I'd missed some social chatter at the beginning because the summary said that one coworker had talked about something specific he saw on his recent vacation. That felt sort of fun to hear about even though it was not from him directly, and I think that that summarization/reminder for me to ask the person for real later is part of what people think LLMs can do well.

I don't currently use AI assistants in my IDE (yet?) but my coworkers do, and I often find myself ignoring the not-really-a-security-issue comments that Copilot erroneously identified on our PRs. My coworkers also sometimes write documents with AI coauthoring and I generally find them a bit vague and not as helpful as if they had written it entirely by hand. I do like when they credit the AI coauthor though so I can know to be careful in my reading.

I also still type my own notes because the act of note taking in real time allows me to clarify requirements better - e.g. I can read back what I typed and say, is that what you meant?. I have noticed myself being slightly lazier about deciding to start taking notes if I think it'll be quick and the notetaker will get it. 

## Effects I have noticed

### My gut reaction is no longer to ignore AI answers completely, but I still fact-check them

The first time I used a prompt that I wrote with PydanticAI and got out the answer I wanted, it felt like magic, and I understood why people were excited about it. Simon Willison's keynote at PyCon 2024 made me start to feel this way too, but it was different when it came from my own hands.

I now do actually read the AI summaries when I Google Python and Django syntax questions. With that said, if the consequences of the Python syntax being run are potentially destructive, I will always click into sources that are hopefully vetted and read them. This works because I am already experienced and can safely evaluate whether the commands are likely to be destructive and whether the sources are trustworthy. 

Following this same principle, I use Duolingo daily, but also pay for small group language classes through Alliance Française, since I don't know enough French on my own to fact-check the Duolingo AI but I think my French teacher can correct me before I go too far down the wrong path.

### Friends who don't work for tech companies now ask me if AI is useful when they find out about my employment

People are curious! It's fun to talk about things I find interesting! My wife does complain that I sound like I am stating facts even when I express opinions, though. 

Two examples this month:

1. A new local friend mentioned that she was having trouble loading AO3 on Firefox. I looked at the extensions she had installed and recommended she disable one of either uBlock Origin or Adblock Plus, since they do the same thing and might conflict with each other - I got lucky and that seemed to resolve it. She then decided I was good at computers and asked if she should be using AI tools to help with her graduate thesis in social science. I tried to give a diplomatic answer -- some things about them are bad, some are useful, like any statistical tool it's important to understand what it is good for and what it is bad for because it will not stop you from using it incorrectly and giving you nonsense output instead of something valid, like any tool period it can be used for good and for evil. 

2. A long time friend of my wife mentioned on their monthly call that he is hearing about people using AI at the bank he works for (I think he works in a role that coordinates other people), and had a lot of questions for me about what it can and can't do. At first I was surprised by what he said it was being used for, but digging into the actual details, it made sense to me and I felt it had appropriate caveats and checks in place at this time. 

### Two things I now think LLMs are sort of good for

One: Extracting semistructured data from completely unstructured human-created text, if it doesn't have to be perfect and can be "good enough" and/or reviewed by a human later.

One thing that's interesting to note is that expert human abstraction of medical data into a structured format is also not 100% accurate - sometimes patient charts are ambiguous, and the main goal of a medical chart's authors isn't to be used for later research most of the time. It is also still true that the map (chart) is not the territory (body) - I worked on a cancer dataset once that consisted mainly of patients who met the dataset inclusion criteria because their doctors had diagnosed them based on the imaging and biopsy, and in the subsequent surgery it was found that the cancer was larger than expected and they might not have gone to surgery at that stage had that been known.

Two: Searching through a large dataset to find an approximate match for a query that can be contextualized and dug into in more depth by a human. More broadly, summarization?

Are LLMs good enough at these things to be worth the known bad side effects? I'm not sure, but if they are good at things is a research question so I guess whoever did get accepted to the PhD programs I was rejected from will publish on it in the next few years. My intuition is, probably not in the long term, but neither are cars or airplanes and I use those too. I am not sure yet what harm reduction looks like for my use of cars either. 

Is it also bad that LLMs are being used for things that they are not suitable for? Yes. I don't control what other people do though. 

## Related links

<https://www.bloodinthemachine.com/p/how-ai-is-killing-jobs-in-the-tech-f39> - it seems like most of the people in this article who lost their tech jobs due to a refusal to work with AI, or due to tech companies laying them off in an AI hype focused change, found it very difficult to find new work. One quoted person explicitly said that they'll retire early instead. 

<https://unthinking.photography/articles/on-lacework> - my absolute favorite article on AI datasets and human curation, I keep coming back to it. I link it now because it is part of why I feel that LLMs are not necessarily uniquely bad for humanity, they just do the preexisting things that machines do to humans, and by proxy that humans do to other humans, at a larger scale. 