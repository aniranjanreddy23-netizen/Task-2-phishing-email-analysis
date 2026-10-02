# Task 2: Phishing Email Analysis

## Objective

The objective of this task is to identify phishing characteristics
in a suspicious email sample.

## Phishing Indicators Found

### 1. Suspicious Sender Address

The sender address uses a suspicious look-alike domain:

`security-alert@m1crosoft-support.example`

The word `m1crosoft` uses the number `1` instead of the letter `i`.

### 2. Urgent Language

The email uses urgent phrases such as:

- URGENT
- within 24 hours
- immediately

This creates pressure on the recipient to act quickly.

### 3. Threatening Language

The email threatens that the account will be suspended or locked
if the recipient does not verify the account.

### 4. Suspicious URL

The email contains:

`http://m1crosoft-support.example/verify`

The domain does not match Microsoft's official domain.

### 5. Account Verification Request

The email asks the recipient to verify their account through a link.

### 6. Social Engineering

The email uses urgency and fear of account suspension to influence
the recipient's behavior.

### 7. Look-Alike Domain

The use of `m1crosoft` instead of `microsoft` is a deceptive
look-alike spelling technique.

## Header Analysis

Important email-header fields that can be checked include:

- From
- Return-Path
- Reply-To
- Received
- Message-ID
- SPF
- DKIM
- DMARC

These fields can help determine whether the sender and message
origin are authentic.

## Recommended Actions

1. Do not click suspicious links.
2. Do not open unexpected attachments.
3. Verify the sender independently.
4. Visit the organization's official website directly.
5. Report the suspicious email.
6. Delete the email after reporting it.

## Conclusion

The sample contains several phishing indicators, including a
suspicious sender address, look-alike domain, urgent language,
threatening language, and a suspicious verification link.
