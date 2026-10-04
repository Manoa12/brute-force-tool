# Brute Force Tool

Brute force tool that tests combinations (passwords, hashes, or credentials) until it finds the right one. Supports dictionary mode (wordlist) and/or combination generation.

🚧 **Work in progress** — core logic still being built, features may be incomplete or change.

## How it works

- Loads a wordlist or generates combinations
- Tests each attempt against the target (hash, login form, protected file...)
- Stops as soon as an attempt succeeds, or reports failure once the list is exhausted

## Usage

```bash
python brute_force.py --target <target> --wordlist <wordlist.txt>
```

## ⚠️ Disclaimer

Educational project — for use only on your own systems or with proper authorization.
