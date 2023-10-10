# Decision Record for a transportation Mobile App

### By Ana Alarcon and Oriana Bermudez

## _Route Rider_ 🚛

---

## Real-time Location 📍

### Context:

The team has been assigned the task of developing a mobile app for a modern transportation company. The app's primary purpose is to enable users to book and track rides, access driver details, view ride history, and make secure payments. To accomplish these tasks effectively, several key requirements have been outlined for the app development process.

### Problem Statement 🤔

Implementing real-time tracking of both driver and passenger locations requires choosing appropriate technologies like WebSocket or server-sent events to establish and maintain a continuous connection between the app and the server.

##### Options Considered 🔁

- WebSocket
- Server-sent events

##### Decision ⭐

- WebSocket

##### Rationale 💡

In the realm of real-time location updates for our ride booking and tracking platform, the team carefully weighed the options of WebSocket and server-sent events. After a comprehensive evaluation considering factors like bidirectional communication, efficiency, and versatility, we opted for WebSocket as the preferred technology. WebSockets emerged as the optimal choice due to their ability to establish and maintain continuous bidirectional communication between drivers and users within our app [1]. This feature is paramount for promptly conveying ride status updates and delivering timely push notifications, ensuring a seamless user experience.

On the other hand, server-sent events, while a viable technology, did not offer bidirectional communication or the same level of versatility in transmitting diverse data types, making WebSocket the superior choice for real-time location updates in our transportation app.

Furthermore, the versatility of WebSockets, enabling the transmission of diverse data types such as text, video, and images [1], perfectly aligned with the multifaceted requirements of our app. This functionality enriches the app's capabilities and enriches the overall user experience by providing a more dynamic and engaging platform for both drivers and passengers. The decision to leverage WebSockets was driven by its ability to meet our project's needs effectively and contribute to the real-time tracking and communication requirements vital for our platform's success.

---

## Resources

[1] Perfectz Digital. “Comparing WebSocket and Server-Sent Events: Choosing the Right Real-Time Communication Protocol”. LinkedIn. Accessed: Sept 28th, 2023. [Online]. Available: https://www.linkedin.com/pulse/comparing-websocket-server-sent-events-choosing-right/
