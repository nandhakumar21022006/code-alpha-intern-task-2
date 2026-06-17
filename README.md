# code-alpha-intern-task-2
**🔒 Cyber Security Internship – Task 3**
**Secure Coding Review**
**📌 Objective**

To perform a security review of a Python application, identify security vulnerabilities, and provide remediation recommendations using static analysis and manual code inspection.

**🛠 Tools Used**
Kali Linux
Python 3
Bandit (Static Code Analyzer)
**🚀 Steps Performed**
Developed a vulnerable Python login application.
Performed static code analysis using Bandit.
Identified security weaknesses.
Implemented secure coding practices.
Developed a remediated version of the application.
**🔍 Vulnerabilities Identified**
Hardcoded Password

Issue:

if username == "admin" and password == "admin123":

Risk:
Credentials are exposed directly in source code.

Bandit Finding:
B105: hardcoded_password_string

**🛡 Remediation**
Avoid hardcoded credentials.
Use password hashing.
Store credentials securely.
Implement input validation.
Limit login attempts.
**📊 Result**

Bandit successfully detected:

Hardcoded password vulnerability
CWE-259: Use of Hard-coded Password
**📚 Key Concepts Learned**
Static Code Analysis
Secure Coding Practices
Password Hashing
Vulnerability Assessment
Code Review Methodology
**✅ Conclusion**

This task provided hands-on experience in secure coding review and vulnerability assessment. Using Bandit and manual inspection, security weaknesses were identified and remediated by applying secure coding practices.
