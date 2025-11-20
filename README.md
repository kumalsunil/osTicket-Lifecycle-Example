<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# 🎫 Ticket Lifecycle Example: Submission to Resolution

This section demonstrates the complete flow of a ticket using the configuration settings from the previous guide, showing the customer view, agent queue, and final resolution.

---

### 1. 🌐 End-User Submission (Customer View)

The user, **Ken**, navigates to the public Support Center URL (`http://localhost/osTicket`).

* **Support Center Home:** Ken sees the main page and clicks **Open a New Ticket**.
    * <img width="1521" height="681" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/f1296fb9-1468-4c41-a0d3-dca366ddb4c8" />
* **Ticket Creation:** Ken fills out the form, providing his contact information and selecting the **Password Reset** Help Topic.
    * <img width="1521" height="681" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/4c2ee4af-a6f0-42a3-90b7-b65532557eb4" />

### 2. 🗃️ Agent Queue (Staff Control Panel)

After submission, the ticket appears in the **Agent Panel** queue.

* **Open Tickets View:** The agent logs into the Staff Control Panel and sees the new ticket (**Ticket #162094**) with the subject "Forgot my password" in the **Open** status.
    * <img width="1521" height="681" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/906e0715-ec11-419b-a7cd-14b80ea96b00" />

### 3. ✍️ Agent Response and Resolution

The agent clicks on the ticket to view the thread and resolve the issue.

* **Ticket Thread:** The agent reviews the user's initial message. The **Help Topic (Password Reset)** and the submitting user **Ken** are clearly visible. The agent prepares a response.
    * <img width="1002" height="952" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/dad94f64-e0c6-4075-b6b8-bf406608b558" />
* **Resolution and Status Change:** The agent provides the resolution ("I reset your password.") and, critically, changes the **Status** to **Resolved** or **Closed**.
    * <img width="987" height="952" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/eebc9417-a7b9-41ec-a6d9-d640c6d3b94b" />

The ticket lifecycle is complete, and the resolution is recorded in the system.
