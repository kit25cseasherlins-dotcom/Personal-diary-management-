#  Personal Diary Management System (C )

##  Project Overview

The **Personal Diary Management System** is a command-line application written in **C** that allows users to securely maintain daily diary entries.
It includes features like password protection, writing entries, viewing records, and deleting specific entries.


## Objective

To develop a secure and user-friendly system that:

* Stores personal diary entries
* Protects data using password authentication
* Allows efficient management of entries



## Technologies Used

* **Language:** C
* **Concepts:** File Handling, Structures, Strings, Dynamic Memory
* **Libraries:** `stdio.h`, `stdlib.h`, `string.h`, `ctype.h`, `time.h`


## Key Features

### Password Protection

* First-time users create a password
* Password is stored securely using a simple hashing method
* Login required every time the program runs

---

###  Write Entry

* Add diary entries (up to 500 characters)
* Automatically stores current date
* Saves data to file (`diary.txt`)

---

### View Entries

* Displays all stored diary entries
* Reads directly from file

---

###  Delete Entry

* Lists entries by date
* User selects entry number
* Removes selected entry safely

---

##  How It Works

1. User sets password (first time only)
2. Password is hashed and stored
3. User logs in using password
4. Menu-driven system allows:

   * Add entry
   * View entries
   * Delete entry

---

##  File Structure

```id="p9sl0n"
project-folder/
│── diary.txt        (stores entries)
│── password.dat     (stores hashed password)
│── diary.c          (main source code)
```

---

##  How to Run

### Step 1: Compile

```id="m4kqyl"
gcc diary.c -o diary
```

### Step 2: Run

```id="p3kz8g"
./diary
```

 On Windows:

```id="cz2hj5"
diary.exe
```

---

##  Sample Output

```id="9j66y7"
PERSONAL DIARY MANAGEMENT

Enter password:
Login Successful!

1. Write New Entry
2. View All Entries
3. Delete an Entry
4. Exit
```

---

## Applications

* Personal journaling systems
* Secure note management
* Beginner-level secure file handling project
* Learning file operations in C

---

## Future Enhancements

* Strong encryption instead of simple hash
* GUI-based diary system
* Search entries by date
* Edit existing entries
* Cloud storage integration

---

##  Limitations

* Uses simple hashing (not secure for real-world use)
* File-based storage (no database)
* Limited input size

---

##  Author

**Sherlin S**


---

##  Acknowledgment

This project is developed as part of academic learning to demonstrate file handling, data structures, and secure input handling in C.
