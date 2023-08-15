# OpenWrt Multi daloRADIUS Versi 1.3 and 2.0 PHP7.4 - FW OpenWrt 21.02.3 LE 28 Mod by @reyre
![Hotspot-Login](https://github.com/masbroo69/OpenWrt-Daloradius-V2.0/assets/28827754/39bce07b-cff4-4ad0-928a-a5c4ac4ec139)
![Hotspot-Login](https://github.com/masbroo69/OpenWrt-Daloradius-V2.0/assets/28827754/f2c7991f-9a96-4a7f-aff5-0b543617c644)
daloRADIUS is an advanced RADIUS web management application aimed at managing hotspots and general-purpose ISP deployments. It features user management, graphical reporting, accounting, a billing engine and integrates with GoogleMaps for geo-locating.

![DaloradiusGraph](https://github.com/masbroo69/OpenWrt-Daloradius-V2.0/assets/28827754/b0866afe-38b8-454a-aa7a-141b2394e825)
daloRADIUS is written in PHP and JavaScript and utilizes a database abstraction layer which means that it supports many database systems, among them the popular MySQL, PostgreSQL, Sqlite, MsSQL, and many others. It is based on a FreeRADIUS deployment with a database server serving as the backend. Among other features it implements ACLs, GoogleMaps integration for locating hotspots/access points visually and many more features.

![LuCI](https://github.com/masbroo69/OpenWrt-Daloradius-V2.0/assets/28827754/bdfa46e7-fed6-41f0-b5d8-fca1a79124d2)
OpenWrt 21.02.3 LE 28 and FiberHome HG680P with more packages ported, more devices supported, better performance, and special optimizations for users. Compared the official one, we allow to use hacks or non-upstreamable patches / modifications to achieve our purpose. Source from anywhere.

**Firmware information:**
    
    - Firmware OpenWrt 21.02.3 LE 28 HG680P Kernel 5.4.204-reyre | REYRE-STB Mod by @reyre
    - Tested on STB HG680P
    - Themes AlphaOS by @derisamedia
    - Freeradius3, CoovaChilli, PHP7, MariaDB, etc
    - Default IP: 192.168.1.1
    - Default username: root
    - Default password: indonesia
    - Default WIFI name: WiFi
    - Default WIFI password: none

**This is a list of luci applications installed in this firmware:**

    - Pass Wall 
    - OpenClash
    - Libernet
    - Xderm-Mini
    - v2rayA (The password and username are the same as luci's)
    - NetMonitor and bandwidthd
    - Amlogic Service
    - File Manager tinyfm
    - AdGuardHome (The password and username are the same as luci's)
    - Load Balancing
    - ZeroTire

**Features Fix for Daloradius v2.0:**  

    - Server Status and Information
    - Users and Hotspots Management Graphs
    - Batch Add Users Management (Random User, Pass and PIN)
    - Management Users Listing (When importing Batch Add Users)
    - List Profiles Configuration
    - Management Users Listing
    - Printable Tickets with qrCode
    - Plans Management Currency with IDR
    - Settings Primary Language with Indonesia
    - WISPr-Bandwidth-Max-Up (Upload not leaking)
    - Login by role (Voucher, Member and Trial)
    - Test User Connectivity and Disconnect User,
    - All reports that display graphs work fine, 
    - Responsive Web-UI and Graph for phone or tablet, etc
