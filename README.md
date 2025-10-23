# CS305-Portfolio
CS 305 Module Eight Journal – Adryan Knight
Artifact Summary

For my portfolio submission, I selected my work on Artemis Financial, combining both the Vulnerability Assessment Report (Project One) and the Practices for Secure Software Report (Project Two).
Artemis Financial is a financial-services firm that required a comprehensive review of its software to identify and mitigate security risks. My role was to analyze the existing code base for vulnerabilities, document findings, and refactor the application using secure-coding practices aligned with OWASP and NIST standards.

Reflection

In the vulnerability assessment phase, I conducted both manual and static code analysis to identify weaknesses in the Artemis Financial application. This included outdated dependencies (such as Spring Boot 2.2.4 and Jackson 2.10.x), hard-coded credentials, missing input validation, and unencrypted connections. I learned to interpret dependency-check results, recognize common CVEs, and prioritize remediation based on severity and exploitability. This phase deepened my understanding of how layered vulnerabilities can compromise data confidentiality and system integrity

CS 305 Project One Template

.

The refactoring phase focused on implementing encryption and secure communication protocols. I used AES-256 for data encryption, enforced HTTPS/TLS 1.2, added SHA-256 checksum verification, and improved input validation to prevent injection attacks. Certificate generation and checksum verification ensured that data remained authentic and tamper-proof during transmission. These updates aligned Artemis Financial’s application with modern cryptographic standards (FIPS 197) and reinforced defense-in-depth principles

CS 305 Project Two

.

What I did particularly well was aligning my recommendations and implementations with industry-standard best practices. Each refactoring step was grounded in OWASP Top Ten and NIST SP 800-53 guidance, demonstrating how secure coding contributes to overall software reliability. I also improved error handling, encapsulation, and code quality, which helped reduce exposure to future exploits.

The most challenging part was manually correlating transitive vulnerabilities within dependencies that could not be automatically scanned due to network restrictions. Researching CVEs and verifying safe versions built valuable analytical skills I can apply to future code reviews and vulnerability management processes.

After refactoring, I verified both functionality and security through successful code execution and static analysis. No runtime errors occurred, and the refactored code adhered to encryption and validation protocols. These results confirmed that I could strengthen application security without breaking functionality — a critical skill for secure-software development.

This artifact demonstrates my ability to:

Identify and assess vulnerabilities using structured methods (manual and static analysis).

Apply secure-coding practices like AES encryption, certificate validation, and secure configuration.

Test, verify, and document results in professional reports suitable for technical and non-technical stakeholders.

Employers can see from this work that I understand the full lifecycle of software-security hardening — from vulnerability identification to secure implementation and verification. This project highlights my ability to transform an insecure codebase into a resilient, standards-compliant system that protects sensitive data while maintaining operational integrity.
