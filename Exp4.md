# Experment - 4:- Analyze Email Headers and Detect Email Spoofing Using MHA (Mail Header Analyzer)

## Aim
To analyze email headers and detect email spoofing using MHA (Mail Header Analyzer) for verifying the authenticity of emails and preventing phishing attacks.

## Description
MHA (Mail Header Analyzer) is a web-based tool that helps in examining the detailed headers of an email message to identify the path taken by the email, sender information, and potential signs of spoofing or forgery. Email headers contain metadata such as sender IP, mail servers involved, timestamps, and authentication results (SPF, DKIM, DMARC). Analyzing these headers helps in detecting if an email is legitimately sent or spoofed, which is crucial for email security and forensic investigations.

## Tools and Equipment Used
- **MHA (Mail Header Analyzer)**: Online or offline tool for analyzing email headers.
- **Email Client or Server**: Where the suspicious email is received.
- **Computer/Workstation**: Device with internet access (for online MHA) or with MHA installed.
- **Sample Email Header**: The header data extracted from the suspicious email.

## Procedure
1. **Extract Email Header**: Open the suspicious email and locate the full email header information using the email client’s options (e.g., "Show Original", "View Source").
![alt text](<Screen Shorts/Exp 4/Screenshot 2025-09-02 000507.png>)
2. **Copy the Email Header**: Select and copy the entire email header content.
![alt text](<Screen Shorts/Exp 4/Screenshot 2025-09-02 000532.png>)
3. **Open MHA Tool**: Access the Mail Header Analyzer tool either online via its website or offline if installed locally.
![alt text](<Screen Shorts/Exp 4/Screenshot 2025-09-02 000616.png>)
4. **Paste Email Header**: Paste the copied header information into the MHA input field.
![alt text](<Screen Shorts/Exp 4/Screenshot 2025-09-02 000927.png>)
5. **Analyze Header**: Submit the header data to MHA for analysis.
![alt text](<Screen Shorts/Exp 4/Screenshot 2025-09-02 001045.png>)
6. **Review Results**:
   - Check the received path and IP addresses of mail servers.
   - Verify SPF (Sender Policy Framework), DKIM (DomainKeys Identified Mail), and DMARC (Domain-based Message Authentication, Reporting, and Conformance) authentication status.
   - Identify any anomalies or signs of spoofing, such as forged sender IPs or mismatched domains.
![alt text](<Screen Shorts/Exp 4/Screenshot 2025-09-02 001212.png>)
7. **Document Findings**: Record analysis results including whether the email is legitimate or spoofed, and any suspicious patterns or indicators.
![alt text](<Screen Shorts/Exp 4/Screenshot 2025-09-02 001341.png>)
![alt text](<Screen Shorts/Exp 4/Screenshot 2025-09-02 001354.png>)
## Result
The email header is analyzed thoroughly, revealing the sending path and authentication results. The use of MHA successfully detects email spoofing attempts by highlighting discrepancies in sender information or failed authentication checks. This allows for informed decisions in handling potentially fraudulent emails.

