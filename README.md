# Password Strength Test

This is a simple password strength test. It checks for length, the presence of uppercase and lowercase characters, numbers, and special characters. It also checks for the presence of repeated characters.

## How to Run

1. Clone the repository.
2. Open the project in a modern browser.

## How it Works

The password strength is calculated based on the number of weaknesses in the password. The password weaknesses are:

- Length: The password is too short (deduction: 40) or could be longer (deduction: 15).
- Uppercase characters: The password has no uppercase characters (deduction: 20) or could use more (deduction: 5).
- Lowercase characters: The password has no lowercase characters (deduction: 20) or could use more (deduction: 5).
- Numbers: The password has no numbers (deduction: 20) or could use more (deduction: 5).
- Special characters: The password has no special characters (deduction: 20) or could use more (deduction: 5).
- Repeated characters: The password has repeated characters (deduction: 10 for each repetition).

The strength of the password is then deducted for each weakness. The resulting strength is then used to set the width of the strength meter.
