---
title: Javascripting.
description: This does nothing.
date: 2020-02-18
tags: ['javascript']
layout: layouts/post.njk
---

## Variables
Primitives............. Compound Data
ex: 5, true, abdc ..... Arrays [] <b>&</b> Objects {}


let & const are used to declare variables
use LET, If you plan to change it later
useCONST otherwise

Arrays (lists).............. Objects (dictionaries)
const arr = [1,2,3] ........ const <font color=green>obj</font> = {<font color=red>name</font>:"Steve", age: 33}

EXAMPLE............. console.log(<font color=green>obj</font>.<font color=red>name</font>);
output would be..... <i>Steve</i>

<h3>for in loop to interate over an object</h3>
EXAMPLE 2...........for (let key in obj) {console.log(key, obj[key]);}
output would be..... <i>Name Steven age 33</i>

<h3>for of loop to interate over an array</h3>
EXAMPLE 3..........for (let num of nums) {console.log(num);}
output would be..... <i>1 2 3</i>

FUNCTION is any code you want to use more than once.
EXAMPLE............ function NAMEofFUNCTION (paramater1NAME,paramater2NAME)
