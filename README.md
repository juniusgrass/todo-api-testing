# Todo List API Testing Project

This project demonstrates two different approaches to test a RESTful Todo List API.

---

## ✅ Method 1: Postman + Newman (Low-code, quick start)

- Tools: Postman, Newman CLI, HTML Reporter
- CI Integration: GitHub Actions runs Newman
- Best for:
  - Fast testing without code
  - Visual reporting
  - Collaboration with non-developers

👉 [Go to method-1-postman-newman](./method-1-postman-newman)

---

## ✅ Method 2: Python + requests (Code-based, flexible)

- Tools: Python, requests, pytest
- CI Integration: GitHub Actions runs Python tests
- Best for:
  - Custom assertions and logic
  - Code version control
  - Integration with Python ecosystem

👉 [Go to method-2-python-requests](./method-2-python-requests)

---

## 🔍 Method Comparison

| Feature                | Postman + Newman | Python + requests |
|------------------------|------------------|-------------------|
| Code required          | ❌ No            | ✅ Yes            |
| Flexibility            | ⚠️ Limited      | ✅ High           |
| Visual reports         | ✅ Built-in      | ⚠️ Requires setup |
| CI/CD friendly         | ✅ Easy          | ✅ Easy           |
| Collaboration          | ✅ Non-coders    | ⚠️ Developer-only |
