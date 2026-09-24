# ENSE 375 – Software Testing and Validation
# Academic Grade Analyzer

**Group 3 Members:**  
* Zifran Chowdhury (Student ID: 200502201)  
* Gabriel Sampaga (Student ID: 200426525)  
* Mohammad Suhayb Hoolash (Student ID: 200510097)  

---

## Table of Contents
* [1 Introduction](#1-introduction)
* [2 Design Problem](#2-design-problem)
  * [2.1 Problem Definition](#21-problem-definition)
  * [2.2 Design Requirements](#22-design-requirements)
    * [2.2.1 Functions](#221-functions)
    * [2.2.2 Objectives](#222-objectives)
    * [2.2.3 Constraints](#223-constraints)
* [3 Solution](#3-solution)
  * [3.1 Solution 1](#31-solution-1)
  * [3.2 Solution 2](#32-solution-2)
  * [3.3 Final Solution](#33-final-solution)
    * [3.3.1 Components](#331-components)
    * [3.3.2 Environmental, Societal, Safety, and Economic Considerations](#332-environmental-societal-safety-and-economic-considerations)
    * [3.3.3 Test Cases and Results](#333-test-cases-and-results)
    * [3.3.4 Limitations](#334-limitations)
* [4 Team Work](#4-team-work)
  * [4.1 Meeting 1](#41-meeting-1)
  * [4.2 Meeting 2](#42-meeting-2)
  * [4.3 Meeting 3](#43-meeting-3)
  * [4.4 Meeting 4](#44-meeting-4)
* [5 Project Management](#5-project-management)
* [6 Conclusion and Future Work](#6-conclusion-and-future-work)
* [7 References](#7-references)
* [8 Appendix](#8-appendix)

---

## 1 Introduction
Calculating semester and cumulative grade point averages (GPAs) by hand can be confusing and lead to calculation errors for university students. Because courses often have different credit weights, manual calculations can give students an inaccurate picture of their overall academic standing. 

The Academic Grade Analyzer is an application designed to calculate accurate term and cumulative GPAs based on course grades and credit weights. It also evaluates academic standing flags such as Good Standing or Academic Probation. 

This report documents the design process for the application.

---

## 2 Design Problem

### 2.1 Problem Definition
University students frequently miscalculate their GPAs when managing multiple courses with varying credit weights. Relying on manual arithmetic or basic spreadsheets often introduces errors, preventing students from understanding their true standing until official grades are posted. Without a simple, reliable tool to evaluate marks, students risk unexpected academic warnings or probation.

The goal of this project is to build an Academic Grade Analyzer that accepts course marks and credit values, accurately computes weighted term and cumulative GPAs, and determines academic standing according to university grading policies. The application must be deterministic, easy to run, and structured to allow thorough software testing.

### 2.2 Design Requirements
The Academic Grade Analyzer shall be designed to provide students with an accurate and reliable method of analyzing their academic performance.

#### 2.2.1 Functions
The Academic Grade Analyzer shall provide the functionality required to accept, validate, and analyze student academic information. The following functional and non-functional requirements define the expected behaviour and characteristics of the system.

**Functional Requirements:**
- The system shall allow users to enter the course name, course mark, and corresponding value for each course.
- The system shall validate that entered marks and credit values are within ranges before performing calculations.
- The system shall calculate the weighted term GPA based on the marks and credit values provided by the user.
- The system shall calculate cumulative GPA using previously completed courses and their corresponding credit values.
- The system shall determine the user's academic standing based on the applicable university grading policies.
- The system shall provide clear results that allow users to understand how their GPA and academic standing were determined.
- The system shall produce the same results when provided with the same valid input data.

**Non-Functional Requirements:**
- The system shall perform deterministic calculations without relying on external services during normal operations.
- The system shall provide clear error messages when invalid or incomplete information is entered.
- The system shall be simple enough for a university student to use without specialized technical knowledge.
- The system shall be structured in a manner that allows its calculations, input validation, and academic-standing logic to be independently tested.
- The system shall not require users to provide unnecessary personal or sensitive information to perform GPA calculations.

#### 2.2.2 Objectives
The primary objective of the Academic Grade Analyzer is to provide university students with a simple and reliable tool for analyzing their academic performance. The system is intended to reduce errors associated with manual GPA calculations and help students better understand their academic standing.

**The objectives of the system are to:**
- Provide students with an accurate method of calculating weighted term and cumulative GPA.
- Account for differences in course credit values when analyzing academic performance.
- Help students understand how their GPA and academic standing are determined.
- Reduce the likelihood of calculation errors associated with manual GPA calculations.
- Provide a straightforward interface that allows students to analyze their academic performance without specialized technical knowledge.
- Present calculated results in a clear and understandable manner.

#### 2.2.3 Constraints
**The design of the Academic Grade Analyzer is subject to the following constraints:**
#### Economic Factors
- The application shall be developed using freely available development tools and shall not require paid external services for its core functionality.

#### Security and Access
- The application shall not require access to official university records or student information systems.
- The application shall minimize the collection of personal or sensitive information and only require information necessary to perform academic calculations.

#### Reliability
- The application shall produce consistent and deterministic GPA and academic-standing results when provided with the same valid input data.
- The application shall validate course marks and credit values before performing calculations to reduce the possibility of incorrect results.

#### Ethics
- The application shall apply the predefined grading scale and academic-standing rules consistently to all users.
- The application shall clearly identify calculated GPA and academic-standing results as estimates and shall not present them as official university records.

#### Societal Impacts
- The application shall serve as an analytical aid to help students better understand their academic performance.
- The application shall not be presented as a replacement for official university academic advising or academic records.

#### Technical Constraints
- GPA calculations shall account for different course credit values rather than treating all courses as equally weighted.
- The application shall perform its core GPA and academic-standing calculations without relying on external services during normal operation.
---

*(To be completed in future deliverables)*

## 3 Solution

### 3.1 Solution 1
### 3.2 Solution 2
### 3.3 Final Solution
#### 3.3.1 Components
#### 3.3.2 Environmental, Societal, Safety, and Economic Considerations
#### 3.3.3 Test Cases and Results
#### 3.3.4 Limitations

---

## 4 Team Work

### 4.1 Meeting 1
**Time:**  
**Agenda:** 

| Team Member | Previous Task | Completion State | Next Task |
| :--- | :--- | :--- | :--- | 
| Member 1 Name | N/A | N/A | N/A |
| Member 2 Name | N/A | N/A | N/A |
| Member 3 Name | N/A | N/A | N/A |

### 4.2 Meeting 2

### 4.3 Meeting 3

### 4.4 Meeting 4

---

## 5 Project Management

---

## 6 Conclusion and Future Work

## 7 References

## 8 Appendix
