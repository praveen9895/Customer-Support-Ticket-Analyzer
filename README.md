# Customer Support Ticket Analyzer

## 📌 Project Title

**Customer Support Ticket Analyzer**
*Data Analytics – Python (Module End Assignment)*

---

## 📖 Project Overview

The **Customer Support Ticket Analyzer** is a Python-based data analytics project designed to analyze and extract insights from customer support ticket data. The project focuses on organizing ticket information, cleaning and processing customer feedback text, analyzing ticket priorities, and identifying common issue patterns.

This system works with both preloaded and user-added tickets, making it flexible and scalable. By leveraging Python data structures, text-processing techniques, and analytical logic, raw customer support data is transformed into meaningful insights that help improve service quality and operational efficiency.

---

## 🎯 Objectives

* Organize customer support ticket data efficiently
* Clean and standardize issue description text
* Analyze ticket priorities and workload distribution
* Identify common keywords and issue patterns
* Generate summary statistics for decision-making

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Core Concepts:**

  * Lists and Dictionaries
  * Functions
  * Loops and Conditional Statements
  * String Manipulation
  * Sets and Sorting

---

## 🗂️ Project Features

### 1. Data Loading & Setup

* Ticket data is stored using a **dictionary of lists** structure.
* Each list represents a ticket attribute:

  * Ticket Number
  * Customer Name
  * Issue Description
  * Priority Level
* Supports **dynamic ticket addition** with auto-incremented ticket numbers.
* User inputs are validated to maintain data consistency.

---

### 2. Data Cleaning & Text Processing

* Issue descriptions are cleaned using:

  * Lowercase conversion
  * Removal of punctuation
  * Extra space normalization
  * Slang word replacement (e.g., `ok` → `okay`)
* Ensures consistency and improves accuracy in keyword analysis.

---

### 3. Functions, Loops & Logic

* User-defined functions for:

  * Case-insensitive keyword search
  * Counting matching tickets
* Loops used to iterate through tickets for:

  * Cleaning
  * Analysis
  * Summary generation
* Conditional statements ensure:

  * Valid priority inputs
  * Accurate filtering of ticket data

---

### 4. Summary Statistics

* Calculates the number of tickets by priority:

  * High
  * Medium
  * Low
* Identifies the ticket with the **longest issue description** using word count analysis.
* Helps highlight complex issues requiring special attention.

---

### 5. Sorting & Structuring Output

* Extracts **unique words** from all issue descriptions using a set.
* Sorts vocabulary alphabetically for structured presentation.
* Maintains alignment across ticket attributes for clarity and traceability.

---

### 6. Output Presentation

* Displays results in a clean and readable format.
* Outputs include:

  * Ticket records
  * Summary statistics
  * Keyword analysis
* Designed for both technical and non-technical users.

---

## 📊 Insights & Findings

* Common customer issues include:

  * Slow service
  * Poor handling
  * Feedback related to good or excellent support
* High-priority tickets indicate urgent matters requiring immediate action.
* Keyword analysis helps identify trends in customer sentiment.

---

## ✅ Conclusion

This project demonstrates the effective use of **Python for data cleaning, analysis, and reporting**. The insights generated can help organizations improve customer support quality, optimize response strategies, and enhance overall customer satisfaction.
