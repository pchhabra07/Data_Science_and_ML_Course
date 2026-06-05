# 🐍 Python & Data Science — Lecture Notes & Practice

> A complete, hands-on journey from **Python Basics** all the way through **Machine Learning** and **Scikit-Learn Data Cleaning** — with personal notes and live code examples in every notebook.

---

## 💻 Repository Structure

```
├── 📓 Python_Lec1_CB_PythonBasics_Strings_Lists_Tuples_Dicts_Sets.ipynb
├── 📓 Python_Lec2_CB_MatchCase_IfElse_WhileLoop.ipynb
├── 📓 Python_Lec3_CB_Functions_Params_ArgsKwargs_Scope_LambdaFunction.ipynb
├── 📓 Python_Lec4_CB_Recursion_Decorators.ipynb
├── 📓 Python_Lec5_CB_Generators_OOPS_Inheritance.ipynb
├── 📓 Python_Lec6_CB_Encapsulation_Polymorphism.ipynb
├── 📓 Python_Lec7_CB_Abstraction.ipynb
├── 📓 Python_Lec8_CB_Numpy_Pandas.ipynb
├── 📓 Python_Lec9_ManualDataCleaning_Encoding_Mapping.ipynb
├── 📓 Python_Lec10_CB_ExploratoryDataAnalysis_EDA.ipynb
├── 📓 Python_Lec11_CB_Graphs_MatplotLib_MLTheory.ipynb
├── 📓 Python_Lec12_CB_SKLearn_MLFlow_TrainTestSplit_Scaling_Seaborn.ipynb
├── 📓 Python_Lec13_CB_ColumnTransformations_DataCleaning_using_SKLearn.ipynb
├── 📓 Python_Lec14_CB_Part1_PCA_Manually.ipynb
├── 📓 Python_Lec14_CB_Part2_PCA_SKLearn.ipynb
├── 📓 Python_Lec15_CB_LinearRegression_MultipleLinearRegression_Manual_SKLearn.ipynb
├── 📁 assignments/
│    └── 📓 CB_Assignment1.ipynb
└── 📁 datasets/
```

---

## 📚 Lecture-by-Lecture Breakdown

---

### 📓 Lecture 1 — Python Basics: Strings, Lists, Tuples, Dicts & Sets

**File:** `Python_Lec1_CB_PythonBasics_Strings_Lists_Tuples_Dicts_Sets.ipynb`

The very first notebook — building the foundation of Python from scratch.

| Topic | What's Covered |
|---|---|
| **Hello World & Comments** | `print()`, single-line comments (`#`), multi-line docstrings (`"""`) |
| **Variables & Data Types** | Declaring variables, `int`, `float`, `str`, `bool`; dynamic typing |
| **Variable Naming Rules** | What makes a valid variable name; invalid examples (2myvar, my-var, etc.) |
| **Multiple Assignment** | Assigning multiple variables at once: `x, y, z = "a", "b", "c"` |
| **Type Casting** | `int()`, `float()`, `str()` — converting between types |
| **Strings** | Indexing, slicing, string methods (`.upper()`, `.lower()`, `.strip()`, `.replace()`), string length, f-strings, string formatting |
| **Boolean** | Truthy/falsy values, `bool()` function, comparison operators |
| **Operators** | Arithmetic, assignment, comparison, logical operators |
| **Lists** | Creating lists, indexing, negative indexing, slicing, `.append()`, `.insert()`, `.remove()`, `.pop()`, `.sort()`, `.reverse()`, `.copy()`, `.extend()`, list concatenation, looping through lists |
| **Tuples** | Immutable sequences, creating tuples, single-item tuples (the trailing comma rule), indexing, slicing, unpacking, joining tuples |
| **Dictionaries** | Key-value pairs, accessing values (`.get()`), updating values, `.keys()`, `.values()`, `.items()`, `.update()`, `.pop()`, looping over dictionaries, nested dictionaries |
| **Sets** | Unordered & unindexed collections, no duplicate values, `.add()`, `.update()`, `.remove()`, `.discard()`, set operations (union, intersection, difference), `frozenset` |

---

### 📓 Lecture 2 — Control Flow: Match-Case, If-Else, While Loop

**File:** `Python_Lec2_CB_MatchCase_IfElse_WhileLoop.ipynb`

