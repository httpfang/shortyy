
# 🔗 Shortyy - URL Shortener

Welcome to **Shortyy**! 🚀 A simple and efficient URL shortener to make your links look sleek, memorable, and easy to share. Whether you're a developer or just someone who wants to simplify their links, Shortyy has you covered. ✨

## 🌟 Features

- 🔗 Shorten long URLs into concise, easy-to-share links.
- 📊 Track the number of clicks on each shortened URL.
- 🌍 Custom domain support for a personalized touch.
- 🔒 Securely stores and redirects links.

## 📸 Preview
![Shortyy Screenshot] https://shawtyshort.netlify.app/banner1.jpg *(Replace this with an actual screenshot of the app)*

---

## 🚀 Getting Started

Follow these steps to set up **Shortyy** locally and start shortening URLs in no time! ⏱️

### Prerequisites

Before you begin, make sure you have the following installed:

- **Node.js** (v14 or higher)
- **MongoDB** (or a MongoDB connection string if using MongoDB Atlas)
- **Git**

### 📥 Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/httpfang/Shortyy.git
cd Shortyy
```

### 📦 Install Dependencies

Use `npm` to install all necessary packages:

```bash
npm install
```

### 🔧 Environment Setup

Create a `.env` file in the root of the project with the following details:

```plaintext
MONGO_URI=your_mongodb_connection_string
PORT=3000
BASE_URL=http://localhost:3000
```

Replace `your_mongodb_connection_string` with your actual MongoDB URI.

### 🚀 Start the Application

After setting up the environment, start the server:

```bash
npm start
```

By default, Shortyy runs on [http://localhost:3000](http://localhost:3000). You can access the app in your browser and start shortening URLs right away!

---

## 🤖 API Documentation

Shortyy also provides a simple API for developers to integrate URL shortening into their own projects. Here’s a quick overview:

- **POST /api/shorten** - Shorten a URL
  - **Body**: `{ "url": "https://example.com" }`
- **GET /:shortcode** - Redirect to the original URL

_For more detailed API documentation, check the source code or run the app._

---

## 🛠️ Development

To run the app in development mode with **nodemon** (if you have it installed):

```bash
npm run dev
```

This will automatically restart the server when you make changes to the code.

---

## 🧑‍💻 Contributing

We welcome contributions! 🎉 Please feel free to open issues or submit pull requests to improve **Shortyy**.

1. **Fork the repository** and clone your fork locally.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them.
4. Push your branch and submit a pull request.

---

## 🎉 Show Your Support

If you like **Shortyy**, please ⭐️ the repo to show your support! 

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [Fang](https://github.com/httpfang)
