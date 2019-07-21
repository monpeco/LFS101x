### About The Linux Foundation

Since its inception in 1991, Linux has grown to become a major force in computing - powering everything from the New York Stock Exchange, to mobile phones, supercomputers, and consumer devices.

The Linux Foundation partners with the world's leading developers and companies to solve the hardest technology problems and accelerate open technology development and commercial adoption. The Linux Foundation makes it its mission to provide experience and expertise to any initiative working to solve complex problems through open source collaboration, providing the tools to scale open source projects: security best practices, governance, operations and ecosystem development, training and certification, licensing, and promotion.

Linux is the world's largest and most pervasive open source software project in history. The Linux Foundation is home to Linux creator Linus Torvalds and lead maintainer Greg Kroah-Hartman, and provides a neutral home where Linux kernel development can be protected and accelerated for years to come. The success of Linux has catalyzed growth in the open source community, demonstrating the commercial efficacy of open source and inspiring countless new projects across all industries and levels of the technology stack.

The Linux Foundation's work today extends far beyond Linux, fostering innovation at every layer of the software stack. The Linux Foundation is the umbrella organization for many critical open source projects that power corporations today, spanning all industry sectors:

Big data and analytics: ODPi, R Consortium
Networking: OpenDaylight, ONAP, OPNFV
Embedded: Dronecode, Zephyr
Web tools: JS Foundation, Node.js
Cloud computing: Cloud Foundry, Cloud Native Computing Foundation, Open Container Initiative
Automotive: Automotive Grade Linux
Security: The Core Infrastructure Initiative
Blockchain: Hyperledger
And many more.
To learn more about The Linux Foundation, visit The Linux Foundation's website.


---
### Focus on Three Major Linux Distribution Families

In the next chapter, you will learn about the components that make up a Linux distribution.

For now, what you need to know is that this course focuses on the three major Linux distribution families that currently exist. However, as long as there are talented contributors, the families of distributions and the distributions within these families will continue to change and grow. People see a need, and develop special configurations and utilities to respond to that need. Sometimes that effort creates a whole new distribution of Linux. Sometimes, that effort will leverage an existing distribution to expand the members of an existing family.

For a rather long list of available distributions, see The LWN.net Linux Distribution List.

---

### The Red Hat Family

Red Hat Enterprise Linux (RHEL) heads the family that includes CentOS, Scientific Linux, and Oracle Linux.

Fedora has a close relationship with RHEL and contains significantly more software than Red Hat's enterprise version. One reason for this is that a diverse community is involved in building Fedora, with many contributors who do not work for Red Hat. Furthermore, it is used as a testing platform for future RHEL releases.

In this course, CentOS is often used for activities, demos, and labs because it is available at no cost to the end user and has a much longer release cycle than Fedora (which releases a new version every six months or so).

The basic version of CentOS is also virtually identical to RHEL, the most popular Linux distribution in enterprise environments.


---

### Key Facts About the Red Hat Family

Some of the key facts about the Fedora distribution family are:

It often serves as an upstream testing platform for RHEL.
CentOS and Scientific Linux are close clones of RHEL, while Oracle Linux is mostly a copy with some changes.
Kernel version 3.10 is used in RHEL/CentOS 7.
It supports hardware platforms such as x86, x86-64, Itanium, PowerPC, and IBM System z.
It uses the RPM-based yum package manager (we cover it in more detail later) to install, update, and remove packages in the system.
RHEL is widely used by enterprises which host their own systems.

---

### The SUSE Family

The relationship between SUSE, SUSE Linux Enterprise Server (SLES), and openSUSE is similar to the one described between Red Hat Enterprise Linux, CentOS, and Fedora.

In this case, we decided to use both openSUSE Leap 15 and the previous version, openSUSE Leap 42, as reference distributions for the SUSE family, as it is available to end users at no cost. Because the two products are extremely similar, the material that covers openSUSE can typically be applied to SLES with few problems.

Note: Despite the confusing numbering scheme, openSUSE Leap 15 is the newer one; version numbers were adjusted to mimic SLES.

---

### Key Facts About the SUSE Family

Some of the key facts about the SUSE family are listed below:

SUSE Linux Enterprise Server (SLES) is upstream for openSUSE.
Kernel version 4.12 is used in openSUSE Leap 15.
It uses the RPM-based zypper package manager (we cover it in more detail later) to install, update, and remove packages in the system.
It includes the YaST (Yet Another Setup Tool) application for system administration purposes.
SLES is widely used in retail and many other sectors.


---

### The Debian Family

The Debian distribution is upstream for several other distributions, including Ubuntu. In turn, Ubuntu is upstream for Linux Mint and a number of other distributions. It is commonly used on both servers and desktop computers. Debian is a pure open source community project (not owned by any corporation) and has a strong focus on stability.

Debian provides by far the largest and most complete software repository to its users of any Linux distribution.

Ubuntu aims at providing a good compromise between long term stability and ease of use. Since Ubuntu gets most of its packages from Debian’s stable branch, Ubuntu also has access to a very large software repository. For those reasons, we will use Ubuntu 18.04 LTS (Long Term Support) as the reference Debian family distribution for this course. Ubuntu is a registered trademark of Canonical Ltd. and is used throughout this course with their permission.


---

### Key Facts About the Debian Family

Some key facts about the Debian family are listed below:

The Debian family is upstream for Ubuntu, and Ubuntu is upstream for Linux Mint and others.
Kernel version 4.15 is used in Ubuntu 18.04 LTS.
It uses the DPKG-based APT package manager (using apt-get, apt-cache, etc. which we cover in more detail later) to install, update, and remove packages in the system.
Ubuntu has been widely used for cloud deployments.
While Ubuntu is built on top of Debian and is GNOME-based under the hood, it differs visually from the interface on standard Debian, as well as other distributions.



