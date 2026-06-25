# Source Code Security Review
Automated and manual source code security review of a PHP web application using Snyk, GitHub integration, and Visual Studio Code.
## Findings Summary

| Finding | Severity | CWE |

|---|---|---|

| Reflected XSS (index.php) | High | CWE-79 |

| Hardcoded Database Credentials | Medium | CWE-798 |

| Missing HttpOnly Flag on Auth Cookie | Low | CWE-1004 |

| MD5 Password Hashing | Medium | CWE-327 |

| Unrestricted File Upload (RCE risk) | High | CWE-434 |
## Tools Used

Snyk · GitHub · Visual Studio Code
