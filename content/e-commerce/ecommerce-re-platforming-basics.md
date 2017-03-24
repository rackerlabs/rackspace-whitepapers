---
permalink: ecommerce-re-platforming-basics/
audit_date:
title: Ecommerce Re-Platforming Basics
type: whitepaper
created_date: '2014-01-06'
created_by: Rackspace Support
last_modified_date: '2017-03-10'
last_modified_by: Cat Lookabaugh
product: Ecommerce
product_url: ecommerce
---


<img src="{% asset_path ecommerce/ecommerce-re-platforming-basics/Ecommreplatforming-2_0.png %}" width="194" height="195" />

### Introduction

Over the past decade, buying patterns and technology advances have
radically altered business goals and competitive realities. Consumers
demand faster, more engaging shopping experiences across multiple
channels—in-store, of course, but increasingly also mobile and online.
And the impact of a negative customer experience is significant: One
Google survey reveals that more than half (52%) of consumers are less
likely to engage with a business after a single bad mobile
experience<sup>1</sup>. If a customer has to wait longer than a split second for
a webpage to load, or if that site cannot deliver a rich, multichannel
experience, that customer could be lost forever. Already, many retailers
are realizing that their current platforms are no longer suited to their
demanding digital customers’ needs, not to mention their own.

Given the project scope and the potential consequences, re-platforming
may seem daunting. This guide offers valuable insights into
re-platforming, including how to determine if it’s time to make a move,
what factors need to be considered to ensure success, and which common
architectures meet the needs of most enterprises.

### Knowing when the time is right

According to a recent Forrester Research survey, more than half of
ecommerce executives (54%) say re-platforming is their top priority over
the next 12 months<sup>2</sup>. That’s not surprising, given another Forrester
survey<sup>3</sup> that indicates that 81% of online retailers are currently
using a self-built or licensed on-premises solution, yet 74% fear their
existing solutions won’t scale with their growth plans. And almost half
(46%) of retailers report difficulty hiring the staff needed to manage
their licensed platform or to continually tweak their internally built
ecommerce platform. Ultimately, this means organizations are expending
significant time and effort keeping up with market demands and running
the underlying infrastructure.

The evolution of traditional retail into digital channels highlights the
need for performance. The infrastructure required to deliver the digital
experience is becoming increasingly complex, with demands for enhanced
usability, responsiveness, and agility. This is occurring at a time when
resources are spread thin across the organization, driven by demands
like big data, internal user needs, and disaster recovery. Trying to
push into the new digital reality with older systems results in sluggish
performance and widespread inefficiency.

Most ecommerce stores re-platform every two to three years<sup>4</sup>. However,
the timeline for re-platforming will vary based on the retailer’s unique
customer experience and performance goals. Re-platforming an ecommerce
operation is a huge undertaking, encompassing both components of the
ecommerce store:

- Evaluating the ecommerce platform: Can the current platform support future
initiatives, or is it hindering existing plans?
- Evaluating the hosting solution: Should the organization maintain an in-house
platform, move everything to a service provider, or employ a hybrid solution?

Both elements are equally important to an ecommerce store’s success.
Putting a resource-heavy ecommerce platform on subpar infrastructure can
be just as disastrous as a restrictive ecommerce platform on
enterprise-level metal.

**TOP 5 REASONS CITED FOR ECOMMERCE PLATFORM REPLACEMENT5:<sup>5</sup>:**

-   58%: To improve business agility
-   56%: To lower overall operational and ownership costs
-   51%: To align the cost of ownership against our online revenues
-   51%: To support our multichannel initiatives
-   51%: To speed up deployment of new features and functionality

### Time for action

In the face of the changing behavior of buyers, existing ecommerce sites
may be exhibiting signs that their glory days are behind them. Signs to
look for include:

- Unacceptable response times or frequent outages
- Inability to keep up with competitors’ functionality
- Stalled omnichannel sales strategies caused by inadequate integration between
channels
- Difficulty complying with industry and government compliance mandates
- Cost-prohibitive improvements needed to fix gaps in the system

