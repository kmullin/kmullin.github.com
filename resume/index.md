---
layout: resume
title: /resume

# Resume stuff
profile: |- # preserve newlines, no newline at end
  Seasoned DevOps/Site Reliability Engineer with 10+ years of experience designing, developing, and implementing large-scale infrastructure systems, both on-prem baremetal and cloud based. My expertise lies in creating tools and writing infrastructure as code, with a deep understanding of continuous integration and delivery principles.

  I've honed my skills by working closely with cross-functional teams of developers, and operations personnel, and I have excellent communication and collaboration skills. I'm a strong problem solver and am adept at troubleshooting complex issues in real-time and devising effective solutions to prevent future incidents. I do not run away from fires, and have been in the trenches of some of the largest most impactful incidents any organization will ever face.

  I also helped launch a brand new AWS Service known as IVS during my tenure at Twitch.

jobs:
  - company: Twitch
    title: Senior Systems Development Engineer / Site Reliability Engineer
    location: San Francisco, CA
    dates:
      start: Nov 2013
      end: Mar 2023
    description: |-
      Initially part of a 3-person operations team, I advocated for automation and operational excellence. I developed most of the Puppet configuration management, provisioning and monitoring systems, reducing new datacenter build and deployment time by 75%. This facilitated Twitch's growth demands.
      In addition to on-call operations and troubleshooting, I mentored interns, junior developers, and operations staff. My earlier baremetal datacenter experience was instrumental in designing and scaling essential infrastructure such as DNS, DHCP, LDAP, and HTTP Proxies (Squid).
      Later, I shifted focus to writing critical core services which would support cross organizational operational processes.
    duties:
      - Designed, implemented and scaled Hashicorp Consul to 100+ datacenters in an automatable and maintainable way
      - Mentored and guided software and operations engineers to level up their skills and understanding of best practices around operational maintainability
      - Aided and guided troubleshooting during impactful outages
      - Worked with skip-level directors and VPs on operational vision and direction
      - Migrated legacy baremetal services to AWS, generally necessitating new design patterns
      - Designed and built network monitoring and alerting services for Anycast IP addressing
      - Researched new technologies and designed PoCs to reduce technical debt and operational toil
      - Built and deployed a baremetal Secrets Management system
      - Negotiated, procured and configured IPAM appliances

  - company: UserVoice, Inc.
    title: Head of Operations
    location: San Francisco, CA
    dates:
      start: Apr 2011
      end: Nov 2013
    description:
      Build, scale, and maintain operations of production SaaS product for 100,000+ customers.
    duties:
      - Capacity Planning
      - Manage Remote Hardware
      - Maintain/Support/Contribute to Production Codebase
      - Site Reliability and Performance

  - company: Friendster, Inc.
    title: System Administrator
    location: Mountain View, CA
    dates:
      start: Jul 2007
      end: Jul 2011
    description:
      Build, install, and maintain 2000+ servers in a data center.
      Maintain and expand both the edge network and internal networks.
    duties:
      - Manage Data Center
      - Meet/Negotiate with Vendors
      - Write Automation Scripts
      - Build/Design Inventory System using Python/Django
      - Manage High Availability Database Architecture and Replication

  - company: EFI, Inc.
    title: Engineering/Desktop Support
    location: Foster City, CA
    dates:
      start: Mar 2007
      end: Jun 2007
    description:
      Support engineers using ClearCase on Windows and Linux platforms.
      Troubleshoot server-side issues affecting ClearCase on Red Hat Enterprise Linux and Solaris.
    duties:
      - Answer High-Priority Help Desk Calls
      - Troubleshoot User Issues
      - Maintain System Inventory
      - Research/Plan New Source Code Control Technologies

skills:
  - Programming:
    - Golang
    - Python
    - Ruby
    - PHP
    - Perl
  - Virtualization:
    - KVM (qemu)
    - Xen
    - VMWare (ESXi, Server)
  - Containerization:
    - Docker
    - Podman
  - Distributed Databases:
    - Consul
    - Zookeeper
  - Configuration Management:
    - Puppet
    - Chef
    - Ansible
  - Linux Distributions:
    - Debian / Ubuntu
    - RedHat (CentOS)
    - Arch
    - Gentoo
    - Slackware
  - Services:
    - OpenVPN
    - NIS
    - NFS
    - OpenLDAP (slapd)
    - DNS (Bind9, nsd, unbound)
  - Webservers / Load Balancers:
    - Nginx
    - Haproxy
    - Apache
    - Tomcat
  - Datastores:
    - DynamoDB
    - MySQL
    - Redis
    - Riak
    - MemcacheD
    - MongoDB
    - PostgreSQL
  - Monitoring:
    - Nagios
    - Ganglia
    - Cacti
    - Graphite
    - Collectd

# hobbies:

---
