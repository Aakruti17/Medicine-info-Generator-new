# 🩺 Medicine Info Generator

**An AI-powered multilingual medicine information web app using Google's Gemini API**

![Hero Banner](https://github.com/Aakruti17/Medicine-info-Generator-new/blob/bba84de20674ce3ab6093f7388687cfe61a4d034/medicine_info_generator%20new/medicine_info_generator%20-%20Copy/screenshot/banner.png)



## 📌 Overview

The **Medicine Info Generator** is a web application designed to provide detailed, AI-generated information about medicines. It supports **English**, **Hindi**, and **Marathi**, allowing users to access data such as:

- Uses and benefits  
- Side effects  
- Warnings and precautions  

Users can also **download** the information as **PDF** or **TXT** files and access their **recent search history** for convenience.



## ✨ Features

- 🧠 Powered by **Google Generative AI (Gemini 1.5 Flash)**
- 🌐 Supports **three languages**: English, Hindi (हिन्दी), and Marathi (मराठी)
- 📄 **Download results** as PDF or TXT (with Devanagari font support)
- 🕘 **Recent search history** with delete and re-search functionality
- 🧾 Rich AI responses formatted using **Markdown**
- 📱 Fully **responsive UI** with modern styling and icons



## 🚀 Live Demo

👉 [Click here to try it live](https://your-username.github.io/medicine-info-generator)



## 🖼️ Screenshots

| Home Page | AI Response | PDF Download |
|-----------|-------------|---------------|
| ![Home](https://github.com/Aakruti17/Medicine-info-Generator-new/blob/9cc150554bcd24d0a8abbc638179565030a27656/medicine_info_generator%20new/medicine_info_generator%20-%20Copy/screenshot/home.png) | ![Result](https://github.com/Aakruti17/Medicine-info-Generator-new/blob/9cc150554bcd24d0a8abbc638179565030a27656/medicine_info_generator%20new/medicine_info_generator%20-%20Copy/screenshot/result.png) | ![PDF](https://github.com/Aakruti17/Medicine-info-Generator-new/blob/9cc150554bcd24d0a8abbc638179565030a27656/medicine_info_generator%20new/medicine_info_generator%20-%20Copy/screenshot/pdf.png) |



## 🛠 Tech Stack

| Category         | Tools / Libraries                    |
|------------------|--------------------------------------|
| 💻 Frontend      | HTML, CSS, JavaScript                |
| 🎨 UI Icons      | Font Awesome                         |
| 🧠 AI Model      | Google Generative AI (Gemini 1.5)    |
| 🌐 Language Files | JSON (lang-en, lang-hi, lang-mr)    |
| 📄 PDF Generator | jsPDF with Noto Sans font support    |
| 📝 Markdown      | Marked.js                            |
| 📦 Storage       | localStorage (for recent searches)   |



## 📁 Project Structure
medicine-info-generator/ <br/>
├── index.html # Main HTML <br/>
├── style.css # App styling <br/>
├── /fonts/ <br/>
│ └── NotoSansDevanagari-Regular.ttf <br/>
├── /screenshots/ <br/>
│ ├── banner.png <br/>
│ ├── home.png <br/>
│ ├── result.png <br/>
│ └── pdf.png <br/>
├── /lang/ <br/>
│ ├── lang-en.json <br/>
│ ├── lang-hi.json <br/>
│ └── lang-mr.json <br/>
├── /images/ <br/>
│ ├── medicine.jpg <br/>
│ └── logo.jpg <br/>

## 🔑 Setup & Usage

1. **Clone the repository**
```bash
git clone https://github.com/Aakruti17/Medicine-info-Generator-new.git
cd Medicine-info-Generator-new
```
2. **Add your Google Gemini API Key**
Replace the placeholder API key in index.html:
javascript
```
const API_KEY = "your-api-key-here";
```
3. **Open the app**
You can either:
Open index.html directly in a browser
Or use a local server (like Live Server in VS Code)

## 🧪 How It Works
* When a user enters a medicine name, a prompt is sent to Google’s Gemini model
* AI returns structured information using Markdown
* The result is rendered with marked.js for proper formatting
* Language preference is applied via predefined instructions
* Downloads are handled using jsPDF and Blob API

## 📥 Download Options
* TXT File: Plain text export of the AI result
* PDF File: Supports custom fonts (Noto Sans Devanagari) for Hindi/Marathi

## 🌐 Multilingual Support
Available in:
* 🇬🇧 English (lang-en.json)
* 🇮🇳 हिंदी (lang-hi.json)
* 🇮🇳 मराठी (lang-mr.json) </br>
To add more languages, simply create a new JSON file and update the langFiles map in the script.

## 👤 Author
Aakruti Gulhane
* 📧 aakrutigulhane117@gmail.com
* 🌐 https://github.com/Aakruti17
* 🔗 https://www.linkedin.com/in/aakruti-gulhane-397035291/
