# Student Grade Manager App
This app is a student grade manager. It reads students grades as input from a text file and creates individual "Student" objects from this text file, line-by-line, each containing student data. It proceeds to the end of the list and populates each Student object into an ArrayList from the class CourseSection. The GUI pulls the available StudentID's and populates them into a scrollable ListView, and when a studentID is selected, his/her corresponding grades appear for each assignment AND their final grade in the class is calculated. There are also four functional buttons on the GUI, add, remove, clear, and search.

## Add:
Allows the user to add a Student object to the ArrayList and have it display in the ListView with the corresponding assignment grades the user inputs.

## Remove:
Allows the user to remove a Student object from the ArrayList.

## Clear:
Allows the user to clear the text of the Text Fields.

## SearchID:
Allows the user to bypass scrolling in the ListView and simply input the StudentID they are searching for and display it in the ListView.

# Getting Started
To test this program, simply download the StudentGradeManagerAPP_Lib folder from this repository, and unzip the folder after downloading. Keep the Marks.txt file in the same folder as the StudentGradeManagerApp.jar file and simply double-click the .jar file. The program should open and load the .txt file and functionality will be present.

You can also download the individual .java files (Student, CourseSection, CourseSectionView, and CourseSectionApp) and copy the code into an IDE of your choosing (i.e. Eclipse, DrJava, JCreator). Make sure to name the class the same name the file is named, i.e. CourseSectionApp should be named CourseSectionApp, if you create a new Java file and copy the code into it).

# Prerequisites
You will need a JDK (Java Development Kit) if you plan to compile the code in an IDE, however if you plan to just run the .jar file on your desktop, a JDE (Java Development Environment) should suffice.

# Built With
Eclipse - Java IDE
JavaFX - GUI library 
Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

# Authors
Al Pizano
See also the list of contributors who participated in this project.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details

# Acknowledgments
Inspiration credit to Dr. Xiaoli Yang at Purdue University Northwest
