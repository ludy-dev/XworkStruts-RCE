# XworkStruts-RCE
(CVE-2017-5638) XworkStruts RCE Vuln test script

The Jakarta Multipart parser in Apache Struts 2 2.3.x before 2.3.32 and 2.5.x before 2.5.10.1 has incorrect exception handling and error-message generation during file-upload attempts, which allows remote attackers to execute arbitrary commands via a crafted Content-Type, Content-Disposition, or Content-Length HTTP header, as exploited in the wild in March 2017 with a Content-Type header containing a #cmd= string.

Usage>

    python XworkStruts RCE (CVE-2017-5638).py <dst_ip> <dst_port> (user defined port)
    
    python XworkStruts RCE (CVE-2017-5638).py <dst_ip> (default : 80/tcp)

[updated!]
Script was editted for Python3 

Just using Vuln Test for your System
