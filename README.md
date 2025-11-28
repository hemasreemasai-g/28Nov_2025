**✅ Q1: Basic Callback Demonstration**
Problem Statement

You are building a simple simulation of user interaction on a website.
Write a function called displayMessage that takes a name and displays a greeting message:

**["Hello, <name>!"]**


Create another function called getUserInput that accepts a callback.
This function should simulate retrieving a username after 1 second and then call the callback with the retrieved name ("Alice").

Steps

Define the displayMessage function to output a greeting.

Define the getUserInput function that simulates fetching "Alice" after 1 second and calls displayMessage as a callback.



**✅ Q2: Asynchronous Timer with Callback**
Problem Statement

Create a function timer that takes:

a duration (in milliseconds)

a callback function onComplete

The function should use setTimeout to simulate a countdown.
When the timer ends, it should execute onComplete with the message:

**["Timer of <duration> ms finished"]**

Steps

Define timer that accepts duration and onComplete.

Use setTimeout to delay for duration, then call onComplete with the finish message.
