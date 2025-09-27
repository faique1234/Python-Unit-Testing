# Python Unit Testing

This repository demonstrates how to use **unit testing in Python** with simple examples.

## 📌 Functions
We define three functions inside `functions.py`:
- `square(x)` → returns x squared  
- `double(x)` → returns x multiplied by 2  
- `pwr(n)` → returns n raised to the power of n (n^n)  

## 🧪 Unit Tests
All tests are written inside `test_functions.py` using the built-in `unittest` module.

### Example Tests
- `square(4)` → `16`  
- `square(-2)` → `4`  
- `double(3)` → `6`  
- `double(-6)` → `-12`  
- `pwr(2)` → `4`  
- `pwr(3)` → `27`  

## 🚀 Running Tests
In terminal (or GitHub Codespaces / Colab):
```bash
python -m unittest test_functions.py
