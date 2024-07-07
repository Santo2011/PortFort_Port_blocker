# PortFort_Port_blocker
Unleash the Power to Control Your Ports!
# Project Overview
PortFort is a user-friendly desktop application designed to empower users with granular control over their computer's ports (USB, Wi-Fi, Ethernet, Webcam). It offers a graphical user interface (GUI) for enabling and disabling these ports, along with a robust authentication and verification system to ensure secure port management.
# Key Features
Intuitive GUI: PortFort presents a visually appealing and easy-to-navigate interface with clear icons representing each port type (USB, Wi-Fi, Ethernet, Webcam). Granular Control: Users can effortlessly enable or disable individual ports based on their preferences and security requirements. Secure Authentication: A secure login system safeguards unauthorized access to PortFort's functionalities. Verification Mechanism: Upon login, a 4-digit code sent via email is required for verification, adding an extra layer of security.
# Installation
Prerequisites tkinter PIL (Pillow) sqlite3 random subprocess
Additional libraries for specific port control functionalities (e.g., pywinusb for Windows USB control) may be required. Refer to their respective documentation for installation instructions.

# Download
Clone or download the PortFort repository from GitHub (link to your repository).

# Run the Application
Navigate to the downloaded directory in your terminal. Execute the main Python script using the following command: python main.py

# Usage
Launch PortFort: Double-click the main.py file or execute the command mentioned above. Login: Enter your registered email address and password on the login screen. Verification: Check your email for a 4-digit code sent from PortFort. Enter the code in the verification prompt displayed within the application. Port Management: Upon successful verification, you'll be presented with the main UI. Click the corresponding icons to enable or disable desired ports.

# Output
![346292919-b8312f3e-1fc1-4b5c-b85f-f3bb7f1e494b](https://github.com/Santo2011/PortFort_Port_blocker/assets/125989475/57817dee-3b3a-4fab-beaf-b0f6f7cd4025)
![346292917-0073e995-fd6f-44a5-96e1-c6ea05753db4](https://github.com/Santo2011/PortFort_Port_blocker/assets/125989475/1e64913b-49ac-4158-ae83-92a801c7e752)
![346292916-43b0fde8-a369-4d8f-bd5d-5b0a2fa45046](https://github.com/Santo2011/PortFort_Port_blocker/assets/125989475/ebb69099-fdb1-4937-aea5-0b5cbb234f49)
![346292915-fc9f4414-7bab-497a-bbb9-f0c909846bf6](https://github.com/Santo2011/PortFort_Port_blocker/assets/125989475/2b4b00d0-aa92-4d91-842e-a0ccf4bfc446)
![346292914-c8a75263-e6ba-4ec3-823a-66a350ca92f1](https://github.com/Santo2011/PortFort_Port_blocker/assets/125989475/6f45bd2a-a107-48a0-82ac-69b5319813e5)
![346292913-f2349adb-d838-49bf-81bc-efb583232e85](https://github.com/Santo2011/PortFort_Port_blocker/assets/125989475/00d901db-7eb9-4e35-b35a-9242d9dae075)
![346292911-ce23672d-99e0-498e-b21b-18c7f6e24dad](https://github.com/Santo2011/PortFort_Port_blocker/assets/125989475/2485fb5c-c9e2-48f6-8a48-85f88710df69)
![346292907-218c1ce9-4c6c-426a-87a5-ef2d3eaa1e64](https://github.com/Santo2011/PortFort_Port_blocker/assets/125989475/25fa260a-2914-4e6c-a643-15e473ff3c85)
![usb](https://github.com/Santo2011/PortFort_Port_blocker/assets/125989475/34ca27d1-9db9-49ce-abc9-422e63b884b6)

# Additional Notes
For enhanced security, consider implementing two-factor authentication (2FA) using libraries like pyotp. Refer to the documentation of the additional port control libraries for specific usage instructions. This application is intended for educational purposes. For production environments, consult with IT security professionals for guidance on implementing robust port control mechanisms.

# Disclaimer
Modifying port configurations can potentially impact applications or system functionality. Use PortFort with caution and at your own risk. Back up your system before making significant changes.
