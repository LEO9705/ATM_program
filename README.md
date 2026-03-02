# Simple ATM Program (C++)

## What it does
A console-based ATM simulator that lets the user:
- check the current balance
- deposit money
- withdraw money (with insufficient-funds protection)
The program runs in a menu loop until the user chooses Exit.

## What I learned
I practiced breaking a program into functions (`showBalance`, `deposit`, `withdraw`) and using a `do-while` menu loop with a `switch` statement. I also learned how to format currency output using `iomanip` (`fixed` and `setprecision(2)`).

## Requirements
A C++ compiler (`g++` or `clang++`)

## How to run (macOS / Linux)
```bash
g++ main.cpp -o app
./app
```
## Command Prompt
```bash
app.exe
```
## PowerShell
```bash
.\app.exe
```

## Next improvements
- Validate non-integer input (prevent crashes when the user types letters)
- Prevent negative deposits/withdrawals more robustly
- Add a transaction history (optional)
