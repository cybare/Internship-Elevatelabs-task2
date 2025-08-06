# Internship-Elevatelabs-task2

## Task 2 - Analyze a Phishing Email Sample.

### Objective: 

Identify phishing characteristics in a suspicious email sample.

### Tools: 

Email client or saved email file (text), free online header analyzer.

### Deliverables: 

A report listing phishing indicators found

### Solution:

### 1) Microsoft Phished Email from online source

![Microsoft Phished email](Samplemail/MicrosoftPhishedEmail.png)

#### Step 1: Examine sender's email address for spoofing.

Displayed email: `support@msupdate.net`

Remark : Microsoft would use something like `@microsoft.com`, not `@msupdate.net`. So it is suspicious

#### Step 2: Look for Suspicious Email Content 

It Claims the password was changed this is common scare tactic

We can see IP and browser info added to make it look legit which is not needed if legitimate.

This is asking user to act quickly ("your account has been compromised")

#### Step 3: Suspicious Links

Links use like:

 -"Reset your password"
  
 -"Learn how to make your account more secure"

 -Hovering over the links (not visible in image) might show a **non-Microsoft domain**

#### Step 4: Urgent / Threatening Language

"If this wasn't you, your account has been compromised"

This is designed to panic users into clicking

#### Step 5 :Generic ending

"The Microsoft account team" instead of a named employee

Real emails often include more specific contact details or footer formatting


#### Step 6. Summary of Phishing Traits

| Traits                        | Found |
|-------------------------------|-------|
| Spoofed sender address        | Yes |
| Mismatched domain             | Yes |
| Urgent/threatening language   | Yes |
| Generic branding              | Yes |
| Links pushing fast action     | Yes |
| Realistic formatting (to deceive) | Yes |

---


### 2) Paypal Phised Email from online source

![Microsoft Phished email](Samplemail/PaypalPhisedEmail.png)

#### Step 1: Examine sender's email address for spoofing.

Displayed email: `services@paypal-accounts.com`

Remark : PayPal's real domain is `paypal.com`, not `paypal-accounts.com`.

#### Step 2: Suspicious Link/Button

Displayed Button: "Confirm Your Information"

Actual Link (on hover): Likely goes to a malicious or fake PayPal clone website.

Remark: Generic text with a sense of urgency + data collection request.

#### Step 3: Urgent and Threatening Language

“You have 24 hours to solve the problem or your account will be permanently disabled.”

Phishing emails often try to scare users into acting quickly without thinking.

#### Step 4: Generic Greeting

"Dear PayPal customer"

Legitimate companies like PayPal address users by their real name.

#### Step 5:  Spelling and Grammar Errors

“You have 24 hours to solve the problem” – awkward phrasing

“permanetly” — (typo or missing elsewhere in real samples)

These often indicate a low-effort phishing campaign.

#### Step 6: Mismatched Domain Branding

Logo and visual style try to mimic PayPal, but:

Domain is fake

Button doesn't go to `paypal.com`

Email layout is simplistic

#### Step 7: Summary of Phishing Traits

| Trait                         | Found |
|------------------------------|-------|
| Spoofed email address        | Yes |
| Suspicious button/link       | Yes |
| Urgent language              | Yes |
| Generic greeting             | Yes |
| Grammar issues               | Yes |
| Visual impersonation         | Yes |
| Realistic formatting (to deceive) | Yes |

---
