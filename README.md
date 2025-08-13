# password_strength_evaluation
# 🔐 Password Strength Evaluation — GitHub Repository

## 1. Objective & Scope
The aim of this project is to **understand what makes a password strong**, evaluate passwords of varying complexity using **online password strength tools**, and document the results. This includes:
- Testing multiple passwords with different complexity levels.
- Recording scores, classifications, and tool feedback.
- Analyzing results to identify best practices for password creation

## 2. Methodology
- **Password Creation**
  - Over 20 dummy passwords created with varying lengths (6–20+ chars) and complexity levels.
  - Included weak passwords (dictionary words, sequences) and strong ones (random strings, long passphrases).
- **Tools Used**
  - Primary: [passwordmeter.com](https://passwordmeter.com)
  - Secondary: Additional online strength checkers.
- **Process**
  1. Input password into checker.
  2. Record score, classification, and tool feedback.
  3. Take screenshots for evidence.
- **Documentation**
  - Scores stored in `results_template.csv`.
  - Screenshots saved in `/screenshots/passwordmeter/`.

## 3. Results Summary (from Screenshots)
| ID | Password Example | Length | Score | Classification | Feedback |
|----|------------------|--------|-------|----------------|----------|
| 01 | devender | 8 | 8% | Very Weak | only lowercase |
| 02 | dev@123 | 7 | 49% | good | Add uppercase letters and symbols |
| 03 | Dev!@0508@! | 11 | 100% | Strong | Good mix of characters |
| 04 | devender12345 | 13 | 58% | good | Common sequence |

## 4. Key Findings
- **Length Matters** — Above 12 characters gives a clear boost.
- **Character Variety** — Uppercase, lowercase, numbers, and symbols improve scores.
- **Avoid Patterns** — Sequences and dictionary words are easy to crack.
- **Passphrases Work** — Long, uncommon word combinations are strong.
- **Randomness is King** — Truly random passwords are the hardest to crack.

## 5. Tips for Strong Passwords
1. Use **12–16+ characters**.
2. Mix **upper, lower, numbers, symbols**.
3. Avoid dictionary words, birthdays, and predictable substitutions.
4. Create **unique passwords** for each account.
5. Use a **password manager**.

## 6. Common Password Attacks
- **Brute Force** — Tests all combinations; length and complexity slow it down.
- **Dictionary Attack** — Uses common words; effective against weak passwords.
- **Hybrid Attack** — Mix of dictionary and small variations.
- **Credential Stuffing** — Uses leaked passwords from breaches.

## 7. Complexity vs Security
- 8 lowercase-only chars: **26^8** possibilities.
- 8 chars (upper/lower/number/symbol): **95^8** possibilities.
- Adding characters increases complexity exponentially.

---
**🔗 [View Screenshots Folder](./screenshots/passwordmeter)**
```
