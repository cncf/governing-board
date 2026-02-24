# RESOLUTIONS OF THE CNCF GOVERNING BOARD

Approved by email vote on February 13, 2026

WHEREAS, several CNCF projects have requested exceptions to the CNCF IP Policy, which are subject to approval by the Governing Board under the CNCF Charter.

## **Blanket License Exception for sharp-libvips**

WHEREAS, the kagent project has requested an exception (Issue [\#1212](https://github.com/cncf/foundation/issues/1212)) to use [sharp-lipvips](https://github.com/lovell/sharp), a subdependency of the newest version of Next.js, to enable kagent’s use of newer versions of Next.js;

WHEREAS, the declared overall license of sharp-libvips is LGPL-2.1 or later, but due to bundled components that are licensed LGPL-3.0 or later, the effective license applying to sharp-libvips is LGPL-3.0 or later; 

WHEREAS, because Next.js is used by multiple CNCF projects, the CNCF Legal Committee recommends APPROVAL of a blanket request to allow any CNCF project to use sharp-libvips **as part of Next.js** (and not on a standalone basis), under LGPL-2.1 or later or LGPL-3.0 or later, provided that all of the following conditions are satisfied:

* Sharp-lipvips may be used as a build-time dependency, install-time dependency, or build & test tooling;  
* The CNCF project’s own code may interact with Next.js via dynamic linking, a separate process, or network interaction (static linking would not be permitted under this exception); and  
* Sharp-lipvips must be used in unmodified form.

RESOLVED, the Governing Board hereby APPROVES the recommended exception subject to the scope and conditions described in the foregoing recital.

## **Blanket License Exception for certifi**

WHEREAS, the Konveyor project has requested an exception (Issue [\#1208](https://github.com/cncf/foundation/issues/1208)) to use [certifi](https://github.com/certifi/python-certifi), which is licensed under MPL-2.0.

WHEREAS, the certifi component is a commonly used dependency, and the Governing Board previously approved its use by OSCAL Compass.

WHEREAS, the CNCF Legal Committee recommends APPROVAL of a blanket exception to allow any CNCF project to use certifi under MPL-2.0, provided that it is either (a) stored unmodified in a designated third-party folder, or (b) not stored in the CNCF project repository and instead retrieved at installation or build time from the upstream third party repository or package repository.

RESOLVED, the Governing Board hereby APPROVES the recommended exception subject to the scope and conditions described in the foregoing recital.

## **Blanket License Exception for go-textseg**

WHEREAS, a blanket exception has been requested (Issue [\#1242](https://github.com/cncf/foundation/issues/1242)) to allow all CNCF projects to use [go-textseg](http://github.com/apparentlymart/go-textseg). 

WHEREAS, the CNCF Legal Committee recommends APPROVAL of a blanket exception to allow any CNCF project to use go-textseg under the [Unicode-DFS-2016](https://spdx.org/licenses/Unicode-DFS-2016.html) license.

RESOLVED, the Governing Board hereby APPROVES the recommended exception subject to the scope and conditions described in the foregoing recital.
