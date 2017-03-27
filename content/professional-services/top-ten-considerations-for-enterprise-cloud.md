---
permalink: top-ten-considerations-for-enterprise-cloud/
audit_date:
title: Top Ten Considerations For Enterprise Cloud
type: whitepaper
created_date: '2013-05-31'
created_by: Rackspace Support
last_modified_date: '2017-03-06'
last_modified_by: Cat Lookabaugh
product: Professional Services
product_url: professional-services
---

***By [Rafat Shaheen](http://www.rackspace.com/blog/author/rafat-shaheen/),
Senior IT Strategist, Enterprise Cloud Solutions***

### Introduction

More than ever before, Enterprise IT must be a strategic partner to the
business. By focusing more on innovation and less on operations, the IT
organization can help the enterprise achieve a new level of competitive
advantage. This re-focusing of priorities changes the way most
organizations think about how IT services are delivered and consumed.
Companies clinging to traditional strategies of bare metal ownership
will find themselves increasingly stuck in the woods as they balance
cost, support, and the maintenance of expertise against fragile IT
budgets.

Enter [cloud computing](http://www.rackspace.com/cloud). Limitless
capacity and instant capability. Once considered a fad, cloud is proving
to be a well-traveled path to achieve more efficiency, agility, and
innovation — without the burdens of hardware procurement, lengthy
deployment timelines, and ongoing management hassles. Today, cloud is a
viable business model delivering real benefits for real-world use cases.
In fact, 86% of companies use more than one cloud service.<sup>1</sup>

So, what do you need to know about cloud computing in the enterprise?

### Enterprise Cloud Considerations

Here are ten considerations as you plan your enterprise IT strategy
around the cloud:

#### 1. Policy-Based Computing

System administrators and decision makers need intuitive tools to manage
the guidelines and policies that control behavior and interactions on
cloud-driven systems. Policy-based computing — the software paradigm for
building cloud resource management tools — eases IT management by
simplifying the control of remote systems.

Policies can be set at the infrastructure, application, and operational
level. Typically, a dashboard of system behavior is constantly updated
and available for decision makers.

-   **Infrastructure-level policies** are primarily concerned with the
management of the underlying resources and respective utilization levels. For
example, you may want to allocate a larger compute instance if the utilization
of CPU or memory reaches a certain threshold.
-   **Application-level policies** address the availability, uptime,
reliability, and recover-ability of application services. For example, a
service registry that monitors the application service lifecycle may trigger
the allocation of additional infrastructure resources if the response time of
the service falls below 200 milliseconds.
-   **Operational-level policies** deal with the arbitration and resource
allocation for application services to run your distributed datacenter. For
example, an operational policy may resolve the contention of resource requests
from two different applications by determining the relative priority and impact
on service levels.

#### 2. Cloud-aware Applications

The challenge of migrating existing legacy applications is a common
barrier for many enterprises contemplating the cloud. Often, these
business critical applications were built on proprietary or outdated
platforms and can’t benefit from the cloud without re-architecting.
Under this scenario, application availability is largely dependent on
the underlying computer system and on data center middleware. Keeping
these layers resilient over time happens at a significant cost.

In the cloud, there are two important characteristics that can enhance
application performance. First, compute resources are inherently
abundant and disposable. Second, delivery of services over the Internet
entails multiple dependencies.

Properly architected cloud solutions are designed with failure
resiliency built into the application itself. A [cloud-architected
application](http://www.rackspace.com/enterprise_hosting/hosted_applications/)
is composed of loosely coupled, inter-related services that can fail,
scale, and recover independently of one another.

For example, a retail software system — designed for the cloud — can
withstand service interruption, even during the peak traffic that occurs
on Black Friday. Based on exact utilization thresholds, the system can
spawn individual catalog browsing processes, shopping cart instances, or
demand generation analytics system processes. If one of the cloud
servers providing one of these services becomes unhealthy or
unreachable, the system can easily spin up another server, recover the
service, and rejoin the system with very limited interruption.

It is important to recognize that cloud represents an environment where
there is a shift from a single monolithic application to a distributed
application built from orchestrated services. As the cloud continues to
proliferate, applications will become increasingly cloud-aware. We can
expect them to be designed for resiliency and error tolerance with
loosely coupled components and a preserved, recoverable application
state.<sup>2</sup>

#### 3. Specialized Clouds

The cloud has largely been one-size-fits-all. But as cloud adoption
grows from strategic use to daily use, specialized clouds are emerging
to provide businesses with a custom-fit approach.

For example, from a basic storage perspective, healthcare Electronic
Health Records (EHR) and HR records seemingly have the same general
needs. However, factoring in requirements for security, confidentiality,
and privacy compliance quickly changes those needs. A specialized cloud
can give the healthcare entity and the HR firm a turnkey cloud outfitted
with elements that are customized to the specific needs of that
industry, workload, or business process.

We expect to see multiple, special purpose clouds continue to develop,
especially in areas related to Federal Government, Healthcare, and
Financial Services.<sup>3</sup>

#### 4. Fully Distributed Data Centers

The fully distributed data center model uses cloud resources to deliver
services regardless of source or location. A hybrid cloud is the most
practical delivery model, involving service provisioning from a
combination of on-premise, external cloud providers, and other
distributed locations. This business critical functionality is essential
in disaster planning, maintaining high availability and scalability.
According to a KMPG benchmarking survey<sup>4</sup>, more than half of
enterprises are seeking a [hybrid
solution](http://www.rackspace.com/cloud/hybrid/) that combines internal
and cloud resources to efficiently deliver and run multi-site data
center networks. As data centers are replicated, enterprises need
service providers who can deliver deeper service-level monitoring,
transformation services, and governance capabilities across data
centers.

#### 5. Moving Off BIg Iron

Imagine a world without the big iron servers in the data center. It’s
just around the corner. Many applications being migrated to the cloud
are architected to utilize open source technologies. These technologies
leverage smaller systems that can scale both horizontally and
massively.

Open source technology includes a family of document-oriented NoSQL
database systems (mongodB, Cassandra, CouchdB, Riak), distributed
key-value storage systems (e.g., voldemort, Redis, and memcached) and
distributed configuration, synchronization, and naming services such as
ZooKeeper, Hadoop and many others.

This shift towards [open source
technology](http://www.rackspace.com/cloud/openstack/resources/)
provides a tremendous opportunity to enhance IT agility and boost ROI
tooling and monitoring capabilities. It allows enterprises to get the
most out of IT resources. For larger IT organizations, making this move
means wading through a sea of providers. Finding a strategic partner
with a portfolio of tools to provide the control, visibility,
accountability, security, and scale that you need to run smoothly is
essential.

#### 6. Mandate for Dev/Ops

The term
[Dev/Ops](http://www.rackspace.com/blog/enterprise-cloud-forum-recap-prepare-for-devops-success/)
implies a combination of software development and operations. It
describes a practice that streamlines the software delivery process and
improves the cycle time from inception to deployment with an emphasis on
feedback for better quality software. This practice strikes a balance
between the need to change (to deliver new features and functions by the
software development team) and the fear of change (addressing system
stability by the operations team).

Traditionally, development and operations teams have improved their
processes independently. Agile software development enables developers
to deploy software more rapidly, while ITIL tracks the impact of change
as a set of risks.

One can think of DevOps as extending the Agile methodology (which helped
to connect developers, testers, and business representatives) to also
include operations. In other words, a DevOps approach extends the Agile
methodology beyond software release to include the deployment phase.

DevOps for organizations should include shared metrics and measurements
between teams, an evolved Agile process, and tools for automating
release management. In the cloud era, applications need to be coded to
operate in the cloud, which means coding for maximum scale and stateless
operation. Secondly, improved operations skills will be needed to drive
evolving scripting and coding, take advantage of automation, and employ
APIs to programmatically launch tasks.

#### 7. Rise of Big Data

The term [big data](http://www.rackspace.com/big-data/) refers to the
massive amount of unstructured data that are difficult to analyze and
manage using common database management tools. They are characterized by
their expanding volume size, high velocity of change, and variety of
data types and resources. The 2012 presidential election<sup>5</sup>
demonstrated the power of big data as candidates crunched vast amounts of
voter data to craft focused messaging and targeted ads.

For most enterprises, the deluge of data from internal and external
sources is overwhelming both the traditional infrastructure deployed to
store it and the teams responsible for managing it. To mine and
repurpose this data to make solid data-driven decisions requires a
broader set of tools. By using cloud storage and management tools to
increase the usability of data by just 10%, a median Fortune 1000
company could reap over $2 billion a year in added revenue.<sup>6</sup>

#### 8. True Cloud Federation

Deciding to move an application from your data center to the cloud or
between clouds presents challenges. The closed proprietary platforms in
some clouds make it difficult, if not impossible, to move an application
deployed on Cloud A to Cloud B. To address those challenges and reduce
the chance of platform lock-in, emerging industry standards and open
platforms in the cloud (like
[OpenStack<sup>&reg;</sup>](http://www.rackspace.com/cloud/openstack/resources/))
enable total cloud interoperability. This interoperability means that
moving between clouds becomes less of a chore and gives businesses more
freedom and flexibility. Workloads can move between clouds to meet
specific requirements and can be optimized for geography, performance,
cost, or other variables. If virtualization abstracted hardware, cloud
federation will provide abstraction at a much higher level with
resulting benefits of elasticity, mobility, and transparency.

#### 9. The Growth of SaaS

The [Software-as-a-Service
(SaaS)](http://www.rackspace.com/enterprise_hosting/saas/) space, one of
the key consumption models for cloud, is positioned to become the
primary method of distributing and utilizing software. Many [Independent
Software Vendors
(ISVs)](http://www.rackspace.com/enterprise_hosting/saas/) are working
to architect their software to take advantage of the cloud delivery
model. According to Gartner<sup>7</sup>, the top growth areas in SaaS through
2016 are office suites, digital content creation, and business
intelligence tools. For the growing number of SaaS operators, cloud
adoption is essential for building infrastructure that scales with
growth instead of making large CAPEX investments for infrastructure
ahead of the curve or holding on to unused capacity.

#### 10. Mission Critical in the Cloud

As cloud technologies evolve and businesses get more comfortable with
security and governance, more top tier applications and workloads are
expected to find a home in the cloud. For example, complex Enterprise
Resource Planning (ERP) applications that have been a staple in the
backend of large enterprises are transforming to cloud ERP.

Cloud ERP can serve as an affordable, customizable, and collaborative
environment where financial and operational capabilities are integrated
with social and mobile technologies. Other examples of enterprise
software delivered through the cloud include backend payment, settlement
and clearing, customer relationship management, payment systems,
business intelligence, content management, business process, and data
management.

Enterprises are being forced to rethink the organizational value of
high-maintenance elements like
[databases](http://www.rackspace.com/cloud/databases/),
[email](http://www.rackspace.com/email-hosting/), and
[collaboration](http://www.rackspace.com/enterprise_hosting/sharepoint/)
in light of the resource savings, reliability, and expert support
delivered in the cloud.

### Summary

With the focus in IT changing from operations to strategic partnership,
enterprises are looking to the cloud to help them become more agile and
responsive to the needs of the business. From [hybrid
clouds](http://www.rackspace.com/cloud/hybrid/) that span multiple
geographies to consuming Software-as-a-Service in the public cloud,
large organizations continue to make the cloud an integral part of their
IT strategy. As cloud adoption accelerates, innovation and evolution
will be central themes. Enterprises that understand the limitations,
capabilities, and potential of the evolving cloud are well positioned to
enhance their position in the marketplace.

**About Rackspace Enterprise Cloud Solutions**

Powered by an elite team of Sr. IT Strategists, Architects, Solution
Engineers and Sr. IT Consultants, the [Rackspace Enterprise Cloud
Solutions](http://www.rackspace.com/enterprise_hosting/advisory_services/)
team enables enterprises to harness the power of the hybrid cloud. Our
extensive Advisory & Professional Services portfolio offers end-to-end
solutions for our customers. Begin your ***[Fanatical
Support<sup>&reg;</sup>](http://www.rackspace.com/whyrackspace/support/)***
experience with a complimentary [IT Evolution
Workshop](http://www.rackspace.com/enterprise_hosting/advisory_services/),
where our strategists help to define a cloud strategy and actionable
roadmap that will propel your organization toward its optimized
solution. Contact us at **1-800-440-1249** or send us an email at
<advisory_services@rackspace.com> to schedule your workshop today.

Continue the conversation in the [Enterprise Cloud
Forum](http://www.linkedin.com/groups/Enterprise-Cloud-Forum-4167570?goback=.anp_4167570_1360705132758_1)
on Linkedin. Along with 670+ other IT professionals, our Rackspace
Senior IT Strategists and Cloud Solution Architects debate some of the
most controversial topics facing the enterprise.

### References:

<sup>1</sup> According to a 2012 Cloudability survey of more than 3,200 customers
in more than 80 different countries.

<sup>2</sup> Background information on this trend can be found at
<http://searchcloudcomputing.techtarget.com/feature/Business-continuity-moves-to-the-cloud-as-applications-become-resilient>

<sup>3</sup> As one example of this trend, see
<http://techandscience.com/techblog/ShowArticle.aspx?ID=1676>

<sup>4</sup> According to “Continuity Insights & KPMG LLP Present The 2011-2012
Global Business Continuity Management (BCM) Program Benchmarking Study.”
<http://www.kpmg.com/US/en/IssuesAndInsights/ArticlesPublications/Documents/2012-cin-kpmg-management-study.pdf>

<sup>5</sup>
[http://www.rackspace.com/blog/election-2012-powered-by-the-cloud-infographic/](http://www.rackspace.com/blog/election-2012-powered-by-the-cloud-infographic/%20)

<sup>6</sup>
[/how-to/turning-big-data-into-big-dollars](/how-to/turning-big-data-into-big-dollars)

<sup>7</sup> According to Gartner’s “Forecast: Public Cloud Services, Worldwide,
2010–2016, 2Q12 Update”

### About Rackspace

Rackspace<sup>&reg;</sup> Hosting is the open cloud company, delivering
[open technologies](http://www.rackspace.com/open-cloud/) and powering
hundreds of thousands of customers worldwide. Rackspace provides its
renowned ***[Fanatical
Support<sup>&reg;</sup>](http://www.rackspace.com/whyrackspace/support/)***
across a broad portfolio of IT products, including [Public
Cloud](http://www.rackspace.com/cloud/), [Private
Cloud](http://www.rackspace.com/cloud/private/), [Hybrid
Hosting](http://www.rackspace.com/cloud/hybrid/) and [Dedicated
Hosting](http://www.rackspace.com/managed_hosting/dedicated_servers/).
The company offers choice, flexibility and freedom from vendor lock in.
