---
permalink: versed-in-virtual-desktop-racksapces-knowledge-of-hosted-virtual-desktop/
audit_date:
title: "Versed in Virtual Desktop: Rackspace's Knowledge of Hosted Virtual Desktop"
type: whitepaper
created_date: '2012-07-23'
created_by: Rackspace Support
last_modified_date: '2017-03-16'
last_modified_by: Cat Lookabaugh
product: Professional Services
---

***By:***
***John Engates, Rackspace CTO***
***Robbie Wright, Rackspace Enterprise Marketing Sr. Manager***
***Christopher Johnson, Rackspace Product Engineer***

### Abstract

Distributed computing has been pervasive in it organizations for nearly
two decades, but the tables are beginning to turn. Hosted Virtual
desktop, also known as Virtual desktop infrastructure (Vdi), is one of
the fastest growing trends in it today, partially because of the benefi
ts it offers in management, access, performance and security. This
whitepaper discusses Rackspace’s experience in quick deployment and
hosting of virtual desktop environments.

### Introduction - Why use Hosted Virtual Desktop?

IT organizations both large and small have begun to push back against
the complexities and pressures caused by the traditional distributed
computing model in practice in most environments today. Many see the
transition to [Hosted Virtual
Desktop](http://www.rackspace.com/hostedvirtualdesktop/) as a solution
to several of the problems in their desktop computing environment.
Gartner defines Hosted Virtual desktop as “a technology providing
mechanisms for centralizing a thick-client desktop PC without the need
to re-engineer applications for centralized execution.”

According to a survey by Gartner, the top driver for the migration to a
virtual desktop environment is a desire for improvement in business
agility. When deployed correctly, desktop virtualization provides
greater flexibility in deployment, allows for simplified image
management, facilitates greater systems management capabilities and
promotes mobility – without compromising security. Additionally, hosted
virtual desktop solutions can better enable compliance with both
government regulations like Sarbanes-Oxley and HIPAA as well as software
licensing agreements.

While this technology offers some excellent benefits, careful
consideration of the solution is imperative for successful
implementation. Significant expertise is necessary to understand all of
the variables that might come into play in an organization.

### Hosted virtual desktop - Technical considerations

Several components are required to effectively implement a Hosted
Virtual Desktop solution:

1) Virtualization software to serve as a host for the individual
desktops

2) Brokering or session management software to facilitate the
connection between users and their desktops

3) Management tools for the overall virtual desktop environment

4) P hysical infrastructure to facilitate the required service level
agreement (SLA) and performance of the solution

5) A hosting strategy to determine what hosting solution provides the
greatest value to the organization

#### Consideration 1: Virtualization Platform

Multiple virtualization platforms can be used for desktop
virtualization including Microsoft<sup>&reg;</sup> Hyper-V<sup>7trade;</sup>,
VMware<sup>&reg;</sup> ESX<sup>&trade;</sup>, Citrix<sup>&reg;</sup>
XenServer<sup>&trade;</sup> and others. The hypervisor does not significantly
impact end-user experience, and thus, should be selected based on the needs and
existing expertise of the IT department. With a growing landscape of
hypervisor-agnostic orchestration and management tools, the implications
of choosing the “wrong” hypervisor are becoming less pronounced, but
this remains an important decision when considering how an environment
will scale. For the purpose of this paper, we will focus on Citrix
XenServer.

XenServer is an enterprise-class server virtualization platform built
on the open-source Xen hypervisor for the management of Windows<sup>&reg;</sup>
and Linux virtual machines. Rackspace has chosen XenServer for the Hosted
Virtual Desktop reference architectures included later in this
whitepaper, in part, because of Citrix’s deep involvement with the
open-source community. Citrix has made great strides toward integration
of Xen technology with the open-source OpenStack cloud orchestration and
management platform that Rackspace believes will result in significant
efficiencies in the virtual desktop market in the future.

#### Consideration 2: Brokering/Session Management Software

Brokering/session management software provides the infrastructure
necessary to facilitate the user sessions in a Hosted Virtual Desktop
environment. there are several building blocks of this component:

