---
layout: page
title: Enhanced Artifacts
permalink: /artifacts
---

# Enhanced Artifacts

## Enhancement 1: Software Design and Engineering

### Project: Contact Management Application
**Original Course:** CS 320 - Software Testing, Automation, and Quality Assurance  
**Language:** Java Migration to JavaScript (Web Application)  
**Enhancement:** Language conversion with modern web architecture

### Repository Links
- [Original Java Code](https://github.com/Chris-Merced/CS320ContactServiceOriginal)
- [Enhanced JavaScript Web App](https://github.com/Chris-Merced/CapstoneContactsApplication)

<details markdown="1">
<summary><strong>Enhancement Narrative</strong></summary>

### Artifact Description
The artifact I selected is a Java contact management system originally created for CS 320 (Software Testing, Automation, and Quality Assurance). The original implementation consisted of two classes: Contact and ContactService, which provided basic CRUD operations for managing contact information in a console application. It was a straightforward implementation that demonstrated object-oriented programming principles but remained limited to command-line interaction.

### Justification for Inclusion
I selected this artifact because it provided an excellent opportunity to demonstrate comprehensive skill development across multiple areas of software engineering. The enhancement process allowed me to showcase critical competencies that align with industry standards in modern web development and my own personal growth.
The transformation from Java to JavaScript demonstrated my adaptability and proficiency in multiple programming languages. I implemented ES6+ features including modern class syntax, modules, and arrow functions, showing mastery of contemporary JavaScript development practices. The integration of webpack as a build tool demonstrated my understanding of modern development workflows, including module bundling, code optimization, and asset management.
I added localStorage persistence for client-side data management, form validation for better user experience, and deployed the application to GitHub Pages using modern DevOps practices.

### Course Outcomes Addressed
- **Outcome 2:** Professional-Quality Communication was met through comprehensive documentation including detailed README files, inline code comments, and clear architectural explanations. The responsive web interface created an intuitive user experience that effectively communicates functionality. The modular file structure and consistent naming conventions reflect professional communication through code organization.
- **Outcome 3:** Design and Evaluate Computing Solutions was demonstrated through the architectural transformation that required careful analysis of the original Java implementation and strategic decisions about leveraging JavaScript's capabilities. I evaluated different storage options for client-side persistence and implemented efficient form validation algorithms. The webpack configuration process involved analyzing build optimization strategies and making informed decisions about performance and deployment.
- **Outcome 4:** Innovative Techniques and Tools was extensively demonstrated through the use of webpack 5 for module bundling, modern JavaScript features, Babel transpilation for browser compatibility, and GitHub Pages deployment strategy. These tools reflect current industry practices and emerging technologies.
  
### Enhancement Process
During the conversion from Java to JavaScript, I learned several key concepts:

The enhancement process provided significant learning experiences and presented challenges that strengthened my technical capabilities.
The initial challenge involved mapping object-oriented Java concepts to JavaScript's prototype-based model, leading to a deeper understanding of different programming paradigms. ES6 class syntax provided familiar structure while requiring adaptation to JavaScript's unique features.
Implementing localStorage required understanding browser security models and data serialization challenges not present in the original Java implementation. Working through these limitations developed practical knowledge of web platform constraints.
This enhancement also changed my approach to software development by forcing me to emphasize class based structure implementation, professional organizational techniques in project structure, and a refreshment on deployment strategies. The experience of transforming a working application into a professionally deployable system provided insights into the software development lifecycle beyond academic exercises. 
The enhancement successfully demonstrated software engineering principles.

### Challenges Faced
- **Data Validation**: Implementing robust client-side validation without server-side backup required careful consideration of edge cases
- **State Management**: Managing application state in a stateless web environment presented unique challenges compared to the object-oriented approach
- **Cross-Browser Compatibility**: Ensuring localStorage functionality works consistently across different browsers

### Skills Demonstrated
- **Language Migration**: Successfully converted complex business logic between programming paradigms
- **Web Development**: Created a fully functional single-page application with modern JavaScript
- **Documentation**: Provided clear README and deployment instructions for GitHub Pages hosting
- **User Interface Design**: Implemented responsive, accessible design patterns




</details>

---

## Enhancement 2: Algorithms and Data Structures

### Project: Contact Management Application - Performance Optimization
**Original Course:** CS 320 - Software Testing, Automation, and Quality Assurance  
**Enhancement:** Hash map implementation for improved efficiency

### Repository Links
- [Original Implementation](https://github.com/Chris-Merced/CS320ContactServiceOriginal)
- [Enhanced with Hash Map Structure](https://github.com/Chris-Merced/CapstoneContactsApplicationWithHashmap)

<details markdown="1">
<summary><strong>Enhancement Narrative</strong></summary>

### Artifact Description
This artifact is a contact management application originally developed in Java for CS 320: Software Testing, Automation, and Quality Assurance. The original implementation used basic object-oriented principles with getter and setter methods to manage a contact list stored in an ArrayList data structure. The application provided fundamental CRUD operations for contact management but relied on linear search algorithms for data retrieval, resulting in O(n) time complexity for lookup operations.
The enhanced version transforms this into a modern JavaScript web application while fundamentally improving the underlying data structure implementation. The enhancement specifically focuses on replacing linear search operations with hash map-based lookups to achieve O(1) average-case time complexity for contact retrieval operations.

### Justification for Inclusion
I selected this artifact for my ePortfolio because it demonstrates my understanding of algorithmic efficiency and the practical impact of data structure selection on application performance. The enhancement showcases several key competencies in algorithms and data structures.
The original implementation used findIndex() operations on arrays, which require linear traversal through all elements in the worst case. By implementing a hash map structure alongside the existing array, I reduced contact lookup operations from O(n) to O(1) average-case time complexity.
The enhancement demonstrates my ability to select appropriate data structures for specific use cases. I implemented a dual-structure approach where the original array is preserved alongside the hashmap where the array maintains insertion order for display purposes while the hash map enables efficient key-based lookups.
This implementation illustrates my understanding of the space-time trade-off principle. While the hash map increases memory usage, it provides significant performance improvements for search operations, which is crucial for scalability as the contact database grows.
By adding a contactHashMap object that maintains key-value pairs where contact IDs serve as keys and contact objects serve as values, the searchContactByID(), deleteContact(), updateContact() and addContact() methods can perform direct object property access rather than iterating through array elements, significantly increasing performance throughout the application.

### Course Outcomes Addressed
- **Outcome 3** (Computing Solutions): The enhancement demonstrates my ability to design and evaluate computing solutions using algorithmic principles. I analyzed the performance bottleneck of linear search operations and implemented a solution that manages the trade-offs between memory usage and query performance. The decision to maintain both data structures shows evaluation of different solution approaches.
- **Outcome 2** (Professional Communication): The implementation includes comprehensive documentation explaining the algorithmic improvements, performance benefits, and design decisions. The code is well-commented and follows professional naming conventions that make the efficiency improvements clear to technical audiences.

### Enhancement Process
The process of enhancing this artifact provided significant learning opportunities in both theoretical and practical aspects of algorithm implementation.
Working through the transition from array-based linear search to hash map lookups reinforced my understanding of how data structure choice directly impacts application performance. The decision to maintain both the original array and add the hashmap taught me that optimal solutions often involve combining multiple data structures rather than replacing one with another entirely.
The enhancement process required me to think critically about when optimization is necessary and worthwhile. While the performance improvement from O(n) to O(1) lookup is theoretically significant, it reminded me to consider the practical implications based on expected data size and usage patterns.
Implementing hash maps in JavaScript using object properties provided insight into how different programming languages handle associative data structures. Understanding that JavaScript objects function as hash tables reinforced the connection between language features and underlying algorithmic concepts.

### Challenges Faced
- **Data Consistency**: The primary challenge was ensuring data consistency between the array and hash map structures. Every add, update, and delete operation required careful coordination between both data structures to prevent synchronization issues.
- **Incremental Enhancement**: Maintaining backward compatibility with existing array-based methods while adding hash map functionality required careful architectural planning.
- **Language-Specific Implementation**: Adapting hash map concepts to JavaScript's object-based approach required understanding platform-specific considerations.

### Skills Demonstrated
- **Algorithm Analysis**: Deep understanding of time complexity trade-offs and performance optimization strategies
- **Data Structure Design**: Appropriate selection and implementation of hash-based data structures for specific use cases
- **Performance Optimization**: Measurable improvements in application responsiveness through algorithmic enhancements
- **Technical Documentation**: Clear explanation of design decisions and performance improvements with supporting analysis


</details>

---

## Enhancement 3: Databases

### Project: Classic Messenger Application
**Original Course:** Personal Project  
**Enhancement:** Admin Interface for User Manipulation

### Repository Links
- [Original Implementation - Front End](https://github.com/Chris-Merced/Classic-Messenger-App-Frontend)
- [Original Implementation - Back End](https://github.com/Chris-Merced/Classic-Messenger-App-Backend)
- [Enhanced with Admin Interface - Front End](https://github.com/Chris-Merced/Classic-Messenger-App-Frontend/tree/feat/admin-panel)
- [Enhanced with Admin Interface - Back End](https://github.com/Chris-Merced/Classic-Messenger-App-Backend/tree/feat/admin-panel)



<details markdown="1">
<summary><strong>Enhancement Narrative</strong></summary>

### Artifact Description
This artifact is the Classic Messenger App, a full-stack messaging application originally developed as a personal project. The application is built with Node.js and Express on the backend, React on the frontend, and PostgreSQL as the database management system. The original implementation provided core messaging functionality including user authentication, real-time communication via WebSockets, friend management, and conversation handling. The application was deployed on Heroku and demonstrated foundational full-stack development skills.

The enhanced version adds comprehensive administrative capabilities and database optimizations that significantly improve both security and performance. Specifically, the enhancement introduces role-based access control through an admin panel, implements user moderation features including banning and timeout functionality, and optimizes database performance through strategic indexing on frequently queried columns.

### Justification for Inclusion
I selected this artifact for my ePortfolio because it demonstrates my ability to design and implement secure, scalable database solutions for real-world applications. The enhancement showcases several critical competencies in database management and security:

**Role-Based Access Control Implementation**: The enhancement required careful design of privilege management systems that prevent unauthorized access to sensitive administrative functions. I implemented middleware authentication checks that verify both session validity and admin status before allowing access to protected routes. This demonstrates my understanding of defense-in-depth security principles where multiple layers of verification protect critical functionality.

**Database Schema Evolution**: Adding the `banned` boolean column and `ban_expires` timestamp column to the users table required careful consideration of existing data integrity and application logic. I implemented these changes in a way that maintained backward compatibility while enabling new administrative features.

**Strategic Database Indexing**: The implementation includes a concurrent index on the `LOWER(username)` column in the users table. This optimization directly addresses performance bottlenecks identified during development, where frequent username lookups for authentication and user searches were causing unnecessary query overhead. Creating the index concurrently ensures zero downtime during deployment, demonstrating awareness of production environment constraints.

**Automated Maintenance Processes**: The cron job implementation that automatically unbans users when their ban period expires shows understanding of database maintenance automation and scheduled task management. This prevents manual administrative overhead and ensures consistent policy enforcement.

**Secure Administrative Workflows**: The admin panel frontend validates input and provides clear feedback, while the backend implements server-side validation and authorization checks. This dual-layer approach demonstrates understanding that client-side validation alone is insufficient for security.

The artifact was improved through the addition of three new backend routes (`/admin/ban`, `/admin/unban`, `/admin/adminStatus`), corresponding database query functions (`banUser()`, `unbanUser()`, `makeAdmin()`, `checkAdminStatus()`), middleware authentication for the admin router, modifications to the login controller to check ban status, and a React-based admin panel that provides an intuitive interface for administrative actions.

### Course Outcomes Addressed
- **Outcome 5** (Security Mindset): This enhancement primarily demonstrates a strong security mindset through multiple defensive measures. The implementation of role-based access control prevents privilege escalation by requiring both valid session authentication and admin status verification before allowing access to sensitive operations. The modification to the login controller that checks ban status before completing authentication demonstrates adversarial thinking by preventing banned users from circumventing restrictions. The middleware on the admin router creates a protective barrier that stops unauthorized requests before they reach controller logic. Additionally, deleting all active sessions when a user is banned ensures they cannot continue accessing the application even if they were logged in at the time of banning.

- **Outcome 4** (Innovative Techniques): The use of concurrent indexing (`CREATE INDEX CONCURRENTLY`) demonstrates knowledge of advanced database techniques that allow schema modifications without application downtime. The automated cron job for ban expiration handling shows innovative application of scheduled task management to reduce manual administrative burden. The implementation of Redis pub/sub for real-time WebSocket communication across multiple server instances reflects understanding of scalable distributed system architecture.

- **Outcome 3** (Computing Solutions): The enhancement required evaluating trade-offs between performance and security. The decision to check ban status during login adds a database query to the authentication process, but this overhead is justified by the security benefits. Similarly, adding the username index improves query performance but increases storage requirements and write overhead slightly. These decisions demonstrate the ability to analyze and manage design trade-offs based on application requirements.

- **Outcome 2** (Professional Communication): The implementation includes clear error handling with meaningful messages, comprehensive comments explaining security considerations, and well-organized code structure that makes the administrative functionality easy to understand and maintain. The admin panel provides clear user feedback for all operations, demonstrating consideration for the end-user experience.

### Enhancement Process
The process of enhancing this artifact provided significant learning opportunities in database security, performance optimization, and full-stack integration:

**Authentication Architecture**: Implementing the admin middleware taught me about the importance of centralized authorization checks. Initially, I considered checking admin status within each controller function, but refactoring this into middleware demonstrates better separation of concerns and makes the codebase more maintainable. Understanding the difference between authentication (verifying identity) and authorization (verifying permissions) became clearer through this implementation.

**Database Performance Considerations**: The decision to create the username index came from recognizing a pattern where `getUserByUsername()` was called repeatedly throughout the application for various operations. This taught me to identify performance bottlenecks by analyzing query patterns rather than just responding to obvious slowdowns. Using `CREATE INDEX CONCURRENTLY` required learning about PostgreSQL-specific features and understanding the trade-offs between standard and concurrent index creation.

**Session Management Security**: Implementing the ban functionality revealed the importance of session invalidation. Initially, I only set the banned flag in the database, but realized that users with active sessions could continue using the application. Adding the logic to delete all sessions for banned users taught me about the security implications of stateful authentication and the need to consider all access pathways when implementing restrictions.

**Cron Job Implementation**: Setting up the automated ban expiration check within the existing scheduled cleanup task taught me about efficient resource usage. Rather than creating a separate cron job, I added the unban logic to the existing session cleanup function that already ran on a schedule, demonstrating the principle of consolidating scheduled tasks when appropriate.

### Challenges Faced
- **Data Consistency**: The primary challenge was ensuring data consistency across the ban-related columns. The `banned` boolean and `ban_expires` timestamp needed to be managed carefully to prevent inconsistent states. For example, ensuring that permanent bans have a NULL `ban_expires` value while temporary bans have a valid timestamp required careful logic in both the `banUser()` and `unbanUser()` functions.

- **Middleware Implementation**: Understanding Express middleware patterns and ensuring the middleware had access to the necessary request information (cookies, body parameters) required careful study of the Express request/response cycle.

- **Automated Testing**: Testing the cron job functionality presented challenges because automated processes are difficult to observe in real-time. I learned to use shorter time intervals during development and implemented comprehensive logging to verify that the ban expiration logic executed correctly.

### Skills Demonstrated
- **Database Security**: Implemented role-based access controls with proper privilege management
- **Performance Optimization**: Strategic use of database indexing to improve query performance
- **Full-Stack Integration**: Seamlessly integrated administrative features across frontend and backend
- **Security Mindset**: Applied defensive programming practices to protect against adversarial exploits
- **System Architecture**: Designed scalable solutions considering distributed systems and zero-downtime deployments

</details>

