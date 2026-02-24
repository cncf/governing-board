# RESOLUTIONS OF THE CNCF GOVERNING BOARD

Approved on August 31, 2023

WHEREAS, several CNCF projects have requested exceptions to the CNCF IP Policy, which  
are subject to approval by the Governing Board under Section 11(g) of the CNCF Charter.

## k6-operator usage on Dapr project for e2e stress tests

WHEREAS, the Dapr project requested a licensing exception (See Issue [\#461](https://github.com/cncf/foundation/issues/461)) to use  
the [k6 load testing tool](https://github.com/grafana/k6) via the [k6-operator component](https://github.com/grafana/k6-operator), both of which are made available  
by Grafana Labs. k6 is published by Grafana under the GNU Affero General Public  
License, version 3.0 (AGPL-3.0), while k6-operator is published by Grafana under  
Apache-2.0.

WHEREAS, that the Governing Board approved the requested exception to enable Dapr  
to use k6 load testing tool via the k6-operator component solely for testing purposes as  
described in the exception request, conditioned on Grafana Labs providing a specific  
written statement requested by the legal committee.

WHEREAS, Grafana Labs has agreed to provide a slightly modified version of the  
statement originally requested. The modified statement is set forth below:

“Dapr’s use of the k6-operator under Apache-2.0 to run the  
unmodified k6 load testing tool under AGPL-3.0 does not  
constitute distribution or making the AGPL-3.0 program available  
over a network, and therefore would not result in the AGPL-3.0’s  
source code sharing provisions applying to Dapr’s use of the  
k6-operator."

WHEREAS, the Legal Committee has reviewed the updated statement and continues to  
recommend approval of the requested exception.

RESOLVED, that the Governing Board hereby ratifies and confirms its prior approval of  
the requested exception to enable Dapr to use k6 load testing tool via the k6-operator  
component solely for testing purposes as described in the exception request ([Issue  
\#461](https://github.com/cncf/foundation/issues/461)).

## Policy Clarification on Documentation Licensing

WHEREAS, CNCF’s IP policy (in [Section 11 of the CNCF charter](https://github.com/cncf/foundation/blob/main/charter.md#11-ip-policy)) states that CNCF  
project code will be licensed under Apache-2.0, and CNCF documentation will be  
licensed under Creative Commons Attribution 4.0 International (CC-BY-4.0).

WHEREAS, many CNCF project source code repositories include just an Apache-2.0  
license. As a result, unless otherwise separately indicated, files in the source code  
repository which are typically thought of as “documentation” (notably those such as  
README files, release notes, etc.) are published by the projects under Apache-2.0.

WHEREAS, a community member has asked whether these README and similar files  
need to be licensed under CC-BY-4.0 ([Issue \#230](https://github.com/cncf/foundation/issues/230)). A relicensing would likely require  
consent of all contributors to the applicable files.

WHEREAS, the Legal Committee recommends approving a license exception to permit  
source code repositories’ documentation files to be published under either Apache-2.0 or  
CC-BY-4.0.

RESOLVED, that the Governing Board hereby approves a license exception to permit  
CNCF project source code repositories’ documentation files to be published under either  
Apache-2.0 or CC-BY-4.0.

## Fontawesome fonts licensed under OFL 1.1

WHEREAS, the Prometheus project has requested an exception to permit use of the  
Font Awesome license bundle which is licensed under the SIL Open Font License 1.1  
([OFL-1.1](https://spdx.org/licenses/OFL-1.1.html)). The Legal Committee recommends declining the request to add OFL-1.1 to  
the CNCF Licensing Allowlist ([Issue \#360](https://github.com/cncf/foundation/issues/360)), but recommends approving a blanket  
exception to enable use of any Fontawesome font licensed under the OFL 1.1.

RESOLVED, that the Governing Board hereby declines the request to add OFL-1.1 to  
the CNCF Licensing Allowlist ([Issue \#360](https://github.com/cncf/foundation/issues/360)), but hereby approves a blanket exception to  
allow use of any Fontawesome font licensed under the SIL Open Font License 1.1  
([OFL-1.1](https://spdx.org/licenses/OFL-1.1.html)).

## In-kernel eBPF Programs licensed under GPL 2.0 or GPL 2.0 or later

WHEREAS, multiple CNCF projects have submitted license exception requests (e.g.,  
Issues [\#474](https://github.com/cncf/foundation/issues/474) and [\#226](https://github.com/cncf/foundation/issues/226)) for eBPF programs running in the kernel.

WHEREAS, the Legal Committee recommends approving a blanket exception for  
in-kernel eBPF programs licensed under either of the following licenses, either on its  
own or dual licensed in combination with any license already on the CNCF Licensing  
Allowlist Approved Licenses list (e.g., MIT License):

* GPL 2.0  
* GPL 2.0 or later

RESOLVED, that the Governing Board hereby approves a blanket exception for in-kernel  
eBPF programs licensed under either of the following licenses, either on its own or dual  
licensed in combination with any license already on the CNCF Licensing Allowlist  
Approved Licenses list (e.g., MIT License):

* GPL 2.0  
* GPL 2.0 or later

## Cilium use of docker/go-metrics under CC-BY-SA 4.0

WHEREAS, Cilium uses the docker/go-metrics package for collecting metrics. The code  
in this package is licensed Apache 2.0, and the package’s documentation is licensed  
CC-BY-4.0-SA. Cilium uses the package’s code (unmodified) but does not incorporate or  
distribute its documentation in compiled versions of the cilium-cli tool.

WHEREAS, that the Governing Board hereby approves a license exception to permit  
Cilium to use the documentation for the docker/go-metrics package.

## Cilium use of Golang packages under MPL-2.0

WHEREAS, Cilium uses the following Golang packages, which are licensed under  
MPL-2.0, in unmodified form:

* github.com/hashicorp/go-memdb  
* github.com/shoenig/go-m1cpu  
* github.com/hashicorp/packer-plugin-sdk

WHEREAS, the Legal Committee recommends approving an exception to permit Cilium  
to use the Golang packages listed above in unmodified form under the MPL-2.0.

RESOLVED, that the Governing Board hereby approves a license exception to permit  
Cilium to use the Golang packages listed above in unmodified form under the MPL-2.0.  
