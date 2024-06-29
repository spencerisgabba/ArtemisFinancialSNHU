# ArtemisFinancialSNHU

Client Overview

Client: Artemis Financial, a company offering financial services such as wealth management, investment advice, and financial planning.

Issue: Address security vulnerabilities in their software to protect sensitive financial data and ensure secure communications.
Addressing Software Security Vulnerabilities

What was done well:

    Thoroughly reviewed the codebase for potential weak points.
    Utilized security testing tools and best practices for secure coding.
    Documented each vulnerability, its impact, and proposed solutions.

Importance of secure coding:

    Prevents unauthorized access, data breaches, and other security incidents.
    Maintains the integrity, confidentiality, and availability of data.

Value of software security:

    Protects sensitive information, ensures regulatory compliance, maintains customer trust, and prevents financial losses.

Vulnerability Assessment

Challenges: Identifying hidden vulnerabilities that were not immediately apparent during the initial code review.

Helpful tools: OWASP Dependency-Check and manual code reviews.
Increasing Layers of Security

Methods used:

    Implemented AES encryption with a 256-bit key for data at rest and in transit.
    Generated a self-signed certificate for HTTPS communication.
    Implemented cryptographic hash functions to verify data integrity.

Future assessment techniques:

    Use a combination of automated security testing tools and manual code reviews.
    Follow established security best practices and regularly update dependencies.

Ensuring Functional and Secure Code

Steps taken:

    Performed functional testing after refactoring.
    Conducted secondary static testing using OWASP Dependency-Check.
    Manually reviewed code to ensure no new vulnerabilities were introduced.

Resources, Tools, and Coding Practices

Helpful tools and practices:

    OWASP Dependency-Check: For identifying known vulnerabilities.
    Java Keytool: For generating self-signed certificates and managing keystores.
    Spring Boot: For implementing secure HTTPS communication.
    SHA-256 Hash Algorithm: For ensuring data integrity.
    AES Algorithm: For encrypting sensitive data.
    Manual Code Review: For identifying potential vulnerabilities.

Examples of Work

For future employers:

    Refactored code snippets demonstrating secure coding practices.
    Screenshots of successful application execution with HTTPS enabled.
    Dependency-check reports illustrating security status before and after refactoring.
    Documentation of the security assessment process and mitigation techniques.

Summary

We examined and refactored Artemis Financial’s software to address security vulnerabilities and ensure secure communication. Key steps included implementing AES encryption, generating a self-signed certificate for HTTPS, adding an endpoint for SHA-256 checksum, and updating application properties for HTTPS. Secondary static testing using OWASP Dependency-Check confirmed compliance with security enhancements. The final report includes documentation, code snippets, and screenshots demonstrating the successful execution and security improvements.
