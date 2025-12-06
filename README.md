# PA Attendance Portfolio

A full data-to-web analytics project analyzing Pennsylvania school-district attendance from **2001–2009**.  
This project ingests raw Excel files, cleans and standardizes them, engineers meaningful metrics (attendance rates, lost instructional time, trends), clusters school districts, forecasts progress toward a 95% attendance target, and publishes everything through an interactive web portfolio.

🔗 **Live Demo:** https://pa-child-accounting-attendance-anal.vercel.app  
🔗 **Repository:** https://github.com/DMDTague/PA-Attendance-Portfolio

---

## 📌 Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Architecture](#architecture)
- [How I Built It](#how-i-built-it)
- [What I Learned](#what-i-learned)
- [Improvements / Future Work](#improvements--future-work)
- [Why This Matters](#why-this-matters)

---

## 🧠 Overview

This portfolio analyzes multi-year Pennsylvania child-accounting and attendance data.  
The project turns raw spreadsheets into an accessible, visual platform that helps highlight district-level attendance trends, chronic absenteeism patterns, lost instructional time, and projected progress toward state attendance goals.

The result is a polished, publicly accessible data product.

---

## 🛠️ Technologies Used

### **Backend / Data**
- **Python**
- **Pandas**, **NumPy**
- **Excel data ingestion**
- **Clustering / forecasting**

### **Frontend**
- **React**
- **Vite**
- **JavaScript**
- **HTML / CSS**

### **Dev / Deployment**
- **ESLint**
- **Vercel (static hosting)**

---

## ⭐ Features

- 📂 **Processes 8+ raw Excel files** spanning 2001–2009  
- 🧹 **Cleans**, **normalizes**, and merges inconsistent child-accounting data  
- 📊 **Calculates attendance rates** and district-level trends  
- ⏳ **Computes lost instructional time**  
- 🔍 **Clusters school districts** by attendance similarity  
- 📈 **Forecasts progress** toward 95% attendance  
- 🌐 **Interactive web portfolio** with charts and explanations  
- 💡 Makes complex educational data accessible to any user  

---

## 🧱 Architecture


### **1. Data Pipeline (Python)**
- Imports Excel files  
- Cleans and standardizes inconsistent year-to-year formatting  
- Engineers metrics (rates, trends, missing data handling)  
- Outputs JSON/CSV for frontend consumption  

### **2. Frontend (React + Vite)**
- Loads processed datasets  
- Renders charts, tables, explanations  
- Presents district-level insights cleanly  

### **3. Deployment**
- Vite build → uploaded to Vercel → live static portfolio  

---

## 🏗️ How I Built It

1. Gathered the full set of PA attendance spreadsheets  
2. Wrote a Python ETL pipeline to merge and standardize each year’s data  
3. Engineered new metrics like lost instructional time  
4. Applied clustering to group districts by pattern  
5. Built a frontend to transform the analysis into a readable story  
6. Designed the UI as a “portfolio report” that anyone can navigate  
7. Deployed using Vercel for instant public access  

---

## 📚 What I Learned

- Handling **messy real-world datasets** across multiple years  
- Feature engineering beyond raw attendance numbers  
- Using **clustering** to reveal statewide patterns  
- Designing a front-end UI for a data analysis project  
- Combining Python analytics with a React-based web interface  
- Managing a full data pipeline → frontend → deployment workflow  

---

## 🚀 Improvements / Future Work

- Add API endpoints instead of static JSON  
- Expand forecasting models  
- Include district-level comparison tools  
- Add export (CSV/PDF) functionality  
- Document the dataset schema more formally  
- Add tests for the Python ETL pipeline  

---

## 🎯 Why This Matters

This project:

- Helps educators and policymakers understand **attendance trends over time**
- Quantifies **lost instructional time**
- Shows how far districts are from hitting **state attendance goals**
- Makes an otherwise opaque dataset **accessible and visual**
- Demonstrates end-to-end **data engineering → analysis → web development**

---

## ✅ Summary

**PA Attendance Portfolio** is a complete analytics project —  
turning inconsistent Excel files into a structured analysis and a polished, public dashboard.

It reflects skills in:

- **Data cleaning**
- **Feature engineering**
- **Clustering / forecasting**
- **Frontend development**
- **Deployment**
- **Communicating insights clearly**
