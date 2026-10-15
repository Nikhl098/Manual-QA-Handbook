# Test Design Techniques Cheat Sheet

## Equivalence partitioning
Split inputs into groups that behave the same, test one value per group.
Age field accepts 18 to 60:
- Invalid low: below 18 (test 10)
- Valid: 18 to 60 (test 35)
- Invalid high: above 60 (test 75)

## Boundary value analysis
Test at and next to each edge.
Same field: 17, 18, 19, 59, 60, 61.

## Decision table
| Condition | R1 | R2 | R3 | R4 |
|---|---|---|---|---|
| Valid username | Y | Y | N | N |
| Valid password | Y | N | Y | N |
| Action | Login | Error | Error | Error |

## State transition
Example: login with a limit of 3 attempts.
Logged out, attempt 1 fails, attempt 2 fails, attempt 3 fails, Locked.

## Error guessing
Empty input, spaces only, very long text, special characters, past or future dates, zero, negative numbers, duplicates.
