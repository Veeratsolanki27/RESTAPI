---RESTful API FLASK--- 

-This project is a fully functional RESTful API built using Flask, designed for managing users, items, stores, and tags in a retail-like system.

🧪 Fully Tested Endpoints: Developed and tested multiple REST endpoints for users, items, stores, and tags using HTTP verbs (GET, POST, PUT, DELETE).

🔐 JWT-Based Authentication: Integrated Flask-JWT-Extended to handle access and refresh tokens, login/logout mechanisms, and secure route protection.

🛑 Token Blacklisting: Built a custom blocklist.py system to invalidate JWT tokens after logout, enhancing security.

🧰 Data Validation & Serialization: Used Marshmallow schemas to validate input and serialize output, reducing boilerplate code.

🌐 Swagger UI Integration: Enabled auto-generated, interactive OpenAPI 3.0 documentation using Flask-Smorest, allowing visual API testing and debugging.

🧱 Database Abstraction: Utilized SQLAlchemy ORM with SQLite; codebase is easily configurable for other RDBMS like PostgreSQL/MySQL.

📦 Dependency Management: Managed project requirements with requirements.txt and a virtual environment for isolated Python packages.

🔄 Refresh Token Flow: Implemented secure refresh logic to renew access tokens without requiring user re-login.

🔁 Error Handling: Centralized exception handling using Flask-Smorest’s built-in mechanisms for clean API responses.

## Screenshots

###  Interface
![App Screenshot](https://raw.githubusercontent.com/Veeratsolanki27/RESTAPI/main/Project%20ScreenShot/Screenshot%202025-06-29%20191901.png)

###  Features
![App Screenshot](https://raw.githubusercontent.com/Veeratsolanki27/RESTAPI/main/Project%20ScreenShot/Screenshot%202025-06-29%20191917.png)

###  Features 
![App Screenshot](https://raw.githubusercontent.com/Veeratsolanki27/RESTAPI/main/Project%20ScreenShot/Screenshot%202025-06-29%20191928.png)

### Schemas Overview
![App Screenshot](https://raw.githubusercontent.com/Veeratsolanki27/RESTAPI/main/Project%20ScreenShot/Screenshot%202025-06-29%20191943.png)
