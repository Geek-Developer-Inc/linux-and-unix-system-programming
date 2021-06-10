# Chapter 1 History and Standards

#### Linux is a member of the UNIX family of operating systems

#### then consider the two key currents that led to the Linux system as it exists today: the GNU project and the development of the Linux kernel

#### Two definitions of the term UNIX are in common use
One of these denotes operating systems that have passed the official conformance tests for the Single UNIX Specification and thus are officially granted the right to be branded as “UNIX” by The Open Group (the holders of the UNIX trademark)
The other common meaning attached to the term UNIX denotes those systems that look and behave like classical UNIX systems (i.e., the original Bell Laboratories UNIX and its later principal offshoots, System V and BSD)

#### The term Linux is commonly used to refer to the entire UNIX-like operating system of which the Linux kernel forms a part

#### One of the important results of the GNU project was the development of the GNU General Public License (GPL), Much of the software in a Linux distribution, including the kernel, is licensed under the GPL or one of a number of similar licenses

#### Software licensed under the GPL must be made available in source code form, and must be freely redistributable under the terms of the GPL

#### Linux kernel version numbers
  Like most free software projects, Linux follows a release-early, release-often model, so that new kernel revisions appear frequently
  The kernel developers adopted a kernel version numbering scheme with each release numbered x.y.z: x representing a major version, y a minor version within that major version, and z a revision of the minor version (minor improvements and bug fixes)
  There is no longer a separation between stable and development kernels
  Sometimes, a stable 2.6.z release may require minor patches to fix bugs or security problems
  Additional responsibility is shifted onto distribution vendors to ensure the stability of the kernel provided with a distribution

#### The Linux Standard Base
  As a general goal, Linux (i.e., kernel, glibc, and tool) development aims to conform to the various UNIX standards, especially POSIX and the Single UNIX Specification
  The LSB develops and promotes a set of standards for Linux systems with the aim of ensuring binary application compatibility across Linux distributions, so that compiled applications should be able to run on any LSB-conformant system running on the same hardware  