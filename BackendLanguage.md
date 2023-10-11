# Decision Record for a transportation Mobile App

### By Ana Alarcon and Oriana Bermudez

## _Route Rider_ 🚛

---

## Backend Language 💻

### Context:

The team has been assigned the task of developing a mobile app for a modern transportation company. The app's primary purpose is to enable users to book and track rides, access driver details, view ride history, and make secure payments. To accomplish these tasks effectively, several key requirements have been outlined for the app development process.

### Problem Statement 🤔

The core challenge revolves around identifying a language that not only aligns with our project's specific requirements but also optimizes development efficiency, performance, and maintainability. The choice of backend language significantly influences the project's scalability, security, and extensibility, making it imperative to evaluate options comprehensively [1]. This decision record should address the multifaceted problem of selecting the ideal backend language by weighing factors such as language performance, ecosystem maturity, developer expertise, and compatibility with our chosen infrastructure, whether it be cloud-based or on-premises [2]. 
Furthermore, it is important to consider the long-term sustainability of the chosen backend language, including its ability to adapt to evolving industry standards and trends.

##### Options Considered 🔁

- Node.js
- Django

##### Decision ⭐

- Node.js

##### Rationale 💡

We have chosen Node.js as the backend language for our cross-platform transportation app with React Native as the UI framework. Node.js's compatibility with JavaScript, which is also used in our React Native frontend, facilitates code sharing and consistency, streamlining our development process. Its non-blocking, event-driven architecture [1] is well-suited for real-time features like tracking and notifications, ensuring a responsive and scalable app. The extensive Node.js ecosystem and active community provide the support and resources needed for long-term maintainability and security [2]. Node.js's performance optimizations and ability to handle a large number of concurrent connections [1] align with the demands of our transportation app, ensuring a seamless and efficient user experience while accommodating the app's growth.

Django is a powerful and popular web framework for Python, known for its robustness and security features. However, we opted for Node.js due to its compatibility with our chosen frontend framework, React Native. Using Node.js ensures a more streamlined development process with a unified JavaScript codebase across both the frontend and backend. While Django is an excellent choice for many web applications, its Python-based ecosystem did not align as seamlessly with our project's frontend technology, making Node.js a more suitable option for our cross-platform transportation app.

---

## Resources

[1] Interview Bit Editors. “Node.js Vs Django: Which One is Better For Web Development?.” Interview Bit. Accessed: Sept 28th, 2023. [Online]. Available: https://www.interviewbit.com/blog/node-js-vs-django/

[2] B. Panchal. “Django vs NodeJS: Which is Better for Web Development?.” Radix. Accessed: Sept 28th, 2023. [Online]. Available: https://radixweb.com/blog/django-vs-nodejs