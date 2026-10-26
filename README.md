# Python Star Patterns

A beginner-friendly Python project demonstrating how to print different star (`*`) patterns in the console using `for` loops, nested loops, and string multiplication.

## 📌 Overview

This repository contains a Jupyter Notebook with examples of common star patterns. It is designed to help beginners practise:

- `for` loops and nested loops
- `range()` and loop boundaries
- The `print()` function and the `end` parameter
- String repetition using the `*` operator
- Using spaces to align output and create simple shapes

## ✨ Patterns Included

The notebook demonstrates these patterns:

1. **Repeated rows of stars** — prints a fixed number of stars on each row.
2. **Rows with a fixed width** — uses nested loops to print stars row by row.
3. **Increasing left-aligned triangle** — adds one star per row.
4. **Right-aligned increasing triangle** — combines spaces and stars for alignment.
5. **Decreasing left-aligned triangle** — removes one star per row.
6. **Right-aligned decreasing triangle** — prints descending rows with leading spaces.

### Example output

Increasing triangle:

```text
*
**
***
****
*****
```

Right-aligned increasing triangle:

```text
    *
   **
  ***
 ****
*****
```

Decreasing triangle:

```text
*****
****
***
**
*
```

## 🛠️ Requirements

- Python 3
- Jupyter Notebook or JupyterLab (recommended), or another Python environment

No third-party Python packages are required for the examples in this notebook.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd Patterns-main
```

Replace `<your-repository-url>` with the URL of your GitHub repository.

### 2. Open the notebook

If Jupyter Notebook is installed, run:

```bash
jupyter notebook
```

Open `patterns.ipynb` in the browser and run the cells in order.

Alternatively, upload `patterns.ipynb` to Google Colab and run it there.

## 🧠 How It Works

A nested loop can control both the rows and the number of stars printed in each row. For example:

```python
n = 5

for i in range(1, n + 1):
    print("*" * i)
```

- `range(1, n + 1)` iterates from 1 through `n`.
- `"*" * i` repeats the star character `i` times.
- `print()` moves to the next line after each row.

To right-align a pattern, print leading spaces before the stars:

```python
n = 5

for i in range(1, n + 1):
    print(" " * (n - i) + "*" * i)
```

## 📂 Project Structure

```text
Patterns-main/
├── README.md
└── patterns.ipynb
```

## 🎯 Learning Goals

After completing the notebook, you should be able to:

- Build simple console patterns using loops.
- Predict how nested loops execute.
- Adjust loop ranges to control pattern dimensions.
- Use spaces to align text output.
- Create your own variations, including pyramids, diamonds, and number patterns.

## 🔮 Ideas for Improvement

- Add centered pyramids and inverted pyramids.
- Create diamond and hollow-square patterns.
- Print number and alphabet patterns.
- Let users enter the pattern size at runtime.
- Refactor repeated logic into reusable functions.

## 🤝 Contributing

Suggestions and improvements are welcome. Fork the repository, make your changes, and open a pull request.

## 📄 License

No license is specified in this repository. Add a license file if you want to define how others may use, modify, and distribute the project.
