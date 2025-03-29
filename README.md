let studentData: string = `{
    "studentName": "Aakash",
    "studentID": 12345,
    "studentCourse": "B. Tech"
}`;
let student: any = JSON.parse(studentData);

console.log(student.studentName, student.studentID, student.studentCourse);
// Prints: Aakash 12345 B. Tech
