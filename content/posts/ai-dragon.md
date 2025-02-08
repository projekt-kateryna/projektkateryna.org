---
title: "Saving the world by feeding the Al Dragon with unbiased open data" 
date: 2024-02-06T08:00:00+03:00
draft: false
url: "/saving-world-with-ai-dragon"
author: "Kaj"
categories: 
  - "presentation"
images: ["/images/ai-dragon.png"]
showimage: false
_build:
  list: false
  publishResources: true
  render: true
---

Talk given by Kaj Arnö on 4 February 2025 at the State of Open Conference 25 (SOOCon) in London.

# Saving the world by feeding the Al Dragon with unbiased open data
{{< youtube b1uJsIhAk-4 >}}

* Webinar recording on youtube: https://youtu.be/b1uJsIhAk-4
* Slides: https://docs.google.com/presentation/d/1Op1JVgcYdjRPgUCJEVtdK5Cp7c8PsDhSGE0d7rt4-5k/edit#slide=id.p1

## Intro given

Okay, welcome back everyone to the Open Data Track. As a reminder, this is the Open Data Track. If you're expecting AI, open source, or an entirely different conference, you're in the wrong place. But if you are here for open data, then you are definitely in the right place. 

We have an amazing talk from a fantastic speaker coming up. This is Saving the World by Feeding the AI Dragon with Unbiased Open Data, a subject which I am sure we're all incredibly interested in. Please give a very warm round of applause to Kaj. 

2: Indeed, my goal is to save the world by feeding the AI dragon with unbiased open data. I'm Kaj Arnö, and I'm the CEO of MariaDB Foundation. And I've worked with free and open source software all of this century, and in that process I've become convinced that openness is a powerful force for good, also when it comes to open data. So I'm a dual citizen of both Finland, my native Finland, and Germany, and in that process I've noted that Finland isn't properly, or hasn't properly been represented in open data. Finland is a country with two languages, and I noted, that Swedish Finland hasn't been sufficiently described. You might know Swedish Finland by two of its representatives, Linus Torvalds, the father of Linux, and Alexander Stubb, our current president. And I founded a project to fix this in 2017 called Projekt Fredrika. And that has given the background for the much larger scope of not just saving little Swedish Finland, but saving the world. 

3: As for MariaDB, it's an open source relational database management system, and that's the reason why I am at Open UK. But for the purposes of this presentation, there's only three things I'd like you to know about MariaDB. I think it's fair to portray it as the future of MySQL. Second, it has the infrastructure needed for AI, AI in the form of vector. The most prolific use case there is to create RAG applications, which means that the large language models are answering the questions, not based on its general training data, but on the specific data you've provided as the creator of that application. And third, MariaDB is the database used by Wikipedia. But now for saving the world. 

4: The 24th of February, three years ago, took the world by surprise. It shouldn't have. With hindsight, we had all the foresight needed to have prevented that happening in the Ukraine. And this foresight we should have had for centuries and at least decades, but it's not as if we didn't get alarm bells ringing. 

5: So one of the first alarm bells was in 2008, when Georgia was attacked by Russia. Well, that's sort of far away. And have you been to Georgia? I don't know where it is. Perhaps it's not important. There were few exceptions to the general attitude, which was, ah, these alarm bells are not important. And one of those exceptions happened to be Finland's then foreign secretary, Alexander Stubb. Now our president. 

6: There were other alarm bells in 2013 in the Ukraine. In Ukraine, Euromaidan should have been a lesson for all of us who didn't do our homework when learning about the history of Ukraine to see that they consider themselves to be part of Europe. We didn't do our homework. And then in 2014, when little green men came to Crimea, the alarm bells still stayed too silent, and Angela Merkel played the role of Neville Chamberlain, trying to appease dictatorship by presuming that common good would be a priority for them. It wasn't. 

7: So in 2022, the armrests then really did go off, but very late and very slowly and very partially. The reason for this is our, our lack of understanding of history through three centuries of successful portrayal of Ukraine as a non-country, non-language, non-culture. It's probably Russia, isn't it? It's outside the general education in Western Europe. 

8: My two central claims for this is that, in hindsight, had the West reacted properly when the alarm bells should have gone off in 2008 and 2014, there wouldn't have been a full-out war in 2022. And this is not much of a hindsight. It is not a question of had we known then what we know now. It is a question of had we used then what we really should have known, had the past been known, and part of the general education, we would have reacted properly. 

9: With the end outcome that military expenditure by the West is now in the hundreds of billions of whatever currency units, not to speak of a million human lives. But, tell you what, history isn't over yet. This isn't the last time when such things can happen. Foresight is still needed. 

10: History is always written by the victors, and those of you with A, good eyesight, and B, very good knowledge of geography, will notice that this picture, which is uploaded to Wikimedia, is portraying Crimea as a part of Russia. Let's hope that victory doesn't happen. 

