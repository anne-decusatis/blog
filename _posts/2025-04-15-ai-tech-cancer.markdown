---
layout: post
title:  "AI and the tech industry in 2025"
date:   2025-04-15 16:00:00 -0400
categories: tech
---

### Or, why I'm no longer working on "curing cancer" [1] (or whatever [2])

Opinions my own and certainly not endorsed by my former employer [3]. 

### I'm looking for a new job for a variety of reasons, but...

The primary reason I'm looking for a new job now is that my now-former employer doesn't employ in Canada. Thus the root cause of the reasoning that led to me looking for a new job is that I decided that living in the US under another Trump administration as a transgender person who needs regular access to medicine to live was no longer tenable, and my wife and I had the privilege to be able to find a legal way out. Mostly her, to be honest. Related advice to my 16-year-old self: Even though you don't care about having prestigious collegiate credentials and don't really expect to live past 18, you know what Pascal's Wager is... [4]

So anyway, it would not be unreasonable to say that working on curing cancer is another thing [5] that I have had to opt out of participating in due to the current anti-trans extremism in US politics.

### What does it even mean for AI to cure cancer?

First: Cancer is not one disease. One of the things done early on for people who've previously had cancer and have it again is that the cells are tested for if it's the same cancer or a new one. Breast cancer and lung cancer cells (for example) look different and respond to different treatments.

Second: I think when most people imagine curing cancer they imagine like, you get cancer, and then something happens, and then you don't have cancer anymore. That is not the way cancer treatment currently works, not least because the cancer might come back, so in the best case scenario you're usually getting scans every 6 months for the rest of your life. A fomer coworker of mine told me once that "pharma companies don't want to cure cancer. They want to create a treatment for cancer." In other words, a one time cure is less profitable than an ongoing dependency. It's fairly trivial to pattern-match this to AIDS activism before there was effective treatment in Let The Record Show [6]. I might also pattern-match to the current best treatment for cystic fibrosis [7]. This is one reason why I believe that the thing most preventing the existence of a cure to cancer is capitalism. 

Third: Drug development moves slowly because people's lives are at stake and our best models are imperfect. A different former coworker of mine told me once that "most things that cure cancer also cause it" -- modifying the way cells work is risky. I think it's disingenuous to say that "AI curing cancer" is the same thing as "AI identifies several candidate drugs, then after 5-ish years or more, one of them becomes standard of care". That would be great, but it's significantly less impressive than the thing Sam Altman thinks will happen.

Fourth: I don't actually think machine learning is completely useless in cancer care. For example, the OpenAI case study with Color Health to identify missed screenings [8]. This kind of improvement within the system, while not the same as curing cancer, is still deeply meaningful. My mom's first round of cancer treatment was delayed by a year due to a missed screening, and the effects of that delay are still felt by her today, so this is personal for me. We should still talk about whether an LLM is the right way to improve that system, or whether the costs of LLMs are worth the benefits. I'm not convinced this needs to be OpenAI facilitated.

Fifth: I do think that AI can't replace clinicians. Meredith Broussard writes about this better than me, in More than a Glitch [9]. I've also heard that regulations are the main thing preventing health insurance companies from using AI fully in place of clinicians. Even cutting edge scan reader technology like Onc.AI's lung cancer scan AI is not marketed as replacing a radiologist [10].

### Bringing it back to the tech industry 

So, I'm looking for a new job. I've spent most of the last 10 years working with big data as a software engineer. The tech industry, and the world, has changed a lot since 2015 when I started this. Some of the changes are good: codes of conduct are more standard in professional tech industry spaces. Some of the changes are bad: most people used to think it was a fringe action to dox people who were in favor of inclusion [11], and now it's happening to government employees [12]. 

One of the changes that is the most felt is that there just isn't money flowing as freely through the tech industry in 2025 as there was in 2015. Companies have to actually be profitable, and they have to cut costs to do that. My rough understanding is that this is as a result of interest rate changes following/caused by COVID-era interest rate lows that impacted how public companies raise capital, but that only started mattering a few years later when it was time to refinance [13]. I'm not an accountant but it just feels like yet another thing Trump has taken from me personally. 

