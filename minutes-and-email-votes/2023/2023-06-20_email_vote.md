# RESOLUTIONS OF THE CNCF GOVERNING BOARD

Adopted June 20, 2024

WHEREAS, several CNCF projects have requested exceptions to the CNCF IP Policy, which are subject to approval by the Governing Board under Section 11(g) of the CNCF Charter.

**License exceptions for various MPL 2.0 components**

WHEREAS, license exceptions have been requested to enable use of the following components–all of which are licensed under the Mozilla Public License version 2.0–as dependencies in unmodified form:

| Brief Description | Packages or Programs |
| :---- | :---- |
| hashicorp/go-plugin MPL-2.0 exception, [Issue \#300](https://github.com/cncf/foundation/issues/300) | hashicorp/go-plugin |
| Pixie license exceptions, [Issue \#301](https://github.com/cncf/foundation/issues/301) | hashicorp/go-immutable-radix hashicorp/raft |
| hashicorp libs (cert-manager),  [Issue \#381](https://github.com/cncf/foundation/issues/381) | rootcerts sockaddr vault |
| Additional hashicorp packages used by Cilium project, [Issue \#400](https://github.com/cncf/foundation/issues/400) | hashicorp/consul/api serf go-rootcerts go-immutable-radix go-hclog \*Overlaps with Issue \#301 |
| external-secrets (hashicorp), [Issue \#485](https://github.com/cncf/foundation/issues/485) | go-immutable-radix go-retryablehttp go-plugin go-rootcerts go-secure-stdlib go-sockaddr go-uuid vault go-version yamux \*Overlaps with Issue \#300 |
| Dependency of Notary, [Issue \#526](https://github.com/cncf/foundation/issues/526) | go-cose |

WHEREAS, the Legal Committee recommends that the license exception requests listed above as dependencies in unmodified form be approved, so long as the Governing Board finds it acceptable that this would result in disclosure obligations for MPL v.2 for downstream adopters beyond what would be required under the Apache License 2.0.

RESOLVED, that the license exception requests listed above (Issues [\#300](https://github.com/cncf/foundation/issues/300), [\#301](https://github.com/cncf/foundation/issues/301), [\#381](https://github.com/cncf/foundation/issues/381), [\#400](https://github.com/cncf/foundation/issues/400), [\#485](https://github.com/cncf/foundation/issues/485), and [\#526](https://github.com/cncf/foundation/issues/526)) to enable use of the specified MPL v.2-licensed dependencies in unmodified form are hereby approved by the Governing Board.

---
**License exception for Windows Exporter**

WHEREAS, the Prometheus project has requested an exception (See [Issue \# 514](https://github.com/cncf/foundation/issues/514)) to enable bringing Windows Exporter–which is licensed under the MIT License–into the Prometheus project.

WHEREAS, the Legal Committee recommends approving Prometheus bringing Windows Exporter into the Prometheus project, and having Windows Exporter (including future modifications and future versions) continue to be licensed under the MIT License.

RESOLVED, that the Governing Board approves the requested licensing exception to enable bringing Windows Exporter into the Prometheus project, and having Windows Exporter (including future modifications and future versions) continue to be licensed under the MIT License.

---
**k6-operator usage on Dapr project for e2e stress tests**

WHEREAS, the Dapr project has requested a licensing exception (See [Issue \#461](https://github.com/cncf/foundation/issues/461)) to use the [k6 load testing tool](https://github.com/grafana/k6) via the [k6-operator component](https://github.com/grafana/k6-operator), both of which are made available by Grafana Labs. k6 is published by Grafana under the GNU Affero General Public License, version 3.0 (AGPL-3.0), while k6-operator is published by Grafana under Apache-2.0.

WHEREAS, CNCF has generally taken a strong line against the inclusion of components licensed under AGPL-3.0, in light of its strong copyleft effect coupled with its provisions relating to remote network interaction, as reflected in the [AGPL Recommendations document](https://github.com/cncf/foundation/blob/main/agpl-recommendations.md) in the foundation repository. However, for k6, the Dapr developers have indicated that k6 and k6-operator are not incorporated into the built project binaries and run-time artifacts; rather, the k6 and k6-operator are used solely for testing purposes, specifically to run end-to-end performance tests of Dapr on a Kubernetes cluster.

WHEREAS, the Legal Committee recommends approving the requested exception conditioned on Grafana Labs confirming in writing that its takes the position that Dapr’s use of the k6-operator under Apache-2.0 to run the unmodified k6 load testing tool under AGPL-3.0 would not result in the AGPL-3.0’s copyleft provisions applying to Dapr’s use of the k6-operator, and that such use would not result in creation of a modified version or derivative work.

RESOLVED, that the Governing Board approves the requested exception to enable Dapr to use k6 load testing tool via the k6-operator component solely for testing purposes as described in the exception request ([Issue \#461](https://github.com/cncf/foundation/issues/461)), conditioned on Grafana Labs providing the written statement described above.  
