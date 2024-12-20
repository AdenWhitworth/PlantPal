<img width="80" src="https://github.com/AdenWhitworth/PlantPal_Front-End/raw/master/src/Images/PlantPal%20Logo.svg" alt="PlantPal Logo">

# PlantPal

Welcome to the PlantPal project! This repository contains links to my personal projects related to the PlantPal application, which helps plant enthusiasts monitor and manage their plants through a seamless interface and IoT integration.

<img width="600" src="https://github.com/AdenWhitworth/PlantPal_Front-End/raw/master/src/Images/PlantPal%20Mockup.png" alt="PlantPal Device">

## Table of Contents
- [PlantPal Live Demo](#plantpal-live-demo)
- [Front-End](https://github.com/AdenWhitworth/PlantPal_Front-End)
- [Back-End](https://github.com/AdenWhitworth/plantpal_server)
- [Hardware](https://github.com/AdenWhitworth/PlantPal_hardware)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## PlantPal Live Demo

The PlantPal application is live and can be accessed at [PlantPal Demo](https://www.plantpalhome.com/). This application integrates seamlessly with the PlantPal back-end, offering an intuitive experience for managing your plants remotely.

<img width="600" src="https://github.com/AdenWhitworth/aden_whitworth_portfolio/raw/master/src/Images/plantpal_demo.png" alt="PlantPal Demo">

<img width="600" src="https://github.com/AdenWhitworth/PlantPal_Front-End/raw/master/src/Images/PlantPal_live.jpg" alt="PlantPal Live device">

### Test User Credentials

You can explore the full functionality of the PlantPal application using the following demo account:

- **Email:** support@plantpalhome.com
- **Password:** testpassword123

Please note that this test account is connected to an actual PlantPal device in my kitchen, so any interactions may affect its operation. Feel free to explore, but please be considerate of its usage!

## Front-End: [PlantPal Front-End](https://github.com/AdenWhitworth/PlantPal_Front-End)

The web-based user interface for the PlantPal application, built with React and designed for seamless user experience.

## Back-End: [PlantPal Back-End](https://github.com/AdenWhitworth/plantpal_server)

The Node.js backend API and serverless AWS Lambda Functions for managing plant data, user authentication, and real-time device communication.

## Hardware: [PlantPal Hardware](https://github.com/AdenWhitworth/PlantPal_hardware)

The hardware repository containing the ESP32 code, PCB schematic, and 3D models for the PlantPal device.

## Technologies Used
- **React**: A powerful JavaScript library for building user interfaces, enabling the development of dynamic and responsive web applications.
- **TypeScript**: A strongly typed superset of JavaScript that enhances code quality and provides better tooling and type safety during development.
- **HTML/JSX**: The foundational markup language used for structuring the components of the React application, ensuring semantic and accessible content.
- **Web Bluetooth**: A JavaScript library that enables communication with Bluetooth Low Energy (BLE) devices directly from the web, enhancing the application's connectivity features.
- **Axios**: A promise-based HTTP client that simplifies making API requests and handling responses, making it easier to interact with back-end services.
- **CSS**: Styles the application with a modern aesthetic, allowing for flexible and maintainable design.
- **React Router**: A library that enables dynamic routing in the application, providing a seamless navigation experience for users.
- **Figma**: A collaborative design tool used for crafting the application's UI/UX, allowing for prototyping and feedback before implementation.
- **MUI (Material-UI)**: A popular React component library that implements Google's Material Design, providing pre-designed components for charts, gauges, and more, enhancing visual consistency.
- **Socket.IO**: A library that facilitates real-time, bidirectional communication between clients and servers, crucial for features like live updates and notifications.
- **Jest**: A delightful JavaScript testing framework that ensures the reliability of the application by allowing developers to write unit tests for their functions and components.
- **TypeDoc**: A documentation generator for TypeScript projects that creates consistent and user-friendly API documentation, making it easier for developers to understand and use the codebase.
- **Node.js**: Backend runtime environment for executing JavaScript on the server.
- **Express.js**: Web framework for building the RESTful API.
- **MySQL**: SQL database for storing user, plant, and device data.
- **JWT (JSON Web Tokens)**: Used for secure authentication.
- **Nodemailer**: A robust email-sending library for Node.js applications, enabling seamless integration with email services for confirming purchases and resetting passwords.
- **Amazon Web Services (AWS)**: 
  - **RDS**: For cloud-hosted SQL database management.
  - **IoT Core**: For handling MQTT protocols.
  - **Lambda**: For processing event-driven changes in SQL and MQTT data.
- **C++**: A powerful object-oriented programming language used for developing the firmware of the PlantPal hardware. It provides the necessary features for efficient memory management and system-level programming.
- **C**: A foundational programming language utilized for low-level hardware control and interfacing. It allows direct manipulation of memory and hardware resources, which is essential for embedded systems development.
- **Arduino**: An open-source electronics platform based on easy-to-use hardware and software. The Arduino IDE is used to write and upload code to the ESP32 microcontroller, enabling rapid prototyping and development.
- **MQTT**: A lightweight messaging protocol designed for low-bandwidth, high-latency, or unreliable networks. MQTT is used for communication between the PlantPal hardware and AWS IoT Core, allowing for efficient data exchange and remote monitoring.
- **BLE (Bluetooth Low Energy)**: A wireless technology designed for short-range communication with low power consumption. BLE is utilized for connecting the PlantPal hardware to mobile devices for real-time monitoring and control.
- **Doxygen**: A documentation generation tool that allows developers to create comprehensive documentation for their codebase. Doxygen is used to generate user-friendly documentation for the PlantPal hardware project, making it easier for other developers to understand and contribute to the project.
- **GitHub Actions**: A robust CI/CD platform that automates workflows such as testing, building, and deploying the application. GitHub Actions ensures consistent code quality and streamlines deployments to production environments.
- **Vercel**: A cloud platform for hosting front-end applications. Vercel handles building and deploying the application, providing a seamless and fast experience for hosting React-based projects.
- **DigitalOcean**: A scalable cloud hosting platform used for deploying and managing the backend. The project uses DigitalOcean's App Platform for hosting and integrates with the DigitalOcean API for automated deployments.

## Getting Started
Instructions for setting up each project can be found in their respective repositories.

## Contribution Guidelines
Feel free to open issues or submit pull requests for any improvements or bug fixes!

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
