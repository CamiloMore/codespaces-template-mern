# 🚀 MERN Codespaces Template

Welcome to the **codespaces-template-mern** repository! This template provides a streamlined setup for developing full-stack applications using the MERN stack: MongoDB, Express, React (via Vite), and Node.js. You can quickly get started with your projects using this containerized environment.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue?style=for-the-badge&logo=github)](https://github.com/CamiloMore/codespaces-template-mern/releases)

## 📦 Table of Contents

1. [Features](#features)
2. [Technologies](#technologies)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
4. [Usage](#usage)
5. [Folder Structure](#folder-structure)
6. [Contributing](#contributing)
7. [License](#license)
8. [Support](#support)

## 🌟 Features

- **Full-Stack**: Build applications with both front-end and back-end capabilities.
- **Containerized**: Run your application in a consistent environment using Docker.
- **Fast Setup**: Get started quickly with pre-configured settings.
- **Scalable**: Easily add new features as your project grows.
- **Community Support**: Join a growing community of developers.

## 💻 Technologies

This template uses the following technologies:

- **MongoDB**: A NoSQL database for storing data.
- **Express**: A web application framework for Node.js.
- **React**: A JavaScript library for building user interfaces, enhanced with Vite for faster development.
- **Node.js**: A JavaScript runtime for building server-side applications.

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Docker**: For running containerized applications.
- **Node.js**: To run JavaScript on the server side.
- **Git**: For version control.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/CamiloMore/codespaces-template-mern.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd codespaces-template-mern
   ```

3. **Run the setup script**:

   ```bash
   ./setup.sh
   ```

4. **Start the application**:

   ```bash
   docker-compose up
   ```

5. **Visit your application**:

   Open your web browser and go to `http://localhost:3000`.

## 🔧 Usage

Once the application is running, you can start developing your features. The front-end code resides in the `client` folder, while the back-end code is in the `server` folder. 

### Front-End Development

1. **Navigate to the client directory**:

   ```bash
   cd client
   ```

2. **Run the development server**:

   ```bash
   npm run dev
   ```

3. **Open your browser**:

   Visit `http://localhost:3000` to see your React application.

### Back-End Development

1. **Navigate to the server directory**:

   ```bash
   cd server
   ```

2. **Run the server**:

   ```bash
   npm start
   ```

3. **Test your API**:

   Use tools like Postman or curl to interact with your API endpoints.

## 📂 Folder Structure

The project follows a structured layout for easy navigation:

```
codespaces-template-mern/
├── client/                # Front-end application
│   ├── public/            # Static files
│   ├── src/               # React components
│   └── package.json       # Front-end dependencies
├── server/                # Back-end application
│   ├── models/            # MongoDB models
│   ├── routes/            # Express routes
│   └── package.json       # Back-end dependencies
├── docker-compose.yml     # Docker configuration
└── README.md              # Project documentation
```

## 🤝 Contributing

We welcome contributions! If you want to help improve this template, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:

   ```bash
   git checkout -b feature/YourFeature
   ```

3. **Make your changes** and commit them:

   ```bash
   git commit -m "Add your message"
   ```

4. **Push to your branch**:

   ```bash
   git push origin feature/YourFeature
   ```

5. **Open a pull request**.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🆘 Support

For issues, please check the [Releases](https://github.com/CamiloMore/codespaces-template-mern/releases) section. If you need further assistance, feel free to open an issue on GitHub.

---

Thank you for checking out the **codespaces-template-mern** repository! We hope this template helps you build amazing applications quickly and efficiently.