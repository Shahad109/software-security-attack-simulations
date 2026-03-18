# software-security-attack-simulations

This repository presents three practical software security case studies performed in a controlled lab environment to demonstrate how software vulnerabilities can be exploited and analyzed for academic learning.

## Included Case Studies

### 1. Buffer Overflow Attack

A stack-based buffer overflow simulation where stack protections were disabled, memory addresses were analyzed using GDB, and crafted payloads were used to overwrite the return address.

### 2. Return-to-libc Attack

A controlled exploit showing how non-executable stack protection can be bypassed by redirecting execution flow to existing libc functions such as system().

### 3. Race Condition Vulnerability

A symbolic link race condition attack demonstrating how improper file access validation in Set-UID programs can lead to privilege escalation.

## Objectives

* Understand common software vulnerabilities
* Analyze exploit mechanics
* Study memory behavior during attacks
* Practice secure coding awareness

## Author

Shahad Alharbi
a student at the University of Jeddah, College of Science and Computer Engineering

## Academic Purpose

These labs were conducted strictly for educational purposes in a secure lab environment.
