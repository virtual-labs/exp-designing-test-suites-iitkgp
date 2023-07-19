## Procedure

Steps for conducting the experiment

#### **General Instructions**

Follow are the steps to be followed in general to perform the experiments in **Software Engineering Virtual Lab.**

1. Read the theory about the experiment
2. View the simulation provided for a chosen, related problem
3. Take the self evaluation to judge your understanding (optional, but recommended)
4. Solve the given list of exercises


#### **Experiment Specific Instructions**
Following are the instructions specifically for this experiment:


1. Type in the above code (in JavaScript) in the text area below the header **"Code"**
2. Click on the **"Create Test Suite"** button just below the code area. 
3. Add a title and summary for the test suite to be created.  When done, click on the **"Add"** button. If this test suite is not supposed to be added, click on the **"Cancel"** link.
4. After clicking on the **"Add"** button from the previous step, a dialog will display the new test suite. Every test suite is identified with a unique ID: an (auto-incrementing) integer prefixed with **"TS"**. The first test suite will have the ID **"TS0 "**, and so on.
5. An already added test suite could be removed by clicking on the **"Remove"** button.
6. Once a test suite has been created, click on the **"Add test cases"** button to add the test cases individually.
7. After clicking on the **"Add test cases"** button a spreadsheet-type dialog will appear just below the button. The spreadsheet has seven columns:
      1. **Test Suite No.**: Test Suite number.
      2. **Summary**: A brief description of the test case (mandatory)
      3. **Script**: A (JavaScript) function to be called for execution (mandatory)
      4. **Expected Output**: The value the above function call is expected to return (mandatory)
      5. **Actual Output**: The value actually obtained after making the function call. This column would be populated automatically after the test suite is executed.
      6. **Manual Testing**: Certain test cases could not be checked automatically. For example, a testing framework may not verify that an HTML element X is not overlapping with another HTML element Y. In such cases, manual intervention is required. To specify that a test case would be executed manually, select the **"Yes"** check box under this column.
      7. **Status**: Indicates the status of a test case after it is executed. Possible values are:
          1. **No Run**: The test suite has not been executed yet or the test case has been set for **Manual Testing**
          2. **Pass**: The concerned test case's expected and actual values are same
          3. **Fail**: The concerned test case's expected and actual values are NOT same
8. The number of columns in the spreadsheet are fixed (seven). The number of initial rows are 5. 
9. **NOTE**: Summary and Script of a test case is mandatory for every test case in the test suite. If a particular test case has no summary, the concerned test case, and all other subsequent test cases, would be ignored!
10. Enter Expected value of the test case. Click on the **"Execute test suite"** button to execute the test cases for the concerned test suite. Please note that this may not execute all the test cases in the test suite if the constraints as mentioned in the previous step are not met. Also, any test case set for **Manual testing** would be skipped.
11. Results of execution of the test suite would appear just below the **"Execute test suite"** button. If all the test cases of the test suite have passed (i.e. values under **Expected Output** column is same as under **Actual Output** column for each row), the background colour of the results dialog would be green. Otherwise, it would be red.

**NOTE**
- This interface allows testing of only JavaScript based of the above code ; other languages are not supported
- Real-life testing frameworks provide a lot of other options, which could not be accommodated here. The basic objective is to present a student with the look and feel of a simple testing framework.

