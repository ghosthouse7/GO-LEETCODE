# 🚀 GO-LEETCODE

![Go Version](https://img.shields.io/github/go-mod/go-version/ghosthouse7/GO-LEETCODE?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)
![Repo Size](https://img.shields.io/github/repo-size/ghosthouse7/GO-LEETCODE?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/ghosthouse7/GO-LEETCODE?style=flat-square)

> "Talk is cheap. Show me the code." - Linus Torvalds

## 📖 About This Repository
This repository serves as a centralized collection of my **LeetCode solutions** and **Data Structures & Algorithms (DSA)** implementations, written exclusively in **Golang**.

The focus of this project is not just to solve problems, but to write **production-grade, idiomatic Go code**.

### 🌟 Key Features
- **Idiomatic Go:** Utilizes extensive use of Pointers, Interfaces, and Structs.
- **Concurrency Patterns:** Solutions involving Goroutines, Channels, and Mutexes where applicable.
- **Performance:** Detailed Time ($O$) and Space ($O$) complexity analysis for every solution.
- **Unit Testing:** Comprehensive `_test.go` files for robust verification.

---

## 📂 Repository Structure

The codebase is organized by algorithmic patterns to facilitate easy navigation and learning:

```text
📦 GO-LEETCODE
 ┣ 📂 arrays          # Two Pointers, Sliding Window
 ┣ 📂 strings         # String Manipulation, Hashing
 ┣ 📂 linked-list     # Fast/Slow Pointers, Reversal
 ┣ 📂 trees           # DFS, BFS, BST Logic
 ┣ 📂 concurrency     # Goroutines, WaitGroups, Channels
 ┣ 📂 dynamic-prog    # Memoization & Tabulation
 ┗ 📜 README.md
| # | Problem Name | Pattern | Difficulty | Time Complexity | Space Complexity |
|:-:|:------------|:-------:|:----------:|:---------------:|:----------------:|
| 1 | [Longest Substring Without Repeating Characters](./strings/longest_substring.go) | Sliding Window | 🟡 Medium | $O(N)$ | $O(min(N, M))$ |
| 2 | [Two Sum](./arrays/two_sum.go) | Hash Map | 🟢 Easy | $O(N)$ | $O(N)$ |
| 3 | [Merge k Sorted Lists](./linked-list/merge_k_lists.go) | Heap / Divide & Conquer | 🔴 Hard | $O(N \log k)$ | $O(1)$ |

 Tech Stack
​Language: Golang (1.26.0)
​Testing: Native go test framework
​Linting: golangci-lint
​🧪 How to Run
​To run the solution for a specific problem or package:
 How to Run
​To run the solution for a specific problem or package:
# Clone the repository
git clone [https://github.com/ghosthouse7/GO-LEETCODE.git](https://github.com/ghosthouse7/GO-LEETCODE.git)

# Navigate to the directory
cd GO-LEETCODE

# Run tests for a specific package (e.g., strings)
go test -v ./strings


🤝 Contribution & Connect
​I welcome discussions on code optimization and alternative approaches.
If you find a bug or have a more optimized solution (O(1) space, anyone?), feel free to open a Pull Request.
​Author: ghost_hunter
​GitHub: ghosthouse7
​Crafted with ❤️ and code by ghost_hunter
