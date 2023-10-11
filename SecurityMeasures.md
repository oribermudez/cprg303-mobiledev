# Decision Record for a transportation Mobile App

### By Ana Alarcon and Oriana Bermudez

## _Route Rider_ 🚛

---

## Security Measures 🔒

### Context
The team has been assigned the task of developing a mobile app for a modern transportation company. The app's primary purpose is to enable users to book and track rides, access driver details, view ride history, and make secure payments. To accomplish these tasks effectively, several key requirements have been outlined for the app development process.

### Problem Statement 🤔

The decision to implement security measures, as necessitated by the sensitivity of user information and financial transactions, presents a multifaceted challenge for our organization. In an era of ever-increasing cyber threats and evolving regulatory requirements, the team faces the daunting task of determining the most effective and efficient security measures to protect our assets while ensuring compliance with industry standards and best practices.

Striking the right balance between security and usability remains a persistent dilemma, as overly stringent measures may lead to user dissatisfaction and operational inefficiencies, while lax security could expose us to significant risks and potential data breaches [1]. This decision record aims to address the pressing issue of defining and implementing a comprehensive security framework that safeguards sensitive data and financial transactions, all while considering the dynamic landscape of security threats and the evolving expectations of our users and regulatory bodies.

##### Options Considered 🔁

- Data encryption
- Password complexity rules
- Multi-factor authentication
- VPN
- Session Management
- Data Validation and Sanitization
- Error Handling
- Incident Response Plan

##### Decision ⭐

- Data encryption, multi-factor authentication, and incident response plan

##### Rationale 💡

Among the options we've considered for our security strategy, three key choices stand out as exceptionally important:

Data Encryption is a fundamental pillar of our security approach. It involves converting sensitive user information and financial data into a coded format that is nearly impossible for unauthorized individuals to decipher [1]. This aligns with industry standards and best practices for every application.

Multi-Factor Authentication is another important element. It adds a layer of security by requesting additional ways to verify the user account, such as passwords and biometrics [2]. This significantly reduces the risk of unauthorized access, even if passwords are compromised, which is vital given the sensitive nature of financial transactions.

Lastly, an Incident Response Plan is essential. It's a structured strategy for how we'll handle security incidents when they occur [3]. Since no security system is infallible, having a well-defined plan enables us to react swiftly and effectively to mitigate potential harm and minimize disruptions. This also demonstrates our commitment to proactive security and ensures compliance with legal requirements related to data protection.

While other options were considered, they were not chosen as the core elements of our security strategy because they didn't directly address the paramount concerns of safeguarding sensitive data and ensuring robust account security in the context of our transportation app. Each of the selected options plays a crucial role in forming a comprehensive security framework to protect our assets and user data while complying with industry standards and regulations.

 ---

## Resources

[1] Maropost. “8 Best Practices For Your Mobile App Security in 2022.” Maropost. Accessed: Sept 28th, 2023. [Online]. Available: https://www.maropost.com/8-best-practices-for-your-mobile-app-security-in-2022/

[2] S. Thelen. “Ensuring Secure App Development: Best Practices” Polymetis Apps. Accessed: Sept 28th, 2023. [Online]. Available:https://www.polymetis-apps.com/post/ensuring-secure-app-development-best-practices

[3] S. Jurgenson. “Building Secure Apps: Best Practices for Protecting User Data.” Appmaster. Accessed: Sept 28th, 2023. [Online]. Available:https://appmaster.io/blog/best-practices-for-protecting-user-data