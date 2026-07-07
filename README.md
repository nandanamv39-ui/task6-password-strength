# Task 6 - Create a Strong Password and Evaluate Its Strength

## Objective
Understand what makes a password strong by testing several passwords of varying complexity against an online password strength checker.

## Tool used
[passwordmeter.com](https://www.passwordmeter.com)

## Passwords tested

| Password | Length | Score | Feedback |
|---|---|---|---|
| `aNu@2006` | 8 | Weak | Under 12 characters; contains a date pattern (2006), which is easily guessed |
| `aB12dos@260` | 11 | Fair | Uses all four character types, but still under the 12-character minimum |
| `night_furry_09!` | 16 | Strong | Good length, special characters add strength, no common patterns detected |
| `mdh#DFkuFhk344hjG` | 18 | Very Strong | Excellent length, uses all four character types, no common patterns, estimated crack time over a trillion years |

## Observations
- **Length matters more than complexity.** The 18-character random password and the 16-character passphrase both scored much higher than the shorter passwords, even though the short ones also mixed character types.
- **Predictable patterns weaken a password.** Adding a birth year or date (like `2006`) is flagged immediately, since attackers commonly try dates first.
- **Character variety still helps**, but only once the password is long enough — a short password with symbols and numbers can still be weak.
- **Crack time estimates jump dramatically with length**: from under a year for the weak password to over a trillion years for the strongest one.

## Common password attacks
- **Brute force**: systematically trying every possible character combination until the correct one is found. Longer passwords make
