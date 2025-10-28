# 🔐 Password Strength Evaluation – Task 6  
**By:** Vivek Agrawal  
**Date:** October 27, 2025  
**Tool Used:** Bitwarden, PasswordMeter, Security.org Password Checker  
**Environment:** Kali Linux  

---

## 🎯 Objective
To understand what makes a password strong by creating multiple passwords of varying complexity, testing them using online password strength tools, and interpreting how structure, randomness, and diversity affect password security.

---

## 🧠 Methodology
1. Created **five passwords** with increasing levels of complexity.  
2. Tested each password on the following platforms:  
   - [Bitwarden Password Strength Checker](https://bitwarden.com/password-strength/)  
   - [Password Meter](https://passwordmeter.com/)  
   - [Security.org Password Strength Test](https://www.security.org/how-secure-is-my-password/)  
3. Recorded the **ratings** and **estimated crack times**.  
4. Compared results and derived best practices for strong password creation.

---

## 🔢 Passwords Tested and Observations

| No. | Password | Bitwarden Rating | PasswordMeter Rating | Estimated Crack Time | Observation |
|:--:|:--|:--|:--|:--|:--|
| 1 | `sunshine12` | Weak | Very Weak (37%) | <1 day | Common word + short length + no symbols |
| 2 | `SkyBlue2025` | Moderate | Weak (91%) | 41 years | Mixed case + digits, but predictable |
| 3 | `S!ky_Blue2025` | Strong | Good (100%) | 2 million years | Added symbol + underscore increased entropy |
| 4 | `T!ger$Run_47#Fast` | Very Strong | Strong (100%) | 93 trillion years | Long, mixed, random pattern |
| 5 | `!9AqX$7rZ&vLp#T2nK` | Strong | Strong (100%) | 7 quadrillion years | High entropy, randomly generated string |

---

## 📊 Findings
- **Length** significantly increases resistance to brute-force attacks.  
- **Character diversity** (upper/lowercase, numbers, symbols) raises entropy and unpredictability.  
- **Dictionary words** or common phrases drastically reduce security.  
- **Random strings** achieve maximum strength but are hard to memorize.  
- **Passphrases** (e.g., `Coffee$Mountain!River_2025`) balance strength and memorability.  

---

## ⚔️ Common Password Attacks

| Attack Type | Description | Example |
|:--|:--|:--|
| **Brute Force** | Tries all possible character combinations until a match is found. | aaaa → zzzz |
| **Dictionary Attack** | Uses precompiled wordlists of common passwords. | password, qwerty |
| **Phishing** | Tricks users into revealing credentials via fake websites or emails. | Fake login portals |
| **Credential Stuffing** | Reuses stolen credentials from other data breaches. | Leaked account reuse |

---

## 💡 Best Practices for Strong Passwords
1. Use at least **12–16 characters**.  
2. Combine **uppercase, lowercase, numbers, and symbols**.  
3. Avoid **personal information** (names, birthdays, etc.).  
4. Create **unique passwords** for every account.  
5. Prefer **random passphrases** made of unrelated words.  
6. Enable **Multi-Factor Authentication (MFA)** whenever possible.  
7. Use a **password manager** like **Bitwarden** or **1Password** for secure storage.  

---

## 📁 Deliverables
- `PasswordStrengthAnalysis.pdf` — detailed analysis report.  
- `README.md` — summary of observations and findings.  
- `/screenshots/` — captured images from testing tools.  

---

## 🧾 Conclusion
The password strength evaluation demonstrates that **length, complexity, and randomness** are the main factors determining a password’s security.  
Short or predictable passwords are easily compromised, whereas long and randomized ones resist cracking attempts for millennia.  
By adopting strong password habits and enabling MFA, users can drastically improve their protection against unauthorized access and cyberattacks.

---

> ✨ *Prepared by Vivek Agrawal as part of the Cybersecurity Internship — Password Strength Evaluation Task 6 (October 2025).*
