# Password Evaluation Results

## Test 1: `Admin`
- **Score**: 19%
- **Complexity**: Very Weak
- ✅ Uppercase, lowercase
- ❌ No numbers, no symbols
- ❌ Too short
- 🛑 Easily cracked via dictionary attacks

## Test 2: `#Lo@ST002`
- **Score**: 98%
- **Complexity**: Very Strong
- ✅ Includes uppercase, lowercase, numbers, symbols
- ✅ No common sequences
- ✅ Meets all requirements

## Test 3: `#man_(8875)GoN**`
- **Score**: 100%
- **Complexity**: Very Strong
- ✅ High character diversity
- ✅ Long length (16+)
- ✅ No major deductions

---

## Password Security Tips

- Use **passphrases** (e.g., `Sky#9Rain!Tree@Sun`)
- Avoid personal info
- Never reuse passwords
- Use a password manager

## Attack Methods

| Type            | Description                                          |
|-----------------|------------------------------------------------------|
| Brute Force     | Tries all combinations                               |
| Dictionary      | Uses precompiled lists of common passwords/words     |
| Social Eng.     | Exploits personal info (pet names, birthdays, etc.)  |
| Keylogging      | Malware captures keystrokes                          |
| Credential Leak | Uses passwords from breached accounts                |
