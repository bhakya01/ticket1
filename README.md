# ticket1
# 🎫 Customer Support Ticket Analyzer

## 📌 Project Overview

The **Customer Support Ticket Analyzer** is a Python-based data analysis project designed to store, clean, analyze, and extract useful insights from customer support tickets.

Customer support teams receive many tickets every day. Analyzing these tickets helps identify:

* Common customer issues
* Priority distribution
* Frequently used keywords
* Customer support quality
* Areas that may need improvement

This project demonstrates fundamental Python concepts such as **lists, dictionaries, loops, functions, string manipulation, sets, conditional statements, and data analysis**.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Store customer support ticket information.
2. Display the initial ticket data in a readable format.
3. Allow users to add new customer tickets.
4. Automatically generate ticket numbers.
5. Validate ticket priority.
6. Clean issue descriptions.
7. Search ticket descriptions using keywords.
8. Analyze ticket priorities.
9. Find the ticket with the longest issue description.
10. Extract and display unique words used in the tickets.

---

## 🛠️ Technologies Used

* **Python**
* **Google Colab / Jupyter Notebook**
* Python Lists
* Python Dictionaries
* Functions
* Loops
* Conditional Statements
* String Methods
* Sets

---

## 📂 Project Structure

```text
Customer-Support-Ticket-Analyzer/
│
├── Customer_Support_Ticket_Analyzer.ipynb
├── README.md
└── Customer_Support_Ticket_Summary.pdf
```

---

## 📊 Dataset

The project starts with **10 preloaded customer support tickets**.
Each ticket contains:
* `Ticket_No`
* `Customer_Name`
* `Issue_Description`
* `Priority`
  
## ➕ Adding New Tickets

The program asks the user:

```text
How many new tickets do you want to add?
```

For every new ticket, the user enters:

* Customer Name
* Issue Description
* Priority

Ticket numbers are automatically generated starting from **11**.

Only the following priority values are accepted:

```text
High
Medium
Low

## 🧹 Text Cleaning
The issue descriptions are cleaned using Python string operations.

The cleaning process includes:

* Removing punctuation such as `. , ! ? -`
* Removing extra spaces
* Removing leading and trailing spaces
* Converting text to lowercase
* Replacing shorthand/slang such as `ok` with `okay`

## 🔎 Keyword Analysis

A function named:

```python
count_tickets_with_word(word)
```

is created to count the number of tickets containing a particular word.

The following keywords are analyzed:

* `poor`
* `good`
* `slow`
* `excellent`

## 📈 Priority Analysis

The final program calculates the number of:

* High-priority tickets
* Medium-priority tickets
* Low-priority tickets

This helps understand how tickets are distributed according to urgency.

---

## 📝 Longest Issue Description

The program identifies the ticket containing the **highest number of words** in its cleaned issue description.

The output displays:

* Ticket Number
* Customer Name
* Cleaned Issue Description
* Word Count

## 🔤 Unique Word Analysis

All words from the cleaned issue descriptions are collected into a Python `set`.

The program displays:

1. Total number of unique words
2. Sorted list of unique words

## 📌 Key Python Concepts Demonstrated

This project demonstrates practical use of:

```text
Dictionary
List
Set
For Loop
While Loop
If / Elif / Else
Functions
String Methods
Input Validation
Word Counting
Sorting
Set Operations
Data Cleaning

## 📋 Assignment Requirements Covered


```text
Customer Support Ticket Analyzer/
│
├── Customer_Support_Ticket_Analyzer.ipynb
├── Customer_Support_Ticket_Summary.pdf
└── README.md


## 👩‍💻 Author

**Bhakya M**

Data Analytics Learner

## 📜 Conclusion

The Customer Support Ticket Analyzer demonstrates how Python can be used to organize and analyze customer support data.

Through data cleaning, keyword analysis, priority analysis, word counting, and unique-word extraction, the project converts raw ticket information into meaningful insights that can help support teams understand customer issues and improve their service processes.
