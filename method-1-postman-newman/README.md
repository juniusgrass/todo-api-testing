# Method 1: API Testing with Postman and Newman

This folder demonstrates a basic API test project using Postman and Newman.

---

## Tools Used

- Postman – to create and manage API test cases
- Newman – to run Postman collections from the command line
- GitHub Actions – to automate tests in a CI environment (next step)

---

## Collection File

The collection file `todo.postman_collection.json` contains 5 test cases:
- GET all todos
- GET a todo by ID
- POST a new todo
- PUT (update) an existing todo
- DELETE a todo

Each request includes a basic test to check that the HTTP response status is 200.

---

## Run Locally with Newman

To run the tests and generate a report:

```bash
newman run todo.postman_collection.json -r html --reporter-html-export newman-report.html
