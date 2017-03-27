---
permalink: hubspot-disrupts-marketing-in-the-hybrid-cloud/
audit_date:
title: Hubspot Disrupts Marketing in the Hybrid Cloud
type: whitepaper
created_date: '2013-09-05'
created_by: Rackspace Support
last_modified_date: '2017-03-23'
last_modified_by: Cat Lookabaugh
product: Use Cases
product_url: use-cases
---

<a href="http://www.hubspot.com/">
   <img src="{% asset_path use-cases/hubspot-disrupts-marketing-in-the-hybrid-cloud/hubspot.pngg %}" width="311" height="113" />
</a>

**CUSTOMER’S BUSINESS:** Hubspot
is a SaaS offering all-in-one inbound marketing tools.

**CHALLENGES:** Aggressive business growth created new demands for
performance annotation and uptime.

**RACKSPACE<sup>&reg;</sup> SOLUTION:** [Rackspace Hybrid
Cloud](http://www.rackspace.com/cloud/hybrid/), [Managed
Hosting](http://www.rackspace.com/managed_hosting/dedicated_servers/),
[Cloud Servers](http://www.rackspace.com/cloud/servers/), [Rackspace
Private Cloud](http://www.rackspace.com/cloud/private/),
[RackConnect<sup>&reg;</sup>](http://www.rackspace.com/hosting_solutions/hybrid_hosting/rackconnect/)

**BUSINESS OUTCOME:** Efficiency has quadrupled for half the cost of
public cloud.

### Inbound marketing leader’s hybrid solution boosts efficiency while cutting costs.

Today’s consumers are constantly bombarded with interruptive messaging
and have grown increasingly immune to traditional marketing tactics.
Marketers struggling to grab their attention shouldn’t rely on bigger
ads or more frequent emails, according to HubSpot CIO Jim O’Neill, but
rather “creating marketing people love.”

HubSpot helps companies do just that through their all-in-one inbound
marketing software, which they describe as the only marketing tool their
customers need. Those customers agree —10,000 of them, from SMBs to
enterprises, rely on HubSpot’s SaaS offering to engage their audiences
through smart and personalized content generation, social media
monitoring and publishing, lead nurturing, email marketing, and
analytics.

Innovative marketing tools require sophisticated software and
high-performance infrastructure. HubSpot has scaled to meet this need by
combining a traditional managed environment, a public cloud environment,
and — most recently, for its highest computing demands — an
[OpenStack<sup>&reg;</sup>](http://www.rackspace.com/cloud/openstack/)-based
[hybrid cloud](http://www.rackspace.com/cloud/hybrid/) within Rackspace,
boosting their performance and quality of service. This new architecture
has proved itself in action — according to O’Neill, “We were able to
gain four times the efficiency of public cloud for half the cost.”

### An Evolving Relationship

A Rackspace customer since 2007, HubSpot initially started with
[dedicated hosting](http://www.rackspace.com/managed_hosting/dedicated_servers/).
As their platform and customer base grew, they enthusiastically adopted
[public cloud](http://www.rackspace.com/cloud/public) technology,
shifting to a continuous integration and deployment model that allowed
them to deploy production code dozens of times a day. Along with
aggressive business growth came new demands for performance and uptime,
leading the company to a [hybrid
solution](http://www.rackspace.com/cloud/hybrid/) combining public and
private cloud to optimize for the demands of their employees and customers.

HubSpot became the first user of
[RackConnect<sup>&reg;</sup>](http://www.rackspace.com/hosting_solutions/hybrid_hosting/rackconnect/)
at Rackspace, a product that integrates dedicated hosting and public
cloud resources. They were also among the first to adopt OpenStack-based
[Rackspace Private Cloud](http://www.rackspace.com/cloud/private/),
which provided the expertise, support model, and the control portions of
their application needed without sacrificing the speed and flexibility
necessary for their continuous deployment strategy.

OpenStack also aligned with HubSpot’s commitment to the open-source
community. The platform represented their first viable chance to embrace
an open-source cloud operating system that could handle their future
growth and scale, allowing them to extend their usage of open-source
technologies below the application layer into their infrastructure and
computing layer.

### A Fully Automated Hybird Cloud Solution

HubSpot’s deployment strategy allows them to leverage multiple
environments, assigning workloads according to mission criticality and
performance requirements. It starts with a baseline server image
configured to run on either physical or virtual hardware. Deployment
automation tools such as Puppet are used to push the cloud operating
system and application stack into production. “We do not put anything
into production unless it is automated,” says Craig Tracey, DevOps lead
for Hubspot. “Automation is critical to everything that we do. We build
a lot of our failure-recovery mechanisms into the application itself,
and we would not be able to do any of this without APIs.”

The result is an application that is both self-aware and self-reporting,
and common APIs such as those provided by OpenStack give HubSpot the
ability to deploy on public or private infrastructure with no
application rework. This capability allows them to optimize performance
by running applications wherever they run most efficiently. “Our
application literally does not care if it’s running on bare metal or in
the cloud, whether that be private or public,” Tracey says.

“People always look for a price angle on public vs. private. We actually
look at it as the SLA that we’re offering and the quality of service
we’re offering,” O’Neill explains. “What’s beautiful about OpenStack is
that we can choose among environments and have the right service level
and the right quality of service on each of those, based on our
understanding of those workloads. For a web hosting platform, which has
the most mission-critical uptime and performance, we leverage a fully
managed environment. Then there is middleware that bridges those
mission-critical front-end apps with our large-scale, backend, big-data
apps. Our high throughput, big data, high-performance environment is
less about response time and more about scale, so HubSpot tends to fully
control that environment, because it’s bare metal.”

### Dedicated To Real-Time Analytics

HubSpot’s analytics engine, powered by [Apache
Hadoop](/how-to/getting-started-with-apache-hadoop-on-rackspace-cloud),
proved to be well suited to physical hardware, and once again, OpenStack
provided a solution for this need. “For the analytics engine, we’re
using the newly released [OpenStack Bare Metal
driver](https://wiki.openstack.org/wiki/Baremetal),” says Tracey.

“That gives us the flexibility to use the same tools that we use in the
cloud to stand up Hadoop instances on physical servers.”

HubSpot’s OpenStack implementation manages approximately 150 Hadoop data
nodes running on Dell R720 servers configured with 128 GB of RAM and 16
TB of local storage. These specifications allow HubSpot to achieve a
lower cost per GB than offered on public infrastructure and analyze
billions of data points at near real-time. “We can take big data and
stream that right into our web applications,” explains O’Neill. “That
can’t happen in a high-latency, low-cost commoditized infrastructure. It
requires low-latency, medium-cost private infrastructure.”

Private environments also provide HubSpot engineers greater ability to
troubleshoot their application when things go wrong. “When we look at
the private environment, we know what’s going on,” O’Neill says. “We
have the stethoscope and the visibility to understand the problem, and
it really comes down to, ‘Is it a facilities issue, power, network, or
application issue?’ In a public cloud, you’re missing those first three;
you really only know if it’s an application issue or not. We like to
think about it as if we have control over the entire stack.”

### Growing with Fanatical Support<sup>&reg;</sup>

The company has found that Rackspace accommodates their rapid expansion
and offers the range of products they needed to continue evolving. “As a
fast-paced, hypergrowth startup,” O’Neill says, “Rackspace has always
created support programs and teams that met that aggressive growth.”

The Rackspace relationship has also allowed HubSpot to keep their
deployment team lean despite continual pressure to keep up with the
business’ growth. Tracey explains, “My automation team is about 10
engineers for about 100 application developers, which shows that you can
use a small number of engineers to power a large development
organization if you’re leveraging the cloud. We think of engineers at
Rackspace as filling the gaps of the things that we’re either incapable
of doing or not interested in doing, and there’s been a number of
scenarios where they’ve helped us tremendously.”

“I truly believe that our [support with
Rackspace](http://www.rackspace.com/whyrackspace/support/) is
second-to-none,” O’Neill says. “Any time I’ve ever had an issue, I can
pick up the phone, or anyone on our team can pick up the phone and get a
Racker within minutes who knows exactly what to do and how to help us.
We have not experienced that with anyone else.”
