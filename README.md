# ✨ GlowChat

GlowChat is a premium, real-time messaging application built with Node.js, Express, and Socket.io. It features a stunning **Dark Glassmorphism** design with smooth animations and instant message delivery.

## 🚀 Features

- **Real-time Messaging**: Instant communication powered by WebSockets (Socket.io).
- **Premium UI**: Modern dark theme with blur effects, gradients, and a sleek "glow" aesthetic.
- **Smart Distinction**: Visually differentiate between sent and received messages.
- **Auto-Scroll**: Conversations automatically stay focused on the latest activity.
- **Robust Backend**: Built-in error handling for port conflicts and environment configurations.

## 🛠️ Tech Stack

- **Frontend**: HTML5, Vanilla CSS (Glassmorphism), JavaScript (ES6+).
- **Backend**: Node.js, Express.
- **Real-Time**: Socket.io.
- **Typography**: Inter (Google Fonts).

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shivam-BugHunter/chat-app.git
   cd chat-app/chat-app
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment (Optional)**:
   You can specify a custom port by creating a `.env` file or setting the variable in your shell:
   ```bash
   export PORT=5000
   ```

## 🏃 Running the App

Start the development server:

```bash
node index.js
```

The application will be available at `http://localhost:3000` (or your custom port).

## 📁 Project Structure

- `index.js`: The Express server and Socket.io signaling logic.
- `index.html`: The fully-contained frontend with the GlowChat design system.
- `package.json`: Project metadata and dependencies.

## 🤝 Contributing

Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

---
Built with ❤️ by Shivam BugHunter