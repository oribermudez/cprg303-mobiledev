# Decision Record for a transportation Mobile App

### By Ana Alarcon and Oriana Bermudez

## _Route Rider_ 🚛

---

## Payment Integration 💳

### Context

The team has been assigned the task of developing a mobile app for a modern transportation company. The app's primary purpose is to enable users to book and track rides, access driver details, view ride history, and make secure payments. To accomplish these tasks effectively, several key requirements have been outlined for the app development process.

### Problem Statement 🤔

Integrating payment gateways into our system is a crucial step in ensuring secure and convenient payment transactions for our users. However, this presents a multifaceted challenge that extends beyond mere technical integration. The primary concern revolves around security, as payment transactions involve sensitive financial data, making our system an attractive target for cyber threats. Therefore, we must meticulously assess and select payment gateway providers that prioritize robust security measures, including encryption, tokenization, and compliance with industry standards such as PCI DSS [1]. Therefore, this decision record aims to address the complex problem of payment gateway integration, meticulously weighing security, usability, geographical reach, and financial implications, ultimately ensuring that our users can make secure and convenient payments while maintaining the integrity of our system and financial data.

##### Options Considered 🔁

- Paypal
- Stripe

##### Decision ⭐

- Stripe

##### Rationale 💡

After thorough evaluation, our decision to choose Stripe as the payment gateway for our transportation app is based on several key considerations that align with our project's specific needs and goals. While PayPal is a reputable and widely used payment gateway, Stripe is renowned for its robust security measures, including PCI DSS compliance, which ensures the highest standards of data protection for our users' sensitive financial information [2]. This is especially crucial in the transportation industry, where trust and security are important. While PayPal also emphasizes security, Stripe's commitment to security, data encryption, and tokenization [2] significantly mitigates the risk of data breaches and instills confidence in our users when making payments through our app, making Stripe a better fit for the company's objectives.

Moreover, Stripe's user-friendly and developer-friendly interface provides a seamless integration process, minimizing disruptions to our app's user experience and reducing the technical complexity of implementation. Additionally, Stripe's competitive transaction fees and transparent pricing structure help us optimize operational costs while maintaining affordability for both our users and our business. In summary, Stripe's comprehensive security, ease of integration, global reach, and cost-effectiveness [1] make it the ideal choice for our transportation app, ensuring secure and convenient payment transactions that enhance user trust and satisfaction.

---

## Resources

[1] Tipalti. “Comparing the Top Online Payment Software Solutions: Stripe vs. PayPal vs. Square.” Tipalti. Accessed: Sept 28th, 2023. [Online]. Available: https://tipalti.com/best-online-payment-software/

[2] D. Strojny. “Stripe vs PayPal: Who should you choose?.” Memberful. Accessed: Sept 28th, 2023. [Online]. Available: https://memberful.com/blog/stripe-vs-paypal/#:~:text=with%20Memberful%20%E2%86%92-,Security,very%20stable%20and%20secure%20platforms.
