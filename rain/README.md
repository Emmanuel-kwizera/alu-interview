
# Rainwater Retention

This project implements a solution to calculate how much rainwater will be retained between walls of varying heights, represented as a list of non-negative integers.

## Task

### 0. Rain

Write a function `rain(walls)` that calculates the total amount of rainwater that will be retained between the walls after rainfall.

**Prototype**:
```python
def rain(walls)
```

- **walls** is a list of non-negative integers where each integer represents the height of a wall at that position.
- The function should return an integer representing the total amount of rainwater retained between the walls.
- If the list is empty, return `0`.

### Constraints
- Assume that the ends of the list (before index `0` and after index `walls[-1]`) do not retain water.
- The function should account for multiple gaps and varying wall heights to calculate the amount of water that will collect between them.

### Example Usage

```python
walls = [0, 1, 0, 2, 0, 3, 0, 4]
print(rain(walls))  # Output: 6

walls = [2, 0, 0, 4, 0, 0, 1, 0]
print(rain(walls))  # Output: 6
```

### Explanation:

![image](https://github.com/user-attachments/assets/4ec51082-650b-4e7a-81ec-5cde618325db)

For the list `walls = [0, 1, 0, 2, 0, 3, 0, 4]`, the water trapped between the walls can be visualized as follows:

- The first wall (height `1`) and the fourth wall (height `2`) will trap water in the gap between them.
- Similarly, the second and third gaps between walls of heights `2`, `3`, and `4` will trap water as well, leading to a total of `6` units of water.


![image](https://github.com/user-attachments/assets/7e955c00-123d-4b90-9164-1e573d5b7866)

For the list `walls = [2, 0, 0, 4, 0, 0, 1, 0]`, water will be trapped between the first and fourth walls, and between the fourth and seventh walls, also resulting in `6` units of retained water.

## Running the Program

To test the `rain` function, run the following command:

```bash
./0_main.py
```

The `0_main.py` script imports the `rain` function and uses example inputs to demonstrate the functionality of the program.

### Example Output:
```bash
6
6
```

## Repository

- **GitHub repository**: `alu-interview`
- **Directory**: `rain`
- **File**: `0-rain.py`
