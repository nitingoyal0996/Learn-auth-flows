# Learn Auth Flows w/ Me

Welcome to Learn-Auth-Flows! This repository is a collection of my personal experiments and projects aimed at exploring various authentication and authorization workflows. The goal is to deepen my understanding of these crucial areas beyond what is typically required for day-to-day tasks.

## About

This repository serves as a sandbox for me to dive deeper into these topics, experimenting with different methods and technologies without the pressure of building a complete application.

Below is a comprehensive list of authentication and authorization workflows that I plan to explore. This list serves as a roadmap for my learning journey:

### Authentication Workflows

1. Password-based
2. Multi-factor

        Something you know (password) with something you have (smartphone, hardware token)
        Examples: SMS codes, authentication apps (Google Authenticator, Authy), physical keys (YubiKey).

3. Single Sign-On

        Protocols:
        SAML (Security Assertion Markup Language)
        OAuth (Open Authorization) and OpenID Connect
        Examples: Google SSO, Microsoft Azure AD, Okta

4. OAuth and OpenID Connect
5. Passwordless Authentication

        Methods:
        Magic links sent via email
        One-time codes sent via SMS or email
        Biometric verification
        Examples: Auth0 passwordless, Slack magic link.

### Authorization Workflows

1. Role-based access control - RBAC

        Example: Admin, editor, viewer roles.

2. Attribute-Based Access Control (ABAC)

        Description: Permissions are based on attributes (user properties, resource properties, environmental conditions).
        Attributes:
        User attributes (e.g., department, job title)
        Resource attributes (e.g., classification level)
        Environment attributes (e.g., time of day, location)
        Use Case: Fine-grained access control.

3. Policy-Based Access Control (PBAC)

        Description: Uses policies to manage access rights.
        Policy Languages: XACML (eXtensible Access Control Markup Language).
        Use Case: Dynamic access control based on policies.

4. Context-Based Access Control

        Description: Grants access based on the context of the request (user's location, device, behavior).
        Use Case: Enhanced security through contextual information.
        Example: Denying access from unfamiliar locations or devices.

5. Access Control Lists (ACLs)

        Description: Specifies which users or system processes are granted access to objects and what operations are allowed.
        Use Case: Simple and straightforward access control for individual resources.
        Example: File system permissions.

6. Identity and Access Management (IAM)

        Description: Framework for managing digital identities and access to resources.
        Components:
            Identity provisioning and de-provisioning
            Authentication and authorization services
            Role management
            Audit and compliance
        Examples: AWS IAM, Azure Active Directory, Okta.

### Modern Trends and Enhancements

1. Zero Trust Security Model

        Description: Never trust, always verify; assumes threats can be internal or external.
        Principles:
            Continuous verification
            Least privilege access
            Micro-segmentation
        Use Case: Enhanced security posture for enterprise environments.

2. Adaptive Authentication

        Description: Adjusts the authentication requirements based on risk assessment.
        Factors Considered: User behavior, device reputation, location.
        Examples: Requiring MFA only when logging in from a new location.

3. Federated Identity Management

        Description: Allows users to use their identity across multiple domains or services.
        Protocols: SAML, OAuth, OpenID Connect.
        Examples: Single sign-on across multiple business applications.
