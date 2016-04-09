# MoxaNportScan
enumerate Moxa Nport devices,and read the target device information,Password setting status
# Moxa NPort Device Vulnerabilities info
[ Rapid7:R7-2016-01](https://community.rapid7.com/community/infosec/blog/2016/03/17/r7-2016-01-null-credential-on-moxa-nport-cve-2016-1529)

[ DigitalBond Labs:DBLABS-2016-01](http://www.digitalbond.com/labs/advisories/dblabs-2016-01/)

[ ICS-CERT ALERT:ICS-ALERT-16-099-01](https://ics-cert.us-cert.gov/alerts/ICS-ALERT-16-099-01 )
# Search Dork
 ZoomEye:[MoxaHttp] (https://www.zoomeye.org/search?q=MoxaHttp)

 Shodan:[MoxaHttp] (https://www.shodan.io/search?query=MoxaHttp)
# Scan verification
simple.csv is some validation data,from our scanner [icsresearch2.plcscan.org](https://icsresearch2.plcscan.org)

# Usage script
1、copy moxa-enum.nse to nmap script folder

2、run `nmap -sU --script moxa-enum -p 4800 <target ip>`
