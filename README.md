# RESTful API using Vapor and Fluent integrated with PSQL database.
This API provides a robust and efficient platform for managing natural disaster data. Built with the power of Vapor, Fluent, and PostgreSQL, it offers a comprehensive suite of functionalities to effectively track, update, and retrieve information about natural disasters.
## Feature List
CRUD Operations:
## Create (POST): 
Add new disaster records to the database, including details like type, location, date, and initial status.
## Read (GET):
Retrieve all disaster records from the database.
Filter disasters by date range to fetch specific occurrences.
Search for disasters based on location to focus on affected areas.
Query disasters based on their current status (e.g., ongoing, resolved).
## Update (PUT/PATCH):
Modify existing disaster records, allowing adjustments to details like severity, ongoing actions, or final assessments.
Update the disaster status to reflect its current stage (e.g., from "ongoing" to "resolved").
## Delete (DELETE): Remove disaster records from the database, potentially for outdated or irrelevant entries.