In this constrained environment, it's kind of weird that something that isn't constrained in hiring is AI-related tech companies. I assume, but have no proof, that this is because venture capitalists and people who are already rich from a previous tech boom think AI is the next tech boom. This is meaningfully different than AI tech companies not being cost-constrained, and Ed Zitron makes a case that this is unsustainable for OpenAI and its supporters [14]. In some cases the promise of AI is that it'll be cheaper than hiring humans for natural language curation tasks, like Amazon Mechanical Turk but it's real. As far as I can tell this has yet to be proven to work. If you've tried to contact any customer support line this year, you already know that what matters is not whether the computer you're talking to gives you the correct answer or solves your problem, but whether they have to pay someone to talk to you about it (I anti-recommend Walgreens for this, if you haven't). 

You'd think this proliferation of AI would leave me as a data engineer in a very good place. Unfortunately there's only one "the entirety of user-generated content on the internet" to scrape and they've already done that. So most of the small AI tech companies are more of the format "call an LLM API and return the result", which is not exactly the software engineering I've been training to do. It's not useless - there is still value in turning unstructured data into structured data - it's just something different. 

Maybe I'm just burned out but it doesn't seem as thrilling as it used to. I went into data engineering because I knew that machine learning was going to be important, and it was already so opaque and had such a big impact on people's lives. I used to believe that it would be enough for me to improve the inputs to the models, so that they worked well and returned accurate results which had fewer biases, and try to make change so that harmful data was not able to cause more harm [15]. Clearly nobody in power cares about the impact of their actions causing harm to others anymore though [16]. I keep asking myself, what can I do with my technology skills to make this better? And unfortunately it's seeming more and more like technology can't solve social problems that matter to me, and the best option is to do something that is small but that I can live with, with minimal daily worries about being complicit in the harmful systems surrounding me. 


### Citations

1. You may also like my previous fediverse thread on AI and curing cancer: <https://precise.space/@anne/114015751001948584>
2. A reference to <https://x.com/sama/status/1904921537884676398>, which I already regret boosting, even to mock it
3. "We’re on a mission to improve and extend lives by learning from the experience of every person with cancer." <https://flatiron.com/about-us>
4. Proving mainly that people who care a lot about probability and statistics, myself included, have been insufferable since at least the 17th century. <https://en.wikipedia.org/wiki/Pascal%27s_wager> 
5. Along with: our wedding reception, our honeymoon, living in our house in the US rather than an apartment in Canada, seeing my grandparents in person, etc. 
6. My review of the book: <https://app.thestorygraph.com/reviews/5df0e979-bbb5-4228-8e9c-eb0250b91139> 
7. As described by The Atlantic: <https://www.theatlantic.com/magazine/archive/2024/04/cystic-fibrosis-trikafta-breakthrough-treatment/677471/>
8. On the OpenAI website: <https://openai.com/index/color-health/>
9. Read the whole book, but this is the excerpt: <https://www.wired.com/story/artificial-intelligence-cancer-detection/>. My review here: <https://app.thestorygraph.com/reviews/17b58313-1028-4a86-b13b-c4a6c8baaa27>
10. Onc.AI used Flatiron Health data for it, if that helps establish my credibility: <https://www.businesswire.com/news/home/20250206095197/en/Onc.AI-Awarded-FDA-Breakthrough-Device-Designation-for-Serial-CT-Response-Score-Deep-Learning-Model>
11. Lambdaconf 2016, where I personally knew more people on the SJW list than I could count on one hand. <https://geekfeminism.fandom.com/wiki/Lambdaconf_incident>
12. We got one news cycle about it this time but then it got buried by the rest of the political world I guess. <https://www.nbcnews.com/health/health-news/federal-health-workers-terrified-dei-website-publishes-list-targets-rcna190711>
13. I also knew more than a handful of people impacted by the Spotify layoffs: <https://markets.businessinsider.com/news/stocks/spotify-layoffs-tech-streaming-debt-market-daniel-ek-interest-rates-2023-12>
14. Went to find the old one and saw that he posted a new one! <https://www.wheresyoured.at/openai-is-a-systemic-risk-to-the-tech-industry-2/>
15. I'm kind of tired of talking about my role in this but it should never have happened in the first place & it transformed me in profound ways, mostly negatively <https://www.vice.com/en/article/spotify-joe-rogan-transphobic/>
16. I'm just gonna link to <https://www.npr.org/sections/politics/> and assume one of the top five stories when you click on it is relevant. Top five when I checked this: "4 takeaways from the week: In a world that craves stability, Trump brings the chaos"; "How DOGE may have improperly used Social Security data to push voter fraud narratives"; "Supreme Court says Trump officials should help return wrongly deported Maryland man"; "Trump plans order to cut funding for NPR and PBS"; "States push Medicaid work rules, but few programs help enrollees find jobs"