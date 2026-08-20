# Student Digital Well-being & Academic Outcomes: Interactive Power BI Application

## 📌 Project Overview
This project is an interactive, end-to-end data analytics dashboard built in Power BI. It explores the intersection of student social media usage, behavioral addiction, academic performance, and mental wellness. 

Designed with a modern, application-style user interface, this tool empowers distinct stakeholders—including Academic Advisors, Mental Health Counselors, and Institutional Researchers—to navigate complex behavioral datasets seamlessly and extract actionable insights.

---

## 🚀 Live Dashboard Preview

*(Click the image icon in your GitHub editor and upload your Homepage screenshot here)*
**[Upload Homepage Screenshot Here]**

---

## 🛠️ Key Features & Technical Execution

*   **Advanced Data Modeling:** Engineered a robust Star Schema architecture connecting demographic dimension tables with behavioral fact metrics (1:1 relationships) using a custom DAX Calendar table.
*   **Custom DAX Measures:** Developed targeted calculations to quantify addiction scoring, relationship conflict levels, and percentage-based academic impact models.
*   **Application-Style UI/UX:** Replaced standard report tabs with a centralized navigation menu, utilizing hover-state buttons, custom vector graphics, and a unified color palette (Deep Navy & Warm Coral) for an intuitive user experience.
*   **Interactive Storytelling:** Implemented advanced Bookmark and Selection pane features to allow users to toggle seamlessly between demographic perspectives (Gender vs. Academic Level) within a single view.
*   **Granular Drill-Throughs:** Created a customized CRM-style Student Profile directory, enabling stakeholders to drill down from aggregated scatter plots into individual student health and performance metrics.

---

## 📊 Core Analytical Modules

### 1. Executive Overview & Demographics
Provides a high-level summary of total users, average screen time, and behavioral addiction rates broken down by academic level.
<img width="1039" height="582" alt="Screenshot 2026-08-20 at 4 30 30 PM" src="https://github.com/user-attachments/assets/5ec335f1-e449-491e-9ddd-2bc892334183" />

### 2. Interactive Story View
Utilizes Power BI bookmarks to dynamically switch analytical views without cluttering the canvas, comparing platform preferences side-by-side.
<img width="1040" height="583" alt="Screenshot 2026-08-20 at 4 31 58 PM" src="https://github.com/user-attachments/assets/413fd917-c02c-46f7-9eef-3351a1ddaafa" />
<img width="1032" height="584" alt="Screenshot 2026-08-20 at 4 32 12 PM" src="https://github.com/user-attachments/assets/1d15b5cf-f676-4eef-9c31-6f5a43533152" />


### 3. Individual Student Profile (Drill-Through)
A dedicated, hidden page accessed via table drill-through, detailing a specific student's sleep patterns, usage hours, and mental health ratings.
<img width="1037" height="588" alt="Screenshot 2026-08-20 at 4 32 25 PM" src="https://github.com/user-attachments/assets/c568eb18-53a6-410f-bb72-cbfa21dfafc5" />

---

## 💻 Tech Stack
*   **Tool:** Power BI Desktop
*   **Languages:** DAX (Data Analysis Expressions)
*   **Techniques:** Star Schema Modeling, Data Cleaning, Bookmark Routing, Drill-Through Navigation, UI/UX Design

---

## 📥 How to Run This Project Locally
1. Clone this repository or download the `.zip` file.
2. Extract the contents and locate the `.pbix` file.
3. Open the file using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
4. Use the on-screen navigation buttons on the Homepage to explore the modules.
