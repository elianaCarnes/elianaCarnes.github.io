---
layout: essay
type: essay
title: "Asking Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2025-01-30
published: false
labels:
  - Asking questions
---

# What is Stack Overflow?
Stack Overflow was established in 2008 by Jeff Atwood and Joel Spolsky. This community-based forum is one of the highest-quality places for software developers to ask questions. Over the years, the site has grown to have 14 million registered users. It has an upvote/downvote system that allows users to find good-quality threads that share both helpful questions and answers. But what does it mean to ask a good-quality question?

<img width="300px" class="rounded float-start pe-4" src="https://www.zdnet.com/a/img/resize/fc7b8d4b1f4b34862881ebf41dec855600480098/2022/08/01/71433421-11f6-4ee9-97d5-3249e8457842/stack-overflow-logo-crop-for-twitter.jpg?auto=webp&width=1280">

# Asking SMART questions
According to Eric Raymond in his essay [*"How to Ask Questions the Smart Way"*](http://www.catb.org/esr/faqs/smart-questions.html), there are ways to ask questions more effectively, like formatting your subject line in an "Object - Deviation" format. This allows people to clearly see your issue at first glance. Through a clear subject line, you may catch the attention of the person who knows the solution. He also explains the importance of research and context within the body of your question. Providing proper context with your question saves others time when they try to respond. It is also important to provide an example of your code that clearly demonstrates the issue presented. A person should also conduct themselves in a specific way when answering questions. It is most efficient to be clear and polite but to always avoid unnecessary details and not seem urgent or frustrated in your post. When behaving in this manner, it is most likely you will receive a helpful reply.

# Examples
Take a look at these two examples, both asking questions about arrays in Java on Stack Overflow

The first example asks [Why is processing a sorted array faster than processing an unsorted array?](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array). In the body of the question, they have two pieces of code, each timed for how long it takes to execute. The first piece of code processes a sorted array, which logically should take more time, but as the user shows, it actually takes longer for the unsorted array to be processed than the sorted one. They talk about their initial thoughts about the data being moved into the cache during sorting, but ultimately ask why this is happening by restating the question in the title: Why is processing a sorted array faster than processing an unsorted array?

When asking their question, this user provided example code, multiple tests to show their point, and used a concise and professional manner of typing. Because of the additional steps this user took to ask a smart question, they received insightful responses that were deeply informative. Ultimately, the community found that the reason the sorted array was faster depended on the compiler. In the comments, the most helpful response was upvoted 144 times, allowing others with a similar question to quickly see the response. This is an example of a user that asked a smart question, and as a result, they were able to solve their problem and help others who had similar issues. 

In comparison, another user asks [I am trying to figure out why my code is not working](https://stackoverflow.com/questions/62227709/i-am-trying-to-figure-out-why-my-code-is-not-working). Unlike the previous post, the title of this post is very vague and gives no insight into what the question is about. This resulted in the post getting much less response from other Stack Overflow users. In the body, the user gives some insight into their question. They write about how their string array will not print, even when they do not see any syntax errors. They also attach a screenshot of the code. Using an image is not ideal, as others cannot easily copy and paste the program to test and see if they result in the same error. By not formatting their post according to the smart guidelines, this user had a less beneficial experience. 

Unlike the previous example, this post did not get many views and only has two replies with a few upvotes. The replies still answer the user’s question, leading them to the conflicting names of the class Arrays and the imported library java.util.Arrays. 

While both users had their questions answered, the first post led to an informative reply, while the second person only received a brief sentence explaining the error. These two examples illustrate the importance of asking smart questions in the field of software engineering.
