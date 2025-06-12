---
layout: project
type: project
image: img/menu.png
title: "User Database project"
date: 2024-11-02
published: true
labels:
  - Unix
  - C++
summary: "A C++ project that manages user accounts by making updates to a database file with the use of an interactive menu"
---

<img class="img-fluid" src="https://plus.unsplash.com/premium_photo-1661963874418-df1110ee39c1?fm=jpg&q=60&w=3000&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8Y29kZXxlbnwwfHwwfHx8MA%3D%3D" width="300">

This project is a C++ based database that operates from a terminal on a Unix system, I made this project as a final project for ICS 212, Fall 2024. The database was designed to create a system for users to store and edit records by reading the records from a file into a dynamically allocated linked list. This allowed for the user to add, delete, search and print records and maintain a database that updated with the changes made in the terminal by the user. When the application runs it loads the saved records from the file into a singly linked list at startup, and when the user exits the records and any changes are saved back to the same file.  

The function below shows how the program updates the file with the linked list when the user quits 
```

int llist::writefile() {
    std::ofstream outfile(filename);
    if (!outfile) return -1;

    record* current = start;
    while (current) {
        outfile << current->accountNumber << "\n"
                << current->name << "\n"
                << current->address << "\n";
        current = current->next;
    }
    return 0;
}
```
# Using Unix
Instead of using modern developing enviorments I also gained experience working within the Unix terminal using the vi text editor. This also meant looking for syntax errors line by line and losing work if I closed the window without saving with keyboard shortcuts. Debugging the program was also different, and I implemented a debug feature that worked through a global variable. This allowed me to enable and disable any debug outputs by adding a debug flag during compliation. 
