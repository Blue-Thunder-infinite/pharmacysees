# PharmacySees 🏥💊

Welcome to **PharmacySees**, a full-stack open-source application designed for dynamic pharmacy control. Built using the MEAN stack, this application provides a comprehensive solution for managing pharmacy operations efficiently.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue?style=for-the-badge&logo=github)](https://github.com/Blue-Thunder-infinite/pharmacysees/releases)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

PharmacySees aims to streamline pharmacy management. It provides an intuitive interface for managing inventory, prescriptions, and customer interactions. This project is designed to be user-friendly and adaptable to various pharmacy needs.

## Features

- **User Authentication**: Secure login and registration for users.
- **Inventory Management**: Keep track of stock levels, suppliers, and orders.
- **Prescription Handling**: Manage prescriptions efficiently with easy access for pharmacists.
- **Responsive Design**: Built with Bootstrap 5 for a mobile-friendly experience.
- **Real-time Updates**: Utilize Angular and RxJS for dynamic content updates.
- **File Uploads**: Use Multer for handling file uploads securely.

## Technologies Used

This project employs a variety of technologies to deliver a robust solution:

- **Angular**: For building dynamic single-page applications.
- **Bootstrap 5**: For responsive and modern UI design.
- **CORS**: To handle cross-origin requests.
- **Express.js**: As the backend framework.
- **MongoDB**: For data storage and management.
- **Multer**: For handling file uploads.
- **Node.js**: For server-side JavaScript execution.
- **Nodemon**: For automatic server restarts during development.
- **Prim**: For UI components.
- **RxJS**: For reactive programming.
- **Signals**: For managing state changes.
- **SOLID principles**: To ensure clean and maintainable code.
- **TypeScript**: For type safety and improved developer experience.

## Installation

To set up PharmacySees locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Blue-Thunder-infinite/pharmacysees.git
   cd pharmacysees
   ```

2. **Install Dependencies**:
   For the server:
   ```bash
   cd server
   npm install
   ```

   For the client:
   ```bash
   cd client
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the server directory and configure your MongoDB connection string and other necessary environment variables.

4. **Run the Application**:
   Start the server:
   ```bash
   npm run dev
   ```

   Then, start the client:
   ```bash
   cd client
   ng serve
   ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:4200`.

## Usage

After setting up the application, you can:

- Register a new user or log in with existing credentials.
- Navigate to the inventory section to add or update stock.
- Manage prescriptions by adding new entries or reviewing existing ones.
- Upload relevant documents or images using the file upload feature.

For detailed documentation on each feature, please refer to the [Wiki](https://github.com/Blue-Thunder-infinite/pharmacysees/wiki).

## Contributing

We welcome contributions from everyone! To contribute to PharmacySees:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your branch and create a pull request.

For more detailed guidelines, please refer to the [Contributing Guide](https://github.com/Blue-Thunder-infinite/pharmacysees/blob/main/CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Blue-Thunder-infinite/pharmacysees/blob/main/LICENSE) file for details.

## Contact

For questions or feedback, please reach out:

- **Email**: support@pharmacysees.com
- **GitHub**: [Blue-Thunder-infinite](https://github.com/Blue-Thunder-infinite)

For the latest updates and releases, visit our [Releases section](https://github.com/Blue-Thunder-infinite/pharmacysees/releases).

[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue?style=for-the-badge&logo=github)](https://github.com/Blue-Thunder-infinite/pharmacysees/releases)

Thank you for your interest in PharmacySees! We hope this application meets your pharmacy management needs.