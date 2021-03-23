# Wizeline Academy Assignment 2
## Postman & Newman API automation

## Installation

Requires [Node.js](https://nodejs.org/) + npm
Requires Newman
Requires newman-reporter-htmlextra

## To run test:
```
newman run './Collections/WA_Second_Assessment.postman_collection.json' -e './Enviroments/Wize_Academy_Todoist.postman_environment.json' 
-d './Data/newtask.csv' -r htmlextra --reporter-htmlextra-export './Reports/reporte.html'
```

