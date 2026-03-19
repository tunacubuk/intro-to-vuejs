# Vue.js Data Binding Practice 🚀

This is a simple project created to practice the core concepts of Vue.js 3, focusing on data binding and the Options API.

## 📝 About the Project
This application demonstrates how to dynamically render data into HTML and manage attributes using Vue's reactive system. It serves as a foundational exercise for my Management Information Systems studies.

### Key Features:
* **Declarative Rendering:** Displaying data using the `{{ }}` syntax.
* **Attribute Binding:** Using `v-bind:href` for dynamic links and `v-bind:value` for input fields.
* **No-Build Setup:** Running directly in the browser via Vue 3 Global Build (CDN).

## 🛠️ Tech Stack
* HTML5
* [Vue.js 3](https://vuejs.org/)

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Open the `index.html` file in any modern web browser.

```javascript
// Quick look at app.js
Vue.createApp({
    data() {
        return {
            name: "Tuna",
            age: 21,
            job: "Software Engineer",
            website: "[https://vuejs.org/](https://vuejs.org/)"
        }
    }
}).mount('#app')
