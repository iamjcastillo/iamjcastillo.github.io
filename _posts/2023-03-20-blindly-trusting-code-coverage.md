---
layout: post
title: Code coverage
subtitle: And the risks behind blindly trusting it
tags: [code coverage,  unit testing,  software quality,  software development]
comments: true
---

Code coverage is a metric that measures how much of your codebase is exercised by your tests. While increasing code coverage can lead to a culture of engineering excellence and reduce defects in the long run, relying solely on code coverage might be misleading as argued by the following article.

Developers may focus on increasing code coverage without ensuring that their tests are effective and meaningful. As the article [Unit Testing Fraud: Why Code Coverage is a Lie](https://daily.dev/blog/unit-testing-fraud-why-code-coverage-is-a-lie) shows, a codebase with high code coverage can still have critical defects, which means that code coverage alone is not a guarantee of quality. In fact, efforts to increase code coverage could be even wasteful, creating technical debt from low-value tests that need to be maintained.

Code coverage should not be used as the sole metric for evaluating the quality of unit tests. Instead, developers should focus on writing tests that provide meaningful coverage and effectively catch defects. This means identifying critical areas of the codebase and designing tests that cover those areas in a meaningful way.



 

