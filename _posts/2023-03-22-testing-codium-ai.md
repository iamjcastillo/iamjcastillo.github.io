---
layout: post
title: Testing Codium AI
subtitle: Can it help you refactor? 
tags: [software development, refactoring, coding katas, Codium AI]
comments: true
cover-img: https://media.licdn.com/dms/image/sync/D4E27AQFxq2fD6Ec0Zg/articleshare-shrink_800/0/1679536061167?e=1680562800&v=beta&t=-A26Cd8eOIVqN3CnD8eWqdlvPWHnSj9PiG0-1NAx0js
---

Have you ever found yourself needing to refactor legacy code, but just don't having the time or resources to test every possible scenario? As a developer, I know firsthand the importance of thorough testing when it comes to refactoring legacy code. That's why I'm excited to try out **Codium AI**, a tool that promises helping to generate test which can be used as a safety net for refactoring legacy code, without requiring an excessive amount of time or effort.

To put it to the test, I've decided to use Codium AI against the Gilded Rose Kata, a classic coding challenge that involves updating an inventory management system. I'm curious to see just how effective Codium AI can be in generating the tests I need to ensure my changes are safe and reliable.

If you're interested in giving Codium AI a try, you can check out the extension for yourself on their website: **[https://codium.ai](https://codium.ai/).** I'll be using it in combination with my go-to code editor, Visual Studio Code. The Codium AI extension for VS Code promises to make generating tests even easier, and I'm looking forward to seeing how this integration can help streamline my workflow.

### The experiment

I decided to undertake a practical exercise utilizing the renowned Gilded Rose kata, which may be accessed via the following link: [https://github.com/matthewmorgan/gilded-rose-python-with-tests](https://github.com/matthewmorgan/gilded-rose-python-with-tests) 

In order to initiate this exercise, I established the repository and subsequently utilized Codium AI to generate the first tests. This tool offers a variety of options for configuring the testing process, although I ultimately opted to proceed with the default settings.

![1](/assets/img/codium_ai/c1.JPG){: .mx-auto.d-block :}

I was surprised by the initial results, as out of the first six tests that the tool generated, only one exhibited a failure. To be honest, my expectations were more reserved and I had anticipated a comparatively poorer performance.

![2](/assets/img/codium_ai/c2.JPG){: .mx-auto.d-block :}

After conducting a few more tests, I made the decision to maintain only the successful tests, in order to check the code coverage.

![3](/assets/img/codium_ai/c3.JPG){: .mx-auto.d-block :}

As evidenced by the image above, the initial results were quite promising. With a mere four tests, a substantial proportion of the code's lines were covered. Encouraged by this outcome, I continued incorporating additional tests in order to determine if achieving a full coverage was feasible. The resulting improvement in coverage can be observed below.

![4](/assets/img/codium_ai/c4.JPG){: .mx-auto.d-block :}

Throughout the course of this process, I made an interesting observation. Specifically, I noted that the tool continued to encounter difficulties with certain tests. Despite attempting to rectify this by deleting and subsequently regenerating the tests, the tool was ultimately unable to achieve the desired outcome. 

![5](/assets/img/codium_ai/c5.JPG){: .mx-auto.d-block :}


### Afterthoughts 

Overall, I must say that the experience of using Codium AI to generate tests for legacy code was both enjoyable and informative. While the tool certainly had its limitations and encountered difficulties with certain tests, I appreciated the fact that some configuration options were available to help tailor the tests to my specific needs.

In conclusion, I believe that Codium AI has the potential to bring significant benefits to developers seeking to streamline their testing processes and save time and effort when refactoring legacy code. While it may fall short in some respects, the tool's ability to generate a "safety net" of tests quickly and easily is certainly an attractive prospect. I look forward to continuing to explore the possibilities offered by Codium AI and other tools like it as I strive to optimize my development workflows.