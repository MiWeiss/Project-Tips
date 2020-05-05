## What should I do if there's a bug I cannot identify?
Do not panic. This is absolutely normal:

    75% of a developer’s time is spent on debugging (1500 hours a year!) 
   
Source: [This Article](https://coralogix.com/log-analytics-blog/this-is-what-your-developers-are-doing-75-of-the-time-and-this-is-the-cost-you-pay/)

#### So what can I do to identify bugs quickly?
The following are common techniques to identify bugs quickly:

1. **Split complex functions into many subfunctions** and 
write good unit tests for them [(see here)](../README.md#1-1-high-test-coverage-with-meaningful-tests).
This makes your code nicer to read and the failing tests *often* indicate exactly where stuff is going wrong.
2. **Use static code analyzers** (such as PMD). 
Warnings from such code analyzers are almost always a good indication that somethings is going wrong.
Making sure to fix such warnings whenever they occur will make sure your project remains in an easily understandable state.
3. **Observe the value of variables during code execution**.
If you're using an advanced IDE (such as IntellJ or Eclipse) this can easily be done by setting breakpoints and running 
the code in debugging mode.
If you're using simpler tools like BlueJ or simple text editors, print the values of your variables to the console as
the program runs to identify unexpected values (this is a dirty hack - luckily, you'll soon switch to real IDEs :speak_no_evil:).
4. **Ask your mate**.
Sometimes, a second pair of eyes just sees more. 
Don't hesitate to ask your teammates to review your code and be helpful if they ask you to review theirs.
5. **Explain your code to a Rubber Duck** :duck: [(Yes, that's a thing)](https://en.wikipedia.org/wiki/Rubber_duck_debugging).
By forcing yourself to precisely and explicitly formulate what your code is doing, you will spot many errors yourself.
It may sound stupid, but try it.
6. (If an error is printed to the console): **Google / StackOverflow** are reliable buddies.

**Last Resort**: Only if you completed steps (1) to (6), consider contacting a TA. 
Note that we are neither Rubber Ducks nor Search Engine Proxis. :v:


