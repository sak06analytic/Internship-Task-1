# Internship-Task-1
# Excel Data Cleaning 

This repository contains ready-to-use Excel Data & formulas for cleaning messy data.

# Features:
- Remove ₹, commas from price columns
- Convert text dates like "August 14, 2020" to "DD-MM-YYYY"
- Ready formulas to copy-paste
- Clean Excel files included

# Files Included:
| File Name                | Description                         

 C:\Users\saksh\Downloads\netflix_titles.csv\netflix_titles.csv -> Original dataset                                       
 C:\Users\saksh\Downloads\TASK-1.xlsx -> Ready-to-use date clean dataset   

# Formulas :
 Dateadd =TEXT(DATEVALUE(A2),"DD-MM-YYYY")
 Duration = Find & Replace
 Remove Special Characters (Except Alphabets & Numbers) = =TEXTJOIN("",TRUE,IF(ISNUMBER(FIND(MID(A2,ROW(INDIRECT("1:"&LEN(A2))),1),"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ ")),MID(A2,ROW(INDIRECT("1:"&LEN(A2))),1),""))

# Usage:
Download → Open in Excel → Auto-clean your data easily!

# Created By:
Sakshi Khedekar (Data Analyst)
