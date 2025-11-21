# 🔑 Password Security Analysis

## Best Practices Learned
- Use **12+ characters** for stronger resistance.
- Mix **uppercase, lowercase, numbers, and symbols**.
- Avoid dictionary words and predictable substitutions.
- Prefer **random strings** or **passphrases**.
- Do not reuse passwords across accounts.

## Tips for Creating Secure Passwords
- **Length is strength** → Aim for 12–16 characters or more.
- **Diversity of characters** → Combine uppercase, lowercase, numbers, and special symbols.
- **Avoid personal info** → Do not use names, birthdays, phone numbers, or common phrases.
- **Randomness matters** → Avoid predictable substitutions like `P@ssw0rd`; use truly random strings.
- **Passphrases are powerful** → Use multiple unrelated words with symbols (e.g., `Blue_Tiger#99`).
- **Unique per account** → Never reuse the same password across different services.
- **Password managers help** → Generate and store strong, unique passwords securely.
- **Enable MFA** → Add multi-factor authentication for extra protection.

## Password Cracking Techniques
- **Brute Force** → Tries all combinations; strong passwords resist due to length and complexity.
- **Dictionary Attack** → Uses wordlists like SecLists; weak passwords fall quickly.
- **Hybrid Attack** → Combines dictionary words with substitutions (e.g., P@ssw0rd).
- **Credential Stuffing** → Exploits leaked credentials from breaches.
- **Rainbow Tables** → Precomputed hash lookups for faster cracking.

## SecLists
- SecLists is a popular open-source repository of wordlists used in security testing.
- It includes password lists, usernames, fuzzing payloads, and sensitive data patterns.
- Attackers use SecLists for dictionary and brute force attacks.
- Repo: [danielmiessler/SecLists](https://github.com/danielmiessler/SecLists)

## Conclusion
Password complexity directly affects security:  
- **Weak passwords** are cracked in seconds.  
- **Medium passwords** resist casual attacks but remain vulnerable.  
- **Strong and very strong passwords** are practically impossible to brute force within a reasonable time.  

Strong passwords combine **length, complexity, randomness, and uniqueness**.  
They are the first line of defense against brute force, dictionary, and hybrid attacks.