1) The **Web Interface** uses a Java-based front end to provide the
user interface. High availability is usually built into this layer
through the use of redundant web interface servers, providing end users
seamless access to their virtual desktop, even in the event of a web
interface hardware failure.

2) The **Desktop Delivery Controller** is installed on servers in the
data center and is responsible for user authentication, management of
the assembly of users’ virtual desktop environments and brokering
connections between users and their virtual desktops. It controls the
state of the desktops, starting and stopping them based on demand and
administrative configuration. It also includes profile management, in
some editions, to manage user personalization settings in virtualized or
physical windows environments.

3) **Citrix Provisioning Services** creates and provisions virtual
desktops from a single desktop image on demand, optimizing storage
utilization and providing a pristine virtual desktop to each user every
time they log on. Desktop provisioning also simplifies desktop images,
provides the best flexibility and offers fewer points of desktop management for
both applications and desktops.

Possibly the most difficult part of architecting a Hosted Virtual
Desktop environment is understanding user requirements.

To assist in this, Rackspace has identified four common use profiles:

<img src="{% asset_path professional-services/versed-in-virtual-desktop-racksapces-knowledge-of-hosted-virtual-desktop/taskuser_HVD_whitepaper.png %}" />

**Task User** – PC users who perform well-defi ned tasks, use few
applications and have limited requirements from their PCs

<img src="{% asset_path professional-services/versed-in-virtual-desktop-racksapces-knowledge-of-hosted-virtual-desktop/knowledgeuser_HVD_whitepaper.png %}" />

**Knowledge User** – Typically attend meetings, visit branch offices, work from
home and even coffee shops; these “anywhere workers” expect access to all of the
same applications and data wherever they are

<img src="{% asset_path professional-services/versed-in-virtual-desktop-racksapces-knowledge-of-hosted-virtual-desktop/poweruser_hvd_whitepaper.png.png %}" />

**Power User** – PC users who run resource-intensive applications

<img src="{% asset_path professional-services/versed-in-virtual-desktop-racksapces-knowledge-of-hosted-virtual-desktop/officeuser_hvd_whitepaper.png %}" />

**Office User** – PC users who run primarily an office suite of productivity
applications

Classifying users into one of these profiles can provide organizations
a great head start in sizing their Hosted Virtual desktop solution. Once
users are classified, the it organization can rightsize the resources
provisioned for virtual desktops in each profile. This should primarily
involve determining, for each virtual desktop, the number of virtual
CPUs, amount of memory, storage space, input/output operations per
second (iops) and bandwidth required to perform optimally.

Citrix Xendesktop<sup>&trade;</sup> is a lightweight, universal virtual desktop
client that facilitates each of these user profi les. It provides a rich,
high-defi nition desktop with full streaming audio and video. Each
profile can be delivered as a streamed desktop or a persistent desktop.
Streamed desktops are built on the fly and torn down at the end of each
session, and therefore do not retain any applications not built into the
streamed image between sessions. In contrast, persistent desktops run
like regular virtual machines and remain in existence after the end of
the session. Persistent desktops are typically assigned to a single
person and retain any added applications from session to session.

Citrix Xenapp<sup>&trade;</sup> provides a framework for streamlining
application delivery by streaming windows applications through a remote desktop
session. It can be embedded in Xendesktop or run outside of the desktop
itself. One of the major benefits of delivering applications in this
fashion is ease of deployment. Xenapp allows it organizations to deploy
a new application, or patch or upgrade an existing application just once
for the entire organization, instead of once for every desktop or
virtual machine in an environment.

#### Consideration 3: Systems Management

Systems management is another key consideration in a Hosted Virtual
Desktop environment. As with any virtualized environment, a number of
services are required for proper operation and management including an
Active Directory domain, a domain controller, a Microsoft SQL database,
a Dynamic Host Configuration Protocol (DHCP) server, a Domain Name
Services (DNS) server, a Network Time Protocol (NTP) server and several
administration tools. As much has been written on these topics in other
virtualization documentation, we will focus briefly on the systems
management tools specific to a Hosted Virtual Desktop environment,
and specifically those tools in the enclosed reference architectures.

