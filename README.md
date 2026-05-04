# IT23401044_ITPM_Assignment_01
# ITPM Assignment 1 – Transliteration Accuracy Testing

## Student Details

Name: Dulari
Registration Number: IT23401044

## Project Description

This project evaluates the accuracy of a Sinhala chat transliteration system using Singlish inputs. The system is tested using automated test cases executed through Playwright.

## Technologies Used

* Python 3.11
* Playwright
* OpenPyXL
* Google Chrome

## Setup Instructions

### 1. Install Dependencies

pip install -U pip
pip install playwright openpyxl
playwright install

### 2. Run the Test Script

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"

### 3. Output

The script automatically updates:

* Actual Output
* Status (PASS / FAIL)

## Notes

* This project focuses only on chat-style transliteration.
* Performance and backend testing are not included.
