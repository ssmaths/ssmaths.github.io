
# Learning Website Architecture
## API Calls


**Problem:**  APIs are Application programming interfaces. API calls allow applications to interact with each other in a systematic and predicatable way. 
It is important therefore to learn to interact with APIs with standard messages. 
So let's begin.

**Approach:** Let's take some notes for standard API calls and how to use them.

**Outcome:** 
REST(Representational State Transfer) remains the most widely used pattern for web services

Common items to remember about REST:
1. Each request from the client must contain all the information the server needs to understand it. The server doesn't "remember" previous requests.
2. The user interface (client) and the data storage (server) are independent. You can change your mobile app's UI without touching the server's database logic.
3. REST APIs use standard HTTP methods to perform actions as follows:

**The Anatomy of a Call:**
Every standard API call (specifically RESTful ones) consists of four main parts:

1 Endpoint (URL): The specific "address" of the service (e.g., api.weather.com/v1/forecast).

2 Method (The Action): * 
   GET: "Give me data."

   POST: "Create something new."

   PUT/PATCH: "Update this existing thing."

   DELETE: "Remove this."

3 Headers: The "envelope" details—things like your API key (security) and the type of data you're sending.

4 Body (Payload): The actual data you are sending to the server (common in POST and PUT calls).
   
