# CodeAlpha_Task-Automation-with-python-scripts
This Python automation script, built for CodeAlpha Internship Task 3, extracts all email addresses from a .txt file using regex and saves them into a new file. It demonstrates the use of re for pattern matching and file handling to automate repetitive tasks efficiently.

#  Email Extractor Automation

**CodeAlpha Internship – Task 3**

##  Introduction
This project is developed as part of the **CodeAlpha Internship (Task 3)**.  
The script automates the task of scanning through a text file, extracting all valid email addresses using **regular expressions**, and saving them into a new output file.  

This is a practical task automation example, showcasing how Python can simplify repetitive work like data cleaning and information extraction.

##  Objective
The main goal of this task is to:
- Accept a text file with random content (names, emails, text, etc.).
- Extract all valid email addresses automatically.
- Save the results into a clean `.txt` file.

##  Features
- Uses **regex (re)** to detect valid email formats.  
- Reads any `.txt` file containing text data.  
- Saves extracted emails into `emails.txt`.  
- Shows the total number of emails found.  
- Works entirely offline.  

##  Technologies Used
- **Python 3**
- **Regex (`re` module)**
- **File Handling (read/write)**

##  How to Run
1. Save the script as `email_extractor.py`.  
2. Create an `input.txt` file and add text with email addresses inside it.  
   Example:  
```

Contact us at [support@example.com](mailto:support@example.com) or [sales@example.org](mailto:sales@example.org).
You can also reach out to [admin123@test.com](mailto:admin123@test.com).

````
3. Run the program in terminal:  
```bash
python email_extractor.py
````

4. Check the output file `emails.txt` for extracted addresses.

## 📖 Example Run

```
 Extracted 3 email(s) and saved to emails.txt
```

Output file (`emails.txt`):

```
support@example.com
sales@example.org
admin123@test.com
```

##  Learning Outcomes

* Using **regular expressions** to find patterns.
* Handling **file input and output** in Python.
* Automating repetitive tasks with small scripts.
* Writing reusable and simple automation utilities.
---
  **Author**: Srinidhi
  **Internship**: CodeAlpha Internship
  **Task**: Task 3 – Task Automation with Python Scripts (Email Extractor)


