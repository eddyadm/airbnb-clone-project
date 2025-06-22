# airbnb-clone-project

**Project brief**
The Airbnb Clone is a group-based full-stack project in the ALX Software Engineering program that involves replicating the core features of Airbnb, focusing on backend architecture, data modeling, and API creation

**Team Roles and Responsibilities**
	• Backend Developer: Responsible for implementing API endpoints, database schemas, and business logic
	• Database Administrator: Manages database design, indexing, and optimizations
	• DevOps Engineer: Handles deployment, monitoring, and scaling of the backend services
  • QA Engineer: Ensures the backend functionalities are thoroughly tested and meet quality standards


**Technology Stack**
	• Django: A high-level Python web framework used for building the RESTful API
	• Django REST Framework: Provides tools for creating and managing RESTful APIs
	• PostgreSQL: A powerful relational database used for data storage
	• GraphQL: Allows for flexible and efficient querying of data
	• Docker: Containerization tool for consistent development and deployment environments
  • CI/CD Pipelines: Automated pipelines for testing and deploying code changes


**Database Design**
The Airbnb Clone project simulates a simplified version of Airbnb, requiring a structured and relational database to manage various types of entities such as users, properties, reviews, and locations. The database design reflects real-world relationships and supports both file-based storage and MySQL-based relational storage in later stages

**Feature breakdown**
Property Creation-	Users can create new property listings by providing essential details like name, description, price, and number of rooms
Location-	Each property is linked to a specific City and State, ensuring accurate geographical placement and filtering
Pricing-	Listings include pricing information to help users understand costs upfront
Search & Filter-	Users can search and filter properties based on location, price range, amenities, and availability

**API Security**
Secure Storage of Credentials-	User passwords are hashed before storage; sensitive information like API keys and tokens are securely stored and never exposed in code
Authentication-	Ensure that only authenticated users can access protected endpoints
Authorization-	Ensure that only authorised users have access to the righful resources

**CI/CD Pipeline**
Continuous Integration (CI) and Continuous Deployment (CD) streamline the process of building, testing, and deploying the Airbnb Clone project, ensuring code quality, faster releases, and reliable delivery
_Typical CI/CD Tools Used_
GitHub Actions — Integrated with GitHub for automating testing and deployment workflows.
Docker — Containerizes the app for consistent environments across development, testing, and production.
Testing Frameworks — Unittest, Pytest for automated testing
