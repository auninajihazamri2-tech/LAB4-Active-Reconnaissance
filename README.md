# LAB 4: Active Reconnaissance & Footprinting

* **Name:** NUR AUNI NAJIHA BINTI MOHD ZAMRI
* **Class:** L01-B04
* **Lecturer:** Ts. Adani Kamal
* **Target Machine:** DVWA (Damn Vulnerable Web Application) – `10.0.2.4`
* **Submission Due Date:** 20/11/2026

---

## Overview & Objectives
This repository contains the technical report and evidence for **Lab 4: Active Reconnaissance & Footprinting**. The exercise was performed within an isolated VirtualBox lab environment to map network exposure and running services on an authorized vulnerable target (DVWA) from a Kali Linux attacker host.

---

## Summary of Findings

* **Network Environment:** VirtualBox NAT Network (`10.0.2.0/24`)
* **Attacker Host:** Kali Linux (`10.0.2.15`)
* **Target Victim:** DVWA (`10.0.2.4`)
* **Discovered Open Ports & Services:**
  * **21/tcp** – FTP (`ProFTPD 1.3.2c`)
  * **22/tcp** – SSH (`OpenSSH 5.3p1`)
  * **80/tcp** – HTTP (`Apache httpd 2.2.14` with PHP 5.3.1)
  * **443/tcp** – HTTPS (`Apache httpd 2.2.14` with PHP 5.3.1)
  * **3306/tcp** – MySQL Database

---

## File Submissions
* **Full Report (PDF):** `VA Lab 4 submission.pdf` (available in this repository).
