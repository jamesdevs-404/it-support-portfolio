# ⚠️ Terminate AD User Account – SOP

**Purpose:**  
This SOP describes the process to securely terminate a user’s access in Active Directory and related systems, ensuring company data and security policies are preserved.

---

## **Scope**
For IT Support staff responsible for offboarding employees in AD, email, and corporate systems.

---

## **Prerequisites**
- Termination notice from HR
- Approved ticket in ticketing system
- Access to ADUC, email admin portal, and other relevant systems
- Knowledge of user’s accounts and assigned resources

---

## **Procedure**

### **1. Verify Termination Request**
- Confirm HR termination notice is valid.
- Ensure request is documented in the ticketing system.

### **2. Disable AD Account**
1. Open **Active Directory Users and Computers (ADUC)**.
2. Navigate to the user’s OU.
3. Right-click the user → Select **Properties** → **Account** tab.
4. Check **Account is disabled**.
5. Optionally, move the user to a **Terminated Users OU** for record-keeping.

### **3. Remove from Groups and Permissions**
- Check group memberships and remove sensitive access (shared drives, admin groups, VPN, etc.).
- Document changes for auditing purposes.

### **4. Reset Password**
- Reset the account password to a secure temporary value to prevent unauthorized access.

### **5. Disable Email and Other Services**
- Access **Exchange Admin Center** or email admin portal.
- Disable mailbox access or set forwarding if required.
- Revoke access to cloud apps (Office 365, SaaS apps, etc.).

### **6. Collect Company Assets**
- Ensure laptops, mobile devices, and security tokens are returned.
- Update inventory records.

### **7. Document Completion**
- Log all steps in the ticketing system.
- Notify HR and manager that termination procedures are complete.
## **Security Considerations**
- Never share terminated user credentials.
- Follow least privilege principle—revoke all access immediately.
- Preserve critical data per company retention policies.
- Only perform termination after HR authorization.
