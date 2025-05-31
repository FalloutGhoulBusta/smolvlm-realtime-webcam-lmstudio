# 📷 Realtime Webcam Interaction App (Powered by LM Studio)

A lightweight web application for real-time interaction with your webcam, leveraging **LM Studio** as the backend API for vision-language processing.

---

## 🚀 Features
- 🎥 **Live Webcam Feed**: Stream your webcam directly in the browser.
- 🤖 **LM Studio Integration**: Send frames to **LM Studio** for real-time analysis (supports models like `moondream2`).
- 📝 **Customizable Prompts**: Dynamically change instructions (e.g., "What do you see?").
- ⏱️ **Adjustable Intervals**: Control how often frames are sent (100ms to 2s).
- 🔄 **Real-Time Responses**: Display LM Studio's outputs instantly.

---

## 📦 Prerequisites
1. **LM Studio**: Download and run [LM Studio](https://lmstudio.ai/) locally.
   - Ensure the **Local Inference Server** is active (default: `http://localhost:1234`).
   - Load a compatible vision-language model (e.g., `moondream2`).
   - For detailed setup, see [`setup.md`](./setup.md).

---

## 🛠️ Setup & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/smolvlm-realtime-webcam.git
   cd smolvlm-realtime-webcam
   ```
2. Open `index.html` in a browser (HTTPS or `localhost` required for camera access).
3. Grant camera permissions when prompted.
4. Configure the **Base API URL** (default: `http://localhost:1234`).
5. Enter an instruction (e.g., "Describe this image in detail").
6. Click **Start** to stream frames to LM Studio.
7. View responses in the **Response** box.

---

## ⚙️ Configuration
- **Base API URL**: Point to your LM Studio server (e.g., `http://localhost:1234`).
- **Request Interval**: Adjust the frequency of API calls (default: 500ms).

---

## 📌 Notes
- **LM Studio Compatibility**: Works best with vision-language models like `moondream2`.
- **Local Development**: Use `localhost` or enable HTTPS for camera access.
- **Troubleshooting**:
  - Ensure LM Studio's local server is running.
  - Check the browser console for errors.

---

## 📜 License
This project is licensed under the [MIT License](./LICENSE).

---

## 🤝 Contributing
We welcome contributions! Please read our [Contribution Guidelines](./CONTRIBUTING.md) for details.

---

✨ **Report issues** or **suggest improvements** [here](https://github.com/your-repo/smolvlm-realtime-webcam/issues).