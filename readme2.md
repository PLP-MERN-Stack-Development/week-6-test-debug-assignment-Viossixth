## Installation and Running the Project

1. **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <project-directory>
    ```
2. **Install dependencies:**
    ```bash
    npm install
    ```
3. **Start the application:**
    ```bash
    npm start
    ```

## Running Tests and Debugging Techniques

- **Run tests:**
  ```bash
  npm test
  ```
- **Debugging techniques used:**
  - Utilized `console.log` statements for tracing issues.
  - Used Node.js and browser debuggers to set breakpoints and inspect variables.
  - Employed error boundaries and handled exceptions for robust debugging.
 
#Steps to run tests and debugging techniques used.
    
I introduced a CORS error which didnt allow to change the status of a bug. I used The dev tools and console to locate the error after checking the front-end code and backend terminal if the UI is fine and if the MongoDB is connected properly. I had to add patch method under the Mongoose Methods and my Application started working properly.


## Testing Approach and Coverage

- **Testing approach:**  
  The project uses unit and integration tests to ensure code reliability. Tests are written using frameworks like Jest and React Testing Library.
- **Coverage:**  
  Test coverage includes core components, API endpoints, and utility functions. Coverage reports are generated with `npm run test -- --coverage` to monitor and improve test completeness.