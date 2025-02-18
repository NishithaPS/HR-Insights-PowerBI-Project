# 📊 Employee Attendance Analysis - Power BI Dashboard

## 📝 Project Overview
This project presents an interactive **Power BI dashboard** to analyze **employee attendance trends** over multiple months for **AtliQ**.  
The dashboard tracks key attendance metrics such as **Present %, Work from Home %, and Sick Leave %**, helping HR teams and managers monitor workforce availability, absenteeism patterns, and overall employee engagement.

---

## 📂 Dataset Description
The dataset consists of **employee attendance records** from **April 2022 to June 2022**, stored in an Excel file with four sheets:

1. **April 2022**
2. **May 2022**
3. **June 2022**
4. **Attendance Key** (reference for attendance status codes)

### 📌 Sample Data:
| Employee Code | Name         | 1-Jun | 2-Jun | 3-Jun | ... | Total Present Days | Present % | WFH % | Sick Leave % |
|--------------|-------------|-------|-------|-------|-----|------------------|-----------|-------|--------------|
| Atq-406     | Thanos Thakur | P     | P     | P     | ... | 13               | 76.5%     | 0%    | 0%           |
| Atq-462     | Jarvis Singh  | P     | P     | P     | ... | 13               | 76.5%     | 0%    | 0%           |

---

## 🔑 Attendance Key:
| Code  | Description                  |
|-------|------------------------------|
| **P**   | Present                     |
| **PL**  | Paid Leave                  |
| **SL**  | Sick Leave                  |
| **HPL** | Half-day Paid Leave         |
| **HSL** | Half-day Sick Leave         |
| **WFH** | Work from Home              |
| **FFL** | Floating Festival Leave     |
| **HFFL**| Half-day Floating Leave     |
| **BL**  | Birthday Leave              |
| **LWP** | Leave Without Pay           |
| **HLWP**| Half-day Leave Without Pay  |
| **BRL** | Bereavement Leave           |
| **HBRL**| Half-day Bereavement Leave  |
| **HWFH**| Half Work from Home         |
| **WO**  | Weekly Off                  |
| **HO**  | Holiday Off                 |
| **ML**  | Menstrual Leave             |
| **HML** | Half-day Menstrual Leave    |

---

## 📊 Power BI Dashboard Features

### ✅ **KPIs (Key Performance Indicators):**
- **Present %** = (Total Present Days / Total Working Days) * 100
- **Work from Home %** = (Total WFH Days / Total Working Days) * 100
- **Sick Leave %** = (Total Sick Leave Days / Total Working Days) * 100

### 🎛 **Filters & Slicers:**
- **Month Slicer**: Allows selection of a specific month for attendance analysis.

### 📅 **Tables & Reports:**
1. **Employee Attendance Summary**  
   - Columns: Name, Present %, Work from Home %, Sick Leave %  
2. **Daily Attendance Record**  
   - Columns: Name + Attendance for each day of the selected month.  

### 📈 **Visualizations:**
- **📊 Area Chart**: Present % trend over time.
- **📊 Area Chart**: Work from Home % trend over time.
- **📊 Area Chart**: Sick Leave % trend over time.
- **📅 Tables**:
  - **Days of the week vs. Present %**
  - **Days of the week vs. Work from Home %**
  - **Days of the week vs. Sick Leave %**

---

## 🔍 Project Analysis & Insights

### 📌 1. **Attendance Trends:**
- The **majority of employees have a high Present %**, indicating **strong attendance behavior**.
- The **Work from Home % is minimal**, suggesting that remote work is either **not widely encouraged** or is **limited to specific cases**.

### 📌 2. **Weekly Patterns:**
- **Weekends (WO - Weekly Off) and holidays (HO - Holiday Off) are well accounted for.**
- There is a **consistent attendance pattern** across employees, with minor fluctuations.

### 📌 3. **Sick Leave Usage:**
- **Sick Leave % is relatively low**, which could indicate **a healthy workforce** or **employees not taking sick leave often**.
- If certain weeks show a **higher sick leave rate**, further analysis might be required to detect potential trends (e.g., seasonal flu outbreaks, workload impact).

### 📌 4. **Work from Home Insights:**
- **Low WFH % suggests that remote work is not a regular practice within the organization.**
- If WFH rates increase in certain periods, it could be due to **policy changes, weather conditions, or specific job roles allowing remote work**.

### 📌 5. **Employee Leave Behavior:**
- **Special leaves (e.g., Birthday Leave, Bereavement Leave, Floating Festival Leave, Menstrual Leave) are rarely used.**
- Analyzing these leaves further could help HR teams **optimize leave policies** for better employee satisfaction.

### 📌 6. **Data-driven HR Decision Making:**
- HR can use this dashboard to **identify employees with high absenteeism** and take necessary actions.
- If absenteeism is linked to **specific job roles, departments, or seasons**, **policy adjustments** can be made.
- The dashboard helps in **workforce planning, ensuring business continuity and productivity**.

---

## 🔄 Future Enhancements
✅ **Add dynamic measures** for year-over-year comparisons.  
✅ **Introduce employee-specific attendance trends** over multiple months.  
✅ **Implement predictive analytics** for absenteeism forecasting.  
✅ **Automate data refresh** for real-time attendance tracking.  
✅ **Integrate machine learning models** to predict absenteeism trends.  

