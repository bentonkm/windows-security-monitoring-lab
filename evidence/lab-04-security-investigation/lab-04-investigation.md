\# Lab 4: Basic Security Investigation



\## 1. Objective



Review findings from previous Windows security monitoring labs and identify configuration or system issues requiring attention.



\## 2. Findings



\### Finding 1: Potentially Unwanted App Protection



\* PUA blocking was disabled.

\* This was an intentional user configuration.

\* Disabling this feature reduces protection against potentially unwanted applications.



\### Finding 2: TCP/IP Warning



\* Event ID: 4266.

\* Source: Tcpip.

\* Windows reported failure to allocate a temporary UDP port.

\* Further monitoring may be useful if the warning continues.



\### Finding 3: Windows Firewall



\* All three firewall profiles were enabled.

\* Public network was active during inspection.



\## 3. Recommended Actions



1\. Consider enabling potentially unwanted app blocking.

2\. Monitor recurring TCP/IP warnings.

3\. Keep Windows Firewall enabled.

4\. Keep Microsoft Defender security intelligence updated.



\## 4. Investigation Conclusion



The review identified one intentional security configuration weakness and one network-related system warning.



No confirmed malware infection or unauthorized access was established during these checks.



\## 5. Skills Demonstrated



\* Security finding identification.

\* Windows event investigation.

\* Risk awareness.

\* Basic incident documentation.



