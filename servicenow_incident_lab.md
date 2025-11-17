# ServiceNow Incident Lab – Password Reset Request

## Overview
This lab demonstrates how to create, manage, and resolve an IT support incident using a ServiceNow Developer Instance. The scenario focuses on performing a password reset request, documenting actions, and properly closing the ticket using ITIL best practices.

---

## 🧩 Scenario: Password Reset Request
A user contacted the help desk requesting assistance with accessing their account due to a forgotten password. This lab walks through creating and resolving the incident in ServiceNow.

---

## 🔐 Steps Performed

### **1. Logged Into ServiceNow Developer Instance**
- Accessed the ServiceNow personal developer instance.
- Navigated to the **Incident** module.

---

### **2. Created a New Incident**
- Selected **Create New** under *Incidents*.
- Filled in the following fields:
  - **Caller:** (Example: John Doe)
  - **Short Description:** "User unable to log in — password reset request"
  - **Category:** Service Request / Access Issue (depending on instance setup)
  - **Priority:** Set appropriately based on impact and urgency (e.g., Priority 3 - Moderate)

---

### **3. Classified and Prioritized the Incident**
- Set the **Impact** and **Urgency** fields to automatically generate a priority.
- Ensured correct assignment group (e.g., *Service Desk* or *IT Support*).

---

### **4. Performed Password Reset**
- Verified user identity according to policy.
- Performed a password reset using the appropriate admin console (ADUC or system authentication tool).
- Generated temporary password and noted requirement for password change at next login.

---

### **5. Documented Work Notes**
Documented all troubleshooting and resolution actions using Work Notes:
- Confirmed user identity
- Reset password
- Communicated temporary password
- User confirmed successful login

Example Work Note:
```
User identity verified. Password reset completed. Provided temporary password and instructed user to update password upon login. User confirmed successful access.
```

---

### **6. Resolved and Closed the Incident**
- Changed status to **Resolved**.
- Added comments summarizing the fix.
- Set **Resolution Code:** Password Reset / Solved.
- Closed the incident after confirming the user regained access.

---

## 📘 Resolution Summary
The user was unable to log in due to a forgotten password.  
A new temporary password was set, the user successfully authenticated, and the incident was resolved following ITIL practices.

---

## 🎓 Skills Demonstrated
- ServiceNow ticket creation  
- Incident classification & prioritization  
- Password reset workflow  
- Work Notes and resolution documentation  
- ITIL-aligned incident lifecycle  

---

## 📸 Screenshot Placeholders (Optional)
If you want to include screenshots later, add them like this:

```
![New Incident Form](screenshots/incident_form.png)
![Work Notes](screenshots/work_notes.png)
```

---

## ✔️ End of Lab
This lab demonstrates a foundational help desk workflow using ServiceNow and is excellent for building a technical portfolio.
