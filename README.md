# CS151-GroupUp

GroupSchedule
-------------
- **Project title** : Group Up
- **Team #4** : Namyoon Cho, Danilo Makarewycz, Preethi Mohan
- **Proposal Contributions**:   
  Namyoon made an idea of pfoject, wrote Operations for each user and formatted the README file. </br>
  Danilo wrote High-level description of solution, Functionality, Previous works. </br>
  Preethi Mohan wrote Problems/issue to resolve, Description of assumptions / operating environments / intended usage. </br>
  
- **Code and Report Contributions**:  
  + Namyoon
    - code 
      -login/signup
    - report
      -wrote the state diagram
      -updated diagrams
      -formatted the report into GitHub
  + Danilo
    - code
      -Day/Schedule/User/ErrorPopup/MysqlConn classes and all the exception classes, handled database and execptions.
      -Designed and normalized database in MySQL.
      -Wrote the MYsqlConn class which contains methods to insert, delete, and query information permanently stored in the database.
      -Handled the Model and Controller aspects of the MVC design pattern.
      -Formatted and implemented the Singleton design pattern in User.
      -Enabled the code to create User and Schedule objects from user inputs and queried data to display in the UI and store in the database.
      -Edited default GUI text fields and combo boxes to display queried information
      -Edited the base personal schedule display made by Preethi to dislay time inputs previously saved by a user.
    - report
      -wrote the case diagram
  + Preethi  
    - code
      -all main gui pages such as login/signup/dashboard/schedule.
      -implemented editable calendars for the use to check boxes in.
      -Handled fetching data from user inputs in a personal schedule upon save, and putting them into a Schedule obect.
      -designed the primary visuals of all GUI classes.
      -created text and passord fields, labels, and buttons for the user to interact with.
    - report
      -wrote the sequence diagram and usecase diagram
  
- **Problem/issue to resolve**  
  >  People face various difficulties in coordinating schedules for meetings, meetups, and other such events, where viewing everyone's schedule in one place is not usually an option and deciding availability is complicated. Oftentimes, people will simply coordinate over text or mail to share their own availabilities, which can be unorganized without a means of displaying availabilities together. People, mainly students and office workers/coworkers, need a way to ease the process of coordinating schedules and finding available times.   

- **Previous works**  
  > **Already existing websites**
    - Google Calendar [1]
    - When2meet [2]</br></br>
    
  >  **Problems with existing applications**
     - Google calendar has a shared calendar option, but is mainly meant for workspaces, and events can only be created by the owner. When2meet users can share weekly and multi-day views, but is not appealing to the eye and users cannot easily access their information nor other scheudles.

 
- **Description of assumptions / operating environments / intended usage**
  >  This application is intended for students and coworkers, where the operating environment to be used is a .jar file and a relational database management system / server that supports SQL code (For the purpose of this project, the RDBMS is simulated using MySQL Workbench. To run this program, it is assumed that the user has MySQL Workbench already downloaded). It is assumed that schedules on this website will only be shared with known or “friended” people; in other words, schedules will not be public.

- **Diagrams**
  [Link to UML diagrams](https://github.com/nxmyxxn/CS151-GroupUp/tree/preethiBranch2/diagrams#uml-diagram)

- **Functionality**
  > This application will allow users to view and edit both personal and group schedules in one place. It will allow users to create their own group schedules with other users, where people will be allowed to describe their availability on the selected days on a scale from “no availability” to “completely free.” This will grant users better customization options and can involve users’ flexibility.  An automated group schedule created by the application itself will also exist. Users who utilize this feature will not have to spend extra time looking at schedules and planning available times; available times will be automatically mapped out for a group, increasing time efficiency in terms of scheduling. Additionally, this application will allow users to make both weekly schedules for meetups that are intended to be weekly occurrences and monthly schedules to plan monthly occurrences, major events, and/or inconsistent events.  

- **Operations for each user**  
  > **Student/ Co-workers**  
    - create account
    - log in/ log out
    - make timetable
    - write schedule in the calendar</br></br>
        
   > **Student/ Co worker who owns the schedule**
    - Add member
    - Delete member

- **Solution**  
  When users create groups and display their free time on the calendar, they can see the free time in common, making it easier to make appointments or share schedules with each other.

- **Steps to run the code**
  1. Welcome page : You can see Signup button and Login Button. If you have your account you can login if not you can sign up. 
  2.  Signup : It is possible only by entering a password that meets the conditions based on the exception code written. 
  3.  Login : Log in with the information that is registered as a member.
  4.  Create Own Schedule : On the Home page there is Schedules button. If you click that button, you can make there own schedules.
      Check the checkboxs in the calendar when you are free.
  4.  Create Group : On the Home page there is Create Group button. If you click that button, you can make their own group and see each other's schedules. 
  5.  Check the free time on the calendar : You can just check the check boxed and click the save button.
  6.  Check the common free time of your freinds or group users.
  7.  Logout : On the Home page there is Logout button. If you click that button, you can see the welcomepage again.

- **Snapshot of the running program**
  ![initialWelcomePage](https://user-images.githubusercontent.com/72899436/236298065-8675a9aa-d959-4b65-a372-43dc861b1d68.PNG)
  
  ![home](https://user-images.githubusercontent.com/72899436/236298127-438581eb-c49b-4d99-82da-7cf119cb992a.PNG)
  
  ![SignUp0](https://user-images.githubusercontent.com/72899436/236317735-21e83d15-60c7-4abe-965d-780ace11054a.PNG)
  
  ![login](https://user-images.githubusercontent.com/72899436/236297958-73fa85eb-c354-49d6-8ccc-dbbd877425a7.PNG)
  
  ![createScheduleWithCheck](https://user-images.githubusercontent.com/72899436/236298192-df33db90-955b-42c7-81e3-09b6229c189e.PNG)

- **References**
  > - [1] https://calendar.google.com/ 
  > - [2] 8 Degrees, LLC “when2meet” https://www.when2meet.com/.
 
