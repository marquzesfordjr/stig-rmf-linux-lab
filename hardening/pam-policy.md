# Password Policy

- Control: IA-5
Complexity:

minlen = 14

minclass = 4

maxrepeat = 3

Expiration:

PASS_MAX_DAYS 60

PASS_MIN_DAYS 1

PASS_WARN_AGE 7


- Control: AC-7
Account Lockout:

deny=5

unlock_time=900
