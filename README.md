# Ansible-for-Network-Automation
A basic skeleton framework for using Ansible for network automation tasks.

I regularly create automations in Python using Rest APIs (the Python `requests` library) or Netmiko for SSH, but I created this Ansible skeleton as well. I really don't like using Ansible as it feels quite restrictive when directly compared to Python / any other programming language, but it does serve a purpose for simplicity sake. 

The example skeleton represents a backup operation. When executed, (after some tweaking), this setup could call out to Cisco IOS, ASA, and NXOS devices and perform the system equivalent of a "show run" and export it to a file. This still could use some reporting and Git tracking built in, but that can be easily built on top of this skeleton. 

I hope this helps someone else, if not me in the future. Happy automating!

Also, a big note: rely heavily on the Ansible documentation. It's thorough, and it's detailed. It explains everything about every module with regards to requests/responses.