Citrix XenCenter<sup>&trade;</sup> provides the management layer for all Xen
servers.This tool manages the virtualization layer of the server
hardware and handles tasks like live migrations and performance
monitoring and hardware utilization within the virtualized
environment.

Desktop Director<sup>&trade;</sup> is the web-based operations console for
XenDesktop. It is designed to simplify the provisioning and delivery of virtual
desktops that reside in an environment as well as facilitating all of
the day-to-day management functions from a single pane of glass.

Finally, Citrix EdgeSight<sup>&trade;</sup> provides a comprehensive agent-based
monitoring system used to track system resources of all the components
of the Hosted Virtual Desktop solution. It supports alarm thresholds,
event response and historical reporting.

#### Consideration 4: Physical Infrastructure

Choosing the correct physical infrastructure to support a Hosted
Virtual Desktop environment is critical to its acceptance and long-term
viability in an organization. Undersizing components that compromise the
availability or the performance of a virtualized desktop will lead to
poor user experience and lost productivity. Therefore, it is necessary
to scope the appropriate computing resources (processor, memory,
networking, storage, etc.) to support the environment.

Advances in virtualization technology have made server hardware
practically a commodity. For these reference architectures, Rackspace
chose Dell<sup>&trade;</sup> R810 servers because of the availability of
Intel<sup>&reg;</sup> Octa-Core Xeon<sup>&reg;</sup> processors that enable
optimal desktop density. Best practices recommend five virtual desktops per CPU
core, in this case allowing 100-150 desktops per physical server.

Networking is another important consideration as part of physical
infrastructure for a Hosted Virtual Desktop solution. If there is a
single point of failure in the network, users cannot access their
virtual desktops, resulting in lost productivity and dissatisfied users.
Therefore, high availability (n+1) and the best possible service level
agreements are required in the networking layer at the firewall, network
load balancer and switching levels. In addition, better performance can
be expected when Hosted Virtual Desktop is deployed closer in proximity
to other hosted applications. With a growing number of applications
being served in the cloud or through a Software-as-a-Service model, the
logical deployment location to reduce network latency is often with a
cloud provider. We will examine this in more detail shortly.

Other networking considerations should be around WAN optimization and
secure access to virtual infrastructure. Citrix’s NetScaler<sup>&trade;</sup>
can handle both of these tasks by providing virtual private network (VPN) access
for users and using advanced algorithms for WAN optimization.
Alternatively, the same effect could be accomplished by using an F5<sup>&reg;</sup>
BIG-IP<sup>&reg;</sup> device that provides SSL VPN as well as advanced load
balancing functionality.

In this case, a separate WAN optimization solution like those from
Riverbed<sup>&reg;</sup> or Brocade<sup>&reg;</sup>, if desired, would be
necessary. However, one of the simplest ways to accelerate performance by
reducing latency is using Akamai<sup>&reg;</sup> IP Application Accelerator.
This technology helps to optimize the paths that data takes across the Internet
based on a number of factors, often routing around congestion or outages that
would reduce performance. It also can put end users’ data physically closer to
them by leveraging Akamai’s vast Content Delivery Network (CDN).

Storage environments must be architected to accommodate frequently
recurring events with high input/output (I/O) demands, known as “I/O
storms.” I/O storms can include events like logon, logoff, boot,
shutdown, antivirus scans and application patches. Typically, a
virtualized desktop will require 14-24 IOPS under normal workload, but
during these events, these demands can increase fivefold. Storage
requirements for the average virtual desktop usually include 40-45
gigabytes (GB) of vDisk storage (for the desktop itself), 20-40 GB of
user and profile storage, and 5 GB of write-cache storage. If the
storage environment is not scoped and implemented correctly, users will
experience greatly degraded performance during these periods.

Rackspace and NetApp<sup>&reg;</sup> have partnered to design a storage solution
suited to handle I/O storms while avoiding costly over-provisioning of
storage resources. Flash cache cards in the NetApp array help achieve
the IOPS needed to support an enterprise Hosted Virtual Desktop
solution. Rackspace also uses NetApp’s primary storage deduplication
technology, allowing organizations to avoid storing duplicate data like
desktop images, significantly reducing storage requirements. Other
NetApp technologies in use in the Rackspace solution include Link
Aggregation Control Protocol (LACP) channel bonding (to achieve 2 GB
links) and RAID-DP for economical fault tolerance.

