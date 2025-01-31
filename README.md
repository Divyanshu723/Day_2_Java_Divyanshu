# Homework Solutions

This repository contains solutions for three different Java homework assignments related to data processing, sentiment analysis, and API response parsing.

## Table of Contents
1. [Question 1: Student GPA Calculation](#question-1-student-gpa-calculation)
2. [Question 2: Sentiment Analysis](#question-2-sentiment-analysis)
3. [Question 3: API Response Parsing](#question-3-api-response-parsing)

---

### Question 1: Student GPA Calculation

**Description:**
In this exercise, we calculate the GPA of students based on their grades and retrieve students who fall within a specified GPA range.

**Methods Implemented:**
- `calculateGPA(int[] studentIdList, char[][] studentsGrades)`: Computes the GPA for each student based on their grades.
- `getStudentsByGPA(double lower, double higher, int[] studentIdList, char[][] studentsGrades)`: Retrieves a list of student IDs whose GPA falls within the specified range.

---

### Question 2: Sentiment Analysis

**Description:**
The goal of this exercise is to perform sentiment analysis on restaurant reviews by identifying positive or negative opinions on different features of the restaurant (like service, food, ambiance).

**Methods Implemented:**
- `detectProsAndCons(String review, String[][] featureSet, String[] posOpinionWords, String[] negOpinionWords)`: Detects positive and negative opinions on features in the given review.
- Helper methods for detecting specific opinion patterns, such as `checkForWasPhrasePattern` and `checkForOpinionFirstPattern`.

---

### Question 3: API Response Parsing

**Description:**
In this exercise, we parse an XML response returned by a REST API to extract book-related information like title, author name, publication year, etc.

**Methods Implemented:**
- `parse(String response)`: Parses the XML string and extracts required fields (title, author name, publication year, average rating, ratings count, and image URL).
- Helper methods for parsing XML tags and converting them to appropriate data types (e.g., Integer, Double).

---

### Technologies Used:
- Java 8 or later
- Gradle (for build automation)

---

