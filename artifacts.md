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

<details>
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

<details>
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
- [Enhanced with Admin Interface - To be Uploaded]()

<details>
<summary><strong>Enhancement Narrative</strong></summary>

### Artifact Description

### Justification for Inclusion


### Enhancement Process

</details>

