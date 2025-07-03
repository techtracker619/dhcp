# 📡 DHCP Role Installation and Scope Configuration Lab

A hands-on lab to install the **DHCP Server Role** on Windows Server 2019, create a new DHCP scope, configure exclusions, lease duration, and DNS options — all through the GUI.

---

## 🧠 Why This Lab?

Dynamic Host Configuration Protocol (DHCP) is essential for automating IP address assignment in enterprise networks. This lab helps practice real-world server setup tasks and reinforces core Windows Server administration skills.

---

## 🧭 Step-by-Step Guide

### 1. Open Server Manager
- Click `Manage` > `Add Roles and Features`.



---

### 2. Select Role-Based Installation
- Choose `Role-based or feature-based installation`.

---

### 3. Choose Server
- Select the local server from the server pool.

---

### 4. Select DHCP Server Role
- Under **Server Roles**, check `DHCP Server`.
- When prompted, click **Add Features**.
- Click **Next** > **Next** > **Install`.

![imagealt](https://github.com/techtracker619/dhcp/blob/497b3be5a00e76ab7614c37f44719bbd4d09b975/screenshots/VirtualBox_AC-DC-SERVER_30_06_2025_01_48_43.png)

---

### 5. Open DHCP Console
- Go to **Tools** > **DHCP** from Server Manager.
![imagealt](https://github.com/techtracker619/dhcp/blob/497b3be5a00e76ab7614c37f44719bbd4d09b975/screenshots/VirtualBox_AC-DC-SERVER_30_06_2025_01_51_27.png)

---

### 6. Create New DHCP Scope
- Right-click on `IPv4` > Select `New Scope`.

![imagealt](https://github.com/techtracker619/dhcp/blob/497b3be5a00e76ab7614c37f44719bbd4d09b975/screenshots/VirtualBox_AC-DC-SERVER_30_06_2025_01_58_21.png)

---

### 7. Define Scope Name
- Example:  
  - **Name:** `VM-Test`  
  - **Description:** _(Optional)_

![imagealt](https://github.com/techtracker619/dhcp/blob/497b3be5a00e76ab7614c37f44719bbd4d09b975/screenshots/VirtualBox_AC-DC-SERVER_30_06_2025_01_59_04.png)

---

### 8. Configure Exclusions
- Exclude high IPs like `192.168.1.201` - `192.168.1.255`.
- Optional: Add subnet delay (e.g., 1ms).

![imagealt](https://github.com/techtracker619/dhcp/blob/497b3be5a00e76ab7614c37f44719bbd4d09b975/screenshots/VirtualBox_AC-DC-SERVER_30_06_2025_02_02_14.png)

---

### 9. Lease Duration
- Set lease to `8 Days` or as needed.

![imagealt](https://github.com/techtracker619/dhcp/blob/497b3be5a00e76ab7614c37f44719bbd4d09b975/screenshots/VirtualBox_AC-DC-SERVER_30_06_2025_02_02_37.png)

---

### 10. Configure DHCP Options
- Choose: **Yes, I want to configure these options now**.

![imagealt](https://github.com/techtracker619/dhcp/blob/497b3be5a00e76ab7614c37f44719bbd4d09b975/screenshots/VirtualBox_AC-DC-SERVER_30_06_2025_02_02_56.png)

---

### 11. Set DNS and Domain
- Domain: `mylab.local`  
- Server Name: `My Lab Server`  
- IP: `192.168.100.10`

![imagealt](https://github.com/techtracker619/dhcp/blob/497b3be5a00e76ab7614c37f44719bbd4d09b975/screenshots/VirtualBox_AC-DC-SERVER_30_06_2025_02_03_50.png)

---

## 🧪 Key Skills Practiced

- Installing server roles with Server Manager  
- Creating and configuring DHCP scopes  
- Managing exclusions, lease time, and DNS options  
- GUI-based server administration  
- Real-world network services setup in a virtual lab

---

## 🤝 Author

**Anthony Jenkins**  
Follow for more labs on Active Directory, DHCP, GPOs, Cybersecurity, and Systems Administration.

<!-- 📚 Byte Library Section -->
<h3>📚 Byte Library</h3>
<p>
  Explore free IT & Cybersecurity resources, labs, and articles built for beginners and career switchers.
  <br />
  👉 <a href="https://byte-library.com/" target="_blank" style="text-decoration: none; font-weight: bold;">
    Visit Byte Library
  </a>
</p>