11: It's a very different situation if you look at how Finland is portrayed on Wikipedia and Ukraine. So if you look at nationalism, in Finland it's something where we sort of pat ourselves on the shoulder, regardless of which language we're portrayed in. It's national awakening. It's the Russian eagle that tries to rob us of rule of law. And we have great poets and great composers, painters, and we did honorable resistance. against Russia in the 19th century. In the Ukraine, well, they had nationalism too, but that was pogroms, and it was the root of Nazism and violence and lots of dissonance. Yet it's the same history. It's the same type of thing that happened in Ukraine and in Finland, only we didn't lose, they did. Most Ukrainians are classified as Russians. I am happy to note that no Finns of that era are classified as Russians. 

12: The way to correct this is cultural self-defense at less than 0.1% of the cost of the military expense now to fix stuff that we screwed up. And I still remind you that history is not over yet. And this is a Project Kateryna, named after a painting by Taras Shevchenko, which is trying to rectify things by, and this is an expression, decolonization of Ukrainian history in Wikipedia. 

13: So examples of this. Wikipedia has partial truths. It's not blatant lies. And those of you very interested in history might know that there's a guy called Ivan Mazepa who sided with us, being the Nordics, the Scandinavians, in Poltava, 1709. Well, it's still being fought over in Ukraine, whether he betrayed Russia or whether his colleagues betrayed Ukraine by siding with Sweden. In 1709. And that needs to be portrayed properly. There's a lack of nuance in how things are portrayed. 

14: Here there's a picture also from Wikipedia Foundation about a Viking named Rurik, who was the person who founded in 1870. Well, what exactly did he found? Was it Russia? Was it Kiev? Was it Ukraine? And these things are a form of propaganda by a thousand cuts, because it's not a question of fixing one thing, it's all of the things how Ukraine, in this case, is portrayed on Wikipedia.

15: The consequence of not portraying it properly, by copying how the Russians have depicted Ukraine over the centuries, is what happened in 2008 and 2014. It's the lazy truth. Those who really should be the most educated people in politics, in journalism, they go to the place where they believe that the truth exists, which would then have been Wikipedia, and now is AI. And if Wikipedia mainly provides partial truth, how can neutral point of view prevail? 

16: The solution, though, there is a solution, and that is the title of this presentation, To Feed the AI Dragon. The good news is that we can influence open data, Wikipedia, Wikidata. And they have a goal of a neutral point of view. The value here is the credibility by Wikipedia and Wikidata, and the accessibility of it. There's a platform for it. And it is one of the best sources of training data for AI. So just go fix it. 

17: We have nearly all the infrastructure. We have the universities and scholars providing this truth, or neutral point of view. Here, the very good authority on this is Timothy Snyder, a professor at Yale. And the technology exists. So Wikipedia exists. Vector databases exist. AI, retrieval augmented generation. We have Python scripts. So what is missing? Well, what's missing is that the collective West, to use an expression favored in Russia, is missing an institution with the task to feed this AI dragon with neutral point of view. And to provide a vaccine against the propaganda that exists all across the partial truth by curating neutral point of view data into Wikipedia. 

18: I think such an institution should be named after Denis Diderot, who's the guy who originated the concept of an encyclopedia. The question then would be, who should be this organization? Where should it be? Should it be in your wonderful country here in the UK? I think you have a good track record of influencing world history, or at least attempting at it, and you were one of the first to realize what was happening in Kiev in Ukraine in 2022. I think EU very much has it as its interest for this to happen. Otherwise, the old adage about first they came for the communists. I'm not one, so I didn't do anything. Then they came for the homosexuals. Well, I'm not one, so I didn't do anything about it. Then they came for the Jews. Well, I'm not a Jew, so I didn't do anything about it. That will happen. It will not stop at Ukraine. The US hopefully should have this as their self-interest. And even because this is a question of cultural self-defense, I would imagine that even an organization of the type of NATO should have it as its interest. 

19: So my call to arms, call to action for you is, please help me navigate the collective West to find and to found and to fund the appropriate institution for this. Thank you. We have time for questions. 

So what should we do when the AI dragon gives us results we do not like?

We cannot control how these AI dragons are exactly being fed. But what we can do is we can do exactly what I'm proposing here, is feeding it with proper open data. And I think most organizations that train their dragons are only thankful for the credibility and the curation done by Wikimedia organizations. So we can exactly do what I'm proposing here, feeding it with knowledge, non-propaganda. 

What are the practical steps that anybody in this room can do to help me organize this? 

Is to identify those people who have either plentiful money or connections to the organizations in which interest this really should be, to connect us with them. I think this is an interest of society at large, at least the freedom, free liberal West should be interested in this. And I think it should be self-evident. I am searching for the right people to talk to. So if you know about whom I should be talking to, please use the email address on the LinkedIn there and help by connecting. 

So the question is how do we define neutral point of view? 

And my happy answer is I don't have to. Wikimedia Foundation has already defined this and Wikipedia already has a mechanism for mediating between how things are being described. There is a mechanism that has been in place for describing Israel and Palestine for years and the equilibrium has been found. So that's a problem that is sort of already solved and outside the scope of this. So we just need to feed the neutral point of view information. And if we feed it with something that isn't neutral, we will be reprimanded and it will not stay in Wikipedia. So there is this control mechanism. 

Thank you. That was an absolutely fantastic talk. 