Control the flow of your Python programs.

| Topic | What's Covered |
|---|---|
| **Match-Case** | Python's structural pattern matching (equivalent to switch-case); matching on values with `match` and `case` |
| **If / Elif / Else** | Conditional branching; nested if-else; using comparison and logical operators in conditions |
| **While Loop** | Repeated execution with a condition; `break` to exit, `continue` to skip; loop `else` clause |

---

### 📓 Lecture 3 — Functions: Parameters, Args/Kwargs, Scope & Lambda

**File:** `Python_Lec3_CB_Functions_Params_ArgsKwargs_Scope_LambdaFunction.ipynb`

Everything about writing reusable, flexible functions.

| Topic | What's Covered |
|---|---|
| **Functions** | Defining with `def`, calling functions, return values, purpose of reusable code blocks |
| **Parameters vs Arguments** | Parameters = variable names in the definition; Arguments = actual values passed when calling |
| **Positional Only Arguments** | Using `/` in the signature to force positional-only parameters |
| **Keyword Only Arguments** | Using `*` in the signature to force keyword-only parameters |
| **`*args`** | Accepting any number of positional arguments; `*args` creates a tuple inside the function |
| **`**kwargs`** | Accepting any number of keyword arguments; `**kwargs` creates a dictionary inside the function |
| **Local & Global Scope** | Variables inside vs. outside functions; using the `global` keyword to modify a global variable from within a function |
| **Lambda Function** | Anonymous one-liner functions: `lambda args: expression`; no `return` keyword needed; used for short, simple operations |

---

### 📓 Lecture 4 — Recursion & Decorators

**File:** `Python_Lec4_CB_Recursion_Decorators.ipynb`

Advanced function concepts that power elegant, composable code.

| Topic | What's Covered |
|---|---|
| **Recursion** | A function calling itself; base case to stop recursion; classic examples like factorial, Fibonacci |
| **Decorators** | A function that takes another function as input and returns it with added functionality; the `@decorator_name` syntax as shorthand for `func = decorator(func)`; building wrapper functions with `*args` and `**kwargs` |
| **Coding Questions** | Practice problems applying recursion and decorators |

---

### 📓 Lecture 5 — Generators, OOP & Inheritance

**File:** `Python_Lec5_CB_Generators_OOPS_Inheritance.ipynb`

Bridging functional and object-oriented Python.

| Topic | What's Covered |
|---|---|
| **Generators** | Functions that can pause and resume using `yield`; difference between `yield` (pauses, returns value, resumes) and `return` (ends execution completely); lazy evaluation for memory efficiency |
| **OOP — Overview** | Grouping data and functions together; modelling real-world entities; advantages: organised, reusable, and maintainable code |
| **Classes & Objects** | Class as a blueprint/design; object as the real instance created from it |
| **`__init__` Method** | Constructor that runs automatically upon object creation; used to initialise object properties |
| **`self` Parameter** | First parameter of all class methods; refers to the instance itself |
| **Class Properties vs Object Properties** | Class properties are shared across all objects; object properties are unique to each instance |
| **Updating Class Properties** | Using `ClassName.property = new_value` to update a shared class-level variable |
| **Inheritance** | A child (derived) class inheriting methods and properties from a parent (base) class |
| **`super()`** | Calling the parent class's methods without explicitly naming the parent class |
| **Method Overriding** | Child class providing its own implementation of a parent class method |

---

### 📓 Lecture 6 — Encapsulation & Polymorphism

**File:** `Python_Lec6_CB_Encapsulation_Polymorphism.ipynb`

The other two pillars of Object-Oriented Programming.

| Topic | What's Covered |
|---|---|
| **Encapsulation** | Bundling data (attributes) and methods together inside a class and restricting direct external access |
| **Private Attributes** | Using `__` (double underscore) prefix to make an attribute private; accessing it from outside the class raises an `AttributeError` |
| **Protected Attributes** | Using `_` (single underscore) prefix as a convention that the attribute should not be accessed from outside the class (no error, but not recommended) |
| **Polymorphism — Concept** | Same function/method name behaving differently depending on the data type or number of arguments passed |
| **Built-in Polymorphism** | Example: `len("Pratham")` counts characters; `len([1,2,3])` counts elements — same function, different behaviour |
| **Method-based Polymorphism** | Different classes can define methods with the same name; Python decides which method to execute based on the object calling it |

