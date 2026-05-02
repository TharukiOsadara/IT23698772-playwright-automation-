# IT23698772-playwright-automation-

# IT3040 - ITPM Assignment 1: Transliteration Accuracy Testing

## 1. Project Overview
This project is an individual assessment for the **IT3040 - Information Technology Project Management** module[cite: 1]. The goal is to test a live application for its transliteration accuracy, specifically converting chat-style Singlish into Sinhala output[cite: 1].

*   **Target Application**: [PixelsSuite Chat Translator](https://www.pixelssuite.com/chat-translator)[cite: 1]
*   **Student Name**: [Insert Your Name Here]
*   **Registration Number**: [Insert Your Reg No Here]
*   **Course**: BSc (Hons) in Information Technology - Year 3 (SLIIT)[cite: 1]

---

## 2. Objective & Scope
The main objective is to assess the correctness of the Chat Sinhala transliteration function using words, phrases, and structures common in informal Sinhala typing[cite: 1]. 

*   **In-Scope**: Chat-style Singlish transliteration[cite: 1].
*   **Out-of-Scope**: Standard Sinhala transliteration, backend APIs, performance, and security testing[cite: 1].

---

## 3. Singlish Input Types Covered
As per the requirements in **Assignment 1 - Option 1 - For students familiar with Sinhala.pdf**, the following 24 input types are covered with at least two test cases each[cite: 1]:

*   **Question forms**[cite: 1]
*   **Command forms**[cite: 1]
*   **Greetings**[cite: 1]
*   **Requests**[cite: 1]
*   **Responses**[cite: 1]
*   **Repeated Words**[cite: 1]
*   **Punctuation Marks**[cite: 1]
*   **Romanization/Spelling Variants**[cite: 1]
*   **Isolated English Word Insertions**[cite: 1]
*   **Multi-Word English Phrases**[cite: 1]
*   **English Digital Terms**[cite: 1]
*   **Platform/App Names**[cite: 1]
*   **English Abbreviations/Acronyms**[cite: 1]
*   **English Clipped Forms**[cite: 1]
*   **Place Names**[cite: 1]
*   **Person Names**[cite: 1]
*   **Numbers and Numeric Suffixes**[cite: 1]
*   **Currency**[cite: 1]
*   **Time Formats**[cite: 1]
*   **Dates**[cite: 1]
*   **Unit of Measurements**[cite: 1]
*   **Slang and Casual Phrasing**[cite: 1]
*   **Online Identifiers**[cite: 1]
*   **Inputs Containing Emojis**[cite: 1]

---

## 4. Setup & Installation
Follow these steps as outlined in **Automation Steps - Option 1.pdf**[cite: 2]:

### Step 1: Install Prerequisites
*   Install **Python 3.11/3.12**[cite: 2].
*   Install **Google Chrome**[cite: 2].

### Step 2: Environment Configuration
*   Extract the project files to your drive (e.g., `D:\test_automation`)[cite: 2].
*   Open Command Prompt and navigate to the directory:
    ```bash
    cd /d D:\test_automation
    ```

### Step 3: Install Dependencies
*   Run the following commands in the terminal[cite: 2]:
    ```bash
    pip install -U pip
    pip install playwright openpyxl
    playwright install
    ```

---

## 5. Execution Instructions

### Step 1: Prepare the Excel File
*   Open **Assignment 1 - Test cases.xlsx**[cite: 2].
*   Enter your 50 unique test cases under columns: **TC ID**, **Input length type**, **Input**, and **Expected output**[cite: 1, 2].
*   **Leave Actual output and Status blank** (these are filled by the script)[cite: 2].

### Step 2: Run Playwright Script
*   Run the automation using the following command in Command Prompt[cite: 2]:
    ```bash
    python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "[https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator)" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
    ```

### Step 3: Verify Results
*   Reopen the Excel file to confirm the **Actual output** and **Status** columns are populated[cite: 2].
*   Manually fill the **Singlish input types covered** and **Evidence or rationale** columns as per Appendix 2[cite: 1, 2].

---

## 6. Submission Checklist
*   [ ] All files renamed with registration number[cite: 1].
*   [ ] Completed Excel file included[cite: 1].
*   [ ] Full Playwright project repository included[cite: 1].
*   [ ] Git repository is publicly accessible[cite: 1].
*   [ ] Similarity score is below 10%[cite: 1]. and Evidence or rationale.

---
