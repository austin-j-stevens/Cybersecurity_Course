This is just a overview of what I had learned about throughout the duration of the course by week. 
There are subfolders as well which detail some of the examples of the work done to illustrate the capacity to complete the tasks talked about. 



**** Week 1 ****

The first week was mostly just setting up the enviroments we would be using for most of the course. Getting to know our fellow classmates and an introduction to the different career paths and opportunities within the Cybersecurity and Information Security fields.
Going over the general topics such as the question of "What is information security?" and "Why does security matter?"
These are good questions to be asking through each step of the program. Each of the modules would have their own unique answer. 
We also started right away with the CIA triad. Ensuring we understand the different areas of security and how to discern between confidentiality, integrity, and availability. 
Moving from that we moved into the different types of attacks. Such as database attacks, network attacks, and user attacks. 
Going over the different certifications as well. Mainly the Security+ exam. But also researching other ones that sound interesting. We went over it more towards the end of the class. 


----Main Sections----
# Class introductions
# Going over syllabus
# Career options
# CIA triad
# Different types of attacks
# Certification research
# Setting up vagrant machines



**** Week 2 ****

Started off with understanding security within a organization. How it functions within a company and understanding why it is necessary.
Going over the structure of the company from different teams, differnt levels of access, and the responsibilities of the different employees. From the general population to the C-suite users. 
Learned about security controls, identifying threats, possible attacks/exploits. And how to justify the controls to a risk. 
Thoroughly went over the governance and compliance framework along with BCP/DR.
Utalized OWASP to create risk analysis spreadsheets and a heat map for the risk assessment.

----Main Sections----
# Organazation roles and responsibilities 
# Security structure within a organization
# Security controls
# Threat and risk identification
# Governance and compliance
# Owasp and risk analysis



****Week 3****

Beginning with the technical side of the program we began our introduction into terminal. Learning about the different commands within the Linux framework and using them in different activities. 
Started off pretty basic with just navigating the file system of the Ubuntu vagrant machine. Then going into differnt commands that would assist in future coursework and activities. Working with 'find', 'grep', 'awk', and 'sed'.
Using the differnt commands in tandem was necessary to learn, along with how to utalize them to the fullest potential. 

----Main Sections----
# Introduction to terminal and the Linux system
# working with the different basic terminal commands (ls, cd, touch, mkdir, ect...).
# Understanding the structure of the terminal commands
# creating strings of commands for specific outputs



****Week 4****

Continuing on with the Linux architecture fundementals. We began with researching many differnt distros, along with their pro's and con's.
Managing processes within the terminal with commands like 'top', 'ps', and 'kill'.
Working with 'apt' and how to update different elements of the system. 
Managing different access controls. Starting with auditing passwords for users, elevating privileges, and creating and managing groups.
Going over the file permissions and monitoring services as well. 

----Main Sections----
# Linux distro research
# Managing processes through terminal
# Using the package installer
# Access controls such as passwords and groups
# Verifying and modifying file permissions
# Monitoring system processes



****Week 5****

Going even further into the terminal was understanding the automation and redundency of how systems should be configured. 
Working on creating and extracting files within a tar ball. 
Creating and implementing cron jobs on the system for automated maintenance and backups.
And managing the log files on the system. Creating backups and rotating the log files. 

----Main Sections----
# Using tar/untar
# Creating cron jobs
# Managing and monitoring log files.



****Week 6****

The last section of the Linux terminal was focusing on adding in everything we had learned so far, and making it into scripts. 
We created basic scripts that would do things such as zip the current logs and replace the old logs on the system after a certain amount of time. 
Understanding compound commands using && or | within the string structure. 
Using bash to run scripts with differnt variables and user inputs. 
And a scavenger hunt through the system files of the vagrant machine looking for different flags. 

----Main Sections----
# Scripting with bash
# Using all of the commands learned to locat files on the system that were hidden 
# Compound commands
# Creating scripts with variables



****Week 7****

Changing from the Linux architecture, we bagan unit 7 with the Windows Command Prompt. Using wmic and task manager to manage processes, gpedit to modify password policies. 
We also touched on the different tools for automation by scheduling tasks to run with the Task Scheduler. 
Using Powershell cmdlets and pipelines to navigate Windows and retrueve system events. And scripting within Powershell. 
Then we started in on Active Directory, learning about domain controllers and using the tools within AD to create, monitor, and manager links to group policy objects and users and computers. 