---

### 📓 Lecture 7 — Abstraction

**File:** `Python_Lec7_CB_Abstraction.ipynb`

The final OOP pillar — hiding complexity.

| Topic | What's Covered |
|---|---|
| **Abstraction — Concept** | Hiding internal implementation details and only exposing important/relevant features to the user |
| **Abstract Classes** | Parent class that has at least one abstract method (no implementation); created using Python's `abc` module (`ABC`, `abstractmethod`) |
| **Abstract Methods** | Methods declared in the abstract class without a body; all child classes **must** provide their own implementation |
| **Rule Enforcement** | Attempting to instantiate an abstract class raises a `TypeError`; child classes without implementing all abstract methods also raise an error |
| **Practical Example** | `MainBankApp` as an abstract class with an abstract method; `MobileBankApp` and `WebBankApp` as concrete child classes each providing their own implementation |

---

### 📓 Lecture 8 — NumPy & Pandas

**File:** `Python_Lec8_CB_Numpy_Pandas.ipynb`

The two most essential libraries for Data Science in Python.

#### 🔢 NumPy

| Topic | What's Covered |
|---|---|
| **What is NumPy** | Library for mathematical and numerical operations; `np.array()` to create arrays |
| **NumPy Arrays vs Lists** | Arrays enforce same data type for all elements (unlike Python lists) |
| **`.shape`** | Returns the shape/dimensions of an array |
| **0-D Arrays (Scalars)** | A single element: `np.array(5)` |
| **1-D Arrays (Vectors)** | A collection of elements: `np.array([1,2,3])` |
| **2-D Arrays (Matrices)** | A collection of 1-D arrays: `np.array([[1,2,3],[4,5,6]])` |
| **3-D Arrays (Tensors)** | A collection of 2-D arrays: `np.array([[[1,2,3],[4,5,6]],[[7,8,9],[10,11,12]]])` |
| **Array Operations** | Broadcasting, indexing, slicing, arithmetic operations across arrays |

#### 🐼 Pandas

| Topic | What's Covered |
|---|---|
| **What is Pandas** | Library for reading and working with structured data; loads CSV/JSON files into DataFrames |
| **DataFrame** | A 2D tabular data structure with rows and columns |
| **`.loc[idx]`** | Accessing rows by index label |
| **Reading Data** | `pd.read_csv()` for CSV files |
| **DataFrame Operations** | Selecting columns, filtering rows, groupby, aggregations, merging, and many more Pandas operations |

---

### 📓 Lecture 9 — Manual Data Cleaning: Encoding & Mapping

**File:** `Python_Lec9_ManualDataCleaning_Encoding_Mapping.ipynb`

Hands-on data cleaning using the Titanic dataset — entirely by hand (no Scikit-Learn yet).

| Topic | What's Covered |
|---|---|
| **What is Data Cleaning** | Handling missing data, removing duplicates, encoding/mapping columns to numerical values |
| **Rules for Missing Data** | Fill missing values if < ~10% of the column is missing; drop the entire column if > 30-40% is missing |
| **`.info()`** | Shows total entry counts per column; used to identify which columns have missing values |
| **`.head()`** | Prints the first 5 rows of the DataFrame |
| **Filling Missing Values** | `.fillna(value)` to fill `NaN` values; `.mean()`, `.median()`, `.mode()` to compute fill values |
| **Dropping Columns** | `.drop(columns, axis=1)` to remove entire columns; `axis=0` = rows, `axis=1` = columns |
| **Removing Duplicates** | `.drop_duplicates()` |
| **Mapping** | Using `.map()` to replace categorical values with numeric values for columns with 2 categories or where priority makes sense (e.g., `True` → `1`, `False` → `0`) |
| **One Hot Encoding** | `pd.get_dummies()` for columns with more than 2 categories (e.g., `embarked` → `embarked_C`, `embarked_S`, `embarked_Q`); `drop_first=True` to reduce redundant columns |
| **Why Not Map Multi-Category Columns** | Mapping 3+ categories to 0, 1, 2 implies a false priority/ordering; One Hot Encoding avoids this |
| **Priority Mapping** | When priority genuinely exists (e.g., `pclass`: 1st class > 2nd > 3rd), mapping to 3, 2, 1 is appropriate |
| **Boolean to Numerical** | `.replace({True: 1, False: 0})` to convert all boolean columns to integers |
| **Saving the Clean Dataset** | `df.to_csv('filename.csv', index=False)` to export the cleaned DataFrame |

