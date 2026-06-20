# Mobile Forensics 📱

## About

Mobile Forensics is a branch of digital forensics that focuses on the acquisition, preservation, analysis, and reporting of digital evidence from mobile devices such as smartphones, tablets, SIM cards, and memory cards.

The objective of mobile forensics is to recover and analyze data in a forensically sound manner while maintaining the integrity of evidence.

---

## Digital Footprint

A digital footprint refers to the trail of data generated through a user's activities on digital devices and online platforms.

Examples:

- Browsing history
- Search queries
- Social media activity
- Location data
- Emails and messages
- Download history
- Application usage

---

## What is Digital Forensics?

Digital Forensics is the process of identifying, preserving, collecting, examining, analyzing, and presenting digital evidence.

### Main Branches of Digital Forensics

- Computer Forensics
- Mobile Device Forensics
- Network Forensics
- Cloud Forensics
- Malware Forensics
- Memory (RAM) Forensics
- Database Forensics
- IoT Forensics

---

## Digital Forensics Investigation Process

1. Identification
2. Preservation
3. Collection
4. Examination
5. Analysis
6. Documentation
7. Reporting

---

## What is Mobile Forensics?

Mobile Forensics focuses on extracting and analyzing data from mobile devices to support investigations.

### Common Evidence Sources

- Call logs
- SMS messages
- Contacts
- Emails
- Photos and videos
- Browser history
- GPS location data
- Application data
- Social media artifacts
- Cloud backups

---

## Evidence Seizure Best Practices

When handling a mobile device:

- Document the device condition.
- Photograph the device.
- Record date and time.
- Maintain chain of custody.
- Prevent remote access.
- Isolate the device from networks.
- Use Faraday bags when necessary.

---

## Common Mobile Operating Systems

### Android

- Linux-based operating system.
- Open-source ecosystem.
- Uses EXT4 or F2FS file systems.

### iOS

- Developed by Apple.
- Closed ecosystem.
- Uses APFS file system.

---

## Mobile Data Acquisition Methods

### Logical Acquisition

Obtains accessible files through the operating system.

Examples:

- Contacts
- Messages
- Media files
- Application data

### File System Acquisition

Obtains the complete file system structure.

Provides:

- System files
- Application files
- Deleted artifacts (limited)

### Physical Acquisition

Bit-by-bit copy of device storage.

Provides:

- Deleted data recovery
- Unallocated space analysis
- Deep forensic examination

---

## Android Forensics

### Android File System

Important directories:

- /system
- /data
- /cache
- /sdcard

### USB Debugging

Allows communication between Android devices and forensic workstations.

### Android Debug Bridge (ADB)

Common Commands:

```bash
adb devices
adb shell
adb pull
adb backup
adb logcat
