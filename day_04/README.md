### 🧩 **Day 4: Multiplication Table Generator — Loops and Ranges**

**📝 Problem Description:**  
Ask the user for a number and print its multiplication table **up to 20**.  
Then, display the **sum of all results** in the table.  
Finally, ask the user if they want another table (Y/N) and continue until they say “N”.

**💡 Example:**
```

Input:
5

Output:
5 x 1 = 5
5 x 2 = 10
...
5 x 20 = 100
Sum of all results = 1050

```

**⚙️ Constraints:**
- Number must be positive and less than 100.

**🧠 Step-by-Step Explanation:**
1. Use a `for` loop with `range()`.  
2. Multiply and print each line.  
3. Maintain a running total using a variable.  
4. Use a `while` loop for repeat functionality.

**💭 Hints:**
- Practice both `for` and `while` versions.  
- Try saving results in a list for later use.

**🎯 Concept Learned:**  
Loops, Range, Repetition, Accumulation

---


while True:
   user_number = int(input("Enter Your Number: "))
   
   result_list = []
   
   for num in range(1, 21):
      print(f"{user_number} x {num} = {user_number * num}")
      result_list.append(num * user_number)
   

   sum_of_results = 0
   
   for i in result_list:
      sum_of_results += i
   
   print(f"Sum of Result: {sum_of_results}")
   
   ask_user = input("Do you want another table: (Y/N)\n").lower()
   
   if ask_user != "y" or ask_user != "yes":
      break