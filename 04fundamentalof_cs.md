# 🖥 Fundamentals of Computer Security

## 🔐 Identification, Authentication, and Authorization

| Concept | Description | Example |
|----------|--------------|----------|
| Identification | Claiming an identity | Typing username |
| Authentication | Proving identity | Entering password / fingerprint |
| Authorization | Granting access | Accessing certain files after login |

---

## 🧩 Key Principle:
> “Authentication verifies who you are. Authorization decides what you can do.”

---

## 🔑 Authentication Methods

- Knowledge-based: Passwords, PINs
- possesion-based:smart card,OTP tokens
- Internet-based: Biometrics(fingerprint,face ID)
- multifactor authentication (MFA): combination of 2 or more above
- single sign-on(SSO): one-time login across multiple systems (e.g,google or microsoft SSO)
- # authorization models
- DAC (discretionary access control): owner decides who can access (windows permission)
- MAC (mandatory access control): access based on clarification levels (military systems)
- RBAC (role-based access control): permission assigned to roles (admin , manager,user)
- ABAC (attribute-based access control): acccess based on conditons (time,location,user type)
## example:

-An "HR Manager" role can view employee data, while "Employee" role can only view their own profil

-Best Practices

-strong, unique unique passwords.

-Apply MFA wherever possible.

-Review role-based permissions regularly.

-Log all authentication and access events. 


![download](https://github.com/user-attachments/assets/2b96e548-d5d2-447b-9dd5-ffae8d7a0a12)




