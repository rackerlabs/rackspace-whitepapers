---
permalink: nervous-about-the-cloud-go-hybrid-instead/
audit_date:
title: Nervous About Cloud? Go Hybrid Instead.
type: whitepaper
created_date: '2012-10-30'
created_by: Rackspace Support
last_modified_date: '2017-03-16'
last_modified_by: Cat Lookabaugh
product: Cloud Overview
product_url: cloud-overview
---

### Introduction To Hybrid Hosting

By Paul Croteau, Enterprise Solutions Evangelist, Rackspace<sup>&reg;</sup> Hosting

### 1. Executive Summary

Hybrid hosting refers to the combination of customer-dedicated servers
and public cloud infrastructure used in parallel to meet a hosting
objective. Hybrid hosting can provide the security features,
performance, and customization of dedicated hardware along with the cost
savings, utility, and bursting aspects that cloud technology offers. How
best to leverage this technology combination will be dictated by your
business rules, industry/regulatory requirements, application
capabilities, and budget, among other things. This paper offers an
introduction to the concept of hybrid hosting, provides illustrative use
case examples, and ends with five questions to consider before making
technical changes.

### 2. What Is Hybrid Hosting?

Various marketing campaigns have helped increase public awareness of the
cloud, but they have also inadvertently generated confusion and
misperceptions about what the cloud is, and isn’t. The following
definitions should provide clarity for the purpose of this paper:

-   **Public Cloud Hosting:** The hosting of content that resides on a
shared/multi- tenant infrastructure that customers purchase as a service.
Customers may have administrative access to complete virtual private servers
(also referred to as virtual machines or VMs), or they may control content
through a portal and not have actual access to the server operating system.
Billing is usually a utility-based, month-to-month commitment with no long-term
contractual obligation.

-   **Dedicated Hosting:** Content is hosted on physical servers that are
dedicated to the customer. This can range from pure colocation — where customers
procure and install the equipment, and support the content — to a fully Managed
Operations service, where customers lease the equipment and own the content
responsibilities, and the service provider installs and supports the network and
server hardware. Pricing is usually based on the number of devices and other
technologies that are deployed. Contract terms can range from 12 months to 36
months or longer. Customers pay for the hardware that is deployed regardless of
how much it is used.

-   **Private Cloud Hosting:** Content hosted on virtualized servers that run on
customer-dedicated hypervisors instead of multi-tenant devices. Private Cloud is
also referred to as “Dedicated Virtualization Hosting” (VMware, Hyper-V, Xen,
etc.).

-   **Hybrid Hosting:** The combination of dedicated and/or private cloud
hosting with public cloud hosting.

### 3. Why Consider A Hybrid Solution?

A common perception about virtualization is that moving from physical to
virtual servers can lower your hosting costs, and in many cases this is
correct. There also exists the perception that cloud hosting is still an
emerging technology that lacks proper security features and therefore is
not ready for mission-critical applications. In many cases, this is also
correct. But, when properly planned, a hybrid configuration can help
lower your costs without increasing your security risk or decreasing
application performance.

By working with a provider that offers both cloud and dedicated hosting
— and the ability to securely connect the two — you can experience the
“cure for the common cloud.” After conducting a proper internal
analysis, you should be able to identify which of your servers can be
virtualized, which need to remain physical, and which can be
consolidated or eliminated.

### 4. Reselling Hybrid Services

Consider the real-world case of an advertising agency taking advantage
of a hybrid solution. Before coming to Rackspace, this company supported
internal hardware and outsourced parts of their customer-facing
infrastructure. They managed multiple contracts with multiple vendors
with varying levels of support available, sometimes none at all. As
their business grew, they found teams distracted from focusing on core
business objectives. Their clients were requesting project services of
varying lengths, so paying for hardware not in use during slow periods
was becoming expensive. Because their customers ranged from global brand
names to niche players, almost all of them required additional
capabilities and security features. Furthermore, sites need be 100%
available when launching marketing campaigns or new products.

