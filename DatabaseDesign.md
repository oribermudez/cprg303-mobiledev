# Decision Record for a transportation Mobile App
### By Ana Alarcon and Oriana Bermudez

## _Route Rider_ 🚛
***
## Database Design 📂

### Context

The team has been assigned the task of developing a mobile app for a modern transportation company. The app's primary purpose is to enable users to book and track rides, access driver details, view ride history, and make secure payments. To accomplish these tasks effectively, several key requirements have been outlined for the app development process.

### Problem Statement 🤔

Developing a mobile app for a modern transportation company presents a multifaceted challenge when it comes to choosing the appropriate database type, whether relational or non-relational. The issue lies in finding the right balance between data structure, scalability, and adaptability to meet the unique requirements of the app. Relational databases like MariaDB, excel in ensuring data consistency, enforcing relationships, and performing complex queries, making them a natural choice for managing structured data [1] such as user profiles and secure payment information. However, this choice could introduce rigidity that may not align with the dynamic nature of the transportation app's ride-related data, potentially hindering adaptability and scalability.

In contrast, non-relational databases like MongoDB offer flexibility and scalability that can cater to the ever-evolving ride-related data and accommodate the expected growth in data volume as the transportation company expands. MongoDB's document-based structure and schema-less design align well with the dynamic nature of ride data, facilitating easy adaptation to changing business requirements [1]. Nevertheless, this flexibility may come at the expense of data consistency and the ability to perform complex relational queries, which could be essential for other aspects of the app, such as managing user profiles and securing payment information. Hence, the challenge at hand is to make an informed decision that optimally balances the competing factors of data structure, scalability, and adaptability, ensuring that the chosen database type aligns effectively with the overarching goal of developing a robust and efficient transportation app.

##### Options Considered 🔁

- MongoDB
- MariaDB

##### Decision ⭐

- MongoDB

##### Rationale 💡

After careful consideration, we have decided to implement MongoDB as the database solution for our transportation app. MongoDB's flexibility enables us to adapt better to changing business requirements and rapidly iterate on our app's features without the constraints of a fixed schema.
Furthermore, MongoDB's scalability and performance optimizations [1] make it an excellent choice for our app's real-time tracking and reporting functionalities, ensuring that users can access ride details and track their journeys with minimal latency. While MariaDB databases excel in managing structured data with complex relationships, MongoDB's strengths lie in its ability to handle semi-structured or unstructured data efficiently [1]. Although we recognize that some aspects of our app, such as managing user profiles and securing payment information, may benefit from MariaDB's data consistency and relational capabilities, the predominant use case for our app centers around ride data, where MongoDB's adaptability, scalability, and real-time capabilities are invaluable.

As for MariaDB, it is a robust relational database system, and while it excels in managing structured data, we opted for MongoDB due to the dynamic nature of our ride-related data. MariaDB's fixed schema might introduce unnecessary complexity and rigidity into our database design, making it less suitable for handling the ever-changing ride-related data in our transportation app. Therefore, we chose MongoDB as it better aligns with our need for flexibility and scalability..

***

## Resources

[1] E. Plesky. “MariaDB vs MongoDB: Which is Right for You?MongoDB Vs MariaDB.” Plesk. Accessed: Sept 28th, 2023. [Online]. Available: https://www.plesk.com/blog/various/mariadb-vs-mongodb/.