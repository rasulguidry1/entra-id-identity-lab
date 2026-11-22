🔐 Microsoft Entra ID | Enterprise Identity & Access Management Lab

Technologies: Microsoft Entra ID, Microsoft 365, MFA, Conditional Access, RBAC, Microsoft Authenticator

📌 Project Overview

Designed and implemented an enterprise Identity and Access Management (IAM) lab using Microsoft Entra ID to simulate identity security operations for a 100-employee organization.

The project demonstrates employee identity administration, secure authentication, role-based access controls, identity lifecycle management, and Zero Trust security principles.

🏢 Business Scenario

Organization: Contoso Technologies (Fictional)

Departments: IT, Finance, Human Resources, Engineering, and Sales.

Security Challenges:

* Unauthorized access through compromised credentials
* Excessive employee permissions
* Inconsistent authentication requirements
* Delayed removal of employee access
* Limited visibility into authentication failures

Solution: Implement centralized identity administration and security policies through Microsoft Entra ID.

🛠️ Technical Implementation

1. Identity Administration

* Created and managed test employee identities.
* Configured department-based security groups.
* Assigned users to appropriate groups.
* Implemented role-based permissions.
* Applied least-privilege access principles.

2. Multi-Factor Authentication

* Configured MFA requirements.
* Registered test accounts with Microsoft Authenticator.
* Validated successful MFA authentication.
* Tested authentication failures.
* Reviewed Microsoft Entra sign-in logs.

3. Conditional Access

* Created Conditional Access policies.
* Configured MFA requirements for selected users.
* Tested policies using report-only mode.
* Implemented access restrictions.
* Validated allowed and blocked sign-in scenarios.

4. Role-Based Access Control

* Configured Microsoft Entra administrative roles.
* Assigned limited administrative permissions.
* Tested restricted administrative operations.
* Verified permission boundaries between standard and privileged users.

5. Identity Lifecycle Management

* Simulated employee onboarding.
* Assigned department-specific access.
* Updated access during employee transfers.
* Disabled departing employee accounts.
* Revoked active sessions.
* Verified removal of access.

🧪 Security Testing & Validation

| Security Test | Result |
| --- | --- |
| Authorized employee authentication | ✅ Passed |
| MFA enforcement | ✅ Passed |
| Conditional Access restrictions | ✅ Passed |
| Unauthorized administrative operation blocked | ✅ Passed |
| Disabled account sign-in prevented | ✅ Passed |
| Employee access removal | ✅ Passed |

🔍 Security Findings

The lab demonstrated how Microsoft Entra ID security controls can reduce identity-related risks.

Key Findings:

* MFA adds protection against password-only account compromise.
* Conditional Access enables context-based authentication requirements.
* RBAC limits unnecessary administrative privileges.
* Identity lifecycle controls help prevent former employees from retaining access.
* Sign-in logs support authentication troubleshooting and security investigations.

💼 Business Impact

This project demonstrates practical approaches to:

* Reducing unauthorized access risks
* Strengthening employee authentication
* Enforcing least-privilege access
* Standardizing identity administration
* Improving employee offboarding security
* Supporting Zero Trust security strategies

🧰 Technologies Used

* Microsoft Entra ID
* Microsoft 365 Admin Center
* Microsoft Authenticator
* Conditional Access
* Role-Based Access Control
* Microsoft Entra Sign-in Logs

📸 Project Documentation

Supporting evidence includes identity configuration, authentication policies, role assignments, sign-in testing, and employee lifecycle scenarios.

🎯 Skills Demonstrated

Identity Administration | MFA | Conditional Access | RBAC | Least Privilege | Identity Lifecycle Management | Zero Trust | Authentication Troubleshooting
