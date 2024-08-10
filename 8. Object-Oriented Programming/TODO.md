# 1. Create a module for the driver code
- Create `main.py` module that will import and make use of the custom class code

# 2. Setup modules/packages for custom classes code
- Keep custom class code separate the driver code. That is, the code in `main.py` that makes use of the classes.
- At the minimum, the class definitions should be created in a separate module.
- Bonus points if you create a package that contains a module for each custom class and makes use of relative imports within the package.

# 3. Create a class
## Define the Person class in 
Define a class 'Person' with the following attributes:
- name: the person's name
- age: the person's age in years
- friends: data structure for keeping track of friends
## Add methods to the Person class
- Define a method 'greet' that prints a greeting using the person's name and age.
- Define a method 'happy_new_year' that prints a happy new year greeting for every friend

# 4. Instantiate objects
## Create Person objects
In `main.py` Instantiate five Person objects as the table below describes

| Name  | Age | Friends         |
|-------|-----|-----------------|
| Alice | 28  | Bob, Carl, Devon|
| Bob   | 30  | Alice, Carl     |
| Carl  | 27  | Alice, Bob      |
| Devon | 32  | Alice           |
| Earl  | 29  |                 |

## Use object attributes
- Calculate the total years lived by all five people when summed

## Call object methods
- Call the 'greet' method on each object.
- Call the 'happy_new_year' method on each object

# 5. Inheritance
## Create a class that inherits from another class
Define a class 'Student' that inherits from 'Person'.
## Define additional attributes
Student should have two additional attributes:
- student_id: unique ID of the student at their school
- school_name: name of the school they attend

# 6. Polymorphism
## Override method
- Define a method in the 'Student' class that overrides the 'greet' method in the 'Person' class so that it also mentions that they're a student along with the name of the school they attend.
