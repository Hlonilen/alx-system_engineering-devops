Issue summary: 

This postmortem report provides an in-depth analysis of the network incident that occurred on February 12, 2024, between 13:00 PM and 17:00 PM. The incident was caused by a network loop, which was detected and addressed following a rigorous diagnostic procedure. This event caused a network failure for all users in the firm, and users were unable to access online apps unless they were hosted locally on the company's LAN. This paper discusses the incident timeline, root cause analysis, impact assessment, and preventative steps to avoid such occurrences in the future.

Impact Details

❖Incident Date and Time: February 12, 2024, 13:00 PM — 17:00 PM
❖Incident Duration: 5 hours
❖Incident Severity: High
❖Incident Impact: Network performance degradation, service interruptions
❖Affected Systems/Services: Core network devices, various services
❖Incident Response Team: Network Operations Team, System Administrators

Timeline:

1.February 12, 13:00 PM: Abnormal network traffic patterns detected, indicating potential network issue.
2.February 12, 13:15 PM: Incident response team alerted, initial investigation launched.
3.February 12, 14:00 PM: Network devices inspected, logs reviewed to identify potential root causes.
4.February 12, 14:30 PM: Suspicion of network loop raised based on traffic patterns and device status.
5.February 12, 15:00 PM: In-depth analysis confirmed presence of network loop.
6.February 12, 15:30 PM: Network loop identified in the server room in a switch.
7.February 12, 16:00 PM: Loop removed, network traffic normalized.
8.February 12, 16:30 PM: Services gradually restored.
9.February 12, 17:00 PM: Incident resolved, network stability regained.

Root Cause:

The primary cause of the network failure was a network loop discovered in the server room. The loop was unintentionally created by an IT intern who was performing network troubleshooting on the network switch.

Resolution:

The network loop was discovered following extensive diagnostic and network troubleshooting. A log examination was undertaken to provide insight into any unusual network behavior, and physical inspection was used to identify the looping in the switch.

Corrective and Preventive Measures:

1.STP Implementation: Deploy Spanning Tree Protocol across the network.
2.Regular Audits: Periodic network configuration audits to identify and rectify misconfigurations.
3.Traffic Analysis: Implement traffic analysis tools to identify potential loop scenarios.
4.Segmentation and VLANs: Properly segment network traffic using VLANs (Virtual Local Area Networks) to isolate different segments, reducing the propagation of loops across the entire network.
