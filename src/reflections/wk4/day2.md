# Day 2 | HTTP Requests Continued

## Afternoon Code
+ [Gregslist with API](https://github.com/hollidavis/gregslist-mvc/tree/SandboxAPI)

## Daily Journal:

**What are the three states of a Promise?**

+ Pending: Initial State, before the Promise succeeds or fails
+ Resolved: Completed Promise
+ Rejected: Failed Promise

**How do promises seek to resolve the issues of "callback hell"?**

+ A promise has 2 possible outcomes: it will either be kept when the time comes, or it won't. This helps to prevent "callback hell" to ensure that code will never be stuck, it'll always move forward. 

**What is the difference between .then() and .catch()?**

+ Then() is used to dictate what happens after a promise is successful while catch() is used to dictate what should happen if a promise fails. 