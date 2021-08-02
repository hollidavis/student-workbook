# Day 2 | Using An ORM to interact with a Database

## Afternoon Code
+ [Gregslist - Node](https://github.com/hollidavis/gregslist-node)

## Daily Journal:

**What are the three types of relationships?**

+ One to One
+ One to Many 
+ Many to Many

**What are the benefits of the traditional linking of relationships instead of Embedding?**

+ Embedding has many limitations (such as document size limits) that can cause problems as the program grows. Using relationships avoids these.

**What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?**

+ You need to look at how your data will be accessed to determine how you want to structure your many to many. You will need to map out how things are related and which relationships will need to be called or accessed when the data is used. 