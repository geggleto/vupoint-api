# API Stateless Services

# Email Service

- REQUIRED
    - array to
    - string from
    - string subject
    - string body
    
- OPTIONAL
    - array cc
    - array bcc

- EXAMPLE

`curl -X POST -d "to[]=a@a.com&from=b@b.com&subject=Test&body=Test" /email`