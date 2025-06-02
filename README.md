# Micro-IT
Students management system 


1. mockUsers
Contains login credentials for:

👨‍🎓 Students (role: 'student')

👨‍👩‍👧 Parents (role: 'parent')

👨‍🏫 Teachers (role: 'teacher')

All users have email format: name@gsk.edu.in

Default password for all accounts: gsk@628

2. mockStudents
Profiles of all students with:

ID, Name, Email

Roll Number, Class, Section

Parent link via parentId

Contact and admission details

3. mockParents
Profiles of each student’s parent

Includes contact number and relationship

Linked to student via childrenIds

4. mockAttendance
Attendance records over a week (Oct 1–5)

Includes status (present, absent, late) and optional remark

5. mockMarks
Midterm marks for each student across 3 subjects

Includes subject ID, marks, exam type, and date

6. mockFees
Tuition, Exam, and Library fees per student

Tracks due dates, payment status, and transactions

7. mockLeaveRequests
Leave requests submitted by students

Includes leave dates, reasons, review status, and teacher review

💡 Purpose:
This mock data is ideal for:

🌐 Frontend UI testing

🔁 API integration demo

🧪 Unit & integration tests

📊 Simulating end-to-end academic flows

🏫 College Info:
All records are linked to a single college ID: c1 (e.g., GSK Institute).

