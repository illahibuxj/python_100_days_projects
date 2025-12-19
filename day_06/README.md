"""
### 🧩 **Day 6: List Statistics Calculator — Lists and Iteration**

**📝 Problem Description:**  
Ask the user to input a list of numbers separated by commas.  
Then display:
- The list in sorted order.  
- The total sum.  
- The average.  
- The minimum and maximum numbers.  
- How many numbers are even and odd.

**💡 Example:**
```

Input:
5, 8, 2, 9, 1

Output:
Sorted List: [1, 2, 5, 8, 9]
Sum: 25
Average: 5.0
Min: 1
Max: 9
Even Count: 2
Odd Count: 3

```

**⚙️ Constraints/Rules:**
- List must contain 2–20 numbers.

**🧠 Step-by-Step Explanation:**
1. Use `.split(',')` to create list.  
2. Convert each element to integer using `map()`.  
3. Calculate stats using `len()`, `sum()`, `min()`, `max()`.  
4. Loop to count evens and odds.

**💭 Hints:**
- Explore built-ins like `sorted()`.  

**🎯 Concept Learned:**  
Lists, Type Conversion, Aggregation Functions, List Iteration

---


## 📺 **Watch the Solution of this Exercise on YouTube**

IB Coding School: [**Python 100 Days Projects**](https://youtube.com/playlist?list=PL-XnT4KCow_9ozafUVLBIAQ0H7FOeVef6&si=P2Bk2eSdP_eKWeCf) 