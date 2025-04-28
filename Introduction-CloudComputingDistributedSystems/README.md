# 1. What is Cloud Computing

# 2. Software as a Service and Utility Computing
- **Software as a Service**
- **Utility Computing**
- **Utility Computing: Mitigate Risks**
- **Utility Computing – Amazon EC2**
- **Amazon EC2**
- **Utility Computing – MS Azure**
- **Spectrum of Abstractions**

# 3. Cloud Computing
- **Cloud Computing**
- **Significance of Cloud Computing**
- **Cloud Killer Apps**

# 4. Economics of the Cloud
- **Should I Move Into A Cloud?**
- **Adoption Challenges**
- **Growth Challenges**
- **Policy And Business Challenges**

# 5. Distributed Systems
- **Some Terminology**
- **More Terminology**
- **Loss of Reliability**
- **Distributed Systems vs Network Applications**
- **What About the Web?**
- **What About the Cloud?**

# 6. Networks
- **Who Recognizes This?**
- **Classic View of Network API**
- **Classic Approach "Broken" in Many Ways**
- **Classic OSI Stack**

# 7. Tunneling
- **Tunneling Analogy**
- **Tunneling in Networks**
- **Example: Microsoft VPN Stack**

# 8. End-to-End Argument
- **End-to-End Argument**
- **Saltzer et al. Analysis**
- **Generalized End-to-End View?**
- **What Can We Learn From This?**
- **When Should the Network Do More?**

# 9. Network Infrastructure
- **A Network is Like a "Mostly Reliable" Post Office**
- **Network Components**
- **Internet Topology**

# 10. Network Protocols
- **Protocol Layering**
- **Protocol Layering Example**

# 11. TCP/IP Protocols
- **Basic Elements of Any Protocol Header**
- **Demuxing Fields**
- **IP (Internet Protocol)**
  1. **IP Address**
  2. **IP(v4) Address Format**
- **UDP (User Datagram Protocol)**
- **TCP (Transmission Control Protocol)**
  1. **TCP Pipeline**
  2. **TCP Windowing**
- **UDP vs. TCP Comparison**
- **SCTP (Stream Control Transmission Protocol)**
- **Summary**

---

# Cloud Computing & Networking Explained 

## 1. What is Cloud Computing?
Cloud computing means using the internet to store, manage, and process data instead of using your own computer or servers. It's like renting computing power and storage from a big company (like Amazon or Microsoft) instead of buying and maintaining your own hardware.

## 2. SOFTWARE AS A SERVICE AND UTILITY COMPUTING

### Software as a Service (SaaS)
SaaS is when you use software over the internet without installing it on your computer. Examples include Gmail, Netflix, or Microsoft 365. You don't need to download anything—just log in and use it online.

### Utility Computing
Utility computing is like paying for electricity—you only pay for what you use. Instead of buying a whole server, you rent computing power when needed. This makes it cheaper and more flexible.

### Utility Computing: Mitigate Risks
Using utility computing reduces risks because:
- You don't have to buy expensive hardware.
- You can scale up or down easily (add more power when needed, reduce when not).
- The cloud provider handles security and maintenance.

### Utility Computing – Amazon EC2
Amazon EC2 (Elastic Compute Cloud) is a service where you can rent virtual computers (called instances) in the cloud. You pay only for the time you use them, just like paying for electricity.

### Amazon EC2
- Lets you run applications on Amazon's servers.
- You can choose how much power (CPU, memory) you need.
- Good for businesses that need flexible computing power.

### Utility Computing – MS Azure
Microsoft Azure is similar to Amazon EC2 but by Microsoft. It provides virtual machines, storage, and other cloud services where you pay based on usage.

