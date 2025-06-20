# Project Description
This project is a full-stack clone of the popular accommodation booking platform AirBnB.
The goal is to build a functional web application that allows users to browse property listings, 
view detailed property information, and complete bookings.
The project will cover frontend development, backend APIs, database design, and deployment.

# Learning Objectives
By completing this project, you will:

* Learn to implement responsive UI/UX designs
* Understand how to structure a complex web application
* Practice working in a team with defined roles
* Develop skills in component-based frontend architecture
* Learn best practices for web application development

## Tech Stack
* **Frontend:** HTML, CSS, JavaScript (React or similar framework)
* **Version Control:** Git and GitHub
* **Design Tools:** Figma for UI/UX design

## Requirements
Project Initialization

Set up GitHub repository with proper documentation
Include comprehensive README with project overview
UI/UX Design Planning

Document design goals and key features
Create page descriptions for main views
Analyze Figma design specifications
Identify color schemes and typography
Roles and Responsibilities

Define team structure and responsibilities
Document each role’s contribution to the project
UI Component Patterns

Plan reusable UI components
Document component architecture
Best Practices
Code Organization: Maintain clean, modular code structure
Version Control: Use feature branches and meaningful commit messages
Responsive Design: Ensure mobile-first approach
Accessibility: Follow WCAG guidelines
Documentation: Keep all project documentation updated
Testing: Implement unit and integration tests
UI/UX Design Planning
Design Goals
Create intuitive booking flow
Maintain visual consistency
Ensure fast loading times
Prioritize mobile responsiveness
Key Features
Property search and filtering
Detailed property viewing
Secure checkout process
User authentication
Primary Pages
Page	Description
Property Listing View	Grid display of available properties with filters
Listing Detailed View	Complete property details with images and booking form
Simple Checkout View	Streamlined payment and booking confirmation
Importance of User-Friendly Design
A well-designed booking system reduces friction in the user journey, increases conversion rates, and improves customer satisfaction. Clear navigation, intuitive interfaces, and responsive design are critical for success.

Figma Design Specifications
Color Styles:

Primary: #FF5A5F
Secondary: #008489
Background: #FFFFFF
Text: #222222
Secondary Text: #717171
Typography:

Primary Font: Circular, Medium (500), 16px
Headings: Circular, Bold (700), 24px-32px
Secondary Text: Circular, Book (400), 14px
## Project Roles and 
| Role | Responsibilities |
| --- | --- |
| Project Manager | Oversees timeline, coordinates team, manages deliverables |
| Frontend Developers | Implements UI components, ensures responsive design |
| Backend Developers | Builds APIs, manages database, implements business logic |
| Designers | Creates mockups, maintains design system, ensures UX quality |
| QA/Testers | Writes test cases, performs testing, reports bugs |
| DevOps Engineers | Manages deployment, CI/CD pipeline, server infrastructure |
| Product Owner | Defines requirements, prioritizes features, represents stakeholders |
| Scrum Master | Facilitates agile processes, removes blockers, organizes meetings |
## UI Component Patterns
# Planned Components
1.Navbar
  * Logo
  * Search bar
  * User navigation
  * Responsive menu

2.Property Card
  * Property image
  * Basic details (price, location, rating)
  * Favorite button
  * Responsive layout

3.Footer
  * Site links
  * Company information
  * Social media links
  * Copyright information
Each component will be designed for reusability and consistency across the application.


-------------------------------
Delete everything above this, before submitting for review
-------------------------------

# FrontEnd
# airbnb-clone-project

# Overview

# Project Goals

# Tech Stack

# UI/UX Design Planning
_Objective: Document the planning process for the UI/UX design.
Outline the design goals and the key features that need to be implemented.
Include descriptions of the three primary pages: Property Listing View, Listing Detailed View, and Simple Checkout View in a table view
Explain the importance of a user-friendly design in a booking system.
Objective: Understand and explore the figma environment
Create a list for all color styles, Typography (front family, font weight, font size)
Explain the importance of identifying design properties of a mock up design._
  
