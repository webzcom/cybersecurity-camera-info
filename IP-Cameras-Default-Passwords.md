# IP Cameras Default Passwords

## Resource
- https://ipvm.com/reports/ip-cameras-default-passwords-directory


REPORTS
PUBLIC
IP Cameras Default Passwords Directory
Avatar
Ethan Ace
•
Published Feb 09, 2018 05:33 AM
PUBLIC - This article does not require an IPVM subscription. Feel free to share.
Below is a directory of 50+ manufacturer's default passwords.

Note: Change Default Passwords

Leaving default passwords is dangerous and makes it easy for even inexperienced attackers to take control, brick or watch your video feed. Worse, since many cameras are made available over the Internet (often because of another risky practice, port forwarding or because the manufacturer defaulted UPnP on), the cameras may be attacked from anywhere in the world.

Manufacturer List Default Passwords

While IPVM strongly recommends using complex passwords, users may still need to know defaults when cameras are first configured or factory defaulted, and finding these credentials can be aggravating, with many manufacturers burying them in PDF manuals or not documenting them at all.

For each manufacturer, we list the username first and pasword section in the following format: username/password. Where manufacturers have multiple defaults, or differences in newer/older firmwares, we have noted it:

- ACTi: admin/123456 or Admin/123456
- Amcrest: admin/admin
- American Dynamics: admin/admin or admin/9999
- Arecont Vision: none
- AvertX: admin/1234
- Avigilon: Previously admin/admin, changed to Administrator/<blank> in later firmware versions
- Axis: Traditionally root/pass, new Axis cameras require password creation during first login (note that root/pass may be used for ONVIF access, but logging into the camera requires root password creation)
- Basler: admin/admin
- Bosch: None required, but new firmwares (6.0+) prompt users to create passwords on first login
- Brickcom: admin/admin
- Canon: root/camera
- Cisco: No default password, requires creation during first login
- Dahua: Requires password creation on first login. Previously this process was recommended but could be canceled; older models default to admin/admin
- Digital Watchdog: admin/admin
- DRS: admin/1234
- DVTel: Admin/1234
- DynaColor: Admin/1234
- FLIR: admin/fliradmin
- FLIR (Dahua OEM): admin/admin
- FLIR (Quasar/Ariel): admin/admin
- Foscam: admin/<blank>
- GeoVision: admin/admin
- Grandstream: admin/admin
- Hanwha: admin/no default password, must be created during initial setup
- Hikvision: Firmware 5.3.0 and up requires unique password creation; previously admin/12345
- Honeywell: admin/1234
- IndigoVision (Ultra): none
- IndigoVision (BX/GX): Admin/1234
- Intellio: admin/admin
- Interlogix admin/1234
- IQinVision: root/system
- IPX-DDK: root/admin or root/Admin
- JVC: admin/jvc
- Longse: admin/12345
- Lorex: admin/admin
- LTS: Requires unique password creation; previously admin/12345
- March Networks: admin/<blank>
- Mobotix: admin/meinsm
- Northern: Firmware 5.3.0 and up requires unique password creation; previously admin/12345
- Oncam: admin/admin
- Panasonic: Firmware 2.40 and up requires username/password creation; previously admin/12345
- Pelco: New firmwares require unique password creation; previously admin/admin
- Pixord: admin/admin
- Q-See: admin/admin or admin/123456
- Reolink: admin/<blank>
- Samsung Electronics: root/root or admin/4321
Samsung Techwin (old): admin/1111111
Samsung (new): Previously admin/4321, but new firmwares require unique password creation
Sanyo: admin/admin
Scallop: admin/password
Sentry360 (mini): admin/1234
Sentry360 (pro): none  
Sony: admin/admin
Speco: admin/1234
Stardot: admin/admin
Starvedia: admin/<blank>
Sunell: admin/admin
SV3C: admin/123456
Swann: admin/12345 
Trendnet: admin/admin
Toshiba: root/ikwd
VideoIQ: supervisor/supervisor
Vivotek: root/<blank>
Ubiquiti: ubnt/ubnt
Uniview: admin/123456
W-Box (Hikvision OEM, old): admin/wbox123
W-Box (Sunell OEM, new): admin/admin
Wodsee: admin/<blank>
If we have missed a manufacturer or made errors, please comment (or email info@ipvm.com) and we will add/fix it.

Missing? May Be An OEM

