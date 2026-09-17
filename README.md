# Assignment Analyser

A lightweight, CLI-based Java assignment evaluation system that performs static code metric collection, automated compilation checks, and token-based similarity analysis.

## Features
- **Static Analysis**: Calculates Lines of Code (LOC), class count, and method declarations.
- **Automated Compilation**: Tests source files using native system processes.
- **Plagiarism Detection**: Uses Jaccard index token analysis to measure source overlap.
- **CLI-First Architecture**: Runs fully in a terminal environment without GUI dependencies.
- **Report Generation**: Outputs evaluation summaries directly to a text file.

## Prerequisites
- **Java Development Kit (JDK)**: OpenJDK 17 or higher
- **System Path**: Ensure `javac` and `java` commands are accessible in your system terminal environment.

## Project Structure
