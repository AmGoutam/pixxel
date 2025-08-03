# 📸 Pixxel – AI-Powered Image Editor

Pixxel is a modern, full-featured AI image editing platform designed for creatives, marketers, and developers. With powerful AI integrations and a sleek user interface, Pixxel allows users to enhance, edit, and export images seamlessly with pro-level tools – directly in the browser.

> ⚡ Built with Next.js, Tailwind CSS, and Fabric.js – with AI capabilities powered by third-party services.

---

## 🚀 Features & Functionality

- 🖥️ **Modern Dashboard** – A responsive, intuitive, and elegant dashboard layout for a smooth editing experience.
- ✂️ **Image Resizing & Cropping** – Precision tools to adjust image dimensions and crop with ease.
- 🎨 **AI Image Enhancement** – Automatically improve image quality using advanced AI models.
- 🧼 **Background Removal** – One-click AI-powered background remover for clean, transparent subjects.
- 🌈 **Background Editing**
  - Change background color
  - Add background from Unplash image library
- 💾 **Auto Save** – Your progress is automatically saved in real-time.
- 🔒 **Authentication with Clerk** – Secure user management system with account handling.
- 📦 **Free & Pro Plans**
  - **Free Plan** – Limited access to basic tools.
  - **Pro Plan** – Unlocks full access to advanced AI editing features.

---

## 🛠️ Tech Stack

| Technology     | Purpose                                |
|----------------|----------------------------------------|
| **Next.js**    | Frontend Framework (App Router)        |
| **Tailwind CSS** | Utility-first UI styling              |
| **Clerk**      | Authentication & user session handling |
| **Fabric.js**  | Canvas-based image manipulation        |
| **Unplash API**| Free stock photo integration           |
| **Conves.js**  | AI-enhancement utilities (if used)     |

---

## 🔐 Authentication

- Auth & user management powered by **Clerk**
- Authenticated users can access editor tools, and autosave sessions

---

## 💡 Future Enhancements

- 👥 Collaborative editing
- 🧠 Prompt-based AI art generation
- ☁️ Cloud-based storage
- 📊 Analytics dashboard for Pro users

---

## 📂 Project Structure (Simplified)

```bash
Pixxel/
├── app/
│   ├── dashboard/
│   ├── editor/
│   └── auth/
├── components/
├── utils/
├── lib/
├── public/
└── styles/
