# Fundamentals of computer security
## Identification, authentication, and authorization
| Concept           | Description          | Example          |
|-------------------|----------------------|--------------------------|
|**Identification** | Claiming an identity | Typing username |
|**Authentication** | Proving identity     | Entering password / fingerprint |
|**Authorization**  | Granting access      | Accessing certain files after login |

## Key Principle 
"Authentication verifies who you are. Authorization decides what you can do."


<img width="318" height="159" alt="download" src="https://github.com/user-attachments/assets/4b37ffb2-2b6e-4ac6-97e8-1d94c1aa309e" />


## Authentication Methods 
- Knowledge-based: Passwords, PINs
- Possession_based: Smart cards, otp tokens
- Inherence-based: Biometrics (fingerprint, face ID)
- Multifactor Authentication (MFA): Combination of 2 or more above
- Single sign-on (SSo): One-time login across multiple systems (e.g., Google or microsoft SSO)
# Authorization Models
- DAC (Discretionary Access Control): Owner decides who can access (Windows permissions).
- MAC (Mandatory Access Control): Access based on classification levels (military systems).
- RBAC (Role-Based Access Control): Permissions assigned to roles (Admin, Manager, User).
- ABAC (Attribute-Based Access Contol): Access based on conditions (time, location, user type).
## Example: 
An "HR Manager" role can view employee data, while "Employee" role can only view their own profile.
# Best Practices 
- Use strong, unique passwords.
- Apply NFA wherever possible.
- Review role-based permissions regularly.
- Log all authentication and access events.