# Project Roles and Responsibilities
_Objective: Define and document the roles and responsibilities within the project.
List and describe the roles such as Project Manager, Frontend Developers, Backend Developers, Designers, QA/Testers, DevOps Engineers, Product Owner, and Scrum Master.
For each role, outline their key responsibilities and how they contribute to the project’s success._

# UI Component Patterns
_Objective: Begin exploring the UI components for the AirBnB Clone project.
- Describe the components you plan to create, such as a Navbar, Property Card, and Footer_

---
# BackEnd
---

## Overview
The server-side architecture for the Airbnb Clone project is engineered to offer a resilient and extensible framework. It is built to oversee user accounts, property data, reservations, and financial transactions. This core infrastructure will support the diverse functionalities needed to replicate Airbnb's essential features, guaranteeing a seamless experience for both guests and hosts.  

### Project Goals
**User Management:** Implement a secure system for user registration, authentication, and profile management.  
**Property Management:** Develop features for property listing creation, updates, and retrieval.  
**Booking System:** Create a booking mechanism for users to reserve properties and manage booking details.  
**Payment Processing:** Integrate a payment system to handle transactions and record payment details.  
**Review System:** Allow users to leave reviews and ratings for properties.  
**Data Optimization:** Ensure efficient data retrieval and storage through database optimizations.  

### Tech Stack
**Django:** A high-level Python web framework used for building the RESTful API.  
**Django REST Framework:** Provides tools for creating and managing RESTful APIs.  
**PostgreSQL:** A powerful relational database used for data storage.  
**GraphQL:** Allows for flexible and efficient querying of data.  
**Celery:** For handling asynchronous tasks such as sending notifications or processing payments.  
**Redis:** Used for caching and session management.  
**Docker:** Containerization tool for consistent development and deployment environments.  
**CI/CD Pipelines:** Automated pipelines for testing and deploying code changes.  

## Team Roles  

**Backend Developer:** Responsible for implementing API endpoints, database schemas, and business logic.  
**Database Administrator:** Manages database design, indexing, and optimizations.  
**DevOps Engineer:** Handles deployment, monitoring, and scaling of the backend services.  
**QA Engineer:** Ensures the backend functionalities are thoroughly tested and meet quality standards.  
**Business Analyst:** Understands customer’s business processes and translates those needs into requirements.  
**Product Owner:** Responsible for a product's vision, evolution, and that the product meets customer requirements.  
**Project Manager:** Manages the software development team, and ensures delivery within time and budget constraints.  
**UI/UX Designer:** Crafts the overall experience, visual interface of a digital product to make it intuitive, accessible, and enjoyable for users.  
**Software Architect:** Designs the high-level system architecture, selects the technology stack, and defines technical standards for development.  
**Test Automation Engineer:** Designs the test automation framework, and writes and maintains scripts for automated testing.  

## Technology Stack


### Django:  
Django is a high-level Python web framework used to build the server-side application logic. Its philosophy provides a comprehensive suite of tools for rapid and secure web development, advantageous for a feature-rich platform with complex data models.  

**Role in the Project:** Django's Object-Relational Mapper abstracts database operations, which will allow us to define and interact with data models using Python. The framework includes a built-in authentication system for managing user accounts and a default admin panel for administrative data management.  

### Django REST Framework:  
Django REST Framework is a powerful and flexible toolkit that builds upon Django to create Web APIs. It provides the necessary components to expose the application's data and business logic to external clients, such as a web frontend or mobile application.  

**Role in the Project:** Django REST Framework will be used to construct the RESTful API endpoints such as /api/properties/, /api/bookings/. Its primary functions include serializing Django querysets and model instances into JSON format, handling request authentication to secure endpoints, and managing permissions to control user access to specific resources.  

### PostgreSQL:  
PostgreSQL is an open-source object-relational database system used for the primary persistence of all application data. It is selected for its high degree of compliance with the SQL standard, performance with complex queries, and robust features that ensure data integrity.

**Role in the Project:** PostgreSQL stores all critical information, including user credentials, property details, pricing, availability calendars, booking histories, reviews, and transaction records. Its support for ACID (Atomicity, Consistency, Isolation, Durability) transactions is essential. This guarantees that operations like a booking and its corresponding payment are processed as a single, indivisible unit, preventing data corruption by ensuring the operation either completes successfully or fails without leaving the database in an inconsistent state.  

