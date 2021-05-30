---
layout: post
title: Hello World!
categories: general
published: true
---


Hello, and welcome to my personal blog. I'm **Jorge Moreno Palenzuela**, a software engineer who enjoys learning as much as I can (probably like you). I've worked on GMV and The Olympics, as a Data Science and Data Engineer, respectively, and during this time I've worked quite a lot with **AWS**, learning some really interesting things in the process.

Although I'm not creating this blog for publicity, marketing, or to blow up, I'm creating it for a selfish reason. When we learn something, especially if it's something difficult, we want to share it with more people. Both to help them, but also to help us to consolidate the knowledge. You probably have experience the same.

In most occasions, since my learning comes from the work in my company, I just use the new knowledge to implement whatever solution we need. That (and the posterior documentation of my work, handover to colleagues, etc.), is usually enough to fulfill this need of sharing the new knowledge. But it's not always an option.

That's the main reason to start this blog. In one hand, I'll help *me* by consolidating my new knowledge, documenting things I've learn so I can access them again in the future, etc. On the other hand, besides this post may appear a bit selfish up until now, you must know that I'll dedicate all my efforts while building this blog to try to help *you* to learn whatever you came here to learn. Not a single post nor paragraph will be written here if I don't see that it will help you learn and progress in a subject in the best way I can transmit. And, of course, any feedback for the improvement of any post will be greatly appreciated.

That said, hope you find something interesting in the blog and can have as much fun as I'll have writing them. I'll see you in the next post. Goodbye and have a happy life!

## The content

The main focus of this blog will be **AWS**. Over the years I've had to develop very interesting and useful solutions for which, surprisingly, I did not find a lot of posts or tutorials, so I had to end up combining several sources with a bit of initiative to arrive to them. In this blog, I'll try to condense all this research and explain it in the most simple and direct way as posible. I'll also do a small review of the basics so you can dive into AWS and implement these even if you don't have any experience yet.

Although I'll not be focusing on it, I'll end up talking a lot about **Python** as well. For some of these tutorials we would need some coding and, to be honest, Python is the programming language that I work most with, and due to its versatility, it will help us (obviously if I want to show how to deploy a Serverless website in AWS I'll use other languages or frameworks that are more suited, like JS and React).

We may at some point take a glance to other technologies (Docker, JS, ...), but only whenever they help us to build specific resources or applications in our cloud that could be interesting for us.

### Principles

Once said this, you must know that the **principles** I'll be following whenever a write a new entry (and therefore what you must expect from the tutorials) are the following:

- **Cloudformation**. I understand that at the beginning the AWS console may look like the easiest way to creating new resources (and it's nice to play and learn stuff) but for these tutorials I want to show the good way of deploying resources, how you would do it in a company, and I think Cloudformation (Infrastructure as code) is the way to go for this. Even if you intend to use the content for yourself and not for a company, I really think that you should learn how to use this. I promise that once you have practice with it, it's even easier than having to manually deploy everything from the console.
'
- **Serverless**. As far as I'm able, I will try to avoid running servers and hosting applications in them. Sometimes it won't be possible, but I think one of the main advantages of the Cloud (and AWS in particular) is that it allows you to build serverless applications for almost every use case you have. With them, you don't need to manage servers, you only pay for what you use, they scale pretty well, etc.

- **Security, scalability and availability.** I'll try that every new resource or integration that we deploy in our tutorials is compliant with the AWS pillars and best practices (as far as it's in my hand). If we are going to deploy our applications in the Cloud, let's benefit from it as much as we can.