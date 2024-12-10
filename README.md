# CYSE-PROJECT


**Project Overview:**
   The purpose of our project is to develop an autonomous system that continuously monitors a collection of files and scans them for potential malware threats.
This system will be designed to run in the background, automatically detecting and analyzing files in real-time or at regular intervals, without the need for manual intervention. 
By leveraging advanced scanning techniques and algorithms, the system aims to identify malicious software, such as viruses or malware, that could pose a threat to the integrity and security of the file system.
The goal is to ensure that any harmful files are detected promptly and quarantined or flagged for further analysis, and then an alert or notifaction is sent to and admin,
providing an added layer of protection against cybersecurity risks and helping maintain the overall safety and stability of the system.


**Installation:**
In order to install this software onto a desired system to scan for files, the user must download the script onto their device, the user would then need to give the script access to their system/device in order to grant it permission to scan the files on that system. Next, the user would need to input their email address into the script so the software knows who to send an alert to given a malicous file has been detected. Once the user has all of these steps completed, the software should autonomously scan the user’s system for malicous files and, in the case of a malicous file, the user’s provided email will be notified of such.


**Usage:**
In order for the system’s user to activate the software, all they need to do is run the script and the program will autonomously scan the files for malware and analyze the data it receives. Once active, the program will automatically parse the logs to check the user’s cpu usage, then, if the cpu usage on their device is over 2%, the program will alert the user that there may potentially be malicious activity in their system.


**Recommendations:**
There can be many improvements made to the system to ensure that it runs efficiently and to ensure that the script is correctly detecting suspicious files. For more security, training the system to detect the patterns of malware and comparing it to the scanned files can help with more accurately identifying harmful files. Tools to help monitor traffic flow such as NTA can also help with identifying suspiciously large file sizes. DNS filtering can be used to ensure that the domains that are commonly used by malware is blocked.

**Team Members:**

Our team members include: Jack Valcourt, Eli Stearns, Gianmarcos Serrano, Lamar Jackson, Emmanuel Oparaocha, and Ghazi Alotaibi.
