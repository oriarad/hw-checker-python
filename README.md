# Overview
Checking homework exercise of code, is very similar to testing software.  
Still, there is one significant difference - when checking homework exercises, you usually need to check many different pieces of code (aka - the students' submissions) for the same functionality (aka - the exercise's requirements).  
So, this project is a framework that helps the teacher/instructor to automatically execute test-cases on multiple code submissions.

# Features
* Unit-testing multiple code with the same test-cases
* Summaries the tests results - for each student
* Execute coding-conventions checkers (in case instructed to follow)
* Produce a RTF/Word documents to the submitted code, for each submitted file - so the teacher will be able to review and comment each student submission


# Example
Put under the root folder, your test case file, the "script" folder content, and under "submissions" folder, all the submissions - every student, under seperate folder:

- Root
  - submissions
    - John_Smith
      - myfile.py
      - another_file_to_test.py
    - Rick_Sanchez
      - myfile.py
      - another_file_to_test.py
    - Keyser_Soze
      - myfile.py
      - another_file_to_test.py
    - Louis_Cyphre
      - myfile.py
      - another_file_to_test.py      
  - execute_all_tests.bat
  - test_homework3.py
```bat
execute_all_tests.bat submissions
```

# Results
![Image of tests_images](resources/results_example.PNG)
