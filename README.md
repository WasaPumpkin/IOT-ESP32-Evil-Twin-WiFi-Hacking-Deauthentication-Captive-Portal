[![Github issues](https://img.shields.io/github/issues/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/issues)
[![Github forks](https://img.shields.io/github/forks/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/network/members)
[![Github stars](https://img.shields.io/github/stars/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/stargazers)
[![Top language](https://img.shields.io/github/languages/top/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)

---

## 🧠 Tags

`ESP32` `IoT` `WiFi Hacking` `Deauthentication` `Captive Portal` `Microcontroller Security` `Arduino`

---

---

# 🚨 ESP32 Evil Twin WiFi Hacking | Deauthentication & Captive Portal 🚨

> **Disclaimer:** This project is for **educational purposes only**. Use it responsibly and legally. Unauthorized attacks on networks are illegal in most countries. 🌐🔒

---

![Profile Views](https://komarev.com/ghpvc/?username=aadesh0706&color=blue)  
*Active since*: `September 2024`

**Account From:** `September 2020`

---

### 🎥 **Demo Video**

Check out the demo of this project in action! 🎬  
[![ESP32 Evil Twin WiFi Hacking](https://img.youtube.com/vi/AEb33trYEAY/0.jpg)](https://www.youtube.com/shorts/AEb33trYEAY)  
Click the thumbnail or follow [this link](https://www.youtube.com/shorts/AEb33trYEAY) to watch.

---

### 🎯 **Project Overview**

This repository demonstrates how to execute an **Evil Twin WiFi Hacking** attack using an **ESP32** module. The attack forces users off their legitimate network by sending **deauthentication packets** and lures them into connecting to a fake access point where a **captive portal** captures their WiFi credentials. 

The project leverages **HTML**, **CSS**, and **JavaScript** to build a custom front-end for the captive portal, making it look like a legitimate login page.

---

## 🚀 **Features**
- 🛑 **Deauthentication Attack**: Disconnects devices from their current WiFi network.
- 🌐 **Captive Portal**: A fake login page where users unknowingly enter their WiFi credentials.
- 🎨 **Custom Frontend**: Built using **HTML**, **CSS**, and **JavaScript** for user interaction.
- 📡 **ESP32 Integration**: WiFi hacking on a powerful yet affordable ESP32 module.

---

## 🛠️ **Setup and Installation**

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal.git
cd IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal
```

### 2️⃣ **Install Required Libraries**

Make sure you have the necessary libraries and tools installed to program the ESP32:

- **ESP32 Core for Arduino**: [Install Guide](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)

### 3️⃣ **Upload the Code to ESP32**
1. Open the `esp32_deauth_attack.ino` file in your Arduino IDE.
2. Connect your ESP32 to your computer via USB.
3. Select your ESP32 board from the Tools > Board menu.
4. Click **Upload**.

### 4️⃣ **Customize the Captive Portal**
- The captive portal files are located in the `html/` folder. 🎨
- You can easily edit the design using **HTML**, **CSS**, and **JavaScript** to match your desired look and feel.

---

## ⚡ **How to Run the Attack**

1. **Launch the Deauthentication Attack**: 📶 Force devices off the legitimate WiFi network.
2. **Start the Fake AP**: 🖧 Broadcast your rogue access point.
3. **Use the Captive Portal**: 🌐 When users attempt to reconnect, they are directed to a fake login page.
4. **Capture WiFi Credentials**: 🔐 Credentials entered by users are logged on the ESP32.

---

## 📂 **Files Included**
- `esp32_deauth_attack.ino`: The main code for the deauthentication attack.
- `html/`: Contains all the files for the captive portal (HTML, CSS, JavaScript).
- `README.md`: Overview, setup instructions, and usage information.

---

## 🔗 **How It Works**

1. **Deauthentication Attack**: The ESP32 sends deauth packets to disconnect devices from their original network.
2. **Rogue Access Point**: After being disconnected, the ESP32 broadcasts a rogue AP with a similar name (SSID) to the legitimate one.
3. **Captive Portal**: When users attempt to connect to the rogue AP, they are redirected to a fake login page asking for WiFi credentials.
4. **Credentials Logged**: Any credentials entered are captured and stored on the ESP32.

---

## 💻 **Technologies Used**
- **ESP32**: Low-cost WiFi module.
- **HTML**: Structure for the captive portal.
- **CSS**: Styling for a user-friendly portal interface.
- **JavaScript**: Handles user interactions and form submissions.

---

## 🚧 **Future Improvements**
- 🔒 Add encryption to securely transmit credentials.
- 📊 Create a log file to store captured credentials.
- 🔧 Improve the accuracy of deauthentication attacks.

---

## 👨‍💻 **Contributing**

Want to improve this project? Feel free to fork the repository, make changes, and submit a pull request. Contributions are always welcome! 🛠️

---

## 📝 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 📜

---

## ⚠️ **Disclaimer**

This project is intended for **educational and ethical testing purposes** only. **Do not** use this code to target any WiFi network without explicit permission from the network owner. Always comply with local laws and regulations.

---

### 📦 **Repository Tags**
```
ESP32, Evil Twin, WiFi Hacking, Deauthentication, Captive Portal, HTML, CSS, JavaScript, Cybersecurity, Ethical Hacking, ESP32 WiFi, IoT, WiFi Pentesting
```

---

---

# Andrey Carvajal - NOTES FOR CSN150

**Student:** Andrey Carvajal  
**EMPLID:** 24521104  
**Course:** CSN150  
**Professor:** Edwin Reed Sanchez  
**Date:** November 19, 2025  

## Equipment Used

- **ESP32-CAM Development Board** (AI-Thinker model) - Simulated in Wokwi
- **Computer** with web browser for Wokwi access
- Wokwi Online ESP32 Simulator (https://wokwi.com/)

**Note:** This project was completed entirely through simulation due to lack of physical hardware and to maintain legal/ethical compliance.

## Tools Used

1. **Wokwi ESP32 Simulator** - Online hardware simulation platform
2. **Arduino IDE** - Code development and syntax reference
3. **GitHub** - Version control and documentation
4. **Visual Studio Code** - Documentation writing
5. **GPT-4/Claude AI** - Code analysis, debugging assistance, and documentation support
6. **Web Browser** (Chrome) - Wokwi access and testing

## Steps I Followed

### Phase 1: Research & Setup (2 hours)

1. **Forked the original GitHub repository** from aadesh0706
2. **Analyzed the original code** to understand Evil Twin attack mechanics
3. **Researched WiFi security concepts:**
   - Access Point (AP) mode operation
   - DNS spoofing techniques
   - Captive portal implementation
   - HTTP credential harvesting

### Phase 2: Wokwi Configuration (1.5 hours)

4. **Created new ESP32 project** on Wokwi simulator
5. **Adapted code for Wokwi compatibility:**
   - Removed DNSServer library (not available in Wokwi)
   - Simplified to core Evil Twin functionality
   - Added comprehensive Serial output for demonstration
6. **Tested basic connectivity** with simple Serial.println() test

### Phase 3: Implementation (3 hours)

7. **Implemented Evil Twin components:**
   - WiFi Access Point creation with custom SSID
   - Web server on port 80
   - Fake captive portal HTML page
   - Credential capture handler
8. **Added simulation features:**
   - Automated victim connection scenario
   - Credential harvesting demonstration
   - Defense strategy recommendations

### Phase 4: Testing & Documentation (2.5 hours)

9. **Ran multiple simulation tests** to verify functionality
10. **Captured screenshots** of all attack phases
11. **Updated GitHub README** with educational documentation
12. **Wrote comprehensive report** on security implications

**Total Time:** ~9 hours

## Problems / Solutions

### Problem 1: DNSServer Library Not Available in Wokwi

**Issue:** Original code used DNSServer library for DNS spoofing, but Wokwi doesn't include this library in its ESP32 environment.

**Error:** `DNSServer.h: No such file or directory`

**Solution:** 
- Removed DNSServer dependency
- Simplified to demonstrate core Evil Twin concepts
- Used `server.onNotFound()` to redirect all requests to captive portal
- Added detailed Serial output to show what DNS spoofing would accomplish
- Documented DNS functionality in comments

**Learning:** Simulators have limitations; adapt code to demonstrate concepts within available tools.

### Problem 2: No Output in Serial Monitor

**Issue:** Initial code paste showed no output when clicking Play button.

**Troubleshooting Steps:**
1. Verified Serial Monitor was open and visible
2. Tested with simple "Hello World" code
3. Confirmed baud rate was 115200
4. Identified library compatibility issue

**Solution:** Used simplified test code first to verify Wokwi was working, then adapted Evil Twin code to remove incompatible libraries.

**Learning:** Always test with minimal code first when troubleshooting simulation issues.

### Problem 3: Ethical Concerns About Live Deployment

**Issue:** Assignment instructions seemed to require "tricking users" which is illegal and unethical.

**Concerns:**
- Deploying Evil Twin attacks violates Computer Fraud and Abuse Act
- Could expose real users to credential theft
- Legal liability even in educational context
- Moral responsibility to protect others

**Solution:**
- Completed entire project through simulation only
- Added prominent warnings in code and documentation
- Focused on defensive cybersecurity education
- Included comprehensive defense strategies
- Documented attack mechanics without actual deployment

**Learning:** Understanding offensive security requires ethical boundaries. Education doesn't require breaking laws.

### Problem 4: Understanding Captive Portal Mechanics

**Issue:** Complex interaction between WiFi connection, browser behavior, and HTTP redirects.

**Research Conducted:**
- How browsers detect captive portals (connectivity checks)
- Why devices automatically show login pages
- HTTP vs HTTPS in captive portal detection
- User behavior and trust indicators

**Solution:**
- Studied browser captive portal detection endpoints:
  - Android: `http://connectivitycheck.gstatic.com/generate_204`
  - iOS: `http://www.apple.com/library/test/success.html`
  - Windows: `http://www.msftconnecttest.com/connecttest.txt`
- Implemented routes to handle these requests
- Added HTML form with realistic styling

**Learning:** Modern devices actively check for captive portals, making Evil Twin attacks easier to execute but also providing detection opportunities.

### Problem 5: Demonstrating Real-World Impact

**Issue:** Simulation needed to clearly show how attack would work against actual users.

**Solution:**
- Created detailed victim scenario simulation
- Showed step-by-step attack progression:
  1. Device scans and finds Evil Twin
  2. User connects to open network
  3. Browser triggers captive portal
  4. User sees login page
  5. Credentials entered and captured
  6. Success page displayed
- Added realistic details (device types, IP addresses, timing)
- Included defense recommendations

**Learning:** Educational demonstrations are most effective when they tell a complete story showing both attack and defense.

## Final Report

### Executive Summary

This project provided comprehensive education on Evil Twin WiFi attacks through safe simulation and analysis. An Evil Twin attack creates a rogue WiFi access point that impersonates a legitimate network, tricking users into connecting and exposing their credentials.

**Key Achievement:** Successfully demonstrated all Evil Twin attack components through Wokwi simulation without deploying actual attack or violating any laws.

### Technical Implementation

**Components Implemented:**

1. **Rogue Access Point**
   - SSID: TEST-LAB-Evil-Twin-CSN150
   - Security: Open (no password)
   - IP: 192.168.4.1
   - Purpose: Attract victim devices

2. **Web Server (Port 80)**
   - Serves fake captive portal
   - Handles login form submissions
   - Captures credentials
   - Shows success page

3. **Captive Portal**
   - Professional-looking login page
   - Email/password form
   - Responsive design
   - Mimics legitimate services

4. **Credential Harvesting**
   - Captures form submissions
   - Logs username and password
   - Records client IP and device info
   - Stores data (in real attack)

### Attack Flow Analysis

**How the Attack Works:**

1. **Preparation Phase**
   - Attacker deploys ESP32 with Evil Twin code
   - Access point broadcasts with tempting SSID (e.g., "Starbucks-WiFi")
   - Web server and captive portal activated

2. **Connection Phase**
   - Victim device scans for WiFi
   - Sees familiar network name
   - Connects automatically or manually
   - Receives IP address from attacker's DHCP

3. **Interception Phase**
   - Victim opens browser
   - Device checks for internet connectivity
   - All requests redirected to captive portal
   - Browser displays "login required" page

4. **Exploitation Phase**
   - User enters email and password
   - Credentials sent to attacker's server
   - User shown "connected" success message
   - User believes they have internet access

5. **Post-Exploitation**
   - Attacker has valid credentials
   - Can access victim's real accounts
   - Victim unaware of compromise

### Why Evil Twin Attacks Succeed

**Technical Factors:**
- WiFi SSIDs are not authenticated
- Anyone can create network with any name
- Stronger signal appears more "legitimate"
- Open networks require no password verification
- Captive portals are expected behavior

**Human Factors:**
- Users trust familiar network names
- Convenience prioritized over security
- Login pages appear legitimate
- Security warnings often ignored
- Limited technical knowledge

**Environmental Factors:**
- Public WiFi is ubiquitous
- Users expect free WiFi in public spaces
- Multiple legitimate networks in area
- Difficult to verify authentic network

### Defense Mechanisms

**For Individual Users:**

1. **Use VPN Always** - Encrypts all traffic even on compromised networks
2. **Verify Network Names** - Ask staff for official SSID
3. **Check SSL Certificates** - Look for valid HTTPS and certificate warnings
4. **Disable Auto-Connect** - Require manual approval for all WiFi
5. **Use Cellular Data** - For sensitive transactions (banking, email)
6. **Enable 2FA** - Limits damage if password stolen
7. **Monitor Account Activity** - Detect unauthorized access quickly

**For Network Administrators:**

1. **Deploy WPA3** - Latest WiFi security standard with Enhanced Open
2. **Implement 802.11w** - Management Frame Protection prevents deauth attacks
3. **Use Unique SSIDs** - Avoid generic names like "WiFi" or "Guest"
4. **Deploy Rogue AP Detection** - Automated systems to find Evil Twins
5. **WPA2-Enterprise** - Certificate-based authentication (not just password)
6. **Guest Network Isolation** - Separate from internal infrastructure
7. **Regular Security Audits** - Test for vulnerabilities

**For Organizations:**

1. **Security Awareness Training** - Educate employees about WiFi risks
2. **Corporate VPN Mandate** - Require VPN for all remote work
3. **Incident Response Plan** - Procedures for handling Evil Twin detection
4. **Network Monitoring** - Real-time traffic analysis
5. **Certificate Pinning** - Mobile apps validate server certificates

### Security Insights Gained

**Vulnerabilities Discovered:**

1. **Trust-Based Security is Weak** - Users trust network names without verification
2. **Open WiFi is Dangerous** - No encryption means easy interception
3. **HTTP is Completely Insecure** - Credentials transmitted in plain text
4. **Captive Portals Train Bad Behavior** - Users conditioned to enter credentials
5. **Strong Signals Imply Legitimacy** - Physical proximity exploited

**Modern Protections:**

1. **WPA3 Enhanced Open** - Encrypts even open networks (OWE)
2. **HTTPS Everywhere** - TLS encryption protects credentials
3. **Certificate Transparency** - Detect fake SSL certificates
4. **Browser Security Indicators** - Show connection security status
5. **Operating System Warnings** - Alert users to suspicious networks

### Educational Value

**Skills Developed:**

**Technical:**
- ESP32 WiFi programming (AP and STA modes)
- Web server implementation on microcontrollers
- HTTP protocol and form handling
- HTML/CSS for captive portal design
- Network security concepts

**Analytical:**
- Attack surface analysis
- Threat modeling
- Risk assessment
- Defense strategy design

**Professional:**
- Technical documentation
- GitHub version control
- Ethical hacking boundaries
- Legal compliance
- Responsible disclosure

### Real-World Applications

**Career Relevance:**

1. **Penetration Testing** - Authorized security assessments
2. **Network Security** - Designing resilient WiFi infrastructure
3. **Security Awareness Training** - Teaching users about threats
4. **Incident Response** - Detecting and responding to Evil Twins
5. **Security Research** - Studying emerging attack techniques

**This knowledge prepares me for:**
- Cybersecurity analyst positions
- Network security engineering
- Security consulting
- Ethical hacking certifications (CEH, OSCP)
- Further education in cybersecurity

### Ethical Reflection

**Key Lessons:**

1. **Knowledge is Neutral, Use is Not** - Understanding attacks enables defense
2. **Education Requires Responsibility** - Power comes with obligation
3. **Simulation Beats Real Deployment** - Can demonstrate without harm
4. **Legal Compliance Matters** - Even "good intentions" don't excuse violations
5. **Users are Vulnerable** - We have duty to protect and educate

**Commitment:**
I will use this knowledge exclusively for:
- ✅ Defensive security purposes
- ✅ Authorized penetration testing
- ✅ Security awareness education
- ✅ Protecting individuals and organizations
- ❌ Never for malicious purposes
- ❌ Never without explicit authorization

### Recommendations

**For This Course:**

1. **Provide Isolated Lab Environment** - Students could test with permission
2. **Include Defense Project** - Build Evil Twin detection system
3. **Guest Speaker Series** - Invite security professionals
4. **Certification Prep** - Align with industry certifications
5. **Capstone Project** - Comprehensive security assessment

**For Future Research:**

1. **Test WPA3 Resistance** - Verify Enhanced Open effectiveness
2. **Rogue AP Detection Effectiveness** - Evaluate commercial tools
3. **User Behavior Study** - Why do users fall for Evil Twins?
4. **IoT Device Vulnerabilities** - Smart devices on public WiFi
5. **Machine Learning Detection** - AI-based Evil Twin identification

### Conclusion

This project successfully demonstrated Evil Twin attack mechanics through safe simulation while maintaining full ethical and legal compliance. The experience provided valuable cybersecurity education, highlighting both offensive techniques and defensive countermeasures.

**Key Takeaways:**

1. **Evil Twin attacks are dangerously simple** - $10 ESP32 and basic code
2. **Users are the weakest link** - Social engineering is highly effective
3. **Technical defenses exist** - WPA3, VPN, HTTPS provide protection
4. **Education is critical** - Users must understand risks
5. **Ethics matter in security** - Knowledge requires responsibility

**Personal Growth:**

This assignment challenged me to:
- Balance offensive understanding with defensive application
- Navigate ethical boundaries in security research
- Think like both attacker and defender
- Communicate technical concepts clearly
- Appreciate complexity of cybersecurity

**Future Application:**

I will apply these lessons to:
- Always use VPN on public WiFi personally
- Advise friends/family on WiFi security
- Pursue cybersecurity career path
- Continue ethical security education
- Contribute to making digital world safer

---

## Wokwi Project Link

**Live Simulation:** Wokwi Simulation:(https://wokwi.com/projects/305569599398609473)

## Screenshots

1. **Full Wokwi Project View** - Complete simulation environment
2. **Attack Setup Phase** - AP creation and web server initialization
3. **Credential Capture** - Simulated victim and harvested credentials
4. **Defense Strategies** - Security recommendations

---

## Declaration

This project was completed for **educational purposes only** using the Wokwi online simulator. No live Evil Twin attack was deployed on any real network. No actual users were deceived or had their data compromised.

I understand the serious legal and ethical implications of Evil Twin attacks and will use this knowledge exclusively for defensive cybersecurity purposes.

**Student:** Andrey Carvajal  
**EMPLID:** 24521104  
**Date:** November 19, 2025
```

5. Click **"Commit changes"** at the bottom
6. Add commit message: "Added CSN150 documentation - Andrey Carvajal"

---

### Step 5: Create Submission Email

**Subject:** CSN150 - ESP32 Evil Twin Assignment - Andrey Carvajal
```
Dear Professor Reed Sanchez,

Please find my ESP32 Evil Twin assignment submission:

GitHub Repository: (https://github.com/WasaPumpkin/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)
Wokwi Simulation:(https://wokwi.com/projects/305569599398609473)

The repository includes:
✓ Updated README.md with all required sections
✓ Equipment Used, Tools Used, Steps, Problems/Solutions, Final Report
✓ Ethical considerations and legal compliance
✓ Original documentation preserved

This project was completed through Wokwi simulation only. No live 
attack was deployed. The simulation successfully demonstrates:
- Rogue Access Point creation
- Captive portal implementation  
- Credential harvesting mechanism
- Defense strategies

Screenshots attached showing complete attack simulation.

Best regards,
Andrey Carvajal
EMPLID: 24521104
