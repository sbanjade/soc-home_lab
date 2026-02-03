# SOC Home Lab (VMware + Ubuntu Server + Windows + Splunk)

## Overview
This project demonstrates a SOC-style home lab built to practice log monitoring, incident detection, and basic incident response.

## Lab Architecture
- Host: Windows (VMware Workstation)
- Ubuntu Server 22.04 LTS: SIEM server (Splunk)
- Windows 10/11 VM: Log source (Windows Event Logs)

## Goals
- Collect Windows security logs centrally
- Analyze authentication and system events in a SIEM
- Create detections/alerts for suspicious activity
- Document findings with an incident report

## Progress
- [x] Ubuntu Server VM created and reachable over SSH
- [ ] Windows log source VM
- [ ] Splunk installed and configured
- [ ] Forwarding Windows logs to Splunk
- [ ] Alerts + incident report
