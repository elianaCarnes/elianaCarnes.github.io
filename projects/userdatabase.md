---
layout: project
type: project
image: img/menu.png
title: "User Database project"
date: 2024-11-02
published: true
labels:
  - Unix
  - C
summary: "A C-based project that manages user accounts by making updates to a database file with the use of an interactive menu"
---

<img class="img-fluid" src="https://plus.unsplash.com/premium_photo-1661963874418-df1110ee39c1?fm=jpg&q=60&w=3000&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8Y29kZXxlbnwwfHwwfHx8MA%3D%3D" width = "300">

This project is a C-based database I created as a final project in ICS 212, Fall 2024. The application operates on a Unix system and uses file-based storage to keep record of user-inputted information like name, address and account number. 

With this application a user is able to add, delete, find or print records through a menu that directly interacts with the database. The database file is read at the runtime and updated as the user chooses the quit option. It was made within the span of a month using vi text editor.

In this project I gained experience with properly implementing a debug feature through the use of a global variable. 

### Example Code:
```c

void displayMenu()
{
    if (debugmode)
    {
        printf("\n[DEBUG] Called function: displayMenu\n");
    }

    printf("\nPlease choose an option from the menu below:\n");
    printf("add: Add a new record to the database\n");
    printf("printall: Print all records in the database\n");
    printf("find: Find a record by account number\n");
    printf("delete: Delete a record by account number\n");
    printf("quit: Exit the program\n");
}
