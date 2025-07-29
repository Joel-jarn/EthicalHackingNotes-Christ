# 🛡️ Ethical Hacking Notes

## 🔓 Password Cracking

**Password Cracking** is the process of recovering passwords from stored or transmitted data using various techniques.

### 🛠 Techniques:
- **Brute Force Attack** – Trying every possible combination.
- **Dictionary Attack** – Using a list of likely passwords.
- **Rainbow Tables** – Precomputed tables of hash values.
- **Phishing** – Tricking users into giving passwords.
- **Keyloggers** – Software/hardware to capture keystrokes.

### 💡 Prevention:
- Strong passwords (mix of letters, numbers, symbols)
- Two-Factor Authentication (2FA)
- Avoid common or reused passwords

---

## 🌐 Types of Networks

1. **LAN (Local Area Network)** – Home or office.
2. **WAN (Wide Area Network)** – Internet.
3. **MAN (Metropolitan Area Network)** – City-wide.
4. **PAN (Personal Area Network)** – Bluetooth devices.
5. **WLAN (Wireless LAN)** – Wi-Fi networks.
6. **CAN (Campus Area Network)** – University or large organization.

---

## 🔁 UDP vs TCP

| Feature | TCP (Transmission Control Protocol) | UDP (User Datagram Protocol) |
|--------|--------------------------------------|-------------------------------|
| Connection | Connection-oriented | Connectionless |
| Reliability | Reliable (guarantees delivery) | Unreliable (no guarantee) |
| Speed | Slower | Faster |
| Use Case | Email, Web, File Transfer | Streaming, VoIP, Gaming |
| Flow Control | Yes | No |
| Error Checking | Yes | Minimal |

---

## 🧮 Subnet

A **Subnet** is a segmented piece of a larger network. It helps manage IP addresses and isolate traffic for performance or security.

- Example: `192.168.1.0/24`  
- The `/24` indicates the subnet mask (255.255.255.0)

### Benefits:
- Organized IP allocation
- Reduced congestion
- Enhanced security

---

## 📣 Internet Broadcast

**Internet Broadcast** is when one sender transmits data to all hosts in a network.

- Common address: `255.255.255.255` (IPv4)
- Used in protocols like **ARP** or **DHCP**
- Typically restricted to local networks

---

## 🌐 IP Address

### IPv4 vs IPv6

| Feature | IPv4 | IPv6 |
|--------|------|------|
| Bit Length | 32-bit | 128-bit |
| Format | Decimal (`192.168.0.1`) | Hexadecimal (`2001:db8::1`) |
| Addresses | ~4.3 billion | Virtually unlimited |
| Header | Simple | Complex |
| Security | Optional | Built-in IPSec |
| Status | Still common | Growing use

---

## 📤 Transfer Protocol

A **Transfer Protocol** defines rules for data transmission between devices.

### Common Examples:
- **HTTP / HTTPS** – Web traffic
- **FTP / SFTP** – File transfers
- **SMTP / POP3 / IMAP** – Email protocols
- **SSH** – Secure remote access
- **Telnet** – Remote login (not secure)

---

## 🔐 [Have I Been Pwned](https://haveibeenpwned.com/)

**Have I Been Pwned** is a website where you can check if your email or password has appeared in any known data breaches.

### Features:
- Check if your **email or phone** has been leaked.
- Verify if your **passwords** have been exposed.
- Get breach **alerts** by subscribing with your email.
- Useful for both individuals and organizations.

### Why It's Important:
- Raises awareness of leaked personal data.
- Encourages better password practices.
- Helps companies monitor security exposure.

> If listed in a breach: change passwords immediately and enable 2FA.