---

### 📓 Lecture 10 — Exploratory Data Analysis (EDA)

**File:** `Python_Lec10_CB_ExploratoryDataAnalysis_EDA.ipynb`

Exploring and understanding data patterns before building any model.

| Topic | What's Covered |
|---|---|
| **Recap of Data Cleaning Steps** | Summary of everything done in Lec9: missing values, duplicates, encoding, saving |
| **What is EDA** | Exploring data to understand patterns, distributions, and relationships between columns |
| **`.value_counts()`** | Counting occurrences of each unique value in a column; useful for categorical columns |
| **`.describe()`** | Summary statistics for the entire DataFrame: count, mean, std, min, 25th/50th/75th percentile, max |
| **Cross-tabulation (`.crosstab()`)** | Finding the relationship between two categorical columns (e.g., how many males/females survived) |
| **Normalisation in Crosstab** | `normalize='index'` → percentage per row (e.g., % of males that survived); `normalize='columns'` → percentage per column |
| **Boolean Indexing / Filtering** | `df[df['column'] == value]` to filter rows; chaining to get specific columns of filtered results |
| **`.groupby()`** | Grouping a continuous column by a categorical column to compute aggregate values (mean, sum, etc.) — used when one column is continuous and the other is categorical |
| **Feature Engineering Exploration** | Creating derived features like `family_size = sibsp + parch + 1` from existing columns |

---

### 📓 Lecture 11 — Graphs (Matplotlib), Histograms & ML Theory

**File:** `Python_Lec11_CB_Graphs_MatplotLib_MLTheory.ipynb`

Visualising data and understanding the theory behind Machine Learning.

#### 📊 Data Visualisation with Matplotlib

| Topic | What's Covered |
|---|---|
| **Matplotlib** | Core plotting library; using `matplotlib.pyplot` (aliased as `plt`) |
| **Histograms** | `.hist()` to plot distributions; `bins` parameter to control grouping resolution |
| **Boolean Indexing in Plotting** | Filtering data before plotting (e.g., plotting age of only survivors) |
| **Feature Creation** | Combining `sibsp` and `parch` into a new `family_size` column for better insights |

#### 🤖 Machine Learning Theory

| Topic | What's Covered |
|---|---|
| **What is ML** | Traditional Programming: input + logic → output. ML: input + output (data) → logic (patterns) |
| **ML vs Deep Learning** | ML: features provided manually; DL: features extracted automatically through layers |
| **Generative AI** | Creating new data from existing data (e.g., chatbots, voice generation) |
| **Supervised Learning** | Labelled data with features and a target value; Regression (numerical target), Classification (categorical target) |
| **Unsupervised Learning** | No target value; model finds structure via Clustering |
| **Semi-Supervised Learning** | ~70% labelled data, ~30% unlabelled; combines both approaches |
| **Reinforcement Learning** | Learning through reward and punishment signals |
| **Batch Learning (Offline)** | Entire dataset used at once for training; slow for huge datasets; can't adapt to new data quickly; good for static datasets |
| **Online Learning** | Model learns continuously from new incoming data; adapts in real-time |

---

### 📓 Lecture 12 — Scikit-Learn: ML Flow, Train-Test Split, Scaling & Seaborn

**File:** `Python_Lec12_CB_SKLearn_MLFlow_TrainTestSplit_Scaling_Seaborn.ipynb`

Introduction to Scikit-Learn and the standard ML workflow.

#### ⚙️ Feature Engineering & ML Flow

| Topic | What's Covered |
|---|---|
| **Feature Engineering** | Feature Selection (choosing relevant features), Feature Extraction (deriving from raw data), Feature Creation (building new ones like One Hot Encoded columns or `family_size`) |
| **ML Flow** | Load data → Clean data → Split into Train/Test sets → Scale data → Train model → Evaluate model |
| **Why Not Test on Training Data** | Avoids overfitting; a model tested on its own training data will get ~100% accuracy, which is misleading |

#### 🔪 Train-Test Split (Scikit-Learn)

