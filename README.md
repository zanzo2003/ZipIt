<div align="center">
  <h1 align="center">ZipLink 🔗</h1>
  <p align="center">
    <strong>Snip It. Share It. Track It.</strong>
    <br />
    A powerful, open-source URL shortener that combines robust analytics, enhanced security, and lightning-fast performance.
  </p>
  <p align="center">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
    <img src="https://img.shields.io/github/stars/shashwath-bhaskar/ZipLink-Snip-It.-Share-It.-Track-It.?style=social" alt="GitHub stars">
    <img src="https://img.shields.io/github/forks/shashwath-bhaskar/ZipLink-Snip-It.-Share-It.-Track-It.?style=social" alt="GitHub forks">
  </p>
  <br />
</div>

## ✨ Features

ZipIt streamlines the process of shortening URLs, making sharing links effortless and efficient. Our platform is built to deliver the ultimate link management experience.

-   🔗 **Simple URL Shortening**: A clean and intuitive interface for creating short, memorable URLs in just a few clicks.
-   📊 **Powerful Analytics**: Gain deep insights with a comprehensive analytics dashboard. Track clicks, geographic data, and referral sources in real-time to optimize your campaigns.
-   🛡️ **Enhanced Security**: Rest assured with robust security measures. All links are protected, and user data is secured using JWT-based authentication.
-   ⚡ **Fast & Reliable**: Enjoy lightning-fast redirects and high uptime thanks to a reliable, high-performance infrastructure.

## 🚀 Tech Stack

-   **Backend**: Java, Spring Boot, Spring Security, JWT
-   **Frontend**: React.js, React Router, Framer Motion, Tailwind CSS
-   **Database**: MySQL / PostgreSQL

## 📋 Prerequisites

-   Java JDK 17 or later
-   Node.js v18 or later
-   A running instance of MySQL or PostgreSQL

## ⚙️ Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### 1. Clone the Repository

```bash
git clone https://github.com/shashwath-bhaskar/ZipLink-Snip-It.-Share-It.-Track-It..git
cd ZipLink-Snip-It.-Share-It.-Track-It.
```

### 2. Backend Setup

The backend is a Spring Boot application.

1.  **Navigate to the backend directory**:
    The backend code is located in the root of the `Ziplink` module.

2.  **Configure Environment Variables**:
    The application uses environment variables for configuration. You can set them in your IDE's run configuration or your shell profile.

    ```sh
    # Database credentials
    DB_PSWD="your_database_password"
    DB_USR="your_database_username"

    # JWT Configuration
    JWT_SECRET="your_super_secret_jwt_key_with_at_least_256_bits"
    JWT_EXP="86400000" # Expiration time in milliseconds (e.g., 24 hours)

    # CORS Allowed Origins
    ORIGINS="http://localhost:3000" # Frontend URL
    ```

3.  **Update `application.properties`**:
    Make sure your `src/main/resources/application.properties` file is configured to connect to your database.

4.  **Run the application**:
    You can run the `ZiplinkApplication` main class from your IDE or build and run the JAR file.

### 3. Frontend Setup

The frontend is a React application.

1.  **Navigate to the frontend directory**:
    ```bash
    cd ziplink-frontend
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Start the development server**:
    ```bash
    npm run dev
    ```

    The application will be available at `http://localhost:3000` (or another port if 3000 is in use).

## 🖼️ Screenshots

*(This is a great place to add screenshots of your application's landing page, dashboard, and analytics view to give users a visual preview.)*

**Landing Page**
!Landing Page

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.


