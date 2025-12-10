# Phishing-email-analysis-report
This repository contains a detailed analysis of a sample phishing email. The project identifies and explains common phishing indicators using a publicly available scam email example. The analysis includes:  Examination of the sender’s email address for spoofing   Identification of suspicious attachments and content  Detection of urgency or  threats

Objective ; 
To analyze a suspicious email and identify red flags commonly found in phishing attempts.

*Steps Performed

1] Collected a publicly available phishing email sample.

2] Examined the sender’s email address for spoofing.

3] Analyzed email headers using an online header analyzer.

4] Identified suspicious links or attachments inside the email.

5] Looked for urgent or threatening language used to pressure the recipient.

6] Checked for mismatched URLs by hovering over any links.

7] Verified the presence of spelling and grammar errors.

8] Summarized all phishing traits observed.

*Findings (Based on Sample Email Provided)

1. Sender Address Spoofing ; Display name claims to be “App Store”, but the real email is from
                             billingservice-info0033@refundsubsweb.com — an unrelated and suspicious domain.
                             Apple only sends emails from official domains such as @apple.com.

2. Header Observations ; Instead of routing through Apple mail servers, the sender domain is unrelated.
                         In a real header analysis, SPF/DKIM/DMARC would likely fail for this domain.

3. Suspicious Attachment ; The email contains Invoice.pdf (187 KB).
                           Legitimate Apple invoices appear inside the email or Apple ID portal — not as attachments.
                           Attachments in phishing emails often contain malware or fake login pages.

4. Urgent/Threatening Language ; Subject claims a payment was “Dispatched,” creating panic.
                                 Fake purchase details (Mobile Legends Diamonds) are used to scare the user into reacting quickly.

5. Mismatched or Missing URLs ; The sample contained no direct links, only an attachment.
                                This can be a tactic to force users to open the malicious file.

6. Spelling & Grammar Errors ; Incorrect sentences such as: “This is the details of your activity”
                                                             “mobile legend App”
                                                             Inconsistent capitalization and poor formatting not typical of Apple emails.

7. Summary of Phishing Traits ; Fake sender identity
                                Suspicious, non-Apple domain
                                Urgency and scare tactics
                                Malicious PDF attachment
                                Grammar and spelling mistakes
                                Generic greeting (“Dear Customer”)
                                Attempt to imitate Apple branding
