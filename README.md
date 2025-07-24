# FileIntegrityChecker
COMPANY:CODTECH IT SOLUTIONS
NAME:KALAIMATHI G
INTERN ID:CT04DG1843
DOMAIN:CYBER SECCURITY & ETHICAL HACKING
DURATION:4 WEEKS
MENTOR:NEELA SANTHOSH
DESCRIPTION:📝 Task 1: File Integrity Checker – Description
In the realm of cybersecurity, ensuring the integrity of files is a fundamental necessity. Task 1 of the CodTech Cyber Security Internship involves building a File Integrity Checker using Python, aimed at detecting unauthorized or accidental changes in files by computing and comparing their cryptographic hash values. This task not only enhances your understanding of file security and hashing but also lays a strong foundation for secure programming practices.

🔐 Objective
The primary objective of this task is to develop a Python script that monitors changes in files by calculating and storing their hash values (using a cryptographic hash function such as SHA-256) and comparing them over time. This allows the detection of any changes, whether due to corruption, unauthorized modifications, or accidental overwriting. If the hash value of a file changes, it indicates that the file has been modified.

⚙ How It Works
A hash function takes input data (in this case, file content) and produces a fixed-length string, typically in hexadecimal format, known as a hash value or digest. Even a tiny change in the file content will result in a completely different hash. This makes hashing a powerful tool for verifying data integrity.

In this task, the program performs the following steps:

Scanning Files: It walks through a specified directory and collects a list of all files.

Hash Generation: For each file, it calculates the SHA-256 hash using Python’s built-in hashlib library.

Saving Hashes: It stores the file paths and their respective hash values in a JSON file named file_hashes.json.

Checking Integrity: On subsequent runs, the program re-calculates hashes and compares them with the previously saved ones.

Reporting Changes: If any hash has changed, or if a file has been added or deleted, the program flags these differences in a clear report.

This implementation provides an easy and effective way to verify file integrity without needing any external packages. It leverages standard Python libraries such as os, json, and hashlib.

📦 Deliverables
A standalone Python script: file_integrity_checker.py

JSON file to store hashes: file_hashes.json

Console-based interface to select between saving hashes or checking file integrity

Optional enhancements like logging or a GUI can be added for extra credit

💡 Why This Task Matters
File integrity monitoring is widely used in enterprise systems, cybersecurity protocols, compliance audits, and backup verification systems. From detecting malware infections to ensuring data reliability in secure environments, hashing and integrity checks are crucial techniques.

By completing this task, you will:

Understand and implement cryptographic hashing

Learn about file handling and directory traversal in Python

Develop skills in data serialization using JSON

Practice clean and readable code with comments and structure

Be introduced to real-world cybersecurity use cases

🛠 Tools & Technologies Used
Python 3.x

hashlib for SHA-256 hash calculation

os for file system navigation

json for saving/loading hash data

📁 Usage Example
First, run the script and choose the save option to store initial hash values of your files.

Later, run the script again and choose the check option.

The program will alert you of:

Modified files (hash changed)

Deleted files (missing)

New files (not previously hashed)

🏁 Conclusion
This task is essential for anyone beginning their journey in cybersecurity or software development. It introduces core security concepts like data integrity, cryptographic functions, and system monitoring. The Python-based File Integrity Checker you build will not only fulfill the internship requirement but also serve as a strong portfolio project that demonstrates your understanding of practical security implementations


#OUTPUT:
![Image](https://github.com/user-attachments/assets/f57952b6-146c-4700-b0f0-5eb13be3285b)
