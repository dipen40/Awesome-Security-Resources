## Vulnerability Attacks

- [Clickjacking](https://github.com/D4Vinci/Clickjacking-Tester) - Clickjacking is an attack that fools users into thinking they are clicking on one thing when they are actually clicking on another. 
     - [Reference CVE]()
        -   [2017](https://cwe.mitre.org/data/definitions/1021.html)

- [Session Hijacking](https://github.com/OWASP/www-project-web-security-testing-guide/blob/master/v41/4-Web_Application_Security_Testing/06-Session_Management_Testing/03-Testing_for_Session_Fixation.md) - In these cases, vulnerable web applications authenticate users without first destroying existing sessions associated with said users. This allows attackers to access users' accounts by hijacking their active sessions. 
     - [Reference CVE]()
        -   [2021](https://hackerone.com/reports/1201396)
        -   [2021](https://www.cvedetails.com/cve/CVE-2021-36320/)

- [SQL Injection](https://github.com/sqlmapproject/sqlmap) - sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers. 
[@Payload](https://github.com/payloadbox/sql-injection-payload-list)
     - [Reference CVE]()
        -   [2022](https://www.cvedetails.com/vulnerability-list/opsqli-1/sql-injection.html)
     
- [Web Cache Poisoning](https://portswigger.net/web-security/web-cache-poisoning) - Cache poisoning is a type of cyber attack in which attackers insert fake information into a domain name system (DNS) cache or web cache for the purpose of harming users.
    - [Reference CVE]()
        -   [2021 - Poisoning your Cache for 1000$ - Approach to Exploitation Walkthrough](https://galnagli.com/Cache_Poisoning/)

- [XSS](https://github.com/daffainfo/AllAboutBugBounty/blob/master/Cross%20Site%20Scripting.md) - Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted web sites. <br>
[@Payloads](https://github.com/payloadbox/xss-payload-list/blob/master/Intruder/xss-payload-list.txt)
[@Practice](https://prompt.ml/0)
     - [Reference CVE]()
        -   [2021](https://www.cvedetails.com/vulnerability-list/year-2021/opxss-1/xss.html)
