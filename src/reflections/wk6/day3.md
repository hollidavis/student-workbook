# Day 3 | Simulating Multiple Pages with the Vue Router

## Afternoon Code
+ [Gregslist - Vue](https://github.com/hollidavis/gregslist-vue)

## Daily Journal:

**What are lifecycle hooks? What are lifecycle hooks used for?**

+ Lifecycle hooks are a window into how the library you're using works behind-the-scenes. Lifecycle hooks allow you to know when your component is created, added to the DOM, updated, or destroyed.

**How have you utilized lifecycle hooks in your afternoon projects?**

+ I have used onMounted & onUpdated the most out of all the lifehooks. I've used them in my afternoon projects to make sure that get requests are loaded on page load and that the page updates when data changes.

**What are mounting hooks? When might you use them?**

+ In the mounted hook, you will have full access to the reactive component, templates, and rendered DOM (via this.$el). Mounted is used for modifying the DOM---particularly when integrating non-Vue libraries