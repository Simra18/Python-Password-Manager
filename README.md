# Password Manager in Python
This mini-project implements a **GUI-based Password Manager in Python** as part of the **Python Lab (PBL) internal assessment**.  
It demonstrates key concepts including **Tkinter GUI development**, **file handling**, **CRUD operations**, and user interaction via message boxes.

---

## Team Members

| Name | Roll Number |
|------|-------------|
| Tanisha | 1/24/SET/BCS/289 |
| Kiranjeet Kaur | 1/24/SET/BCS/295 |
| Drishti Parashar | 1/24/SET/BCS/298 |
| Simra Fatima | 1/24/SET/BCS/307 |

**Faculty Mentor:** Mr. Kushal (Assistant Professor)  
**Department:** Computer Science & Engineering  
**Institute:** MRIIRS  
**Academic Year:** 2025–2026  

---

## Overview
The Password Manager is a simple GUI application built using Python’s **Tkinter** library.  
It allows users to store, retrieve, view, and delete login credentials in a structured manner.

Key operations include:

- Adding new username–password entries  
- Retrieving the saved password for a specific username  
- Displaying all stored credentials  
- Deleting selected credentials  
- Error handling through message boxes  
- Persistent storage using a text file  

The application demonstrates the practical usage of **GUI programming**, **file handling**, and **CRUD operations**.

---

## Features

### Add Credentials  
Stores username–password pairs inside `passwords.txt`.

### Retrieve Password  
Displays the saved password for the entered username.

### View All Records  
Shows the list of all existing username–password entries.

### Delete Credentials  
Removes a selected user entry from the file.

### Tkinter GUI  
Graphical user interface with input fields and interactive buttons.

### Error Handling  
Uses message boxes for errors, confirmations, and prompts.

---

## Technologies and Modules Used

| Component | Purpose |
|----------|---------|
| Tkinter | GUI creation |
| tkinter.messagebox | Pop-up alerts and notifications |
| Python File Handling (I/O) | Read and write password data |
| OS Module | Used implicitly during file operations |

---

## System Workflow

1. User enters username and password.  
2. **Add** → Saves credentials to `passwords.txt`.  
3. **Get** → Retrieves password for the entered username.  
4. **List** → Displays all saved username–password pairs.  
5. **Delete** → Removes selected user credentials.  
6. Message boxes provide feedback and error alerts.

---

## Internal Working

### 1. Function: `add()`
- Appends new credentials to the text file  
- Shows a success message  

### 2. Function: `get()`
- Searches for a username  
- Displays the associated password  

### 3. Function: `getlist()`
- Reads the file  
- Displays all stored credentials in a formatted manner  

### 4. Function: `delete()`
- Removes specific credentials  
- Rewrites the updated list to the file  

---

## Sample Output
*(Screenshots from the project report may be added here.)*

---

## Conclusion
This project successfully demonstrates a functional **Password Manager** using Python.  
It highlights key programming concepts including:

- Tkinter GUI development  
- Text file data storage  
- CRUD operations  
- Exception handling  
- User-friendly interface design  

### Future Enhancements
- Encrypt stored passwords  
- Use a database instead of text files  
- Add search functionality  
- Built-in strong password generator  
- Multi-user authentication  
