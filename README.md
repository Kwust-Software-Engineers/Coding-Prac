# Android Assignment 1 – Android Calculator Application

## Course

Mobile Application Development

## Practical

Android Calculator Application

## Duration

2 Hours

---

# Objective

Develop an Android calculator application using Android Studio that performs the four basic arithmetic operations using Java and XML.

---

# Assignment

Create an Android application named:

```
SAMCALC
```

The application should allow the user to:

- Enter two numbers
- Select one mathematical operation
- Calculate the result
- Display the answer on the screen

---

# Functional Requirements

## 1. User Interface

Design an interface containing:

- Two EditText controls for entering numbers
- One RadioGroup containing four RadioButtons
  - Add
  - Subtract
  - Multiply
  - Divide
- One Button labelled **Calculate**
- One TextView for displaying the result

---

## 2. Input Validation

The application should:

- Ensure both numbers are entered before performing any calculation.
- Display an appropriate message if either field is empty.
- Ensure an operation has been selected.

---

## 3. Processing

When the **Calculate** button is clicked, the application should:

- Read the two numbers.
- Determine the selected operation.
- Perform the calculation.
- Display the result.

---

## 4. Error Handling

The application should:

- Prevent division by zero.
- Display an appropriate error message when division by zero is attempted.

---

# Submission Procedure

## Step 1

Create a new GitHub repository using the following naming format:

```
android-assignment-1-RegistrationNumber
```

Example:

```
android-assignment-1-BIT221-001-2026
```

---

## Step 2

Create the Android project in Android Studio.

Project Name:

```
SAMCALC
```

Package Name:

```
com.example.samcalc
```

---

## Step 3

Develop the application according to the requirements provided above.

---

## Step 4

Commit your work regularly while developing.

Example commit messages:

```
Initial project created

Designed calculator interface

Implemented addition

Implemented subtraction

Implemented multiplication

Implemented division

Added input validation

Handled divide by zero

Final testing completed
```

Do **not** wait until the end and make only one commit.

---

## Step 5

Push the completed project to your GitHub repository.

Ensure the repository contains:

```
README.md

Complete Android Studio Project

Java Source Code

XML Layout Files

Gradle Files
```

---

## Step 6

Take screenshots of your application.

Include screenshots showing:

- Calculator interface
- Addition
- Subtraction
- Multiplication
- Division
- Divide-by-zero error message

Create a folder named:

```
Screenshots
```

and upload all screenshots.

---

## Step 7

Generate the APK file.

Create a folder named:

```
APK
```

Place the generated APK inside that folder.

---

## Step 8

Submit **only the GitHub repository link**.

Example:

```
https://github.com/YourUsername/android-assignment-1-BIT221-001-2026
```

Do **not** upload ZIP files unless specifically instructed.

---

# Repository Structure

Your repository should look similar to the following:

```
android-assignment-1-BIT221-001-2026

│── app
│── gradle
│── APK
│     └── SAMCALC2.apk
│
│── Screenshots
│     ├── home.png
│     ├── addition.png
│     ├── subtraction.png
│     ├── multiplication.png
│     ├── division.png
│     └── divide_by_zero.png
│
│── README.md
│── build.gradle
│── settings.gradle
```
---

# Academic Integrity

Students must submit their own original work.

Sharing source code or copying another student's work is considered academic misconduct and may result in disciplinary action.

---

# Submission Deadline

To be communicated by the lecturer.
