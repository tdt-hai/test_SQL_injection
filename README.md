# test_SQL_injection use sql lite
- username: admin
- password: admin123
- sql command for server
  - SELECT * FROM users WHERE username='admin' AND password='admin123'
- sql command injection
  - SELECT * FROM users WHERE username='admin' OR 1=1; -- ' AND password='123456'
- Running injection
   + username: 'or 1=1;
   + password: nothing
## Demo

- Link: [Demo](https://test-sql-injection.herokuapp.com/)

## Set up
-  `Clone project:`[Download](https://github.com/tdt-hai/test_SQL_injection.git)
- Run: 
    - `B1: clone project ` 
    - `B2: npm install`
    - `B4: npm start`

