📊 CGPA Calculator (C++)
A simple C++ program that calculates the GPA (Grade Point Average) for a semester and the overall CGPA (Cumulative Grade Point Average) based on user input of grades and credit hours.
🚀 Features
✅ Input number of courses
✅ Enter grade and credit hours for each course
✅ Calculates total credits
✅ Calculates total grade points (grade × credit hours)
✅ Computes Semester GPA
✅ Computes Overall CGPA
✅ Displays individual course details
🧠 How It Works
User enters the number of courses
For each course:
Enter grade (A, B, C, etc.)
Enter credit hours
Program converts grades into grade points
Formula used:
Total Grade Points = Σ (grade points × credit hours)
GPA = Total Grade Points / Total Credits
CGPA is calculated similarly (can be extended for multiple semesters)
📝 Grade Point Table (Example)
Grade
Points
A
10
B
8
C
6
D
4
F
0
⚠️ Note: You can modify this grading system based on your university.
💻 Sample Output
C++
Enter number of courses: 3

Course 1:
Grade: A
Credits: 4

Course 2:
Grade: B
Credits: 3

Course 3:
Grade: C
Credits: 2

Total Credits: 9
Total Grade Points: 68

GPA: 7.55
CGPA: 7.55
🛠️ Technologies Used
C++
Standard Input/Output (cin, cout)
📂 Project Structure
C++
CGPA-Calculator/
│── cgpa_calculator.cpp
│── README.md
▶️ How to Run
Compile the program:
Bash
g++ cgpa_calculator.cpp -o cgpa
Run the program:
Bash
./cgpa
(For Windows users: cgpa.exe)
🎯 Future Improvements
GUI version using C++ libraries
Support for multiple semesters
Save results to file
Add percentage calculation
👨‍💻 Author
Pooja Sahu
B.Tech CSE (AIML)