Organizations may face new requirements that didn’t exist or that have
changed markedly from when the [ecommerce
platform](http://www.rackspace.com/ecommerce-hosting/) was built. As the
product catalog grows, database requirements may change. An increase in
concurrent users influences Web server size and configuration. Operating
in a global environment may require the ability to [localize
content](http://www.rackspace.com/cloud/files/technology/?page=cdn),
display and handle transactions in the buyer’s local currency, and
manage local compliance requirements.

Ecommerce operations dealing with physical and digital products or
software-as-a-service offerings have different considerations than a
pure online product retailer. Furthermore, they may need multiple types
of payment capabilities, ranging from one-time to subscription-based
models. Just as important as billing methods are the requirements for
dealing with renewals, expired cards, refunds, and channel issues such
as affiliate marketing commissions.

Of course, any organization considering an ecommerce re-platforming
project must account for momentous changes in mobile and social media
technologies that have occurred since the previous platform was
implemented. By 2017, eMarketer predicts, nearly 80% of digital buyers
will be shopping on a mobile device, with sales from tablets
representing nearly 70% of purchases<sup>6</sup>. Recently, Facebook ad
click-through rates ballooned to 275% while cost-per-click dropped 40%,
making social selling another vital imperative to consider in the
re-platforming process.<sup>7</sup>.

Once the need to re-platform is acknowledged, it’s critical to establish
project goals. But in order to develop those goals, the team must craft
a strategy appropriate for the company’s unique business needs and
consider the demands of multiple stakeholders. Business leaders may be
focused on issues such as conversion rates and customer retention, while
technologists may be more concerned with security, compliance, and
performance. And, of course, there is the customer, who wants fast
access to quality content and ease of completing a transaction.

A successful project balances those goals. “Ultimately, the issue of
re-platforming an existing ecommerce system comes down to determining
the investment required to meet the organization’s goals. There is more
to cloud economics than the oft-touted ‘convert CAPEX to OPEX,’”
explains [Mahesh Gandhe, Senior Solution Marketing Manager at
Rackspace](http://www.rackspace.com/blog/author/mahesh-gandhe/).

Chris Vitale, director of ecommerce at [Pep
Boys](http://stories.rackspace.com/customers/pep-boys), describes the
tangible, future state that most retailers are pursuing but can only
attain by re-platforming their systems: “We’re going to have a multi-
channel experience where someone interacts with us online, an
expectation is set, then they continue through to the store and have an
entire, almost traditional, in-store experience with us.”

### Ecommerce platform selection

The ecommerce platform consists of the software used to manage the look
and feel of the site, inventory, payment processes, and so on. The
platform selection is a critical driver of the hosting choice, so there
is a lot to consider. This list offers a foundation for platform
requirements, although additional concerns unique to the business will
undoubtedly be uncovered during the selection process.

- **PRODUCT MERCHANDISING:** Controlling how products and information are
displayed, and how discounts are presented to the customer and processed in a
payment system; presenting product customization requirements; displaying global
product content.
- **DATA COMPATIBILITY:** Parsing of multiple data points simultaneously for a
split-second redirect to dynamic pages or to deliver custom content, allowing
incompatible data types or data stored in silos to “talk” to each other, not
hindering customer  experience initiatives.
- **PAYMENT SYSTEM:** Supporting trials with opt-in/opt-out capability, physical
product purchasing, access management for SaaS products, support for global
payments, shopping cart compatibility.
- **CHANNEL MANAGEMENT:** Features to differentiate customer segments, serve
dynamic content based on customer profile, price list management to offer
alternative pricing to selected customers, global compliance management.
- **MOBILE FUNCTIONALITY:** Creating high-impact mobile interfaces across
smartphones and tablets, real-time processing, mobile shopping cart optimization.
- **MARKETING:** Tools for customer contact testing, multivariate testing
capabilities, acquisition/retention marketing (PPC campaigns, SEO, email list
management), support for affiliate programs.
- **CUSTOMER CONTACTS:** Ability to customize and send transactional emails for
account creation, order-related contacts, localized content, new product versions.
- **HOSTING MANAGEMENT:** Access to scalable, dedicated bare-metal components;
implementing cloud expandability for bursting; meeting PCI compliance; building
in redundancy for disaster recovery.

### Hosting Selection

Every company has unique business and IT requirements, and there are
many solutions that may be a good fit. Sometimes, the best configuration
for a business includes more than one option. When evaluating hosting
options, it’s important to consider whether potential integration and
deployment issues are aligned with the organization’s IT resources and
experience. There’s a huge difference between a general cloud provider
that only offers raw infrastructure—leaving organizations to figure out
how to deploy and connect the ecommerce platform—and hosting specialists
that can provide expertise around unique workloads. Choosing a hosting
partner with specialized experience in ecommerce platforms and
infrastructure helps the organization sort out the complexities to
architect an optimal solution.

Organizations should review their options against their strategy to
choose the right combination. Options include:

- **CLOUD:** Takes advantage of massively scalable infrastructure and
preconfigured or highly customizable environments to reduce hardware and
management burdens. Choose a [public cloud](http://www.rackspace.com/cloud/)
for low cost or a [private cloud](http://www.rackspace.com/cloud/private/) for
workloads subject to stringent security or compliance mandates.
- **ON-PREMISES:** Puts the burden of hardware, security, performance, and scale
on the IT team and budget. This option delivers ultimate control—as well as all
the headaches that accompany being responsible for the entire ecommerce
infrastructure.
- **HYBRID:** Combines on-premises or dedicated hardware with the resources to
achieve cloud efficiencies while meeting certain security or compliance needs.
In a [hybrid cloud environment](http://www.rackspace.com/cloud/hybrid/), a
retailer can move certain workloads, like email or content delivery, to the
cloud while maintaining control over other critical systems best run on dedicated
or on-premises equipment.

“I can’t think of a scenario where the ‘all-on-premise’ solution would
be optimal,” says Gandhe. “With that option, you either have to
provision for the peak periods—meaning you’re overinvesting in capacity
for the other periods—or you provision for normal day-to-day traffic and
risk being unable to meet spikes in demand.”

Steve Vitale, director of ecommerce at Spencer Gifts, echoes Gandhe’s
statement: “Our traffic and business can increase 100 times to 1,000
times what they were in the off-season. We have to scale on and off, but
we also have to try not to carry too much infrastructure in the
off-season. That’s why we went with the Rackspace Hybrid Cloud based on
RackConnect. We split our application between a dedicated private
infrastructure for our checkout process, and we use the public cloud for
product descriptions, prices, and other information.”

### Making the move

Based on the knowledge and expertise gained while serving some of the
top retailers in the United States, [Rackspace Digital, a practice
specializing in](http://www.rackspace.com/pt/digital)[content
management,](http://go.rackspace.com/digital#content-target)[mobile,
and](http://go.rackspace.com/digital#mobile-target)[ecommerce
hosting](http://go.rackspace.com/digital#commerce-target), has developed
four reference architectures for ecommerce solutions built on
[Magento](http://www.rackspace.com/ecommerce-hosting/magento/) or
[Oracle Retail](http://www.rackspace.com/oracle-retail):

- **BASIC:** A pure cloud configuration with both Web server and database
residing in the cloud, with the ability to add Web and database servers for
scalability.
- **INTERMEDIATE:** A three-tier, cloud-based architecture using dedicated
servers for both Web and data-base servers. Single Web and database servers are
segmented behind a physical firewall, and customer credit card information is
stored using the third-party payment gateway.
- **ADVANCED:** A three-tier, hybrid (cloud + dedicated) architecture that
relies on transactional data stored in dedicated servers behind a physical
firewall, with the ability to burst into cloud servers for holiday spikes or
sudden increases in load.
- **PREMIER:** A three-tier, self-contained, PCI-capable hybrid (cloud +
dedicated) architecture designed to support the highest number of online
transactions using a resilient, highly available infrastructure with failover
capabilities at every layer of the solution.

### What is Rackspace digital?

Best practices, architecture guidance, and proactive support for leading
digital platforms around:

- **WEB CONTENT MANAGEMENT SYSTEMS:** Application and infrastructure hosting
expertise for leading WCMS platforms including WordPress, Drupal, Sitecore,
Adobe, and Ektron.
- **ECOMMERCE SOLUTIONS:** Open, hybrid infrastructure and services for building
secure, scalable, and highly available ecommerce stores built on Magento, Oracle
Commerce, hybris, and Intershop.
- **MOBILE SERVICES:** Flexible, mobile infrastructure and application platform
hosting expertise in Node.js, FeedHenry, and Mutual Mobile for highly scalable,
reliable mobile experiences.

### Bringing it all together

An online store is a company’s window to the world. It needs to stand up
to daily traffic and unexpected spikes, while offering customers a safe
and secure place to shop. A core component, of course, is enabling
customers to make purchases using credit cards. If the number of credit
card transactions is relatively small, a third-party payment gateway is
economical and may be the best option. If credit card transaction volume
is very high, though, it may be more cost-effective to store credit card
information in the data center of a service provider that can meet [PCI
compliance requirements](http://www.rackspace.com/ecommerce-hosting/pci/).

Catalog display logic and shopping cart logic may both reside on the
same server, in a two-tier architecture: The first tier is composed of a
combined Web and application tier; the second, a database layer. Another
approach is a three-tier architecture. In this case, the Web layer is
the first tier, the app layer is the second, and the database layer is
the third.

“We generally find that ecommerce operations start with a two-tier
architecture, then, as the business grows, they start separating two
layers so that each tier can scale independently,” explains Gandhe.
“Deciding between a two-tier and a three-tier reference architecture
really depends on scalability needs for the catalog display and shop-
ping cart.”

Display logic and shopping cart logic can either run on [cloud
servers](http://www.rackspace.com/cloud/servers/) or [dedicated
servers](http://www.rackspace.com/managed_hosting/dedicated_servers/).
Cloud is both persistent and highly elastic, with speedy provisioning to
scale on demand. Dedicated servers, on the other hand, provide a
single-tenant environment for exclusive usage.

The type of database and volume of I/O transactions will dictate which
database technology is right for an ecommerce operation. “Cloud
databases are the best option if you want to use a MySQL database and
want Rackspace to manage it for you,” says Gandhe. “If you want to use a
database that supports virtual environments, then you can run your own
database on cloud servers. If your database of choice doesn’t support
virtualization, or for the highest I/O performance, we recommend running
your database on a dedicated server.”

### Conclusion

Ultimately, re-platforming an ecommerce system comes down to determining
the investment required to meet the business goals. Factors such as the
pattern of demand, [total cost of
ownership](http://www.rackspace.com/enterprise-cloud-solutions/advisory-services/#tco-workshop),
and transformation costs need to be considered in any financial analysis
of a potential solution. Choosing the ecommerce platform software
balances the cost of licensing and management against the benefit of
instant access to the tools needed to build and grow a competitive site.
Sufficient variability in demand is required to realize cost savings
using a public cloud hosting model; flat workloads are cheaper on
dedicated infrastructure over a fixed contract term.

Transforming infrastructure can be costly and time-consuming, and
relying on internal skills may not be ideal. “In almost all cases, I’d
strongly recommend that a company approaching the re-platforming stage
look into working with a partner that is able to apply skills and
resources that are likely in short supply internally,” says Gandhe.

<strong>LEARN MORE ABOUT RACKSPACE DIGITAL SOLUTIONS AT
[GO.RACKSPACE.COM/DIGITAL](http://www.rackspace.com/pt/digital)

</strong>

**Sources:**

<sup>1</sup>
[http://googlemobileads.blogspot.com/2012/09/mobile-friendly-sites-turn-visitors.html](http://googlemobileads.blogspot.com/2012/09/mobile-friendly-sites-turn-visitors.html%20)

<sup>2</sup>
[http://blogs.forrester.com/peter_sheldon/13-08-01-commerce_technology_continues_its_
bull_run](http://blogs.forrester.com/peter_sheldon/13-08-01-commerce_technology_continues_its_%20bull_run)

<sup>3</sup> [Understanding TCO When Evaluating Ecommerce Platforms, 2012,
Forrester
Research.](http://www.slideshare.net/Carnage3604/forrester-tco-comparison)

<sup>4</sup> [Understanding TCO When Evaluating Ecommerce Platforms, 2012,
Forrester
Research.](http://www.slideshare.net/Carnage3604/forrester-tco-comparison)

<sup>5</sup> [Understanding TCO When Evaluating Ecommerce Platforms, 2012,
Forrester
Research.](http://www.slideshare.net/Carnage3604/forrester-tco-comparison)

<sup>6</sup>
[http://www.emarketer.com/Article/Smartphones-Tablets-Drive-Faster-Growth-Ecommerce-
Sales/1009835](http://www.emarketer.com/Article/Smartphones-Tablets-Drive-Faster-Growth-Ecommerce-%20Sales/1009835)

<sup>7</sup>
[http://success.adobe.com/assets/en/downloads/whitepaper/13926_di_social_sentiment_
v10.pdf](http://success.adobe.com/assets/en/downloads/whitepaper/13926_di_social_sentiment_%20v10.pdf)
