Phishing (notes)

Phishing = social engineering attack to trick users into giving sensitive data (credentials, financial info, etc.)

Common types:

Email phishing (mass emails with malicious links/attachments)
Spear phishing (targeted attack)
Smishing (SMS)
Vishing (phone calls)

Indicators:

Suspicious sender/domain (typos, lookalike domains)
Mismatch between link text and actual URL
Urgent language (account suspension, security alert)
Unexpected attachments (.exe, .zip, .html)

SOC perspective:

Check email headers (SPF, DKIM, DMARC)
Analyze URLs (domain reputation, sandbox if needed)
Investigate attachments (hash, VirusTotal, sandbox)
Look for similar emails across users (possible campaign)

Mitigation:

User awareness training
Email filtering rules
Blocking domains/IPs
MFA reduces impact of credential theft
