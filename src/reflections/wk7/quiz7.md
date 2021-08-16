# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
+ One-way data-binding: The data flows in a single direction
+ Two way data binding: When the user types in the input , value gets updated to match the value in input . 
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
+ Quicker Loading Time
+ Uses Less Bandwidth
+ Makes it easier to build in advanced features
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
Runs the specified function on page load
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
V-model is a way to create two way data binding on forms. This is often used when creating forms or a search functionality.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
This is used to listen for an event and when it happens to trigger a function typically. 
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-if-else, v-else
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key is typically something that will be unique for each element encountered in the v-for. It helps to distinguish the different between elements. 
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
Slots are used to change specified pieces inside of components. For example you could have a button component and have a slot for the button text that you then specify each time you use it.
```