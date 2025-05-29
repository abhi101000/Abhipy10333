# Basic Vulnerability Scan Report

## 🛠️ Tools Used
- **Nessus Essentials** (Tenable)
- Target: Local machine (IP: 169.254.119.58)

## 📋 Summary
A basic vulnerability scan was performed on the local machine using Nessus Essentials. The scan identified **21 vulnerabilities** in total.

## ⚠️ Key Vulnerabilities Found

### 1. SSL Self-Signed Certificate
- **Severity**: Medium
- **Description**: The system is using a self-signed SSL certificate.
- **Fix**: Replace with a certificate from a trusted Certificate Authority (CA).

### 2. SMB Signing Not Required
- **Severity**: High
- **Description**: SMB signing is not enforced which could lead to man-in-the-middle attacks.
- **Fix**: Enable SMB signing via group policy or registry settings.

### 3. Outdated Software Detected
- **Severity**: High
- **Description**: Some installed software is outdated and may contain known vulnerabilities.
- **Fix**: Update the affected software to the latest version.

## 📸 Screenshots
- Included in this repository:
  - Scan summary
  - List of detected vulnerabilities
  - Detailed view of one vulnerability

## 💡 Experience
This task helped me understand how vulnerability scanners work, how to interpret scan results, and the importance of keeping systems updated and secure.
