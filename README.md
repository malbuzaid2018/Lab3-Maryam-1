# COMP 271 002 SU18 Lab 3

# Team project

Work in teams of two (optionally) but submit individually (see details below)

# Objectives

An understanding of the following concepts and techniques:

- algorithmic complexity
- runtime performance
  - how to measure
  - how it relates to algorithmic complexity
- abstract data types (ADT)
- array-based versus linked lists
- getting started with iterators
- automated unit testing using JUnit
  - testing for exceptions
  - test fixtures and assertions
  
# Instructions

The key idea is to think about this lab like a physics experiment! 
You will set it up and then take measurements.

1. Review the code.
1. Fix the syntax errors (if any, though there probably aren't any).
2. Run the code for various inputs to gain an understanding of what it does.
3. Complete the items marked TODO in the code and get the tests to pass.
2. Conduct the performance measurements: you will find the running times in the test report.
4. Create a markdown document called Answers.md and answer the various questions embedded in the code.

# Deliverables and submission

Please submit the following deliverables:

- Shared GitHub lab3 repository where you worked on this project as a group 
  (there should be commits from all group members); or individual GitHub repo if you worked alone
- Individual Sakai submission under "Lab 3":
  - URL of shared GitHub team repository
  - Brief description of your collaboration style and summary of your 
    individual contributions to this team project

# Grading

- 8 submission via GitHub
- 8 tests passing and completion of items marked TODO
- 8 performance testing for increasing problem sizes
- 16 written part
  - 12 responses to the questions above
  - 4 grammar, style, formatting


*40 points TOTAL*

# Listing of questions embedded in the code

TestIterator and TestList Classes
- setUp methods
It does not make any difference if list is a new ArrayList or a new LinkedList.

TestList Class
- testRemoveObject method
list.remove(5) removes the value at index 5 and moves the values to the right of 
it left 1 index. This decreases the total list size by 1.
list.remove(Integer.valueOf(5)) removes the entry in the list that has a value 
of 5. Values to the right of this entry are moved left 1 index.

# Link to Google Spreadsheet for arraylist and linked comparison

https://docs.google.com/spreadsheets/d/1cMoOLd-TjWxw3DsshBoT4s4CtSpXfUL-ztVXhQ52Zdw/edit?usp=sharing


