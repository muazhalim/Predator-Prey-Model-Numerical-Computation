# Predator-Prey-Model-Numerical-Computation

This project **simulates predator-prey dynamics** using numerical methods to solve differential equations. The goal is to analyze population changes over time using different integration techniques.

## Features  

- Implements **Euler’s Method, Heun’s Method, and Ralston-4** to solve differential equations  
- Uses **NumPy** for matrix operations and **Matplotlib** for visualization  
- Compares numerical methods with the **exact solution** to analyze accuracy  
- Evaluates **runtime performance** of different solvers  

## Tech Stack  

- **Python**  
- **Libraries:** NumPy, Matplotlib, SciPy  

## How to Run  

1. **Install dependencies**:  
   ```bash
   pip install numpy matplotlib scipy
   ```
2. **Run the Jupyter Notebook**:  
   ```bash
   jupyter notebook Final_Coursework.ipynb
   ```
3. **Visualize results**: The notebook plots predator-prey population changes over time.  

## Example Output  

```
Method: Euler  
Error: 0.0321  
Runtime: 0.004s  

Method: Heun  
Error: 0.0098  
Runtime: 0.006s  

Method: Ralston-4  
Error: 0.0012  
Runtime: 0.008s  
```

## Future Improvements  

- Implement **adaptive step-size methods**  
- Extend the model with **real-world ecological data**  
- Compare more numerical solvers like **Runge-Kutta-4**  
