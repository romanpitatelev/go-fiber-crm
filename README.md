### Simple CRM Lead Management System

The Simple CRM Lead Management System is a Go application that provides a RESTful API for managing leads. It utilizes the Fiber web framework and the GORM ORM library to handle HTTP requests and interact with a SQLite database.
Features

    Retrieve all leads
    Retrieve a specific lead by ID
    Create a new lead
    Delete an existing lead

## Prerequisites

Before running the application, make sure you have the following installed:

    Go programming language (version 1.16+)
    SQLite database engine

## API Endpoints

The following API endpoints are available:

    GET /api/v1/lead: Retrieve all leads.
    GET /api/v1/lead/:id: Retrieve a specific lead by ID.
    POST /api/v1/lead: Create a new lead.
    DELETE /api/v1/lead/:id: Delete an existing lead.
