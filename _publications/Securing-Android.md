---
title: "Securing Android Inter-Process Communication (IPC) Using NGAC"
collection: publications
category: conferences
permalink: /publication/Securing-Android
excerpt: 'This paper applies the Next-Generation Access Control (NGAC) model to strengthen the security of Android’s inter-process communication (IPC) mechanisms against unauthorized interactions between apps and services.'
date: 2025-08-26
venue: '22nd Annual International Conference on Privacy, Security, and Trust (PST)'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1109/PST65910.2025.11268876'
bibtexurl: '/files/secureandroid.bib'
citation: 'J. Simental, E. Azizli, M. Abdelgawad, and I. Ray, "Securing Android Inter-Process Communication (IPC) Using NGAC," in <i>Proc. 2025 22nd Annual Int. Conf. Privacy, Security, and Trust (PST)</i>, 2025, pp. 1-6, doi: 10.1109/PST65910.2025.11268876.'
---
Android apps communicate with each other through a mechanism called Inter-Process Communication (IPC) that allows them to exchange messages known as intents. IPC uses Mandatory Access Control (MAC), referred to as an Intent Firewall, to protect and manage intents between apps. However, IPC poses a significant risk, as malicious apps can exploit IPC to attack other apps. This vulnerability arises from the security architecture and implementation inherent to the Android operating system. To mitigate this vulnerability, we have implemented NIST Next Generation Access Control (NGAC) on top of the Intent Firewall to strengthen the enforcement of IPC access control. The NGAC module enforces stricter IPC security policies by using app attributes, including the installation source, app signature, and app type. We tested the NGAC module on Android 13 across various apps, and we evaluated its performance to ensure that the time required to verify intents between apps remains efficient. The results show that the NGAC module is effective and efficient in securing Android IPC.