### Spectrum Of Abstractions
This means different levels of cloud services, from basic (like raw computing power) to fully managed (like SaaS where you don't manage anything). Examples:
- **Low-level (more control):** EC2, Azure VMs (you manage the server).
- **High-level (less control):** SaaS like Gmail (you just use the app, no setup needed).

## 3. CLOUD COMPUTING

### Cloud Computing
Cloud computing means using the internet to access computing services like storage, software, and processing power instead of using your own computer or servers. It's like renting a powerful computer online instead of buying one.

### Significance of Cloud Computing
- **Saves Money:** No need to buy expensive hardware.
- **Flexible:** You can increase or decrease resources as needed.
- **Access Anywhere:** Work from any device with an internet connection.
- **Automatic Updates:** The cloud provider handles software updates and security.

### Cloud Killer Apps
These are popular applications that work best in the cloud:
- **Netflix:** Streams movies without needing DVDs.
- **Dropbox:** Stores files online instead of on your computer.
- **Zoom:** Runs video calls without installing heavy software.
- **Spotify:** Plays music directly from the internet.

## 4. ECONOMICS OF THE CLOUD

### Should I Move Into A Cloud?
Moving to the cloud is good if:
✅ You want to save money on hardware.
✅ You need flexibility (scaling up/down).
✅ You want easy access from anywhere.
But it may not be good if:
❌ Your internet is slow/unreliable.
❌ You have very sensitive data (security concerns).

### Adoption Challenges
- **Security Worries:** Some fear hackers or data leaks.
- **Internet Dependency:** If the internet goes down, work stops.
- **Learning Curve:** Employees may need training to use cloud tools.

### Growth Challenges
- **Cost Over Time:** Cloud bills can grow if not managed properly.
- **Vendor Lock-in:** Hard to switch providers once you rely on one.
- **Performance Issues:** If too many users share the cloud, it may slow down.

### Policy And Business Challenges
- **Legal Rules:** Some countries restrict where data can be stored.
- **Business Changes:** Companies must adapt workflows for the cloud.
- **Hidden Costs:** Extra fees for support, storage, or data transfers.

## 5. DISTRIBUTED SYSTEMS

### Some Terminology
- **Distributed System:** Multiple computers working together as one system (like a team).
- **Node:** A single computer or device in the system.
- **Cluster:** A group of computers connected to work on big tasks.
- **Latency:** The delay when data travels between computers.

### More Terminology
- **Fault Tolerance:** The system keeps working even if some parts fail.
- **Scalability:** The system can grow by adding more computers.
- **Consistency:** All computers see the same data at the same time.
- **Load Balancing:** Work is shared evenly between computers.

### Loss of Reliability
- If one computer fails, the system should still work.
- But if too many fail or the network breaks, the system may crash.
- Solutions: Backup systems, automatic recovery, and redundancy (extra copies of data).

### Distributed Systems vs Network Applications
| **Distributed Systems** | **Network Applications** |
|------------------------|-------------------------|
| Many computers act as one (e.g., Google's servers). | One main server, many users (e.g., Facebook). |
| Focus: Sharing work & data. | Focus: Connecting users to a service. |
| Example: Bitcoin (many computers verifying transactions). | Example: Online banking app (you connect to a bank's server). |

### What About the Web?
- The **Web (Internet)** is a giant network, not a distributed system.
- Websites (like YouTube) run on distributed systems behind the scenes.
- Your browser just talks to one server at a time.

### What About the Cloud?
- The **Cloud is built on distributed systems**.
- When you use cloud services (like Netflix), many hidden computers work together to deliver it fast.
- Benefits: More power, no single point of failure, and grows with demand.

## 6. NETWORKS

### Who Recognizes This?
Think of a network like a **postal system** for computers. Instead of sending letters, computers send **data packets** (small pieces of information). Every device (like your phone or laptop) has an **IP address**, which works like a home address for mail.

### Classic View of Network API
- **Network API (Application Programming Interface):** A set of rules that lets programs talk to the network.
- Example: When you open a website, your browser uses the API to ask the network, *"Get me this webpage!"*

### Classic Approach "Broken" in Many Ways
The old way of networking had problems:
❌ **Too rigid** – Hard to update or improve.
❌ **Security flaws** – Easy for hackers to break in.
❌ **Slow for modern needs** – Not good for video calls, cloud gaming, etc.

### Classic OSI Stack
The **OSI (Open Systems Interconnection) model** is a 7-layer guide for how networks should work:

| **Layer** | **What It Does** | **Example** |
|-----------|------------------|-------------|
| 7. Application | User-level apps (websites, email) | Chrome, Outlook |
| 6. Presentation | Formats data (encryption, compression) | HTTPS, ZIP files |
| 5. Session | Manages connections (start/stop chats) | Zoom calls |
| 4. Transport | Ensures data arrives correctly (TCP/UDP) | Error-checking in downloads |
| 3. Network | Routes data between networks (IP addresses) | Internet routers |
| 2. Data Link | Handles local network traffic (MAC addresses) | Wi-Fi, Ethernet |
| 1. Physical | Cables, signals (raw 0s and 1s) | Fiber optics, USB |

## 7. TUNNELING

### Tunneling Analogy
Imagine tunneling like a **secret underground passage**:
- You send a package (data) through a public road (the internet).
- But you hide it inside a **locked box (encryption)** so no one can see or steal it.

### Tunneling in Networks
- **What it does:** Sends private data safely over a public network.
- **How?** Wraps data in a secure "tunnel" (like a VPN).
- **Used for:** Secure office access, bypassing censorship, safe public Wi-Fi.

### Example: Microsoft VPN Stack
- A **VPN (Virtual Private Network)** creates a secure tunnel between your computer and a private network (like your office).
- **Microsoft's VPN** does this by:
  1. Encrypting your data (like a secret code).
  2. Sending it through the internet safely.
  3. Unlocking it only at the destination.
- **Why use it?** To work remotely without hackers stealing company data.

## 8. END-TO-END ARGUMENT

### End-to-End Argument
- **Simple Idea:** Some features (like security, error-checking) should be handled by the **end devices** (your computer/phone), not the network.
- **Example:** When you send an email, your email app (not the internet) should check if it was delivered correctly.
- **Why?** The network is just a "dumb pipe"—it should focus on moving data, not fixing problems.

### Saltzer et al. Analysis
- **Who?** Computer scientists (Saltzer, Reed, Clark) wrote a famous paper in 1984.
- **Main Point:** Putting too much "intelligence" (like security checks) inside the network makes it:
  - **Slower** (extra steps for every message).
  - **Less flexible** (hard to upgrade).
  - **Less reliable** (if the network fails, everything fails).

### Generalized End-to-End View?
- **Bigger Picture:** Not just networks—this idea applies to many systems!
- **Example:** In a self-driving car, the car itself (not the road) should decide how to avoid accidents.
- **Rule:** Keep the system simple, and let the "ends" (users/devices) handle complex tasks.

### What Can We Learn From This?
1. **Don't overcomplicate the middleman** (network/roads/software).
2. **Trust the endpoints** (they know best what they need).
3. **Simpler systems are easier to fix and improve.**

### When Should the Network Do More?
Sometimes, the network **should** help:
- **Basic checks** (e.g., "Is this message too big to send?").
- **Performance boosts** (e.g., caching videos closer to users).
- **Emergency fixes** (e.g., rerouting traffic if a cable breaks).
- **But:** Only if it doesn't break the end-to-end rule!

**Remember:** The internet works because it's simple. Apps (not the network) handle the hard stuff!

## 9. NETWORK INFRASTRUCTURE

### A Network is Like a "Mostly Reliable" Post Office
- Imagine sending letters (data) through a post office (network).
- **Mostly works:** Letters usually arrive, but sometimes get lost or delayed.
- **No guarantees:** Like mail, networks try their best but can't promise perfection.
- **Why?** Traffic jams, broken cables, or overloaded servers can cause issues.

### Network Components
1. **Devices (Computers, Phones, Servers)** – Like people sending/receiving mail.
2. **Routers & Switches** – Like post offices that sort and forward mail.
3. **Cables/Wi-Fi** – Like roads and airplanes that carry mail.
4. **Protocols (Rules)** – Like postal rules (how to write addresses, stamp letters).

### Internet Topology
- **"Topology" = Shape of the Network**
  - **Star Topology:** All devices connect to one central router (like a main post office).
  - **Mesh Topology:** Many connections between devices (like many post offices working together).
  - **Hybrid:** Mix of both (most real networks, like the internet).

## 10. NETWORK PROTOCOLS

### Protocol Layering
- **What?** Breaking network tasks into simple, separate steps (layers).
- **Why?** Easier to fix/upgrade one layer without breaking others.
- **Example (Like Sending a Letter):**
  | **Layer** | **Task** |
  |-----------|---------|
  | **Application** | Write the letter (email, website request). |
  | **Transport** | Put in envelope, add address (TCP/IP). |
  | **Network** | Post office sorts mail (routers pick best path). |
  | **Physical** | Mail truck delivers (cables/Wi-Fi carry data). |

### Protocol Layering Example (Web Browsing)
1. **Application Layer (Chrome/Firefox)** – You type "www.google.com".
2. **Transport Layer (TCP)** – Breaks your request into small packets.
3. **Network Layer (IP)** – Adds addresses so routers know where to send data.
4. **Physical Layer (Wi-Fi/Ethernet)** – Sends as electrical signals/radio waves.

**Reverse at Google's Server:**
- Physical → Network → Transport → Application → You see the Google page!

## TCP/IP PROTOCOLS

### Basic Elements of Any Protocol Header
Every data packet has a **header** (like an envelope) that contains:
- **Sender & Receiver Address** (Where to send/return the data).
- **Type of Data** (Is it a webpage, video, or email?).
- **Size & Order** (How big is it? Is it part 1, 2, or 3?).
- **Error Checks** (Is the data damaged?).

### Demuxing Fields
- **"Demuxing" = Sorting Mail at the Post Office**
- The header helps the computer **sort incoming data** to the right program (e.g., email goes to Outlook, video goes to YouTube).

### IP (Internet Protocol)

#### 1. IP Address
- Like a **home address** for your computer on the internet.
- Example: `192.168.1.1` (IPv4) or `2001:0db8:85a3::8a2e:0370:7334` (IPv6).

#### 2. IP(v4) Address Format
- Made of **4 numbers (0-255)** separated by dots.
- Example: `192.168.1.1`
  - First part (`192.168`) = **Network** (like a city).
  - Last part (`1.1`) = **Device** (like your house).

### UDP (User Datagram Protocol)
- **Fast but Unreliable** (like sending a postcard).
- No guarantee it arrives.
- Used for:
  - Video calls (Zoom, Skype).
  - Online games (fast updates matter more than errors).

### TCP (Transmission Control Protocol)
- **Slow but Reliable** (like sending a registered letter).
- Guarantees data arrives **in order** and **without errors**.
- Used for:
  - Websites (Chrome, Firefox).
  - Email (Gmail, Outlook).

#### 1. TCP Pipeline
- Sends multiple packets at once (like a conveyor belt).
- If one packet is lost, only that one is resent.

#### 2. TCP Windowing
- Adjusts speed based on network traffic (like a car slowing down in traffic).
- Prevents overloading the connection.

### UDP vs. TCP Comparison

| Feature          | **UDP**                          | **TCP**                          |
|------------------|----------------------------------|----------------------------------|
| **Speed**        | Fast (no checks)                 | Slower (checks data)             |
| **Reliability**  | No guarantee                     | Guaranteed delivery              |
| **Use Case**     | Video calls, gaming              | Websites, emails, downloads      |

### SCTP (Stream Control Transmission Protocol)
- **Mix of TCP and UDP** (reliable but faster).
- Used for:
  - Phone calls over the internet (VoIP).
  - High-speed trading (needs speed + reliability).

### Summary
- **IP** = Internet address system.
- **UDP** = Fast but risky (good for videos/games).
- **TCP** = Slow but safe (good for websites/emails).
- **SCTP** = Best of both (used for calls/finance).
