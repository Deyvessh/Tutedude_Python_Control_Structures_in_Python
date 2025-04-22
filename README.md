## 📜 Program Explanation: Even/Odd Checker & Sum from 1 to 50

### 📌 Part 1: Check if a Number is Even or Odd

```python
number = int(input('Enter a number: '))

if number % 2 == 0:
    print(f'{number} is an even number.')
else:
    print(f'{number} is an odd number.')
```

### ✅ Description:

- **`input()`**: Takes user input as a string.
- **`int()`**: Converts the string to an integer.
- **`number % 2`**: Uses the modulus operator to check for a remainder.
  - If remainder is `0`, it's an **even number**.
  - If remainder is `1`, it's an **odd number**.

### 💡 Example:

```
Enter a number: 17
17 is an odd number.
```

---

### 📌 Part 2: Calculate the Sum from 1 to 50

```python
sum = 0

for i in range(1, 51):
    sum += i

print(f'The sum of numbers from 1 to 50 is: {sum}')
```

### ✅ Description:

- **`sum = 0`**: Initializes the sum variable to 0.
- **`range(1, 51)`**: Loops from 1 to 50 (since the end is exclusive).
- **`sum += i`**: Accumulates the sum by adding each value of `i` from the loop.

### 🧾 Dry Run (Partial):

| i   | sum           |
|-----|---------------|
| 1   | 0 + 1 = 1     |
| 2   | 1 + 2 = 3     |
| 3   | 3 + 3 = 6     |
| ... | ...           |
| 50  | 1275 (final)  |

### 💡 Output:

```
The sum of numbers from 1 to 50 is: 1275
```

