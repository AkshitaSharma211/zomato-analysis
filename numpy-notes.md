# NumPy Notes

## Why NumPy for ML?
- Faster than Python lists
- Used by pandas, scikit-learn internally
- Handles matrix operations which ML needs

## What I learned
- Creating arrays
- Array operations
- Slicing 1D and 2D arrays
- reshape and conditional filtering

## 📊 More Concepts I Learned

### 🔢 Statistical Operations
- Calculated basic statistics on arrays:
- Mean (`np.mean`)
- Median (`np.median`)
- Standard Deviation (`np.std`)
- Variance (`np.var`)

## 🔀 Sorting & Indexing
- Sorted arrays using `np.sort`
- Reversed arrays using slicing (`[::-1]`)
- Found positions using:
- `np.argmax` → index of maximum value  
- `np.argmin` → index of minimum value  

## 🧱 Array Stacking
- Combined arrays using:
- `np.vstack()` → vertical stacking  
- `np.hstack()` → horizontal stacking  

## 🎯 Conditional Filtering
- Filtered data using conditions:
- Extracted passing marks (`marks >= 50`)
- Extracted failing marks (`marks < 50`)
- Calculated pass percentage

## ⚡ Performance Comparison
- Compared Python lists vs NumPy arrays
- NumPy is faster because:
- Uses vectorized operations  
- Avoids explicit Python loops  