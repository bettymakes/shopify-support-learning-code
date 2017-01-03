# Dana Williams' Float Question

Hey Dana!  

I've included comments in both your HTML and your CSS files. Some are general
comments about syntax and convention. To address your question regarding why your
floated boxes appear to be broken, the main piece of code to focus on is around
line 54 - 56.  

I've added an additional rule to be applied to all elements:
```
  * {
    box-sizing: border-box;
  }
```

This will fix the problem you're currently experiencing with your boxes. I've
included detailed comments explaining what the fix does and a link to a resource
for you to dig further.

Don't hesitate to reach out if you have any other questions.
Let's chat about this at our next Office Hours :).

Happy New Year Dana!

Betty
