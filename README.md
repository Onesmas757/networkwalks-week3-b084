
# Networkwalks Academy – Week 3 Cybersecurity Projects

## Overview

This repository documents my Week 3 practical cybersecurity projects under Networkwalks Cyber & AI Solutions.

The projects focused on understanding password security, password hash extraction, password recovery and the practical use of cybersecurity tools.

## Learning Objectives

- Understand password hashing and encryption.
- Extract password hashes from protected PDF files.
- Use John the Ripper (JTR) for password recovery.
- Use Networkwalks Hash Calculator and Password Cracker.
- Explore AI-assisted security testing using Claude Desktop and HexStrike MCP.
- Understand the importance of strong passwords and secure authentication.

## Project Modules

### 1. Password Cracking with John the Ripper (JTR)

**Tools used:**
- John the Ripper
- Linux terminal
- PDF hash extraction
- Wordlists

**Practical workflow:**

1. Obtained the authorized lab PDF.
2. Extracted its password hash.
3. Saved the hash in a text file.
4. Loaded the hash into John the Ripper.
5. Executed the password recovery process.
6. Verified the result using John the Ripper's show command.

**Commands used:**

```bash
cat hash1.txt
john hash1.txt
john --show hash1.txt
```

**Result:** John the Ripper successfully recovered the lab password.

### 2. Password Cracking with Networkwalks Tools

**Tools used:**
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web browser

**Practical workflow:**

1. Opened the Networkwalks Hash Calculator.
2. Uploaded the authorized password-protected PDF.
3. Extracted the PDF hash.
4. Copied the complete hash.
5. Opened the Networkwalks Password Cracker.
6. Submitted the hash for testing.
7. Retrieved the successful result.
8. Verified access to the protected lab PDF.

**Result:** Successfully completed the password recovery exercise and captured the assigned lab flags.

### 3. AI-Assisted Password Recovery (Additional Practice)

**Tools explored:**
- Claude Desktop
- HexStrike MCP
- John the Ripper
- rockyou.txt wordlist

The additional practical exercises explored how AI-assisted workflows can interact with cybersecurity tools to support authorized password security testing.

The exercises included:
- Setting up the HexStrike MCP environment.
- Connecting Claude Desktop to the MCP server.
- Checking the availability of John the Ripper.
- Extracting PDF password hashes.
- Running authorized password recovery tests.
- Reviewing the results.

**Result:** Successful recovery was reported for the two additional lab PDFs.

## Skills Acquired

- Linux command-line operations
- Password hash extraction
- Password security assessment
- John the Ripper
- Wordlist-based password testing
- AI-assisted cybersecurity workflows
- Basic MCP integration concepts
- Technical documentation and evidence management

## Lessons Learned

This practical demonstrated that weak and predictable passwords can be recovered through dictionary-based attacks.

It reinforced the importance of:
- Using long, unique passwords.
- Avoiding common dictionary words.
- Implementing secure password storage.
- Understanding the risks of weak authentication.
- Conducting security testing only with proper authorization.

## Scope and Ethical Considerations

All activities documented here relate to authorized training exercises and designated lab materials.

The techniques are intended for cybersecurity education and defensive security assessments, not unauthorized access.

## Acknowledgements

Special appreciation to Networkwalks Cyber & AI Solutions and the instructors for providing practical learning resources and hands-on cybersecurity challenges.

**Batch:** B084  
**Project:** Week 3  
**Focus:** Password Cracking and Cybersecurity Tools

---

*This repository serves as my learning record and practical evidence of the Week 3 cybersecurity projects.*

