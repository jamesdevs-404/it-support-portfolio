# 🗝 Unlock AD User Account – SOP

**Purpose:**  
This Standard Operating Procedure (SOP) outlines the steps for unlocking a locked Active Directory (AD) user account while maintaining security best practices.

---

## **Scope**
For IT Support staff authorized to manage user accounts in Active Directory Users and Computers (ADUC).

---

## **Prerequisites**
- Access to ADUC or RSAT tools
- Proper permissions to unlock accounts
- Verified user identity

---

## **Procedure**
1. **Verify User Identity**
   - Confirm the user’s full name, department, and username.
   - Ask security questions or confirm via ticket system.

2. **Open Active Directory Users and Computers (ADUC)**
   - Press `Windows + R` → Type `dsa.msc` → Press **Enter**.
   - Navigate to the correct Organizational Unit (OU).

3. **Locate the Locked User**
   - Search for the username in the search bar.
   - Double-click the user object.

4. **Unlock the Account**
   - In the **Account** tab, check the box **Unlock account**.
   - Click **Apply** → **OK**.

5. **Confirm with the User**
   - Inform the user that their account is unlocked.
   - Have them log in to verify access.

---

## **Sample Screenshot**
Here’s an example screenshot showing the **Unlock account** checkbox in ADUC:  
![Unlock AD User Screenshot](../screenshots/unlock-ad-user.png)

---

## **Notes**
- Always check **why** the account was locked (multiple failed login attempts, expired password, etc.).
- For repeated lockouts, investigate Event Viewer for security events.
