---
title: "Sectigo eIDAS TSA Disclosure Statement"
version: "1.0.6"
author: "Sectigo (Europe) S.L."
date: "TBD - Set during publishing"
address: "Rambla Catalunya 33, 3º"
address_line_two: "08007 Barcelona, Spain"
copyright_header: "Copyright Notice"
copyright_notice: "Copyright Sectigo 2026. All rights reserved."
copyright_body: "No part of this publication may be reproduced, stored in or introduced into a retrieval system, or transmitted, in any form or by any means (electronic, mechanical, photocopying, recording or otherwise) without prior written permission of Sectigo Limited. Requests for any other permission to reproduce this Sectigo document (as well as requests for copies from Sectigo) must be addressed to:"
copyright_legal: "Attention Legal Practices"

---

## Introduction

This document is the Sectigo's eIDAS TSA Disclosure Statement (TSADS).
This declaration is not a substitute for the TSA Policy & Practice Statement (TSPPS) of Sectigo. The TSPPS is available at https://sectigo.com/legal and at https://sectigo.com/eIDASCPS

The eIDAS TSA Disclosure Statement summarizes the terms and conditions of the Time stamping services offered by Sectigo in a more readable and understandable format for the benefit of our subscribers and relying parties.

## Contact info

The Sectigo services and the repository are accessible through several means of communication:

- On the web: [http://www.sectigo.com/legal](http://www.sectigo.com/legal)
- By email: legalnotices@sectigo.com
- By mail:
  - Sectigo
  - Exmouth House, 3 /11 Pine St, London, EC1R 0JH, United Kingdom
  - Tel: +44 (0) 161 874 7070

## Time stamps token types and usage

Sectigo aims to deliver time-stamping services in accordance with the Regulation (EU) No 910/2014 (“eIDAS Regulation”), amended by the regulation 1183/2024 of April 11th, 2024 (aka eIDAS 2). However, Sectigo timestamps may be equally applied to any application requiring proof that a datum existed before a particular time.

Supported signing algorithms are sha256WithRSAEncryption. Acceptable Time Stamp Request Hashes include SHA-256, SHA-384 and SHA-512. Sectigo may charge fees for the services provided by the Sectigo qualified TSA.

The identifier of the certificate policy in the TSA certificate(s) specified in the present document is: 1.3.6.1.4.1.6449.1.2.1.

By including this object identifier itu-t(0) identified-organization(4) etsi(0) time stamp-policy(2023) policy-identifiers(1) best-practices-ts-policy (1) in a time-stamp token, Sectigo claims conformance to this time-stamp policy.

Sectigo issues qualified time stamps in compliance with the latest version of the ETSI EN 319 421.

The Sectigo's Time Stamping service is available 24x7.

## Limits of use

Sectigo does not set reliance limits for timestamp services, however reliance limits may be set by applicable law or by agreement. The Sectigo TSA assures time with ±1 second of a trusted UTC time source.

If a trusted UTC time source cannot be acquired the time stamp will not be issued. Sectigo maintains secure records concerning the operation of the qualified TSA according to the legal requirements for the purpose of providing evidence in legal proceedings.
Sectigo's qualified timestamps are issued according to the EU Regulation 910/2014 (aka eIDAS) amended by Regulation 1183 /20 24 of the European Parliament and of the Council of April 11th, 2024 (aka eIDAS 2).

## Obligations of subscribers

Subscribers must verify that the time-stamp token has been correctly signed and check the Sectigo validation services (i.e., CRL) to confirm that the private key used to sign the time-stamp token has not been compromised.

Subscribers must use secure cryptographic functions for time-stamping requests or software toolkit to create timestamps. Subscribers must inform its end users (including any relevant Relying Parties) about the Sectigo policies and practices documentation.

## Obligations of relying parties

Before placing any reliance on a Timestamp, relying parties must verify that the TST has been correctly signed and that the associated TSU certificate has not been revoked.

Sectigo CA Certificates, TSU Certificates and the related CRLs are published at https://www.sectigo.com/legal

If this verification takes place after the end of the validity period of the certificate, the Relying Party should follow the guidance denoted in Annex D of ETSI EN 319 421. The Relying Party should take into account any limitations on usage of the timestamp indicated by the TSPPS, the Subscriber Agreement and any other documentation provided by Sectigo.

## Retention of event logs

All TSA event logs are retained in accordance with the retention period for audit logs in the CP/CPS.

## Limited warranty and limitations of liabilities

Except for the guarantees expressly defined in the subscriber agreement applicable to the subscriber, all other express or implicit guarantees are not applicable, especially any guarantee of suitability for a specific use or of compliance with special requirements of the subscribers. Therefore, the provision of the time stamping service does not discharge the subscriber from analyzing and verifying the legal or regulatory requirements applicable to it.

Sectigo cannot be held liable:

- in case of an unauthorized or non-compliant use (with the legal and contractual requirements) of the time stamps, the revocation information as well as the equipment or software made available for the provision of the service.
- for any damages resulting from errors or inaccuracies, when these errors or inaccuracies result directly from the erroneous nature of the information communicated by the subscriber.
- under any circumstance in case of any use that is not compliant with the uses defined in the TSPPS or in any agreement.
- under any circumstance in case of breach of obligations by the Subscriber and/or the Relying Parties.
- for indirect damages resulting from the use of a time stamp.

Additional limitations may be defined by the subscriber agreement signed between the subscriber and Sectigo.

## Applicable documentation

The applicable documents are published at https://sectigo.com/legal and https://sectigo.com/eIDASCPS

## Privacy policy

The privacy policy is published at https://sectigo.com/privacy-policy

## Refund policy

Sectigo does not refund fees for time-stamp services.

## Applicable law, complaints and dispute resolution

The Sectigo qualified TSA aims to deliver time-stamping services used in support of qualified electronic signatures (i.e., in line with the eIDAS Regulation), as well as under other applicable laws and regulations.

Complaints from customers or other parties related to Sectigo TSA services will be handled without any unreasonable delay and the complaining party will receive an answer to the complaint within 14 calendar days from the reception of the complaint.
In case of a dispute arising, the parties shall try to settle the dispute through negotiations and conciliation.

## Sectigo repository, trust marks and audit

Sectigo and their qualified services are regularly audited. In the case of the TSA this is in line with the requirements stated in ETSI EN 319 4 21 by an accredited body in accordance with standard ETSI EN 319 403 when related to trust services according to Regulation 910/2014 of the European Parliament and of the Council of 23 July 2014 (amended by 1183/2024 as of April 11th, 2024).