### GraphQL:  
GraphQL is a query language for APIs that provides a more efficient and flexible alternative to traditional REST for data fetching. It enables a client to request a specific set of data fields from the server in a single API call.  

**Role in the Project:** Instead of relying on multiple REST endpoints that return fixed data structures, GraphQL allows the frontend client to define its exact data requirements. For example, a property list view can query for only the title and price, while a detailed property view can query for all associated data. This capability reduces over-fetching of data, minimizes the network payload, and improves application performance.  

### Celery:
Celery is a distributed task queue system for executing asynchronous operations outside of the main application's request-response cycle. This is used for tasks that are too time-consuming to be handled synchronously without negatively impacting user experience.  

**Role in the Project:** When a user action initiates a long-running process, the task is offloaded to a Celery worker. For example, after a booking is confirmed, Celery manages the background execution of tasks such as:  
       - Sending a confirmation email to the guest.  
       - Transmitting a notification to the host.  
       - Initiating payment processing via a third-party gateway.  
       - Updating search indexes or availability data.  

### Redis:
Redis is a high-performance, in-memory key-value data store. In this architecture, it serves two distinct functions: as a caching layer to reduce database load and as a message broker to facilitate communication between the web application and Celery.  

**Role in the Project:**  
       - Caching: Redis stores the results of frequent or expensive database queries. Serving this data directly from memory significantly reduces latency and lessens the load on the PostgreSQL database.  
       - Message Broker: Redis acts as the intermediary that holds tasks for Celery. The Django application places a task message in a Redis queue, and Celery workers retrieve and execute the task from that queue. It can also be used for session storage.  

### Docker:
Docker is a platform for developing, shipping, and running applications in containers. A container packages the application code along with all its dependencies, libraries, and configuration files into a single, isolated unit.  

**Role in the Project:** Docker ensures environment parity between development, testing, and production. By containerizing the application and its services (PostgreSQL, Redis), developers can run the entire stack consistently on any machine. This practice eliminates environment-specific issues, streamlines the onboarding process for new developers, and provides a predictable target for deployment.  

### CI/CD Pipelines:
CI/CD (Continuous Integration/Continuous Deployment) refers to a set of automated practices that manage the build, testing, and deployment processes of the application.  

**Role in the Project:** These automated pipelines are triggered by code commits to the project's repository.  
       - Continuous Integration CI: Automatically builds the application and runs a suite of tests to verify the correctness of the new code and prevent regressions.  
       - Continuous Deployment CD: If the CI stage passes, the pipeline can automatically deploy the new version of the application to various environments, such as staging or production, enabling rapid and reliable software delivery.  

## 🛢 Database Design 

### Entities
**1. User**  
This entity represents any individual who interacts with the platform, whether they are a guest booking a stay or a host listing a property.  

`id:` A unique identifier for each user.  
`name:` The user's name.  
`surname:` The user's surname.  
`password:` The user's password.  
`email:` The user's email address.  
`host:` A boolean value to indicate if the user has privileges to list properties.  

**2. Property**  
This entity represents a rentable space listed by a host. It contains all the descriptive information about the listing.  

`id:` A unique identifier for the property.  
`host_id:` A reference to the id of the user who owns this property.  
`title:` The title of the listing.  
`description:` A detailed text description of the space.  
`price_per_night:` The cost for a single night's stay.  
`location:` The address or geographical coordinates of the property.  

**3. Booking**  
This entity represents a reservation of a specific property by a guest for a defined period. It acts as the central link between a guest, a property, and a transaction.  

`id:` A unique identifier for the booking.  
`guest_id:` A reference to the id of the user who made the booking.  
`property_id:` A reference to the id of the property being booked.  
`start_date:` The check-in date for the reservation.  
`end_date:` The check-out date for the reservation.  
`status:` The current state of the booking.  

**4. Review**  
This entity captures the feedback a guest leaves for a property after their stay is complete.  

`id:` A unique identifier for the review.  
`booking_id:` A reference to the completed booking this review is for.  
`rating:` A numerical score.  
`comment:` The text content of the guest's review.  
`created_at:` A timestamp indicating when the review was submitted.  

