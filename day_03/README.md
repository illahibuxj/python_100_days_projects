
### 🧩 **Day 3: Student Grading System — Nested Conditions**

**📝 Problem Description:**  
Create a simple grading system.  
The program should take a student’s marks (0–100) and print their grade:
- 90–100 → A  
- 80–89 → B  
- 70–79 → C  
- 60–69 → D  
- Below 60 → F  

Also, if the marks are **above 90**, print `"Excellent!"`, if below 50, print `"Needs Improvement!"` and between 50 to 90 print `keep it up`.

**💡 Example:**
```

Input:
Marks: 85

Output:
Grade: B
Keep it up!

```

**⚙️ Constraints:**
- Marks must be between 0 and 100.

**🧠 Step-by-Step Explanation:**
1. Take marks as integer input.  
2. Use nested `if-elif-else` structure.  
3. Include boundary conditions carefully (e.g., 89 vs 90).  
4. Add motivational message based on performance.

**💭 Hints:**
- Handle invalid inputs (negative or >100).  
- Use logical grouping (`and` operators).

**🎯 Concept Learned:**  
Nested Conditions, Ranges, Validation, Decision Making

---



user_marks = int(input("Enter Your Marks: "))

if not (user_marks >= 0 and user_marks <= 100):
   print("\n❌ Please enter marks between 0 and 100\n")

else:
   if user_marks >= 90 and user_marks <=100:
      if user_marks > 90:
         print("\nGrade: A")
         print("Excellent!\n")
      else:
         print("\nGrade: A")
         print("Keep it Up!\n")
   elif user_marks >=80 and user_marks < 90:
      print("\nGrade: B")
      print("Keep it Up!\n")
      
   elif user_marks >=70 and user_marks < 80:
      print("\nGrade: C")
      print("Keep it Up!\n")
      
   elif user_marks >=60 and user_marks < 70:
      print("\nGrade: D")
      print("Keep it Up!\n")
      
   else:
      if user_marks < 50:
         print("\nGrade: F")
         print("Needs Improvement!\n")
      else:
         print("\nGrade: F")
         print("Keep it Up!\n")