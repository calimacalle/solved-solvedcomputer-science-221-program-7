Download Link: https://assignmentchef.com/product/solved-solvedcomputer-science-221-program-7
<br>
Learningobjective:

To use abstractclasses and methods.

To usepolymorphism.

Assignment:

Writea Java application that expands the student grade system from Program 6. Makeany necessary corrections to Program 6.

Sincea faculty member is a person, create a class Faculty that is derived from Person.A faculty member has a department (String) and an ArrayList ofcourses (ArrayList&lt;Course). The difference isthat faculty doesn’t get a grade in a course, but has a number of students.This number should be included when the faculty’s course is added. When thefaculty information is printed, the totalnumber of students should be printed (instead of a grade).

Thisin turn means that Course is slightly differentfor student and faculty. Both have a department (String), a number (int),and credit hours (int). The student has agrade (char), and the faculty has a numberof students (int). So make a new hierarchy withan abstract class Course at the top thatcontains common information. From this derive new classes StuCourseand FacCourse that contain respectively thegrade and the number of students, with appropriate setters and getters. Makeall methods in Course that will be redefinedin the subclasses abstract methods.

InTest.java add some faculty with coursesand number of students per course. Add grades to all of the students’ courses.Make an array of Person and put all students,graduate students and faculty into it. Use a loop to print all information onall Persons. I reserve the right to use my Test.javain place of yours.

Signatures of constructors thatwill be called from Test.java:

Student(int idNumber, String firstName, String lastName)

Student(int idNumber, String firstName, String lastName,

String major)

GraduateStudent(int idNumber, String firstName, String lastName,

String major)

Faculty(int idNumber, String firstName, String lastName,

String department)

Signatures of constructors thatwill be called indirectly when anyone adds a course:

Course(String newDept, int newNumber, int newHours)

//for students:

StuCourse(String newDept, int newNumber, int newHours)

//for faculty:

FacCourse(String newDept, int newNumber, int newHours, int newNumStu)

Signatures of methods that willbe called from Test.java:

//for students:

setMajor(Stringmajor)

addThesisTopic(StringthesisTopic)

addCourse(Stringdept, int num, int hours)

changeGrade(Stringdept, int num, char grade)

//for faculty:

addCourse(Stringdept, int num, int hours, int numStudents)

Submissioninstructions:

Uploadthe files Course.java, StuCourse.java, FacCourse.java, Person.java, Student.java,GraduateStudent.java, Faculty.java,and Test.java to “Program 7”. Do notsubmit class files or any of the BlueJ control files. Be sure to press thesubmit button.

Policies:

Thepolicies given on WebCT are in effect for this and all assignments.

Youmay submit on WebCT multiple times, so there is no excuse for not submittingpartial solutions.