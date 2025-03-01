
---

# EliteWrap Usage Guide

This guide provides detailed instructions on how to use EliteWrap to package and execute applications. Follow the steps below to get started.

## Prerequisites

- Ensure that you have `calc.exe` and `notepad.exe` (or any custom `.exe` programs) in your working directory.

## Step 1: Setup

1. **Download the EliteWrap Software**:
   - Download `elitewrap.zip` from the provided link. ( Password is 'p4ssw0rd' )
   - Extract the contents of the zip file to your desired location.

## Step 2: Prepare Your Environment

1. **Navigate to EliteWrap Directory**:
   - Open a command prompt.
   - Change your directory to the location where you extracted `elitewrap`.

   ```bash
   cd path\to\elitewrap
   ```

## Step 3: Organize Your Files

1. **Place Executable Files**:
   - Ensure that `calc.exe` and `notepad.exe` are placed in the same directory as EliteWrap.

## Step 4: Execute EliteWrap

1. **Run EliteWrap**:
   - In the command prompt, run the following command:

   ```bash
   elitewrap
   ```

   ![EliteWrap Command Line Interface](https://github.com/user-attachments/assets/f2c2e821-616e-4452-94bf-a87edf78a730)

## Step 5: Configure EliteWrap

1. **Set Output File**:
   - Enter the name of the output file when prompted (e.g., `elitetest.exe`).

2. **Execution Parameters**:
   - Specify which file to run visibly (e.g., `calc.exe`).
   - Choose the operation mode from the following options:
     1. Pack only
     2. Pack and execute, visible, asynchronously
     3. Pack and execute, hidden, asynchronously
     4. Pack and execute, visible, synchronously
     5. Pack and execute, hidden, synchronously
     6. Execute only, visible, asynchronously
     7. Execute only, hidden, asynchronously
     8. Execute only, visible, synchronously
     9. Execute only, hidden, synchronously
   - Enter additional command lines if necessary.
   - Specify a second file to install surreptitiously (e.g., `notepad.exe`).

   ![EliteWrap Configuration](https://github.com/user-attachments/assets/305f3ba5-5816-4af3-a1a3-58c590cd7f16)

## Step 6: Verify Installation

1. **Check Directory Contents**:
   - Attach a screenshot of the directory showing all files including the newly created `elitetest.exe`.

   ![Directory Screenshot](https://github.com/user-attachments/assets/d6d00924-f770-438f-bbe3-4b9842f42dd6)

## Step 7: Monitor Task Execution

1. **Check Running Applications**:
   - Open Task Manager.
   - Verify if the hidden application is also running.
   - Attach a screenshot of the Task Manager as proof.

   ![Task Manager Screenshot](https://github.com/user-attachments/assets/694746f7-a2a1-4c84-ab2d-4fea81427640)

## Step 8: Reflection and Submission

1. **Documentation**:
   - Attach a screenshot for each of the above steps to document your work process.

2. **Reflection**:
   - Write a brief reflection on what you learned by creating and using such a Trojan horse.
   - Discuss the potential impacts if the Trojan were used to distribute malicious programs:
     - What types of damage could such a Trojan cause?
     - What personal, organizational, or societal harms might result?

3. **Mitigation Strategies**:
   - Provide strategies for mitigating the risks associated with Trojan horses. Consider:
     - How can users protect themselves from unintentionally installing Trojans?
     - What security practices should organizations implement to defend against such threats?

Please submit all screenshots and written responses to the course management platform by the deadline specified.
## Reference: https://grimthereaperteam.medium.com/how-to-create-the-simple-trojan-fd8303b85a38

---
