# Web-API
📌 Objective:

This project is about learning how to create a Web API — a tool that allows other programs or users to access and interact with your data over the internet.

You'll learn:
1. What an API is and why you'd use one.
2. To build a web API that returns data to its users.
3. How to use Flask (a Python web framework) to build and serve a simple web API.
---

❓ What is an API?:

API stands for Application Programming Interface. It allows different computer programs to talk to each other.

For example:
- Your weather app talks to a weather API to get real-time data.
- A Twitter bot might use Twitter’s API to like tweets or fetch tweet details.
---

🕸️ What is a Web API?:

A Web API lets programs exchange information over the internet. Instead of downloading entire datasets, a user or program can request just what it needs — for example: the current weather in a specific city — and the API responds with that data, often in real time.

---

🧭 When Should You Build an API?:

- Your dataset is too large to easily download all at once.
- Users need to access the data in real time.
- The data is frequently updated.
- Users only need access to a part of the data at any one time.
- Users will need to perform actions other than retrieve data, such as contributing, updating, or deleting data.
---

🔑 Key API Terminology
| Term     | Meaning                                                                 |
|----------|-------------------------------------------------------------------------|
| HTTP     | A protocol for transferring data over the web.                         |
| GET      | An HTTP method used to request data from the server.                   |
| POST     | An HTTP method used to send new data to the server.                    |
| URL      | The address of a web resource (like a webpage or API endpoint).        |
| Endpoint | A specific path in the API where you can get or send data (e.g., `/users`, `/weather`). |
| JSON     | A popular format for sending and receiving data. It’s easy for both humans and machines to read. |
