---
layout: essay
type: essay
title: "Want to Get Better Answers? Use Smart Questions!"
# All dates must be YYYY-MM-DD format!
date: 2025-01-30
published: true
labels:
  - Stack Overflow
  - Smart Questions
---
<img src="../img/essays/DogQuestion.jpg">

*"A prudent question is one-half of wisdom."* – Francis Bacon

## Why Smart Questions

A smart question is the most effective way to gain knowledge about something that isn’t easily learned. It is an essential skill in both problem-solving and learning. In Eric Raymond’s How to Ask Questions the Smart Way, he emphasizes that well-structured questions are more likely to receive helpful and insightful answers. Asking a question is more than just requesting information, it requires effort, clarity, and structure. To explore this concept, let's examine two questions posted on Stack Overflow: one that exemplifies a well-asked question and another that demonstrates poor question-asking practices.

## Example 1: The Smart Question

An example of a smart question is titled, [Why is subtracting these two epoch-milli Times (in year 1927) giving a strange result?](https://stackoverflow.com/questions/6841333/why-is-subtracting-these-two-epoch-milli-times-in-year-1927-giving-a-strange-r) 
The user presents a concise yet descriptive title that immediately captures the essence of the issue. Giving many details such as the test case "1927-12-31 23:54;08" - “1927-12-31 23:54;07", with an expected output of “1”, and the actual output “353”. And how shifting the time 1 second forward would give the expected time normally. Along with the most important code snippets that influences the calculation and result.

```
Timezone(`TimeZone.getDefault()`):

sun.util.calendar.ZoneInfo[id="Asia/Shanghai",
offset=28800000,dstSavings=0,
useDaylight=false,
transitions=19,
lastRule=null]

Locale(Locale.getDefault()): zh_CN

```

This gives people analyzing the problem a clue to what has gone wrong and could instantly filter out many things like the Parse was incorrect or the date time was not formatted correctly. Pointing out the problem instantly that, despite looking like these two datetimes are only 1 second off, the calculations instead return 353.
Responses to this question were insightful, revealing that the discrepancy was due to historical time zone adjustments. In 1927, Shanghai's local time changed by 5 minutes and 52 seconds, accounting for the surprising result. This question was quickly answered and revealed a lot of knowledge about both the way Java computes time and historical anomalies.

## The “Dumb” Question

In contrast, the question titled [“Not Returning the Right Value”](https://stackoverflow.com/questions/26141822/not-returning-the-correct-value) reflects the problems of poorly asked questions. The post simply states that the output of the returnGpa function is always 0.0. In the question, the title is vague, it lacks meaningful details or any description of the problem. Such as why, what function is expected to set the Gpa, did anything go wrong with that? The user simply passed the whole program into the post and stated it wasn’t working, and that supposedly “everything else works”. It does not demonstrate any attempts of the developer trying to debug the problem on their own, but just simply asking for answers when running into a problem.

The problem itself also, was extremely simple. And thankfully, a user helped and pointed out that the setGpa function doesn’t save the gpa to any instance variables in the object. So returning the Gpa would always return the default value of 0. Which could have been easily found with a tiny bit of debugging, one of the key points to a smart question, giving test cases that reflect the problem, and trying to find the root of the problem.

## Comparison

The key difference between a smart and a dumb question lies in the information it conveys. A smart question includes key details like sample code, test cases, and uses those test cases to form a clear, focused question. For example: *"Why is there a 353-second difference when changing just one second?"* In contrast, a dumb question simply asks why something isn’t working, without providing much context or detail. Worst of all, it shows a lack of effort from the poster; they haven’t tried to solve the problem themselves, let alone identify its potential cause. A smart question is crafted thoughtfully, and even if the solution is simple, solving it still provides a valuable learning experience for the poster.


## Reflection

Through these examples, it is clear that smart questions, characterized by specifically, clarity, and a reflection of effort and willingness to learn that came from the poster, encourage more valuable discussions and lead to efficient solutions. While poorly framed questions usually have no value, reflecting the poster’s lack of effort, and resulting in minimal engagement. By framing our questions smartly, we not only solve our own problems, but also create enticing conversations and exchangement of knowledge. We learn more if we really know what we are asking, and what we are asking for.


- ChatGPT is used to assist in writing this essay only in word choice, spelling, and grammar.


