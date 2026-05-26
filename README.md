# Password Strength Checker

A simple Python-based Password Strength Checker that evaluates password security using multiple validation rules.

## Features

- Checks minimum password length
- Detects uppercase letters
- Detects lowercase letters
- Detects digits
- Detects special characters
- Interactive command-line interface

## Technologies Used

- Python 3
- Regular Expressions (`re` module)

## Project Structure

```bash
password-strength-checker/
│
├── main.py
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
```

## Installation

Clone the repository:

```bash
git clone https://github.com/hardevdagur03-wq/password-strength-checker.git
```

Navigate to the project folder:

```bash
cd password-strength-checker
```

Run the program:

```bash
python main.py
```

## Example Output

```bash
=== Password Strength Checker ===

Enter password: Hello123

Medium Password: Add special characters for better security.
```

## Password Validation Rules

| Rule | Requirement |
|------|-------------|
| Length | Minimum 8 characters |
| Uppercase | At least one uppercase letter |
| Lowercase | At least one lowercase letter |
| Digit | At least one number |
| Special Character | At least one special symbol |

## Future Improvements

- GUI version using Tkinter
- Password entropy calculation
- Password generator
- Dark web breach API integration
- Web version using Flask

## Author

Hardev Dagur

## License

This project is licensed under the MIT License.
