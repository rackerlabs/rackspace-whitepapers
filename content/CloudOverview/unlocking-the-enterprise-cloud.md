---
permalink: unlocking-the-enterprise-cloud/
audit_date:
type: whitepaper
created_date: '2012-07-23'
created_by: Rackspace Support
last_modified_date: '2017-03-07'
last_modified_by: Cat Lookabaugh
product: White Paper
product_url: white-paper
resource: 'https://www.rackspace.com/knowledge_center/sites/default/files/whitepaper_pdf/Unlocking the Enterprise Cloud_OpenStack 032811.pdf'
---

***Written by:
John Engates, Chief Technology Officer
Robbie J. Wright, Senior Manager, Enterprise Marketing***

### Abstract
[Cloud computing](http://www.rackspace.com/cloud/what_is_cloud_computing/)
stands well poised to help enterprises significantly improve their business
IT speed, agility and costs. However, the fear of technology “lock-in” –
difficulty in efficiently switching cloud hosting providers or platforms
due to enterprise size and scale – continues to discourage some large
corporations from realizing the benefits of the Cloud. This whitepaper
discusses the lock-in enterprises face with cloud computing and how the
OpenStack open-source platform can help to eliminate that conundrum.
Next, it defines in detail the components and inner workings of
OpenStack technology. It concludes by providing basic guidance on how to
help successfully evaluate the value of OpenStack technology for the
enterprise.


### Introduction

The [OpenStack](http://openstack.org/) platform is a new open-source
cloud operating system based on technology from Rackspace [Cloud
Servers](http://www.rackspace.com/cloud/cloud_hosting_products/servers/) and [Cloud
Files](http://www.rackspace.com/cloud/cloud_hosting_products/files/) platforms
and the NASA Nebula Cloud platform, and contributions from the 50+
organizations participating in the community. **Its concept, planning
and creation materialized out of a shared interest in building an
open-source, massively scalable cloud-computing platform. ** With broad
industry collaboration and support, this open-source platform is
emerging as the de-facto open industry standard allowing federation,
portability and choice for cloud consumers.

Rackspace, the world’s leading specialist in the hosting and [cloud
computing](http://www.rackspace.com/cloud/what_is_cloud_computing/) industry,
was having trouble in helping enterprise customers migrate from – and in
some cases, to – other providers. Rackspace noticed that the symptoms
they were experiencing stemmed from one problem: lock-in. Due to a lack
of standardization in the Cloud, it was nearly impossible to achieve
massively scalable, easy-to-implement cloud computing.

But every cloud has a silver lining. Knowing the beauty of cloud
computing lies in its flexibility, Rackspace realized the Cloud needed
flexibility not just in front-end use, but also in the back-end
architecture. The company founded OpenStack, a cloud-computing platform
that eliminates lock-in by using an open-source licensing model and
therefore allowing the software to be deployed broadly. Developers and
participants, including NASA, Citrix and Dell are now jumping onboard to
continue to spur further innovation.

Rackspace collaborated with major technology industry leaders to create
OpenStack platform, but not just for themselves. Its open-source
architecture makes it available to the world. And though organizations
of all sizes will realize its benefits, OpenStack provides perhaps the
largest impact at enterprise scale. As enterprise IT seeks more
cost-effective, flexible and productive computing, OpenStack represents
an incredibly powerful business tool by abolishing vendor and technology
lock-in. 

### The enterprise cloud today

#### Cloud computing for the enterprise

Cloud computing is essentially software-powered hardware. The Cloud is a
pool of virtualized hardware controlled by software that provides users
the ability to provision and decommission resources as efficiently as
possible – truly an elastic and instant computing concept. For
enterprises, this level of computing flexibility can provide three major
benefits: speed, agility and cost. Cloud computing provides resources in
a matter of seconds or minutes, as compared to days, weeks or longer for
physical infrastructure expansions. Also, it removes the limitations of
physical platforms, in that it can theoretically scale infinitely. And
cloud computing’s utility model allows an enterprise to pay solely for
the resources it uses instead of absorbing the sunk cost of physical
hardware in the traditional computing model. These significant
advantages are tempting many enterprises to move quickly into cloud
computing. According to IDC, **47% of IT and business leaders say they
are already using cloud computing or are actively researching it.** <sup>1</sup>
Additionally, Gartner research predicts that 20% of businesses will own
no IT assets by 2012. <sup>2</sup> This rising trend in Cloud adoption can be
attributed not just to its overall computing model, but also to its
modular implementation options. So while the transition from traditional
to cloud computing is taking place, enterprises can switch to the Cloud
where applicable and stick with traditional hosting where required.
After all, the Cloud is for everyone, but not for *everything.*

*<sup>1</sup> “Cloud Computing Survey: IT Leaders See Big Promise, Have Big Security
Questions” CIO Magazine, October 2008
<sup>2</sup> “Gartner’s Top Predictions for IT Organizations and Users, 2010 and
Beyond: A New Balance” Gartner, Inc., December 2009*

#### Types of cloud computing

The industry has appropriated the term “Cloud” to span many different
hosting and even internal virtualization solutions. For our purposes, we
will use the following terminology:

- [The Cloud](http://www.rackspace.com/cloud/) – often known as the
“Public Cloud,” an off-premise (hosted), multi-tenant solution that
enables a true utility computing model
- [Private Cloud](http://www.rackspace.com/managed_hosting/private_cloud/index.php) –
single-tenant virtualization solutions hosted either on- or off-premise
-  Dedicated Hosting](http://www.rackspace.com/managed_hosting/index.php) – both
virtualized and un-virtualized single-tenant computing solutions hosted
off-premise
- [Hybrid Hosting](http://www.rackspace.com/hosting_solutions/hybrid_hosting/) – a
mix of the Cloud and Dedicated Hosting/Private Cloud in a solution

Each of these solutions and their hybrid mixture has its own advantages
and limitations, making different solutions more appropriate for
different use cases. The Cloud offers the most leverage and greatest
flexibility to enterprises, but some regulatory bodies have yet to allow
it for certain compliance-heavy applications. The Private Cloud makes it
easier to address security, privacy, compliance and other risks
associated with using multi-tenant, shared resources but typically
requires more up-front and ongoing investment for enterprises. Dedicated
Hosting typically can help enterprises address their compliance
requirements, but is usually more costly, less flexible and slower to
adjust for heavy traffic. And finally, as a mixed solution, Hybrid
Hosting offers the elasticity of cloud computing along with security of
dedicated servers, providing the ability to further optimize the use of
computing resources, even within a single application.

*Note: The Rackspace whitepaper entitled [“Consideration for the Cloud:
The Process Every Enterprise Should Think
Through”](/how-to/consideration-for-the-cloud-the-process-every-enterprise-should-think-through) provides
additional background information on the subject of cloud computing and
hybrid hosting at the enterprise level.*

#### The fear of lock-In

Cloud computing can resolve the four major issues that enterprise IT
environments face today: reliability, availability, scalability and
affordability. Its speed, agility and cost allow enterprises to increase
capacity on the fly without investing in new infrastructure, training
new and existing personnel, and licensing new software.

But even though cloud computing may seem like the ultimate platform for
traffic flexibility, the closed platforms that some providers offer can
reduce an enterprise’s provider flexibility. The industry refers to this
phenomenon as “lock-in.” By using a given hosting company’s proprietary
system or an ISV’s proprietary virtualization platform, **switching to
another provider or platform often becomes so expensive, difficult and
time-consuming that enterprises instead remain locked in to their
existing providers, reducing bargaining power and, therefore, the
ability to seek greater value. **  Enterprises fear lock-in because they
are concerned first and foremost about integrating with their existing
computing resources. They need an IT model that can easily plug into the
legacy systems, hardware components, and software applications they have
built up over years of computing upgrades. Thus, a cloud computing
solution that helps move enterprises toward open federation while
remaining portable and easy to implement is paramount to CEOs, CFOs,
CIOs and other IT executives.

### The Openstack platform for the enterprise

#### How it solves lock-In

The OpenStack Project was created to resolve the enterprise hosting
issue of lock-in and promote federation. Its mission is “to produce
the ubiquitous open-source cloud computing platform that will meet the
needs of public and private cloud providers regardless of size, by being
simple to implement and massively scalable.” To simplify the
implementation of cloud computing, the OpenStack platform establishes a
standard cloud platform for all hosting providers to use. And by making
cloud implementation easier for providers, the OpenStack platform does
the same for enterprises. The OpenStack community has effectively
created an orchestration standard that allows enterprises to “architect
once, deploy anywhere.” **The open-source model makes it much easier for
an enterprise to adopt and maintain cloud computing by eliminating the
time, difficulty and expense of re-architecting IT applications. **In
contrast to proprietary platforms such as Amazon Web Services and the
limited functionality of VMware, the OpenStack platform alleviates
lock-in by allowing enterprises to switch hosting providers quicker,
easier and cheaper.

#### Other enterprise advantages

The OpenStack platform provides the massive scalability that enterprises
demand. While the Cloud generally provides ample space for bursts in
Internet and intranet traffic, enterprises deal with much larger amounts
of data and users than the average business. Unfortunately for
enterprises, most cloud computing platforms simply do not provide the
scale and flexibility to meet their needs. However, the OpenStack
platform aims to solve this problem. As an extremely large collector of
data, NASA needed an open-source cloud platform with the ability to
handle massive scale. Thus, the OpenStack platform provides the ability
to scale storage in the Cloud not only to accommodate NASA’s
astronomical amounts of data, but those of enterprises as well.
Additionally, as more and more enterprises discover future scalability
enhancements, the OpenStack open-source platform will give all
enterprises access to such innovations.

**The OpenStack open-source model is an engine for innovation.** It
brings together individuals and companies in the developer community and
gives them a chance to help drive the [enterprise
cloud](http://www.rackspace.com/enterprise/) forward. And because
Rackspace, NASA and Internap are running this platform in production
today, the OpenStack platform has a proven track record. This allows the
project to attract many very high-quality developers, who will
undoubtedly help make great strides in advancing enterprise-level cloud
computing. Additionally, it provides enterprises the ability to be
involved with the development of the platform by contributing code and
submitting fixes that benefit their implementation.

As for interoperability, the OpenStack platform allows enterprises to
run workloads in various environments without siloing them off from one
another. Regardless of hybrid or public or private cloud implementation,
the OpenStack platform gives enterprises the ability to host in-house,
at a provider, or both. It alleviates the traditional complexity of such
separated systems by enabling them to work together effectively.

### Openstack technology in detail

#### What is OpenStack technology?

**OpenStack technology is made up of two main components: Compute and
Object Storage. Both components work to abstract the physical layer from
the application layer. Thus, entire virtual environments that operate
just like today’s enterprise data centers can be easily built or
dismantled. **And most importantly, the entire platform is built to run
on industry-standard x86 hardware.

OpenStack Compute is an orchestration layer that merges the best of
Rackspace’s code from Rackspace Cloud Servers and the code behind NASA’s
Nebula cloud platform. Within it, everything is componentized to allow
users to deploy the pieces that are right for them. This prevents
enterprises from being forced to use specific load balancers,
hypervisors, etc. and gives them the ability to leverage legacy systems.
The modular design of OpenStack Compute empowers enterprises to plug in
any technology they need and/or want rather than adopt the monolithic
and proprietary stack typically pushed by traditional IT vendors.

OpenStack Object Storage is the very same code that powers Rackspace
Cloud Files today. In lieu of a central database, it distributes data
throughout the system for redundancy. This storage model makes Object
Storage massively scalable for enterprise needs, up to multiple
petabytes.

The application programming interfaces, or APIs, for OpenStack Compute
and Object Storage are both REST based. Also, both APIs originate out of
the Rackspace API. So any tools and services that an enterprise has
built to run on the Rackspace API will also run on OpenStack.

#### Basic business integration

In order to work effectively for businesses, OpenStack technology must
integrate with other common systems. **The OpenStack platform was
designed to be modular and ready to incorporate standard
features** (legacy or new), including the following:

- User Control Panel
- Ticketing System
- Network Management
- Monitoring Systems
- Host Server Management

#### Enterprise integration

To refine the OpenStack platform for the enterprise, the community added
the ability to simply plug in to common enterprise-level IT systems.
These include:

- Admin Control Panel
- User Management
- Departmental Accounting Chargeback
- Enterprise Software Integration Systems

#### OpenStack participants

**Numerous computing companies are signing up to help build upon the
OpenStack platform** that Rackspace and NASA founded. The list below is
a small sampling of the ecosystem participants who are currently adding
capabilities:

- Microsoft contributed support for its hypervisor, Hyper-V
- Dell, Intel and AMD are optimizing their hardware to run the OpenStack
platform and determining the best specifications to run an OpenStack
Cloud
- Citrix added support for XenServer, and is now working on support for
VMware ESX
- NTT Data added support for IPv6
- Opscode is writing scripts to support automation

Each of these participants will help integrate the OpenStack platform at
the enterprise level. And as more computing product and service
providers get involved, the OpenStack platform could become an even
better open-source platform for [enterprise
cloud](http://www.rackspace.com/enterprise/) computing.


### Applying Openstack technology

#### Best uses for cloud

Because the OpenStack platform is best applied to cloud computing, an
enterprise should first decide how it intends to use the Cloud. As we
stated earlier, **today the Cloud is for everyone but not for
everything.** Some businesses use Dedicated Hosting to run databases on
dedicated hardware for PCI compliance or because they do not want
sensitive data residing on a shared platform. Other applications – for
example, web servers and certain SaaS tools – run well in the Cloud
because of its elasticity and ability to rapidly scale. The brief, but
critical, assessment outlined below can help decision makers quickly
determine whether the Cloud is right for a given application. That way,
time, resources, money and liability are not invested in an enterprise
endeavor that does not provide optimal value.

To begin, assess the application itself:

- Is the workload I/O intensive?
- Is it latency-sensitive?
- Does it require special treatment for security compliance?
- Is it a legacy, proprietary application or form factor?

If the answer to all of these questions is “no,” the Cloud will likely
be a value-added option for an enterprise’s IT strategy.

#### Best uses for the OpenStack platform

In order to provide the maximum flexibility that makes cloud computing
so advantageous, enterprises can optimize the OpenStack platform by
using it in one of four ways:

- Externally hosted Cloud
- Internally hosted Private Cloud
- Externally hosted Private Cloud
- Hybrid of externally hosted Private Cloud and Cloud


Though OpenStack technology is applicable to any computing platform –
Cloud or not – the above list represents the uses in which we believe
enterprises could derive the most benefit.  

### Summary

Cloud computing can potentially provide enterprises with speed, agility
and cost-effective IT environments, but the fear of provider and
technology lock-in has prevented many enterprises from adopting the
Cloud. To remedy this situation, Rackspace founded OpenStack, an
open-source community and cloud-computing platform. **Its
standardization of cloud computing, growing development community and
trusted computing providers make it a viable option for enterprises that
are considering Cloud adoption.** Certain Cloud uses will give
enterprises the most benefit from the OpenStack platform, but no matter
what its use case the platform provides the same main benefit: ease of
integration.


## Learn more

If you’d like to hear from the author, please contact the Rackspace
Enterprise team and we will happily schedule some time to discuss this
topic further with you.

Philip Bankey\
210.312.1779\
[philip.bankey@rackspace.com](http://mailto:philip.bankey@rackspace.com)

Katie Schmidt\
210.312.1788\
[katie.schmidt@rackspace.com](http://mailto:katie.schmidt@rackspace.com%20)
