# Credit Card Validator

A **C++ program** to validate credit card numbers using the **Luhn algorithm**. This tool checks whether a given credit card number is valid by performing a checksum calculation.

---

## 🚀 Features

- **Easy Input**: Enter a credit card number for validation.
- **Luhn Algorithm Implementation**: Validates credit card numbers efficiently.
- **Clear Output**: Displays whether the card is valid or invalid.

---

## 🛠 How It Works

1. **Odd Digits**: Add digits in odd positions (from the right) directly to the total.
2. **Even Digits**: Double the digits in even positions. If the result is two digits, sum them (e.g., `14 → 1 + 4 = 5`).
3. **Checksum**: Compute the sum of all processed digits.
4. **Validation**: If the total checksum is divisible by `10`, the card is valid.

---

## 🧾 Example

Enter a credit card number: `4532015112830366`

**output**:
4532015112830366 is valid
