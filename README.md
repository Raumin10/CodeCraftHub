# CodeCraftHub

Personal learning goal tracker API built with Node.js and Express. The API allows developers to create, view, update, and delete courses they want to learn.

Course data is stored in a local `courses.json` file, so no database is required.

## Project Overview

CodeCraftHub is a simple REST API for tracking learning courses.

Each course contains:

- An automatically generated numeric ID
- Course name
- Course description
- Target completion date
- Current learning status
- Automatically generated creation timestamp

The application runs on port `5000` by default.

## Features

- Create a new course
- View all courses
- View one course by ID
- Update an existing course
- Delete a course
- Automatically create `courses.json` if it does not exist
- Validate required fields
- Validate target dates using the `YYYY-MM-DD` format
- Validate course status values
- Return helpful error messages
- Store data without a database

Allowed course status values:

```text
Not Started
In Progress
Completed
