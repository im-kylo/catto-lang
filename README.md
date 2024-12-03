# Index
1. [Functions](#functions)
1. [Command Line Examples](#command-line-examples)
1. [Usage Cases](#usage-cases)
1. [Configuration](#configuration)
1. [Syntax](#syntax)
<!-- 1. [Functions](#functions)
1. [Functions](#functions)
1. [Functions](#functions) -->





# About Catto-Lang
**Catto-Lang** is an open-source programming language built with simplicity and ease of readable & memorization in mind. It excels at fast, reliable code, and resource efficiency. This makes it great at handling large amounts of data and information at once. Its[syntax is flexible, readable, and beginner-friendly. **Catto-Lang** offers abbreviated syntax for maximum flexibility and workflow performance, ease of understanding and memorization. 

<!-- 
# Introduction
**Catto-Lang** is a langauge specifically made for:
 * Forking [Discord.py](https://github.com/Rapptz/discord.py/)
 * Creating Custom Programs with ease
 * Fast and efficient code
 * Ease of learning
 * Readability
 * And ___eventually___ public use
 * And more -->

# Functions
At its core, it is a interpreter-compiler hybrid. This means that it is able to both interprete and compile code in a single package using separate commands in the Command Line. This, however, can result in many errors due to the overlapping interpreter and compiler. As such, you must make a `.catto.config` file to prevent these errors. See [configuration](#configuration).

#### Command Line Examples
Interpreted:
```
catto --int interpreted-example.catto
```

Compiled:
```
catto --com compiled-example.catto
```
# Usage Cases
**Catto-Lang** can be used for any number of instances; machine-learning, building applications, and more. 

# Configuration
A `.catto.config` is a configuration file to specify a multitude of parameters for your project. 

# Syntax
|Symbol|Description|Example|
|------|-----------|-------|
|`$with`|Imports a built-in or 3rd-party library into your project|`$with typing`|
|`define`  `def`|Defines a variable.|`define exampleVar`  `def exampleVar`|
|`func`|Defines a function that can be called by other classes or functions|`func exampleFunction()`|
|`cl`  `class`|Placeholder|`cl ExampleClass()` `class ExampleClass()`|
|`as`|Permits an abbreviated or easier way of declaring a variable or library|`$with tpying as type` `def exampleVar as Var`|





---

Contact: <cattolang.contact@gmail.com>
