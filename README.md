# NETWORKWALKS-AYODELE-B083-WK3-PM1-2-PASSWORD-CRACKING-WITH-JTR-AND-NW-TOOLS

# Password Cracking: Penetration Testing Project

**Pentester:** Samuel Ayodele (Haywhy0x)   
**Program:** Networkwalks, Cybersecurity  
**Date:** 26 September 2026  


## Overview
This project covers the password cracking phase of a penetration test. The goal was to recover passwords from locked files using their hash values, done with John the Ripper and the Networkwalks lab tools.

## Scope and Authorization
Only test systems and files you own or have written permission to test. These files were provided as part of an authorized educational cybersecurity lab.

## Tool Used
John the Ripper, alongside the Networkwalks lab tools/files provided for this exercise.

## Methodology and Findings

### File 1
- **Hash value:** 

![hash](01-locked%20file%201%20hash%20value.png)


- **Command:** <!-- e.g. john --format=... hash1.txt -->
- **Cracked password:** 

![cracked password](01-cracked%20password.png)


- **Flag captured:** 

![flag](01-flag%20captured.png)



### File 2
- **Hash value:** 

![hash](02-locked%20file%202%20hash%20value.png)


- **Command:** <!-- ... -->
- **Cracked password:** 

![cracked password](02-cracked%20password.png)


- **Flag captured:** 

![flag](02-flag%20captured.png)



### File 3
- **Hash value:** 

![hash](03-locked%20file%203%20hash%20value.png)


- **Command:** <!-- ... -->
- **Cracked password:** 

![cracked password](03-cracked%20pasword.png)


- **Flag captured:** 

![flag](03-flag%20captured.png)



## Recommendations
- Use long, random passwords instead of common words or patterns.
- Use a strong hashing algorithm (bcrypt, Argon2) rather than a weak or unsalted one.
- Enable account lockout or rate limiting after repeated failed attempts.

## Conclusion
This project gave me hands-on practice cracking passwords from hash values using John the Ripper. I recovered the passwords for all three locked files and captured their flags. This showed me how weak passwords and hashing methods can be broken quickly with the right tool, and why strong passwords and modern hashing algorithms matter.

## Disclaimer
This work was done for educational purposes on files provided for an authorized lab.
