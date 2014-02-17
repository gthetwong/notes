# JavaScript BDD with Jasmine

## Objectives

1. Experience some of the differences between clean/good and unclean/bad JS
2. Learn Jasmine as a tool to help you write BDD JS specs

## Good JS vs. Bad JS

### Why you should care:

#### Less bugs

Bad js is at times *very* hard to debug

#### Maintainable code

* Don't leave unused variables dangling in the wind
* Don't assign crap to variables that are undefined
* Don't use `==` when you should use `===`
* Don't make two libraries override each others' functionality by putting crap in global scope
* Keep your cyclomatic complexity down to a minimum
* Have your functions do one thing well
* Don't write assignments in `if`and `for` equality checks
* Don't assume braces

#### Lower blood pressure

#### Happier team members

### All of the above is hard to keep track of manually

### Use a tool: JSHint

[JavaScript: The Good Parts](http://www.amazon.com/JavaScript-Good-Parts-Douglas-Crockford/dp/0596517742)

[About JSHint](http://www.jshint.com/about/)

#### Exercise: take some js you've written, and dump it into JSHint

### Let's add JSHint to Sublime

#### Sublime Package Control

Forllow the Simple section of the installation instructions here: [Sublime Package Control Installation Instructions](https://sublime.wbond.net/installation)

#### JSHint Gutter

**CRUCIAL:** First, run `node -v` in your terminal. This should output the version of node on your machine. If you don't have `nodejs` installed:

* **ON MAC:** In your terminal, run this: `brew install node`
* **ON LINUX:** In your terminal, run this: `apt-get install nodejs`

Follow the Sublime Package Manager section of the instructions here:
[JSHint Gutter Installation Instructions](https://sublime.wbond.net/packages/JSHint%20Gutter)

If you have Sublime Text 3, enable Automatically linting on edit or save

#### Exercise: Write some js code in Sublime and play with JSHint