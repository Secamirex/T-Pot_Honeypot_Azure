# T-Pot Honeypot on Azure
![image](https://github.com/user-attachments/assets/07c438f9-4be3-49e3-b961-180892e9b308)


<h2> Lab objective: </h2>

* To  Install and configure the T-Pot honeypot on an Azure VM to monitor adversary attack behaviour on the VM host. 

<h2>Installation steps:</h2>

1. Install a new VM on Azure
2. Select " Debian image" with 16GB/4VCPU specs
3. Once the VM is installed, SSH  into the VM machine
4. Navigate to T-Pot GitHub page :GitHub - telekom-security/tpotce: 🍯 T-Pot - The All In One Multi Honeypot Platform 🐝
5. Install 'git' via CLI 
	 
		• sudo apt-get update && sudo apt install git -y

6. Clone the GitHub repository:  git clone https://github.com/telekom-security/tpotce

![image](https://github.com/user-attachments/assets/3abd55b8-2557-426a-a19d-f679eb7608c4)

7. Cd /tpotce
8. Run ./install.sh script

![image](https://github.com/user-attachments/assets/db21dff2-3154-4990-a631-3cfdd14d1ed2)

9. you will be prompted with the successful message below once installed. Reboot the VM.

![image](https://github.com/user-attachments/assets/a9245b24-e315-4bff-a5e8-d3ba9da761db)

10. Open up the following ports on Azthe ure side.

![image](https://github.com/user-attachments/assets/f950d37f-7b8f-4128-a19c-d632ffe246be)

![image](https://github.com/user-attachments/assets/81eb0a16-0bff-479c-8f89-4f53dc112435)

11. Access to T-Pot via user types is as follows

![image](https://github.com/user-attachments/assets/8e6676bd-cf28-4506-a3b7-dad4e64a46c4)

12. You can log in from your browser and access the T-Pot WebUI and tools: <strong> https://<your.ip>:64297 </strong>
* user: [<WEB_USER>]
* password: [password]

![image](https://github.com/user-attachments/assets/9cebd86d-d544-49ca-88ff-0563839e4fa4)

13. T-Pot landing page is <strong> Kibana </strong> which has a variety of dashboards and visulaisations.

![image](https://github.com/user-attachments/assets/a4bd65dc-fc84-4a2c-8d47-f51be96a063b)

14. Clicking on the <strong> Attack Map </strong> will redirect user to teh attack map. it requires logging in using <WEB_USER> credentials.

![image](https://github.com/user-attachments/assets/e0deeb76-20e9-49da-8c03-2f687c3c5985)

