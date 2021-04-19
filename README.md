# C Sharp Grade Book Application

The C Sharp Grade Book Application is a designed to allow instructors to create gradebooks, add students to those grade books, add grades to those students, and calculate statics such as GPA (Grade Point Average).

## Accepted Commands

### Commands when no gradebooks are open
- "Create `Name of Gradebook` `Is this Gradebook Weighted (true/false)`" : Creates a new gradebook with the provided name
- "Help" : gives you a list of all valid commands within the given context
- "Load `Name of GradeBook`"
- "Quit" : Closes the application

### Commands when a gradebook is open
- "Add `Name of Student` `Type of Student` `Type of Enrollment`" : Adds a new student to the open gradebook
- "Remove `Name of Student`" : Removes a student with the provided name from the gradebook. (if a student with that name exists in the gradebook)
- "List" : Lists all students in the open gradebook
- "AddGrade `Name of Student` `Score`" : Adds to the given value to provided student's grades.
- "RemoveGrade `Name of Student` `Score`" : Removes the given value from the provided student's grade. (if that value exists in the stundent's grades)
- "Statistics all" : Provides statistical output for all students in the open gradebook
- "Statistics `Name of Student`" : Provides statistical out put for the provided student. (if that student exists)
- "Help" : Gives you a list of all valid commands within the given context
- "Save" : Saves the currently open gradebook
- "Close" : Closes the gradebook

# Setup the Application

## If you want to use Visual Studio
If you want to use Visual Studio (highly recommended) follow the following steps:
-	If you already have Visual Studio installed make sure you have .Net Core installed by running the "Visual Studio Installer" and making sure ".NET Core cross-platform development" is checked
-	If you need to install visual studio download it at https://www.microsoft.com/net/download/ (If you'r using Windows you'll want to check ".NET Core cross-platform development" on the workloads screen during installation.)
-   Open the .sln file in visual studio
-	To run the application simply press the Start Debug button (green arrow) or press F5
-   If you're using Visual Studio on Windows, to run tests open the Test menu, click Run, then click on Run all tests (results will show up in the Test Explorer)
-   If you're using Visual Studio on macOS, to run tests, select the GradeBookTests Project, then go to the Run menu, then click on Run Unit Tests (results will show up in the Unit Tests panel)

(Note: All tests should fail at this point, this is by design. As you progress through the projects more and more tests will pass. All tests should pass upon completion of the project.)

## If you don't plan to use Visual studio
If you would rather use something other than Visual Studio
-	Install the .Net Core SDK from https://www.microsoft.com/net/download/core once that installation completes you're ready to roll!
-	To run the application go into the GradeBook project folder and type `dotnet run`
-	To run the tests go into the GradeBookTests project folder and type `dotnet test`

# Features you will impliment

- Add support for Ranked Grading
- Add support for Weighted GPAs
