# Test Automation

This repository contains the test automation script and the 50 negative test cases for the ITPM Transliteration Accuracy Testing assignment (IT3040).

## Setup Instructions

1. Install Python 3.11 or 3.12
2. Open Command Prompt and navigate to this folder.
3. Run the following commands to install dependencies:
```bash
pip install -U pip
pip install playwright openpyxl
python -m playwright install
```

## Running the Automation

To execute the test automation and verify the transliteration outputs, run the following command:

```bash
python test_automation.py --excel "Assignment 1 - Test Cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```
