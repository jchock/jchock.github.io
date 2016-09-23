---
layout: essay
type: essay
title: Coding According to Standards
date: 2016-09-22
labels:
  - Software Engineering
---

## History of Coding Standards

Prior to learning about ESLint and coding standards in general, I always tried to make my code as readable as possible. Whether I was coding in C/C++ or in something like Matlab, I strived to make it as easy as possible for anyone to be able to understand my code. I was never really taught a name for this practice except the term "style" that was stressed highly in my C programming course. To the professor, good "style" meant having code that was properly organized and well documented, with functions that made sense and macros to define recurring values that had a meaning. For example, if a program to calculate a car's average gas mileage was to be written, a macro such as TANK_CAPACITY might be used to represent how many gallons of gas a car could carry. While I haven't used this practice in JavaScript, the proper organization of code has stuck with me. Thanks to ESLint, ensuring everything is organized properly has become an easy task that I no longer need to do on my own.

## Impressions of ESLint

When I first started using ESLint, I found myself not needing to modify much about my code or the way I write code since I'm used to writing code that's well organized. However, I sometimes miss a space between a "if" statement and the following conditional statement in parentheses. ESLint catches this and provides me with feedback to correct it. For some, correcting all of these issues to get a green checkmark may be bothersome, but I find that it helps me keep my code organized and allows me to write code with better "style". In fact, it's convenient to have ESLint assist me with my coding practices and I appreciate how picky it is. In the past, I would be looking over my code over and over to make sure my code was consistent in terms of organization. If I had a space between an operand and its corresponding operators, I would need to make sure the spacing showed up in all of my code. Now, with ESLint, I don't need to look over my code multiple times because ESLint does it for me and marks where I have issues. On top of organizational remarks, ESLint also provides feedback on syntax errors, much like a C/C++ compiler would. With the green checkmark, I know that my code is free of syntax errors and from there, I only need to worry about runtime errors.

## Final Thoughts

ESLint is a great tool to have while coding in JavaScript because it provides users with a coding standard to follow. In the end, this not only helps the programmer write correct, well formatted code, but it also allows others who follow the same standard to be on the same page as the person writing the code. They won't need to line up the curly braces and indentations with their eyes to determine where a block of code begins and ends. Furthermore, others who read the code will still be able to follow along relatively easily due to the fact that the code is consistent throughout. To me, seeing the green checkmark is like having a successful compilation when coding in C/C++. It's a great feeling to know that you've made it far enough to test your code and that your program is free of syntax bugs. 



