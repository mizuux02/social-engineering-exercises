 WRITE-UP 1: Phishing Analysis Fundamentals
 Phishing Analysis Fundamentals – TryHackMe Write-Up
 Room Overview

The Phishing Analysis Fundamentals room teaches you how to analyze suspicious emails by focusing on:

Email headers

Spoofing detection

Authentication checks (SPF, DKIM)

Email body red flags

Suspicious URLs

Dangerous attachments

This room is fully theory based you only analyze information that is already provided.

1. Email Header Analysis

Email headers contain hidden metadata that reveals:

The real sender

The server path the email traveled

Whether the email was spoofed

Whether security checks passed/failed

Important Header Fields

From: → Who claims to send the email

Return-Path: → Where the email actually came from

Received: → All servers involved

SPF: → Verifies sender’s mail server

DKIM: → Verifies message integrity

What I Did

Viewed the complete header block provided in the room.

Compared the From and Return-Path domains to detect spoofing.

Checked the Received lines for unknown or suspicious servers.

Looked at SPF/DKIM results to determine legitimacy.

Common Findings

Sometimes the sender domain does not match the real sending server.

SPF or DKIM may fail, signaling a spoofed or malicious email.

Mail routing sometimes shows unusual foreign servers.

2. Email Body Analysis

Attackers often include:

Fake security warnings

Threatening account alerts

Suspicious links

Malicious attachments

What I Did

Viewed the email body preview.

Hovered over the clickable link to see the actual URL.

Inspected attachment names and file types.

Identified typical phishing indicators such as:

Urgent language

Grammar/spelling mistakes

Unfamiliar “support team” names

Fake branding or logo

3. Suspicious Links & Attachments
Links

The displayed link may look safe, but the hovered link often points to a malicious site.

I checked for mismatched domains or odd TLDs 

Attachments

Dangerous formats include: .html, .htm, .zip, .docm, .exe

These often contain credential harvesters or malware.

Conclusion

From this room, I learned how to thoroughly analyze phishing emails by examining both headers and body content.
Key lessons include:

SPF/DKIM failures indicate spoofing

Sender identity must always be verified

Links often hide malicious websites

Attachments are common malware delivery methods

Urgent or emotional wording is a strong phishing indicator

This room helped build a strong foundation for detecting fraudulent emails and understanding attacker tactics.
