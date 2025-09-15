# Browser Storage API

The **Browser Storage API** allows web applications to store data directly in a user's browser. It provides different ways to save data:

- **LocalStorage** – Stores data permanently until manually cleared. Useful for saving user preferences, themes, or login info.  
- **SessionStorage** – Stores data only for the current browser session. Data is cleared when the tab is closed.  
- **IndexedDB** – A powerful database for storing large amounts of structured data.  
- **Cookies** – Small pieces of data sent with every request to the server, often used for authentication and tracking.  

These storage options help websites remember information and improve user experience without relying entirely on a server.



## LocalStorage Methods

LocalStorage allows you to store data in the browser as key-value pairs. Here are the main methods:

- **setItem(key, value)** – Save data  
Example: `localStorage.setItem('username', 'Lijan');`

- **getItem(key)** – Get saved data  
Example: `const user = localStorage.getItem('username'); // Output: Lijan`

- **removeItem(key)** – Delete a specific item  
Example: `localStorage.removeItem('username');`

- **clear()** – Delete all saved data  
Example: `localStorage.clear();`

These methods help you **store, retrieve, and manage data** directly in the browser.
