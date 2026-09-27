# Dmoney Project

## Project Overview
This is a REST API testing project for the Dmoney application using Postman and Newman.

## Tools Used
- Postman
- Newman
- HTML Extra Reporter
- Git & GitHub

## Files
- Dmoney Rest API.postman_collection.json
- Dmoney Rest API.postman_environment.json
- report.html

## How to Run

Run the collection:

```bash
newman run "Dmoney Rest API.postman_collection.json" -e "Dmoney Rest API.postman_environment.json"
```

Generate HTML report:

```bash
newman run "Dmoney Rest API.postman_collection.json" -e "Dmoney Rest API.postman_environment.json" -r "cli,htmlextra" --reporter-htmlextra-export report.html
```
