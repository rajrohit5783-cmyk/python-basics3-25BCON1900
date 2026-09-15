# README Audit

## README Fact-Check Table

| Claim Made in README | True? | Evidence / Correction Made |
|---|---|---|
| Program demonstrates Python classes and objects | Yes | The code defines a `Student` class and creates an object using `s1 = Student()`. |
| Program calculates factorial | No | There is no factorial calculation in the program. Claim should be removed. |
| Program generates Fibonacci numbers | No | There is no Fibonacci logic in the program. Claim should be removed. |
| Program defines a `Student` class | Yes | The code contains `class Student:`. |
| Program uses a constructor | Yes | The class contains the `__init__()` method. |
| Student name is stored | Yes | `self.name = "Rahul"` stores the student's name. |
| Student roll number is stored | Yes | `self.roll = 101` stores the roll number. |
| Student marks are stored | Yes | `self.marks = 87.5` stores the marks. |
| Program takes student information from the user | No | There is no `input()` function. All student information is hard-coded. |
| Program accepts terminal input | No | The program does not request any input from the user. |
| Program validates student information | No | No validation conditions are present. |
| Program handles invalid input | No | There is no user input or `try/except` error handling. |
| Program creates a Student object | Yes | The code creates `s1 = Student()`. |
| Program displays the student's name | Yes | `print("Name:", s1.name)` displays the name. |
| Program displays the student's roll number | Yes | `print("Roll:", s1.roll)` displays the roll number. |
| Program displays the student's marks | Yes | `print("Marks:", format(s1.marks, ".1f"))` displays the marks. |
| Marks are displayed with one decimal place | Yes | The code uses `format(s1.marks, ".1f")`. |
| Student information is dynamically entered | No | The values are fixed inside the class constructor. |
| Program uses external Python libraries | No | There are no imports or external dependencies. |
| NumPy is required | No | NumPy is not imported or used. |
| `requirements.txt` is required | No | The program has no external dependencies. |
| `pip install -r requirements.txt` is required | No | No packages need to be installed. |
| Python 3 is required | Yes | The project is a Python script and can be run using Python 3. |
| Program can be run using `python struct.py` | Yes | `struct.py` is a standalone Python script. |
| Program has error handling | No | No explicit error-handling logic exists. |
| Project uses an MIT License | No | No `LICENSE` file is provided. The README should not claim MIT unless one is added. |
| Project contains a Student class example | Yes | The program defines `Student`, creates an instance, and displays its attributes. |
| Project demonstrates object attributes | Yes | `name`, `roll`, and `marks` are stored as instance attributes. |
| Program contains multiple students | No | Only one object, `s1`, is created. |
| Program supports editing student details | No | There is no code for modifying the object's attributes after creation. |
| Program stores student data permanently | No | The data only exists while the Python program is running. |
