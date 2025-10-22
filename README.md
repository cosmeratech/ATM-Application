# ATM Console Application

A simple C++ console-based ATM simulation to check balance, deposit, and withdraw funds.

## Features
- Check balance
- Deposit money
- Withdraw money with insufficient-funds check
- Clear-screen between actions (Windows `cls`)

## Requirements
- Windows (uses `system("cls")` and `system("pause>0")`)
- C++ compiler (e.g., MinGW g++)

## Build
Compile from PowerShell:

```bash
g++ -std=c++17 -O2 -o ATMApplication.exe ATMApplication.cpp
```

## Run
```bash
./ATMApplication.exe
```

## Usage
1. Choose an option from the menu:
   - 1: Show current balance
   - 2: Enter an amount to deposit
   - 3: Enter an amount to withdraw (must not exceed balance)
   - 4: Exit
2. The app clears the screen after each selection and pauses before exit.

## Notes
- Initial balance is 500.
- Input is read from standard input; non-numeric input is not validated.

## License
MIT


