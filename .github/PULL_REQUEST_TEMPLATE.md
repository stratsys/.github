## Security Checklist

- Access control has been implemented across these changes ([Access control](https://owasp-top-10-proactive-controls-2018.readthedocs.io/en/latest/c7-enforce-access-controls.html))
- Injections has been prevented ([Sql](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html), [OS](https://cheatsheetseries.owasp.org/cheatsheets/DotNet_Security_Cheat_Sheet.html#os-injection) and [LDAP](https://cheatsheetseries.owasp.org/cheatsheets/DotNet_Security_Cheat_Sheet.html#ldap-injection))
- Sensitive data has been identified and is being protected properly ([Protect Data Everywhere](https://owasp-top-10-proactive-controls-2018.readthedocs.io/en/latest/c8-protect-data-everywhere.html))
- Exposure of technical errors and system information has been prevented ([Error and Exception handling](https://owasp-top-10-proactive-controls-2018.readthedocs.io/en/latest/c10-handle-errors-exceptions.html))
- Multitenancy data isolation has been implemented across these changes ([Multitenancy](https://en.wikipedia.org/wiki/Multitenancy))
- Any web UI is escaping output to prevent XSS ([Encode and Escape data](https://owasp-top-10-proactive-controls-2018.readthedocs.io/en/latest/c4-encode-escape-data.html))
 
- [ ] This pull request fulfills all security requirements