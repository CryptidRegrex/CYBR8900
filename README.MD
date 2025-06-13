# Wireless Network Exploitation: Deauthentication Attacks, Password Cracking, and Credential Capture

## Overview

This study investigates key wireless network vulnerabilities, focusing on three common exploitation techniques used by threat actors:

- **Deauthentication Attacks** – Force client disconnections to expose reconnection credentials.
- **Password Cracking** – Use captured WPA/WPA2 handshakes to brute-force or dictionary-attack passwords.
- **Credential Capture / Evil Twin** – Leverage rogue access points (e.g., Evil Twin) to steal login credentials.

As wireless networking remains essential for global communications, understanding these attack methods—and how to defend against them—is vital for cybersecurity awareness.

## Objectives

- Demonstrate Wi-Fi deauthentication attacks using tools like `aireplay-ng` and `mdk3`.
- Capture WPA* handshakes and crack passwords using tools like `aircrack-ng`, `hashcat`, and `hcxpcaptool`.
- Set up rogue APs (e.g., using `hostapd` or `Bettercap`) to simulate credential capture.
- Evaluate countermeasures including WPA3, 802.11w, MAC filtering, and HTTPS/HSTS protections.

## Research Questions

1. How do deauthentication attacks disrupt communication, and what mitigations exist?
2. How vulnerable are common password practices when WPA* handshakes are captured?
3. How do rogue APs deceive users, and how can such attacks be detected or prevented?

## Methodology

All testing occurs in a **controlled lab environment** using authorized equipment only.

### 1. Deauthentication Attacks
- Tools: `aireplay-ng`, `mdk3`
- Test disconnection effects and countermeasures (e.g., 802.11w)

### 2. WPA* Handshake Capture & Cracking
- Tools: `airodump-ng`, `hcxpcaptool`, `hashcat`
- Perform dictionary attacks and evaluate password complexity effectiveness

### 3. Evil Twin & Rogue AP Simulation
- Tools: `hostapd`, `Bettercap`
- Simulate user credential theft via fake APs and test HTTPS/HSTS resilience

### 4. Security Analysis
- Review efficacy of newer standards (WPA3)
- Evaluate detection strategies for rogue activity and attacks

## Ethical Considerations

> **Note:** All experiments are strictly ethical, confined to isolated lab environments using devices owned or authorized by the researcher. No unauthorized access or real-world exploitation is involved.

---

This project serves as both a practical assessment of wireless vulnerabilities and a guide for implementing modern defenses in real-world networks.