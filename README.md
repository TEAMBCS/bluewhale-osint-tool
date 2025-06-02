
# BLUE WHALE OSINT TOOL

**Version:** 1.0  
**Author:** Parvez Hasan  
**Team:** Bangladesh Cyber Squad  

---

## Overview

BLUE WHALE OSINT TOOL (MAX) is a comprehensive, all-in-one OSINT (Open Source Intelligence) toolkit designed for cybersecurity researchers, ethical hackers, and investigators. This powerful Python-based CLI tool provides a wide range of information-gathering modules — all without relying on expensive external APIs (except a free IP lookup).

---

## Features

- **IP Lookup:** Retrieve geolocation and ISP info for any IP address (using free public API).
- **Phone Number Info:** Validate phone numbers and get region & carrier data.
- **Email Validation:** Syntax check with MX DNS record verification (no external APIs).
- **Username Search:** Check username availability on popular platforms like GitHub, Twitter, Reddit, Instagram.
- **Domain WHOIS Lookup:** Query domain registration info and dates.
- **Image EXIF Metadata:** Extract metadata from images to identify location, camera model, and timestamps.
- **Subdomain Scanner:** Enumerate common subdomains with DNS resolution and multithreading.
- **TCP Port Scanner:** Scan common ports for open/closed status on a target IP.
- **Text Extraction:** Extract emails, IP addresses, and URLs from text files for further analysis.
- **System Info:** Display local system and environment information.
- **Animated Inputs & Rich Console UI:** Beautiful CLI experience powered by `rich` and `questionary` libraries.

---

## Requirements

- Python 3.7 or higher
- pip packages:
  - requests
  - whois
  - phonenumbers
  - exifread
  - rich
  - questionary
  - dnspython

---

## Installation


   ```bash
   git clone https://github.com/parvezhasan/blue-whale-osint-max.git
   cd bluewhale_osint_tool
   ```

2. Install dependencies:

   ```bash
   pip install requests whois phonenumbers exifread rich questionary dnspython
   ```

---

## Usage

Run the tool with Python:

```bash
python main.py
```

You will see a beautiful banner and a menu-driven interface where you can select modules by arrow keys.

---

## Modules Explained

| Option | Module                 | Description                                                      |
|--------|------------------------|------------------------------------------------------------------|
| 1      | IP Lookup              | Get geolocation, ISP, timezone and more for an IP address       |
| 2      | Phone Number Info      | Check phone carrier, region, and validity                        |
| 3      | Email Validation       | Syntax + MX DNS record check for email addresses                 |
| 4      | Username Search        | Check popular sites for username availability                    |
| 5      | Domain WHOIS Lookup    | Retrieve domain registration information                         |
| 6      | Image Metadata (EXIF)  | Extract metadata from images (location, camera, dates)           |
| 7      | Subdomain Scanner      | Scan for common subdomains on a target domain                    |
| 8      | TCP Port Scanner       | Scan common TCP ports on an IP address                            |
| 9      | Extract Emails, IPs, URLs from Text | Extracts info from text files                        |
| 10     | System Info            | Displays local system OS info                                    |
| 11     | Exit                   | Exit the tool                                                    |

---

## Contributing

Feel free to fork the repo, add new features, or report bugs!  
Open pull requests and issues are welcome.

---



-

---

*Stay ethical. Use responsibly.*