| Topic | What's Covered |
|---|---|
| **Concept** | Data is split: ~70% Training, ~30% Testing |
| **`train_test_split`** | `from sklearn.model_selection import train_test_split`; accepts `X` (features) and `Y` (target); returns `X_train`, `X_test`, `Y_train`, `Y_test` |

#### 📏 Scaling

| Topic | What's Covered |
|---|---|
| **Why Scale** | Features like `Age` (0–80) and `CTC` (in lakhs) on very different scales can mislead the ML model |
| **MinMax Scaler** | Transforms values to a [0, 1] range: `x = (X - min) / (max - min)`; `fit_transform` on training data, `transform` only on test data (using the same fit from training) |
| **Standard Scaler (Z-score)** | `x = (X - mean) / std`; unbounded range but 68% values fall in [-1, 1], 95% in [-2, 2], 99.7% in [-3, 3] |
| **Fit vs Transform** | `fit` calculates the parameters (min, max, mean, std); `transform` applies the transformation; always fit on training data only |

#### 📈 Seaborn & Multivariate Analysis

| Topic | What's Covered |
|---|---|
| **Univariate Analysis — Categorical** | `sns.countplot(df, x='column')` to count observations per category; `hue` parameter for colour-coded grouping |
| **Multivariate Analysis — Numerical-Numerical** | Scatter plots: `sns.scatterplot(df, x='col1', y='col2')` |
| **Multivariate Analysis — Numerical-Categorical** | Bar plots: `sns.barplot(df['sex'], df['age'])` |
| **Multivariate Analysis — Categorical-Categorical** | Heatmaps on crosstabs |

---

### 📓 Lecture 13 — Column Transformations & Data Cleaning using Scikit-Learn

**File:** `Python_Lec13_CB_ColumnTransformations_DataCleaning_using_SKLearn.ipynb`

Automating the entire data cleaning pipeline using Scikit-Learn transformers.

| Topic | What's Covered |
|---|---|
| **Why SKLearn for Cleaning** | Automates and standardises the same transformations done manually in Lec9; makes the pipeline reproducible and avoids data leakage |
| **SimpleImputer** | Fills missing values in columns; default strategy is `mean`; configurable via `strategy` parameter (`mean`, `median`, `most_frequent`, `constant`) |
| **OrdinalEncoder** | Encodes categorical columns where order/priority matters (like `class`: First > Second > Third); takes a `categories` parameter with ordered list |
| **OneHotEncoder** | Encodes multi-category columns without priority into binary dummy columns; replaces `pd.get_dummies()` from manual cleaning |
| **SKLearn 2D Input Requirement** | Scikit-Learn always expects 2D array input; use `[[column]]` (double square brackets) instead of `[column]` |
| **Train-Test Split with SKLearn** | `train_test_split` to split data before applying any transformation (always fit only on training data) |
| **ColumnTransformer** | Applies multiple different transformers to different columns in one step, rather than doing them one by one |
| **ColumnTransformer Syntax** | Takes a `transformers` parameter: list of `(name, transformer_object, [columns_to_apply_on])` tuples |
| **`remainder` Parameter** | `passthrough` → keep columns that had no transformation; `drop` → remove those columns |
| **Full Pipeline** | Combining Train-Test Split → SimpleImputer → OrdinalEncoder / OneHotEncoder → ColumnTransformer into a clean, automated data preparation pipeline |

---

### 📓 Lecture 14 — Principal Component Analysis (PCA)

This lecture is divided into two parts covering both manual calculations and library implementations.

#### 📊 Part 1: PCA Manually
**File:** `Python_Lec14_CB_Part1_PCA_Manually.ipynb`

Understanding PCA from scratch using linear algebra.

| Topic | What's Covered |
|---|---|
| **Random Seed Initialization** | Setting `np.random.seed()` for reproducible data generation |
| **Synthetic Multi-Dimensional Data** | Creating synthetic 3D datasets using multivariate normal distribution (`np.random.multivariate_normal`) with mean vectors and covariance matrices |
| **Mean Vector & Standardization** | Computing means per feature and centering data |
| **Covariance Matrix Computation** | Calculating the covariance matrix manually from feature matrices using `np.cov()` |
| **Eigen Decomposition** | Finding eigenvalues and eigenvectors of the covariance matrix using `np.linalg.eig()` |
| **Selecting Principal Components** | Sorting eigenvalues to identify top eigenvectors that explain the maximum variance |
| **Projection Matrix Creation** | Creating a transformation matrix `W` by stacking the top selected eigenvectors |
| **Mathematical Dot Product Projection** | Projecting the original high-dimensional dataset onto the lower dimensional subspace using matrix multiplication (`np.dot`) |
| **3D Data Projection Visualization** | Visualizing 3D data and principal axes using Matplotlib's 3D plotting tools (`Arrow3D`, `FancyArrowPatch`, `proj3d`) |