#### Consideration 5: Hosting

Finally, organizations must determine the best hosting solution for
their virtual desktop solution: whether to host internally or
externally. While many host this application internally in their own
data centers, a growing number are choosing external managed hosting
solutions in order to reduce the IT overhead required to manage a
virtual desktop environment and to leverage benefits in flexibility and
performance that may be realized in an external data center. Security
concerns surrounding external hosting of a virtual desktop solution can
be mitigated with a correctly architected environment.

Typically, a hosted environment provides for faster deployment, cutting
months or even years off of the deployment time of internal IT and/or a
large IT outsourcing firm. If hosting at an external data center, the
primary consideration should be whether the organization desires to
manage the physical equipment (pure colocation) or if they prefer to
have someone else take care of physical layer issues (managed
colocation).

> ***Experience in Action: Deploying Hosted Virtual Desktop for a Multi-billion Dollar Manufacturer***

> **A large consumer packaged goods manufacturer had been outsourcing
> with a large IT firm to implement a virtual desktop solution. However,
> after 18 months of continuous work, their IT firm was unable to deploy a
> production-ready solution. Citrix recommended that this company contact
> Rackspace as an alternative to accelerate the solution. Rackspace worked
> with a host of companies to architect and deploy a solution to full
> production within just two months.**


Rackspace provides infrastructure management services up to the
physical device level for Hosted Virtual Desktop solutions, allowing its
customers to avoid time-consuming trips to a remote data center to deal
with physical layer issues like hardware failures. Rackspace works with
its customers to enlist channel partners to provide broader services
like end user help desk and application support.

Because of the growing number of web-based applications, there is often
a performance advantage of deploying in an external data center because
of decreased latency between these applications and Hosted Virtual
Desktop environments. Rackspace even has the capability, with its
Rackconnect<sup>&trade;</sup> hybrid computing solution, to provide seamless,
direct connections between dedicated Hosted Virtual desktop infrastructure and
applications running in Rackspace’s public cloud, providing its
customers with the optimal mix of platforms to enable their client
computing environment.

Rackspace provides solutions with a 100% network availability service
level agreement (SLA). To enable networking high availability,
Rackspace provides options for redundant firewalls, high availability
load balancers and redundant switching.

To enable disaster recovery, hosting providers can provide geographic
redundancy more easily than in-house solutions. For example, because of
Rackspace’s globally distributed data centers, it can provide a primary
Hosted Virtual desktop solution in one data center with data replication
to other sites all over the world without a signifi cant capital
investment. This global footprint can also be leveraged to place Hosted
Virtual Desktop resources physically closer to end users, reducing
latency.

### Rackspace's additional expertise

Rackspace has extensive experience and expertise in dedicated and cloud
hosting environments. Rackspace enterprise customers will have the
advantage of an implementation team that is engaged before contract
signing to assist in providing a seamless transition from sales into
support. this team deploys the customer’s environment, staying with them
through deployment and transitioning to the permanent account team. They
act as the single point of contact for any customer need during an
implementation process. these and other aspects of Rackspace’s solution
can greatly expedite deployment of a Hosted Virtual desktop solution.

Further, Rackspace has teamed with top companies across the industry to
deliver a comprehensive Hosted Virtual desktop solution and can help its
customers leverage the right provider to help customize a solution for
their organization.

Leveraging its experience in deploying Hosted Virtual desktop solutions
with customers of all sizes, Rackspace developed the following reference
architectures to help educate its customers on best practices. the
larger of these two architectures is built for modular scalability, and
has been deployed for one Rackspace customer today in a Hosted Virtual
desktop environment with over 50,000 users.

### Summary

Hosted Virtual desktop solutions offer worlds of new flexibility and
agility to enterprises large and small. Rackspace has built
relationships with best-in-class providers to create virtual desktop
solutions for some of the world’s largest companies. Because of their
level of sophistication, Virtual desktop environments require advanced
expertise in deployment and management. Rackspace can help organizations
achieve this while expediting production readiness.


