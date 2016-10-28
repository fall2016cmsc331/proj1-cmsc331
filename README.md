# proj1-cmsc331

# This project is for students and advisors in the College of Natural and Mathematical Sciences.
# All of the files will be listed in the folder "proj1-cmsc331" under the username "fall2016cmsc331".
The names of the files are as following:






# In order to download and use the project, download the whole folder into the "swe2016" folder in the GL system.
 The site map will show the order and set up of the website.
 In order to use the website, you must go to https://swe.umbc.edu/~usernameHere.
 All of the files that you just downloaded will appear there. 
 The first file for the student website is 'login.html'.
 Clicking on that file will bring you to the beginning of the student website. 
 The first file for the advisor website is 'advisorCreater.html'.
 Clicking on that file will bring you to the beginning of the advisor website.
 All of the CSS code is coded in 'standard.css'.

# The authors of this project are: Anonymous 1, Anonymous 2, and Anonymous 3.

# In order to successfully use this project, you need a database to contain 3 tables.

# The first table is named 'student_table' and contains all of the information of the students. 
# The following is each column (there are 63) with their type values and any additional information about them.
 count int auto_increment primary_key
 fName varchar(40) -This is the student's first name
 lName varchar(40) -This is the student's last name
 campusID varchar(7) -The student's campus ID with a max number of 7 characters (format: AB12345)
 major text -The student's major.
 minor text NULL -The student's minor, it's allowed to be NULL since not all students have a minor.
 email varchar(35) -The student's email.
 2ndMajor int NULL -The student's second major (if applicable)
 goals1 text - Asks for the student's goals once they graduate college.
 goals2 text - Asks for the resources the student has used in order to learn more about their future goals
 goals3 text NULL - Asks if the student has had any intern or research experience, it's a NULL field since the student might have none.
 currClass1 varchar(15) - A current class the student is taking
 currClass2 varchar(15) - A current class the student is taking
 currClass3 varchar(15) - A current class the student is taking
 currClass4 varchar(15) NULL - A current class the student is taking, might be NULL. 
 currClass5 varchar(15) NULL - A current class the student is taking, might be NULL. 
 currClass6 varchar(15) NULL - A current class the student is taking, might be NULL. 
 nextClass1 varchar(15) NULL - A class the student is considering taking next semseter, might be NULL if they don't know which class(s) they want to take next semester. 
 nextClass2 varchar(15) NULL - A class the student is considering taking next semseter, might be NULL if they don't know which class(s) they want to take next semester. 
 nextClass3 varchar(15) NULL - A class the student is considering taking next semseter, might be NULL if they don't know which class(s) they want to take next semester. 
 nextClass4 varchar(15) NULL - A class the student is considering taking next semseter, might be NULL if they don't know which class(s) they want to take next semester. 
 nextClass5 varchar(15) NULL - A class the student is considering taking next semseter, might be NULL if they don't know which class(s) they want to take next semester. 
 nextClass6 varchar(15) NULL - A class the student is considering taking next semseter, might be NULL if they don't know which class(s) they want to take next semester. 
 reason1 text NULL - The student's reason for taking the next class next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 reason2 text NULL - The student's reason for taking the next class next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 reason3 text NULL - The student's reason for taking the next class next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 reason4 text NULL - The student's reason for taking the next class next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 reason5 text NULL - The student's reason for taking the next class next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 reason6 text NULL - The student's reason for taking the next class next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 numCredits1 varchar(1) NULL - The number of credits for the class the student wants to take next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 numCredits2 varchar(1) NULL - The number of credits for the class the student wants to take next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 numCredits3 varchar(1) NULL - The number of credits for the class the student wants to take next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 numCredits4 varchar(1) NULL - The number of credits for the class the student wants to take next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 numCredits5 varchar(1) NULL - The number of credits for the class the student wants to take next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 numCredits6 varchar(1) NULL - The number of credits for the class the student wants to take next semester, might be NULL if they don't know which class(s) they want to take next semester. 
 totalCredits varchar(3) - Total credits earned so far by the student.
 gpa tinyInt(4) - Current gpa
 upperCredits tinyInt(4) - The number of upper level credits the student has taken.
 WICredit tinyInt(4) - 1 if they have taken the course, 0 if they have not
 PECredit tinyInt(4) - the number of PE credits the student has taken.
 engCredit varchar(1) - The number of english credits the student has taken
 AHCredit varchar (1) - The number of arts and humanities credits the student has taken
 SSCredit varchar(1) - The number of social science credits the student has taken
 mathSciCredit varchar(1) - The number of math and science credits the student has taken
 cultCredit varchar(1) - The number of culture credits the student has taken
 langCredit varchar(1) - The number of foreign language credits the student has taken
 acPerform text - The student's self evaluation of their academic performance
 resource1 varchar(1) NULL - True or null if the student studied with classmates this semester.
 resource2 varchar(1) NULL - True or null if the student asked questions before/during/after class.
 resource3 varchar(1) NULL - True or null if the student took notes during class and reviewed them regularly.
 resource4 varchar(1) NULL - True or null if the student participated in blackboard discussion
 resource5 varchar(1) NULL - True or null if the student used a tutoring center.
 resource6 varchar(1) NULL - True or null if the student received tutoring from the Learning Resource Center.
 resource7 varchar(1) NULL - True or null if the student visited office hours. 
 resource8 varchar(1) NULL - True or null if the student emailed professors or TAs for help.
 timeCom1 text NULL - The student's current volunteer and co-curricular activities, if any.
 timeCom2 text NULL - The student's current time commitments to a job or family, if any
 timeCom3 text NULL - The length of the student's commute, if applicable
 commute varchar(3) NULL - The amount of hours the student commutes per week, if applicable.
 work varchar(3) NULL - The amount of hours the student works per week, if applicable.
 family varchar(3) NULL - The amount of hours the student spends for family responsibilities, if applicable.
 activities varchar(3) NULL - The amount of hours of extra curricular activities the student participates in, if applicable. 
 questions text NULL - Any questions the student might have.

