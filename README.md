<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Prerequisites and Installation

This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.

## **Environments and Technologies Used**
- **Microsoft Azure Virtual Machine** 
- **IIS** 
- **CGI**
- **PHP**
- **Osticket Software**
- **Rewrite Module**
- **MySQL Server**
- **Heidi SQL**

## **Operating Systems Used**
- **Windows 10**
---

## **Objectives**
The objectives of this project include:
1. Install and set up prerequisites for osticket
2. Install and configure Osticket for post-installation.
---

## **Configuration/Implementation Steps**

### **Step 1: Set Up Environment**
- Create an Azure Windows 10 VM.
- Must connect to Azure VM using Windows Remote Desktop 

---

### **Step 2: Install osTicket**
- Download the required prerequisites from [osTicket documentation](https://docs.osticket.com/en/latest/Getting%20Started/Installation.html#prerequisites) and place them in a zip folder. 

---

### **Step 3: Configure Web Server and Set Up Database**
- Set up IIS to recognize PHP, configure necessary PHP extensions, and adjust file permissions.
- Install HeidiSQL, create the osTicket database, and connect it to osTicket.

---
### **Step 4: Finalize Installation:**
- Complete the web-based setup by creating an osTicket account and setting up the URL for end users to submit tickets.

## **Results**
Successfully installed and configured osTicket software, ready to be logged into and customized to meet organziation needs.

## **Screenshot of the Results**
<p>With all prerequisites and recommended technologies installed, here's what the osticket web interface should look like:</p> 
<div align="center"> <img src="https://github.com/user-attachments/assets/55d291ac-e086-49cf-bc33-8d2e428e5abd" alt="image" style="max-width:100%; height:auto;"/> 
</div> 
<div align="center"> <img src="https://github.com/user-attachments/assets/6d7f7b81-5513-48fe-a393-37f028884ca2" alt="image" style="max-width:100%; height:auto;"/> 
</div>
<p>Completed process of configuring IIS and setting up HeidiSQL:</p> 
<div align="center"> <img src="https://github.com/user-attachments/assets/3cc1d0cc-8513-429c-b61b-dfb4814e71de" alt="image" style="max-width:100%; height:auto;"/> 
</div>
<div align="center"> <img src="https://github.com/user-attachments/assets/15253e7a-365f-4465-96cc-df808f28ec6b" alt="image" style="max-width:100%; height:auto;"/> 
</div>
<p>Successfully created an active account and set up the URL for end users to submit their tickets::</p> 
<div align="center"> <img src="https://github.com/user-attachments/assets/01baad1f-fa28-4983-a53f-82992b8cbf54" alt="image" style="max-width:100%; height:auto;"/> 
</div>
<div align="center"> <img src="https://github.com/user-attachments/assets/e3adf9a5-3e32-4114-a0d0-996f8b00ac27" alt="image" style="max-width:100%; height:auto;"/> 
</div>











---
