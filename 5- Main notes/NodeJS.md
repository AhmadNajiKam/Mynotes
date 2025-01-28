Here are **30 Node.js challenges** to help you master the platform, progressing from beginner to advanced concepts:

---
[[Node.JS|Node.JS]] [[AI Responses]]
### **Beginner Challenges**
1. **Hello World Server**  
   Create a basic HTTP server that responds with "Hello, World!" to all requests.

2. **Module Magic**  
   Create a custom module that exports a function to calculate the factorial of a number. Import and use it in another file.

3. **File System Explorer**  
   Write a script that reads a directory and lists all files with the `.js` extension.

4. **Command-Line BMI Calculator**  
   Build a CLI tool that takes height and weight as arguments and returns the BMI.

5. **NPM Init & Dependency**  
   Initialize a project with `npm`, install `lodash`, and use a utility function (e.g., `_.chunk()`).

6. **Simple Express Server**  
   Set up an 1 server that serves a static HTML page at the root route (`/`).

7. **URL Query Parser**  
   Create an endpoint that accepts a `name` query parameter and responds with `Hello, {name}!`.

8. **Middleware Logger**  
   Add middleware to an Express app that logs the request method and URL for every incoming request.

9. **Dynamic Routing**  
   Build an Express route that accepts `/:username` and returns a welcome message with the username.

10. **Environment Variables**  
    Create a script that reads a port number from `process.env` and defaults to `3000` if unset.

---

### **Intermediate Challenges**
11. **RESTful Book API**  
    Build a CRUD API for managing books (title, author, ISBN) using in-memory storage (no database).

12. **Database Integration**  
    Connect to a MongoDB database using Mongoose and create a `User` model with `name`, `email`, and `age`.

13. **Authentication with JWT**  
    Implement user registration/login endpoints that issue JWTs for authenticated requests.

14. **Error Handling**  
    Add a custom error-handling middleware to your Express app to catch and format errors.

15. **File Upload**  
    Create an endpoint that accepts image uploads and saves them to a `uploads/` directory.

16. **Rate Limiting**  
    Use `express-rate-limit` to restrict users to 100 requests per hour.

17. **WebSocket Chat**  
    Build a real-time chat app using `socket.io` where users can send messages to all connected clients.

18. **Template Rendering**  
    Use EJS or Pug to render a dynamic HTML page displaying data from an API (e.g., a list of blog posts).

19. **Validation Middleware**  
    Validate user input for an endpoint using `express-validator` (e.g., check email format).

20. **Testing with Jest/Mocha**  
    Write unit tests for your factorial module (Challenge #2) using Jest or Mocha.

---

### **Advanced Challenges**
21. **OAuth with Google**  
    Implement Google OAuth login using Passport.js to allow users to sign in with their Google account.

22. **Redis Caching**  
    Cache API responses for 10 minutes using Redis to improve performance.

23. **CLI Tool with Commander.js**  
    Create a CLI tool using `commander` to generate project templates (e.g., `my-cli create <project-name>`).

24. **Web Scraper**  
    Use `axios` and `cheerio` to scrape data from a webpage (e.g., news headlines) and return it as JSON.

25. **Microservices with Docker**  
    Containerize a Node.js app using Docker and deploy two services (e.g., API and database) that communicate.

26. **Webhook Endpoint**  
    Build an endpoint that accepts GitHub webhook payloads (on push events) and logs the commit details.

27. **PDF Generation**  
    Use `pdfkit` to generate a PDF invoice from user-provided data (e.g., product, price, customer name).

28. **Rate-Limited Proxy**  
    Create a proxy server that fetches data from an external API and enforces rate limiting.

29. **Security Hardening**  
    Add security headers (CSP, XSS, CORS) using `helmet` and sanitize user input to prevent XSS attacks.

30. **Full-Stack Todo App**  
    Build a full-stack Todo app with:  
    - Frontend (HTML/CSS/JS or React)  
    - Backend (Express + MongoDB)  
    - User authentication (JWT or sessions)  
    - CRUD operations for todos  
    - Deployment to Heroku/AWS

---

### **Tips**
- Use `nodemon` for automatic server restarts during development.  
- Explore debugging with `debugger` and Chrome DevTools.  
- Version control your code with Git.  
- Document your APIs with Swagger/OpenAPI.  

Each challenge builds on prior concepts, reinforcing your Node.js skills. Tackle them in order, and you’ll gain confidence in building robust backend systems! 🚀