A hybrid configuration can enable such a customer to front online
properties with public cloud web servers that can be protected by a
dedicated physical firewall and supported by physical database and
application clusters. Some projects can run completely on the public
cloud while others dictate the need to run on a private cloud.

<img src="{% asset_path cloud-overview/nervous-about-the-cloud-go-hybrid-instead/introtohybrid_1.png %}" width="596" height="441" />

### 5. Large Physical To Virtual Migration/Consolidation

Hybrid configurations are not limited by scale. In the example below,
several cabinets worth of servers and storage in a customer data center
are moved off-site while secure VPN tunneling enables access to internal
and external applications. By deploying dedicated hypervisors and the
necessary supporting infrastructure (high-speed storage, clustered
databases, network security, etc.), much of the internal support burden
is removed, internal resources are made available for other uses, and
operating expenses are lowered (power and cooling, support costs,
etc.).

Once migrated into our facility, Rackspace provides industry-leading
support, network and power SLAs, and hardware replacement guarantees,
all for a monthly fee with no massive upfront capital expenditure. The
example below can be expanded to hundreds of servers or more; the
benefits are consistent.

<img src="{% asset_path cloud-overview/nervous-about-the-cloud-go-hybrid-instead/introtohybrid_2.png %}" width="587" height="229" />

### 6. Modest Entry Points

Hybrid hosting can help businesses of all sizes, not just those looking
for massive consolidation or hardware downsizing. A very basic
configuration can move your business into a hybrid cloud. The
illustration below shows customer-facing public cloud servers connected
to a dedicated physical database server. The firewall protects the cloud
servers while facilitating secure network communication between them and
the database server. Rackspace provides a RackConnectTM solution for
this secure network connection between dedicated and public cloud
infrastructure. This combination provides the best of both worlds:
public cloud flexibility and utility combined with a more secure
dedicated infrastructure and server hardware.

<img src="{% asset_path cloud-overview/nervous-about-the-cloud-go-hybrid-instead/introtohybrid_3.png %}" />

### 7. Questions Worth Asking

Potential cloud outsourcing scenarios are infinite. To pursue this
concept further requires internal analysis. Find out what your pain
points are, define risk levels, and, if possible, get a solid grasp on
your true cost of downtime. Knowing how much you lose for every hour of
downtime helps you properly scope out your hosting costs.

When planning for the introduction of hybrid hosting into your
infrastructure, you should ask yourself the following questions:

-   **How well do you understand your current application environment?** Ask
for internal utilization reports that provide historical traffic and  hardware
performance statistics. Data points to gather include peak  concurrent users,
average and peak bandwidth requirements, storage needs,  IOPS requirements,
database performance metrics, network segmentation and  licensing requirements,
among others.

-   **Do any regulatory or industry requirements need to be adhered to?**
Isolation is often required for compliance to standards such as PCI or  HIPAA.
They may also forbid the use of multi-tenant infrastructure.

-   **Are all of the applications currently running certified or supported by
their vendors to run in a virtualized environment?** In some cases, software
companies will not provide support if their application is installed on a
virtualized platform.

-   **Do you understand your current hardware environment?** Server reports can
be run to determine historical and average metrics such as processor, memory and
disk utilization. Servers running at low utilization are excellent virtualization
candidates. It also helps to know the factors that cause spikes in CPU and memory
use.

-   **Has a budget been defined for this project?** A hosting provider should
work with you to help design a system that optimizes your investment while
adhering to your technical and financial needs. Many options are available and
scope creep gets expensive quickly. This is another reason why knowing your cost
of downtime is important.

### 8. Summary

A hybrid configuration provides the security features, performance and
customization of dedicated hardware along with the cost savings, utility
and bursting aspects that cloud technology offers. This combination of
cloud and dedicated hosting can help businesses of all sizes, with the
caveat that while cloud technology may benefit everyone, it is not meant
for everything. Figuring out how to efficiently implement a hybrid
platform is based on a number of business-specific factors. Finding a
trusted, experienced cloud provider is key to helping you discover how
hybrid best fits into your business.
