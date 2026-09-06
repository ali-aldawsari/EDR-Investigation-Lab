 EDR Investigation Lab

 Overview

A hands-on EDR investigation lab focused on detecting Windows user account creation activity using Windows Security Logs.

 Use Case

User Account Creation Detection

The objective was to simulate user account creation activity and investigate the resulting Windows security event.

 Lab Environment

- Windows Server 2019
- VirtualBox
- Windows Security Event Logs

 Investigation Steps

 1. Lab Overview

Defines the investigation scenario, use case, and Windows Server 2019 lab environment.

[Lab Overview](1.png)

 2. Simulated User Account Creation

Created a test user account to generate a Windows security event for investigation.

[User Account Creation](22.png)

 3. Security Log Review

Reviewed Windows Security Logs to investigate security-related activity and identify relevant events.

[Security Log Review](3.png)

 4. Event ID 4720 Filtering

Filtered the Security log for Event ID 4720, which indicates that a user account was created.

[Event ID 4720 Filtering](4.png)

 5. Event ID 4720 Analysis

Analyzed Event ID 4720 and confirmed the creation of the `SOCLab` user account.

[Event ID 4720 Analysis](5.png)

 Key Findings

- Detected a new user account creation event.
- Identified Event ID 4720 as the relevant Windows security event.
- Reviewed event details to identify the created account.
- Practiced a basic SOC investigation workflow using Windows Security Logs.

 Skills Demonstrated

- EDR Investigation
- Windows Event Log Analysis
- Security Event Identification
- Event ID 4720 Analysis
- User Account Activity Monitoring
- Basic SOC Investigation
