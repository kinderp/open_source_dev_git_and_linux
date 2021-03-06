# dev_and_linux

# Cheatsheet

## SysVinit to Systemd Cheatsheet
* [Fedora](https://fedoraproject.org/wiki/SysVinit_to_Systemd_Cheatsheet)
* [Debian](https://wiki.debian.org/systemd/CheatSheet)
* [openSUSE](https://en.opensuse.org/openSUSE:Cheat_sheet_13.1#Services)

# LF Projects

* Big Data 
  * [odpi](https://www.odpi.org/) [r-consortium](https://www.r-consortium.org/)
* Networking 
  * [opendaylight](https://www.opendaylight.org/) 
  * [opnfv](https://www.opnfv.org/) 
  * [onap](https://www.onap.org/)
* Embedded 
  * [dronecode](https://www.dronecode.org/) 
  * [zephyrproject](https://www.zephyrproject.org/)
* Web Tools 
  * [js foundation](https://js.foundation/)  
  * [nodejs](https://nodejs.org/en/)
* Cloud 
  * [cloudfoundry](https://www.cloudfoundry.org/) 
  * [cloud nnative computing foundation](https://www.cncf.io/) 
  * [open containers initiative](https://www.opencontainers.org/)
* Automative 
  * [automotive](https://www.automotivelinux.org/)
* Security 
  * [the core infrastructure initiative](https://www.coreinfrastructure.org/)
* Blockchain 
  * [hyperledger](https://www.hyperledger.org/)

# [Open Source Guides For The Enterprise](https://www.linuxfoundation.org/resources/open-source-guides/)
Leverage best practices for running an open source program office or starting an open source project in your organization. Developed by The Linux Foundation in partnership with the TODO Group, these resources represent the experience of our staff, projects, and members.

# System Info

* [uname](https://linux.die.net/man/1/uname)
```bash
>uname --help
Usage: uname [OPTION]...
Print certain system information.  With no OPTION, same as -s.

  -a, --all                print all information, in the following order,
                             except omit -p and -i if unknown:
  -s, --kernel-name        print the kernel name
  -n, --nodename           print the network node hostname
  -r, --kernel-release     print the kernel release
  -v, --kernel-version     print the kernel version
  -m, --machine            print the machine hardware name
  -p, --processor          print the processor type (non-portable)
  -i, --hardware-platform  print the hardware platform (non-portable)
  -o, --operating-system   print the operating system
      --help     display this help and exit
      --version  output version information and exit

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Full documentation at: <https://www.gnu.org/software/coreutils/uname>
or available locally via: info '(coreutils) uname invocation'

```

```bash
>uname -a
Linux linux-pnjx 4.12.14-lp150.12.7-default #1 SMP Tue Jul 17 12:08:37 UTC 2018 (4804d19) x86_64 x86_64 x86_64 GNU/Linux
```

```bash
>uname -s
Linux
```

```bash
>name -n
linux-pnjx
```

```bash
>uname -r
4.12.14-lp150.12.7-default
```

```bash
>uname -v
#1 SMP Tue Jul 17 12:08:37 UTC 2018 (4804d19)
```

```bash
>uname -m
x86_64
```

```bash
uname -p
x86_64
```

```bash
>uname -i
x86_64
```
 
```bash
>uname -o
GNU/Linux
```
 


# [CI tools](https://stackify.com/top-continuous-integration-tools/?utm_referrer=https://lms.quickstart.com/custom/862395/page12873.html)
* [Jenkins](https://jenkins.io/)
* [travis-ci](https://travis-ci.org/)
* [teamcity](https://www.jetbrains.com/teamcity/)
* [gocd](https://www.gocd.org/)
* [gitlab](https://about.gitlab.com/features/gitlab-ci-cd/)
* [bamboo](https://www.atlassian.com/software/bamboo)
* [codeship](https://codeship.com/)
* [circleci](https://circleci.com/)

# Standard

* [Linux Standard Base LSB](https://wiki.linuxfoundation.org/lsb/start)

# Man Pages

* 1 User Commands (standard commands)
* 2 System Calls
* 3 Subroutines (Library Functions)
* 4 Devices
* 5 File Formarts and files used by a program
* 6 Games
* 7 Miscellaneous
* 8 System Administration
* 9 Kernel Documentation
* n New (mainly uded by Tcl/Tk)
* suffix
  * p (e.g. 1p) Posix Standard Specifications
  * x (e.g. 3x) X Window System

# Info Commands

Key | Function
------------ | -------------
n | Go to next node
p | Go to previous node
u | Go tu upper node
l | Go to last visited node
space or PageDown | Go to next page
delete or backspace or PageUp | Go to previous page
/ or CTRL+s | Search for the string prompted for
i | Search for a node containing the stirng prompted for

The info systems is a hierarchical tree of nodes, each of nodes may have multiple pages.
