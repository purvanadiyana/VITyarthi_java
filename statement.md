# Problem Statement: Automated Java Assignment Analyser

## Overview
Evaluating student programming assignments manually is time-consuming, prone to human error, and inconsistent across large cohorts. Course instructors and teaching assistants require an automated tool to quickly parse, analyze, compile, and evaluate Java project submissions from a command-line interface.

## Target Users
- Course Instructors and Faculty
- Teaching Assistants (TAs)
- Automated Evaluation Pipelines

## Scope & Core Functionality
The **Assignment Analyser** provides an end-to-end evaluation pipeline for Java source files:
1. **Static Code Analysis**: Parses `.java` source files to extract code metrics including total Lines of Code (LOC), class counts, and method declarations without external parsing libraries.
2. **Subprocess Compilation & Execution**: Interacts directly with system compilers (`javac` and `java`) via Java's `ProcessBuilder` to verify executability and catch build errors.
3. **Plagiarism & Similarity Detection**: Implements token-based Jaccard similarity algorithms to compute lexical similarity percentages between code files and flag potential plagiarism.
4. **Automated Reporting**: Generates structured summary reports summarizing metric collections and build statuses.
