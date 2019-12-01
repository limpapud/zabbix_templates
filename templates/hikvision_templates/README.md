### Brief information:

**hikvision_templates** is a zabbix template for Hikvision company NVR's (Network Video Recorder) using SNMPv2. Tested on Zabbix v4.4 and Hikvision NVR 9664-i8

### Sources used:

- [Hikvision MIB]( http://www.circitor.fr/Mibs/Mib/H/HIKVISION-MIB.mib) - Management Information Base of Hikvision vendor.
- [MIB Browser]( https://www.manageengine.com/products/mibbrowser-free-tool/) - free MIB browser from ManageEngine
- [snmpwalk]( ) - an SNMP application that uses SNMP GETNEXT requests to query a network entity for a tree of information

###  Information covered by a template:

- Low Level Discovery
- - *LLD of installed HDD's*
- Triggers
- - *HDD count change* 
- - *HDD state change*
- Items
- - *Count of installed HDD's*
- Mappings
- - *HDD disk state mappings*

### Planned functionality:

- Adding generic SNMP items (NIC interfaces, uptime, product name, e.t.c)
- LLP of HDD capacity and free space
- Triggers for free space control


Files
-------------------
Existing filed and descriptions are as below:

Main folder:

> - *template_hikvisionNVR.xml* - Zabbix template.
> - *HIKVISION-MIB.mib* - MIB file from [www.circitor.fr]( http://www.circitor.fr/Mibs/Mib/H/HIKVISION-MIB.mib)

Contributions
----------------------
Want to contribute? That is great! Please **Fork** and **Pull** to main branch.

> **Notes:**
> - Author appreciates any size of contribution.
> - Have some **Issues** or thoughts to share? You can share it via opening *Issue* or sending an  email that is mentioned in the end of page to author.

Usage and Licencing
-------------
Project is distributed with **MIT** licence.
> **That mean that:**
> - This software and derivatives **may be used for commercial purposes**
> - This software **may be modified**
> - This software **may be distributed**
> - This software **may be used and modified in private**
> - This licence includes a **limitation of liability**
> - This licence explicitly states that it **DOES NOT provide any warranty**
> - A copy of the licence and copyright notice must be included with the software.


### Contact

You can contact with author through [![](https://www.shareicon.net/data/16x16/2015/11/02/665918_email_512x512.png)](mailto:omarbayramov@hotmail.com) **omarbayramov@hotmail.com** mail.
Additionaly I am adding links to social network accounts and blog.

[Facebook![](https://www.shareicon.net/data/32x32/2016/06/20/606800_facebook_48x48.png)](https://www.facebook.com/Omar.X.Bayramov) [Wordpress![](https://www.shareicon.net/data/32x32/2016/07/14/606997_wordpress_64x64.png)](https://omarbayramov.wordpress.com/) [LinkedIn![](https://www.shareicon.net/data/32x32/2016/06/20/606446_linkedin_48x48.png)](https://www.linkedin.com/in/omarbayramov/)