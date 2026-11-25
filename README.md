# JavaScript Debugging Exercises

This folder has six JavaScript programs that had errors. Each program is fixed and saved in its own file.

## Files and Fixes

| File | Problem | Fix |
|------|---------|-----|
| `q1.js` | `message` was declared inside the function, so it could not be used outside it. | Return `message` from the function and save it in a variable outside. |
| `q2.js` | A number has no `toUpperCase()` method, so `convertToUppercase(12345)` gave a TypeError. | Change the input to a string with `String(text)` first. |
| `q3.js` | A closing bracket `)` was missing in `console.log("Final Grade: " + student1;`. | Add the missing `)`. |
| `q4.js` | A closing bracket `)` was missing in `calculateBill(1000, 2, 20;`. The calculation also ran before the checks. | Add the missing `)` and move the quantity and discount checks to the top. |
| `q5.js` | The return statement used `netSallary`, which is a spelling mistake. | Use the correct name `netSalary`. |
| `q6.js` | `countDown` called itself forever because it had no stopping condition. | Add `if (n < 0) return;` as the base case. |

## How to Run

You need [Node.js](https://nodejs.org) installed.

Open a terminal in this folder and run any file with:

```
node q1.js
```

Change `q1.js` to `q2.js`, `q3.js` and so on to run the other files.

## Expected Output

- `q1.js`: `Welcome to JavaScript!`
- `q2.js`: `12345` and `HELLO`
- `q3.js`: Grades `A` for Ram and `C` for Sita
- `q4.js`: Total payable `1350` and `1600`
- `q5.js`: Net salary `31500` for Ram and `43200` for Sita
- `q6.js`: Numbers from `5` down to `0`
