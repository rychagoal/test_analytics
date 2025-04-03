# 📊 Attendance Analysis — Data Analysis Mini Project

This project is an exploratory data analysis (EDA) of student attendance records. The goal is to uncover patterns in attendance behavior, identify issues with attendance across teachers and students, and visualize the key insights.

## 🗂️ Dataset Description

The dataset includes the following fields:

| Column         | Description                                  |
|----------------|----------------------------------------------|
| `event_id`     | Event ID                                     |
| `event_date`   | Date of the event                            |
| `customer_id`  | Student ID                                   |
| `is_attend`    | Attendance flag (1 — attended, 0 — missed)   |
| `group_ids`    | Study group ID                               |
| `teacher_ids`  | Teacher ID                                   |
| `attendance_id`| Unique attendance record ID                  |

## 🔍 Analysis Steps

### 1. Data Check
- Total rows: 320
- No missing values detected

### 2. Overall Attendance Rate
- Average attendance across all events: **82.5%**

### 3. Attendance by Event
- Calculated present and absent student counts for each `event_id`
- Computed attendance percentage per event

### 4. Teacher Attendance Performance
- Identified teachers with low attendance (<75%) in their events
- Visualized share of low-attendance sessions per teacher

### 5. Student Attendance Stats
- Counted total and missed sessions for each student
- Listed students with attendance below 75%
- Visualized attendance distribution

### 6. Attendance by Weekday
- Added `weekday` column and translated to English
- Analyzed which weekdays have higher or lower attendance

## 🧰 Libraries Used

- `pandas` — data analysis and manipulation
- `matplotlib` and `seaborn` — data visualization
- `Jupyter Notebook` — development environment

## 📁 Output Files

- `attend_percentage.csv` — event-level attendance percentages
- `teachers_stats.csv` — per-teacher attendance metrics
- `low_attend_students_stats.csv` — students with low attendance

## 🧠 Opportunities for Improvement

- Map teacher and student IDs to actual names (if available)
- Compare attendance between groups
- Add time-based trends and filters

---

**Author:** Tamara Rychagova
📧 rychagovatam@gmail.com
🌍 Serbia Novi Sad
🔗 [LinkedIn](https://www.linkedin.com/in/tamara-rychagova-51524893)
