WRITE-UP 2: Phishing Emails in Action
Phishing Emails in Action – TryHackMe Write-Up
Room Overview

The Phishing Emails in Action room demonstrates realistic phishing attacks.
It shows how attackers:

Construct fake emails

Hide malicious URLs

Imitate official brands

Use psychological tricks (urgency, fear)

Steal credentials through fake login pages

This room simulates real attacker behavior so you can recognize phishing attempts in the wild.

1. Phishing Email Scenario Analysis

The room provides a sample phishing email such as:

Fake bank security alerts

Password reset messages

“Unusual login detected” warnings

Delivery failure notices

Fake internal company IT messages

What I Did

Read the entire email carefully.

Identified red flags:

Suspicious sender domain

Urgent message with threats

Generic greeting instead of my name

Poor grammar or formatting

Observed whether the email tried to create fear or urgency.

Typical Red Flags

“Your account will be locked in 24 hours!”

Company name spelled slightly incorrectly

Email sent from a free Gmail/Yahoo address

Fake support team claiming to be “Security Department”

2. Link & Website Inspection

Most phishing attacks rely on malicious URLs.

What I Did

Hovered over the link in the email to reveal the real URL.

Checked if:

The domain matched the company

There were spelling errors (e.g., paypa1.com)

The link redirected to another suspicious page

Noted if the link pointed to a login page meant to steal credentials.

Suspicious URL Patterns

Slight spelling changes:
micr0soft-support.com

Fake login pages:
security-update-login.net

Strange domain endings:
.xyz, .shop, .click

3. Attacker Goals & Tactics

Most phishing attackers aim to:

Steal usernames and passwords

Capture credit card info

Install malware via attachments

Gain access to company accounts

Trick victims into resetting their password

What I Observed

The phishing email often tries to:

Create urgency (“verify now!”)

Force quick action

Get the victim to click without thinking

Redirect the victim to a fake login website

This matches real-world phishing behavior.

Conclusion

From this room, I learned how phishing emails are constructed and delivered.
Key lessons include:

Attackers use urgency to pressure victims

Fake login pages often mimic popular services

Real URL always reveals the phishing attempt

Sender domain and branding tell you if the email is fake

Understanding attacker psychology helps in detecting scams
