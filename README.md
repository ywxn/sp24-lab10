# sp24-lab10
Materials for week 10 lab in CS-370.

_April 2, 2024_

Organization:
* mvc-timer: The MVC example application developed by Prof Davis

## Team Members for Part 1
Neel Troeger
Jas Liu

## Team Roles for Part 1
Who will start out as
* DRIVER: Neel
* NAVIGATOR: Jas

You will switch halfway through this activity.

## Part 1 Documentation

_Write your answers to the questions below._

* What were the main ideas from the pre-lab reading?

Model-view-controller separates code into three parts, model, which is the backend, view, which is the front-end, and controller, which is the brains of what is displayed.

* What questions did you have about this material? What did you find confusing?

Dependency injection was a bit confusing.

### Exercise 0: Run the tests and the application
View the README file in the mvc-timer directory. Run the tests and the application.

_If you have any trouble running the application or tests, please note it here._

### Exercise 1: Read the code
Read the code to understand what happens when you run the text timer application, starting from timer.py. 

Then read the code to understand what happens when you run the GUI application, set the time, and start the timer.

What questions do you have? _Write them here. If you need to know, ask Prof Davis since she wrote the code!_

N/A

### Exercise 2: Patterns and principles
_Answer the following questions to the best of your ability._
* Which concrete classes implement the Observer and Observable roles?
view_gui and view_text use the Observer pattern to observe the model, and display the time remaining.

* How do the model, controller, and view classes gain references to each other? What style of dependency injection does the application use: constructor, method, or property injection?

Constructor injection is used to pass references to the model, view, and controller classes.

### Exercise 3: Extending the code
Extend the text or GUI application to play a sound when the timer is done.

[x]

As time permits, try other exercises from the README in the `mvc-timer` directory.

[x]

_Record here: What extensions did you implement or attempt to implement?_

Questions:
2,3,4,6