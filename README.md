# airbnb-clone-project

**Project brief**
The Airbnb Clone is a group-based full-stack project in the ALX Software Engineering program that involves replicating the core features of Airbnb, focusing on backend architecture, data modeling, and API creation

**Team Roles and Responsibilities**
Database Administrator- install and configure databases, Setup database instances and environments for development, testing, and production
Backend Developer- Write and maintain code that runs on the server using languages such as Node.js, Python, and design, implement, and manage databases, and Integrate third-party services and external APIs
DevOps Engineer- Design, build, and maintain Continuous Integration/Continuous Deployment (CI/CD) pipelines using tools like Jenkins, GitHub Actions, GitLab CI, and automate testing, building, and deployment processes to improve development speed and reliability.
QA Analyst- Review and analyze business and technical requirements, and identify testable conditions and prepare test plans accordingly

**Technology Stack**
Github- Tracks code changes, enables collaboration, and supports CI/CD pipelines
PostgreSQL / MySQL- Stores persistent data. SQL (PostgreSQL/MySQL) for structured data; NoSQL (MongoDB) for flexibility
Docker- 	Packages apps and dependencies for consistent deployment across environments
Kubernetes- Automates deployment, scaling, and management of containerized applications

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
