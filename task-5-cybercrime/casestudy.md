# Case Study: The "Corporate Credential" Phishing Attack

**Phishing** is a deceptive cybercrime where attackers pose as legitimate institutions—such as banks, government agencies, or tech providers—to trick individuals into revealing sensitive information. This typically includes login credentials, credit card numbers, or personal identification data.

### How it Happens: Step-by-Step
In a typical scenario, the attack follows a calculated path:

1.  **The Bait:** The victim receives an email or SMS (Smishing) that mimics a trusted brand, such as a major bank or a cloud service provider. The message usually employs **social engineering** to create a sense of urgency, claiming "unauthorized login attempts" or "immediate account suspension."
2.  **The Hook:** The message contains a call-to-action link to a "secure verification portal." This website is a pixel-perfect clone of the legitimate site but is actually hosted on a malicious server controlled by the attacker.
3.  **The Catch:** The victim, feeling pressured, enters their username, password, and sometimes a one-time password (OTP). The attacker captures these credentials in real-time using a "Man-in-the-Middle" (MitM) framework.
4.  **The Payload:** Once the attacker has access, they may drain bank accounts, steal identity documents, or use the compromised account to launch further "lateral" attacks on the victim's professional contacts.

### Targets and Consequences
While anyone with an internet connection is a potential target, attackers often focus on **employees in finance departments** or **elderly users** who may be less familiar with modern digital security cues.

The consequences are often severe. For individuals, it leads to **direct financial loss** and the exhausting process of identity restoration. For businesses, a single phished credential can result in a massive **data breach**, leading to regulatory fines (like GDPR or HIPAA), legal action, and a permanent loss of consumer trust. According to the *IBM Cost of a Data Breach Report*, phishing remains one of the most expensive initial attack vectors due to the time required to detect the intrusion.
