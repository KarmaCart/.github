# KarmaCart: A Sustainable Shopping Web Application Showcase

---

## Introduction

Welcome to KarmaCart, a web application developed as a learning project to explore new technologies and promote sustainable shopping practices. With KarmaCart, I aimed to create a functional prototype that demonstrates my skills as a developer while addressing real-world challenges in sustainability.

## Demo
The KarmaCart application can be accessed at [https://karma-cart.andersbuck.dev/](https://karma-cart.andersbuck.dev/). In the demo, users can experience the barcode scanning feature, product browsing, and explore products information on ethical practices as well as their Ethical Score.

![GIF of a demo of the KarmaCart web application.](https://github.com/KarmaCart/.github/blob/main/profile/KarmaCart-Demo.gif)

## Technology Stack

KarmaCart was built using a modern and robust technology stack, including:

- **Frontend**: React, JavaScript, Ant Design
- **Backend**: Node, TypeScript
- **IaC (Infrastructure as Code)**: AWS CDK (Cloud Development Kit)
- **AWS Services**: CloudFront, S3, API Gateway, Lambda, DynamoDB
- **AI Consultation**: GPT-4

## Architecture

- KarmaCart follows a serverless architecture deployed to individual Engineering and Production AWS Accounts. This setup allows for separate environments for managing changes to the application.
- GitHub actions gain temporary access using STS to execute synthesized CloudFormation from the AWS CDK.
- Devices access static and dynamic content of the web application using CloudFront and the API Gateway.

![Architecture diagram of the KarmaCart web application.](https://github.com/KarmaCart/.github/blob/main/profile/KarmaCart-AR.png)

## Skills Utilized

Through KarmaCart, I aimed to showcase the following key skills and competencies:

- **Full-stack Development**: Demonstrated proficiency in both frontend and backend development, from designing a user interfaces to implementing server-side logic.

- **DevOps and Infrastructure Management**: Leveraged AWS Cloud Development Kit (CDK) for infrastructure as code (IaC) to define and deploy KarmaCart's architecture. Implemented CI/CD pipelines with GitHub Actions for automated testing, deployment, and rollback processes. Utilized AWS services such as CloudFront, S3, API Gateway, Lambda, and DynamoDB to ensure scalable and reliable application deployment.

- **Responsive Design**: Ensured optimal user experience across various devices and screen sizes through responsive design principles and mobile-first development approach.

## Reflect

While KarmaCart is a successful demo web application, if I was to implement something similar again I would:

- **TSX Frontend**: Write front-end in in TypeScript (TSX) making it easier to develop in the various layers of the application (Backend and IaC code being in TypeScript).
- **Structure CSS**: Find a better pattern for structuring the CSS. With it being a small application it was manageable to include inline CSS but if this were to scale it would be difficult to manage.
- **Relational DB**: Experiment with a serverless relational DB for more flexibility. DynamoDB suits a use case where performance is more critical and a sacrafices flexibility.
- **Better Barcode Scanner**: While the barcode scanner library I chose works, it is not very flexible and has low performance when used on a low quality camera. Creating a barcode scanner from a lower level api might suit the applications needs better.

## Connect With Me

Feel free to reach out to me at [andersbuck.dev@gmail.com](andersbuck.dev@gmail.com).

---
