# Students Scoresheet System (Java Console)

This project is a **Java console application** that collects student performance data, calculates totals, assigns letter grades, and displays a formatted report including class statistics.

---

## Features

- Collect school and teacher details
- Accept multiple students' data
- Capture marks for six subjects:
  - English
  - Math
  - History
  - Geography
  - Science
  - Programming
- Automatically calculate:
  - Total marks per student
  - Grade per student
  - Subject totals
  - Class averages
  - Grade distribution (A, B, C, D, E)

---

## Grading Criteria

| Average Score | Grade |
|---------------|-------|
| 80 and above  | A     |
| 70–79         | B     |
| 60–69         | C     |
| 50–59         | D     |
| Below 50      | F     |

Note: Grade F is counted under grade **E** statistics.

---

## How the Program Works

1. User enters school information and academic year
2. User specifies number of students
3. Program prompts for each student's name and subject marks
4. The program computes:
   - Total score for each student
   - Average score
   - Final letter grade
5. A well-formatted table is printed showing:
   - All marks
   - Totals
   - Letter grades per student
6. Class totals, averages, and grade distribution are shown at the bottom of the report

---




```sh
javac studentsScoresheet.java
