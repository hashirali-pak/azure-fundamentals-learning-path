# Module 4: Describe Azure Identity, Access and Security

## Key Learnings  
1. **Directory Services**  
   - **Microsoft Entra ID**: Cloud-based identity/access management supporting SSO, MFA and device management.  
   - **Microsoft Entra Domain Services**: Managed domain services (LDAP, Kerberos) for legacy apps in Azure.  
   - **Hybrid Integration**: Sync on-premises AD with Entra ID using Microsoft Entra Connect.  

2. **Authentication Methods**  
   - **Single Sign-On (SSO)**: One credential for multiple apps (requires secure initial authentication).  
   - **Multifactor Authentication (MFA)**: Combines passwords with phone codes/biometrics for added security.  
   - **Passwordless**: Replaces passwords with Windows Hello, Authenticator App or FIDO2 security keys.  

3. **Access Control & Security Models**  
   - **Conditional Access**: Grants/denies access based on signals (location, device risk).  
   - **Role-Based Access Control (RBAC)**: Assigns permissions via roles (Owner, Reader) at scopes (subscriptions, resource groups).  
   - **Zero Trust**: "Never trust, always verify" model with least-privilege access.  
   - **External Identities**: Collaborate securely with external users via B2B/B2C features.  

---

## Achieved Learning Objectives  
- Explained **Microsoft Entra ID** and **Domain Services** for hybrid/cloud environments.  
- Compared authentication methods (SSO, MFA, passwordless) by security/convenience trade-offs.  
- Applied **RBAC** to manage resource access hierarchically (management groups → resources).  
- Described **Conditional Access** policies to enforce adaptive security (e.g., block untrusted locations).  
- Defined **Zero Trust** and **Defense-in-Depth** as foundational security frameworks.
