# QuikShort-URL Shortener and QR Code Generator

## Introduction

QuikShort is a web application that allows you to easily shorten long URLs and convert plain text into QR codes. With a sleek and user-friendly interface, QuikShort streamlines the process of creating shareable links and QR codes for efficient sharing.

Checkout web-app demo here - [QuikShort](https://serene-babka-f5ce1d.netlify.app/)

## Table of Contents

- [Introduction](#introduction)
- [Screenshot](#screenshot)
- [Technologies](#technologies)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Screenshot

![QuikShort](./client/src/screenshot/Screenshot1.png)
![QuikShort](./client/src/screenshot/Screenshot2.png)
![QuikShort](./client/src/screenshot/Screenshot3.png)
![QuikShort](./client/src/screenshot/Screenshot4.png)
![QuikShort](./client/src/screenshot/Screenshot5.png)

## Technologies

- MongoDB for database
- Express.js node js framework
- React for frontend
- Node.js for backend

## Features

- URL Shortening: Shorten long URLs to create concise and easy-to-share links.
- QR Code Generation: Convert plain text, such as URLs or any other information, into QR codes for quick and easy scanning.
- Customizable Short URLs: Customize the generated short URLs to make them more memorable or brand-friendly.
- User Analytics: Gain insights into link performance with an integrated analytics dashboard, providing click statistics and geographic data.
- User Authentication: Create an account or log in to save and manage your shortened URLs and generated QR codes securely.

## Getting Started

### Prerequisites

Before running the project, make sure you have the following prerequisites installed on your system:

- Node.js and npm: Install from [https://nodejs.org/](https://nodejs.org/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/unkitsingh0/QuikShort
    cd your-project
    npm install
   ```

2. Set up the MongoDB connection:

   - Ensure you have MongoDB installed and running on your system.
   - Create a MongoDB database for the BookMyShow project and note down the connection string.

3. Configure the application:

   - Create a `.env` file in the root directory of the project.
   - Add the following environment variables to the `.env` file:

   ```
   PORT=8080                  # The port on which the application will run
   MONGODB_URI=your_mongodb_uri_here  # The MongoDB connection string
   ```

### Usage

1. Start the server:

   ```bash
   npm start

   ```

2. Open your web browser and point it to the BookMyShow application at `http://localhost:3000`.

3. Dive into the captivating world of cinema as you peruse a captivating array of available movies. Once you've made your selection, effortlessly access showtime details.

4. Time to set the stage! Choose your preferred showtime and secure the seats that suit your movie-going experience.

5. With the seats reserved, you're just a few steps away from movie magic. Simply follow the prompts to complete the booking process by providing the required information.

6. On the homepage, relish the convenience of quick access to the details of your most recent movie booking.

### Contributing

We embrace contributions from our community of enthusiasts! If you're eager to contribute to our project, we'd appreciate it greatly. Just adhere to these guidelines:

```markdown
## Contributing

- Fork the repository.
- Create a new branch for your feature/bug fix.
- Make your changes and test thoroughly.
- Create a pull request with a clear description of your changes.
```

## Contributions

This project was conceived, designed, and implemented by Ankit Singh. As the sole author and developer, I have crafted every aspect of this project, from inception to completion.

While this project was created independently, I appreciate your interest and encourage you to explore and use it. If you have any questions, feedback, or suggestions, please feel free to reach out.

Thank you for checking out my work!

## License

This project is open source and is available under the [MIT License](LICENSE). The MIT License is a permissive open-source license that allows you to use, modify, and distribute this software for free, provided you include the original copyright notice and disclaimers.
For more details, please read the [LICENSE](LICENSE) file.

## Acknowledgements

QuikShort's development has been possible with the support and contributions from various individuals and open-source projects. We would like to express our gratitude to the following:

1. Frontend dependency or package

- **@fortawesome/fontawesome-svg-core, @fortawesome/free-solid-svg-icons, @fortawesome/react-fontawesome** - FontAwesome provides a comprehensive set of scalable vector icons, enhancing the visual appeal of QuikShort.

- **@reduxjs/toolkit** - The Redux Toolkit simplifies state management in React applications, making it more efficient and maintainable.

- **axios** - A promise-based HTTP client, Axios facilitates seamless communication with servers and external APIs.

- **bootstrap** - Bootstrap, a powerful front-end framework, contributes to creating a modern and responsive design for QuikShort.

- **copy-to-clipboard** - This library enables the easy implementation of the copy-to-clipboard functionality, enhancing user experience.

- **file-saver** - FileSaver.js facilitates the saving of files on the client-side, enriching QuikShort's functionality.

- **gh-pages** - The gh-pages package simplifies the deployment of QuikShort to GitHub Pages.

- **html2canvas** - html2canvas is instrumental in generating screenshots of the web page, a crucial feature for QuikShort's QR code generation.

- **mdb-react-ui-kit** - The MDB React UI Kit provides a collection of UI components for React, contributing to the overall visual aesthetics and user experience.

- **react, react-dom** - The core libraries for building user interfaces in React, powering QuikShort's frontend.

- **react-bootstrap, react-cookie, react-hot-toast, react-loader-spinner, react-qr-code, react-redux, react-router-dom** - These dependencies enhance QuikShort with various features like Bootstrap components, cookie handling, toast notifications, loading spinners, QR code generation, and routing.

- **react-scripts** - React Scripts provides scripts and configuration for Create React App, streamlining the development process.

- **react-tooltip** - The React Tooltip library adds interactive tooltips to QuikShort, improving user guidance and interaction.

- **web-vitals** - Web Vitals contributes to the measurement of real-world performance of QuikShort, ensuring optimal user experiences.

2. Backend dependency or package

- **bcrypt** - Bcrypt is a key component in securing user passwords through hashing and salting, enhancing the overall security of QuikShort.

- **cors** - The CORS middleware allows QuikShort to handle cross-origin resource sharing, facilitating secure communication between the frontend and backend.

- **dotenv** - The dotenv library simplifies the configuration of environment variables, ensuring a secure and organized setup for QuikShort.

- **express** - Express.js is the foundational web framework for QuikShort, enabling the creation of robust and scalable APIs.

- **jsonwebtoken** - Jsonwebtoken is crucial for secure user authentication and authorization in QuikShort through the generation and validation of JSON Web Tokens.

- **mongoose** - Mongoose is an elegant MongoDB object modeling tool, simplifying interactions with the MongoDB database and enhancing data management in QuikShort.

- **nanoid** - Nanoid is employed for the generation of unique and concise IDs, a key feature in QuikShort's URL shortening process.

- **nodemailer** - Nodemailer enables the sending of emails from the server, contributing to features like account verification and password reset in QuikShort.

We express our gratitude to the developers and communities behind these dependencies for their hard work and dedication, which has been crucial in making QuikShort a robust and feature-rich web application.

---

Welcome to QuikShort! Whether you're here to shorten URLs, generate QR codes, or explore our web app's features, we're thrilled to have you on board.

Should you have any questions or inquiries, please don't hesitate to get in touch with us. You can raise an issue within the repository, and we'll be more than happy to assist you.

Our goal is to make your experience with QuikShort delightful. Enjoy the convenience of quick link shortening, seamless QR code generation, and more. We're here to ensure your journey with QuikShort is smooth and enjoyable.

Thank you for choosing QuikShort! Happy linking and QR coding!
