# 🌐 Networking Basics

---

## 🧠 Task 1: What is a Network?

Networks are simply **things connected**.  
For example, your friendship circle: you're all connected because of similar interests, hobbies, skills, etc.

### 📌 Real-Life Examples of Networks:
- A city's public transportation system  
- Infrastructure such as the national power grid  
- Meeting and greeting your neighbours  
- Postal systems for sending letters and parcels  

### 🖥️ In Computing:
Networking is the same idea—just applied to **technological devices**.

For example:  
Your phone connects to the internet to access services. These devices form networks.

> A **network** in computing can consist of **2 to billions of devices**, such as:
- Laptops  
- Phones  
- Security cameras  
- Traffic lights  
- Farming equipment  

### ⚙️ Why Are Networks Important?
- **Integrated into daily life** (e.g., weather data, electricity, traffic control)
- Critical concept in **cybersecurity**

📌 Example:  
_Alice, Bob, and Jim form their own simple network._

> Networks can come in **all shapes and sizes**, and we'll explore more of them in this module.

---

## 🌐 Task 2: What is the Internet?

Now that we understand what a network is, let's explore the **Internet**.

### 💡 The Internet:
> A **giant network** made up of many **smaller networks** joined together.

#### Example:
Alice meets new friends—Zayn and Toby—but they don’t speak the same language as Bob and Jim. Alice acts as a **translator/messenger**, forming a bridge between networks.

---

### 🏛️ Historical Background:
- **1960s**: ARPANET project (US Defence Department)
- **1989**: Tim Berners-Lee creates the **World Wide Web (WWW)**
- The Internet evolves into a **repository for storing and sharing information**

---

### 🔀 Types of Networks:
| Type            | Description                                                  |
|-----------------|--------------------------------------------------------------|
| **Private**     | Small networks (e.g., home or office)                        |
| **Public**      | The Internet (connecting private networks together)         |

---

## 🔎 Task 3: Identifying Devices on a Network

To communicate effectively, devices must be **identified and identifiable**.

### 🧍 Humans vs Devices
| Human           | Device                          |
|----------------|----------------------------------|
| Name            | IP Address (can change)         |
| Fingerprint     | MAC Address (permanent by design)|

---

## 🌐 IP Addresses

An **IP address** (Internet Protocol address) is a way of identifying a device on a network.

#### 💡 IP Address Format:
- Consists of **four octets** (e.g., `192.168.1.77`)
- Assigned temporarily and **can change**
- Cannot be **duplicated within the same network**

### 🧭 IP Address Types:
| Type         | Purpose                                          |
|--------------|--------------------------------------------------|
| **Public**   | Identifies device on the **Internet**            |
| **Private**  | Identifies device **within a local network**     |

### 🖥️ Example Table:
| Device Name      | IP Address     | IP Address Type |
|------------------|----------------|------------------|
| DESKTOP-KJE57FD  | 192.168.1.77   | Private          |
| DESKTOP-KJE57FD  | 86.157.52.21   | Public           |
| CMNatic-PC       | 192.168.1.74   | Private          |
| CMNatic-PC       | 86.157.52.21   | Public           |

🖼️ Screenshot:  
![Private/Public IP Example](https://assets.tryhackme.com/additional/cmn-aoc2020/day-8/1.png)

#### 🌐 ISP Role:
Public IPs are provided by your **ISP** (Internet Service Provider), usually for a **monthly fee**.

🖼️ Screenshot:  
![ISP Public IP](https://assets.tryhackme.com/additional/cmn-aoc2020/day-8/2.png)

---

## 🆚 IPv4 vs IPv6

### 🌐 IPv4:
- Uses `2^32` addresses (~4.29 billion)
- Shortage due to growth in connected devices

### 🌐 IPv6:
- Uses `2^128` addresses (340 trillion+)
- More efficient and **solves IPv4 shortage**

🖼️ Screenshot comparing IPv4 and IPv6:
_(Image not provided but can be assumed here)_

---

## 🔒 MAC Addresses

Every networked device has a **physical network interface** (microchip on the motherboard) with a unique **MAC address**.

### 📌 Format:
- **12-character hexadecimal**: e.g., `a4:c3:f0:85:ac:2d`
- First 6 chars = manufacturer
- Last 6 chars = unique serial

---

## 🎭 MAC Spoofing

### 🚨 What is Spoofing?
> **Spoofing** is pretending to be another device by copying its MAC address.

### 🔓 Why is this a problem?
If a firewall allows all traffic from a certain MAC (e.g., admin), a **spoofed** device can gain **unauthorized access**.

### ☕ Real-Life Example:
Public Wi-Fi networks (e.g., cafes, hotels) may:
- Track devices via MAC address
- Charge based on per-device access

---

# 🧾 Summary

| Concept            | Description                                                    |
|--------------------|----------------------------------------------------------------|
| **Network**         | Two or more devices connected                                  |
| **Internet**        | Large global public network of interconnected private networks |
| **IP Address**      | Identifies a device temporarily (Public/Private)              |
| **MAC Address**     | Unique hardware identifier                                     |
| **IPv4/IPv6**       | Versions of IP addressing schemes                             |
| **Spoofing**        | Faking a device’s MAC address to gain unauthorized access     |

---
