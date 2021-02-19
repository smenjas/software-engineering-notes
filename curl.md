# `curl`

The `curl` command allows you to send HTTP requests from the command line.

## Examples
- Send a POST request:
  ```bash
  curl -X POST http://localhost:3000/users -H "Content-type: application/json" -d '{"username":"Pam", "email":"pam@example.com"}'
  ```
