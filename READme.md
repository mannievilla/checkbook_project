## Command Line Checkbook Application
* You will create a command line checkbook application that allows users to track their finances with a command line interface.

#### Project Requirements
* Build a .py file that will be run from the command line.

* When run, the application should welcome the user, and prompt them for an action to take:

```view current balanc```
```add a debit (withdrawal)```
```add a credit (deposit)```
```exit```

* The application should notify the user if the input is invalid and prompt for another choice.

* The application should persist between times that it is run.

* Example, if you run the application, add some credits, exit the application and run it again, you should still see the balance that you previously created. In order to do this, your application will need to store its data in a text file. Consider creating a file where each line in the file represents a single transaction.

* Utilize functions to call the balance, debit, credit, and exit