---
layout: post
title:  "Conference talks from my personal archive"
date:   2025-04-16 11:00:00 -0400
categories: tech
---

When I took down my previous blog in 2020 for personal safety reasons, the major thing it contained was overviews of technical talks I have given. This post contains links and context throughout my career that I still want to reshare in 2025.

### Stay Hydrated: similarities between Python programming and swordfighting (5 min)

Presented at PyCon Lightning Talks, May 2024.

[Slides]({{site.url}}{{site.baseurl}}/media/2024-pycon.pdf) and [speaker notes]({{site.url}}{{site.baseurl}}/media/2024-pycon.txt).

### How To Eliminate Surprises In Your Data (30 min)

Note from 2025: I no longer wish to remain complicit in building the professional reputation of Jon Pretty, including by using his software such as Magnolia. I don't care about what happened in UK court since then, and I still believe [Yifan](https://medium.com/@yifanxing/my-experience-with-sexual-harassment-in-the-scala-community-9245b4a139de). I have no further interest in being a part of the Scala community after this and several other community issues over the years I actively wrote Scala: [example one](https://github.com/typelevel/general/issues/74), [example two](https://contributors.scala-lang.org/t/politics-safety-and-the-future-of-scala/5317).

How To Eliminate Surprises In Your Data was co-written and co-presented with my then-coworker Idrees Khan. 

Presented at Scale By The Bay, November 2019 ([slides]({{site.url}}{{site.baseurl}}/media/2019-11-14-surprises-data.pdf), [speaker notes]({{site.url}}{{site.baseurl}}/media/2019-11-14-surprises-data.pdf)); Northeast Scala Symposium, March 2020 ([slides]({{site.url}}{{site.baseurl}}/media/2020-03-surprises-data.pdf)).

Accepted to Scala Matsuri, June 2020; had to withdraw as travel from the US to Japan wasn't possible in June 2020. 

Abstract: How do you know you can trust the accuracy of the data flowing through a pipeline, and the insights derived from it? At Spotify, we have an infrastructure team focused on data quality to address this problem. From the cultural changes we’re making to give data engineers a quality mindset, to the specific tools we’ve written, we’ll explain how we increase confidence and eliminate surprises in our data contents, and how we approach problems in the wide space of ‘data quality.’ You’ll learn about a few key moments in the pipeline lifecycle when data quality might be compromised, and the approach we took to improving them.

### You can run (almost) anything on the JVM, so why not run everything on the same JVM?! The magic of interoperability! (8 min)

Presented at Spotify internal Data & Insights conference, May 2019.

[The slides and demo code are available](https://github.com/anne-decusatis/jvm-interoperability).

Further bits and pieces:

[GraalVM](https://www.graalvm.org/) -- not covered in this talk, a different virtual machine to run Java bytecode and other things on

Languages I wanted to include but didn't yet:

- [Haskell](https://eta-lang.org/) -- sbt plugin hasn’t been updated in a while & shells out to an unsupported/broken version of their runtime env - could rewrite
- [OCaml](http://www.ocamljava.org/) -- last updated 2015 - in OCaml website the hello world program doesn’t print anything - it’s a tree traversal
- [PHP](https://github.com/jphp-group/jphp)

### A Pop Punk Introduction to Scala (20 min)

Presented at QueensJS Meetup, February 2018.

Abstract: Over the past few years, I’ve learned a lot about the functional programming language Scala, and grown to appreciate it. I’ve also come to truly embrace, rather than be embarrassed about, some of the music I enjoy. Scala doesn’t make me want to leave this town and run forever [1] -- let me explain some concepts of how it works, through 🎶the power of song🎶. You’ll leave this talk with a basic understanding of how to adapt functional patterns you may be familiar with from other languages into Scala idioms. ( [1] Yellowcard, Ocean Avenue)

Links: 
Spotify playlist containing all of the songs I excerpted (note, several songs contain profanity, use your best judgment): [https://open.spotify.com/user/precisememory/playlist/3NSMipHDzfs5Vb6Aubfpin](https://open.spotify.com/user/precisememory/playlist/3NSMipHDzfs5Vb6Aubfpin). 

Slides, with embedded autoplaying mp4 files, in .odp format (I made them in LibreOffice): [download]({{site.url}}{{site.baseurl}}/media/2018-02-07-pop-punk-scala.odp)

[Font for slides](http://www.fontspace.com/cloutierfontes/cf-rebelle)

### More than Binary: Inclusive Gender Collection and You (30-45 min)

Note from 2025: I'm no longer comfortable sharing the content of this talk widely, primarily due to changes in the political landscape since I initially wrote and presented it in 2016. 

Presented at PyCon, May 2016; Open Source Bridge, May 2016. Women in Open Source Camp at the UN, June 2016. 


### My favorite Unicode character: the zero width joiner! (20 min)

Presented at !!Con, May 2016.

My favorite Unicode character: the zero-width joiner!

Abstract: Some people have favorite numbers, and since character encodings are basically mappings from binary numbers to characters, I think it’s pretty much equivalent to say I have a favorite character! U+200D ZERO WIDTH JOINER (ZWJ) is used to combine separate characters, usually in Indic and Arabic scripts. In my life as an English speaker and writer, it’s used to make combinations of emoji, such as 👩+‍❤️‍+👩= 👩‍❤️‍👩. I’ll talk about how and why this works, and how it might affect the text that users submit and you display. (If the emoji in this abstract don’t combine into one image on the right, try viewing on a recently updated smartphone.)

[Script is here]({{site.url}}{{site.baseurl}}/media/bangbangcon.txt) and [slides, which display the images even if you don't have the correct font installed, are here]({{site.url}}{{site.baseurl}}/media/bangbangcon.pdf).

[You can install the EmojiOne font I used to create the slides here](https://github.com/eosrei/emojione-color-font).

[A list of all emoji ZWJ sequences out in the world, from the Unicode Consortium](http://unicode.org/emoji/charts/emoji-zwj-sequences.html)


### Divide and Conquer: Starting MergeSort, A Feminist Hackerspace In NYC (8 min)

Note from 2025: MergeSort no longer exists as of 2018 and these slides are in an annoying format, so I don't feel the need to share them. 

Presented at World Maker Faire, Queens NY, September 2015.
