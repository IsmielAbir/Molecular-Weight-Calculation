# 🧪 molweightcal

`molweightcal` is a Python package to calculate the **molecular weight** of a chemical compound given its molecular formula (e.g., `H2O`, `C6H12O6`, `(NH4)2SO4`).

---

## Features
✅ Provides step-by-step calculation for each element

✅ Supports all known elements

✅ Lightweight and fast — no external dependencies

## 🔧 Installation

```bash
pip install molweightcal
```

## 🚀 Usage
```bash
import molweightcal

print(molweightcal("C6H12O6"))
```

## ✅ Output
Molecular weight of C6H12O6: 180.156
Details:
C(6) × 12.011 = 72.066
H(12) × 1.008 = 12.096
O(6) × 15.999 = 95.994

## ❗ Error Handling
molweightcal performs thorough input validation to detect and report issues such as:

✅ Unknown chemical elements (e.g., "Z6H2")
✅ Lowercase letters in invalid positions, etc.