#### ⚙️ Part 2: PCA using Scikit-Learn
**File:** `Python_Lec14_CB_Part2_PCA_SKLearn.ipynb`

Streamlining dimensionality reduction using built-in Scikit-Learn estimators.

| Topic | What's Covered |
|---|---|
| **StandardScaler Scaling** | Fitting and transforming data using `StandardScaler` to ensure zero mean and unit variance before running PCA |
| **PCA Instantiation** | Initializing `PCA` class with desired output dimensions (`n_components`) |
| **Fit & Transform Pipeline** | Fitting the PCA estimator on scaled data and transforming it into principal components |
| **Explained Variance Ratio** | Analyzing `pca.explained_variance_ratio_` to determine the percentage of variance captured by each principal component |
| **PCA Components Matrix** | Reviewing `pca.components_` (the eigenvectors representing the directions of maximum variance in the feature space) |
| **Scatter Plot Visualization** | Plotting projected data along `PC1` and `PC2` coordinate axes to identify patterns and clusters |

---

### 📓 Lecture 15 — Linear Regression & Multiple Linear Regression: Manual & SKLearn

**File:** `Python_Lec15_CB_LinearRegression_MultipleLinearRegression_Manual_SKLearn.ipynb`

Implementing and evaluating both Single and Multiple Linear Regression models manually and using Scikit-Learn.

#### 📈 Single Linear Regression (Manual & SKLearn)

| Topic | What's Covered |
|---|---|
| **Manual Implementation** | Custom `LINEARREGRESSION` class with vectorized slope (`m`) and intercept (`b`) mathematical derivations |
| **SKLearn Implementation** | Training a model with `LinearRegression` from `sklearn.linear_model` on `placement.csv` dataset |
| **Coefficients & Intercepts** | Exposing `coef_` and `intercept_` to predict output package using the $y = mx + b$ equation |

#### 📏 Evaluation Metrics

| Topic | What's Covered |
|---|---|
| **Mean Absolute Error (MAE)** | Measures average magnitude of errors using `mean_absolute_error` |
| **Mean Squared Error (MSE)** | Computes the average squared differences using `mean_squared_error` |
| **Root Mean Squared Error (RMSE)** | Calculated as the square root of MSE (`np.sqrt(mse)`) |
| **R2 Score** | Computes the coefficient of determination (`r2_score`) to measure variance explained by the model |

#### 🧮 Multiple Linear Regression (Manual)

| Topic | What's Covered |
|---|---|
| **OLS Matrix Formulation** | Solving coefficients using Ordinary Least Squares closed-form equation: $\beta = (X^T X)^{-1} X^T y$ |
| **Custom Implementation** | Adding intercept columns of ones (`np.insert`), matrix inversion (`np.linalg.inv`), and dot product operations |

---

## 📝 Assignment

### `assignments/CB_Assignment1.ipynb`
Practice assignment covering concepts from the Python Basics lectures. Includes hands-on coding problems to reinforce understanding of variables, data structures, control flow, and functions.

---

## 🛠️ Tools & Libraries Used

| Library | Purpose |
|---|---|
| `Python` | Core programming language |
| `NumPy` | Numerical arrays and mathematical operations |
| `Pandas` | DataFrames, data loading, data manipulation |
| `Matplotlib` | Data visualisation (histograms, line plots) |
| `Seaborn` | Statistical data visualisation (countplot, scatterplot, barplot) |
| `Scikit-Learn` | Train-test split, scaling, encoding, column transformations, PCA |

---

> 💡 **Note:** All notebooks use the **Titanic dataset** as the primary dataset for data cleaning, EDA, and ML workflow demonstrations — making it easy to trace the same data across lectures and see how it evolves from raw to model-ready.
