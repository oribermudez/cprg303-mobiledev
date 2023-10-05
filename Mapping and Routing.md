# Decision Record for a transportation Mobile App

### By Ana Alarcon and Oriana Bermudez

## _Route Rider_ 🚛

---

## Mapping and Routing 🗺️

### Context:

The team has been assigned the task of developing a mobile app for a modern transportation company. The app's primary purpose is to enable users to book and track rides, access driver details, view ride history, and make secure payments. To accomplish these tasks effectively, several key requirements have been outlined for the app development process.

### Problem Statement 🤔

The app must provide a map interface with accurate ride routes, estimated arrival times, and driver locations. Selecting the right mapping service and routing algorithm while considering factors such as accuracy and traffic data is crucial.

##### Options Considered 🔁

- Google Maps and WebSocket

##### Decision ⭐

- Google Maps and WebSocket

##### Rationale 💡

After careful consideration, we have chosen to integrate Google Maps for mapping and routing functionality within our app. Google Maps stands out as a reliable choice due to its widespread recognition, extensive map data coverage, and real-time traffic updates[1]. These features align seamlessly with the requirements of our transportation app, ensuring our users experience a familiar, feature-rich mapping interface. This decision not only enhances the overall usability but also reinforces the reliability of our application, crucial for a transportation service.

In addition to our mapping service choice, we have opted for WebSocket for real-time communication. This technology facilitates efficient bidirectional communication[2] between drivers and users, enabling timely updates on ride status and push notifications. WebSocket's versatility in transmitting various data types perfectly complements the multifaceted requirements of our app, enriching its functionality and engagement for both drivers and passengers. This strategic decision positions us to meet the dynamic demands of real-time tracking and communication, enhancing the effectiveness and user experience of our transportation app, Route Rider.

---

## Resources

[1] A. Dziuba. “Mapbox vs. Google Maps vs. OpenStreetMap APIs: Finding the Perfect Fit for Your Next App.” Relevant. Accessed: Sept 28th, 2023. [Online]. Available: https://relevant.software/blog/choosing-a-map-amapbox-google-maps-openstreetmap/

[2] Perfectz Digital. “Comparing WebSocket and Server-Sent Events: Choosing the Right Real-Time Communication Protocol”. LinkedIn. Accessed: Sept 28th, 2023. [Online]. Available: https://www.linkedin.com/pulse/comparing-websocket-server-sent-events-choosing-right/
