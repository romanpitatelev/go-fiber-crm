# Simple CRM Lead Management System
(practice project based on video by Akhil Sharma)

The Simple CRM Lead Management System is a Go application that provides a RESTful API for managing leads. It utilizes the Fiber web framework and the GORM ORM library to handle HTTP requests and interact with a SQLite database.
Features

- Retrieve all leads
- Retrieve a specific lead by ID
- Create a new lead
- Delete an existing lead

### Prerequisites

Before running the application, make sure you have the following installed:

- Golang programming language
- SQLite database engine

### API Endpoints

The following API endpoints are available:

- GET /api/v1/lead: Retrieve all leads.
- GET /api/v1/lead/:id: Retrieve a specific lead by ID.
- POST /api/v1/lead: Create a new lead.
- DELETE /api/v1/lead/:id: Delete an existing lead.

### Database

The application uses an SQLite database to store lead information. The database file leads.db will be created in the project directory when you run the application. The database schema will be automatically migrated upon starting the application.
