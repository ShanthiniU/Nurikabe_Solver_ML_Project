# 🧩 Nurikabe Constraint Solver (A.I. Project)

This repository contains a Python implementation of a Constraint Satisfaction Problem (CSP) solver designed to solve **Nurikabe puzzles**. The solver uses foundational search algorithms and heuristics to find a valid solution state.

---

## 💡 What is Nurikabe?

Nurikabe is a binary determination puzzle played on a rectangular grid. The goal is to determine, for each cell, whether it is an "island" (white) or part of the "sea" (black wall), subject to four simple rules:

1.  **Island Size Rule:** Every numbered cell belongs to exactly one island. The number indicates the total count of cells in that island.
2.  **Island Connectivity Rule:** All cells within a single island must be orthogonally connected (touching side-by-side).
3.  **Wall Connectivity Rule:** All wall cells must be orthogonally connected, forming a single contiguous sea.
4.  **$2\times 2$ Rule:** No $2\times 2$ block of wall cells (black cells) is allowed.

---

## ✅ Phase 1 Completion Status

| Phase | Status | Description |
| :--- | :--- | :--- |
| **Phase 1: Setup & Representation** | **COMPLETE** | Grid representation using NumPy, standardized cell constants (WALL=-1, ISLAND=-2), a robust console display with grid lines, and efficient extraction of clue coordinates. |
| **Phase 2: Core Algorithms** | 🚧 IN PROGRESS | Implementing fundamental constraint algorithms, starting with Depth-First Search (DFS) for connectivity checks. |

## 🛠️ Technologies Used

* **Python 3**
* **NumPy** (For efficient grid manipulation and indexing)
* **Google Colab** (Development Environment)

---

## 🙏 Acknowledgement

This project was developed with guidance and collaborative assistance from the **Gemini AI model**. This process was instrumental in structuring the project into logical phases, refining Python best practices, and implementing core algorithmic concepts (like DFS).

---
