## Class 36 Read: XSS with w3af, DVWA

#### Explain how a cross-site scripting attack works in non-technical terms.
Imagine someone slips a fake deposit slip into your bank's forms. You fill it out, thinking it's real, and your money goes to the wrong account. In a similar way, hackers sneak dangerous instructions into a bank's website. When you log in, you unknowingly follow these instructions, letting hackers access your account or steal your information.
#### What are the three types of XSS attacks?
Reflected XSS: Hacker tricks the website into showing their note to you.
Stored XSS: Hacker hides their note in a message, and others who see it accidentally activate it.
DOM-based XSS: Hacker plants a note directly in the website's code and waits for you to trigger it.
If an attacker successfully exploits a XSS vulnerability, what malicious actions would they be able to perform?
-If hackers use XSS they can act as you, do things you can, read your stuff, and even steal your login. They might change how the site looks or put harmful stuff in it.

#### What are some security controls that can be implemented to prevent XSS attacks?
Check Input: Sites must be careful with what you type in, letting only safe things in.
Protect Output: Sites wrap content safely so hidden notes don't work.
Headers Help: Sites tell browsers how to deal with content, blocking sneaky notes.
Content Rules (CSP): Sites set rules to allow only safe stuff, blocking risky notes.
