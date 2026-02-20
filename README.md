# 🎨 AI Image Generator & Gallery

A full-stack creative suite that transforms text prompts into stunning visual art. This application features a **Real-time Gallery** to showcase creations, powered by the speed of **Firebase Studio** and the imagination of **Google AI**.

## 🚀 Overview

This project allows users to generate high-fidelity images using Google's generative models and instantly persist them to a global gallery. It handles the heavy lifting of image hosting, metadata storage, and prompt engineering in one seamless flow.

## ✨ Key Features

* **Text-to-Image Generation:** Powered by Google AI for high-quality, creative visuals.
* **Infinite Gallery:** A masonry-style feed of community-generated images.
* **Cloud Storage:** Images are optimized and stored securely via Firebase Cloud Storage.
* **Social Interaction:** (Optional) Like, download, or share prompts from other creators.
* **Responsive Design:** Fully optimized for mobile, tablet, and desktop creators.

## 🛠️ Tech Stack

* **Core Logic:** [Google AI / Imagen](https://ai.google.dev/) (Image Generation)
* **Backend Ecosystem:** [Firebase Studio](https://firebase.google.com/)
* **Firestore:** For storing prompt metadata and image URLs.
* **Storage:** For hosting the generated `.png` and `.jpg` files.
* **Auth:** Secure user sign-in for personalized galleries.


* **Frontend:** [Insert Framework, e.g., React / Next.js / Flutter]
* **Styling:** [e.g., Tailwind CSS / Framer Motion]

## 🏁 Getting Started

### Prerequisites

* A Firebase Project
* Google AI (Gemini/Vertex AI) API credentials
* Node.js (v18+)

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/ai-image-gallery.git
cd ai-image-gallery

```


2. **Install dependencies:**
```bash
npm install

```


3. **Environment Configuration:**
Create a `.env` file and populate it with your Firebase and Google AI keys:
```env
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
GOOGLE_AI_API_KEY=your_google_ai_key

```


4. **Run the project:**
```bash
npm run dev

```



## 📸 Screenshots

| Generation Interface | Community Gallery |
| --- | --- |
|  |  |

## 🧪 Roadmap

* [ ] **Image Variation:** Generate 4 variations of a single prompt.
* [ ] **In-painting:** Edit specific parts of a generated image.
* [ ] **Prompt Enhancement:** Use Gemini to "upscale" simple user prompts into detailed descriptions.

---

**Built to turn imagination into pixels.**
