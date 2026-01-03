# Internet Programming Project

This repository contains the **Internet Programming** project developed by me and two colleagues. The application, named **"Play Esercizi"**, is a desktop application built with **JavaFX** designed to help users practice coding through various interactive exercises.

## Project Description

The goal of the project is to provide a gamified platform for learning programming concepts. Users can register, log in, and track their progress across different categories of coding challenges.

The main features of the application include:

1.  **User Authentication**: Secure login and registration system for new users.
2.  **Interactive Dashboard**: A main hub displaying exercise categories, progress bars for completion status, and navigation buttons.
3.  **Exercise Categories**:
    * **Find the Error**: Identify bugs in code snippets.
    * **Order the Code**: Rearrange lines of code to form a working program.
    * **Complete the Code**: Fill in missing parts of the syntax.
4.  **Exercise Interface**: A dedicated view for solving problems featuring a timer, navigation between questions (previous/next), and submission capability.
5.  **Leaderboards**: Two distinct ranking systems based on performance:
    * Number of completed exercise sets.
    * Time spent answering questions.

## Repository Structure

* `LabProgrammazione/`: The main root folder containing the JavaFX source code and Maven configuration.
* `Relazione Progetto Programmazione Internet A.A. 23-24.pdf`: Detailed project report (in Italian) including UI screenshots and architectural details.
* `README.md`: This file, with description and instructions.

## Requirements

The project relies on the following technologies:

* **Java 18** (or newer).
* **Maven** (installed and configured).
* **JavaFX**.

## How to Run

To launch the application, follow these steps:

1.  Open your terminal.
2.  Navigate to the main project folder:
    ```bash
    cd LabProgrammazione
    ```
3.  Execute the Maven command to clean and run the JavaFX application:
    ```bash
    mvn clean javafx:run
    ```

## Contributors - Group MPR

* Riccardo Ventura
* Matteo Biacchessi
* Pietro Rizzo
