---
permalink: the-cloud-at-your-pace/
audit_date:
title: The Cloud at Your Pace
type: whitepaper
created_date: '2015-03-19'
created_by: Rackspace Support
last_modified_date: '2017-03-06'
last_modified_by: Cat Lookabaugh
product: Cloud Overview
product_url: cloud-overview
description: > 
  The cloud has taken many twists and turns on its route to maturity. Business 
  advantages include: lower costs, reduced complexity, faster rollout of new apps and 
  capacity, and streamlined processes. But there are concerns, too, and this paper 
  addresses those with Microsoft technology.
---

### 1. EXECUTIVE SUMMARY

The cloud has taken many twists and turns on its route to maturity.
Along the way, many IT leaders have enjoyed real business advantages,
including:

-   Lower costs
-   Reduced complexity
-   Faster roll-out of new apps and capacity
-   Streamlined processes

Yet, some CIOs remain hesitant, reluctant to move any computing assets
outside the confines of the corporate data center. Security, legacy app
support, availability, and licensing costs are among these concerns. And
some assume the cloud is an all-or-nothing proposition: either move it
all, or don’t move anything.

This white paper shows how you can now use the Microsoft technology
stack to address those concerns, while minimizing your risks, and moving
to the cloud at your own pace. This is now possible with a new offering
that provides a cautious path to the cloud using familiar Microsoft
tools, called Microsoft Cloud Platform at Rackspace.

Now you can use the Microsoft technology stack to move to the cloud at
your own pace.

### 2. WHAT HOLDS BACK CLOUD ADOPTION?

According to the 2014 RightScale State of the Cloud Report, 87% of CIOs
surveyed are running mission-critical business applications in a public
Infrastructure-as-a-Service (IaaS) cloud, or at least experimenting with
it.<sup>1</sup>

The report goes on to categorize IT leaders based on their cloud usage:

-   Pioneering cloud-focused CIOs have adopted a “cloud-first” policy
-   More guarded cloud explorers and cloud beginners have some
    mission-critical apps in the cloud, or are working pilot projects
-   Wary cloud watchers have not yet deployed anything to the cloud, but
    are opting to stand back and observe others

Make no mistake about the cloud watchers. Though cautious, they are far
from indecisive. They know what complexities lie buried in the digital
depths of their departments. So the notion of moving sensitive data
off-site seems like a radical overhaul of the IT infrastructure they
worked so hard to build.

For these CIOs, allowing a third party to manage mission-critical data
brings up some significant concerns, including:

-   Privacy and security
-   Legacy application support
-   Noisy neighbors
-   Availability and reliability
-   Learning curve
-   Licensing costs
-   Flexibility
-   Database access

#### Refresher: The Three Types of Clouds

A public cloud provisions virtual machines (VMs) on servers located at a
third- party site. All sys admin services are provided by the third
party, including security, connectivity, data access, and
backup/recovery.

Since resources are available on demand, this is the most cost-effective
solution. But the public cloud doesn’t address concerns with security,
noisy neighbors, or the need to acquire special skills for the cloud.

A private cloud uses virtualization similar to a public cloud, but all
resources are dedicated solely to one client. Sys admin services can be
performed either by a third- party provider or by a company’s own IT
staff. The company still owns and maintains all VMs, regardless of where
they operate.

A private cloud addresses most of the CIO’s concerns, although it does
not deliver as much cost savings as the public cloud.

A hybrid cloud combines the advantages of both public and private
clouds.

Non-mission-critical data can be moved to the public cloud, lowering the
cost of keeping it in-house, while not exposing the company to much
risk. Sensitive data can stay within the private cloud under close
control.

As expected, costs are lower than a private cloud, but higher than a
public cloud.

#### Cloud Concern #1: Privacy And Security

Data centers house confidential data that must never fall into the wrong
hands. With your sensitive data tucked away inside a corporate data
center, you have some guarded level of comfort.

As well, many enterprises have regulatory and compliance concerns that
limit options for locating data.

Outsourcing to a public cloud means relinquishing control of that data
to a cloud provider, trusting them to treat it with as much care as your
own IT team would. You still have responsibility, but much less
authority. This is a popular definition of on-the-job stress; it’s been
called “a known curse of the working world.”<sup>2</sup>

#### Cloud Concern #2: Legacy Application Support

Legacy apps could well predate the current IT workers who manage them.
Even though an older app may be mission-critical, street-smart staffers
often keep their distance, knowing how hard it would be to restore if it
ever failed. Many IT leaders take the stance, “It runs. Don’t touch it.”

Legacy apps could well predate the current IT workers who manage them.

Legacy applications were designed with legacy infrastructure in mind.
How a VB5 COM+ app with direct Win32 API calls would perform on a modern
64-bit cloud operating system would require time-consuming research and
analysis.

