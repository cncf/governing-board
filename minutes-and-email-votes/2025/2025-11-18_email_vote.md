# RESOLUTIONS OF THE CNCF GOVERNING BOARD

Approved by email vote on November 18, 2025

WHEREAS, several CNCF projects have requested exceptions to the CNCF IP Policy, which are subject to approval by the Governing Board under Section 11(c) of the CNCF Charter.

## **Blanket License Exception for any CNCF project to use filepath-securejoin**

WHEREAS, multiple projects have requested a blanket exception (Issue \#[1154](https://github.com/cncf/foundation/issues/1154)) to enable them to use [filepath-securejoin](https://github.com/cyphar/filepath-securejoin) notwithstanding filepath-securejoin’s change in license from BSD-3-Clause to MPL-2.0 AND BSD-3-Clause.

WHEREAS, the CNCF Legal Committee recommends APPROVAL of this requested exception.

RESOLVED, that the Governing Board hereby APPROVES a blanket exception to allow any CNCF project to use filepath-securejoin under MPL-2.0 AND BSD-3-Clause as either (a) a vendored component, (b) build-time dependency, or (c) install-time dependency, in each case that it is dynamically or statically linked with the CNCF project’s own code.

## **License Exception for use of HangeFire.Core by OpenTelemetry**

WHEREAS, OpenTelemetry has requested an exception (Issue \#[1065](https://github.com/cncf/foundation/issues/1065)) for use of Hangfire.Core.

WHEREAS, the CNCF Legal Committee recommends APPROVAL of an exception to allow OpenTelemetry to use Hangfire.Core subject to the following limitations: Hangfire.Core may be used (a) in unmodified form only, (b) as a build-time or install-time dependency only, (c) and as a dependency of the *optional* OpenTelemetry.Instrumentation.Hangfire package, and not a dependency of other packages. Additionally, OpenTelemetry must provide notices to ensure users are aware that installation of OpenTelemetry.Instrumentation.Hangfire will cause the user’s system to automatically retrieve Hangefire.Core, which is available under LGPL-3.0-or-later or a commercial license.

RESOLVED, the Governing Board hereby APPROVES an exception to allow OpenTelemetry to use Hangfire.Core under LGPL-3.0-or-later subject to the limitations and requirements that have been recommended by the Legal Committee as described in the foregoing recital.

## **License Exception for use of Liquibase by Keycloak**  
   
WHEREAS, the Keycloak project submitted a request for license exceptions (Issue \#[1147](https://github.com/cncf/foundation/issues/1147)) to use [Liquibase](https://github.com/liquibase/liquibase), which is available under the Functional Source License, v.1.1 (FSL).

WHEREAS, because FSL is **not** an open source license, the CNCF Legal Committee recommends REJECTION of the requested exception.

RESOLVED, that the Governing Board hereby REJECTS the requested exception to use [Liquibase](https://github.com/liquibase/liquibase) under FSL.

