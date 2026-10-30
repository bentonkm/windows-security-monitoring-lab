\# Lab 3: Windows Event Viewer Analysis



\## 1. Objective



Review Windows System and Security logs to understand system activity and identify events requiring investigation.



\## 2. Tools Used



\* Windows Event Viewer

\* Windows 11

\* Windows System Logs

\* Windows Security Logs



\## 3. System Log Findings



\* Total events: 37,120.

\* Event ID 158: Time-Service informational event.

\* Event ID 4266: TCP/IP warning involving failure to allocate a temporary UDP port because the available port space was exhausted.



\## 4. Security Log Findings



\* Total events: 31,870.

\* Event ID 4798: Local group membership enumeration.

\* Event ID 4624: Successful logon.

\* Event ID 4672: Special privileges assigned to a new logon.



\## 5. Logon Investigation



Event ID: 4624



\* Logon Type: 5 (Service Logon).

\* Account: NT AUTHORITY\\SYSTEM.

\* Process: services.exe.

\* Network activity: No network information reported.



The event is consistent with normal Windows service activity.



\## 6. Conclusion



Windows Event Viewer provided useful information about system operations, network warnings, account activity, and successful logons.



The reviewed events did not establish evidence of malicious activity.



\## 7. Skills Demonstrated



\* Windows Event Viewer navigation.

\* System log analysis.

\* Security event identification.

\* Windows logon investigation.

\* Basic security documentation.