You may be understandably hesitant to move these apps to a new
environment where the only migration strategy is deploy it, start it,
and hope for the best.

#### Cloud Concern #3: Noisy Neighbors

In the corporate data center, you can allocate resources however you see
fit. In the public cloud, you lose much of this control. Memory,
storage, disk I/O, and even CPU cycles must be available for every
tenant that shares the same physical server or cluster. This creates the
“noisy neighbor” syndrome.

Just like an annoying neighbor blaring his stereo at 3 a.m., a fellow
tenant’s high-volume website can disrupt everyone in the neighborhood.
As ViaWest Product Development Director Matthew Wallace notes, noisy
neighbors can cause “spotty performance, unexpected hiccups in service,
or frustrating scaling difficulties that keep the ops team up too many
nights.”<sup>3</sup>

#### Cloud Concern #4: Availability And Reliability

We live in an “always on” world where everyone expects fast and reliable
access to data and applications. If a cloud application goes down,
customers can’t buy products, employees can’t access critical files, and
IT leaders have no choice but to call tech support.

“The most frustrating thing when something goes wrong is not being able
to speak directly with an engineer,” says April Sage of cloud provider
Online Tech in Ann Arbor, MI.

“If you support mission-critical systems, or your online presence is
critical for your business to operate smoothly, you have to be prepared
to invest in a cloud and cloud provider that is capable of providing a
level of protection commensurate with your needs.”<sup>4</sup>

#### Cloud Concern #5: Licensing Costs

How much will licensing cost in the cloud? Good question. Most software
licenses are based on the hardware where the software runs. That doesn’t
align well with the cloud’s elastic nature.

You buy a software license, entitling you to run that software forever.
You rent cloud infrastructure for as long as you need it, and pay for
only what you use. When you don’t need it anymore, that cloud instance
goes away, along with software license you paid for.

Many application vendors, including IBM and Microsoft, are experimenting
with flexible licensing models that adhere more to the spirit of the
cloud.<sup>5</sup> Until then, software licensing in the cloud will continue to
be a moving target.

#### Cloud Concern #6: Learning Curve

You may be unsure what skills you need for a cloud initiative. One thing
is for sure: You probably don’t have all those skills in-house. This
leaves you in an unenviable position: either train your own people, or
rely on outside consultants.

Even the CIO of the United States expressed frustration about the
federal government’s move to the cloud. His 2010 “Cloud First”
initiative directs agencies to favor cloud-based infrastructure over
in-house data centers. But government agencies are moving slowly,
blaming a lack of cloud expertise among federal IT workers.<sup>6</sup>

#### Cloud Concern #7: Flexibility

To maximize your ROI in any migration to the cloud, you must predict
what cloud resources you will require. But it’s not always easy to know
what resources are available, or what quantities you’ll need.

Cloud vendors often sell flexibility, but some vendors are more flexible
than others. And no CIO wants to get locked into a long-term
relationship with a vendor who can’t fulfill its lofty promises.

Whether on-premises or in the cloud, your IT infrastructure exists to
support your business processes, serve your customers, and enable
innovation—both today and in the future. Without flexibility from cloud
vendors, you can’t deliver on that.

#### Cloud Concern #8: Database Access

If data is money, then your relational database (RDBMS) is the bank.
Everyone in the company needs unfettered access to make deposits
(inserts), withdrawals (deletes), and transfers (updates) to get their
jobs done. In the corporate data center, all roads to the bank are fast,
reliable, and relatively well-patrolled.

However, some CIOs fear that moving the database to the public cloud
would be like moving the bank to an island with foreign banking laws,
accessible by a single bridge. Without a dedicated local to help them
maintain connectivity, even company DBAs can feel like strangers in a
strange land.

### 3. SOME CIOS ARE WAITING FOR A SAFER PATH

Despite all these concerns, many IT chiefs are finding success in the
cloud. According to the Verizon report State of the Market Enterprise
Cloud 2014, two out of three enterprises are now using cloud computing
for production applications.

But it would be a mistake to label the remaining one-third of IT leaders
indecisive. On the contrary, they may simply have a lower tolerance for
risk.

“Few of the IT leaders that we’ve spoken to have ever wanted to hold the
business back,” says the Verizon report. “If they ever showed any
hesitation in seizing the opportunities that cloud presented, it was
only reasoned caution.”<sup>7</sup>

Some CIOs just want a safer way to capture the benefits of cloud
computing, at a pace they’re comfortable with.

### 4. KNOW YOUR OPTIONS

Any service delivery model—cloud or otherwise—has to align with one
overall objective: to deliver IT that meets the strategic and
operational requirements of the business.

