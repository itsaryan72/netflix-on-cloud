# 📺 Netflix Titles Dashboard with Amazon QuickSight

This project leverages **Amazon QuickSight** to create an interactive, cloud-based dashboard for visualizing a dataset of Netflix titles. The dashboard offers insights into trends like content category distribution, release patterns, and recent additions.

---

## 🔧 Tools Used

- **Amazon S3** – to store and host the dataset  
- **Amazon QuickSight** – for data visualization and dashboard creation  
- **CSV Dataset** – Netflix Titles Dataset (includes title, type, genre, release year, and added date)

---

## 📁 Project Workflow

### 🪣 1. Upload Dataset to S3
- A cleaned CSV dataset was uploaded to an **Amazon S3 bucket**.
- This bucket served as the primary data source for QuickSight.

### 🔗 2. Connect Dataset to QuickSight
- The dataset was securely connected to Amazon QuickSight via the S3 manifest file.
- Schema and data types were validated and transformed as needed.

### 📊 3. Create Visualizations
- Multiple chart types were explored and used:
  - **Donut Charts** – to show content type distribution (TV Shows vs Movies)
  - **Bar Graphs** – to highlight content release trends by year
  - **Tables** – for listing recently added titles with metadata
  - **Stacked Bars / Filters** – for category-based comparisons

### 📌 4. Dashboard Creation
- Visuals were compiled into a single **interactive dashboard**.
- The dashboard was **published** and could be exported/shared.

---

## 🔍 Key Insights

- 🎬 Clear rise in content production post-2015.
- 📈 TV Shows and Movies are distributed almost equally in recent years.
- 🗂️ Popular genres include Drama, Comedy, and International content.
- 🕒 Latest additions can be tracked easily by filtering the added date.

---

## 🖼️ Dashboard Preview

> *Embed screenshots or GIFs of your dashboard here for visual reference.*

---

## 📦 Dataset Info

Dataset Source: [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
Contains fields like:
- Title
- Type
- Director
- Cast
- Country
- Date Added
- Release Year
- Genre
- Duration
- Description

---

## ✅ Completion Checklist

- [x] Uploaded dataset to S3
- [x] Connected S3 to QuickSight
- [x] Built multiple visualization types
- [x] Published dashboard
- [x] Tested filtering and interaction

---

## 📤 Export & Share

The dashboard can be exported as:
- PDF
- Public or private link (within QuickSight)
- Embedded iframe (if using QuickSight Enterprise Edition)

---

## 📚 Learnings

- Worked with AWS services: **S3** and **QuickSight**
- Understood cloud-based BI tool workflows
- Practiced visual storytelling with real-world data

---

## 📌 Future Enhancements

- Automate data updates via S3 → QuickSight refresh
- Integrate SPICE datasets for faster performance
- Add user-level filtering and dynamic controls

---

## 💡 Inspiration

This project was inspired by the need to visualize large content libraries (like Netflix) and understand release patterns, category spread, and viewer trends using serverless, cloud-native tools.

---

