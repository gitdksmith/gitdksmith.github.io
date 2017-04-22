---
layout: post
title: Recap Week of August 23rd
---

###Tip of the Week
This is shamelessly stolen from a piazza post by Jesse Mao and En-Hsu Yen, but I was intrigued about the difference between an assertion and an exception. The most useful point I took from an answer in the stackoverflow link was that “exceptions address the robustness of your application while assertions address its correctness.” In other words, use exceptions to deal with user input where you might have incorrect input but should be able to recover from it, and use assertions to test something that should always be true. 
