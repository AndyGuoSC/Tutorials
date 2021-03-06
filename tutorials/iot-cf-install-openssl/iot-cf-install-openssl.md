---
author_name: Supriya Cherukunnathu
author_profile: https://github.com/SupriyaCherukunnathu
title: Install OpenSSL
description: Install OpenSSL to send data to the SAP Cloud Platform Internet of Things Service Cloud using MQTT and REST.
auto_validation: true
primary_tag: products>sap-cloud-platform-internet-of-things
tags: [ tutorial>beginner, products>sap-cloud-platform-internet-of-things, topic>internet-of-things, topic>cloud ]
---


## Prerequisites
 - **Proficiency:** Beginner


## Details
### You will learn
- How to install OpenSSL on Windows or macOS

### Time to Complete
10 min

## Next Steps
- **Tutorials:** [Send Data with MQTT](iot-cf-send-data-mqtt)

---

[ACCORDION-BEGIN [Step 1: ](Install OpenSSL)]

1.  For Windows download [OpenSSL](https://sourceforge.net/projects/openssl/files/latest/download).

2.  Extract the downloaded ZIP archive.

3.  For ease of use we recommend that you add the directories from the OpenSSL binaries to your PATH environment variable. For example, you could enter the following in your terminal (only valid for one session):

    `set PATH=%PATH%;c:\<PATH_TO_OPENSSL.EXE>`

    `set PATH=%PATH%;c:\OpenSSL-Win32\bin\`

    >On macOS OpenSSL is usually installed by default (`/user/bin/openssl`).


[VALIDATE_1]

[ACCORDION-END]
