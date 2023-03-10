---
layout: post
title: Pair programming with ChatGPT
subtitle: Can it solve a coding kata? 
tags: [tdd, software development, test driven development, pair programming, coding katas, ChatGPT]
comments: true
thumbnail-img: https://techcrunch.com/wp-content/uploads/2019/03/lp-logo-3.jpg?resize=1200,812
cover-img: https://static.vecteezy.com/system/resources/previews/017/546/156/original/chatgpt-ai-artificial-intelligence-technology-hitech-concept-chat-gpt-with-smart-bot-open-ai-line-lights-technology-abstract-design-for-chat-web-banner-background-transformation-vector.jpg
---

As a software developer, I firmly believe that practicing coding katas can greatly enhance our skills in Test-Driven Development (TDD). It's a fantastic way to improve our ability to write clean, efficient, and maintainable code while following the principles of TDD.

Moreover, I'm a big fan of pair programming, where two developers collaborate on a task while working together on the same computer. I find that pair programming can be a powerful way to enhance our overall development skills and produce higher-quality code.

Recently, as an experiment, I decided to take my skills to the next level and engage in a coding kata with ChatGPT using the ping-pong pair programming technique. In this post, I'd like to share my experience with this unique form of collaboration and how it helped me sharpen my skills in TDD, coding, and pair programming.



### The experiment

I decided to practice using the well-known [Leap Year kata](https://www.codurance.com/katalyst/leap-year). To get things going, I created the first test following the Arrange-Act-Assert pattern. Next, I feed the code to ChatGPT.

![1](/assets/img/pair_programming_chatgpt/1.png){: .mx-auto.d-block :}

I was surprised to see the first results. As this is a well-known coding kata in the community, ChatGPT was able to infer the **whole** solution.

![2](/assets/img/pair_programming_chatgpt/2.png){: .mx-auto.d-block :}

At this point, I tried to enoforce ChatGPT to follow TDD principles by getting **only** the necessary code.

![3](/assets/img/pair_programming_chatgpt/3.png){: .mx-auto.d-block :}

Apparently, that made the trick but, as soon as I entered the next test, it provided me with the whole solution again.

![4](/assets/img/pair_programming_chatgpt/4.png){: .mx-auto.d-block :}

![5](/assets/img/pair_programming_chatgpt/5.png){: .mx-auto.d-block :}

At this point, I didn't see the point on continuing with this approach so I tried a different one. I always try to use meaningful names on my code, but maybe this time it was giving too many clues to ChatGPT. I tried hiding the intention of the code by giving the test a more opaque naming.

![6](/assets/img/pair_programming_chatgpt/6.png){: .mx-auto.d-block :}

The new approach worked well for the couple first iterations and the results were a bit more promising (bearing in mind that my intention was to follow TDD principles).  

![7](/assets/img/pair_programming_chatgpt/7.png){: .mx-auto.d-block :}

Later on, it didn't come as a surprise that, after the third iteration, the model was able to get the full solution again. 

![8](/assets/img/pair_programming_chatgpt/8.png){: .mx-auto.d-block :}



### Afterthoughts 

In conclusion, the experiment with ChatGPT was a fun and unique experience that allowed me to practice coding katas in a different way. It was an good opportunity to test my skills in TDD, coding, and pair programming while also exploring the capabilities and limitations of a language model like ChatGPT.

I found the exercise to be very productive in terms of improving my skills while also providing an opportunity to collaborate with an AI language model. It was a great way to sharpen my skills while still being able to experiment with ChatGPT's capabilities.

Overall, I recommend trying out pair programming and coding katas with a language model like ChatGPT, as it can be an excellent way to enhance your skills as a developer and explore new possibilities in AI-assisted development.