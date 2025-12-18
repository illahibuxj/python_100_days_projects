"""
### 🧩 **Day 5: String Analyzer — Counting Vowels, Consonants, and Digits**

**📝 Problem Description:**  
Write a Python program that analyzes a given sentence and counts:
- Number of vowels  
- Number of consonants  
- Number of digits  
- Number of spaces  

Also, display the **total length** of the sentence (excluding spaces).

**💡 Example:**
```

Input:
"Python 3 is amazing"

Output:
Vowels: 5
Consonants: 8
Digits: 1
Spaces: 2
Length (excluding spaces): 13

```

**⚙️ Constraints:**
- Input can contain letters, digits, and spaces.

**🧠 Step-by-Step Explanation:**
1. Initialize counters for each category.  
2. Loop through each character.  
3. Use `.isalpha()`, `.isdigit()`, and `in` for checks.  
4. Increment counters accordingly.

**💭 Hints:**
- Use `.lower()` for uniform checking.  
- Bonus: ignore punctuation using `.isalnum()`.

**🎯 Concept Learned:**  
Strings, Character Classification, Loops, Counting Logic

---
"""