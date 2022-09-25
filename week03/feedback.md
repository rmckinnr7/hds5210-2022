# Week 3 feedback

First, avoid using the parameter names as internal variable names. That will create confusion in more complicated scenarios.

In 14.4, the first thing you do is calculate an assignment value based on simply the sum of the inputs parameters. Your `return "Invalid"` will never be run because the value of assignment will always be either >= 10 or < 10.  So, this doesn't cause any real issue, but the code is unnecessary and confusing.

After you calculate all of the LACE logic (which you could have done by just calling the LACE() function with the right parameters), you don't do any comparison to if the total is > 10 or not.  So, this wouldn't return the right answers in every circumstance.