To do this, IT leaders must understand their options, especially the
three different types of clouds available: public, hybrid, and private
(see sidebar).

#### Different Clouds, Different Benefits

The public cloud option generally provides the lowest upfront cost
because the provider’s infrastructure is shared across multiple tenants.
However, it doesn’t address the concerns of security, noisy neighbors,
or the need to acquire special cloud skills.

A hybrid cloud can make sense for a company that has identified
applications to move to the cloud, while it retains others in-house.
This approach is best suited for IT environments with few dependencies
between innocuous data that can move to the cloud, and sensitive data
that cannot. High availability and data access questions still loom
large with a hybrid cloud.

But for CIOs who require secure, flexible, and highly available
infrastructure without the downside of noisy neighbors and high
licensing costs, the private cloud makes the most sense.

A private cloud is hosted and managed by an experienced cloud provider.
This is ideal for CIOs who want to tap the power of the cloud without
the pain and expense of managing it themselves. Cloud providers do the
heavy lifting of managing the day-to-day operations of keeping workloads
up and running.

And because a private cloud dedicated to only one client, concerns over
noisy neighbors and governor limits go away.

A managed private cloud also serves as an excellent stepping-stone to
other cloud options. A skilled cloud provider can federate virtual
instances within the company data center, creating a hybrid cloud. Then
they can help the client move on to the public cloud, where there are
even more performance gains and cost savings available.

### 5. MICROSOFT CLOUD PLATFORM AT RACKSPACE

By supporting your IT team’s existing familiarity with Microsoft
Hyper-V, System Center, Windows Server, and Windows Azure Pack, this new
offering relieves the concerns that held you back from the cloud, until
now.

The Microsoft Cloud Platform at Rackspace, a joint offering from two respected,
industry-leading vendors, delivers the agility and efficiency of a public
cloud, combined with the enhanced security, control, and performance of a
dedicated environment.

Cloud Platform is engineered with scalability in mind to support your
high-volume workloads. You get the power of the cloud without the pain and
expense of running it, so you can focus on your strategic priorities.

The Microsoft Cloud Platform at Rackspace is private and secure,
cost-effective, and supports familiar Microsoft tools. It is fully
extensible, SQL-friendly, extremely flexible, and comes bundled with
award-winning ***Fanatical Support<sup>&reg;</sup>*** by Rackspace.

As shown in the following table, this offering addresses most of the concerns
of CIOs who, until now, were reluctant to move to the cloud.

<img src="{% asset_path cloud-overview/the-cloud-at-your-pace/CloudatYourPace-2.png %}" width="507" height="533" />

#### Private And Secure

Managed private clouds bring a level of comfort and added security not
found in public clouds. All system resources—memory, storage, and
bandwidth—are dedicated solely to your IT operation. Sensitive data
stays safe, secure, and isolated from noisy neighbors. And with
Microsoft Hyper-V, security is designed to be transparent. You secure
your VMs exactly the same way you secure your own physical machines,
using the same familiar control panel your staff currently uses.

#### Cost-Effective

You should never have to pay extra for virtualization, and with
Microsoft Cloud Platform at Rackspace, you don’t have to. Since you
already own the licenses, there is no additional fee to use the
virtualization capabilities. License the host machine with Windows
Server 2012 R2 Datacenter and provision unlimited Windows Server guest
OSs with no additional license requirements. Also, you’re not limited to
Windows workloads; Hyper-V also supports a full range of Linux operating
systems.

#### Familiar Tools

Microsoft Hyper-V and Systems Center take hosting VMs to another level.
Offering flexible guest VM support on private and secure hardware makes
Hyper-V is the hypervisor of choice for your workloads. Cloud Platform
builds on the platform by introducing automation, monitoring, and
self-service provisioning through a private implementation of the
Windows Azure Pack.

No special training is required; your administrators can use the same
Microsoft System Management Console they are already familiar with. This
allows you to leverage your existing investments in Microsoft tools and
technologies.

