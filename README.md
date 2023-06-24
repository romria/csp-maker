### Content Security Policy builder

Content Security Policy (CSP) is a security layer that helps to prevent certain types of attacks, including Cross-Site Scripting (XSS) and data injection attacks. This can be achieved by restricting which resources (JavaScript, CSS, Images, etc.) can be loaded on your website.

This project is made to simplify the process of populating CSP rules for `Content-Security-Policy` response header and `<meta>` tags.

🔴IMPORTANT❗🔴 : This software is provided without warranty of any kind. It is not a ready-to-go protection against possible front-end attacks, and you should completely understand what are you doing before adding this feature to your production website

### Prerequisites
* [Node.js](https://nodejs.org/) v18.16.0 or higher

### Installation
```bash
npm install
```

### Run
```bash
npm start
```
open [http://localhost:8000](http://localhost:8000)

### General Resources
* [Content-Security-Policy](https://content-security-policy.com/)
* [OWASP Content Security Policy Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html)
* [Mozilla Developer Network: Content Security Policy](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)
* [CSP Level 3 W3C](https://www.w3.org/TR/CSP3/)
* [CSP with Google](https://csp.withgoogle.com/docs/index.html)
* [CSP A Successful Mess Between Hardening And Mitigation](https://speakerdeck.com/lweichselbaum/csp-a-successful-mess-between-hardening-and-mitigation)
* [The unsafe-hashes Source List Keyword](https://content-security-policy.com/unsafe-hashes/)

### Testing
* [Google CSP Evaluator](https://csp-evaluator.withgoogle.com/)

### Usage
* [Using Google Tag Manager with a Content Security Policy](https://developers.google.com/tag-platform/tag-manager/web/csp)
* [Strict CSP](https://csp.withgoogle.com/docs/strict-csp.html)
