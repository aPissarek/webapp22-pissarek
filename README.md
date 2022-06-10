
# Web App Specification: Manage Your School

Description for a Web App: “Manage Your School”

The purpose of the “Manage Your School” app running on the manage-your-school.com domain is the administration of the students, teachers and classes for an elementary school of 4 years duration. This means there will be 1st, 2nd, 3rd and 4th class level and each level may be divided into groups depending on the number of students. We set our size limit for a class to 15 students in order to enable a proper learning experience for the children. That means if we have, e.g., 45 students in the 1st grade, then there will 3 different classes on class level 1, namely: class 1a, class 1b and class c.	 

Our business activities that need to be supported by the app include hiring new teachers, removing them from our database if they stop working for us for whatever reasons, updating their data – specifically the address in case they move, their family name in case they get married or divorced and the subjects they teach, in case they change, as well as their assigned class (if applicable).	 
Subjects might change for example, if a teacher obtains some additional qualifications and adopts a new subject they can teach, or if they decide to drop one of their taught subjects. 
As for the assigned class of a teacher: Some teachers have a class, which they are responsible for. Every class needs to have a head of class, which is one of the teachers, who oversees the class’ students, takes them out for field trips every once in a while and is generally responsible for the class. In our example of the 3 level-1 classes 1a, 1b and 1c, we would need 3 teachers as head of class for 1st grade, one for each.	 
Of course this means that every class must have a teacher as head of class but not every teacher has to be the head of a class, i.e. not every teacher has an assigned class. The remaining teachers simply teach their subjects to classes without being assigned to any one class in particular. It is worth noting, that in order for a head of class to form a closer bond with the children in their class, we want to have them spend as much time together as possible during the classes because we want the children to have a type of parent figure in school. For this reason, we made a rule that the head of class must also be the teacher in his class for his/her assigned class in all the subjects that he/she teaches. Apart from this, teachers may be assigned freely to teach subjects to classes. Of course, a head of class teacher may also teach his/her subjects to any other class in addition to his assigned class.	 

Furthermore, our app also needs to be able to support the student administration: enrolling new students and managing their data, updating their data if something changes and removing them from our system, if they change school or graduate. For a student we need their personal data, their grade level (1-4), their class (e.g. “2a) and their average grade.
<br>

##We also want to have an overview of the different classes including the class name (e.g. “4c”), who is the head of each class, how many students are in it and its grade average. Of course it should also be possible to update class information, such as the number of students, which might change, as well as the students’ grade average.	

The supported information management tasks should be as follows:
- Show all teachers in a suitable table with all their data
- Hire a new teacher: teacher ID, first name, family name, address, birthdate, subjects, assigned class (if applicable)
- Update the data for an existing teacher: family name, address, subjects, assigned class
- Dismiss a teacher
 <br> 

- Show all students in a suitable table with all their data
- Enroll a new student: student ID, name, birthdate, age, phone number, grade (1-4), class (e.g. 3b), average grade (if applicable)
- Update the data for an existing student: age, phone number, grade, class, average grade (if applicable)
- Dismiss a student (due to graduation or change of school)
 <br> 


- Show existing classes in a suitable table with all their data
- Create a new class: class ID, level (1-4), name (e.g. “2b”), number of students (max 15), grade average of all students in the class (if applicable)
- Update an existing class: number of students, grade average of all students in the class (if applicable)
- Delete a class
 <br> 









