# Episode 1 : Execution Context

* Everything in JS happens inside the execution context. Imagine a sealed-off container inside which JS runs.
It is an abstract concept that hold info about the env. within the current code is being executed.
![Execution Context](../assets/execution-context.jpg "Execution Context")

Simply put, an execution context is an abstract concept of an environment where the Javascript code is evaluated and executed. Whenever any code is run in JavaScript, it’s run inside an execution context.
* In the container the first component is **memory component** and the 2nd one is **code component**

* Memory component has all the variables and functions in key value pairs. It is also called **Variable environment**.

* Code component is the place where code is executed one line at a time. It is also called the **Thread of Execution**.

* JS is a **synchronous**, **single-threaded** language
  * Synchronous:- In an order, once first is finished, then only move to second. if you need to wait for something, then everything stops until the wait is over.
  * Single-threaded:- Can only execute One command at a time.
  * If you make a synchronous request, then you send out the HTTP request over the network and then everything stops. Mouse clicks are ignored. Timers that reach zero at put on hold. Nothing happens until the response gets back.
  * 

<hr>

Watch Live On Youtube below:

<a href="https://www.youtube.com/watch?v=ZvbzSrg0afE&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP" target="_blank"><img src="https://img.youtube.com/vi/ZvbzSrg0afE/0.jpg" width="750"
alt="Execution Context Youtube Link"/></a>

