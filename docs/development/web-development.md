# Web Development

Process of creating and maintaining websites and web applications.

Broadly categorized into two main areas: front-end development and back-end development.

## Frontend 

This involves everything that users interact with directly in their web browsers. 

Key aspects include:

- HTML: The structure of web pages.
- CSS: The styling and layout of web pages.
- JavaScript: Adding interactivity and dynamic behavior to web pages.

Sample Frameworks and Libraries: React, Angular, or Vue.js that streamline development.

## Backend

Runs the core functionality, business logic, data processing, database interactions. 

<details> <summary> Microservice Backend of e-Commerce platform </summary>
```
# Microservices for E-Commerce Platform

User Management Service:  
Manages user accounts, roles, and permissions, including customer and admin access.

Product Management Service:  
Handles product details, including descriptions, pricing, availability, and categorization.

Inventory Management Service:  
Tracks stock levels, manages reordering, and monitors warehouse operations.

Shopping Cart Service:  
Manages user shopping carts, including adding, updating, and removing items.

Order Management Service:  
Handles the entire order lifecycle, from order creation to fulfillment and invoicing.

Payment Processing Service:  
Manages payment transactions, integrating with payment gateways and handling payment confirmations.

Shipping and Fulfillment Service:  
Oversees shipping options, tracking shipments, and managing fulfillment centers.

Customer Review and Rating Service:  
Facilitates customer feedback on products, including submitting reviews and ratings.

Discount and Promotion Service:  
Manages promotional offers, discounts, and coupon codes for products.

Analytics and Reporting Service:  
Generates reports and dashboards on sales performance, user behavior, and inventory metrics.

Wishlist Service:  
Allows users to save products for future purchases and manage their wishlists.

Search and Recommendation Service:  
Provides search functionality and personalized product recommendations based on user behavior.

Integration Service:  
Facilitates integration with third-party applications, such as CRM, marketing tools, and external APIs.

Notification Service:  
Sends alerts and notifications regarding order status, promotions, and customer account updates.

Feedback and Support Service:  
Handles customer inquiries, support tickets, and feedback collection.

```
</details>

<details> <summary> Microservice Backend of Human Capital Management Platform </summary>
```
# Microservices for Human Capital Management Platform

User Management Service:  
Manages user accounts, roles, and permissions, including employee access to the HCM system.

Employee Management Service:  
Handles employee records, including personal information, job details, and employment history.

Recruitment Management Service:  
Manages the recruitment process, including job postings, applications, candidate tracking, and interviews.

Onboarding Service:  
Facilitates the onboarding process for new hires, including document submission, training schedules, and orientation activities.

Payroll Management Service:  
Manages payroll calculations, including salaries, deductions, bonuses, and tax compliance.

Benefits Administration Service:  
Handles employee benefits, including enrollment, changes, and communication regarding benefits packages.

Performance Management Service:  
Manages employee performance evaluations, goal setting, and feedback processes.

Training and Development Service:  
Tracks employee training programs, certifications, and development plans.

Time and Attendance Service:  
Manages employee attendance records, time tracking, leave requests, and scheduling.

Succession Planning Service:  
Supports talent management by identifying and developing internal candidates for key positions.

Employee Engagement Service:  
Manages employee surveys, feedback, and initiatives to improve workplace engagement.

Compliance and Regulatory Service:  
Ensures adherence to labor laws and regulations, managing compliance documentation and audits.

Analytics and Reporting Service:  
Generates reports and dashboards for HR metrics, workforce analytics, and operational insights.

Integration Service:  
Facilitates integration with other systems, such as payroll providers, benefits platforms, and external HR tools.

Notification Service:  
Sends alerts and notifications for important HR events, such as performance reviews, benefits enrollment deadlines, and policy updates.

```
</details>

Key aspects include:

- Server-Side Web Service API: Python, PHP, Ruby, Java, or Node.js that handle business logic.
- Databases: like MySQL, PostgreSQL, or MongoDB that store and manage data.

The Web Application runs on "Web Server" and is rendered on web brower 

## Middleware

Acts as a bridge between the backend and frontend or between different backend services.

Typical software are message brokers, API Gateways or integration services for data transformation.

- `Enterprise Service Bus (ESB)`: Facilitates data exchange, integration in enterprise environment. e.g. Mulesoft, WSO2 
- `API Gateway`: API routing, authentication, rate limiting, analytics. e.g. AWS APIGW, Kong, Apigee
- `Integration Middlware`: ETL processing and handling between applications e.g. Apache Camel, Informatica, Talend
- `Caching Middlware`: Stores frequently used data in memory to improve app performance by reducing database load e.g. redis, memcached
- `Identity Middleware`: Manages Identities, AuthN and AuthZ across applications e.g. KeyCloak, Cognito 
- `RPC Middleware`: allows functions to be exected on remote server as though locally e.g. gRPC, Thrift
- `Message Middleware`: Asynchronous message queuing between applications e.g. Kafka, RabbitMQ
