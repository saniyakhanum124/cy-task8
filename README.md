# cy-task8
# Working with VPNs Task

## Objective
The goal of this task is to demonstrate the use of a VPN for securing internet traffic and confirming that website connections are encrypted using SSL/TLS.

---

## Steps Performed

1. **Download & Install VPN**
   - Downloaded ProtonVPN for Windows 10 from the official website.
   - Installed and logged into my ProtonVPN account.

2. **Connect to VPN**
   - Chose a free VPN server (Netherlands) and successfully connected.

3. **Verify VPN IP**
   - Checked my IPv4/IPv6 address using [whatismyipaddress.com].
   - Confirmed my IP had changed to the VPN server location.  

4. **Confirm Traffic Encryption**
   - Opened `amazon.com` in the browser.
   - Clicked on the padlock icon → viewed the security certificate.
   - Verified details such as:
     - Common Name (CN): www.amazon.com
     - Issued by: DigiCert Global CA
     - Validity Period
     - SHA-256 Fingerprints

   This confirms that HTTPS is being used, meaning the traffic is encrypted with SSL/TLS.

---

## Recommendations
- Always use a trusted VPN when accessing public Wi-Fi or sensitive data.  
- Verify padlock and certificate details on important websites before entering credentials.  
- Never share your real IP details publicly.  
