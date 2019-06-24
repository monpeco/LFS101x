
### Final Thoughts


In order for you to get the most out of this course, we recommend that you have Linux installed on a machine that you can use throughout this course. You do not need to view the course material on a Linux machine (all you need is a browser). However, you will see that there is a lot of follow-along activities and labs that you will benefit from only if you can do them on your own machine. We have prepared a brief installation guide: "[Preparing Your Computer for LFS101x.2](https://prod-edxapp.edx-cdn.org/assets/courseware/v1/3fa6f8f7a7482a6344efeb7dd0d5bdf0/asset-v1:LinuxFoundationX+LFS101x+3T2018+type@asset+block/Preparing_Your_Computer_for_LFS101x.pdf)", that helps you to select a Linux distribution to install, decide on whether you want to do a stand-alone pure Linux machine or a dual-boot one, whether do a physical or virtual install, etc. And then guides through the steps. We will also discuss the installation procedure in detail in a later section.

We have not covered everything in great detail, but keep in mind that most of the documentation in Linux is actually already on your system in the form of man pages, which we will discuss in great detail later. Whenever you do not understand something or want to know more about a command, program, topic, or utility, you can just type man <topic> at the command line. We will assume you are thinking this way and not constantly repeat "For more information, look at the man page for <topic>".

On a related note, throughout the course we use a shorthand that is common in the open source community. When referring to cases where the user has to make a choice of what to enter (e.g. name of a program or file), we use the short hand 'foo' to represent <insert file name here>. So beware, we are not actually suggesting that you manipulate files or install services called 'foo'!

---

### Linux Philosophy

Linux borrows heavily from the well-established UNIX operating system. It was written to be a free and open source system to be used in place of UNIX, which at the time was designed for computers much more powerful than PCs and was quite expensive. Files are stored in a hierarchical filesystem, with the top node of the system being the root or simply "/". Whenever possible, Linux makes its components available via files or objects that look like files. Processes, devices, and network sockets are all represented by file-like objects, and can often be worked with using the same utilities used for regular files. Linux is a fully multitasking (i.e. multiple threads of execution are performed simultaneously), multiuser operating system, with built-in networking and service processes known as daemons in the UNIX world.

Note: Linux was inspired by UNIX, but it is not UNIX.


---

### Introduction

Suppose that, as part of your job, you need to configure a Linux file server, and you run into some difficulties. If you are not able to figure out the answer yourself or get help from a co-worker, the Linux community might just save the day!

There are many ways to engage with the Linux community:

Post queries on relevant discussion forums.
Subscribe to discussion threads.
Join local Linux groups that meet in your area.



---

### More About Linux Community


The Linux community is a far-reaching ecosystem consisting of developers, system administrators, users and vendors who use many different forums to connect with one another. Among the most popular are:

Internet Relay Chat (IRC) software (such as WeeChat, HexChat, Pidgin and XChat)
Online communities and discussion boards including Linux User Groups (both local and online)
Many collaborative projects hosted on services such as GitHub
Newsgroups and mailing lists, including the Linux Kernel Mailing List
Community events, e.g. Hackathons, Install Fests, Open Source Summits and Embedded Linux Conferences.
A portal to one of the most powerful online user communities can be found at linux.com. This site is hosted by The Linux Foundation and serves over one million unique visitors every month. It has active sections on:

News
Community discussion threads
Free tutorials and user tips.
We will refer several times in this course to relevant articles or tutorials on this site.

--- 

### Linux Distributions

So, what is a Linux distribution and how does it relate to the Linux kernel?

The Linux kernel is the core of the operating system. A full Linux distribution consists of the kernel plus a number of other software tools for file-related operations, user management, and software package management. Each of these tools provides a part of the complete system. Each tool is often its own separate project, with its own developers working to perfect that piece of the system.

While the most recent Linux kernel (and earlier versions) can always be found in The [Linux Kernel Archives](https://www.kernel.org/), Linux distributions may be based on different kernel versions. For example, the very popular RHEL 7 distribution is based on the 3.10 kernel, which is not new, but is extremely stable. Other distributions may move more quickly in adopting the latest kernel releases. It is important to note that the kernel is not an all or nothing proposition, for example, RHEL 7/CentOS 7 have incorporated many of the more recent kernel improvements into their older versions, as have Ubuntu, openSUSE, SLES, etc.

Examples of other essential tools and ingredients provided by distributions include the C/C++ compiler, the gdb debugger, the core system libraries applications need to link with in order to run, the low-level interface for drawing graphics on the screen, as well as the higher-level desktop environment, and the system for installing and updating the various components, including the kernel itself.  And all distributions come with a rather complete suite of applications already installed.


--- 

### Services Associated with Distributions

The vast variety of Linux distributions are designed to cater to many different audiences and organizations, according to their specific needs and tastes. However, large organizations, such as companies and governmental institutions and other entities, tend to choose the major commercially-supported distributions from Red Hat, SUSE, and Canonical (Ubuntu).

CentOS is a popular free alternative to Red Hat Enterprise Linux (RHEL) and is often used by organizations that are comfortable operating without paid technical support. Ubuntu and Fedora are widely used by developers and are also popular in the educational realm. Scientific Linux is favored by the scientific research community for its compatibility with scientific and mathematical software packages. Both CentOS and Scientific Linux are binary-compatible with RHEL; i.e. in most cases, binary software packages will install properly across the distributions.

Many commercial distributors, including Red Hat, Ubuntu, SUSE, and Oracle, provide long term fee-based support for their distributions, as well as hardware and software certification. All major distributors provide update services for keeping your system primed with the latest security and bug fixes, and performance enhancements, as well as provide online support resources.

---

### Summary

You have completed Chapter 2. Let’s summarize the key concepts covered:

Linux borrows heavily from the UNIX operating system, with which its creators were well-versed.
Linux accesses many features and services through files and file-like objects.
Linux is a fully multi-tasking, multi-user operating system, with built-in networking and service processes known as daemons.
Linux is developed by a loose confederation of developers from all over the world, collaborating over the Internet, with Linus Torvalds at the head. Technical skill and a desire to contribute are the only qualifications for participating.
The Linux community is a far reaching ecosystem of developers, vendors, and users that supports and advances the Linux operating system.
Some of the common terms used in Linux are: kernel, distribution, boot loader, service, filesystem, X Window system, desktop  environment, and command line.
A full Linux distribution consists of the kernel plus a number of other software tools for file-related operations, user management, and software package management.

---
