# VPN Task Report - Cyber Security Internship

## Task Objective

Understand the role of VPNs in protecting privacy and enabling secure communication. This report outlines the setup of a VPN client, validates encryption, and summarizes the benefits and limitations of using VPNs.

---

## 1. VPN Setup Process

### A. VPN Client Selected

* **Name:** ProtonVPN
* **Type:** Free Tier
* **Download Link:** [https://protonvpn.com](https://protonvpn.com)

### B. Installation Steps

1. Signed up for a free ProtonVPN account.
2. Downloaded the Windows version of ProtonVPN.
3. Installed the client and logged into the application.

### C. VPN Server Connection

* Selected and connected to a free server located in **Netherlands**.
* Connection was established successfully.

### D. IP Address Verification

* **Before VPN:** Local ISP IP address in India.
* **After VPN:** IP address changed to a Netherlands-based IP.
* Verified using [https://whatismyipaddress.com]
* **Screenshot Taken:**

---

## 2. Encryption Check and Behavior Comparison

### A. Secure Website Test

* Accessed https://news.google.com/foryou?hl=en-IN&gl=IN&ceid=IN%3Aen
* Confirmed encrypted connection via HTTPS and lock icon.

### B. Browsing Comparison

* Disconnected VPN and checked:

  * Browsing speed increased slightly.
  * IP address reverted to original.
* Performed speed test on [https://fast.com](https://fast.com):

  * **With VPN:** Reduced speed by \~20-30%.
  * **Without VPN:** Normal speed restored.

---

## 3. VPN Research Summary

### A. Protocols Used

* **OpenVPN** and **WireGuard**

### B. Encryption Standard

* **AES-256-bit encryption** (military grade)

### C. Privacy & Security Features

* DNS leak protection
* No-log policy
* Encrypted tunneling
* Automatic Kill Switch (ProtonVPN paid)

---

## 4. VPN Benefits and Limitations

### Benefits

* Protects against ISP and third-party tracking.
* Masks IP address and location.
* Provides access to region-blocked content.
* Secures traffic over public Wi-Fi.

### Limitations

* Slower connection speeds.
* Limited servers and bandwidth in free VPNs.
* Cannot guarantee complete anonymity.
* Some websites block known VPN IPs.

---

## 5. Supporting Evidence

* Included the following in the GitHub repository:

  * `screenshot-after-vpn.png` (VPN IP)
  * `vpn-connection-interface.png`
  * 'speed- before and after.png'
