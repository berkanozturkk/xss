### XSS Vulnerability Examples

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

#### Overview
This repository provides two examples of scripts: one vulnerable to Cross-Site Scripting (XSS) attacks and one that is secure. XSS is a client-side code injection attack where an attacker can steal sensitive data, cookies, and more by injecting malicious scripts into a vulnerable web application.

#### Features
- ❌ **Vulnerable Script:** Demonstrates a web page susceptible to XSS attacks.
- ✔️ **Secure Script:** Demonstrates a web page with proper XSS protection.

#### Technologies
- **Language:** 
  - ![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  - ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  
#### Prerequisites
- Web Browser
- Basic knowledge of HTML and JavaScript

#### Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/berkanozturkk/xss.git
   ```
2. **Navigate to the directory:**
   ```bash
   cd xss
   ```
3. **Open the HTML files in your web browser:**
   - `vulnerable.html`
   - `safe.html`

#### Understanding XSS
Cross-Site Scripting (XSS) is a vulnerability that allows attackers to inject malicious scripts into web pages. To mitigate XSS:
- **Sanitize Inputs:** Ensure all inputs are cleaned.
- **Validate Inputs:** Check if inputs match expected formats.
- **Encode Outputs:** Convert user input to safe text.

