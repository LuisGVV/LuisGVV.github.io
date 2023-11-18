---
title:  "A year of using ChatGPT"
layout: post
date:  2023-11-18 4:50:43 -0600
categories: AI ChatGPT coding
---

It's been almost a year since the text generation AI boom caused by ChatGPT. It astonished everyone in the tech world with how accurate it can be and the funny use cases. However the main use in your job is where you will get most value out of it in your life.

For non-tech users I've heard them say it makes their job easier and that they're more productive. As a developer I think there are some days when I rely on it to perform annoying or repetitive tasks, but to be honest I can't tell you that it has made me a 10x programmer, or even twice the productive.

Here are 3 examples of how I've been using it:

### 1. Unit testing
Creating stubs and mocked data is way easier with ChatGPT than relying on some weird libraries that abstract your data models and generate test data. Most of the time you don't need to test all of the possible range values for a given test case, so you just feed ChatGPT your class/object sample and it will generate data easily in the format you wish.

If you're using C# one cool thing to do is generate the Moq classes that you will use in your unit tests. Through prompting you can tell ChatGPT if you want certain fields to be null, create spies for your methods and stubs

> Note: if you're using the free version sometimes the response will be cut off because of the output token limit, so you'll be better if you're a paid user

### 2. Writing database queries
Whenever I'm feeling a little bit lazy or if I forget how to perform some specific query I'll just feed into ChatGPT the database schema and then tell it which pieces of data I need.

The most I've been using it is for MongoDB as it is really awesome to generate scripts that insert mock data and navigate around the quirkiness of writing filters if you're not used to writing them by hand.

> Again you should be aware that the input and output token limit can bite you if you're feeding a huge chunk of code.

### 3. Search engine replacement
Of course everyone has tried using it as a replacement for Google and it comes close if not better 99% of the times. From time to time I'll find myself asking ChatGPT questions that you would typically find answers in forums such as Stack Overflow, this is where I think when it works you're simply blown away by how cool is it to have your own AI assistant correct you or point you towards the correct direction. However you 

### Conclusion
If someone reads this probably they will say that I'm missing a lot which is probably true, so please let me know what else can you use ChatGPT into your day to day work and into your workflows. As for me, it hasn't been the case where I think it's been a huge boost.


