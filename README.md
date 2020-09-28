# ES6 modules Hello World

A minimal app that uses modules as defined in ES6. 

As with all Hello Worlds it does very litte other than give you something to follow to get started with your own apps. 

### Notes

* You can only invoke modules from other modules. So any code in your JavaScript app that builds on modules, which would seem to be all of it, has to be contained in a module. To make something  a module you just have to include it with a &lt;script> element with a type attribte of "module".

* The first thing code.js does is import secsSince from module.js. You must refer to module.js as "./module.js" -- it won't work if you refer to it as "module.js".

* The second thing code.js does is call secsSince in module.js and use it in a message that it displays in the HTML code. 

* To run the code without downloading, <a href="http://scripting.com/code/moduleshello/">click here</a>.

