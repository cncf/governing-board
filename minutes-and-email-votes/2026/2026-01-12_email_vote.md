# RESOLUTIONS OF THE CNCF GOVERNING BOARD

Approved by email vote on January 12, 2026

WHEREAS, several CNCF projects have requested exceptions to the CNCF IP Policy, which are subject to approval by the Governing Board under the CNCF Charter.

## Blanket Exception for libpathrs and go-pathrs

WHEREAS, the Governing Board previously approved a blanket exception for filepath-securejoin;

WHEREAS, CNCF projects are also seeking a related blanket exception to use [libpathrs and go-pathrs](https://github.com/cyphar/libpathrs) to improve security (Issue \#[**1154**](https://github.com/cncf/foundation/issues/1154));

WHEREAS, the CNCF Legal Committee recommends APPROVAL of a blanket exception to allow any CNCF project to use libpathrs (available under MPL-2.0 or LGPL-3.0) and go-pathrs (available under MPL-2.0) as either (a) a vendored component, (b) build-time dependency, or (c) install-time dependency, in each case provided that the dependency is dynamically or statically linked with the CNCF project’s own code.  
   
RESOLVED, that the Governing Board hereby APPROVES a blanket exception with the scope recommended by the Legal Committee as described above, with the additional requirement that any CNCF project using libpathrs as a statically linked dependency MUST elect to do so under MPL-2.0 (rather than LGPL-3.0) and declare such election in its documentation. Furthermore, to minimize compliance burdens for CNCF projects and downstream users, it is strongly recommended that projects using libpathrs as a dynamically linked dependency also elect to do so under MPL-2.0 (rather than LGPL-3.0).

## License Exception for use of Eclipse Expressly by Keycloak

WHEREAS, the Keycloak project has requested an exception (Issue \#[**1177**](https://github.com/cncf/foundation/issues/1177)) to use [Eclipse Expressly](https://github.com/eclipse-ee4j/expressly), which is licensed under either EPL-2.0 or GPL-2.0-only with Classpath-exception-2.0,

WHEREAS, the CNCF Legal Committee recommends APPROVAL of the requested exception.

RESOLVED, that the Governing Board hereby APPROVES an exception to allow Keycloak to use Eclipse Expressly as a required upstream dependency, under either EPL-2.0 or GPL-2.0-only with Classpath-exception-2.0, provided that it is used in unmodified form and dynamically linked with the project's code.  
