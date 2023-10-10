# Decision Record for a transportation Mobile App

### By Ana Alarcon and Oriana Bermudez

## _Route Rider_ 🚛

---

## Authentication and Authorization 🔎

### Context:

The team has been assigned the task of developing a mobile app for a modern transportation company. The app's primary purpose is to enable users to book and track rides, access driver details, view ride history, and make secure payments. To accomplish these tasks effectively, several key requirements have been outlined for the app development process.

### Problem Statement 🤔

Implementing a secure authentication and authorization system for both drivers and passengers is vital. Decisions regarding authentication mechanisms (e.g., email/password, social login) and enforcing proper authorization rules must be made.

##### Options Considered 🔁

- Auth0
- OneLogin

##### Decision ⭐

- Auth0

##### Rationale 💡

The decision to choose Auth0 as the preferred Identity and Access Management (IAM) platform for our transportation mobile app, Route Rider, was based on a thorough analysis of available options and alignment with our specific requirements. OneLogin was considered as an authentication and authorization option for our transportation mobile app, but Auth0 was chosen due to its superior developer-friendly approach, extensive support and scalability,and integration flexibility. Additionally, Auth0 offered valuable branding customization options[1] to maintain a consistent user experience while ensuring high security levels, a feature that was lacking in OneLogin. Its extensive support for diverse identity needs and scalability are essential features that align well with the critical need to secure user identities and manage access effectively within our transportation app. Although we anticipate potential cost considerations as user numbers grow, Auth0's strengths in integration flexibility and scalability make it the optimal choice to meet our current and future needs securely and efficiently.

This decision was informed by a comparative analysis of Auth0 and OneLogin in Identity and Access Management (IAM) by J. Flower [1]. The analysis provided valuable insights into the capabilities and benefits of both platforms, ultimately confirming Auth0 as the superior choice for our specific use case. By leveraging Auth0's robust authentication and authorization features, we are confident in our ability to provide a secure and seamless user experience for both drivers and passengers within our transportation app, Route Rider.

---

## Resources

[1] J. Flower. “A Comparative Analysis of Auth0 and OneLogin in Identity and Access Management (IAM).” LinkedIn. Accessed: Sept 28th, 2023. [Online]. Available: https://www.linkedin.com/pulse/comparative-analysis-auth0-onelogin-identity-access-iam-joe-flower/
