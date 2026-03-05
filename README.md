# Adaptive Binary OTP Authentication System 🔐

## Description

This project implements a secure login system using an **Adaptive Binary One-Time Password (OTP)** mechanism developed in Python 🐍. The system dynamically generates OTPs based on the detected login risk level, improving authentication security while maintaining user convenience.

Unlike traditional authentication systems that generate fixed-length OTPs, this system adapts the OTP length based on login conditions. The system also enforces restrictions on username and password length to improve input validation and prevent misuse.

The OTP is generated using Python’s **secrets module**, which provides cryptographically secure random numbers suitable for authentication and security-sensitive applications 🔒.

## Features

* Adaptive OTP generation based on login behavior ⚙️
* Binary OTP creation using secure randomness 🔑
* Username length restriction (maximum 40 characters)
* Password length restriction (maximum 10 characters)
* OTP expiration mechanism for additional security ⏱️
* Simple terminal-based authentication system 💻

## Technologies Used

* Python 🐍
* Secrets module for secure OTP generation 🔐
* Time module for OTP expiration handling ⏳

## Purpose

The main objective of this project is to demonstrate a **secure and adaptive authentication mechanism** that adjusts OTP complexity according to risk conditions while maintaining a simple and lightweight implementation.

This project can be used as a **learning model for authentication systems, cybersecurity concepts, and adaptive security mechanisms** 🛡️.

## Future Improvements

* Integration with email or SMS OTP delivery 📧
* Web-based login interface 🌐
* User database integration 🗄️
* Password encryption using hashing algorithms 🔑
* Login attempt tracking and account lock mechanisms 🚫
