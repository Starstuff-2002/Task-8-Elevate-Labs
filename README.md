# Task-8-Elevate-Labs
# Understanding the Role of VPNs in Privacy and Secure Communication

## Objective
The objective of this task is to understand how VPNs (Virtual Private Networks) contribute to online privacy and security by masking IP addresses, encrypting traffic, and enabling safe browsing over potentially insecure networks.

## Tools Used
- VPN Client: ProtonVPN (Free Tier)
- Web Browser: Google Chrome
- IP Verification Site: https://whatismyipaddress.com

## Steps Performed

### 1. VPN Selection and Registration
ProtonVPN was selected due to its reputation for security, transparency, and the availability of a free plan without data limits. An account was created using an email address and verified through the ProtonVPN portal.

### 2. Installation of VPN Client
The ProtonVPN desktop client was downloaded for Windows. After installation, the application was launched, and login was completed successfully.

### 3. Establishing a VPN Connection
Within the ProtonVPN client, a connection was established to a Netherlands-based server. The client interface confirmed that the connection was active and secure.

### 4. IP Address Verification
The IP address was checked before and after connecting to the VPN using https://whatismyipaddress.com.

- Before VPN: [Original IP] (actual location)
- After VPN: [New IP] (Netherlands location)

This confirmed that the VPN successfully masked the original IP address.

*A screenshot of the IP address after VPN connection is included as part of the deliverables.*

### 5. Testing Encrypted Browsing
A standard website (https://wikipedia.org) was accessed to verify encrypted traffic through the VPN tunnel. The website loaded without issues, confirming that the VPN was functioning properly.

### 6. Disconnection and Comparison
After disconnecting the VPN, the IP address reverted to the original value, and the browsing speed increased slightly. This behavior is typical due to the absence of encryption overhead once the VPN is turned off.

### 7. VPN Encryption and Privacy Research
Key findings from research on VPN technology:

- **Encryption Standard:** Most reputable VPNs, including ProtonVPN, use AES-256 encryption.
- **No-Logs Policy:** ProtonVPN enforces a strict no-logs policy to prevent data retention.
- **Kill Switch:** Provides automatic disconnection from the internet if the VPN connection drops.
- **DNS Leak Protection:** Ensures DNS queries do not expose user activity outside the VPN tunnel.

## Summary

### Benefits of Using a VPN
- Hides the user’s real IP address and geographical location.
- Encrypts data, ensuring privacy over public or untrusted networks.
- Enables access to region-restricted or censored content.
- Protects against ISP tracking and data collection.

### Limitations of VPNs
- May reduce connection speeds due to encryption overhead.
- Free VPN plans often provide fewer server options and limited bandwidth.
- Some online services may block traffic from known VPN IP addresses.
- Users must trust the VPN provider’s privacy practices.

## Deliverables
- Screenshot showing the IP address after VPN connection.
- This README file documenting the VPN setup and analysis process.

## Conclusion
This task demonstrated the effective use of a VPN to enhance online privacy and security. While VPNs introduce minor limitations in terms of speed and accessibility, their benefits for secure communication, especially on public networks, make them a valuable cybersecurity tool.
