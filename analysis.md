# Password Security Analysis

## Best Practices Learned
- Use **12+ characters** for stronger resistance.
- Mix **uppercase, lowercase, numbers, and symbols**.
- Avoid dictionary words and predictable substitutions.
- Prefer **random strings** or **passphrases**.
- Do not reuse passwords across accounts.

## Password Cracking Techniques
- **Brute Force** → Tries all combinations; strong passwords resist due to length and complexity.
- **Dictionary Attack** → Uses wordlists like SecLists; weak passwords fall quickly.
- **Hybrid Attack** → Combines dictionary words with substitutions (e.g., P@ssw0rd).
- **Credential Stuffing** → Exploits leaked credentials from breaches.
- **Rainbow Tables** → Precomputed hash lookups for faster cracking.

## SecLists
- SecLists is a popular open-source repository of wordlists used in security testing.
- It includes password lists, usernames, fuzzing payloads, and sensitive data patterns.
- Repo: https://github.com/danielmiessler/SecLists

## Conclusion
Password complexity directly affects security.  
- Weak passwords are cracked in seconds.  
- Medium passwords resist casual attacks but remain vulnerable.  
- Strong and very strong passwords are practically impossible to brute force within a reasonable time.
