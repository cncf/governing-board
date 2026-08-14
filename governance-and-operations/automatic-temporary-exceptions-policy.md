# Policy for Automatic Temporary Exceptions for Security Vulnerability Fixes

**Approved on June 23, 2026**

The Cloud Native Computing Foundation (CNCF) recognizes that maintaining the security of the ecosystem often requires immediate action. This policy provides maintainers with a streamlined path to address exploitable security vulnerabilities by allowing the temporary use of dependencies that are not on the [CNCF License Allowlist](https://www.google.com/search?q=https://www.cncf.io/allowlist) while approval of a permanent exception to the [CNCF IP Policy](https://github.com/cncf/foundation/blob/main/charter.md#11-ip-policy) is pending.

Capitalized terms and categories used in this policy are defined in the [CNCF Dependency Licensing Glossary](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?usp=sharing).

## Scope of Temporary Approval

This policy grants a **90-day** "Automatic Temporary Approval", commencing upon a CNCF project’s opening a [License Exception Request](https://github.com/cncf/foundation) for the use of non-allowlisted dependencies, provided the usage adheres to the profiles defined below. These profiles are based on the license type and the technical nature of the interaction (e.g., how the code is distributed and how data is exchanged).

## Core Eligibility Requirements

Before applying a temporary exception, maintainers must verify the following:

* **Security Urgency:** The dependency is required specifically to fix an exploitable security vulnerability.  
* **No Feasible Alternatives:** There are no alternatives available that are already permitted under the [CNCF IP Policy](https://github.com/cncf/foundation/blob/main/charter.md#11-ip-policy) or [Allowlist Policy](https://github.com/cncf/foundation/blob/main/policies-guidance/allowed-third-party-license-policy.md) that could be implemented within a reasonable time frame.  
* **Eligible Licenses:** The dependency is distributed under an Eligible License (see below).  
* **License Conditions Satisfied:** The project’s use of the dependency will conform to all applicable requirements under “License-Specific Conditions” below.  
* **Mandatory Exception Filing:** The project must also file a formal [License Exception Request](https://github.com/cncf/foundation).  
* **Risk of Denial:** If the formal request is subsequently denied by the CNCF Governing Board, the project must remove the component and implement an alternative solution as soon as is practicable after receiving notification of the denial.

If a project wants to make use of the temporary exception but is not sure if it applies, please ask in a comment on the license exception request issue you open in GitHub, and CNCF staff will confirm. 

## Eligible Licenses

Only dependencies distributed under the following licenses are eligible for temporary exceptions under this policy:

* Any OSI-approved permissive license  
* MPL-2.0  
* EPL-2.0  
* LGPL-2.1, LGPL 3.0

### Ineligible Licenses

Dependencies licensed under AGPL, GPL-1.0, GPL-2.0, or GPL-2.0, source-available licenses (e.g., BUSL, SSPL), or any license not explicitly listed above **are not eligible** for temporary automatic approval, regardless of the security urgency. If an ineligible license applies, or if a Project’s proposed use does not satisfy the applicable [License-Specific Conditions](#license-specific-conditions), the Project must submit a formal license exception request and wait for a written decision from the CNCF Governing Board **before** using the dependency.

## License-Specific Conditions

If the [Core Eligibility Requirements](#core-eligibility-requirements) above are met, projects must also meet the license-specific conditions listed below to qualify for temporary approval under this policy:

### 1\. OSI-Approved Permissive Licenses (Apache-2.0, MIT, BSD, etc.) 

Automatic temporary approval is granted for dependencies that meet the [Core Eligibility Requirements](#core-eligibility-requirements) and are distributed under an OSI-approved permissive license. No additional scope conditions apply to this temporary approval.

### 2\. MPL-2.0 & EPL-2.0

Automatic temporary approval is granted for dependencies that meet the [Core Eligibility Requirements](#core-eligibility-requirements) and are distributed under MPL-2.0 or EPL-2.0 only if the dependency code is  (a) used in unmodified form and (b) used as a [Separated Component](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?tab=t.0#heading=h.ptkw8b741pgl). Use as [Intermingled Code](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?tab=t.0#heading=h.ebj7sxo4bakz) is prohibited.

### 3\. LGPL (2.1 & 3.0)

Automatic temporary approval is granted for dependencies that meet the [Core Eligibility Requirements](#core-eligibility-requirements) and are distributed under LGPL-2.1 or LGPL-3.0 only if ***all*** conditions of ***either*** of the following 2 profiles is satisfied:

#### Internal Project Tooling Profile

Automatic temporary approval is granted for dependencies that meet the [Core Eligibility Requirements](#core-eligibility-requirements) and are distributed under LGPL-2.1 or LGPL-3.0 only if all conditions of the “[Not Distributed \+ Not Needed by End User (Internal Project Tooling)](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?tab=t.0#heading=h.dr2jtwsaghbf)” definition are true, including the condition that **the dependency must not inject any code or libraries into the final artifact**. 

#### Dynamic Linking Profile

Automatic temporary approval is granted for dependencies that meet the [Core Eligibility Requirements](#core-eligibility-requirements) and are distributed under LGPL-2.1 or LGPL-3.0 only if all of the following requirements are met:

* **Unmodified:** The dependency code must be used in unmodified form (any modifications proposed by the CNCF project must be submitted upstream).  
* **Structural Separation:** The dependency must be used as a [Separated Component](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?tab=t.0#heading=h.ptkw8b741pgl)**.**  
* **Data Exchange:** The communication between the dependency and the CNCF project code must be [Arms-Length Only](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?tab=t.0#heading=h.i9oezys6pski) data exchange (e.g., serialized JSON/Protobuf; neither component may access the other's internal memory structures or shared pointers).  
* **Communication Mechanism:** The dependency may be accessed only through the following permitted mechanisms: [Dynamic Linking](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?tab=t.0#heading=h.e5vagl8vsvzf), [Separate Process](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?tab=t.0#heading=h.vjh0u2jgtpzr), or [Network Interaction](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?tab=t.0#heading=h.790sjgg6tp39). *Under this profile, [Static Linking](https://docs.google.com/document/d/1KZRmaP9u2GHWeetsMjKK129f3VMF8vZG99VczicAWog/edit?tab=t.0#heading=h.ep95jlvvuw5) is **strictly prohibited**.*
