FreeBSD Source:
---------------
This is the top level of the FreeBSD source directory.

FreeBSD is an operating system used to power modern servers, desktops, and embedded platforms.
A large community has continually developed it for more than thirty years.
Its advanced networking, security, and storage features have made FreeBSD the platform of choice for many of the busiest web sites and most pervasive embedded networking and storage devices.

For copyright information, please see [the file COPYRIGHT](COPYRIGHT) in this directory.
Additional copyright information also exists for some sources in this tree - please see the specific source directories for more information.

The Makefile in this directory supports a number of targets for building components (or all) of the FreeBSD source tree.
See build(7), config(8), [FreeBSD handbook on building userland](https://docs.freebsd.org/en/books/handbook/cutting-edge/#makeworld), and [Handbook for kernels](https://docs.freebsd.org/en/books/handbook/kernelconfig/) for more information, including setting make(1) variables.

For information on the CPU architectures and platforms supported by FreeBSD, see the [FreeBSD
website's Platforms page](https://www.freebsd.org/platforms/).

For official FreeBSD bootable images, see the [release page](https://download.freebsd.org/ftp/releases/ISO-IMAGES/).

Source Roadmap:
---------------
| Directory | Description |
| --------- | ----------- |
| bin | System/user commands. |
| cddl | Various commands and libraries under the Common Development and Distribution License. |
| contrib | Packages contributed by 3rd parties. |
| crypto | Cryptography stuff (see [crypto/README](crypto/README)). |
| etc | Template files for /etc. |
| gnu | Commands and libraries under the GNU General Public License (GPL) or Lesser General Public License (LGPL). Please see [gnu/COPYING](gnu/COPYING) and [gnu/COPYING.LIB](gnu/COPYING.LIB) for more information. |
| include | System include files. |
| kerberos5 | Kerberos5 (Heimdal) package. |
| lib | System libraries. |
| libexec | System daemons. |
| release | Release building Makefile & associated tools. |
| rescue | Build system for statically linked /rescue utilities. |
| sbin | System commands. |
| secure | Cryptographic libraries and commands. |
| share | Shared resources. |
| stand | Boot loader sources. |
| sys | Kernel sources (see [sys/README.md](sys/README.md)). |
| targets | Support for experimental `DIRDEPS_BUILD` |
| tests | Regression tests which can be run by Kyua.  See [tests/README](tests/README) for additional information. |
| tools | Utilities for regression testing and miscellaneous tasks. |
| usr.bin | User commands. |
| usr.sbin | System administration commands. |

For information on synchronizing your source tree with one or more of the FreeBSD Project's development branches, please see [FreeBSD Handbook](https://docs.freebsd.org/en/books/handbook/cutting-edge/#current-stable).



---

# WINTERHOLD: The Secure Architecture Framework

**WINTERHOLD** is the name of our complete **architecture framework**, designed to ensure **digital sovereignty**, **critical security**, and **auditability** for the autonomy systems developed by **IA\_AUT\_ECO**.

WINTERHOLD establishes the technical standard for our Fabless partners and institutions.

## The Deep Tech Core: A Sovereign and Secure OS

Our framework relies on uncompromising technical choices, aiming for resilience and enduring security.

The base operating system is **Hearthfire**, a hardened **FreeBSD Fork**, which provides a stable and proven foundation for **Zero Trust Architecture (ZTA)** on **NVIDIA Jetson** platforms.

* **Future Security:** **Post-Quantum Cryptography (PQC)** is implemented to protect long-term communications and the encryption keys of **DELPHINE** against future quantum computer threats.
* **User Interface:** The Graphical User Interface (GUI) for the OS and supervision applications is developed using the **Qt Framework**, ensuring a professional, ergonomic, and portable interface.
* **Central AI Agent:** The entire suite of AI agents (**MASAQ, Skald, Ysgrammor**) runs within a secure container managed by **Hearthfire**, guaranteeing decision traceability.

## The WINTERHOLD Promise: Trust by Design

Our Fabless approach is underpinned by the WINTERHOLD framework, which turns Open Source components into an industrial-grade, Deep Tech solution.

### Regulatory Alignment

WINTERHOLD is designed to meet the challenges of AI and cybersecurity regulations:

* **NIS2 Directive:** Built-in cyber resilience and supply chain risk management (SBOM).
* **AI Act:** Risk classification and traceability of AI decisions (**Ysgrammor**).
* **ISO (Quality and Safety):** Standardization of software design processes and hardware requirements.

## The Modular WINTERHOLD Architecture

WINTERHOLD defines the secure integration of all these essential components:

* **DELPHINE (Koalix):** The Ethical CRM and Sovereign Database for critical data management.
* **The Autonomy Agents (DAWNSTAR & ESBERN):** The multi-agent robotic system (wheelchair and companion) that executes physical autonomy using ROS 2.

## Fabless Model and Standards

Our business model is Fabless; we license the design and software while focusing on core innovation.

* **Design Standardization:** Our partners must adhere to our **Open Source design standards** (3D plans, wear calculations, tolerances) to ensure material compatibility with our software.
* **Software Standards:** We provide continuous software updates, including PQC enhancements, for the deployed architecture.

**WINTERHOLD is the assurance that you are deploying the most powerful, secure, and ethical autonomy solution on the market.**
