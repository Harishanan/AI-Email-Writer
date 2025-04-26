# Smart Email Writer - Gmail Chrome Extension

An **AI-powered Chrome Extension** that integrates directly into Gmail, helping users write smarter, faster, and more professional email replies. Built with a reactive tech stack and enhanced by Google’s Gemini AI, this tool transforms how you manage your email communications.

---

## 🚀 Features

- **Email Detection**: Automatically detects new incoming emails in Gmail using the `MutationObserver` API.
- **AI Response Generation**: Connects to Google Gemini API to generate human-like, context-aware email replies.
- **Tone Selection**: Choose the tone of the reply (Professional, Friendly, etc.) for different situations.
- **One-Click Copy**: Copy the AI-generated reply instantly to your clipboard.
- **Seamless UI**: Non-intrusive Material UI components that blend naturally into Gmail.
- **Reactive Performance**: Powered by Spring WebFlux and Vite for fast, real-time responses.

---

## 🛠 Tech Stack

**Frontend:**
- React (Vite.js)
- Material UI (MUI)
- Axios
- Chrome Extension API (Manifest V3)
- MutationObserver API

**Backend:**
- Java Spring Boot
- Spring WebFlux (Reactive Programming)
- Lombok

**AI Service:**
- Google Gemini API

**Integration:**
- Chrome Browser Extension
- Gmail Web Interface

---

## 📸 Screenshots

| Feature | Screenshot |
|:--------|:-----------|
| Email Detection in Gmail | ![Email Detection](./screenshots/email_detection.png) |
| AI Reply Generator Interface | ![AI Reply Generator](./screenshots/ai_reply_generator.png) |

*(Make sure to add actual images inside a `screenshots/` directory.)*

---

## 📦 Installation

### Backend Setup

```bash
# Navigate to the backend directory
cd backend

# Build the Spring Boot project
./mvnw clean install

# Run the backend server
java -jar target/backend-0.0.1-SNAPSHOT.jar
```

### Frontend Setup

```bash
# Navigate to the frontend directory
cd frontend

# Install dependencies
npm install

# Build the Chrome extension
npm run build
```

### Load Chrome Extension

1. Open Chrome and visit `chrome://extensions/`.
2. Enable **Developer Mode**.
3. Click **Load Unpacked**.
4. Select the `frontend/dist` folder.

**Note**: Ensure the backend server is running before using the extension.

---

## 🧰 Requirements

- Google Gemini API Key
- Java 17+
- Node.js 18+
- Chrome (latest version)
- Gmail Account

---

## 🎯 Roadmap

- [ ] OAuth2 Integration for Gmail API
- [ ] Direct insertion into Gmail compose box
- [ ] Advanced Tone Customization
- [ ] Multi-language Support

---

## 🤝 Contribution Guidelines

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

Please open an issue for major feature requests first.

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🙌 Acknowledgements

- [Google Gemini API](https://deepmind.google/technologies/gemini/)
- [Material UI](https://mui.com/)
- [Spring WebFlux Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html)

---

## 💬 Contact

Created with ❤️ by [Your Name]. Feel free to reach out!

