# 🚀 LeetCode-Problems Repository

Welcome to **LeetCode-Problems**, a structured repository dedicated to solving **LeetCode** challenges in Python! 🧠💡

This repo is designed to enhance your problem-solving skills through **daily coding challenges**, complete with **clear explanations** and **well-structured solutions**. 🎯

---

## 📌 Repository Overview

Each `.ipynb` file corresponds to a specific day's challenges, focusing on different problem types. The problems include **arrays, strings, sorting, searching, dynamic programming, and more!**

---

## 🔢 Daily Challenges Breakdown

| Day | Problems Solved | Difficulty Level |
|----|---------------|----------------|
| **Day 1** | Palindrome Numbers, Two Sum Problem, Roman to Integer | 🟢 Easy |
| **Day 2** | 3Sum | 🔵 Medium |
| **Day 3** | Merge Strings Alternately, GCD of Strings, Kids With the Greatest Number of Candies | 🟢 Easy |
| **Day 4** | Flower Planting, Move Zeroes, Reverse Words in a String, Product of Array Elements | 🟡 Medium |
| **Day 6** | Single Number | 🟢 Easy |
| **Day 7** | Can Place Flowers | 🟢 Easy |
| **Day 8** | Reverse Vowels of a String | 🟡 Medium |
| **Day 9** | Product of Array Except Self | 🔵 Medium |
| **Day 10** | Find the Highest Altitude | 🟢 Easy |

---

## ✨ Example Solutions

### ✅ Palindrome Numbers *(Easy)*  
**Check if an integer is a palindrome.**  

```python
def isPalindrome(x):
    new = str(x)
    return new == new[::-1]

print(isPalindrome(-121))  # Output: False
```

### ✅ Two Sum Problem  *(Easy)*  
**Find two numbers in an array that add up to a given target.**  

```python
def twoSum(nums, target):
    for i in range(len(nums)):
        for j in range(i + 1, len(nums)):
            if nums[i] + nums[j] == target:
                return [i, j]

nums = [1, 2, 3]
target = 3
print(twoSum(nums, target))  # Output: [0, 1]
```
### Reverse Words in a String *(Medium)*
**Reverse the order of words in a sentence.**  

```python
def reverse_words(string):
    return ' '.join(string.strip().split()[::-1])

s = "a good   example"
print(reverse_words(s))  # Output: "example good a"
```

## 🎯 Difficulty Levels
- 🔹 **🟢 Easy** – Beginner-friendly problems that cover fundamental concepts.  
- 🔹 **🟡 Medium** – Intermediate problems that require deeper thought and optimization.  
- 🔹 **🔵 Hard** – Advanced problems that demand strong problem-solving and algorithmic skills.  

---

## 🛠️ How to Use

1️⃣ **Clone the repository:**
```sh
git clone https://github.com/your-username/LeetCode-Problems.git
```

2️⃣ **Navigate to the project folder:**
```sh
cd LeetCode-Problems
```
3️⃣ **Open any** `.ipynb` **file in Jupyter Notebook** or use **Python** to run `.py` files.

---

## 🚀 Future Enhancements

- 📚 **More explanations** for problems.  
- ⚡ **Optimized solutions** for better efficiency.  
- 🔥 **Additional LeetCode problems** added regularly.  
- 🎯 **Categorization by topics like DP, Graphs, Sorting, etc.**  

---

## 🤝 Contribute

Want to improve the repository? **Submit a pull request** or **fork the repo** and add new solutions! Contributions are welcome. 🎉

---

## 📜 License

This project is **open-source** and free to use. Happy coding! 💻🚀
