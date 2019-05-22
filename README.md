# express-react-news
Express api with react client for reading hacker news

## Concepts
- **Express** is a framework built on top of Node.js used for starting servers and building web APIs.

- **Express middleware** is functionality that runs before every request, to process information about the request, add headers to the response, perform logging, and any other kind of useful functionality.

- **CORS:** Adding the `Access-Control-Allow-Origin` with the `*` argument will allow any frontend addresses to be considered as part of the server’s origin. This helps get past the same origin policy check implemented by the browser.

- **API Wrappers** are servers that perform inner requests to other APIs. These can be used to combine multiple API requests into one overall request, to add a more open `Access-Control-Allow-Origin` header, and to accomplish other custom functionality!

- **Serving a React Frontend** can occur within the same server as its backend API. Serve a static directory to the relative path where your React code is built.
