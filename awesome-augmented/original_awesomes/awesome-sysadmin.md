<!--
  Title: Awesome Sysadmin
  Description: A curated list of amazingly awesome open source sysadmin resources.
  Author: n1trux
  -->

# Awesome Sysadmin [![certified awesome!](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

**A curated list of amazingly awesome open source sysadmin resources.** Please read [CONTRIBUTING](./CONTRIBUTING.md) if you wish to add software and consider [donating](https://github.com/n1trux/awesome-donations) to the FLOSS projects you use regularly.

* [Awesome Sysadmin](#awesome-sysadmin)
  * [Automation](#automation)
  * [Backups](#backups)
  * [Build and software organization tools](#build-and-software-organization-tools)
  * [ChatOps](#chatops)
  * [Client Management](#client-management)
  * [Cloning](#cloning)
  * [Cloud Computing](#cloud-computing)
  * [Cloud Orchestration](#cloud-orchestration)
  * [Cloud Storage](#cloud-storage)
  * [Code Review](#code-review)
  * [Collaborative Software](#collaborative-software)
  * [Configuration Management Database](#configuration-management-database)
  * [Configuration Management](#configuration-management)
  * [Continuous Integration & Continuous Deployment](#continuous-integration--continuous-deployment)
  * [Control Panels](#control-panels)
  * [Deployment Automation](#deployment-automation)
  * [Distributed Filesystems](#distributed-filesystems)
  * [DNS](#dns)
  * [Editors](#editors)
  * [Identity Management](#identity-management)
  * [IT Asset Management](#it-asset-management)
  * [Log Management](#log-management)
  * [Mail Clients](#mail-clients)
  * [Mail Servers](#mail-servers)
  * [Monitoring](#monitoring)
  * [Metric & Metric Collection](#metric--metric-collection)
  * [Network Configuration Management](#network-configuration-management)
  * [Newsletter](#newsletters)
  * [NoSQL](#nosql)
  * [Packaging](#packaging)
  * [Project Management](#project-management)
  * [Queuing](#queuing)
  * [RDBMS](#rdbms)
  * [Remote Management](#remote-management)
  * [Security](#security)
  * [Service Discovery](#service-discovery)
  * [Software Containers](#software-containers)
  * [SSH](#ssh)
  * [Statistics](#statistics)
  * [Status Pages](#status-pages)
  * [Ticketing systems](#ticketing-systems)
  * [Troubleshooting](#troubleshooting)
  * [Version control](#version-control)
  * [Virtualization](#virtualization)
  * [VPN](#vpn)
  * [XMPP](#xmpp)
  * [Web](#web)
  * [Wiki Software](#wiki-software)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Books](#books)
  * [Communities/Forums](#communities--forums)
  * [Newsletters](#newsletters)
  * [Repositories](#repositories)
  * [Websites](#websites)
  * [Wikis](#wikis)

## Automation
*Automation build.*

  * [Apache Ant](https://ant.apache.org/) - Automation build tool, similar to make, written in Java.
  * [Apache Maven](http://maven.apache.org/) - Build automation tool mainly for Java.
  * [Bazel](http://bazel.io/) - Google's build system.
  * [GNU Make](http://www.gnu.org/software/make/) - The most popular automation build tool for many purposes.
  * [Gradle](http://gradle.org/) - Another build automation system.
  * [Rake](https://github.com/ruby/rake) - Build automation tool similar to Make, written in and extensible in Ruby.

## Backups
*Backup software.*

  * [Amanda](http://www.amanda.org/) - Client-server model backup tool.
  * [Bareos](http://www.bareos.org/en/) - A fork of Bacula backup tool.
  * [Backupninja](https://labs.riseup.net/code/projects/backupninja) - Lightweight, extensible meta-backup system.
  * [BorgBackup](https://github.com/borgbackup/borg) - A fork of [Attic](https://attic-backup.org) deduplicating backup program written in Python.
  * [Brebis](http://brebisproject.org) - A fully automated backup checker
  * [Burp](http://burp.grke.org/) - Network backup and restore program.
  * [Duplicity](http://duplicity.nongnu.org/) - Encrypted bandwidth-efficient backup using the rsync algorithm.
  * [Elkarbackup](https://github.com/elkarbackup/elkarbackup) - Backup solution based on RSnapshot with a simple web interface
  * [Lsyncd](https://github.com/axkibe/lsyncd) - File Monitor which spawns a process to synchronize the changes (rsync by default).
  * [Obnam](http://obnam.org/) - An easy, secure, snapshots-based backup program with data de-duplication.
  * [Rdiff-backup](http://www.nongnu.org/rdiff-backup/) - An easy A remote incremental backup of all your files.
  * [Rsnapshot](http://rsnapshot.org/) - Filesystem Snapshotting Utility.
  * [Snebu](http://www.snebu.com/) – Snapshot backup with global multi-client deduplication and transparent compression.
  * [UrBackup](http://www.urbackup.org/) - Another client-server backup system.
  * [DREBS](https://github.com/dojo4/drebs) - AWS EBS backup script that supports strategies.
  * [ZBackup](http://zbackup.org/) - A versatile deduplicating backup tool.

## Build and software organization tools
*Build and software organization tools.*

  * [EasyBuild](https://easybuild.readthedocs.org/en/latest/) - EasyBuild builds software and modulefiles for High Performance Computing (HPC) systems in an efficient way.
  * [environment-modules Lmod](https://www.tacc.utexas.edu/research-development/tacc-projects/lmod) - Lmod is a Lua based module system that easily handles the MODULEPATH Hierarchical problem.
  * [HPCBIOS](hpcbios.readthedocs.org/en/latest/) - HPCBIOS is an effort to setup a common, well-documented and reproducible, environment spanning across multiple HPC systems & sites, *inclusive* of documentation.

## ChatOps
*Conversation-driven development and management. See https://www.reddit.com/r/chatops for more information.*

  * [CloudBot](https://github.com/CloudBotIRC/CloudBot) - The simple, fast, expandable Python IRC bot.
  * [Eggdrop](http://www.eggheads.org/) - the world's most popular IRC bot, designed for flexibility and ease of use, and is freely distributable under the GNU GPL.
  * [Err](http://errbot.io/) - a plugin based chatbot designed to be easily deployable, extensible and maintainable.
  * [Hubot](https://hubot.github.com/) - A customizable, life embetterment robot.
  * [Lazlo](https://github.com/djosephsen/lazlo) - A chatops automation framework in Go.
  * [Lita](https://www.lita.io/) - A robot companion for your company's chat room.

## Client management
*Managing software on desktop computers.*

  * [Chocolatey](https://chocolatey.org/) – Windows CLI package manager written in .NET/PS, based on [NuGet](https://www.nuget.org/).
  * [just-install](http://just-install.it/) – Python script for downloading and silently installing MSI files.
  * [OCS Inventory NG](http://www.ocsinventory-ng.org/en/) - Inventory, deployment and network scan.
  * [Opsi](http://www.opsi.org/en) (open PC server integration) - Client Management for Windows based on Debian.
  * [WAPT](https://dev.tranquil.it/wiki/WAPT_-_apt-get_pour_Windows/en) - Network-wide (un)installation, configuration and upgrades of Windows based software.
  * [WPKG](http://wpkg.org/) - Software deployment, upgrade and removal program for Windows.

## Cloning
*Cloning software.*

  * [Clonezilla](http://clonezilla.org/) - Partition and disk imaging/cloning program.
  * [Fog](https://www.fogproject.org/) - Another computer cloning solution.

## Cloud Computing

  * [AppScale](https://github.com/AppScale/appscale) - Cloud software with Google App Engine compatibility.
  * [Archipel](http://archipelproject.org/) - Manage and supervise virtual machines using Libvirt.
  * [CloudStack](http://cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services.
  * [Cobbler](http://cobbler.github.io/) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments.
  * [Cracow Cloud One - Polish Private Cloud](http://cc1.ifj.edu.pl/) - The CC1 system provides a complete solution for Private Cloud Computing.
  * [Eucalyptus](https://www.eucalyptus.com/) - Private cloud software with AWS compatibility.
  * [Flynn](https://flynn.io) - PaaS
  * [Mesos](http://mesos.apache.org/) - Develop and run resource-efficient distributed systems.
  * [OpenNebula](http://opennebula.org/) - User-driven cloud management platform for sysadmins and devops.
  * [Openshift](http://www.openshift.org) - PaaS product from Red Hat.
  * [OpenStack](https://www.openstack.org/) - Build private and public clouds.
  * [The Foreman](http://theforeman.org/) - Complete lifecycle management tool for physical and virtual servers. FOSS.
  * [Tsuru](https://tsuru.io) - Tsuru is an extensible Platform as a Service software.

## Cloud Orchestration

  * [BOSH](http://bosh.io/docs/) - IaaS orchestration platform originally written for deploying and managing Cloud Foundry PaaS, but also useful for general purpose distributed systems.
  * [Cloudify](http://getcloudify.org/) - TOSCA-based cloud orchestration software platform written in Python and YAML.
  * [CloudSlang](http://www.cloudslang.io/) - Flow-based orchestration tool for managing deployed applications, with Docker capabilities.
  * [Juju](https://jujucharms.com/) - Cloud orchestration tool which manages services as charms, YAML configuration and deployment script bundles.
  * [Kubernetes](http://kubernetes.io/) - Orchestration system for Docker containers - ([Source Code](https://github.com/kubernetes/kubernetes), [Documentation](http://kubernetes.io/docs/)) `Apache` `Go`
  * [MCollective](https://puppetlabs.com/mcollective) - Ruby framework to manage server orchestration, developed by Puppet labs.
  * [Overcast](http://andrewchilds.github.io/overcast/) - Deploy VMs across different cloud providers, and run commands and scripts across any or all of them in parallel via SSH.
  * [Rundeck](http://rundeck.org/) - Simple orchestration tool.
  * [Salt](http://saltstack.com/) - Fast, scalable and flexible systems management software written in Python/ZeroMQ.
  * [StackStorm](https://stackstorm.com/) - Event Driven Operations and ChatOps platform for infrastructure management. Written in Python

## Cloud Storage

  * [git-annex assistant](http://git-annex.branchable.com/assistant/) - A synchronised folder on each of your OSX and Linux computers, Android devices, removable drives, NAS appliances, and cloud services.
  * [ownCloud](https://owncloud.org) - Provides universal access to your files via the web, your computer or your mobile devices.
  * [Pydio](https://pyd.io) - Pydio (formerly AjaXplorer) is a mature solution for file sharing and synchronization.
  * [Seafile](https://www.seafile.com/en/home/) - Another Cloud Storage solution.
  * [SparkleShare](http://sparkleshare.org/) - Provides cloud storage and file synchronization services. By default, it uses Git as a storage backend.
  * [Swift](http://docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.
  * [Syncthing](https://syncthing.net/) - System for private, encrypted and authenticated distribution of data.

## Code Review
*Web Based collaborative code review system.*

  * [Gerrit](https://www.gerritcodereview.com/) - Based on the Git version control, it facilitates software developers to review modifications to the source code and approve or reject those changes.
  * [Phabricator](http://phabricator.org/) - Code review tool build by facebook and used by WikiMedia, FB, dropbox etc. Comes with an integrated wiki, bug tracker, VC integration and a CLI tool called arcanist.
  * [Review Board](https://www.reviewboard.org/) - Available as free software under the MIT License.

## Collaborative Software
*Collaborative software or groupware suites.*

  * [Citadel/UX](http://www.citadel.org/) - Collaboration suite (messaging and groupware) that is descended from the Citadel family of programs.
  * [EGroupware](http://www.egroupware.org/start.html) - Groupware software written in PHP.
  * [Horde Groupware](http://www.horde.org/apps/groupware) - PHP based collaborative software suite that includes email, calendars, wikis, time tracking and file management.
  * [Kolab](https://kolab.org/) - Another groupware suite.
  * [SOGo](http://www.sogo.nu/) - Collaborative software server with a focus on simplicity and scalability.
  * [Zimbra](http://community.zimbra.com/) - Collaborative software suite, that includes an email server and web client.

## Configuration Management Database
*Configuration management database (CMDB) software.*

  * [i-doit](http://www.i-doit.org/) - IT Documentation and CMDB.
  * [iTop](http://www.combodo.com/-Overview-.html) - Complete ITIL web based service management tool.
  * [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
  * [Clusto](https://github.com/clusto/clusto) - Helps you keep track of your inventory, where it is, how it's connected, and provides an abstracted interface for interacting with the elements of the infrastructure.
  * [Collins](http://tumblr.github.io/collins/) - At Tumblr, it's the infrastructure source of truth and knowledge.

## Configuration Management
*Configuration management tools.*

  * [Ansible](http://www.ansible.com/) -  It's written in Python and manages the nodes over SSH.
  * [CFEngine](https://cfengine.com/) - Lightweight agent system. Configuration state is specified via a declarative language.
  * [Chef](https://www.chef.io/chef/) - It's written in Ruby and Erlang and uses a pure-Ruby DSL.
  * [Pallet](http://palletops.com/) - Infrastructure definition, configuration and management via a Clojure DSL.
  * [Puppet](https://puppetlabs.com/) - It's written in Ruby and uses Puppet's declarative language or a Ruby DSL.
  * [Salt](http://saltstack.com/) - It's written in Python.
  * [Slaughter](http://www.steve.org.uk/Software/slaughter/) - It's written in Perl.

## Continuous Integration & Continuous Deployment
*Continuous integration/deployment software.*

  * [Buildbot](http://buildbot.net/) - Python-based toolkit for continuous integration.
  * [Drone](https://github.com/drone/drone) - Continuous integration server built on Docker and configured using YAML files.
  * [GitLab CI](https://about.gitlab.com/gitlab-ci/) - Based off of ruby. They also provide GitLab, which manages git repositories.
  * [Go](http://www.go.cd/) - Continuous delivery server.
  * [Jenkins](http://jenkins-ci.org/) - An extendable continuous integration server.

## Control Panels
*Web hosting and server or service control panels*

  * Web hosting
    * [Froxlor](https://froxlor.org/) - Easy to use panel for Linux with Nginx and PHP-FPM support.
    * [ISPConfig](http://www.ispconfig.org) - Hosting control panel for Linux.
    * [Sentora](http://sentora.org/) - Control panel for Linux, BSD, and Windows based on ZPanel.
    * [VestaCP](http://vestacp.com/) - Hosting panel for Linux but with Nginx.
  * DNS
    * [Atomia DNS](http://atomiadns.com/) - DNS management system.
    * [PDNS Gui](https://github.com/odoucet/pdns-gui) - WebGUI which aids in administering domains and records for PowerDNS with MySQL.
    * [Poweradmin](http://www.poweradmin.org/) - Friendly web-based DNS administration tool for PowerDNS server.
  * Revision Control
    * [iF.SVNAdmin](http://svnadmin.insanefactory.com/) - WebGUI to manage Subversion repositories and User/Group permissions.
    * [SCM-Manager](https://www.scm-manager.org/) - The easiest way to share and manage your Git, Mercurial and Subversion repositories.
    * [WebSVN](http://www.websvn.info/) - Opensource web subversion repository browser.
  * Virtualization
    * [Feathur](http://feathur.com) - VPS Provisioning and Management Software.
    * [Panamax](http://panamax.io/) - Project that makes deploying complex containerized apps as easy as Drag-and-Drop.
    * [OpenVZ Web Panel](http://owp.softunity.com.ru/) - Web panel to control your OpenVZ servers.
    * [Virtkick](https://www.virtkick.com/) - A simple orchestrator. Manage virtual machines or Docker containers easily.
    * [WebVirtMgr](https://retspen.github.io) - libvirt-based Web interface for managing virtual machines.
  * Server
    * [Ajenti](http://ajenti.org/) - Control panel for Linux and BSD.
    * [Cockpit](http://cockpit-project.org/) - New multi-server web interface for Linux servers written in C.
    * [Virtualmin](http://www.virtualmin.com/) - Control panel for Linux based on webmin.
    * [Webmin](http://www.webmin.com/) - Linux server control panel.

## Deployment Automation
*Tools and scripts to support deployments to your servers.*

  * [Capistrano](http://capistranorb.com/) - Deploy your application to any number of machines simultaneously, in sequence or as a rolling set via SSH (rake based).
  * [Fabric](http://www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks.
  * [Mina](http://nadarei.co/mina/) - Really fast deployer and server automation tool (rake based).
  * [Rocketeer](http://rocketeer.autopergamene.eu/) - PHP task runner and deployment tool.
  * [Vlad the Deployer](https://github.com/seattlerb/vlad) - Deployment automation (rake based).

## Distributed Filesystems
*Network distributed filesystems.*

  * [Ceph](http://ceph.com/) - Distributed object store and file system.
  * [DRBD](http://drbd.linbit.com/) - Distributed Replicated Block Device.
  * [LeoFS](http://leo-project.net) - Unstructured object/data storage and a highly available, distributed, eventually consistent storage system.
  * [GlusterFS](http://www.gluster.org/) - Scale-out network-attached storage file system.
  * [HDFS](http://hadoop.apache.org/) - Distributed, scalable, and portable file-system written in Java for the Hadoop framework.
  * [Lustre](http://lustre.org/) - Parallel distributed file system, generally used for large-scale cluster computing.
  * [MooseFS](http://www.moosefs.org/) - Fault tolerant, network distributed file system.
  * [MogileFS](http://mogilefs.org/) - Application level, network distributed file system.
  * [OpenAFS](http://www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.
  * [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system.
  * [XtreemFS](http://www.xtreemfs.org/) - XtreemFS is a fault-tolerant distributed file system for all storage needs.

## DNS
*DNS servers.*

  * [Bind](https://www.isc.org/downloads/bind/) - The most widely used name server software.
  * [djbdns](http://cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.
  * [Designate](https://wiki.openstack.org/wiki/Designate) - DNS REST API that support several DNS servers as its backend.
  * [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) - A lightweight service providing DNS, DHCP and TFTP services to small-scale networks.
  * [Knot](https://www.knot-dns.cz/) - High performance authoritative-only DNS server.
  * [NSD](http://www.nlnetlabs.nl/projects/nsd/) - Authoritative only, high performance, simple name server.
  * [PowerDNS](https://www.powerdns.com/) - DNS server with a variety of data storage back-ends and load balancing features.
  * [Unbound](http://unbound.net/) - Validating, recursive, and caching DNS resolver.
  * [Yadifa](http://www.yadifa.eu/) - Lightweight authoritative Name Server with DNSSEC capabilities powering the .eu top-level domain.

## Editors
*Open source code editors.*

  * [Atom](https://atom.io/) - A hackable text editor from Github.
  * [Brackets](http://brackets.io/) - Code editor for web designers and front-end developers.
  * [Eclipse](http://www.eclipse.org/) - IDE written in Java with an extensible plug-in system.
  * [Geany](http://www.geany.org/) - GTK2 text editor.
  * [GNU Emacs](http://www.gnu.org/software/emacs/) - An extensible, customizable text editor-and more.
  * [Haroopad](http://pad.haroopress.com/) - Markdown editor with live preview.
  * [ICEcoder](https://icecoder.net/) - Code editor awesomeness, built with common web languages.
  * [jotgit](https://github.com/jdleesmiller/jotgit) - Git-backed real-time collaborative code editing.
  * [KDevelop](https://www.kdevelop.org/) - IDE by the people behind KDE.
  * [Light Table](http://lighttable.com/) - The next generation code editor.
  * [Lime](http://limetext.org/) - Aims to provide an open source solution to Sublime Text
  * [TextMate](https://github.com/textmate/textmate/) - A graphical text editor for OS X.
  * [Vim](http://www.vim.org) - A highly configurable text editor built to enable efficient editing.
  * [Visual Studio Code](https://code.visualstudio.com/) - An open source cross-platform extensible code editor from Microsoft
  * [Nano](http://nano-editor.org) - Easy to use, customizable text editor.

## Identity Management
*LDAP servers and other tools to manage accounts and identities.*

### LDAP
  * [389 Directory Server](http://www.port389.org/) - Developed by Red Hat.
  * [Apache Directory Server](http://directory.apache.org/) - Apache Software Foundation project written in Java.
  * [OpenDJ](http://opendj.forgerock.org/) - Fork of OpenDS.
  * [OpenDS](https://opends.java.net/) - Another directory server written in Java.
  * [OpenLDAP](http://www.OpenLDAP.org/) - Developed by the OpenLDAP Project.

### Tools and web interfaces
  * [Fusion Directory](https://www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP.
  * [FreeIPA](http://www.freeipa.org/) - Security management solution, can manage LDAP, KRB, DNS, sudo, and more
  * [LDAP Account Manager (LAM)](https://www.ldap-account-manager.org/lamcms/) - Web frontend for managing entries (e.g. users, groups, DHCP settings) stored in an LDAP directory.
  * [Samba](https://www.samba.org/) – Active Directory and CIFS protocol implementation.

## IT Asset Management
*IT Assets Management software.*

  * [GLPI](http://www.glpi-project.org/spip.php?lang=en) - Information Resource-Manager with an additional Administration Interface.
  * [OCS Inventory NG](http://www.ocsinventory-ng.org/en/) - Enables users to inventory their IT assets.
  * [OPSI](http://www.opsi.org/en) - Hardware and software inventory, deployment, and patching for Linux and Windows.
  * [RackTables](http://racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration.
  * [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
  * [Snipe IT](https://snipeitapp.com/) - Asset & license management software.

## Log Management
*Log management tools: collect, parse, visualize ...*

  * [Elasticsearch](https://www.elastic.co/) - A Lucene Based Document store mainly used for log indexing, storage and analysis.
  * [Fluentd](http://www.fluentd.org/) - Log Collector and Shipper.
  * [Flume](https://flume.apache.org/) - Distributed log collection and aggregation system.
  * [Graylog2](https://www.graylog.org/) - Pluggable Log and Event Analysis Server with Alerting options.
  * [Heka](http://hekad.readthedocs.org/en/latest/) - Stream processing system which may be used for log aggregation.
  * [Kibana](https://www.elastic.co/products/kibana) - Visualize logs and time-stamped data.
  * [Logstash](https://www.elastic.co/products/logstash) - Tool for managing events and logs.
  * [Octopussy](http://www.octopussy.pm) - Log Management Solution (Visualize / Alert / Report).

## Mail Clients

  * [Claws Mail](http://www.claws-mail.org/) - Old school email client (and news reader), based on GTK+.
  * [Mutt](http://www.mutt.org/) - Small but very powerful text-based mail client.
  * [Thunderbird](https://www.mozilla.org/de/thunderbird/) - Free email application that's easy to set up and customize.
  * [N1](https://nylas.com/N1) - Extensible mail client.


## Mail servers/webmail

See https://github.com/kickball/awesome-selfhosted#email

## Monitoring
*Monitoring software.*

  * [Adagios](http://adagios.org/) - Web based Nagios interface for configuration and monitoring (replacement to the standard interface), and a REST interface, [SourceCode](https://github.com/opinkerfi/adagios), [Documentation](https://github.com/opinkerfi/adagios/wiki))
  * [Alerta](https://github.com/guardian/alerta) - Distributed, scaleable and flexible monitoring system.
  * [Bosun](http://bosun.org/) - Monitoring and alerting system by Stack Exchange ([Source Code](https://github.com/bosun-monitor/bosun), [Documentation](http://bosun.org/quickstart.html)) `MIT` `Go`
  * [Cacti](http://www.cacti.net) - Web-based network monitoring and graphing tool.
  * [Cabot](http://cabotapp.com/) - Monitoring and alerts, similar to PagerDuty.
  * [cadvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers ([Source Code](https://github.com/google/cadvisor)) `Apache` `Go`
  * [check_mk](http://mathias-kettner.com/check_mk.html) - Collection of extensions for Nagios.
  * [Dash](https://github.com/afaqurk/linux-dash) - A low-overhead monitoring web dashboard for a GNU/Linux machine.
  * [Flapjack](http://flapjack.io/) - Monitoring notification routing & event processing system.
  * [Icinga](https://www.icinga.org/) - Nagios fork that has since lapped nagios several times. Comes with the possibility of clustered monitoring - ([Source Code](https://github.com/Icinga)) - `GPLv2`
  * [LibreNMS](http://www.librenms.org) - Fully featured network monitoring system that provides a wealth of features and device support.
  * [Monit](http://mmonit.com/monit/#home) - Small utility for managing and monitoring Unix systems.
  * [Munin](http://munin-monitoring.org/) - Networked resource monitoring tool.
  * [Naemon](http://www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features.
  * [Nagios](https://www.nagios.org/) - Computer system, network and infrastructure monitoring software application.
  * [Node-Bell](https://github.com/eleme/bell.js) - Real-time anomalies detection for periodic time series, metrics monitor.
  * [Observium](http://www.observium.org/) - SNMP monitoring for servers and networking devices. Runs on linux.
  * [OMD](http://omdistro.org/) - The Open Monitoring Distribution.
  * [PhpSysInfo](https://phpsysinfo.github.io/phpsysinfo/) - A customizable PHP script that displays information about your system nicely.
  * [psdash](https://github.com/Jahaja/psdash) - A linux system information web dashboard using psut
ils and flask.
  * [pyDash](https://k3oni.github.io/pydash/) - Small web-based monitoring dashboard for linux.
  * [Riemann](http://riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis.
  * [Sensu](https://sensuapp.org/) - Monitoring framework.
  * [Sentry](https://getsentry.com/) - Application monitoring, event logging and aggregation.
  * [ServerStatus BotoX](https://github.com/BotoX/ServerStatus) - Display and monitor your servers statistics in a beatiful way.
  * [ServerStatus moejda](https://github.com/mojeda/ServerStatus) - Server Status website script, displays uptime (days), free RAM, free HDD
  * [Shinken](http://www.shinken-monitoring.org/) - Another monitoring framework.
  * [Thruk](http://www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, Icinga and Shinken.
  * [Uchiwa](https://uchiwa.io/) - Simple dashboard for sensu.
  * [Xymon](https://www.xymon.com/) - Network monitoring inspired by Big Brother.
  * [Zabbix](http://www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications.
  * [Zenoss](http://community.zenoss.org) - Application, server, and network management platform based on Zope.





## Metric & Metric Collection
*Metric gathering and display software.*

* Collectors only
  * [Diamond](https://github.com/BrightcoveOS/Diamond) - Python based statistic collection daemon.
  * [Collectd](http://collectd.org/) - System statistic collection daemon.
  * [Collectl](http://collectl.sourceforge.net/) - High precision system performance metrics collecting tool.
  * [Statsd](https://github.com/etsy/statsd/) - Application statistic listener.
  * [tcollector](http://opentsdb.net/docs/build/html/user_guide/utilities/tcollector.html) - System statistic collection daemon written in Python for OpenTSDB

* Dashboards
  * [Grafana](http://grafana.org/) - A Graphite & InfluxDB Dashboard and Graph Editor.
  * [Ganglia](http://ganglia.sourceforge.net/) - High performance, scalable RRD based monitoring for grids and/or clusters of servers. Compatible with Graphite using a single collection process.
  * [RRDtool](http://oss.oetiker.ch/rrdtool/) - Industry standard, high performance data logging and graphing system for time series data.
  * [Dashing](http://dashing.io/) - Ruby gem that allows for rapid statistical dashboard development. An all HTML5 approach allows for big screen displays in data centers or conference rooms.
  * [Facette](http://facette.io) - Time series data visualization and graphing software written in Go.
  * [Freeboard](https://github.com/Freeboard/freeboard) - A damn-sexy front-end real-time dashboard for the internet of things. Transforms raw JSON into delicious UI.
  * [Netdata](http://netdata.firehol.org/) - Real-time performance monitoring for Linux systems with plugin support.

* Storage
  * [OpenTSDB](http://opentsdb.net/) - Store and server massive amounts of time series data without losing granularity.
  * [KairosDB](https://github.com/kairosdb/kairosdb) - Fast distributed scalable time series database, fork of OpenTSDB 1.x.
  * [InfluxDB](https://influxdb.com/) - Distributed time series database with no external dependencies.

* Packages
  * [Prometheus](http://prometheus.io/) - Service monitoring system and time series database.
  * [Packetbeat](https://www.elastic.co/products/beats) - Captures network traffic and displays it in a custom Kibana dashboard for easy viewing.
  * [Graphite](http://graphite.readthedocs.org/en/latest/) - Scalable graphing server.

## Network Configuration Management
*Network configuration management tools.*

  * [GestióIP](http://www.gestioip.net/) - An automated web based IPv4/IPv6 IP Address Management tool.
  * [Oxidized](https://github.com/ytti/oxidized) - A modern take on network device configuration monitoring with web interface and GIT storage.
  * [RANCID](http://www.shrubbery.net/rancid/) - Monitors network device's configuration and maintain history of changes.
  * [rConfig](http://www.rconfig.com/) - Another network device configuration management tool.
  * [trigger](https://github.com/trigger/trigger) - Robust network automation toolkit written in Python.

## Newsletters
*Newsletter software.*

  * [DadaMail](http://dadamailproject.com/) - Mailing List Manager, written in Perl.
  * [phpList](https://www.phplist.com/) - Newsletter manager written in PHP.
  * [LibreMailer](https://github.com/averna-syd/LibreMailer) - Libre Mailer is a modest and simple web based email marketing application.
  * [Lewsnetter](https://github.com/bborn/lewsnetter) - E-mail marketing application (create and send e-mail newsletter via SES). Includes subscription management, delivery, bounce and complaint notification, templates, and some stats.

## NoSQL
*NoSQL databases.*

* Column-Family
  * [Apache HBase](http://hbase.apache.org/) - Hadoop database, a distributed, big data store.
  * [Cassandra](http://cassandra.apache.org/) - Distributed DBMS designed to handle large amounts of data across many servers.
  * [Hypertable](http://hypertable.org/) - C++ based BigTable-like DBMS, communicates through Thrift and runs either as stand-alone or on distributed FS such as Hadoop.
* Document Store
  * [CouchDB](http://couchdb.apache.org/) - Ease of use, with multi-master replication document-oriented database system.
  * [ElasticSearch](https://www.elastic.co/) - Java based database, popular with log aggregation, and email archiving projects.
  * [MongoDB](https://www.mongodb.org/) - Another document-oriented database system.
  * [RavenDB](http://ravendb.net/) - Document based database with ACID/Transactional features.
  * [RethinkDB](http://www.rethinkdb.com/) - Distributed document store database, focuses on JSON.
* Graph
  * [FlockDB](https://github.com/twitter/flockdb) - Twitter's distributed, fault-tolerant graph database.
  * [Neo4j](http://neo4j.com/) - Graph database.
* Key-Value
  * [LevelDB](https://github.com/google/leveldb) - Google's high performance key/value database.
  * [Redis](http://redis.io/) - Networked, in-memory, key-value data store with optional durability.
  * [Riak](http://basho.com/riak/) - Another fault-tolerant key-value NoSQL database.

Comparison of NoSQL servers: http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

## Packaging

  * [fpm](https://github.com/jordansissel/fpm) - Versatile multi format package creator.
  * [omnibus-ruby](https://github.com/chef/omnibus) - Full stack, cross distro packaging software (Ruby).
  * [packman](http://packman.readthedocs.org) - Full stack, cross distro packaging software (Python).
  * [tito](https://github.com/dgoodwin/tito) - Builds RPMs for git-based projects.

## Project Management
*Web-based project management and bug tracking systems*: see https://github.com/Kickball/awesome-selfhosted#project-management

## Queuing

  * [ActiveMQ](https://activemq.apache.org/) - Java message broker.
  * [BeanstalkD](http://kr.github.io/beanstalkd/) - A simple, fast work queue.
  * [Gearman](http://gearman.org/) - Fast multi-language queuing/job processing platform.
  * [Kafka](http://kafka.apache.org) - Extremely high performance publish/subscribe message system.
  * [NSQ](http://nsq.io/) - A realtime distributed messaging platform.
  * [RabbitMQ](http://www.rabbitmq.com/) - Robust, fully featured, cross distro queuing system.
  * [ZeroMQ](http://zeromq.org/) - Lightweight queuing system.

## RDBMS
*Relational DBMS.*

  * [Firebird](http://www.firebirdsql.org/) - True universal database.
  * [Galera](http://galeracluster.com/) - Galera Cluster for MySQL is an easy-to-use high-availability solution with high system up-time, no data loss, and scalability for future growth.
  * [MariaDB](https://mariadb.org/) - Community-developed fork of the MySQL.
    * [adminer](https://www.adminer.org/) -  Database management in a single PHP file ([Source code](https://github.com/vrana/adminer))
  * [Percona Server](https://www.percona.com/software) - Enhanced, drop-in MySQL replacement.
  * [PostgreSQL](http://www.postgresql.org/) - Object-relational database management system (ORDBMS).
  * [PostgreSQL-XL](http://www.postgres-xl.org/) - Scalable PostgreSQL-based database cluster.
  * [SQLite](http://sqlite.org/) - Library that implements a self-contained, serverless, zero-configuration, transactional SQL DBS.

## Remote Management

* [Tiger VNC](http://tigervnc.org/) - TigerVNC is a high-performance, platform-neutral implementation of VNC (Virtual Network Computing), a client/server application that allows users to launch and interact with graphical applications on remote machines.
* [Remmina](http://www.remmina.org/wp/) - A Feature rich remote desktop application for linux  and other unixes.
* [X2go](http://wiki.x2go.org/doku.php) - X2Go is an open source remote desktop software for Linux that uses the NX technology protocol. 

## Security
*Security tools.*

  * [Blackbox](https://github.com/StackExchange/blackbox) - Safely store secrets in Git/Mercurial. Provides tooling to automatically encrypt secrets like passwords.
  * [Bro](https://www.bro.org/) - Bro is a powerful framework for network analysis and security monitoring.
  * [Denyhosts](http://denyhosts.sourceforge.net/) - Thwart SSH dictionary based attacks and brute force attacks.
  * [Fail2Ban](http://www.fail2ban.org/wiki/index.php/Main_Page) - Scans log files and takes action on IPs that show malicious behavior.
  * [FIR](https://github.com/certsocietegenerale/FIR) - Fast Incident Response, a cybersecurity incident management platform.
  * [fwknop](https://www.cipherdyne.org/fwknop/) - Protects ports via Single Packet Authorization in your firewall.
  * [Glastopf](http://glastopf.org/) - A low-interaction web application honeypot to emulate vulnerabilities and gather attack data.
  * [Kippo](https://github.com/desaster/kippo) - A medium-interaction SSH honeypot, mostly used as a standalone SSH daemon with a configurable Filesystem sandbox.
  * [Linux Malware Detect](https://www.rfxn.com/projects/linux-malware-detect/) - A malware scanner for Linux designed around the threats faced in shared hosted environments.
  * [Nmap](https://nmap.org) - Nmap is a free and open source utility for network discovery and security auditing.
  * [OSSEC](http://www.ossec.net/) - OSSEC is a HIDS that performs log analysis, FIM, rootkit detection, and much more.
  * [OSQuery](https://osquery.io/) - Query your servers status and info using a SQL like interface.
  * [pfSense](https://www.pfsense.org/) - Firewall and Router FreeBSD distribution.
  * [Snort](https://www.snort.org/) - Network intrusion prevention system (NIPS) and network intrusion detection system (NIDS).
  * [SpamAssassin](https://spamassassin.apache.org/) - A powerful and popular email spam filter employing a variety of detection technique.
  * [SSHGuard](http://www.sshguard.net/) - A software to protect services in addition to SSH, written in C

## Service Discovery

  * [Consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
  * [Doozerd](https://github.com/ha/doozerd) - Doozer is a highly-available, completely consistent store for small amounts of extremely important data.
  * [etcd](https://github.com/coreos/etcd) - distributed K/V-Store, authenticating via SSL PKI and a REST HTTP Api for shared configuration and service discovery.
  * [ZooKeeper](http://zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

## Software Containers
*Operating system–level virtualization.*

  * [Docker](http://www.docker.com/) - Platform for developers and sysadmins to build, ship, and run distributed applications.
  * [LXC](https://linuxcontainers.org/lxc/) - Userspace interface for the Linux kernel containment features.
  * [OpenVZ](http://openvz.org) - Container-based virtualization for Linux.

## SSH
*SSH tools.*

  * [Advanced SSH config](https://pypi.python.org/pypi/advanced-ssh-config/) - Enhances ssh_config file capabilities, completely transparent.
  * [autossh](http://www.harding.motd.ca/autossh/) - Automatically respawn ssh session after network interruption.
  * [Cluster SSH](http://sourceforge.net/projects/clusterssh/) - Controls a number of xterm windows via a single graphical console.
  * [DSH](https://www.netfort.gr.jp/~dancer/software/dsh.html.en) - Dancer's shell / distributed shell - Wrapper for executing multiple remote shell commands from one command line.
  * [Mosh](https://mosh.mit.edu/) - The mobile shell.
  * [parallel-ssh](http://code.google.com/p/parallel-ssh/) - Provides parallel versions of OpenSSH and related tools.
  * [ssh-cert-authority](https://github.com/cloudtools/ssh-cert-authority) - A democratic SSH certificate authority.
  * [ssh-ca](https://github.com/cloudtools/ssh-ca/) - Allows giving ssh access to servers without putting a users key on the server, as well as expiring access.
  * [SSH Power Tool](http://code.google.com/p/sshpt/) - Execute commands and upload files to many servers simultaneously without using pre-shared keys.
  * [sshrc](https://github.com/Russell91/sshrc) - sources ~/.sshrc on your local computer after logging in remotely.
  * [stormssh](http://stormssh.readthedocs.org) - A command line tool to manage SSH connections.

## Statistics
*Analytics software. See https://github.com/Kickball/awesome-selfhosted#analytics*

## Status Pages

  * [Cachet](https://cachethq.io) - Status page system written in PHP.
  * [Stashboard](http://www.stashboard.org) - Status page for cloud services and APIs.
  * [System Status Dashboard (SSD)](http://www.system-status-dashboard.com/) - Overview about an organization's infrastructure health status.
  * [Staytus](http://staytus.co/) - Staytus is a complete solution for publishing the latest information about any issues with your web applications, networks or services.

## Ticketing systems
*Web-based ticketing system. See https://github.com/Kickball/awesome-selfhosted#ticketing*

## Troubleshooting
*Troubleshooting Tools.*

  + [grml](https://grml.org) – bootable Debian Live CD with powerful CLI tools.
  * [mitmproxy](http://mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems.
  * [perf-tools](https://github.com/brendangregg/perf-tools) - Performance analysis tools based on Linux perf_events (aka perf) and ftrace.
  * [Sysdig](http://www.sysdig.org/) - Capture system state and activity from a running Linux instance, then save, filter and analyze.
  * [Wireshark](https://www.wireshark.org/) - The world's foremost network protocol analyzer.

## Version control
*Software versioning and revision control.*

  * [Fossil](http://www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.
  * [Git](http://git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed.
  * [GNU Bazaar](http://bazaar.canonical.com/) - Distributed revision control system sponsored by Canonical.
  * [Mercurial](https://www.mercurial-scm.org/) - Another distributed revision control.
  * [Subversion](http://subversion.apache.org/) - Client-server revision control system.

## Virtualization
*Virtualization software.*

  * [Archipel](http://archipelproject.org/) - XMPP based virtualization management platform.
  * [ConVirt](http://www.convirture.com/products_opensource.php) - Provides the core functionality for centrally managing your KVM or Xen virtualized environment.
  * [Ganeti](https://code.google.com/p/ganeti/) - Cluster virtual server management software tool built on top of KVM and Xen.
  * [KVM](http://www.linux-kvm.org) - Linux kernel virtualization infrastructure.
  * [OpenNebula](http://opennebula.org/) - Flexible enterprise cloud made simple.
  * [OpenNode](http://opennodecloud.com) - Builds open-source infrastructure management software and implements cloud systems.
  * [oVirt](http://www.ovirt.org/) - Manages virtual machines, storage and virtual networks.
  * [Packer](https://www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration.
  * [Proxmox VE](https://www.proxmox.com/proxmox-ve) - Virtualization management solution.
  * [QEMU](http://www.qemu.org/) - QEMU is a generic machine emulator and virtualizer.
  * [Vagrant](https://www.vagrantup.com/) - Tool for building complete development environments.
  * [VirtualBox](https://www.virtualbox.org/) - Virtualization product from Oracle Corporation.
  * [Xen](http://www.xenproject.org/) - Virtual machine monitor for 32/64 bit Intel / AMD (IA 64) and PowerPC 970 architectures.

## VPN
*VPN software.*

  * [OpenVPN](https://community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange.
  * [Pritunl](http://pritunl.com/) - OpenVPN based solution. Easy to set up.
  * [SoftEther](https://www.softether.org/) - Multi-protocol software VPN with advanced features
  * [sshuttle](https://github.com/apenwarr/sshuttle) - Poor man's VPN.
  * [strongSwan](https://www.strongswan.org/) - Complete IPsec implementation for Linux.
  * [tinc](http://www.tinc-vpn.org/) - Distributed p2p VPN.

## XMPP

_See https://github.com/Kickball/awesome-selfhosted#xmpp_

## Web
*Web servers.*

  * [Apache](http://httpd.apache.org/) - Most popular web server.
  * [Cherokee](http://cherokee-project.com/) - Lightweight, high-performance web server/reverse proxy.
  * [Lighttpd](http://www.lighttpd.net/) - Web server more optimized for speed-critical environments.
  * [Nginx](http://nginx.org/) - Reverse proxy, load balancer, HTTP cache, and web server.
  * [uWSGI](https://github.com/unbit/uwsgi/) - The uWSGI project aims at developing a full stack for building hosting services.

*Web Performance*

  * [HAProxy](http://www.haproxy.org/) - Software based load Balancing, SSL offloading and performance optimization, compression, and general web routing.
  * [Varnish](https://www.varnish-cache.org/) - HTTP based web application accelerator focusing on optimizing caching and compression.


## Wiki Software

See https://github.com/Kickball/awesome-selfhosted#wikis

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

  * [Code as Craft](https://codeascraft.com/) - Etsy's Ops blog, lots of technical posts.
  * [DevOpsGuys](http://blog.devopsguys.com/) - Devops consultants who blog about operations.
  * [Rackspace Developers](https://developer.rackspace.com/blog/) - Slightly biased blog with lots of Devops Topics.

## Books
*Sysadmin related books.*

  * [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
  * [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](http://itrevolution.com/books/phoenix-project-devops-book/) - How DevOps techniques can fix the problems that happen in IT organizations.
  * [The Practice of System and Network Administration](http://everythingsysadmin.com/books.html) - The first and second editions describes the best practices of system and network administration, independent of specific platforms or technologies.
  * [The Visible Ops Handbook: Implementing ITIL in 4 Practical and Auditable Steps](http://www.itpi.org/the-visible-ops-handbook-review.html) - Is a methodology designed to jumpstart implementation of controls and process improvement.
  * [UNIX and Linux System Administration Handbook](http://www.admin.com/) - Approaches system administration from a practical perspective.

## Communities / Forums
*For the social people.*

  * [ArsTechnica OpenForum](http://arstechnica.com/civis/) – IT Forum which is attached to a large news site.
  * [Reddit](https://www.reddit.com) - Really, really large bulletin board system.
    * [/r/Linux](https://www.reddit.com/r/linux) - News and information about Linux.
    * [/r/LinuxQuestions](https://www.reddit.com/r/linuxquestions)
    * [/r/SysAdmin](https://www.reddit.com/r/sysadmin/)
  * [Spiceworks Community](https://community.spiceworks.com/start) – General enterprise IT news and small articles.
  * [StackExchange Network](https://stackexchange.com/sites#technology) – Q&A communities.
    * [Server Fault](https://serverfault.com/) – StackExchange community for system and network administrators.

## Newsletters

  * [Servers for Hackers](https://serversforhackers.com/) - Newsletter for programmers who find themselves needing to know their way around a server.
  * [Web Operations Weekly](http://webopsweekly.com/) - A weekly newsletter on Web operations, infrastructure, performance, and tooling, from the browser down to the metal.

## Repositories
*Software package repositories.*

  * [AlternativeTo](http://alternativeto.net) - Find alternatives to software you know and discover new software.

### Debian-based distributions
  * [Dotdeb](https://www.dotdeb.org/) - Repository with LAMP updated packages for Debian.

### RPM-based distributions
  * [ElRepo](http://elrepo.org/tiki/tiki-index.php) - Community Repo for Enterprise Linux (RHEL, CentOS, etc).
  * [EPEL](https://fedoraproject.org/wiki/EPEL) - Repository for RHEL and compatibles (CentOS, Scientific Linux).
  * [IUS](https://ius.io/) - Community project that provides RPM packages for newer versions of select software for Enterprise Linux distributions.
  * [Remi](http://rpms.famillecollet.com/) - Repository with LAMP updated packages for RHEL/Centos/Fedora.
  * [Software Collections](https://www.softwarecollections.org) - Community Release of [Red Hat Software Collections](https://access.redhat.com/documentation/en/red-hat-software-collections/). Provides updated packages of Ruby, Python, etc. for CentOS/Scientific Linux 6.x.

## Websites
*Useful sysadmin related websites.*

  * [Ops School](http://www.opsschool.org) - Comprehensive program that will help you learn to be an operations engineer.
  * [Digital Ocean Tutorials](https://www.digitalocean.com/community/tutorials) - A surprisingly vast resource for getting the basics of certain applications, tools, or even systems administration topics.

## Wikis
*Useful Wikis for Sysadmins – not to be confused with Wiki software.*

  * [ArchWiki](https://wiki.archlinux.org/) – Arch Linux Wiki which has really nice written articles valid for other distros.
  * [Gentoo Wiki](https://wiki.gentoo.org/) - Gentoo Linux Wiki with a lot in-detail description of Linux components.

## License

![cc license](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/) license.