**5. Payment**  
This entity records the financial transaction associated with a booking.  

`id:` A unique identifier for the payment.  
`booking_id:` A reference to the booking that this payment is for.  
`amount:` The total amount of money that was transacted.  
`transaction_id:` The unique ID provided by the payment gateway.  
`status:` The current state of the payment.  

### Entity Relations

The relationships between these entities define the structure and business logic of the application.  

**User and Property (One-to-Many):**  
A single user can own and list from zero to multiple Properties.  
Each Property belongs to exactly one User.  
Implementation: The Property table has a host_id field that points to a User's id.  

**User/Property and Booking (Many-to-Many via Booking):**  
A User can make multiple Bookings.  
A Property can have multiple Bookings over time.  
The Booking entity connects them: each Booking record belongs to exactly one User and one Property.  
Implementation: The Booking table has both a guest_id and a property_id.  

**Booking and Review (One-to-One):**  
A completed Booking can have exactly one Review.  
Each Review is tied to a single Booking.  
Implementation: The Review table has a unique booking_id field.  

**Booking and Payment (One-to-Many):**  
A single Booking can be associated with multiple Payment records.  
Each Payment record corresponds to exactly one Booking.  
Implementation: The Payment table has a booking_id field.  

## Feature Breakdown
---

The main features that will be implemented for the airbnb clone project, are the following:  

### API Documentation  
This feature provides a clear and standardized guide for how client applications can communicate with the backend. By using standards like OpenAPI alongside tools like DRF and GraphQL, the project ensures that developers can easily understand and interact with the available data and functionalities. This accelerates development and simplifies integration between the frontend and backend systems.  

### User Authentication  
User Authentication is responsible for managing all aspects of user accounts, including secure registration, login, and profile management. It forms the foundation of the platform's security and personalization, ensuring that all actions are performed by verified users. This system is essential for establishing trust and distinguishing between different roles, such as guests and hosts.  

### Property Management  
This feature gives hosts the tools to create, view, update, and delete their property listings through dedicated API endpoints. It serves as the content management system for the platform's core product, the rental properties. This functionality is critical for hosts to accurately present their offerings, including details like price, availability, and amenities.  

### Booking System  
The booking system is the transactional heart of the application, allowing guests to reserve properties for specific dates. It manages the entire reservation lifecycle, from creation and modification to finalization, ensuring that availability is handled correctly to prevent double-bookings. This feature directly connects guests with properties, turning listings into revenue-generating assets.  

### Payment Processing  
This feature handles all financial transactions required to confirm a booking. It integrates with payment gateways to securely process payments from guests and manage the flow of funds. A reliable payment system is crucial for monetizing the platform and providing a trustworthy transaction experience for both guests and hosts.  

### Review System  
The review system allows guests to post ratings and comments about their stays, building a community-driven layer of trust and quality control. By enabling users to share their experiences, this feature provides valuable social proof that helps future guests make informed decisions. It also gives hosts feedback and encourages high standards of service.  

### Database Optimizations  
This feature focuses on enhancing the backend's performance and responsiveness, especially as the amount of data grows. Techniques like indexing allow for faster data retrieval for common queries, while caching reduces the database load by storing frequently accessed information in a faster-access memory layer. These optimizations are vital for providing a smooth and fast user experience.  

## API Security
---

### Security Measures To Implement
Securing the backend API is fundamental to protecting the platform and its users. The following measures will be implemented to create a robust defense against common threats:  

**Authentication:** This is the process of verifying a user's identity. Before any sensitive action can be taken, the API must confirm that the user is who they claim to be. This is typically achieved by requiring a user to log in with a password, after which the server issues a secure, short-lived access token such as in the form of JSON Web Token or JWT, that must be included in all subsequent requests.  

**Authorization:** Once a user is authenticated, authorization determines what they are allowed to do. The system will enforce strict permission checks on every request to ensure users can only access and modify data they own or are permitted to see. For example, a host can edit their own property listings but cannot edit another host's.  

