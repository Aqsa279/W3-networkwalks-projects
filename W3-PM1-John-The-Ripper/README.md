
# W3-PM1 - Password Cracking with John the Ripper

## 1. Project Overview
This project focuses on recovering the password of a protected PDF file using John the Ripper (JTR) and Johnny GUI.

The lab was performed as part of Week 3 Cybersecurity & Ethical Hacking training at Networkwalks Academy.

## 2. Objective
- Understand password-protected PDF files.
- Extract PDF password hashes.
- Configure John the Ripper.
- Perform password recovery using Johnny GUI.
- Understand dictionary-based password attacks.

## 3. Tools Used
- John the Ripper (JTR)
- Johnny GUI
- Online PDF Hash Extractor
- Windows Operating System
- Notepad

## 4. Methodology

### Step 1: Install John the Ripper
Download John the Ripper from its official website and extract the package.

Official Website:
https://www.openwall.com/john/

### Step 2: Install Johnny GUI
Download and install Johnny GUI.

Website:
https://openwall.info/wiki/john/johnny

### Step 3: Configure John the Ripper
- Open Johnny GUI.
- Navigate to Settings.
- Browse to the John executable.
- Select john.exe from the run folder.

### Step 4: Extract PDF Hash
- Open the PDF Hash Extractor.
- Upload the authorized training PDF.
- Extract and copy the complete hash.

Tool:
https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

### Step 5: Save Hash File
- Open Notepad.
- Paste the extracted PDF hash.
- Save the file as hash1.txt.

### Step 6: Load Hash in Johnny
- Open Johnny GUI.
- Select Open Password File.
- Browse and select hash1.txt.

### Step 7: Start Password Recovery
- Click Start New Attack.
- Allow John the Ripper to process the hash.
- Observe the recovered password in Johnny.

### Step 8: Verify Result
- Open the protected training PDF.
- Enter the recovered password.
- Verify that the PDF opens successfully.

## 5. Screenshots
<img width="311" height="415" alt="Screenshot 2026-11-18 104728" src="https://github.com/user-attachments/assets/25a2903d-9f33-49cf-983b-5e6aaa84d1ff" />
<img width="299" height="392" alt="Screenshot 2026-11-18 105702" src="https://github.com/user-attachments/assets/fc73523f-8db1-48c5-9c80-d957cedd0c73" />
<img width="306" height="410" alt="Screenshot 2026-11-18 105943" src="https://github.com/user-attachments/assets/a23f1525-d8df-4f74-8934-0cf62bd9a3ee" />



## 6. Learning Outcomes
- Learned how PDF password hashes are extracted.
- Practiced configuring John the Ripper.
- Learned how to use Johnny GUI.
- Understood password recovery workflows.
- Learned the importance of strong passwords.

## 7. Conclusion
This practical exercise demonstrated how password-protected PDF files can be assessed using John the Ripper and Johnny GUI.

## 8. Disclaimer
This activity was performed for educational purposes in an authorized cybersecurity training lab.

## Author
Aqsa Shafiq

GitHub: https://github.com/Aqsa279

