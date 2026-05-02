# NHS England Digital (nhs-england-digital)

NHS England (incorporating the former NHS Digital and NHSX) provides national digital, data, and technology services for the NHS in England. The organization operates the Spine, the Personal Demographics Service, the Electronic Prescription Service, the Summary Care Record, e-Referral Service, NHS App, NHS.uk, and an extensive API platform of FHIR and REST APIs used by health and care providers, developers, and researchers across England.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/nhs-england-digital/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - Clinical, Demographics, FHIR, Government, Health, Healthcare, NHS, Open Data, Patient Records, Prescriptions, UK

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-04-28

## APIs

### NHS England API Platform

The NHS England API platform hosts a catalogue of national APIs for health and care, including FHIR and REST APIs covering patient demographics, prescriptions, appointments, records, screening, and clinical terminology. The platform provides developer onboarding, sandbox environments, OAuth 2.0 authentication, and production access through API keys and signed JWT authentication.

**Human URL:** [https://digital.nhs.uk/developer](https://digital.nhs.uk/developer)

#### Tags

 - API Platform, Developer Portal, FHIR, Healthcare

#### Properties

- [Documentation](https://digital.nhs.uk/developer)
- [APIReference](https://digital.nhs.uk/developer/api-catalogue)
- [GettingStarted](https://digital.nhs.uk/developer/guides-and-documentation)

---

### Personal Demographics Service (PDS) FHIR API

The Personal Demographics Service is the national electronic database of NHS patient demographic details such as name, address, date of birth and NHS Number. The PDS FHIR API allows authorised systems to retrieve and update patient demographics for citizens registered with the NHS in England, Wales, and the Isle of Man.

**Human URL:** [https://digital.nhs.uk/developer/api-catalogue/personal-demographics-service-fhir](https://digital.nhs.uk/developer/api-catalogue/personal-demographics-service-fhir)

#### Tags

 - Demographics, FHIR, Patient Records

#### Properties

- [Documentation](https://digital.nhs.uk/developer/api-catalogue/personal-demographics-service-fhir)

---

### Electronic Prescription Service (EPS) FHIR API

The Electronic Prescription Service enables prescribers to send prescriptions electronically to a dispenser of the patient's choice. The EPS FHIR API allows clinical systems to create, retrieve, release, claim, and cancel electronic prescriptions for patients in England.

**Human URL:** [https://digital.nhs.uk/developer/api-catalogue/electronic-prescription-service-fhir](https://digital.nhs.uk/developer/api-catalogue/electronic-prescription-service-fhir)

#### Tags

 - FHIR, Pharmacy, Prescriptions

#### Properties

- [Documentation](https://digital.nhs.uk/developer/api-catalogue/electronic-prescription-service-fhir)

---

### e-Referral Service (e-RS) FHIR API

The NHS e-Referral Service combines electronic booking with a choice of place, date and time for first hospital or clinic appointments. The e-RS FHIR API enables clinical systems to integrate referral and booking workflows directly into the patient pathway.

**Human URL:** [https://digital.nhs.uk/developer/api-catalogue/e-referral-service-fhir](https://digital.nhs.uk/developer/api-catalogue/e-referral-service-fhir)

#### Tags

 - Appointments, FHIR, Referrals

#### Properties

- [Documentation](https://digital.nhs.uk/developer/api-catalogue/e-referral-service-fhir)

---

### Summary Care Record (SCR) API

The Summary Care Record holds essential patient information from the GP record. The SCR API enables authorised health and care professionals to retrieve a patient's medication, allergies and adverse reactions, and any additional information shared by the patient's GP.

**Human URL:** [https://digital.nhs.uk/developer/api-catalogue/summary-care-record](https://digital.nhs.uk/developer/api-catalogue/summary-care-record)

#### Tags

 - Clinical, Patient Records

#### Properties

- [Documentation](https://digital.nhs.uk/developer/api-catalogue/summary-care-record)

---

### GP Connect API

GP Connect APIs allow authorised clinical systems to view and book GP services. The APIs provide structured access to GP records including medications, allergies, immunisations, observations, problems, and appointment availability across federated GP systems.

**Human URL:** [https://digital.nhs.uk/developer/api-catalogue/gp-connect-access-record-structured](https://digital.nhs.uk/developer/api-catalogue/gp-connect-access-record-structured)

#### Tags

 - Appointments, Clinical, FHIR, GP, Patient Records

#### Properties

- [Documentation](https://digital.nhs.uk/developer/api-catalogue/gp-connect-access-record-structured)

---

### NHS Login API

NHS login provides a single, secure way for citizens to access NHS digital services. The NHS login API enables relying parties to authenticate users, verify identity to a known level of assurance, and obtain consented identity claims using OpenID Connect.

**Human URL:** [https://digital.nhs.uk/services/nhs-login](https://digital.nhs.uk/services/nhs-login)

#### Tags

 - Authentication, Identity, OpenID Connect

#### Properties

- [Documentation](https://digital.nhs.uk/services/nhs-login)

## Common Properties

- [Website](https://digital.nhs.uk)
- [Documentation](https://digital.nhs.uk/developer)
- [APIReference](https://digital.nhs.uk/developer/api-catalogue)
- [GettingStarted](https://digital.nhs.uk/developer/guides-and-documentation)
- [Blog](https://digital.nhs.uk/blog)
- [News](https://digital.nhs.uk/news)
- [Support](https://digital.nhs.uk/about-nhs-digital/contact-us)
- [StatusPage](https://status.digital.nhs.uk)
- [GitHubOrganization](https://github.com/NHSDigital)
- [TermsOfService](https://digital.nhs.uk/about-nhs-digital/terms-and-conditions)
- [Privacy](https://digital.nhs.uk/about-nhs-digital/privacy-and-cookies)
- [X](https://x.com/NHSEngland)
- [YouTube](https://www.youtube.com/c/NHSDigital)

## Features

| Name | Description |
|---|---|
| National FHIR APIs | HL7 FHIR-based APIs for patient records, prescriptions, referrals, and clinical data exchange. |
| Sandbox Environments | Free, anonymous sandbox endpoints for testing API integrations before production access. |
| OAuth 2.0 and Signed JWT | Production authentication via OAuth 2.0 user-restricted access and application-restricted signed JWT. |
| Developer Onboarding | Structured onboarding pathway from sandbox to integration test to production via Apigee developer portal. |
| NHS Login Identity Provider | Citizen-facing OpenID Connect identity provider for NHS digital services. |
| Spine Connectivity | National secure messaging and data backbone underlying the major NHS APIs. |

## Use Cases

| Name | Description |
|---|---|
| Clinical System Integration | Integrate EHR and clinical systems with national patient demographics, prescriptions, and records. |
| Citizen-Facing Apps | Build apps that authenticate citizens with NHS login and surface their NHS data. |
| Pharmacy Workflow | Receive, release, dispense, and claim electronic prescriptions through the EPS API. |
| Referral Management | Integrate appointment booking and referral workflows via the e-Referral Service. |
| GP Record Access | View structured GP record data across federated systems via GP Connect. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
