# NumPy Learning & Practice

A structured NumPy learning repository covering concepts from beginner to advanced level, with hands-on exercises and real-world data analysis projects.

This repository documents my journey of learning NumPy for **Data Science, Artificial Intelligence, Machine Learning, and internship preparation**.

---

## 📌 About NumPy

[NumPy](https://numpy.org/) (Numerical Python) is a fundamental Python library for numerical computing and scientific computing.

It provides:

- Fast multidimensional arrays
- Vectorized mathematical operations
- Array indexing and slicing
- Statistical operations
- Linear algebra functionality
- Broadcasting
- Efficient memory usage
- Tools for data preprocessing and numerical analysis

NumPy is widely used as a foundation for libraries such as **Pandas, Matplotlib, and Scikit-learn**.

---

## 🎯 Learning Objectives

The main goals of this repository are to:

- Build a strong foundation in NumPy
- Understand NumPy arrays and their properties
- Perform efficient numerical operations
- Learn vectorization and broadcasting
- Work with multidimensional arrays
- Perform data filtering and transformation
- Understand memory-efficient NumPy operations
- Apply NumPy to real-world datasets
- Prepare for internship and technical interviews
- Build a foundation for Data Science and Machine Learning

---

## 📚 Topics Covered

### 1. NumPy Fundamentals

- What is NumPy?
- Why NumPy is used
- NumPy vs Python Lists
- Installing and importing NumPy
- Creating NumPy arrays
- 1D, 2D and 3D arrays
- `ndim`
- `shape`
- `size`
- `dtype`
- `itemsize`
- `nbytes`

### 2. Array Indexing & Slicing

- Positive indexing
- Negative indexing
- Row and column selection
- Array slicing
- Modifying array elements
- Selecting rows and columns

### 3. Array Creation

- `np.zeros()`
- `np.ones()`
- `np.arange()`
- `np.random.rand()`
- `np.random.randint()`

### 4. Mathematical Operations

- Addition
- Subtraction
- Multiplication
- Division
- Element-wise operations
- Vectorization
- `np.sqrt()`
- `np.square()`
- `np.power()`
- `np.abs()`
- `np.exp()`
- `np.log()`
- `np.sin()`
- `np.cos()`

### 5. Aggregation & Statistics

- `np.sum()`
- `np.mean()`
- `np.median()`
- `np.min()`
- `np.max()`
- `np.std()`
- `np.var()`
- `np.percentile()`
- Working with `axis=0`
- Working with `axis=1`

### 6. Boolean & Advanced Indexing

- Comparison operations
- Boolean arrays
- Boolean indexing
- Multiple conditions
- Fancy indexing
- Selecting specific rows
- Selecting specific columns

### 7. Shape Manipulation

- `reshape()`
- Automatic dimension inference using `-1`
- `flatten()`
- `ravel()`
- Transpose
- `.T`
- `np.transpose()`

### 8. Combining & Splitting Arrays

- `np.concatenate()`
- `np.vstack()`
- `np.hstack()`
- `np.split()`
- `np.vsplit()`
- `np.hsplit()`

### 9. Sorting & Searching

- `np.sort()`
- `np.argsort()`
- `np.where()`
- `np.argmax()`
- `np.argmin()`

### 10. Missing Values

- `np.nan`
- `np.isnan()`
- `np.nanmean()`
- `np.nansum()`
- `np.nanmax()`
- `np.nanmin()`
- Replacing missing values

### 11. Linear Algebra

- Matrix addition
- Matrix subtraction
- Element-wise multiplication
- Matrix multiplication
- `@` operator
- `np.matmul()`
- `np.dot()`
- `np.linalg.det()`
- `np.linalg.inv()`

### 12. Advanced NumPy

- Vectorization
- Universal Functions (ufuncs)
- Views vs Copies
- `np.shares_memory()`
- Broadcasting
- Memory optimization
- `dtype` optimization
- Advanced indexing
- Conditional transformations
- `np.einsum()`
- Efficient NumPy programming

---

## 💼 Real-World Practice

The repository also includes practical data analysis exercises designed to simulate internship-level tasks.

### 👨‍🎓 Student Marks Analyzer

Analyzed student performance data using NumPy.

Tasks included:

- Subject-wise averages
- Student-wise averages
- Highest and lowest marks
- Filtering students based on performance
- Pass/Fail classification
- Conditional bonus allocation
- Finding the highest-performing student
- Performance classification using `np.where()`

### 💰 Salary Analysis

Employee salary data is analyzed using NumPy.

Planned analysis includes:

- Average salary
- Minimum and maximum salary
- Salary filtering
- Experience-based analysis
- Performance-based bonuses
- Percentage salary increases
- Final salary calculation
- Identifying high-performing employees

---

## 🛠️ Technologies Used

- Python
- NumPy
- Jupyter Notebook

---

## 📂 Repository Structure

```text
numpy-learning/
│
├── NumPy_Learning.ipynb
├── student_marks_analyzer.ipynb
├── salary_analysis.ipynb
└── README.md
