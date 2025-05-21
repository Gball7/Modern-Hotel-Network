# Goals
The primary goal of this project was to design and implement a robust and secure network infrastructure across a three-floor building, ensuring seamless communication between departments while maintaining network segmentation, security, and scalability. Key objectives included VLAN configuration, DHCP setup, OSPF routing, remote access, and port security.

# My Solution
To meet these requirements, I designed a structured network topology using three routers (one per floor), connected via serial DCE links and configured with OSPF for dynamic routing. Each department was assigned a unique VLAN and IP subnet to ensure proper segmentation and traffic management. Switches were deployed on each floor, and DHCP was configured on routers to enable dynamic IP allocation.

I implemented SSH on all routers to enable secure remote access and configured port security in the IT department to restrict unauthorized device access using MAC address sticky learning. A test PC was added to verify remote connectivity and security configurations.

# Impact
The implemented solution successfully ensured secure inter-department communication, centralized IP address management, and remote access capabilities. The use of VLANs enhanced security and organization, while OSPF and DHCP improved network efficiency and scalability. This project demonstrated my ability to apply core networking principles in a real-world scenario and reinforced my skills in Cisco configurations, network design, and troubleshooting.
