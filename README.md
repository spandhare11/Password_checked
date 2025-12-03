**Password Strength Checker**

A simple, client-side Password Strength Checker built with HTML, CSS, and JavaScript. Type a password into the input and the page shows a numeric score (0.0–10.0), a strength label, and — if the password is Weak or Medium — a suggested stronger password derived by adding missing character types.

**Features**

1. Real-time password scoring (0.0–10.0)

2. Strength categories: Weak, Medium, Strong, Excellent

3. Suggested stronger password (appends characters to the original password when score < 6)

4. Clean, responsive UI using the Lato font

**How score is calculated**

The checker awards points for four core properties. Each satisfied property contributes 2.5 points, for a maximum score of 10.0.

Length ≥ 8 characters → +2.5 points

Mixed case (both lowercase and uppercase letters present) → +2.5 points

Contains digit(s) → +2.5 points

Contains special character(s) (non-alphanumeric) → +2.5 points

**Score ranges and categories**

0.0 – 2.9 → Weak

3.0 – 5.9 → Medium

6.0 – 8.9 → Strong

9.0 – 10.0 → Excellent

**How suggestions are generated**

If the password is Weak or Medium (score < 6.0), the app generates a suggested stronger password by appending missing elements in this order:

Append a lowercase letter (a) if none present

Append an uppercase letter (A) if none present

Append a digit (1) if none present

Append a special character (!) if none present

If the result is still shorter than 8 characters, append x characters until length ≥ 8

**Contact**

If you want improvements or help deploying, open an issue or contact me via the repository. Happy hacking! 🚀

