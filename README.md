# Express/Web Socket Template

A template for an empty Express, Node.js Application complete with:
- Middleware for
  - generic logging of all requests to the server in the console
  - generic error handling
  - generic error responses for endpoint not found
- Templates for
  - Controller files to hold definitions for functions called when an endpoint is hit
  - Route files to tie endpoint URIs to functions defined in a controller
  - Adding routes, and by extension controller methods to `server.js`
  - Managing data sharing through Websockets via `ws`
  

Install dependencies

```bash
npm install
```

Run server

```bash
npm run dev
```

This is just a sandbox for learning Express. There is a full CRUD api at http://localhost:8000/api/posts
