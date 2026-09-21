# IIS Web Server Log Monitoring & Threat Detection

## Overview

This project demonstrates basic web server monitoring and log analysis using Microsoft IIS on a Windows test environment.

The objective was to host a test website, generate web requests, examine IIS logs, and understand how web server logs can be used for security monitoring and threat detection.

## Tools Used

* Windows Server
* Microsoft IIS
* IIS Access Logs
* Web Browser
* Basic Log Analysis

## Project Workflow

1. Installed and configured IIS on a Windows test environment.
2. Hosted a test website using IIS.
3. Accessed the website through a web browser.
4. Generated HTTP requests.
5. Located and inspected IIS log files.
6. Analyzed client IP addresses, HTTP methods, requested URLs, and HTTP status codes.
7. Reviewed the logs for unusual or repeated requests.
8. Documented how IIS logs can support SOC monitoring and investigation.

## Log Analysis

The following information was examined in the IIS logs:

* Client IP address
* HTTP method
* Requested URL
* HTTP status code
* HTTP sub-status code
* User agent
* Request timestamp

## Screenshots

### IIS Website

![IIS Website](screenshots/iis-website.png)

### IIS Logs

![IIS Logs](screenshots/iis-logs.png)

## Security Relevance

IIS logs can help a SOC analyst investigate activities such as:

* Repeated failed requests
* Web reconnaissance
* Directory or file enumeration
* Suspicious URL requests
* Unusual HTTP status codes
* Potential web-based attacks

## Future Improvements

* Forward IIS logs to Splunk or Wazuh.
* Create detection rules and alerts.
* Build a security monitoring dashboard.
* Simulate safe web reconnaissance in a controlled lab.
* Investigate suspicious source IP addresses and request patterns.

## Disclaimer

This project was performed in a controlled personal lab environment for cybersecurity learning and defensive monitoring purposes.

