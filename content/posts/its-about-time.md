---
title: "It's About Time"
date: 2022-05-07T09:56:00-04:00
draft: false
summary: "An interesting question that gets passed around is how to measure the success of automation. One popular answer is by the number of bugs that are found in automation. Sure, by running automation scripts we will occasionaly find bugs, but that isn't why we should do it. We should invest in automation to save time."
---
Since working in tech, I have seen more metrics than I would ever like to see. Anything from a chart in a slide deck to an over engineered Jira dashboard; I have seen it. An observation I have made is that tech *loves* their metrics. This poses an interesting problem for quality engineers because there are some exercises and processes that do not generate a datapoint that be accurately tracked. Automation is one of them.

*BUT WAIT!* We can track automation by the number of bugs automation scripts find!

Yes we can, however, automation normally enters the development life cycle for features that are relatively stable. Automation is leveraged to execute regression test cases. Traditionally, regression test plans should not find too much. (If you are trying to build a feature that seems to break everything around it, a new strategy may be necessary.)