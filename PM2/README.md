
# PM1 – Password Cracking with John the Ripper

## Objective
Perform an authorized PDF password auditing exercise using John the Ripper.

## Environment
- Operating System: Kali Linux
- Password Auditing Tool: John the Ripper
- Hash Extraction: pdf2john
- Wordlist: RockYou

## Practical Steps

1. Prepared the working directory in Kali Linux.
2. Extracted the PDF password hash using pdf2john.
3. Prepared the extracted hash for John the Ripper.
4. Executed a dictionary attack using the RockYou wordlist.
5. Retrieved the recovered password using John's show option.
6. Verified the result by opening the protected PDF.

## Commands Used

```bash
perl /usr/share/john/pdf2john.pl "My Locked PDF1.pdf" > hash1.txt

awk -F: '{print $2}' hash1.txt > hash_clean.txt

john --format=pdf --wordlist=/usr/share/wordlists/rockyou.txt hash_clean.txt

john --show --format=pdf hash_clean.txt
```

## Result

Successfully recovered the PDF password and accessed the protected document.

## Learning Outcomes

- PDF password hash extraction
- Dictionary-based password attacks
- John the Ripper usage
- Password auditing and verification

## Evidence

See the evidence folder for redacted screenshots of the practical steps.

