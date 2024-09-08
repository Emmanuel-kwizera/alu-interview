
# Minimum Operations

This project focuses on finding the fewest number of operations needed to result in exactly `n` characters in a text file containing a single character `H`. The operations available are **Copy All** and **Paste**.

## Task

### 0. Minimum Operations

Write a function `minOperations(n)` that calculates the fewest number of operations needed to reach exactly `n` `H` characters in the file.

**Prototype**:
```python
def minOperations(n)
```

- Returns an integer.
- If `n` is impossible to achieve, return `0`.

**Example**:
```
n = 9
H => Copy All => Paste => HH => Paste => HHH => Copy All => Paste => HHHHHH => Paste => HHHHHHHHH

Number of operations: 6
```

## Usage

```bash
./0-main.py
```

## Repository

- GitHub repository: `alu-interview`
- Directory: `minimum_operations`
- File: `0-minoperations.py`

