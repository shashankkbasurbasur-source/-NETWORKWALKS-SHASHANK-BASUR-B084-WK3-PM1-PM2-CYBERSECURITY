
# Networkwalks Cybersecurity Internship – Week 3

## Password Security and Auditing

This repository documents the practical exercises completed during Week 3 of my Cybersecurity Internship at Networkwalks.

The week's activities focused on PDF password hash extraction, dictionary-based password attacks, password recovery, and practical usage of password auditing tools.

## Practical Modules

### PM1 – Password Cracking with John the Ripper

**Objective:** Perform password auditing on a password-protected PDF using John the Ripper.

**Tools and Environment:**
- Kali Linux
- John the Ripper
- pdf2john
- RockYou Wordlist

**Tasks Performed:**
1. Prepared the Kali Linux environment and working directory.
2. Extracted the password hash from the protected PDF using pdf2john.
3. Prepared the extracted hash in a format suitable for John the Ripper.
4. Performed a dictionary attack using the RockYou wordlist.
5. Retrieved the recovered password using John the Ripper.
6. Verified the recovered password by opening the protected PDF.
7. Successfully captured the training flag.

**Key Concepts:**
- PDF password hash extraction
- Dictionary attacks
- Password auditing
- Wordlist-based password recovery

### PM2 – Password Cracking with Networkwalks Tools

**Objective:** Perform PDF password recovery using Networkwalks online tools.

**Tools Used:**
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Firefox
- Kali Linux

**Tasks Performed:**
1. Downloaded the password-protected PDF provided for the practical.
2. Uploaded the PDF to the Networkwalks Hash Calculator.
3. Extracted and copied the PDF password hash.
4. Submitted the extracted hash to the Networkwalks Password Cracker.
5. Retrieved the recovered password.
6. Verified access by opening the protected PDF.
7. Successfully captured the training flag.

**Key Concepts:**
- Hash extraction
- Password auditing tools
- Dictionary-based password recovery
- PDF password security

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Kali Linux | Practical testing environment |
| John the Ripper | Password auditing and recovery |
| pdf2john | PDF password hash extraction |
| RockYou | Dictionary wordlist |
| Networkwalks Hash Calculator | Online hash extraction |
| Networkwalks Password Cracker | Online password recovery |
| Firefox | Accessing online tools |

## Learning Outcomes

Through these practical exercises, I gained hands-on experience in:

- Understanding how password-protected PDF files store password verification data.
- Extracting password hashes for security auditing.
- Using John the Ripper for dictionary-based attacks.
- Working with wordlists during password auditing.
- Exploring online password auditing tools.
- Understanding the importance of strong and unique passwords.
- Comparing command-line and web-based password auditing workflows.

## Repository Structure

```text
networkwalks-week3-password-cracking/
│
├── README.md
│
├── PM1-John-the-Ripper/
│   ├── README.md
│   └── evidence/
│
└── PM2-Networkwalks-Tools/
    ├── README.md
    └── evidence/
```

## Practical Results

Both mandatory practical modules were completed successfully.

- PM1: PDF password recovery using John the Ripper.
- PM2: PDF password recovery using Networkwalks tools.
- Both exercises: Successfully verified PDF access and captured the respective training flags.

## Disclaimer

All activities documented in this repository were performed within the authorized Networkwalks internship training environment for educational purposes.

Protected PDF files, recovered passwords, raw password hashes, and confidential training materials are excluded from this public repository.

---

**Internship:** Networkwalks Cybersecurity Internship  
**Week:** 03  
**Focus Area:** Password Security and Auditing
