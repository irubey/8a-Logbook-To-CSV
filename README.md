# Logbook-To-CSV 

📊 **Transform your athlete's 8a.nu logbook into a spreadsheet**

## Introduction
8a-Logbook-To-CSV is a tool designed to help athletes easily convert their 8a.nu logbook data into a CSV file for better data analysis and record-keeping.

## Features
- Extracts and organizes logbook entries
- Converts data to a CSV format
- Easy to use with step-by-step instructions

## Prerequisites
- Node.js installed on your system

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/irubey/8a-Logbook-To-CSV.git
   cd Logbook-To-CSV
2. Install the Dependencies
   ```bash
   npm install

## How To - easy as 1,2,3
### Step 1: Prepare 8a.nu Athlete Logbook
- **Sort By Date**
- **Apply Desired Filters** - e.g., All Time
- **Load All Entries** - Click the button near the bottom of the page
- **Scroll Down** until all entries are loaded
- (Optional) **Expand all tags** (click on (...) icons)
- **Select All Text** (Ctrl + A)
- **Copy Text** (Ctrl + C)

### Step 2: Add Logbook .txt File to Project Folder
- Create a new text file in the project directory named `input.txt`.
- Paste the copied text into `input.txt` (Ctrl + V).

### Step 3: Get Your Athlete Logbook Spreadsheet
- (Optional) Change the input and output file names in `logbookToCSV.mjs`:
   ```javascript
   const input = "input.txt"
   const output = "output.csv"
- Run the 'logbookToCSV.mjs file using Node.js
  ```bash
  node logbookToCSV.mjs
- The CSV file will be saved in project directory
