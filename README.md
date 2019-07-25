# Introduction

Reddit is a popular online discussion board where people can create groups, commonly known as 'subreddits', to chat and share content with like-minded people around the world. 

In this project, we will be looking at how we can use machine learning to make an attempt in trying to predict sentiments, more specifically sarcasm/humour/irony.

## Is that legit or... do I smell sarcasm?

Natural Language Processing (NLP) has been one of the longest running computing science fields, starting all the way back from the 1950s with Alan Turing's infamous Turing test - where a machine is said to pass the test if an evaluator cannot tell, behind the scenes, who is the one truly answering a posed question: Machine? or human?

Whilst it sounds like a rather trivial scenario, many decades on we've still yet to truly crack the language code, something that befuddles even the best of us mere humans. That is not to say we've made little progress - we've come far enough to now have chatbots being able to understand, guide, and assist us in services such as product support centres, as well as the more advanced voice assistants residing in each and every smartphone being made today.

Language, however, is not something static. It's not just a mere tool for simple communication. Language is a dynamic, fluid entity that can be moulded to resemble something, but yet truly mean something else. Things like humour, irony, and sarcasm can be complex and at times, thought-intensive to decipher, let alone create.

id|title|author|score
-|-|-|-
chpnge|If the two European heatwaves this year were...|Asian_Canadaball|1
cho8v8|Who invented being gay?|TigerpanzerIV|2
chmghz|Why did gravity ignore this bird?|zlicht|0


## Requirements

* PRAW
* Sklearn
* Tensorflow
* Keras
* XGBoost
* SpaCy (with 'en_core_web_lg')
