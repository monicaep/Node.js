1. In your own words highlight the differences in functionality and purposes Client-Side and Server-Side code serves in a full-stack web application.

The client-side code runs on the browser of the user. It sends HTTP requests and renders the responses for the user to see. The server-side code doesn't render anything, instead it handles HTTP requests sent from the client-side and sends responses to the client-side so that the client-side can render whatever was asked for.

2. What explains Nodes' rise in popularity and use? What does "Isomorphic JavaScript programming" mean? Provide some real-world examples not listed in this checkpoint of companies using Node.js.

Isomorphic Javascript applications are JavaScript applications which run both on the client and server side. This makes app development easier because everything can be written in one language, JavaScript, instead of having to use two different languages (one for client-side and one for server-side) and then make sure that they are communicating effectively. Using JavaScript for both sides also makes it easier to reuse components. Some companies that use Node.js are Walmart, Medium and Ebay.

3. Draw a diagram of a full-stack web application and its key components.

_________________         _________________
|Client Machine  |        |Back-End Server |
| _______________|        | _______________|
| |Browser       |        | |Node.js     | |        ____________
| | _____________| <----> | | ___________|_| <----> | Database |
| | |React       |        | | |Express | | |        ------------
| | | ___________|        | | | ______ | | |
| | | |App       |        | | | |API | | | |
| | | |          |        | | | |    | | | |
------------------        ------------------
