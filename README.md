# AI SOC Analyst

An AI-powered Security Operations Center (SOC) analyst workflow built using n8n and Google Gemini.

## Overview

This project analyzes cybersecurity alerts and generates SOC-style incident analysis automatically.

## Features

- Security alert analysis
- MITRE ATT&CK mapping
- Severity assessment
- Investigation recommendations
- AI-powered incident response guidance

## Tech Stack

- Docker Desktop
- WSL2
- n8n
- Google Gemini API

## Workflow

Security Alert
↓
Edit Fields
↓
AI Agent
↓
Google Gemini Chat Model
↓
SOC Analysis Output

## Sample Alert

Input:

Multiple failed login attempts detected from IP 192.168.1.100 against the administrator account.

Output:

- Severity: High
- Attack Type: Brute Force
- MITRE ATT&CK: T1110.001
- Recommended Actions:
  - Enable MFA
  - Review authentication logs
  - Block malicious source IP

## Skills Demonstrated

- AI Automation
- Security Operations (SOC)
- Prompt Engineering
- Docker
- n8n Workflows
- Incident Analysis
- MITRE ATT&CK Framework

## Author

Christopher Adade
Cybersecurity Student
