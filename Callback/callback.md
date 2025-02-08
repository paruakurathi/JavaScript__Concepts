What is a Callback Function?

A callback function is a function passed as an argument to another function and executed later, usually after some operation completes.

Why Use Callbacks?
1. Asynchronous Execution – Handles time-consuming operations like API calls or file reading.
2. Reusability – You can pass different functions as callbacks.
3. Avoiding Blocking Code – JavaScript is single-threaded, and callbacks help prevent delays

CallBack Hell(Pyramid of DOM):
It occurs when callbacks are nested inside other callbacks, creating difficult.

How to Avoid Callback Hell?
1. Use Promises
2. Use Async/Await
