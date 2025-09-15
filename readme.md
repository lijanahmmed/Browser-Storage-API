# JavaScript Concepts

This repository explains and demonstrates important **JavaScript concepts** such as asynchronous programming, promises, event loop, and timing functions — all in a single code file.

---

## Concepts Covered

- **Async / Await** – Allows writing asynchronous code in a synchronous style. `async` makes a function return a promise, and `await` pauses execution until the promise resolves.  

- **Promise** – An object that represents a value which may be available now, in the future, or never. It has three states: *pending*, *fulfilled*, or *rejected*.  

- **Promise.all** – Accepts an array of promises and runs them in parallel. Resolves when all promises are successful, or rejects if any promise fails.  

- **Fetch API** – A modern way to make HTTP requests in JavaScript. It returns a promise and is often used with `async/await` to get API data.  

- **Event Loop** – The mechanism that handles execution order in JavaScript. It manages the call stack, callback queue, and microtasks to keep JavaScript non-blocking and asynchronous.  

- **setTimeout** – Executes a function once after a specific delay (in milliseconds). Useful for scheduling tasks.  

- **setInterval** – Repeatedly executes a function after a fixed time interval until `clearInterval` is called. Commonly used for timers and animations.  
