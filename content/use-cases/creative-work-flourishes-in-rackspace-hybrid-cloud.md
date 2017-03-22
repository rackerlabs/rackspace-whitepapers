---
permalink: creative-work-flourishes-in-rackspace-hybrid-cloud/
audit_date:
title: Creative Work Flourishes in Rackspace Hybrid Cloud
type: whitepaper
created_date: '2012-09-20'
created_by: Rackspace Support
last_modified_date: '2017-03-21'
last_modified_by: Cat Lookabaugh
product: Use Cases
product_url: use-cases
---

<a href="http://www.behance.com/">
   <img src="{% asset_path use-cases/creative-work-flourishes-in-rackspace-hybrid-cloud/behance1.png %}" width="309" height="78" />
</a>

**CUSTOMER’S BUSINESS:** Behance is the world’s leading online platform for
showcasing and discovering creative work.

**CHALLENGES:** Behance needed a hybrid infrastructure that could keep
pace with its rapid growth.

**RACKSPACE<sup>&reg;</sup> SOLUTION:** [Rackspace
Hosting](http://www.rackspace.com/),
[RackConnect<sup>&reg;</sup>](http://www.rackspace.com/hosting_solutions/hybrid_hosting/rackconnect/),
[Rackspace Cloud Servers](http://www.rackspace.com/cloud/servers/),
[Rackspace Private Cloud](http://www.rackspace.com/cloud/private/)

**BUSINESS OUTCOME:** Building in the [Rackspace Hybrid
Cloud](http://www.rackspace.com/cloud/hybrid/) allows Behance to deliver
speedy image processing, run real-time activity feeds, and store massive
amounts of media.

Behance leverages an array of Rackspace technologies to deliver the
world’s leading portfolio platform.

Behance is the world’s leading online platform for showcasing and
discovering creative work. The site allows creative professionals to
upload work to online portfolios, which others can find and browse
through an array of discovery features. Since 2007, Behance’s
design-centric approach has attracted more than a million users and now
generates 100 million page views per month.

Behance was acquired by Adobe in December of 2012, a move that heralded
even more prodigious expansion. Chris Henry, Head of Technology at
Behance, says, “As we become more and more successful, we need to be
able to scale. We need to be able to grow our infrastructure and
continue to iterate and evolve.” A combination of Rackspace hybrid
architecture, Managed Operations, and automated provisioning allows them
to deploy the right infrastructure for their company’s changing needs.

### Coming to hybrid cloud

Behance first considered adding cloud to its dedicated servers as a way
to speed up one of its service offerings. Henry explains, “We were
having problems processing images. It’s one of the most important things
that we do, and the one physical server we had that was dedicated to it
was totally overrun. It was one of those moments where we knew we had to
act quickly, otherwise we were going to be dead in the water for hours
or days.”

“We had already kind of set up the hybrid environment—we had the F5 load
balancer, we had a cloud account—and it was at that moment where we
said, we need to be able to get servers to do this right now,” he
continues. An F5 distributes load across both dedicated and cloud
servers, making additional computing resources available in minutes. “We
realized that this kind of infrastructure was going to work, because
once we started bringing those servers up and adding them to the
application, things improved immediately. Our users were able to process
images faster and it was also more reliable because when one server had
an issue, the other servers picked it up.”

“We had three or four physical servers at that time, and we added two or
three Cloud Servers to begin with,” Henry says. “As we realized it was
working, we started adding more. Over the past few years, we’ve grown to
having 80 physical devices and more than 170 cloud servers on the
Rackspace Public Cloud.” A combination of Managed Operations and
automated provisioning allows them to stay on top of their
infrastructure as it grows. Henry explains, “What we discovered was that
you could automate all of the provisioning of servers, either via
scripts or via tools like Chef or RightScale. So once we built out a
server, we were able to figure out all the steps that we needed to take
and continually reuse those scripts.”

Behance is also beginning to use Rackspace Private Cloud, powered by
[OpenStack<sup>&reg;</sup>](http://www.rackspace.com/cloud/openstack/). Henry
explains, “We’re starting to work with OpenStack a lot, and we’re really
enjoying working with it. We want to take the flexibility of having
things that are in the public cloud and combine it with our own physical
hardware, so we can choose the underlying hardware, yet still have the
flexibility to be able to spin up a dozen VMs if we need to. We’re
taking away all of the classic limitations of cloud, getting all the
benefits of great hardware, and coupling them with the convenience of
working in a cloud-type environment.”

### Aligning workloads with best-fit resources

What began as a way to speed up image processing has since allowed
Behance to create a complex architecture to handle a variety of tasks.
Henry explains, “The really cool thing about the hybrid infrastructure
that we have is that we have choices. Our databases absolutely need
custom hardware, they need SSDs, they need custom CPUs, and we need to
make sure that our disks are configured in the proper RAID arrays. We’re
able to tweak things at that level, which isn’t always possible in the
cloud.”

“On the flipside,” he continues, “if we want 50 servers to process
images, cloud is a great fit. You have as much CPU as you need at your
fingertips when you need it. We really kind of have the best of both
worlds, and with RackConnect, we have only a few milliseconds of latency
between the two environments. It really is a great fit for someone like
us who’s doing a lot of image processing and very intense data
processing all at the same time.”

Asked if he thinks a cloud-only or dedicated-only solution could deliver
the same results, Henry says, “Having one but not the other doesn’t
always make sense. If we were just on the physical side, it would likely
be too expensive. If were just on the cloud, we probably wouldn’t get
the performance we need.”

### Mixing databases

Behance runs a standard LAMP stack for their application, and MySQL is
supplemented by MongoDB for database services. Their hybrid architecture
means that these databases can work in tandem despite running in
distinct environments. Henry says, “With MySQL, we had a lot of great
resources on the Rackspace side. We had the Rackspace DBA team and
access to hardware choices that we didn’t have in the cloud, so we run
all of that stuff on the physical side. For denormalized things,
real-time feeds and things of that nature, we use MongoDB.”

“MongoDB required us to add and remove things as the cluster grew,” he
continues. “We needed to add shards, and doing that in a physical
environment is much more difficult and definitely more expensive. You
need to actually either provision servers ahead of time or you need to
have the lead time and have to actually do a lot more careful
forecasting. The cloud is a really good fit for that, because if you
become successful overnight, you can spin up those servers that you need
to handle the load.”

Behance also leverages hybrid cloud architecture for storage and image
services. Network Attached Storage from Isilon handles customer image
uploads, while Rackspace Cloud Block Storage provides the backend for
their MongoDB clusters. The combination supports millions of objects,
nearly 80 file systems, and consumes over 11 terabytes of
high-performance SSD storage.

### Fanatical Support<sup>&reg;</sup>

Throughout their growth, Behance has found Rackspace to be an
indispensable complement to their business. Henry says, “When the team
was first formed, there were only two developers and we really had no
idea how to run a server or manage infrastructure. We arrived at
Rackspace because they had the [best service and
people](http://www.rackspace.com/whyrackspace/support/) willing to teach
us how to do these things, and as we’ve grown, that same relationship
has scaled.”

“As we are getting to the point where we need terabytes of storage,
people are helping us figure that out,” he continues. “As we get to the
point where we need an entire cluster of servers just to process images,
they’re helping us and suggesting ways that we can do it and build it.”

Rackspace has allowed Behance’s team to remain small and efficient.
“Rackspace is an extension of our team, and the reason we’ve been as
successful as we have is because we’ve been able to focus on building a
great product and not focus on building infrastructure,” Henry says.
“There’s always going to be people who do things better than us, and
Rackspace is a perfect example of that. They do infrastructure extremely
well, and they support us and enable us to build a great product.”
