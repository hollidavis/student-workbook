# Day 4 | Working with MVC with Complex Data, Array Methods

## Afternoon Code
+ [Master Garden Shop](https://github.com/ShereneC/MasterGardenShop)

## Daily Journal:

**What problems does the Observer Pattern seek to solve?**

+ The Observer Pattern enables developers to update parts of a page in response to certain events, with the data these provide. It helps to synchronize all needed changes when these events happen. 

**What are the three mechanisms of the observer pattern?**

+ The Subscribe Method: adds new observable events
+ The Unsubscribe Method: removes observable events
+ The Broadcast Method: executes all events with bound data

**Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.**

+ The bcw-template generates all the necessary files to utilize the observer pattern. It allows us to utilize models, services, controllers, etc to pull only the data needed forward into the next and such use encapsulation. Also by utilizing the ProxyState we are able to give the site user a copy of the app state that can be manipulated on the DOM without breaking the original.