# Vue-JS--challenge-1

## Create a new Vue JS app

### Vue 2:
-	Root of Vue app is vue instance(object)
-	Whatever data we pass in main.js(file that has vue instance), that we can access in index.html using {{ }}
-	{{ }} : called expression
-	To access data in index.html, first step is to add vue in our project(using script tag) & then we need to connect index.html to main.js using an id=’app’
-	Whenever we change the data in main.js, the change gets reflected in index.html: so vue js is reactive
-	We always display data from javascript to html using vue js

### Steps to create vue 2 app:
1.	Include vue in app (<script src="https://cdn.jsdelivr.net/npm/vue@2.5.13/dist/vue.js"></script>)
2.	Make vue instance in main.js which also has an options object(optional properties) & assign the object to a variable app
3.	Pass data in vue instance
4.	Connect the main.js to index.html using id & el(element):’#app’
5.	Display data in index.html using {{ }} : expression