Dahua and Hikvision have 100+ relabelers/OEMs and many of them may simply use the same password requirements as their base manufacturer. If your chosen manufacturer is not listed, check our Hikvision OEM Directory and Dahua OEM Directory to see if they may be relabeled.

Strong Password Measures Increasing

Industry insights delivered to your inbox weekly.
Sign up to get notified of new reports, investigations, research and more.

Your email address
This site is protected by reCAPTCHA and the Google Privacy Policy and Terms of Service apply.

Several manufacturers, including Hanwha, Hikvision, and Panasonic, now require unique passwords by default, with most requiring a mix of upper and lowercase letters, numbers, and special characters, seen below.



Others do not require unique passwords, but prompt users to set strong passwords when logging into the camera. For example, Bosch displays the message when logging into cameras using firmware 6.20 and above. Dahua includes a similar prompt.



Readers should see our IP Camera Passwords Report for more information on these manufacturers and methods. 

Using Default Passwords

The use of default passwords in production systems is considered poor practice. At the very least, all surveillance network devices, including cameras, clients, and servers, should be changed from the defaults with strong passwords, documented in a secure location. This prevents access to the network using simple password guessing, requiring a more skilled attacker and more complex methods.

However, there are many who still claim default passwords are fine, especially if the surveillance system is on a dedicated network, without access to other client systems. Doing so may also make it easier for techs to access cameras, but anyone with access to the network (authorized or not) may use the default password to access cameras.

Readers should see our Network Security for IP Video Surveillance Guide for more information on passwords and other security measures.

Real World Risk: Mirai Botnet Use of Default Passwords

Waves of unprecedented botnet attacks against major Internet sites have been driven by hacked video surveillance devices that make use of default passwords plus telnet access. This is a powerful example of why default passwords should not be used nor should they be allowed to be used after setup.

For more on this and other vulnerabilities, see our Directory of Video Surveillance Cybersecurity Vulnerabilities and Exploits.

[Note: This post was originally published in 2012 but was substantially revised and updated with new camera information and changes in default password approach for 2016 and 2018]

9 REPORTS CITE THIS REPORT

Factory Default Enclosure Lock Vulnerability Examined
Factory Default Enclosure Lock Vulnerability Examined

Access control systems are typically high security, but a serious, "industry wide" flaw —enclosures secured by default...

Locking Down Network Connections Guide
Locking Down Network Connections Guide

Accidents and inside attacks are risks when network connections are not locked down. Security and video surveillance...

Default Passwords Outlawed in California, US To Follow
Default Passwords Outlawed in California, US To Follow

A new California bill aimed at improving security for connected devices has been signed into law. The law takes aim...

IPVM Vulnerability Scanner Released / Deprecated
IPVM Vulnerability Scanner Released / Deprecated

IPVM is proud to announce video surveillance's first and only cybersecurity vulnerability scanner. This tool allows...

Arecont and Bosch - Default Security Risk
Arecont and Bosch - Default Security Risk

Default passwords are a major security risk, enabling hackers around the world to access and control devices like IP...

Axis Cybersecurity Hardening Guide Examined
Axis Cybersecurity Hardening Guide Examined

In most IT areas, 'hardening' guides are commonplace, providing best practices for improving the cybersecurity of...

IP Camera Trolling - Cybersecurity Showcase
IP Camera Trolling - Cybersecurity Showcase

If you want to convince your customers about the importance of cybersecurity and the risk of being the next Hikvision,...

ONVIF Profile Q Aims To Change Discovery and Default Passwords
ONVIF Profile Q Aims To Change Discovery and Default Passwords

ONVIF is gearing up to release a new profile, called Q. They market it as providing "quick configuration and...

IP Camera Passwords - Axis, Dahua, Samsung
IP Camera Passwords - Axis, Dahua, Samsung

IP cameras are famous / infamous for weak default passwords that can lead to major problems. See our IP Cameras Default...

IPVM is the world's authority on physical security technology, profiled by Time, The Atlantic, Wired and collaborated with the BBC, NY Times, Reuters, WaPo, WSJ, and more.

Site map
About
Contact
FAQ
Tests
Favorite Products
Worst Products
Share A Tip
Online Shows
Calculator
Privacy Policy
Industry insights delivered to your inbox weekly.
Sign up to get notified of new reports, investigations, research and more.

Your email address
This site is protected by reCAPTCHA and the Google Privacy Policy and Terms of Service apply.

