# Task Management and Data Pipeline System
A comprehensive task management system and data pipeline framework, leveraging multiple programming languages and technologies to demonstrate a robust and scalable architecture.

## Project Description
This project encompasses two primary components: a task management system and a data pipeline module. The task management system is designed to handle tasks with varying priorities and statuses, utilizing object-oriented programming principles and concurrency structures. The data pipeline module simulates a data extraction, transformation, and loading (ETL) pipeline, generating mock sales data, aggregating metrics, and outputting the results. Additionally, a mock web API server is included, providing a RESTful router, error handling, and an in-memory database.

## Tech Stack
* **Programming Languages:** Java, C++, Python, C, JavaScript
* **Frameworks and Libraries:** Java Util, Java Time, Python Logging, Python Dataclasses, Node.js HTTP, Node.js URL
* **Data Storage:** In-Memory Database (Node.js)

## Directory Structure
```markdown
.
├── TaskManagementSystem.java
├── StringProcessor.cpp
├── data_pipeline.py
├── file_io.c
├── main.c
├── item.h
├── server.js
├── inventory.h
├── file_io.h
├── Makefile
├── utils.c
├── utils.h
├── item.c
└── inventory.c
```

## Installation and Startup
1. Clone the repository using `git clone`.
2. Navigate to the project directory.
3. Compile the C and C++ files using `make` (assuming a Makefile is present).
4. Run the Java task management system using `java TaskManagementSystem`.
5. Run the Python data pipeline module using `python data_pipeline.py`.
6. Start the Node.js server using `node server.js`.

## Usage and API Examples
### Task Management System
* Create a new task: `Task task = new Task(1, "Example Task", "This is an example task", TaskPriority.MEDIUM);`
* Update task status: `task.setStatus(TaskStatus.IN_PROGRESS);`
### Data Pipeline Module
* Generate mock sales data: `DataPipeline pipeline = new DataPipeline(); pipeline.generate_data();`
* Process and aggregate data: `pipeline.process_data();`
### Node.js Server
* Get all users: `GET /users`
* Get user by ID: `GET /users/:id`
* Create a new user: `POST /users` with JSON payload `{ "name": "John Doe", "role": "Admin" }`

## Contributing
Contributions are welcome and appreciated. To contribute, please fork the repository, make changes, and submit a pull request. Ensure that all code changes are properly tested and documented.

## Licensing
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.