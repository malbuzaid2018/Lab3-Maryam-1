# COMP 271 002 SU18 Lab 3

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

TestPerformance Class
- As the size increase the Add/Remove operation has been perfomed much faster by the LinkedList as compared to the Arraylist. 
Similarly, the Access operation has been performed much faster by ArrayList as compared to the LinkedList. The difference in
the performance is of some fraction of seconds but that counts when we have to compare the complexity or efficiency of both the
structures.

# Link to Google Spreadsheet for arraylist and linked comparison

https://docs.google.com/spreadsheets/d/1cMoOLd-TjWxw3DsshBoT4s4CtSpXfUL-ztVXhQ52Zdw/edit?usp=sharing


