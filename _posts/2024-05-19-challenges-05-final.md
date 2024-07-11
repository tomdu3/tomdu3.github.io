---
title: Weekly Challenges - Week 3 - Individual Assignment
date: 2024-5-19 03:30:00 +0000
categories: [python, task]
tags: [python,programming,code]
---

You are required to complete one of the two following assignments. If you could do both, even better, but I don't want to overload you with too many projects

## Project 1: Student Grades Management System

### Objective
Develop a system to manage and analyze student grades using complex data structures.

## Detailed Explanation and Requirements

- **Students Data Structure**: Use dictionaries to store student information. Each student should have an ID as the key and a dictionary as the value. This inner dictionary should contain the student's name and their grades.
- **Grades Data Structure**: Within each student's dictionary, use a nested dictionary to store subjects and corresponding scores.
- **Dictionary for Students**: The outer dictionary will store student IDs as keys. Each student ID will map to another dictionary containing the student's name and their grades.
- **Nested Dictionaries:** Each student's grades will be stored in a nested dictionary within their personal dictionary. The keys of this nested dictionary will be subjects, and the values will be the scores for those subjects.
**Unique Subjects**: From the whole dictionary, create a variable that will store all the subjects that are tought at the school. You can generate this set using the set function or you can make a list by using a loop and checking if the subject is already in the list.

- Example of the data structure for students:
```python
students = {
    "001": {
        "name": "Alice",
        "grades": {
            "Math": 85,
            "English": 90,
            "Science": 78
        }
    },
```

### Features
- Add new students and their grades.
- Update existing grades.
- Calculate the average grade for each student.
- List all students and their grades (or list all subjects and average grades calculated from students records).

### Guidance
- **Calculations:** Write functions to calculate averages and handle grade updates.
- **Validation:** Ensure grades are valid numbers and handle invalid input gracefully.
- **User Interface:** Create a command-line interface for user interactions.


## Project 2: Contact Book Application

### Objective
Develop a contact book application to store and manage contact information using dictionaries and tuples.

### Requirements
- Store contact details (name, phone number, email) using dictionaries.
- Implement search and update functionalities.

### Features
- Add new contacts.
- Update existing contacts.
- Search for contacts by name.
- List all contacts.

### Guidance
- **Data Structure:** You can use dictionaries, lists, or tuples to store and manage contact information.
- **Search Functionality:** Implement search by name with partial matches.
- **Error Handling:** Manage errors gracefully, such as updating a non-existent contact.
- **User Experience:** Design an intuitive user interface for adding, updating, and searching contacts.

---

Now, the code doesn't have to be perfect and you don't have to implement a very detailed and intuitive user interface. The important thing is that you have all the functionalities (even if they are not all very detailed), that you use complex data structures (sets, tuples, dictionaries, lists) and that your code is working.

