# Bad-USB-ducky-scripts
⚠️ SECURITY RESEARCH & EDUCATIONAL PURPOSES ONLY ⚠️

This repository contains BadUSB/Ducky Script payloads designed for authorized security testing, penetration testing, and vulnerability research. 

These scripts demonstrate USB attack vectors that systems administrators should test against THEIR OWN equipment with explicit written authorization.

---

📁 PAYLOADS INCLUDED:

1. **windows-password-reset.ducky**
   - it contains 4 files, as it's a complicated proccess, instructions are provided
   - Demonstrates local Windows credential bypass techniques
   - Useful for testing physical security controls
   - Recovery scenarios for lost credentials (authorized users only)

2. **chrome-password-viewer.ducky**
   - opens the devices chrome browser and displays it's stored passwords and th owners personal information
   - Extracts stored browser credentials from Chrome profiles
   - Tests whether password managers are being used appropriately
   - Highlights risks of storing credentials in browsers

3. **pin-bruteforce.ducky**
   - it first tries the 30 most popular 4 number codes and then moves on to try every single combiantion
   - Demonstrates PIN code brute-force methodology
   - Shows limitations of short PIN security requirements
   - Can inform policy decisions on lockout mechanisms

---

⚖️ LEGAL DISCLAIMER:

- Use ONLY on systems you own or have explicit written permission to test
- Unauthorized access to computer systems is illegal in most jurisdictions
- Author assumes all responsibility for how these tools are utilized
- This content is for DEFENSIVE security education only
- Do not use for malicious purposes, theft, or unauthorized access

---

🔒 RECOMMENDED USE CASES:

✅ Physical security assessments (with authorization)
✅ Red team exercises (engagement scoped)
✅ Self-testing owned hardware
✅ Security awareness training demonstrations
✅ Vulnerability research and defense development

❌ PROHIBITED USE:

✗ Accessing systems without permission
✗ Stealing credentials or data
✗ Circumventing security controls you don't own
✗ Any criminal activity

---

🛡️ DEFENSE RECOMMENDATIONS:

Organizations should:
- Disable USB ports or restrict to approved devices via Group Policy
- Enable full disk encryption (BitLocker/FileVault)
- Implement device control solutions
- Monitor for unauthorized HID device connections
- Require strong authentication beyond 4-digit PINs

---

License: MIT (Educational/Research Use Only)
Contact: [your contact]
Disclaimer: No warranty provided; use at your own risk
