# Address Security and Compliance Risk in the SDLC

- Status: draft 
- Deciders: CISO, Architects, Dev Managers 
- Date: [YYYY-MM-DD when the decision was last updated]
- Tags: process 

## Context and Problem Statement

Manage the security life cycle of in-house developed, hosted, or acquired software to prevent, detect, and remediate security weaknesses before they can impact the enterprise.

## Decision Drivers

- Establish and Maintain a Secure Application Development Process
- Establish and Maintain a Process to Accept and Address Software Vulnerabilities
- Perform Root Cause Analysis on Security Vulnerabilities
- Establish and Manage an Inventory of Third-Party Software Components
- Use Up-to-Date and Trusted Third-Party Software Components
- Establish and Maintain a Severity Rating System and Process for Application Vulnerabilities
- Train Developers in Application Security Concepts and Secure Coding
- Apply Secure Design Principles in Application Architectures
- Implement Code-Level Security Checks

## Considered Options

Building the foundation of a secure and compliant SDLC would require the following,

- Track application dependencies
- Engage in manual code review
- Create repeatable, documented processes
- Use an automated code analysis solution

## Pros and Cons of the Options

### Track application dependencies

When tracking dependencies, some best practices include:

- Focusing on individual features or use-cases
- Using a dependency manager
- Talking with all internal stakeholders involved in the application’s development, like architects, IT leadership, and developers


### Code reviews

Reviewing source code is fundamental to finding an application’s security weaknesses.
When performing a security code review, some best practices include:

- Looking for vulnerabilities that target the application type
- Reviewing for vulnerability indicators and signatures
- Tracking data flows to identify common vulnerabilities
- Searching for strings, keywords, and code patterns known to be indicators for vulnerabilities and misconfigurations
- Search plain-text data sets for dangerous functions
- Review potentially risky functions for reachability
- Review user input locations for exploitable vulnerabilities that can act as entry points


### Documenting processes

Part of compliance is being able to prove that you can maintain your security posture.
Some ways to embed application security into your application development processes include:

- Building security into the pull request process
- Setting practices for using security tools to validate manual reviews
- Incorporating security checks as a release gate for deployment and software delivery
- Implementing a software delivery model that includes security, functional, and performance sign-offs as a deployment condition


### Automated code analysis

Managing all code reviews manually becomes time-consuming. Additionally, it increases the likelihood of human error risks.
Automated tools that can help streamline the code review process include:

- Static Analysis Security Testing (SAST): identify vulnerable code patterns
- Software Composition Analysis (SCA): scan code for CVEs found in an application’s dependencies

## Links

1. https://scribe.rip/re-introducing-application-security-to-your-team-baeb211f9192
2. https://owasp.org/www-project-code-review-guide/assets/OWASP_Code_Review_Guide_v2.pdf