**Rate Limiting:** This measure protects the API from abuse by limiting the number of requests a single user or IP address can make within a specific time frame. It is a critical defense against brute-force attacks on login endpoints and prevents malicious actors from overwhelming the server with requests, which could lead to a Denial of Service attack that makes the platform unavailable for legitimate users.  

**Input Validation:** All data received by the API from a client will be rigorously validated. The system will check that the data is in the expected format and does not contain malicious code. This is a primary defense against injection attacks, where an attacker attempts to trick the application into executing unintended commands.  

**HTTPS/TLS Encryption:** All communication between the client applications and the server will be encrypted using HTTPS. This ensures that sensitive data, such as passwords, personal information, and authentication tokens, cannot be intercepted or read by attackers while it is in transit over the internet.  

### Importance of Security
For this project, security is not a single feature but a critical requirement that underpins the entire platform's viability.

**Protecting User Data:** The project handles significant amounts of Personal Identifiable Information (PII), including names, email addresses, and booking histories. A data breach would violate user privacy, expose them to identity theft, and result in a catastrophic loss of trust and potential legal action. Strong authentication and authorization are essential to ensure only the legitimate owner can access and manage their personal data.  

**Securing Payments and Financials:** The integrity of payment processing is non-negotiable. Without robust security, attackers could intercept financial data, authorize fraudulent charges, or divert funds, leading to direct financial losses for users and the platform. Encrypting communications with HTTPS and securely managing API keys for payment gateways are crucial for protecting every transaction.  

**Maintaining Platform Integrity:** The value of the platform depends on the integrity of its content, such as bookings and reviews. A lack of security could allow malicious users to create fake bookings to block a property's availability, cancel legitimate reservations, or post fraudulent reviews to manipulate property ratings. Strict authorization rules, ensuring only the verified guest of a completed booking can leave a review, are vital for maintaining a fair and reliable ecosystem.  

## CI/CD Pipeline
---

CI/CD stands for Continuous Integration and Continuous Delivery/Deployment. It is an automated practice that streamlines the process of building, testing, and deploying software. A pipeline is the sequence of automated steps that takes new code from a developer's machine and delivers it to production.  

### Definitions  

**Continuous Integration or CI:** This is the practice where developers frequently merge their code changes into a central repository. After each merge, an automated build and test sequence is run. The primary goal is to detect and fix integration bugs early in the development cycle.  

**Continuous Delivery or CD:** This is the stage that follows a successful CI process. It automatically prepares and packages the tested code for release. The code is kept in a deployable state, allowing for a release to be triggered at any time with the push of a button. Continuous Deployment is an extension of this, where every change that passes all tests is automatically deployed to production without human intervention.  

### Importance of CI/CD
For our Airbnb clone project, CI/CD pipelines will be crucial for several reasons:

**Ensuring Quality and Reliability:** The platform handles critical operations like payments and bookings. The automated testing in a CI pipeline ensures that every code change is rigorously validated, significantly reducing the risk of introducing bugs that could affect users or cause financial errors.  

**Increasing Development Speed:** By automating the repetitive tasks of testing and deploying, developers can focus on building new features. This accelerates the development lifecycle, allowing the platform to evolve and respond to user needs more quickly.  

**Providing Consistent and Reliable Deployments:** Automation eliminates the manual errors that can occur during deployment. Every release is built, tested, and deployed using the exact same process, ensuring consistency and making the release process predictable and less risky.  

### CI/CD Tools  

We will be looking at several tools that may work together to create an effective CI/CD pipeline. The primary tools we will look at for this project will be:  

**GitHub Actions:** This is the orchestrator of the pipeline. As a CI/CD platform integrated directly into GitHub, it can be configured to automatically trigger workflows which are a series of jobs, whenever code is pushed to the repository. These workflows can be used to run tests, build artifacts, and deploy the application.  

**Docker:** This is the containerization tool that will be used for packaging the application. A key step in the CI pipeline will be to build a Docker image containing the Django application and all its dependencies. This image will be consistent and portable, which will ensure the application runs the same way in the testing environment as it does in production.  

**Other Alternatives:** Other tools such as Jenkins or Gitlab CI/CD could also be used to achieve the same outcome.
