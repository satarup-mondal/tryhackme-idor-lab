# TryHackMe - Neighbour (IDOR)

## Objective
Exploit an IDOR vulnerability to access another user's profile and obtain the flag.

## Vulnerability
IDOR (Insecure Direct Object Reference)

## Steps Performed
1. Logged in using guest account
2. Observed URL parameter:
   profile.php?user=guest
3. Modified parameter:
   guest -> admin
4. Accessed admin profile and retrieved flag

## What I Learned
- How IDOR vulnerabilities work
- Importance of authorization checks
- URL parameter manipulation
- Basic web enumeration mindset

## Tools Used
- Browser
- TryHackMe AttackBox

## Platform
TryHackMe 


<img width="1920" height="1033" alt="Screenshot From 2026-05-20 17-53-46 (Edited)" src="https://github.com/user-attachments/assets/be173c6a-3e2c-4c8f-9e9a-e94c0ce727fd" /> 



<img width="1536" height="1024" alt="ChatGPT Image May 20, 2026, 06_10_30 PM" src="https://github.com/user-attachments/assets/cb18ed1e-8200-414e-92bb-73fa81dd65d5" />


