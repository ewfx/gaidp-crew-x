# 🚀 Project Name : Gen AI-Based - Regulatory Reporting Data Validation Tool

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
Gen AI based Data profiling tool, It accepts two inputs 1. Regulations PDF 2. Data set that need to validated against the regulation
It uses the Gen AI- Gemini AI to parse the rules and validate the Data set provided.

## 🎥 Demo
🔗 [Live Demo](#) (if applicable)  
📹 [Video Demo](#) (if applicable)  
🖼️ Screenshots:

![Screenshot 1](link-to-image)
please refer to Demo folder
## 💡 Inspiration
We are from CCIBT and recently worked on automating Data validations in regulatory data file using Alteryx, Other team members work on Regulatory reporting like FR Y 14 

## ⚙️ What It Does
It simple, accepts two files and identifes the discrepancies

## 🛠️ How We Built It
We used gemini AI to parse the PDF file and CSV input file into JSON file format. We passed the JSON files to Gemin AI and prompted it to be a Regulatory expert and identify issues in the file

## 🚧 Challenges We Faced
We are new to Gen AI- this is a good learning exploring API and Gen AI

## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/ewfx/gaidp-crew-x.git
   ```
2. Install dependencies  
pip install requests  
pip install uvicorn
pip install google.generativeai
pip install pdfplumber
npm install axios
npx create-react-app@latest data_profiler
pip install fastapi   
pip install requests  
pip install pandas
   ```
3. Run the project  
**Front End:**
1.update the app in dataprofiler folder 
2. open node js command prompt
3. go to data profiler folder
4.then type npm start

**Back end:**
1. In cmd prompt go to the path where the main.py code is then enter below command
python -m uvicorn  main:app --reload

## 🏗️ Tech Stack
- 🔹 Frontend: React  
- 🔹 Backend: Python
- 🔹 Database: None
- 🔹 Other: Gemini API

## 👥 Team
- CREW X - [GitHub](#) | [LinkedIn](#)
- Gopalakrishnan Venkataraman - [GitHub](#) | [LinkedIn](#)
- Robin Verma
- Vikram Bollipalli
- Shardul Bisht
- Ekta Singh
