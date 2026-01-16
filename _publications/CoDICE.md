---
title: "CoDICE: Roll the DICE for Firmware Attestation"
collection: publications
category: manuscripts
permalink: /publication/CoDICE
excerpt: 'This paper proposes CoDICE, a platform-agnostic framework that standardizes vendor-specific firmware manifests into a layered DICE architecture to ensure secure, verifiable firmware integrity in resource-constrained environments.'
date: 2025-11-27
venue: '7th IEEE International Conference on Trust, Privacy and Security in Intelligent Systems and Applications (TPS-ISA)'
slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
bibtexurl: '/files/codice.bib'
citation: 'R. Podder, J. Simental, E. Azizli, B. Mantha, and I. Ray, "CoDICE: Roll the DICE for Firmware Attestation," in <i>Proc. 2025 7th IEEE Int. Conf. Trust, Privacy and Security in Intelligent Systems and Applications (TPS-ISA)</i>, 2025, pp. 1-10.'
---

The firmware manifest is a critical file used during firmware updates that contains essential instructions and data about the update. This information allows devices to validate, download, and install the firmware update securely and is a critical component for firmware attestation. A compromised firmware manifest can lead to system-wide vulnerabilities and critical operational failure. Although firmware attestation using trusted hardware such as trusted platform modules (TPM) or trusted execution environments is gaining popularity, existing approaches do not provide support for protecting the firmware manifest. However, these approaches are often impractical in resource-constrained environments. Moreover, the lack of standardized firmware manifest formats across vendors exacerbates interop-erability challenges and increases attack surfaces by exposing sensitive information about vendors' firmware. In this paper, we propose CoDICE, a comprehensive attestation framework that integrates Trusted Computing Group's Concise Reference Integrity Manifest (CoRIM) format with the layered Device Identifier Composition Engine (DICE) architecture. CoDICE is platform 1 agnostic. It defines a uniform way to transform unstructured vendor-specific manifests into IETF's Concise Data Definition Language (CDDL)-validated CoRIM structures enabling layered, runtime attestations. CoDICE ensures verifiable firmware integrity, runtime security, confidentiality, and enhanced cross-vendor interoperability. Our proof-of-concept implementation demonstrates the security and practicality of the approach, paving the way for structured, formally analyzable firmware update mechanisms in constrained and heterogeneous environments.