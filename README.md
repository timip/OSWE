# AWAE/OSWE

Preparation for coming AWAE Training. 
Work in progress...

## Atmail Mail Server Appliance: from XSS to RCE (6.4) CVE-2012-2593
- https://www.exploit-db.com/exploits/20009
- https://github.com/sourceincite/poc/blob/master/SRC-2016-0012.py

## ATutor Authentication Bypass and RCE (2.2.1) CVE-2016-2555
- Install: https://sourceforge.net/projects/atutor/files/atutor_2_2_1/
- https://www.exploit-db.com/exploits/39514
- https://srcincite.io/advisories/src-2016-0009/
- https://www.exploit-db.com/exploits/39639
- https://github.com/atutor/ATutor/commit/d74f1177cfa92ed8e49aa65f724f308b4a3ac5b9

## ATutor LMS Type Juggling Vulnerability (<=2.2.1) CVE-?
- Install: https://sourceforge.net/projects/atutor/files/atutor_2_2_1/
- https://srcincite.io/advisories/src-2016-0012/
- https://github.com/sourceincite/poc/blob/master/SRC-2016-0012.py
- https://github.com/atutor/ATutor/commit/2eed42a74454355eddc7fc119e67af40dba1a94c
- Reference: PHP Type Juggling
  - https://www.youtube.com/watch?v=ASYuK01H3Po
  - https://www.netsparker.com/blog/web-security/type-juggling-authentication-bypass-cms-made-simple/

## ManageEngine Applications Manager AMUserResourcesSyncServlet SQL Injection RCE CVE-?
- Install: http://archives.manageengine.com/applications_manager/12900
- https://manageenginesales.co.uk/2018/05/manageengine-applications-manager-build-13730-released/
- https://www.postgresql.org/docs/9.4/functions-binarystring.html
- https://www.mulesoft.com/tcat/tomcat-jsp
- Extra: Deserialization Vulnerability
  - https://www.geeksforgeeks.org/serialization-in-java/
  - https://github.com/frohoff/ysoserial
  - https://blog.jamesotten.com/post/applications-manager-rce/

## Bassmaster NodeJS Arbitrary JavaScript Injection Vulnerability (1.5.1) CVE-2014-7205
- Install: npm install bassmaster@1.5.1
- https://www.npmjs.com/package/bassmaster
- https://www.rapid7.com/db/modules/exploit/multi/http/bassmaster_js_injection
- https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/multi/http/bassmaster_js_injection.rb
- https://www.exploit-db.com/exploits/40689
- https://vulners.com/nodejs/NODEJS:337

## DotNetNuke Cookie Deserialization RCE (<9.1.1) CVE-2017-9822
- Install: https://github.com/dnnsoftware/Dnn.Platform/releases/tag/v9.1.0
- https://www.blackhat.com/docs/us-17/thursday/us-17-Munoz-Friday-The-13th-Json-Attacks.pdf
- https://media.blackhat.com/bh-us-12/Briefings/Forshaw/BH_US_12_Forshaw_Are_You_My_Type_WP.pdf
- https://gist.github.com/pwntester/72f76441901c91b25ee7922df5a8a9e4
- https://paper.seebug.org/365/
- https://www.youtube.com/watch?v=oUAeWhW5b8c
- https://vulners.com/seebug/SSV:96326
- https://www.slideshare.net/MSbluehat/dangerous-contents-securing-net-deserialization
- https://www.exploit-db.com/docs/english/44756-deserialization-vulnerability.pdf
