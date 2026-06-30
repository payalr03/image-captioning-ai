# 🖼️ Image Captioning AI (BLIP / BLIP-2)

This project uses Hugging Face Transformers and the BLIP model to automatically generate captions for images.

It includes three different implementations:
- Local image captioning script
- Gradio web app for image upload
- Web scraping + AI caption generation app

---

## 🚀 Features

- Generate captions for uploaded images
- Web-based UI using Gradio
- Automatic image captioning from websites (web scraping)
- Saves captions to text file

---

## 🧠 Models Used

- BLIP (Salesforce/blip-image-captioning-base)
- BLIP-2 (optional upgrade)

---

## 📁 Project Structure

apps/
├── cli_caption.py # Basic script version
├── gradio_app.py # Gradio image upload app
├── scraper_app.py # Web scraping caption generator

images/
├── sample images

captions.txt # Generated captions

---

## ⚙️ Installation

```bash
pip install -r requirements.txt 
```
---

## ▶️ How to Run

### 1. Basic script
```bash
python apps/cli_caption.py
```

### 2. Gradio app
```bash
python apps/gradio_app.py
```

### 3. Web scraping app
```bash
python apps/scraper_app.py
```

---

## 🌐 Example Use Case

A news agency can automatically:

- Extract images from news articles automatically
- Generate accurate captions using AI models
- Improve SEO (Search Engine Optimization)
- Enhance accessibility for visually impaired users (alt text)
- Speed up the article publishing process

---

## 📌 Tech Stack

- Python
- Hugging Face Transformers
- PyTorch
- Gradio
- BeautifulSoup
- PIL

---

### 👤 Author

Payal R
