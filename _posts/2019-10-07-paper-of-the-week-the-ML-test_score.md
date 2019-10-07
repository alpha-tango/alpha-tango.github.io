---
layout: post
tags: social
---

### Paper of the Week: "The ML Test Score: A Rubric for ML Production Readiness and Technical Debt Reduction"

![ML-Based system testing and monitoring](/images/66335789-5c0b6300-e901-11e9-8fd7-a0ed90dc0350.png){:width="300px"}
![Average ML test scores for interviewed teams](/images/66335730-39794a00-e901-11e9-8577-69c476a24c65.png){:width="300px"}

How do you know if your ML system has enough tests? Has the right tests? Are you confident in your model and your pipeline? The authors of this paper, who are all Google employees, are proposing a rubic to tell if your ML tests are good enough.
ML tests aren't the same as normal software tests, since they need to cover the input data and because testing the behavior of the model is hard when you don't know what the model will behave like!
The authors propose four groups of tests: data tests (testing your input data), model development tests (ensuring your model is effective and has the impact you want), infrastructure tests (testing the pipeline and ensuring models can be rolled back), and monitoring tests (make sure the model isn't stale, and that dependency changes throw alerts). 

I'll definitely be implementing some of these tests for my next project. I recommend checking out the paper, which you can read [here](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/aad9f93b86b7addfea4c419b9100c6cdd26cacea.pdf)
Shout out to Austin #WiDS, who chose this paper for their paper discussion group!

