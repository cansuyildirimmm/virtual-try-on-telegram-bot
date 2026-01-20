# 🤖 Virtual Try-On Telegram Bot
AI-powered virtual try-on system using **Telegram**, **n8n**, and **Replicate API**

---

## 🌍 Languages
- 🇬🇧 English  
- 🇹🇷 Türkçe  

---

# 🇬🇧 ENGLISH

## 📌 Project Description
**Virtual Try-On Telegram Bot** is an AI-powered system that allows users to virtually try on clothes by simply sending a clothing image and a description via Telegram.

The bot processes the image using **Replicate AI models** through an **n8n workflow**, applies the clothing to a predefined human model, and sends the generated result back to the user automatically.

This project demonstrates the integration of **Generative AI**, **automation workflows**, and **chat-based user interaction**.

---

## 🚀 Features
- 📸 Accepts clothing images from Telegram users
- 🧠 AI-powered virtual try-on using Replicate
- 🔄 Fully automated n8n workflow
- 📝 Uses image captions as AI prompts
- 🔐 Secure API token handling with environment variables
- 🤖 Sends generated try-on images back to users

---

## 🧩 How It Works
1. User sends a clothing photo with a description to the Telegram bot  
2. Telegram Trigger node receives the image  
3. Image is converted to Base64 format  
4. Replicate API generates a virtual try-on result  
5. The output image is streamed and sent back to the user  

---

## 🛠️ Tech Stack
- **n8n** – Workflow automation  
- **Telegram Bot API** – User interaction  
- **Replicate API** – AI image generation  
- **JavaScript** – Data processing  
- **GitHub** – Version control  

---

## 📂 Repository Structure

