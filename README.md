# Cowrie SSH Honeypot

Cowrie is a medium-interaction SSH honeypot designed to log brute force attacks and shell interactions.

## Features:
Captures unauthorized SSH login attempts 
Records attack logs in JSON format 
Logs SSH fingerprinting attempts 

## Example of Attack Log:
```bash
cat ~/cowrie-git/logs/cowrie.log | tail -n 10
