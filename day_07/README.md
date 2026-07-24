# 🧩 Day 7: Student Record Manager — Dictionaries & Data Management

## 📝 Problem Description

Create a Python program that stores and analyzes a student's academic record using a **dictionary**.

Ask the user to enter:

* Student name
* English marks
* Mathematics marks
* Science marks

Store the student's name and subject marks in a dictionary.

Then, the program should:

1. Display the complete student record.
2. Calculate and display the **total marks**.
3. Calculate and display the **average marks**.
4. Display the subject with the **highest marks**.
5. Display the subject with the **lowest marks**.
6. Determine whether the student has **Passed or Failed**.

A student passes only if they score **40 or more in every subject**.

## 💡 Example

**Input:**

```text
Student Name: Ali
English Marks: 78
Mathematics Marks: 92
Science Marks: 65
```

**Output:**

```text
Student Record:
Name: Ali
English: 78
Mathematics: 92
Science: 65

Total Marks: 235
Average Marks: 78.33
Highest Marks: Mathematics (92)
Lowest Marks: Science (65)
Result: PASS
```

## ⚙️ Constraints / Rules

* Marks must be between **0 and 100**.
* All marks must be valid integers.
* The student passes only when marks in **all three subjects are 40 or above**.
* Store the student's information using a **dictionary**.
* Use loops where appropriate instead of repeating the same logic unnecessarily.

## 🧠 Suggested Steps

1. Take the student's name as input.
2. Create a dictionary to store subjects and their marks.
3. Take marks for each subject and add them to the dictionary.
4. Use dictionary methods and loops to process the marks.
5. Calculate the total and average.
6. Find the highest and lowest scoring subjects.
7. Check each subject to determine the final Pass/Fail result.
8. Display the results in a clean, readable format.

## 💭 Hints

* Explore dictionary methods such as `.keys()`, `.values()`, and `.items()`.
* `sum()` and `len()` can help calculate the average.
* Think about how `max()` and `min()` can work with dictionary data.
* A loop can be used to check whether the student passed every subject.

### ⭐ Bonus Challenge

Display all subjects where the student scored **80 or above**.

Example:

```text
High-Scoring Subjects:
English: 85
Mathematics: 92
```

If there are no subjects with 80 or more marks, display:

```text
No subject scored 80 or above.
```

## 🎯 Concepts Learned

**Dictionaries, Key-Value Pairs, Dictionary Methods, Loops, Conditionals, Aggregation, Data Processing**

## 📺 **Watch the Solution of this Exercise on YouTube**

IB Coding School: [**Python 100 Days Projects**](https://youtube.com/playlist?list=PL-XnT4KCow_9ozafUVLBIAQ0H7FOeVef6&si=P2Bk2eSdP_eKWeCf) 

🎯 **The End**
