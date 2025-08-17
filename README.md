# 🧠 Weekly Programming Problems – By Vansh Verma  

![GitHub last commit](https://img.shields.io/github/last-commit/VanshVerma4436/Problems_Of_The_Week_By_VanshVerma?color=blue&style=for-the-badge)  
![GitHub repo size](https://img.shields.io/github/repo-size/VanshVerma4436/Problems_Of_The_Week_By_VanshVerma?color=green&style=for-the-badge)  
![GitHub stars](https://img.shields.io/github/stars/VanshVerma4436/Problems_Of_The_Week_By_VanshVerma?style=for-the-badge)  
![GitHub forks](https://img.shields.io/github/forks/VanshVerma4436/Problems_Of_The_Week_By_VanshVerma?style=for-the-badge)  

A curated collection of **weekly programming challenges** inspired by real interview problems from **Facebook, Microsoft, Amazon**, and other top tech companies.  
Each problem includes **clean & efficient code, detailed explanations, and complexity analysis** 🚀.  

---

## 📋 Table of Contents
- [🎯 Overview](#-overview)  
- [📚 Problems Solved](#-problems-solved)  
- [🚀 Getting Started](#-getting-started)  
- [📁 Problem Structure](#-problem-structure)  
- [🛠 Technologies Used](#-technologies-used)  
- [📈 Complexity Analysis](#-complexity-analysis)  
- [🎯 Interview Tips](#-interview-tips)  
- [🤝 Contributing](#-contributing)  
- [📝 Future Plans](#-future-plans)  
- [🌟 Acknowledgments](#-acknowledgments)  

---

## 🎯 Overview
This repository contains **weekly solutions** to programming problems commonly asked in technical interviews.  

Focus areas:  
✅ Clean & readable code  
✅ Optimal **time and space complexity**  
✅ Multiple test cases  
✅ Company context & interview insights  

---

## 📚 Problems Solved  

### Week 1  

| Problem | Company | Difficulty | Topic |
|---------|---------|------------|-------|
| Equal Sum Partition | Facebook  | Medium | Dynamic Programming |
| Word Search in 2D Matrix | Microsoft | Easy | Array/Matrix |
| Greatest Common Divisor (GCD) | Amazon | Easy | Mathematics |

---

### 🔹 Equal Sum Partition (Facebook)  
**Problem:** Determine if a multiset can be partitioned into two subsets with equal sums.  
**Approach:** Dynamic Programming (Subset Sum).  
**Time Complexity:** `O(n × sum)`  
**Key Insight:** If total sum is odd → partition impossible.  

---

### 🔹 Word Search in 2D Matrix (Microsoft)  
**Problem:** Check if a word exists horizontally or vertically in a 2D matrix.  
**Approach:** Linear scan of rows & columns.  
**Time Complexity:** `O(M × N)`  
**Key Insight:** Simple string matching, no backtracking needed.  

---

### 🔹 Greatest Common Divisor (Amazon)  
**Problem:** Find GCD of N numbers.  
**Approach:** Euclidean Algorithm (iterative).  
**Time Complexity:** `O(n log M)`  
**Key Insight:** GCD is associative → `gcd(a,b,c) = gcd(gcd(a,b),c)`.  

---

## 🚀 Getting Started  

### Prerequisites  
- Python 3.7+  
- Jupyter Notebook (optional for interactive learning)  

### Installation  
# Clone the repository
git clone https://github.com/VanshVerma4436/Problems_Of_The_Week_By_VanshVerma.git  

# Navigate to project
cd Problems_Of_The_Week_By_VanshVerma  

# Install Jupyter (optional)
pip install jupyter

📁 Problem Structure

Each problem follows a consistent structure:
 Problem Title: [Name] (Asked by [Company])
├── Problem Statement
├── Company Context
├── Examples with Explanations
├── Input/Output Format
├── Constraints
├── Hints
└── Solution with Comments


🛠 Technologies Used

Python 3.x (primary language)

Jupyter Notebook (interactive development)

Built-in Libraries: math, itertools, etc.

📈 Complexity Analysis
Problem	Time Complexity	Space Complexity	Algorithm Type
Equal Sum Partition	O(n × sum)	O(sum)	Dynamic Programming
Word Search 2D	O(M × N)	O(1)	Linear Search
GCD of N Numbers	O(n log M)	O(1)	Number Theory
🎯 Interview Tips

💡 Equal Sum Partition: Always check if sum is odd → quick elimination.
💡 Word Search: Handle row-wise & column-wise systematically.
💡 GCD Problems: Euclidean algorithm is the most efficient.

🤝 Contributing

Contributions are welcome! To add problems or improve solutions:

Fork the repository

Create a feature branch → git checkout -b feature/NewProblem

Commit changes → git commit -m "Add NewProblem solution"

Push → git push origin feature/NewProblem

Open a Pull Request 🚀

📝 Future Plans

Add more weekly problems

Include multi-language solutions (Java, C++)

Add video explanations

Create difficulty-based categories

Add performance benchmarks

🌟 Acknowledgments

Problems inspired by real technical interviews at Facebook, Microsoft, Amazon

Thanks to the open-source community for contributions 💻

Special thanks to all learners practicing here 🚀

✨ If you find this repository helpful, don’t forget to give it a ⭐ and share it with others!
