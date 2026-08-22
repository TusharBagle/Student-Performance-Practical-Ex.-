# Students Performance Overview

---

## 📌 Project Overview

The **Student Performance Analytics Dashboard** is an interactive Power BI solution designed to analyze student academic performance, attendance patterns, and behavioral observations.

The dashboard transforms raw educational data into meaningful insights that can help educators and administrators identify performance trends, recognize students requiring attention, compare subject-level performance, and investigate individual student outcomes.

Rather than analyzing academic scores alone, this project combines **Academic Performance + Attendance + Behavioral Analysis** to provide a more comprehensive view of student performance.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- 📊 Analyze overall student academic performance
- 📚 Compare average scores across subjects
- 📈 Monitor academic performance across different terms
- 👥 Analyze individual student performance
- 🕒 Evaluate student attendance patterns
- 🧠 Analyze student behavioral observations
- 🚨 Identify students who may require additional academic support
- 🔎 Provide detailed individual student analysis through Drillthrough
- 🎛️ Enable interactive filtering using Class, Section, Subject, and Term
- 💡 Convert raw educational data into actionable insights

---

# 🖥️ Dashboard Structure

The solution consists of multiple interactive analytical views:

### 1. 📚 Students Performance Dashboard
### 2. 🧠 Student Attendance & Behavior Dashboard
### 3. 👤 Student Profile Dashboard
### 4. 💬 Interactive Tooltip

---

# 📊 1. Students Performance Dashboard

The **Students Performance Dashboard** provides the overall academic performance view.

It contains:

- Total Students KPI
- Attendance Percentage KPI
- Average Score KPI
- Average Score by Subject
- Average Score by Term
- Student Performance Overview
- Performance Category
- Student-level academic details
- Interactive filters

### Key Questions Answered

- How are students performing overall?
- Which subjects have the highest or lowest average scores?
- How does performance change across terms?
- Which students have lower performance percentages?
- How does attendance relate to student performance?

### Dashboard Preview

<p align="center">
  <img src="https://github.com/TusharBagle/Student-Performance-Practical-Ex.-/blob/main/Images/Students%20Performance%20Dashboard.png" alt="Students Performance Dashboard" width="1000"/>
</p>

---

# 🧠 2. Student Attendance & Behavior Dashboard

The **Attendance & Behavior Dashboard** focuses on non-academic factors that provide additional context to student performance.

### Key Metrics

- Total Students
- Attendance %
- Behavior Count

### Visualizations

- Attendance Status
- Student Behavior Distribution
- Student Behavior Overview
- Performance Category
- Attendance Percentage

### Behavioral Categories

The dashboard analyzes behavioral observations such as:

- Disruptive
- Late
- Helpful
- Participative
- Absent Without Notice

### Key Questions Answered

- What is the overall attendance pattern?
- What percentage of students are present or absent?
- What behavioral patterns are most frequently observed?
- Which students may require behavioral or attendance-related attention?

### Dashboard Preview

<p align="center">
  <img src="https://github.com/TusharBagle/Student-Performance-Practical-Ex.-/blob/main/Images/Student%20Attendance%20%26%20Behavior%20Dashboard.png" alt="Student Attendance and Behavior Dashboard" width="1000"/>
</p>

---

# 👤 3. Student Profile Dashboard

The **Student Profile Dashboard** is an individual-level Drillthrough page.

It allows users to select a student from the main dashboard and investigate that student's performance in detail.

### Individual Student KPIs

- Average Score
- Attendance %
- Behavior Count

### Visualizations

#### 📊 Academic Performance by Subject

Compares the selected student's average score across subjects.

#### 📈 Academic Performance by Term

Shows the student's academic performance progression across different terms.

#### 🍩 Student Behavior Distribution

Shows the behavioral observations recorded for the selected student.

### Detailed Student Information

The profile also provides detailed records including:

- Student ID
- Student Name
- Term
- Score %
- Performance Category
- Attendance Status
- Behavioral Reason

### Purpose

The Student Profile page helps answer:

> **"Why does this student's performance look the way it does?"**

It allows the user to move from overall analysis to detailed individual investigation.

### Dashboard Preview

<p align="center">
  <img src="Images/Students Profile Dashboard.png" alt="Student Profile Dashboard" width="1000"/>
</p>

---

# 💬 4. Interactive Tooltip

The project also includes a customized Power BI Tooltip page.

The tooltip provides additional student-level information without requiring the user to navigate away from the current dashboard.

### Tooltip Information

- Student Name
- Average Score
- Attendance %
- Academic Performance by Term

### Benefits

- Reduces visual clutter
- Provides additional context
- Improves dashboard interactivity
- Allows users to explore information quickly

### Tooltip Preview

<p align="center">
  <img src="Images/Students Tooltip.png" alt="Students Tooltip" width="700"/>
</p>

---

# 🎛️ Interactive Features

The dashboard provides several interactive features to improve the user experience.

## 🔹 Slicers

Users can filter the dashboard using:

- Class
- Section
- Subject
- Term

All major visuals dynamically respond to the selected filters.

---

## 🔹 Academic & Attendance Views

The dashboard provides two main analytical perspectives:

### 📚 Academic View

Focuses on:

- Academic performance
- Subject comparison
- Term trends
- Student performance

### 🧠 Attendance & Behavior View

Focuses on:

- Attendance status
- Behavioral distribution
- Attendance percentage
- Student behavior patterns

This separation keeps the dashboard clean and prevents information overload.

---

# 🔎 Drillthrough Analysis

The dashboard includes a **Student Profile Drillthrough** feature.

Users can:

1. Open the Student Performance Overview table
2. Right-click a student's record
3. Select **Drillthrough**
4. Open the Student Performance Profile
5. Analyze that student's academic, attendance, and behavioral information

### Analytical Flow

```text
Overall Student Performance
            ↓
     Identify Student
            ↓
        Drillthrough
            ↓
     Student Profile
            ↓
 Academic + Attendance + Behavior
