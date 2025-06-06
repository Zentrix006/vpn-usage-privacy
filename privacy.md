# 📄 VPN Setup, Testing, and Analysis Report

## ✅ VPN Client Used
- **Service**: ProtonVPN (Free Plan)
- **Website**: https://protonvpn.com
- **OS**: Kali Linux

---

## 🛠️ Step-by-Step Process

1. **Created an account** on ProtonVPN and verified my identity.
2. **Installed required packages** on Kali Linux:
   ```bash
   sudo apt update
   sudo apt install openvpn
Logged in and connected using ProtonVPN CLI:

bash
Copy
Edit
sudo protonvpn-cli login myusername
sudo protonvpn-cli connect --fastest
Verified IP address before and after VPN activation using:

https://whatismyipaddress.com

Observed real IP replaced by VPN server IP.

Disconnected the VPN after testing:

bash
Copy
Edit
sudo protonvpn-cli disconnect
🔍 Observations
IP address changed from my original ISP to the VPN provider's server.

Internet access continued smoothly after VPN connection.

Minimal latency increase, which is normal due to encryption and rerouting.

✅ Advantages of VPNs
Encrypts traffic, keeping browsing private.

Prevents eavesdropping on public Wi-Fi.

Bypasses region restrictions on websites.

Hides your real IP address from visited websites.

⚠️ Limitations
Free VPNs may have bandwidth limits and fewer servers.

VPN providers can technically log your traffic — trust is essential.

Doesn't protect from phishing or malware if user is tricked.

📌 Key Takeaways
VPNs are essential tools for privacy and security in untrusted networks.

They provide anonymity, but not full invisibility.

Use VPNs along with strong passwords, MFA, and safe browsing habits.
