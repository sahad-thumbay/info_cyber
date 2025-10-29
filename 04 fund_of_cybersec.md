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
- possession-based: smart cards, OTP tokens
- inherence-based: biometrics (figerprint, face ID)
- multifactor authentication (MFA): combination of 2 or more above
- single sign-on (SSO): one-time login across multiple systems (e.g, google or microsoft sso)


![images](https://github.com/user-attachments/assets/22d520a5-658c-4523-a369-4a695e041896)

-----------------------------

- ## 🔓 Authorization Models
  
- DAC (Discretionary Access Control): Owner decides who can access (windows permissions)

- MAC (Mandatory Access Control): Access based on classification 1 (military systems)

- RBAC (Role-Based Access Control): Permissions assigned to roles (admin , manager, user)

- ABAC (Attribute-Based Access Control): Access based on condition (time, location, user type)

------------
## Example:

- An "HR Manager" role can view employee data, while "Employee" role can only view their own profil
-------
# Best Practices

- use strong, unique  passwords.

- Apply MFA wherever possible.





- Review role-based permissions regularly.

- Log all authentication and access events.


