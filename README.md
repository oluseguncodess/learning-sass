# Welcome 👋🏾

I'm currently learning sass/scss and i'm documenting my progress here till I finish learning 

## What I have learnt 🥷🏾
Here are the list of things i've learnt so far;

* variables in scss
* Partials
* Nesting and indentation
* Mixins 

## Resources ㈾

I'm currently learning scss on Youtube by FreeCodeCamp. 

Here's the link 👉🏾 - [Sass Tutorials for Beginners](https://youtu.be/_a5j7KoflTs?si=cQE4xhx8kcrxhY6T)

To check out sass documentation 👉🏾 - [Sass documentation](sass-lang.com)

## My Documentation ✍🏾

### What is Sass? 

SCSS stands for Sassy Cascading style sheets. It’s a preprocessor that is useful for writing css in a better and more effective way. 

I say it’s a preprocessor that solves problems that arises with css.

Some benefit of scss includes; 

* Writing clean code by eliminating the repetition of code

* Solving problems faced with css such as organizing code. 

* Writing programmable css.

### Variables in scss

---

Variables are a way to store data so they can be referenced easily. To store variables in scss, we use the $ sign as opposed to the sign -- used in css

 e.g 👉🏾
`` `$variable: code; 
`` `

### Partials

* Partials are used to make the css code less bulky and more sectioned. Rather than writing all our code with one file, we can create different files for different sections and write our code. This makes our code more organized and readable. 

* We however have to name those files differently so that the scss compiler can identify those files as partials. We also have to import the files to the main scss file. 

* To name the partial files, we simply place an underscore _ in front of the name of the file and end it with .scss