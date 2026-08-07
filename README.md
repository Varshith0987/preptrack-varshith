# 📘 PrepTrack – PythonProject

PrepTrack is a Python console application that evaluates a student's placement readiness based on attendance, coding practice performance, project completion, profile verification, and graduation eligibility.

It collects student information, analyzes seven days of coding practice, generates performance statistics, and provides a final placement readiness report with personalized feedback.

---

## 🚀 Features

- Student information collection
- Input validation for all required fields
- Attendance validation
- Graduation year eligibility check
- Project completion verification
- Profile verification
- Seven-day coding practice tracking
- Handles absent practice days
- Performance classification
- Pass/Fail analysis
- Highest and lowest score tracking
- First critical score detection
- Average score calculation
- Placement eligibility evaluation
- Final performance report

---

## 📂 Project Structure

```
PrepTrack/
│
├── preptrack.py
└── README.md
```

---

## 🛠 Technologies Used

- Python 3
- Console-based Application

---

## 📋 Inputs

The application asks the user for:

- Student Name
- Registration Number
- Graduation Year
- Attendance Percentage
- Project Completion Status
- Profile Verification Status
- Seven daily coding practice scores
  - Score between 0–100
  - OR `-1` if absent

---

## 📊 Performance Categories

| Score Range | Category |
|-------------|----------|
| 75–100 | Strong |
| 60–74 | Satisfactory |
| 40–59 | Needs Improvement |
| 0–39 | Critical |

---

## 📈 Statistics Generated

The application calculates:

- Attempted Days
- Absent Days
- Passed Days
- Failed Days
- Strong Days
- Satisfactory Days
- Needs Improvement Days
- Critical Days
- Total Score
- Average Score
- Highest Score
- Lowest Score
- First Critical Score (if any)

---

## ✅ Placement Eligibility Checks

The application verifies:

- Graduation year eligibility
- Attendance ≥ 75%
- At least 6 practice days attempted
- Average score ≥ 70
- No critical score
- At least 4 passed practice days
- Project completed
- Profile verified

---

## 📄 Final Status Examples

Depending on the evaluation, the application may display:

- Practice Not Evaluated
- Critical Support Required
- Practice Incomplete
- Insufficient Passed Practices
- Practice Improvement Required
- Attendance Improvement Required
- Graduation Criteria Not Met
- Application On Hold
- Ready for Mock Interview

Each report also includes:

- Primary Blocker
- Next Recommended Action

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/Varshith0897/preptrack-varshith.git
```

Go to the project folder:

```bash
cd PrepTrack
```

Run the program:

```bash
python main.py
```

---

## 💻 Sample Output

```
==================================================
              PREPTRACK REPORT
==================================================

Student Name           : John
Registration Number    : 22CS101
Graduation Year        : 2026
Attendance             : 85.0%

Attempted Days         : 7
Absent Days            : 0
Passed Days            : 6
Failed Days            : 1

Average Score          : 78.57

Final Status           : Ready for Mock Interview
Primary Blocker        : None
Next Action            : Proceed to placement mock interviews

==================================================
```

---

## 🎯 Learning Objectives

This project demonstrates the use of:

- Variables
- Input Validation
- Conditional Statements
- Loops
- Boolean Logic
- Counters
- Nested Conditions
- Data Analysis
- Console-Based Reporting
- Python Programming Fundamentals

---

## 🔮 Future Improvements

- Store student records in a database
- CSV/Excel export
- GUI version using Tkinter
- Web-based dashboard
- Login system
- Performance graphs
- Multiple student management
- PDF report generation



