## Self-Introduction
I am a backend developer with two years of experience, having previously gained valuable marketing domain knowledge through sales roles in the tourism industry, focusing on customer management. I aspire to develop services that assist those facing marketing challenges through my expertise in development.   
Currently, I am developing an all-in-one marketing integration solution at Metaflyer, where I have a deep understanding of marketing-related services, technology, and business processes.
I am passionate about building robust and scalable solutions and continuously learning the latest trends to deliver high-quality results.

## Experience
- Metaflyer 2022.11 - Present(1 year 8 months)
## Skills
- **Programming Languages**
    - Java 17
    - Javascript
- **Frameworks / Libraries**
    - Spring Framework
    - Hibernate
- **Databases**
    - MySQL
    - Oracle
- **Tools**
    - Version Control
        - GitHub
        - GitLab
    - CI/CD
        - Jenkins
    - Cloud Services
        - AWS (Amazon Web Services)
    - Testing Tools
        - JUnit
    - **Additional Skills**
        - API Design and Development
              - RESTful API
            - Facebook Graph API
        - In-Memory Data Grid
            - Hazelcast

## Education
- Jeju National University - Bachelor's Degree in Tourism Management (2016)
- Jungmun High School - Graduated from the Department of Information Processing (2006)
## Projects
### Construction of Mobile Service for Undergraduate Academic Information at Korea National Open University
**Duration: February 5 - July 26, 2024**   
**Technologies Used: Java, Spring Framework, Oracle, RESTful API, SSO, JWT**
- **SSO (Single Sign-On) Integration Project:**
    - Integrated SSO system using enPass 3.0
    - Issued JWT and managed sessions for authorized users
    - Addressed the issue where previous user information was temporarily exposed due to browser caching JWT information:
        - Cleared browser cache on logout
        - Created and issued an empty JWT with cleared user information on logout
- **Modeled and Implemented Admin Page for Managing Academic Information Services:**
    - Menu Management: Created and modified menus, managed access permissions based on academic status of departments and students
    - Administrator Management: Searched and registered administrators using employee DB information, assigned and modified permission levels
    - Notification/Announcement Management: Registered, modified, and deleted notifications and announcements
    - Utilized Oracle DB:
        - Optimized performance by replacing complex queries with Views
        - Enhanced data security by retrieving only the necessary data excluding sensitive user information

### Development and Maintenance of Metaflyer Service
**Duration: November 1, 2022 - Present**
**Key Responsibilities: : Development and maintenance of Metaflyer services**   
**Technologies Used : Java, Spring Framework, MySql, Langchain4j, RESTful API, Naver Commerce API, Hazelcast, SSE, AWS**
- **Key Services Developed:**
    - **AI Message & Image Generation Service:**
        - Developed advanced AI message and image generation features using LangChain
        - Performance Optimization:
            - Applied RAG (Retrieval-Augmented Generation) to provide optimized personalized messages
            - Improved user experience by handling image generation logic as a background task to provide asynchronous data to users, reducing wait times
    - **Naver Smart Store Management Service:**
        - Developed account management structure using seller authentication services provided by Naver Commerce Solution
        - Established an authentication server environment for calling commerce APIs
        - Integrated solution-specific APIs (Seller Authentication Token Parsing API, Subscription Authentication API, Subscription Cancellation Approval API, etc.)
        - Built an event hook receiving structure to process various events occurring in the solution market and developed post-processing functions
        - Optimized API call structure to comply with rate limits using a Blocking Queue to adjust the number of requests per second
    - **GNB Real-Time Notification Feature:**
        - Implemented real-time notification feature using SSE (Server Sent Event)
          Utilized Hazelcast ITopic to implement broadcasting for efficient message propagation in a distributed environment, ensuring high availability and scalability
    - **Marketing Coupon Issuance Service:**
        - Developed and managed a system for issuing promotional coupons for marketing purposes
        - Tracked coupon usage and reissued coupons
    - **Domain Management Service Using AWS Route 53 and ACM:**
        - Registered domains and managed DNS using AWS Route 53
        - Issued and managed SSL certificates using AWS ACM
