# IoT-Security-Lab-05
IoT Security – Lab Assignment 05
Special Topics in Information Security – Seiyun University
This repository contains the full implementation and documentation for Lab Assignment No. 05, focusing on IoT Security and Cyber‑Physical Systems (CPS). The project demonstrates secure IoT data communication, embedded system lifecycle protection, and basic secure boot verification.
 Contents
IoT_Security_Mnoor_<EnrollNo>.ipynb – Google Colab notebook
Part I: IoT sensor data encryption using AES
Part II: IoT device lifecycle simulation
Part III (Optional): Secure boot verification
PDF report with:
Handwritten answers
Code outputs
Screenshots
Title page
 Part I – IoT Data Encryption Simulation
This section simulates an IoT sensor generating temperature and humidity readings, encrypting them using AES lightweight cryptography, and securely transmitting them to a receiver.

Features
Random sensor data generation
AES encryption & decryption
Secure transmission simulation
Comparison of plaintext vs encrypted data
Part II – IoT Device Security Lifecycle
A Python script simulates the five stages of the embedded system security lifecycle:
Threat Modeling
Secure Boot Initialization
Secure Key Injection
OTA Firmware Update Verification
Secure Decommissioning
Each stage is logged with timestamps to mimic real device behavior.
 Part III – Secure Boot Verification (Optional)
This optional task demonstrates a simplified secure boot mechanism:
A stored firmware hash is used as a reference
The system computes the runtime hash
If both match → boot allowed
If not → boot rejected
This helps understand firmware integrity checking.



✅ 👩‍🎓 Author
Student: Munira Azzan Jaffr blfas 
Course: Special Topics in Information Security 
Instructor: Prof. Ahmed Abuamer


