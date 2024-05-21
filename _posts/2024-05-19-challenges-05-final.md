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

### Requirements
- Store student information (name, ID) and their grades using dictionaries.
- Use tuples to store grade details (subject, score).
- Utilize sets to track unique subjects:
  - when you start a all students report, you start the report:
    - `In this school we teach: English, Math, ...'` - this shoud come from the set (collection of unique elements)

### Features
- Add new students and their grades.
- Update existing grades.
- Calculate the average grade for each student.
- List all students and their grades (or list all subjects and average grades calculated from students records).

### Guidance
- **Data Structure:** Use a nested dictionary to store student information and grades.
- **Calculations:** Write functions to calculate averages and handle grade updates.
- **Validation:** Ensure grades are valid numbers and handle invalid input gracefully.
- **User Interface:** Create a command-line interface for user interactions.


## Project 2: Contact Book Application

### Objective
Develop a contact book application to store and manage contact information using dictionaries and tuples.

### Requirements
- Store contact details (name, phone number, email) using dictionaries.
- Use tuples to store immutable contact information (date of birth, address).
- Implement search and update functionalities.

### Features
- Add new contacts.
- Update existing contacts.
- Search for contacts by name.
- List all contacts.

### Guidance
- **Data Structure:** Use dictionaries for mutable data and tuples for immutable data.
- **Search Functionality:** Implement search by name with partial matches.
- **Error Handling:** Manage errors gracefully, such as updating a non-existent contact.
- **User Experience:** Design an intuitive user interface for adding, updating, and searching contacts.

---

Now, the code doesn't have to be perfect and you don't have to implement all the features. The important thing is that you have all the functionalities (even if they are not all very detailed), that you use all the data structures (sets, tuples, dictionaries, lists) and that your code is working.

