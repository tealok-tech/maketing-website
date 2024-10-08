### **For the Technically Curious: Dive Into the Details**

Tealok is built on a foundation of robust technology, designed to offer unparalleled privacy, security, and ease of use. For those interested in what’s under the hood, here’s a closer look at the technical side of Tealok.

---

#### **The Hardware: Lar – Your Digital Powerhouse**

1. **Minisforum or Beelink Units**:
   
   - **Why We Chose Them**: Tealok runs on fully assembled, high-performance Minisforum or Beelink units. These all-in-one systems offer the right balance of power, efficiency, and cost, making them ideal for the needs of a modern digital home.
   - **Specs at a Glance**:
     - **Processor**: AMD Ryzen 9 series for optimal performance.
     - **Memory**: 32 GB of DDR5 RAM to handle multiple applications and processes.
     - **Storage**: 1 TB SSD for fast, reliable storage, with options for additional storage as needed.

2. **Customizability**:
   
   - **DIY Enthusiasts**: While we recommend our pre-assembled units for ease of use, Tealok can also be installed on custom-built hardware for those who prefer to tailor their system to specific needs. Our recommended specs are available for those who want to build their own Lar.

---

#### **The Software: Tealok – The Brain Behind the System**

1. **NixOS Foundation**:
   
   - **Why NixOS?**: Tealok is built on NixOS, a Linux distribution known for its reliability, reproducibility, and security. NixOS allows us to precisely manage system configurations and ensure that every Tealok deployment is consistent and stable.
   - **Containerization**: Tealok leverages Docker containers to isolate applications, ensuring that each service runs smoothly and securely without interfering with others.

2. **Key Software Components**:
   
   - **Tealok Core**: The central software that manages all operations, from data storage to application performance.
   - **Rclone**: Used for managing backups, Rclone ensures that your data is safely stored and easily recoverable.
   - **Postgres**: A robust and reliable database system that supports the backend operations of Tealok applications.

3. **Advanced Features**:
   
   - **Durable Storage**: Tealok’s storage system is designed to last, with automatic backups to ensure that your data is preserved even in the event of hardware failure.
   - **User Authentication**: Tealok includes a secure onboarding flow for setting up user accounts and managing access to services, ensuring that your data remains private and protected.

---

#### **Networking: Seamless and Secure Connectivity**

1. **Local and Remote Access**:
   
   - **DNS-SD for Service Discovery**: Tealok uses DNS-SD (Service Discovery) to make it easy for devices on your local network to find and connect to Tealok services.
   - **Public DNS Support**: For users running public-facing services like email or web hosting, Tealok supports custom DNS configurations, allowing you to manage your digital presence with ease.

2. **Security and Privacy**:
   
   - **TLS Certificates**: Tealok automatically provisions TLS certificates for secure connections, ensuring that all data transmitted over the network is encrypted and protected.
   - **VPN Support**: While not required, Tealok can integrate with VPNs like Tailscale to provide additional security and privacy for your networked services.

---

#### **Open Source and Community-Driven**

Tealok is not just a product; it’s a community. Our software is open source, and we welcome contributions from developers, engineers, and enthusiasts who share our vision of a more secure and empowering digital world.

1. **GitHub Repository**:
   
   - **Explore the Code**: Our full source code is available on GitHub. We encourage you to explore, fork, and contribute to the project.
   - **Issues and Feature Requests**: Have ideas or find a bug? Our GitHub repository is the place to submit issues, suggest features, and help improve Tealok.

2. **Future Development**:
   
   - **LLM Workloads**: We are exploring the potential for local LLM (Large Language Model) workloads, allowing users to run advanced AI models securely within their own home network.
   - **Networked Tealoks**: Imagine a network of Tealoks that share resources and capabilities. This is a future we are excited about, and we invite you to join us in making it a reality.

---

#### **Join the Tealok Community**

Whether you’re a seasoned developer or simply curious about the technology behind Tealok, we invite you to join our community. Together, we can build a digital future that prioritizes privacy, security, and empowerment.

**[Contribute to Tealok on GitHub]**

**[Join Our Community Forum]**