----Main Sections----
# Powershell commands and scripts
# Active Directory tools
# Navigating Windows architecture
# Automating system functions and security features
# Managing users, groups, and computers



****Week 8****

This week we covered the interworkings of a network and the architecture that goes along with it. 
We learned how to identify different requests and responses such as GET and PUT. Understanding network topologies and compare advantages and disadvantages between the different types. 
Took a deep dive into binary and how to convert to decimal format. Going over the ports and protocols that are well known. And understanding how the system works in the way that it does. 
Talked abou the OSI model, ensuring we understood each of the 7 layers. 
Analyzing traffic on the network with Wireshark and using SYN scans to explore unknown networks. 

----Main Sections----
# OSI and TCP/IP model
# Binary, IPv4, IPv6, and MAC addresses
# Types of requests (ACK, SYN, ect)
# Packetsniffing with wireshark
# Network scans



****Week 9****

Going through NAT and DHCP to gain a full understanding of how it works and why it is used. Along with capturing the packets for further inspection. 
Working with routing architecture and creating pathways within activities identical to OSPF.
Capturing BSSID's and SSID's and using Aircrack-ng to get the wireless keys to view the wireless traffic captured within Wireshark. 
Validated DNS records with nslookup and going over email headers. 
Finished this section with a capture the flag competition. 

----Main Sections----

# Understanding NAT and DHCP
# Routing protocols
# Packet capturing
# Cracking wifi encryption
# Investigating DNS records
# Inspecting email headers
# Capture the flag event



****Week 10****

This week was all about cryptography. Starting with the basics of what is encryption, how it works, what makes a strong encryption and the difference between encoding and encrypting. 
Calculating symmetric and asymmetric keys needed for different hosts. 
Creating keys and using the keys to send and decrypt messages. Along with using hashing on those messages. 
Authenticating sites with SSL certificates, and using different attacks against passwords and hash values. 

----Main Sections----
# Intro to cryptography
# Encoding and Encrypting
# Calculating strength of encryption
# Generating keys and hash values
# Attacking and cracking passwords and hash's



****Week 11****


After attacking networks and devices we then started defending. Going over ports again and how they contribute to a device/networks defense.
We then were intruduced to the interworkings of firewalls and how they play such a large role in keeping networks safe from outside threats. We also learned about IDS and IPS systems and how they are different. 
I analyzed threats and protected against them with many different tools such as Security Onion, Snort, OSSEC, and others. 

----Main Sections----

# Firewall intruducion and configuration
# Snort rules and monitor
# Security Onion network monitoring
# IDS/IPS deep dive



****Week 12****

We began this week discussing the role of cloud computing within an organization. How differnt things can be a service such as software or infrastructure. 
We then began working within Azure to create a virtual private cloud network, firewall, and virtual computers within the Azure cloud. 
Ensuring that all access to the VNet could only be done through our local machines talking to a jumpbox. We also began working on setting up the containers with Docker. And making Ansible connections to the VM's within the network. 
Wrote playbooks to configure the VM's and ensure every time they booted up that they would ensure that all the proper software is installed and working properly. 
Created a load balancer within Azure for the differnt web servers, and a firewall to protect from unwanted traffic. 
To finish it up we verified the redundency by turning certain machines off and seeing where the traffic was directed. 

----Main Sections----

# SaaS, PaaS, IaaS, and others. 
# Creating firewall, VM, load balancer in Azure
# Writing yaml playbooks for ansible connections
# Creating docker containers
# Testing for redundency. 



****Week 13****

Now that we had created a network with devices that were secure. We needed to monitor them with an ELK stack. 
We set up the elastic search with filebeat, metricbeat, and packetbeat. 
I had to set up the containers using andsible and docker to ensure it functioned correctly through the script int the yaml file I had written for it. 
I needed to deploy another server within the vnet to host the server itself and allow it to communicate with my local machine so I can view and monitor the information on the ELK server site. 

----Main Sections----

# Created server for ELK
# Yaml scripting
# Installing beats
# Testing functionality of ELK server



****Week 14****

The first day of this week we bagan with HTTP sessions and cookies. Understanding the responses and requests. 
Making different requests such as GET and POST using 'curl' and managing the extensions with Chrome's audit tools. 
Understanding the microservices and the architecture used to learn about how to make more rebust, reliable, and.
