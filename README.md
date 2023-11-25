# CS528FinalProject

Firebase Realtime Database Structure
1. Professors
professors
professorID
name: String
email: String
department: String
2. Students
students
studentID
name: String
email: String
3. Classes
classes
classID
className: String
professorID: String (reference to a professor)
startTime: Number
startDay: Number
4. Check-Ins
checkIns
checkInID
studentID: String (reference to a student)
classID: String (reference to a class)
checkInTime: Timestamp
5. Class Enrollments
classEnrollments
classID
studentID: Boolean (or any placeholder value, e.g., true)