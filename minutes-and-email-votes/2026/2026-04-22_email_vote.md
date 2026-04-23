# RESOLUTIONS OF THE CNCF GOVERNING BOARD

**Approved by email vote on** **April 22, 2026**

### **License Exception to allow Hyperlight to use picolibc**

WHEREAS, the Hyperlight project has requested an exception (Issue \#[1117](https://github.com/cncf/foundation/issues/1117)) to use [picolibc](https://github.com/picolibc/picolibc), which uses an overall declared license of BSD-3-Clause, but which contains components licensed under the following other licenses:

* BSL-1.0 (Boost Software License 1.0)  
* NCSA (University of Illinois/NCSA Open Source License)  
* Public Domain / CC0-1.0  
* BSD-2-Clause  
* Apache-2.0  
* MIT License

WHEREAS, although the upstream picolibc repository contains 3 test files that are licensed under copyleft licenses, the Hyperlight project does not intend to use these files and has committed to ensuring that these files never enter its build process and are not automatically retrieved by the user’s system either. This will be accomplished either by (a) using a sparse checkout of picolibc or (b) maintaining a downstream fork or local copy of picolibc with the copyleft files removed.

WHEREAS, the CNCF Legal Committee unanimously recommends that the Governing Board **APPROVE** an exception to allow Hyperlight to use picolibc subject to the following restrictions and scope:

* **Approved Licenses.** This exception allows use of picolibc files under the following licenses only: BSD-3-Clause, BSD-2-Clause, MIT License, BSL-1.0 (Boost Software License 1.0), NCSA (University of Illinois/NCSA Open Source License), or Public Domain / CC0-1.0.

* **Exclusion of Copyleft Files.** Hyperlight must take measures—such as using sparse checkout or maintaining a downstream fork that excludes the copyleft files—to ensure that copyleft files present in the upstream picolibc repository never enter the Hyperlight build environment and are not automatically retrieved by the end user’s system either.


RESOLVED, the Governing Board hereby APPROVES the recommended exception subject to the scope and restrictions described in the foregoing recital.