# The second table is named "advisor_table" and it contains all of the group and indvidual appointments and infromation about the appointments.
# The following is each column (there are 17) with their type values and any additional information about them.
 count int auto_increment primary_key
 date date - the date of the appointment
 time varchar(5) - the time the appointment is at in military time
 name varchar(35) - The last name of the advisor or "Group" if the appointment is a group appointment
 fName varchar(35) NULL - The first name of the advisor or NULL if the appointment is a group
 available varchar(1) - 'T' if the appointment is available, 'F' if it is not.
 campusID1 varchar(7) - The campus ID of the first student (or only student if it is an individual appointment)
 NOTE: If the appointment is individual, campusID2 - campusID10 will start and remain NULL. If the appointment is a group, the ID slots will be filled one by one and if the 10th slot is full, the appointment becomes unavailable.
 campusID2 varchar(7) NULL - The campus ID of the second student of a group appointment.
 campusID3 varchar(7) NULL - The campus ID of the second student of a group appointment.
 campusID4 varchar(7) NULL - The campus ID of the second student of a group appointment.
 campusID5 varchar(7) NULL - The campus ID of the second student of a group appointment.
 campusID6 varchar(7) NULL - The campus ID of the second student of a group appointment.
 campusID7 varchar(7) NULL - The campus ID of the second student of a group appointment.
 campusID8 varchar(7) NULL - The campus ID of the second student of a group appointment.
 campusID9 varchar(7) NULL - The campus ID of the second student of a group appointment.
 campusID10 varchar(7) NULL - The campus ID of the second student of a group appointment.
 location varchar(15) - The location of the appointment.

# The third and final table is named "advising_table" and it contains information about the advisor.
# The following is each column (there are 6) with their type values and any additional information about them.
 count int auto_increment primary_key
 fName varchar(40) - The advisor's first name
 lName varchar(40) - The advisor's last name
 campusID varchar(7) - The advisor's campus ID
 email varchar(40) - The advisor's email
 office varchar(25) - The location of the advisor's office
