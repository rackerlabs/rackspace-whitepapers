---
permalink: critical-media-recovers-from-disaster-with-rackspace-hybrid-cloud/
audit_date:
title: Critical Media Recovers from Disaster with Rackspace Hybrid Cloud
type: case_study
created_date: '2013-10-15'
created_by: Rackspace Support
last_modified_date: '2017-03-21'
last_modified_by: Cat Lookabaugh
product: White Paper
product_url: white-paper
---

<a href="http://www.critical-media.com/">
   <img src="{% asset_path UseCases/critical-media-recovers-from-disaster-with-rackspace-hybrid-cloud/criticalmedia.png %}" width="296" height="133" />
</a>

**CUSTOMER’S BUSINESS:**
Critical Media is one of the world’s largest media-listening platforms.

**CHALLENGES:** Lacking geographic diversity in its disaster recovery
plan, Critical Media recovered from Hurricane Sandy by rebuilding in the
Rackspace public cloud.

**RACKSPACE<sup>&reg;</sup> SOLUTION:** [Rackspace Cloud
Servers](http://www.rackspace.com/cloud/servers/), [Private
Cloud](http://www.rackspace.com/cloud/private/).

**BUSINESS OUTCOME:** Combining private and public cloud resources from
Rackspace has given Critical Media a DR solution and an agile, reliable
platform without the economic drawbacks of running a public cloud-only
environment at scale.

### Escaping Hurricane Sandy

Offering a growing portfolio of interconnected products, Critical Media
is one of the world’s largest media-listening platforms. Critical Media
captures live TV and radio broadcasts through more than 200
geographically distributed points of presence, and leverages highly
advanced speech-to-text capabilities to make live radio and television
searchable in real-time.

Critical Media has over 1,500 SaaS clients and large PaaS partners,
including many political campaigns and Fortune 1000 corporations. The
company operates its own data center in New York City, and when
Hurricane Sandy struck in late October 2012 they had to move their
entire production environment to the [Rackspace Open
Cloud](https://www.rackspace.com/). Since then, Critical Media has
evolved to a [hybrid cloud
solution](http://www.rackspace.com/cloud/hybrid/) by rebuilding their
data center with [Rackspace Private
Cloud](http://www.rackspace.com/cloud/private/) powered by
[OpenStack<sup>&reg;</sup>](http://www.rackspace.com/cloud/openstack/). They
continue to use Rackspace Open Cloud for their geographic diversity disaster
recovery plan, on-demand production scale, and proof of concept work.

### From Hypothetical to Mission-Critical

The company began in 2005 on bare metal servers and, over time,
transitioned to a manually configured mix of virtual machines. They knew
they needed a more scalable infrastructure to support future growth.

“Deploying virtual machine servers by hand is not a good practice, but
it is more efficient than deploying bare metal servers. Virtualization
provides efficiency gains in that multiple VMs take better advantage of
available CPU, power, and space. But manually configuring and deploying
these VMs doesn’t scale,” says Tom Gilley, executive-in-residence at
Critical Media.

Critical Media was confident that a [public
cloud](http://www.rackspace.com/cloud/public) only option would not make
economic sense given the low product cost basis requirements and the
enormous processing load.

“We process about 40 hours of video every minute,” Gilley says. “That’s
huge, that’s a Google YouTube-class ingest and distribution solution. We
don’t store it like YouTube does, but the scale of handling that amount
of video and resulting meta data is huge for a company like ours.”

“You hear the rhetoric about public cloud that’s absolutely true,” he
says. “For venture capital startups, it’s great, because you have no
capital expenditure and you can trial and start something fast. However,
what many companies learn is that as you scale, relatively higher per
unit costs in the public cloud can eat into your profit margin.”

Due to the public cloud costs, Critical Media elected to forgo public
cloud for production. Instead, they built out their own data center,
which they called the Mission Critical Data Center (MCDC).

Knowing that geographic diversity is necessary to reduce vulnerability
due to natural disasters, Critical Media planned for public cloud as a
supplement to their infrastructure. They evaluated several proprietary
and [open source cloud
options](http://www.rackspace.com/cloud/openstack/). Gilley says, “We
had experience and were involved with the community that was building
around OpenStack, so we made a bet on OpenStack. We liked Rackspace
because it has a good legacy data center foundation and made major
investments in public/private OpenStack technologies. I had built out in
Rackspace in a past company, so I was comfortable with its business
strength and its level of support.”

Critical Media had already gained experience with Rackspace Open Cloud
for proof of concepts and began planning for production services in
Rackspace Open Cloud. However, due to cost constraints and conflicting
priorities, the engineering for deployment of production services to
Rackspace Open Cloud was delayed. Critical Media, as many other top tier
internet providers in the famous IT building, were betting on the
available redundant systems — specifically the in-building generator for
failover.

<img class="right" src="{% asset_path UseCases/critical-media-recovers-from-disaster-with-rackspace-hybrid-cloud/criticalmedia-2.png %}" width="222" height="278" />
Then the natural disaster they worried about, [Hurricane
Sandy](http://en.wikipedia.org/wiki/Hurricane_Sandy), hit. “Downtown
took full frontal attack of Hurricane Sandy’s Atlantic Ocean surge. Our
building, as many others, was literally under ocean water,” says Gilley.
“Basement levels completely flooded to several feet of saltwater into
the lobby. It was an epic event.”

“Our operations team had evacuated,” he continued, “but we had friends
in the building that stayed, and they gave us an assessment of the
situation — it was dire. The fuel and electrical subsystems are in the
basement, so that meant when it flooded, we had no fuel for our
generator and basically had no power. When our battery backup dies we
would be completely down: salt water and electrical subsystems do not
mix. This was not going to be something that our building and data
center would be able to soon recover from.”

### All Hands on Deck to Get Back Up and Running

It was the week before the presidential election, and both the Romney
and Obama campaigns were clients. Critical Media could not afford to
stay dark. Those who could get to the company’s midtown headquarters
did. “The team made the risk decision that we were going to have to do
something really dramatic,” Gilley says. “We decided, let’s refactor the
stack here, on this floor, and move it into Rackspace; let’s OpenStack
it.”

He continues, “Just as the hurricane was passing and the streets were
still flooded, Gilley dispatched his son, who was near and with car for
the apocalyptic trip to pick up a few of the critical bare metal
hypervisors. The daunting plan was to rebuild the virtual machines that
we had at MCDC and deploy them into Rackspace Public Cloud. The Critical
Media applications, systems and operations team that could make it into
the office or log onto the internet worked around the clock, taking
turns sleeping to spin up nearly 200 servers at Rackspace. “We were back
in business. It was incredible. The teamwork was amazing. Half of
Manhattan was still without power and the Mission Critical Data Center
would not have power for many weeks. We made the right decision.”

“We were on the phone with our Rackspace account manager often as we ran
up against allocation limits and support was amazing,” he says. “They
understood the sentiment of the folks here, how rough it was for us, and
escalated our situation for rapid response.”

### Adding Openstack On-Premise for Hybrid Cloud Capabilities

As Critical Media engineers raced to spin up servers and keep production
going, they got a crash course in OpenStack. “The application
development team fell in love with the ability to spin up VMs easily,”
says Gilley. “They became enamored with that opportunity. Perhaps too
enamored, as it put pressure on the systems and operations team to come
up to speed on the nuances of OpenStack, which they did.”

With major products operating out of Rackspace Open Cloud, the company
now had an opportunity to create a hybrid cloud and to deploy OpenStack
into the environment at MCDC. They planned to do it on their own in
three months, but by month two they realized they needed some help. “We
called Rackspace and they told us, ‘We’ve got a new group that will
install and manage OpenStack in your facilities. We call it private
cloud.’”

Due to Critical Media tight time constraints, the new [Rackspace Private
Cloud](http://www.rackspace.com/cloud/private/) group flew in, installed
OpenStack at MCDC, providing OpenStack training for Critical Media
staff, all within a week of contact. Rackspace was and is on-call for
escalations and training to assure all teams were aligned. “We’ve passed
six months with the Rackspace managed Private Cloud,” says Gilley, “and
I expect Critical will continue with Rackspace managing the private
cloud.”

Once the private cloud was up and running, the company began the process
of migrating some of their services back to MCDC. The team is also
developing ways to use public cloud to burst excess load, which Gilley
calls peaking. “We have some services, like video transcoding and
speech-to-text, where we can’t predict the demand until it starts to
trend up, or we have a new partner on boarding before the capital
investment. Those are services we would peak to the cloud,” says Gilley.
While they plan to operate their steady-state load primarily from their
own private cloud, the public cloud will continue to be used as their
disaster recovery solution, peaking and PoCs.

While Critical Media continues growing their business, they now have a
geographically diverse disaster recovery plan in place and a path to
scale their infrastructure as they take on new business. Combining
private and public cloud resources from Rackspace gave them an agile and
reliable platform with none of the economic drawbacks of running a
public cloud-only environment at scale. Hopefully a disaster won’t
strike them twice; but if it does, they’ll be prepared.
