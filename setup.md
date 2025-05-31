# 🛠️ LM Studio Setup Guide

## 1. **Install LM Studio**
- Download [LM Studio](https://lmstudio.ai/) for your OS.
- Launch the application.

## 2. **Configure Local Server**
1. Go to **Server Settings** in LM Studio.
2. Enable the **Local Inference Server** (default port: `1234`).
3. Load a vision-language model (e.g., `moondream2`).

## 3. **Verify the API**
- Test the endpoint with `curl`:
  ```bash
  curl http://localhost:1234/v1/chat/completions -H "Content-Type: application/json" -d '{"model":"moondream2", "messages":[{"role":"user","content":"Hello!"}]}'
  ```

## 🚀 Next Steps
- Update the `Base URL` in `index.html` if needed.
