
# Linear Regression with One Variable

This project implements a **simple Linear Regression model** to predict the profits of a restaurant franchise's food trucks based on the population of different cities.

## 📌 Project Overview

Imagine you are the CEO of a restaurant franchise deciding where to open new food truck outlets. Using historical data from cities where food trucks already operate, this project helps **predict potential profit or loss** in new cities based on population size.

The goal is to understand the relationship between **city population** and **food truck profit** using linear regression with one variable.

## 📊 Dataset

The dataset used is **`ex1data1.txt`**, which contains two columns:

* **Column 1:** Population of a city (in tens of thousands)
* **Column 2:** Profit of a food truck in that city (in tens of thousands of dollars)

> ⚠️ A negative profit value indicates a loss.

## 🧠 Implementation Details

The notebook walks through the complete machine learning pipeline:

### 1️⃣ Data Visualization

* Visualizes population vs. profit using **matplotlib**
* Helps identify trends and linear relationships

### 2️⃣ Data Preprocessing

* Adds an intercept (bias) term to the dataset
* Initializes model parameters (**theta**)
* Sets the learning rate (**alpha**)

### 3️⃣ Cost Function

* Implements the cost function ( J(\theta) )
* Used to monitor model performance and convergence

### 4️⃣ Gradient Descent

* Applies gradient descent to minimize the cost function
* Iteratively updates parameters to find the optimal regression line

## 🛠 Dependencies

Make sure the following Python libraries are installed:

* `numpy`
* `pandas`
* `matplotlib`

You can install them using:

```bash
pip install numpy pandas matplotlib
```

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
2. Ensure **`ex1data1.txt`** is in the same directory as the notebook.
3. Open and run **`Linear_Regression.ipynb`** in a Jupyter Notebook environment.
4. Observe the training process, cost convergence, and prediction results.

## 📈 Output

* Scatter plot of population vs. profit
* Learned regression line
* Optimized parameters using gradient descent

## 📚 Learning Outcomes

* Understanding linear regression from scratch
* Implementing gradient descent manually
* Visualizing and interpreting regression results




