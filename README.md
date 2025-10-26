# Elevate-Lab-internship-task4

Firewall Configuration and Testing Using UFW on Kali Linux

Objective
The goal of this task is to configure and test a firewall using UFW (Uncomplicated Firewall) on Kali Linux. It demonstrates how to install, enable, manage, and verify firewall rules to control network traffic.

Environment
Operating System: Kali Linux
Firewall Tool: UFW
Access: Root privileges

Summary
Installation: UFW was installed along with required dependencies.
Activation: The firewall was enabled and set to start automatically on boot.
Rule Management: Existing rules were viewed in a numbered format for easy reference.
Blocking Traffic: Inbound traffic on port 23 (Telnet) was denied to prevent insecure connections.
Testing: Telnet access was tested and confirmed to be blocked.
Allowing Access: Port 22 (SSH) was allowed to maintain secure remote access.
Cleanup: Test rules were deleted to restore the firewall to its original state.

Concept Summary
A firewall filters network traffic based on predefined rules, protecting systems from unauthorized access.
Inbound rules control external traffic trying to enter the system.
Outbound rules control traffic leaving the system.
Filtering is based on ports, protocols, and IP addresses.

Conclusion

This exercise successfully demonstrated firewall configuration using UFW, showing how to block and allow specific network traffic while maintaining secure system access.