To see this familiar management console in action, watch this
[video](https://www.youtube.com/watch?v=LSkhvunALqk).

#### Extensible

Do you support multiple lines of business that shouldn’t overlap one
another? With Rackspace, you can meet this requirement by building
isolated private cloud networks. This “cloud within a cloud”
encapsulates individual lines of business within their own cloudspaces,
allowing your security staff to define top-level constraints for the
entire group of VMs.

Extending the business couldn’t be easier. Rackspace can spin up another
isolated network on demand. You can even optimize business policies for
each LOB according to specific KPIs like performance, system
utilization, high availability, and of course, security measures.

#### SQL-Friendly

Need a SQL Server instance for a seasonal marketing promotion or
unexpected traffic spike? Through the power of Cloud Platform you can
utilize Database-as-a-Service (DBaaS) to provision SQL Server or MYSQL
databases via a self-service web interface. No DBA required.

Rackspace supports all SQL Server sysadmin functions you use today,
including mirroring, log shipping, and clustering. Your DBAs also have
complete visibility into the advanced SQL Server options, including
physical memory and disk-level settings.

#### Flexible

You can move as much or as little of your application catalog as you
like, keeping your legacy applications running smoothly in an
environment they were designed for. Hardware can be added incrementally
and connected across multiple physical data centers.

Microsoft has announced that it will cease to support Windows Server
2003 on July 14, 2015.<sup>8</sup> But with Rackspace, this is a non-issue. Your
support team can spin up a 32-bit guest OS on your private cloud like
you run today. Your 32-bit apps can then continue to run like they
always have, only at a lower cost and with less administrative
headaches.

Also, there is no hosting provider lock-in. Your VMs are yours to take
with you to any other cloud vendor you choose. You can even federate VMs
in your own corporate data center or even move them to Microsoft Azure.

#### Fanatical Support<sup>&reg;</sup>

Having a support staff that can make your private Microsoft Cloud
Platform work for you is vital to your success. Rackspace developed
***Fanatical Support<sup>&reg;</sup>*** and has applied the same commitment to
Microsoft Hyper-V and Systems Center support. You can rest easy, knowing your
mission-critical apps are managed by a four-time Microsoft Partner of
the Year with deep roots in the Microsoft ecosystem.

Rackspace has also engineered flexible guest OS support into this
offering which provides its award winning ***Fanatical Support<sup>&reg;</sup>***
You choose which VM’s receive the support and which ones you prefer to
support on your own. You can turn this option on and off based on your
needs. This versatile support offering applies to both Windows and Linux
servers.

### 6. CONCLUSION

Many CIOs have concerns about moving workloads from out behind their
firewalls to the cloud. But the benefits of doing so are proven. It
makes sense to start slowly, moving low-priority workloads to
virtualized instances using familiar tools on a familiar operating
system. And now you can, using the new offering called Microsoft Cloud
Platform at Rackspace.

Down the road, if you feel comfortable moving to a hybrid cloud or
public cloud, you have all the flexibility and control you need to do
so.

For a more detailed discussion on what apps can move to the cloud in
which order, see the Rackspace white paper [“Getting Started with the
Cloud: A Step-by-Step Enterprise Implementation Guide”](https://support.rackspace.com/white-paper/getting-started-with-the-cloud-a-step-by-step-enterprise-implementation-guide/).

Moving to the cloud may appear daunting, but you don’t have to go it alone.

To find out more about how Rackspace can help you enjoy the benefits of
the cloud on your own terms, call 800-961-2888 to schedule a demo today.

Or visit <http://www.rackspace.com/microsoft/cloud-os>.

### 7. ENDNOTES

<sup>1</sup> “State of the Cloud Report,” RightScale Corporation, February 2014,
accessed 17 November 2014 from
<http://www.rightscale.com/blog/cloud-industry-insights/cloud-computing-trends-2014-state-cloud-survey>

<sup>2</sup> Kasia Moreno, “Curse Of The CMO: Responsibility Without Authority,”
Forbes.com, 24 July 2014, accessed 5 December 2014 from
<http://www.forbes.com/sites/forbesinsights/2014/07/24/curse-of-the-cmo-responsibility-without-authority/>

<sup>3</sup> Matthew Wallace, “The Problem of Noisy Neighbors in the Cloud,” All
Things D, Feb 2013, accessed 17 November 2014 from
<http://allthingsd.com/20130225/the-problem-with-noisy-neighbors-in-the-cloud/>

<sup>4</sup> Sara Angeles, “8 Reasons to Fear Cloud Computing,” Business News
Daily, 1 Oct 2013, accessed 18 Nov 2014 from
<http://www.businessnewsdaily.com/5215-dangers-cloud-computing.html>

<sup>5</sup> Dan C. Marinescu, “Cloud Computing, Theory and Practice,” Elsevier
Science, Morgan Kaufmann, May 2013, Sec 3.11

<sup>6</sup> Larry Freeman, “The Benefits of Implementing a ‘Cloud First’
Strategy’,” Tech Target, accessed 17 November 2014 from
<http://searchstorage.techtarget.com/NetAppSponsoredNews/Should-You-Adopt-a-Cloud-First-Strategy>

<sup>7</sup> “State of the Market Enterprise Cloud 2014,” Verizon Corporation,
accessed 17 November 2014 from
<http://cloud.verizon.com/enterprise-cloud-report>

<sup>8</sup> Windows Server 2003 support is ending July 14, 2015, accessed 6
February 2015 from
<http://www.microsoft.com/en-us/server-cloud/products/windows-server-2003/>
