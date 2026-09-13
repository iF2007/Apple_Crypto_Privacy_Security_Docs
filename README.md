# 🍎 Apple Cryptography, Privacy, and Security Documents

A curated public archive of Apple security, privacy, and cryptography reference documents — focused on official technical white papers, platform security guides, independent cryptographic evaluations, and audit reports in PDF format (all English editions).

---

## 📦 At a Glance

- **77 PDF documents** currently tracked across **17 primary topic collections**
- **Strictly English editions** preserved for research, compliance, and systems engineering
- **Fully traced origins**: Every document is mapped to its originating Apple web page and upstream CDN/PDF URL

---

## 📚 Collections & Document Sources

| Collection | PDFs | Scope & Coverage | Upstream Apple Source Portal | Primary Direct Download URL(s) |
| :--- | :---: | :--- | :--- | :--- |
| [`Apple_Platform_Security_Guide`](Apple_Platform_Security_Guide/) | 10 | Platform security architecture editions from **2019–2026**, covering Hardware Root of Trust, Secure Boot, Secure Enclave, Data Protection, and Kernel integrity. | [Apple Platform Security Support Guide](https://support.apple.com/guide/security/welcome/web) | [apple-platform-security-guide.pdf](https://help.apple.com/pdf/security/en_US/apple-platform-security-guide.pdf) |
| [`Personal_Safety_User_Guide`](Personal_Safety_User_Guide/) | 4 | Safety Check, AirTag anti-stalking algorithms, Bluetooth unwanted tracking detection, emergency account resets (2022–2026). | [Personal Safety User Guide Web](https://support.apple.com/guide/personal-safety/welcome/web) | [personal-safety-user-guide.pdf](https://help.apple.com/pdf/personal-safety/en_US/personal-safety-user-guide.pdf) |
| [`Private_Cloud_Compute`](Private_Cloud_Compute/) | 2 | Apple Intelligence cloud security architecture: Stateless computation, cryptographic attestation, non-targetability, and independent SOC 3 audit assurance (Ernst & Young). | [Apple Security Blog: PCC](https://security.apple.com/blog/private-cloud-compute/) & [Security Certifications](https://support.apple.com/guide/security-certifications/welcome/web) | [2026-Apple-PCC-SOC-3-Report.pdf](https://help.apple.com/pdf/certifications/en_US/2026-Apple-PCC-SOC-3-Report-05-01-25-to-04-30-26.pdf)<br>[2025-Apple-PCC-SOC-3-Report.pdf](https://help.apple.com/pdf/certifications/en_US/2025-Apple-PCC-SOC-3-Report-11-01-24-to-10-31-25.pdf) |
| [`iMessage_PQ3`](iMessage_PQ3/) | 2 | Post-Quantum Cryptography for iMessage: Kyber-1024 hybrid key encapsulation, post-compromise security, formal protocol verification (Basin et al., ETH Zurich) and independent analysis (Stebila). | [Apple Security Blog: iMessage PQ3](https://security.apple.com/blog/imessage-pq3/) | [Security_analysis_PQ3_Stebila.pdf](https://security.apple.com/assets/files/Security_analysis_of_the_iMessage_PQ3_protocol_Stebila.pdf)<br>[Formal_Analysis_PQ3_Basin.pdf](https://security.apple.com/assets/files/A_Formal_Analysis_of_the_iMessage_PQ3_Messaging_Protocol_Basin_et_al.pdf) |
| [`Audio_Intelligence_Privacy`](Audio_Intelligence_Privacy/) | 1 | Hardware-level microphone data isolation, Secure Exclave architecture, and audio processing sandboxing. | [Apple Privacy Features](https://www.apple.com/privacy/features/) | [Audio_Intelligence_Privacy_Overview_Sep_2026.pdf](https://www.apple.com/privacy/docs/Audio_Intelligence_Privacy_Overview_Sep_2026.pdf) |
| [`Vision_Pro_Privacy`](Vision_Pro_Privacy/) | 1 | Spatial computing privacy: Optic ID biometric security, sensor sandboxing, eye-tracking input event isolation, and world-sensing protections. | [Apple Privacy](https://www.apple.com/privacy/) | [Apple_Vision_Pro_Privacy_Overview.pdf](https://www.apple.com/privacy/docs/Apple_Vision_Pro_Privacy_Overview.pdf) |
| [`iCloud_Private_Relay`](iCloud_Private_Relay/) | 1 | Dual-hop proxy network architecture, Oblivious HTTP (OHTTP), blind RSA signatures, and encrypted DNS (DoH). | [Apple Privacy Features](https://www.apple.com/privacy/features/) | [iCloud_Private_Relay_Overview_Dec2021.pdf](https://www.apple.com/privacy/docs/iCloud_Private_Relay_Overview_Dec2021.PDF) |
| [`Differential_Privacy`](Differential_Privacy/) | 2 | Local Differential Privacy (LDP) algorithms, Laplace/Gaussian perturbation mechanisms, and large-scale learning count-mean sketch math. | [Apple Privacy Features](https://www.apple.com/privacy/features/) & [Machine Learning Research](https://machinelearning.apple.com/research/learning-with-privacy-at-scale) | [Differential_Privacy_Overview.pdf](https://www.apple.com/privacy/docs/Differential_Privacy_Overview.pdf)<br>[learning-with-privacy-at-scale.pdf](https://docs-assets.developer.apple.com/ml-research/papers/learning-with-privacy-at-scale.pdf) |
| [`Privacy_White_Papers`](Privacy_White_Papers/) | 6 | Feature-level privacy designs: Safari ITP, Location Services, Sign in with Apple, HealthKit data protection, App Privacy Report, and Data Broker analysis. | [Apple Privacy Features](https://www.apple.com/privacy/features/) & [Apple Privacy Controls](https://www.apple.com/privacy/control/) | [Safari_White_Paper_Nov_2019.pdf](https://www.apple.com/safari/docs/Safari_White_Paper_Nov_2019.pdf)<br>[Location_Services_White_Paper.pdf](https://www.apple.com/privacy/docs/Location_Services_White_Paper_Nov_2019.pdf)<br>[Sign_in_with_Apple_White_Paper.pdf](https://www.apple.com/privacy/docs/Sign_in_with_Apple_White_Paper_Nov_2019.pdf)<br>[Health_Privacy_White_Paper.pdf](https://www.apple.com/privacy/docs/Health_Privacy_White_Paper_May_2023.pdf)<br>[Health_Fitness_Apps_Privacy.pdf](https://www.apple.com/privacy/docs/Health_Fitness_Apps_Privacy_September_2025.pdf)<br>[A_Day_in_the_Life_of_Your_Data.pdf](https://www.apple.com/privacy/docs/A_Day_in_the_Life_of_Your_Data.pdf) |
| [`App_Store_and_Ecosystem_Security`](App_Store_and_Ecosystem_Security/) | 5 | Sideloading threat analysis, malware propagation models, EU DMA security compliance, developer notarization, and App Store transparency. | [Apple Privacy Docs](https://www.apple.com/privacy/docs/), [Apple Developer Security](https://developer.apple.com/security/), [Apple Legal Transparency](https://www.apple.com/legal/transparency/) | [A_Threat_Analysis_of_Sideloading.pdf](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps_A_Threat_Analysis_of_Sideloading.pdf)<br>[Building_Trusted_Ecosystem.pdf](https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps.pdf)<br>[Complying_with_DMA.pdf](https://developer.apple.com/security/complying-with-the-dma.pdf)<br>[2024_App_Store_Transparency.pdf](https://www.apple.com/legal/more-resources/docs/2024-App-Store-Transparency-Report.pdf)<br>[Helping_Protect_Kids_Online.pdf](https://developer.apple.com/support/downloads/Helping-Protect-Kids-Online-2025.pdf) |
| [`Security_Certifications`](Security_Certifications/) | 3 | FIPS 140-2/3 and Common Criteria compliance overviews, plus CCN/ANSSI Security Target (ST) and Operational Guidance specifications. | [Security Certifications Guide](https://support.apple.com/guide/security-certifications/welcome/web) & [Apple PSD2 Certifications](https://support.apple.com/en-us/102029) | [SCCC_Overview.pdf](https://help.apple.com/pdf/sccc/en_GB/security-certifications-compliance-center-b.pdf)<br>[CCN202511ST_Security_Target.pdf](https://cdsassets.apple.com/live/3M91W9GR/psd2_2024os/CCN202511ST.pdf)<br>[CCN202510Guidance.pdf](https://cdsassets.apple.com/live/3M91W9GR/psd2_2024os/CCN202510Guidance.pdf) |
| [`FaceID`](FaceID/) | 2 | Early Face ID security guides (Sept 2017 & Nov 2017): TrueDepth sensor pipeline, neural network false-match mitigations, and Secure Enclave authorization. | [Apple Business Resources](https://www.apple.com/business/resources/) | [FaceID_Security_Guide_Nov17.pdf](https://www.apple.com/business/docs/site/Face-ID-Security-Paper.pdf) |
| [`iOS`](iOS/) | 10 | Archived iOS Security Guides spanning 2012 to 2019: Keychain hardware key hierarchies, APFS file-based encryption classes, and sandbox boundaries. | [Apple Business IT Resources](https://www.apple.com/business/resources/) | [iOS_Security_Guide.pdf](https://www.apple.com/business/docs/iOS_Security_Guide.pdf) |
| [`macOS`](macOS/) | 6 | Historical Mac security architectures: Apple T2 Security Chip white paper, macOS Security Overview, and OS X security configuration manuals. | [Apple Business IT Resources](https://www.apple.com/business/resources/) | [macOS_Security_Overview.pdf](https://www.apple.com/ae/business/resources/docs/macOS_Security_Overview.pdf)<br>[Apple_T2_Security_Chip_Overview.pdf](https://www.apple.com/mac/docs/Apple_T2_Security_Chip_Overview.pdf) |
| [`CSAM`](CSAM/) | 7 | Private Set Intersection (PSI) protocols, blind secret sharing, and formal external security reviews (Bellare, Pinkas, Forsyth). | [Apple Child Safety](https://www.apple.com/child-safety/) | [Apple_PSI_System_Security_Protocol.pdf](https://www.apple.com/child-safety/pdf/Apple_PSI_System_Security_Protocol_and_Analysis.pdf)<br>[CSAM_Detection_Technical_Summary.pdf](https://www.apple.com/child-safety/pdf/CSAM_Detection_Technical_Summary.pdf) |
| [`COVID-19_ContactTracing`](COVID-19_ContactTracing/) | 11 | Complete joint Apple/Google Exposure Notification Bluetooth & Cryptography specifications (v1.0, v1.1, v1.2) and ENPA analytics paper. | [Apple COVID-19 Contact Tracing](https://covid19.apple.com/contacttracing/) | [Exposure_Notification_Cryptography_v1.2.pdf](https://covid19.apple.com/contacttracing/specs/Exposure_Notification_Cryptography_Specification_v1.2.pdf)<br>[Bluetooth_Specification_v1.2.pdf](https://covid19.apple.com/contacttracing/specs/Exposure_Notification_Bluetooth_Specification_v1.2.pdf) |
| [`Law_Enforcement_and_Transparency`](Law_Enforcement_and_Transparency/) | 4 | US and international law enforcement legal process guidelines (defining non-decryptable customer data boundaries) and semi-annual transparency reports. | [Government Information Requests](https://www.apple.com/privacy/government-information-requests/) & [Legal Transparency](https://www.apple.com/legal/transparency/) | [legal-process-guidelines-us.pdf](https://www.apple.com/privacy/docs/legal-process-guidelines-us.pdf)<br>[law-enforcement-guidelines-outside-us.pdf](https://www.apple.com/legal/privacy/law-enforcement-guidelines-outside-us.pdf)<br>[requests-2025-h2-en.pdf](https://www.apple.com/legal/transparency/pdf/requests-2025-h2-en.pdf)<br>[requests-2024-H2-en.pdf](https://www.apple.com/legal/transparency/pdf/requests-2024-H2-en.pdf) |

---

## 🗂️ Repository Directory Structure

```text
.
├── Apple_Platform_Security_Guide/         # Comprehensive OS & hardware security architecture guides (2019-2026)
├── App_Store_and_Ecosystem_Security/      # Sideloading threat analysis, DMA compliance, App Store transparency
├── Audio_Intelligence_Privacy/            # Microphone privacy, Secure Exclave isolation white paper
├── COVID-19_ContactTracing/               # Exposure Notification Bluetooth, Cryptography specs (v1.0 - v1.2) & ENPA
├── CSAM/                                  # Private Set Intersection (PSI) crypto protocol & independent proofs
├── Differential_Privacy/                  # Local Differential Privacy algorithms & large-scale learning papers
├── FaceID/                                # Face ID TrueDepth and biometric security architecture guides
├── Law_Enforcement_and_Transparency/      # Government legal process guidelines & transparency reports (2024-2025)
├── Personal_Safety_User_Guide/            # AirTag anti-tracking, Safety Check & account recovery guides (2022-2026)
├── Privacy_White_Papers/                  # Feature white papers (Safari ITP, Location, Health, Sign in with Apple)
├── Private_Cloud_Compute/                 # PCC security architecture & Ernst & Young SOC 3 audit reports
├── Security_Certifications/               # SCCC compliance, Common Criteria Security Target & Guidance
├── Vision_Pro_Privacy/                    # Apple Vision Pro spatial computing privacy & Optic ID overview
├── iCloud_Private_Relay/                  # Dual-hop relay, OHTTP, and blind signature system architecture
├── iMessage_PQ3/                          # Kyber-1024 post-quantum cryptography analysis & formal verification
├── iOS/                                   # Archived iOS Security Guides (2012-2019)
├── macOS/                                 # macOS Security Overview, T2 Security Chip, historical OS X guides
└── tasks/                                 # Archival maintenance and sync tasks
```

---

## 🔍 Detailed Document Mapping & Upstream URLs

### 1. Platform & OS Security
- **Apple Platform Security Guide (2019–2026 Editions)**
  - Source: [Apple Support: Platform Security](https://support.apple.com/guide/security/welcome/web)
  - Current PDF: `https://help.apple.com/pdf/security/en_US/apple-platform-security-guide.pdf`
- **Personal Safety User Guide (2022–2026 Editions)**
  - Source: [Apple Support: Personal Safety](https://support.apple.com/guide/personal-safety/welcome/web)
  - Current PDF: `https://help.apple.com/pdf/personal-safety/en_US/personal-safety-user-guide.pdf`
- **macOS Security Overview & T2 Architecture**
  - Source: [Apple Business IT Resources](https://www.apple.com/business/resources/)
  - Direct PDFs:
    - `https://www.apple.com/ae/business/resources/docs/macOS_Security_Overview.pdf`
    - `https://www.apple.com/mac/docs/Apple_T2_Security_Chip_Overview.pdf`
- **iOS Security Guides (2012–2019 Archives)**
  - Source: [Apple Business IT Resources](https://www.apple.com/business/resources/)
  - Direct PDF: `https://www.apple.com/business/docs/iOS_Security_Guide.pdf`

### 2. Post-Quantum Cryptography (PQ3)
- **Security Analysis of iMessage PQ3 (Douglas Stebila)**
  - Source: [Apple Security Research Blog](https://security.apple.com/blog/imessage-pq3/)
  - Direct PDF: `https://security.apple.com/assets/files/Security_analysis_of_the_iMessage_PQ3_protocol_Stebila.pdf`
- **Formal Analysis of iMessage PQ3 (Basin et al., ETH Zurich)**
  - Source: [Apple Security Research Blog](https://security.apple.com/blog/imessage-pq3/)
  - Direct PDF: `https://security.apple.com/assets/files/A_Formal_Analysis_of_the_iMessage_PQ3_Messaging_Protocol_Basin_et_al.pdf`

### 3. Cloud & AI Security Architecture
- **Private Cloud Compute (PCC) SOC-3 Reports**
  - Source: [Apple Security Research: PCC](https://security.apple.com/blog/private-cloud-compute/) & [Security Certifications](https://support.apple.com/guide/security-certifications/welcome/web)
  - Direct PDFs:
    - `https://help.apple.com/pdf/certifications/en_US/2026-Apple-PCC-SOC-3-Report-05-01-25-to-04-30-26.pdf`
    - `https://help.apple.com/pdf/certifications/en_US/2025-Apple-PCC-SOC-3-Report-11-01-24-to-10-31-25.pdf`
- **iCloud Private Relay Technical Overview**
  - Source: [Apple Privacy Features](https://www.apple.com/privacy/features/)
  - Direct PDF: `https://www.apple.com/privacy/docs/iCloud_Private_Relay_Overview_Dec2021.PDF`

### 4. Privacy System Designs
- **Audio Intelligence & Secure Exclave Overview**
  - Source: [Apple Privacy Features](https://www.apple.com/privacy/features/)
  - Direct PDF: `https://www.apple.com/privacy/docs/Audio_Intelligence_Privacy_Overview_Sep_2026.pdf`
- **Apple Vision Pro Privacy Overview**
  - Source: [Apple Privacy](https://www.apple.com/privacy/)
  - Direct PDF: `https://www.apple.com/privacy/docs/Apple_Vision_Pro_Privacy_Overview.pdf`
- **Differential Privacy Papers**
  - Source: [Apple Privacy Features](https://www.apple.com/privacy/features/) & [Machine Learning Research](https://machinelearning.apple.com/research/learning-with-privacy-at-scale)
  - Direct PDFs:
    - `https://www.apple.com/privacy/docs/Differential_Privacy_Overview.pdf`
    - `https://docs-assets.developer.apple.com/ml-research/papers/learning-with-privacy-at-scale.pdf`
- **Feature White Papers (Safari, Location, Sign in with Apple, Health, Ad Tracking)**
  - Sources: [Apple Privacy Features](https://www.apple.com/privacy/features/) & [Apple Privacy Controls](https://www.apple.com/privacy/control/)
  - Direct PDFs:
    - `https://www.apple.com/safari/docs/Safari_White_Paper_Nov_2019.pdf`
    - `https://www.apple.com/privacy/docs/Location_Services_White_Paper_Nov_2019.pdf`
    - `https://www.apple.com/privacy/docs/Sign_in_with_Apple_White_Paper_Nov_2019.pdf`
    - `https://www.apple.com/privacy/docs/Health_Privacy_White_Paper_May_2023.pdf`
    - `https://www.apple.com/privacy/docs/Health_Fitness_Apps_Privacy_September_2025.pdf`
    - `https://www.apple.com/privacy/docs/A_Day_in_the_Life_of_Your_Data.pdf`

### 5. Ecosystem, Sideloading & Compliance
- **Sideloading Threat Analysis & Trusted Ecosystem**
  - Source: [Apple Privacy Docs](https://www.apple.com/privacy/docs/)
  - Direct PDFs:
    - `https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps_A_Threat_Analysis_of_Sideloading.pdf`
    - `https://www.apple.com/privacy/docs/Building_a_Trusted_Ecosystem_for_Millions_of_Apps.pdf`
- **DMA Compliance Security Overview**
  - Source: [Apple Developer Security](https://developer.apple.com/security/)
  - Direct PDF: `https://developer.apple.com/security/complying-with-the-dma.pdf`
- **App Store Transparency Reports**
  - Source: [Apple Legal Transparency](https://www.apple.com/legal/transparency/)
  - Direct PDF: `https://www.apple.com/legal/more-resources/docs/2024-App-Store-Transparency-Report.pdf`
- **Online Child Protection**
  - Source: [Apple Developer Downloads](https://developer.apple.com/support/downloads/)
  - Direct PDF: `https://developer.apple.com/support/downloads/Helping-Protect-Kids-Online-2025.pdf`

### 6. Security Certifications & Common Criteria
- **Security Certifications and Compliance Center (SCCC)**
  - Source: [Apple Support: Security Certifications](https://support.apple.com/guide/security-certifications/welcome/web)
  - Direct PDF: `https://help.apple.com/pdf/sccc/en_GB/security-certifications-compliance-center-b.pdf`
- **Common Criteria Security Target & Guidance (CCN / ANSSI)**
  - Source: [Apple Security Certifications & PSD2 Compliance](https://support.apple.com/en-us/102029)
  - Direct PDFs:
    - `https://cdsassets.apple.com/live/3M91W9GR/psd2_2024os/CCN202511ST.pdf`
    - `https://cdsassets.apple.com/live/3M91W9GR/psd2_2024os/CCN202510Guidance.pdf`

### 7. Child Safety & PSI Crypto Protocol
- **Private Set Intersection & Threat Model Reviews**
  - Source: [Apple Child Safety](https://www.apple.com/child-safety/)
  - Direct PDFs:
    - `https://www.apple.com/child-safety/pdf/Apple_PSI_System_Security_Protocol_and_Analysis.pdf`
    - `https://www.apple.com/child-safety/pdf/CSAM_Detection_Technical_Summary.pdf`
    - `https://www.apple.com/child-safety/pdf/Expanded_Protections_for_Children_Technology_Summary.pdf`
    - `https://www.apple.com/child-safety/pdf/Security_Threat_Model_Review_of_Apple_Child_Safety_Features.pdf`

### 8. Law Enforcement & Transparency
- **Legal Process Guidelines (US & International)**
  - Source: [Apple Privacy: Government Information Requests](https://www.apple.com/privacy/government-information-requests/)
  - Direct PDFs:
    - `https://www.apple.com/privacy/docs/legal-process-guidelines-us.pdf`
    - `https://www.apple.com/legal/privacy/law-enforcement-guidelines-outside-us.pdf`
- **Semi-Annual Transparency Reports**
  - Source: [Apple Legal Transparency Reports](https://www.apple.com/legal/transparency/report-pdf.html)
  - Direct PDFs:
    - `https://www.apple.com/legal/transparency/pdf/requests-2025-h2-en.pdf`
    - `https://www.apple.com/legal/transparency/pdf/requests-2024-H2-en.pdf`

---

## ⚖️ Copyright & Disclaimer

- Apple, iOS, macOS, iPadOS, watchOS, visionOS, Secure Enclave, Face ID, Touch ID, Apple Pay, iMessage, and Apple Intelligence are trademarks of Apple Inc.
- All documents included herein belong to Apple Inc. or their respective academic/independent authors, and are preserved here strictly for archival, educational, research, and audit purposes.
