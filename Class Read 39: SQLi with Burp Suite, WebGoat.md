Class Read 39: SQLi with Burp Suite, WebGoat
taylortommy23 edited this page 12 hours ago · 1 revision
What is SQL injection?
SQL injection: A way hackers trick a website into giving them access to its database by sending malicious commands through input fields. These commands in the input fields manipulate the database and let the hackers steal information or take control of the system.
Can you give an example of how a hacker could use SQL injection to gain unauthorized access?
Imagine a website where you check your stock market account. Hackers can trick the website into thinking they're valid users. The attacker might enter a special code in the username field. The website's security might not catch this, and the hackers can then get into the account without a real password and this lets them access your stock market information without permission.
What are some ways to prevent SQL injection attacks on a web server?
To stop SQL injection attacks we can check and clean user inputs before using them, use special programming techniques that separate user input from SQL commands, limit database access permissions, use tools that block malicious input, keep software updated and test for vulnerabilities.
References: https://www.varonis.com/blog/sql-injection-identification-and-prevention-part-1
