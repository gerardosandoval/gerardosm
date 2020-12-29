---
layout: post
title: Code-Review culture does matter
published: true
description: Having a great code review culture can boost your deliverance
tags: codereview, deliverance
permalink: /blog/code-review-culture-does-matter
---
# Code-Review culture does matter.

Some time ago I found myself working for a company with great social and professional culture, working there felt great, but... it didn't last long.

I realized that there were some organizational issues that were impacting greatly on the engineering team performance:
  - Definition of responsibilities was lacking
  - Devs were mainly working alone with poor team communication
  - Only few development standards and practices were set.

Among those issues, I was always struggling with an specific problem: getting my PR's reviewed, approved and merged.

Deliverance was so slow that some PR's were stuck in the _in review_ column for more than a month, those developments were a lost couse, outdated and with several conflicts, more work was needed to update them that the work needed to develop them in the first place.

  I found myself working in a startup with a very poor code-review culture.

After reading and investigating a while I found that there are some practices that can be adopted to strengthen your code review culture, boost deliverance and build a better team. The next practices are based on a talk by Derek Prior [(link)](https://www.youtube.com/watch?v=PJjmw9TRB7s) and some other readings.


### ¿How to prepare for and improve your code review culture?
- As a team, decide your process and what to expect of reviews and make responsibilities clear:
  - Number of reviews before merging
  - Who can merge?
  - Can I merge my own PR?
  - How should I ask for review?
  - Who and why should be reviewing my code?
- Take in mind that code review does not include QA
- Adopt a styleguide and outsource it

### ¿What are the benefits of a strong code review culture?
- Better code - quality discussions improve code quality
- Better developers - Conflict are good for learning, in a healthy way
- Team ownership - Remove modular dependencies and win developer's versatility
- Healthy debate - More meaningful technical discussions in a proactive culture
- A better place to work

### Rules of Engagement

##### ¿What to do as an author?
- Provide sufficient context. Explain your changes and avoid context hunting. _If content is king, then context is God (Gary Vaynerchuk)._
- Explain why you chose that solutions, not everyone thinks like you.
- ¿You learned something new and useful? Document it! It can help others.

##### ¿What to do as a reviewer?
- Ask, don't tell. Write your observations as a question instead of demanding a change. Asking the right questions the right way results in a better technical discussion.
- Offer compliments and be positive. Comment the code that you find useful and of quality with a compliment.

### In practice

##### ¿How to handle disagreements?
  - Agree to disagree. There's different ways to get things done.
  - Create a discussion and be open to new alternatives. If you don’t know which is better, ask.
  - Ask for a tie breaker opinion.

##### ¿What should I be reviewing anyway?
  - Single responsibility principle
  - Naming, easier to understand and discuss
  - Complexity
  - Test Coverage
  - Look for bugs involving your area of expertise

---

###### Interested? Read these articles for more tips and information:

https://www.youtube.com/watch?v=PJjmw9TRB7s
https://thoughtbot.com/blog/five-tips-for-more-helpful-code-reviews
https://chelseatroy.com/2019/12/18/reviewing-pull-requests/
