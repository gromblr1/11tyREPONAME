---
title: Javascripting.
description: This does nothing.
date: 2020-02-18
tags: ['javascript']
layout: layouts/post.njk
---



| A.R.M        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| The Gromble   | right-aligned | $1600 |
| Krumm         | centered      |   $12 |
| Ickis         | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


<a href="https://sqlbolt.com/">SQL Bolt</a>
<a href="http://jsbin.com/?html,console,output">JS Bin</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/hdI2bqOjy3c" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/c-I5S_zTwAc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Variables
Primitives............. Compound Data
ex: 5, true, abdc ..... Arrays [] <b>&</b> Objects {}


let & const are used to declare variables
use LET, If you plan to change it later
useCONST otherwise

Arrays (lists).............. Objects (dictionaries)
const arr = [1,2,3] ........ const <font color=green>obj</font> = {<font color=red>name</font>:"Steve", age: 33}
<hr>
EXAMPLE............. console.log(<font color=green>obj</font>.<font color=red>name</font>);

> Steve
<hr>

<h3>for in loop to interate over an object</h3>
<hr>
EXAMPLE 2...........for (let key in obj) {console.log(key, obj[key]);};

> ```Name Steven age 33```
<hr>

<h3>for of loop to interate over an array</h3>
EXAMPLE 3..........for (let num of nums) {console.log(num);}
<br>output would be..... <i>1 2 3</i>

FUNCTION is any code you want to use more than once. <br>

EXAMPLE............ function NAMEofFUNCTION (paramater1NAME,paramater2NAME) {return paramater1NAME + paramater2NAME}
<br>output would be..... <i>NAMEofFUNCTION(paramater1NAME,paramater2NAME)</i> 

A method is a function that is associated with an object.
