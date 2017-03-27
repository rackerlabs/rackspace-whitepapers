---
permalink: understanding-the-cloud-computing-stack-saas-paas-iaas/
audit_date:
title: 'Understanding the Cloud Computing Stack: SaaS, PaaS, IaaS'
type: whitepaper
created_date: '2012-07-23'
created_by: Rackspace Support
last_modified_date: '2017-03-07'
last_modified_by: Cat Lookabaugh
product: Cloud Overview
product_url: cloud-overview
---

### Executive Summary

[Cloud Computing](http://www.rackspace.com/cloud/what_is_cloud_computing/)
is a broad term that describes a broad range of services. As with other
significant developments in technology, many vendors have seized the
term “Cloud” and are using it for products that sit outside of the
common definition. In order to truly understand how the Cloud can be of
value to an organization, it is first important to understand what the
Cloud really is and its different components. Since the Cloud is a broad
collection of services, organizations can choose where, when, and how
they use Cloud Computing. In this report we will explain the different
types of Cloud Computing services commonly referred to as Software as a
Service (SaaS), Platform as a Service (PaaS) and Infrastructure as a
Service (IaaS) and give some examples and case studies to illustrate how
they all work. We will also provide some guidance on situations where
particular flavors of Cloud Computing are not the best option for an
organization.

### The Cloud Computing Stack

Cloud Computing is often described as a stack, as a response to the
broad range of services built on top of one another under the moniker
“Cloud”. The generally accepted definition of Cloud Computing comes from
the National Institute of Standards and Technology (NIST) <sup>1</sup>. The
NIST definition runs to several hundred words but essentially says:
Cloud computing is a model for enabling convenient, on-demand network
access to a shared pool of configurable computing resources (e.g.,
networks, servers, storage, applications, and services) that can be
rapidly provisioned and released with minimal management effort or
service provider interaction.<sup>2</sup>

What this means in plain terms is the ability for end users to utilize
parts of bulk resources and that these resources can be acquired quickly
and easily.

NIST also offers up several characteristics that it sees as essential
for a service to be considered “Cloud”. These characteristics include;

- On-demand self-service. The ability for an end user to sign up and
receive services without the long delays that have characterized
traditional IT
- Broad network access. Ability to access the service via standard
platforms (desktop, laptop, mobile etc)
- Resource pooling. Resources are pooled across multiple customers <sup>3</sup>
- Rapid elasticity. Capability can scale to cope with demand peaks <sup>4</sup>
- Measured Service. Billing is metered and delivered as a utility
service <sup>5</sup>

More than a semantic argument around categorization, we believe that in
order to maximize the benefits that Cloud Computing brings, a solution
needs to demonstrate these particular characteristics. This is
especially true since in recent years there has been a move by
traditional software vendors to market solutions as “Cloud Computing”
which are generally accepted to not fall within the definition of true
Cloud Computing, a practice known as “cloud-washing.”

The following diagram depicts the Cloud Computing stack – it shows three
distinct categories within Cloud Computing: Software as a Service,
Platform as a Service and Infrastructure as a Service.

<img src="{% asset_path cloud-overview/understanding-the-cloud-computing-stack-saas-paas-iaas/cloudcomputestackimage1.png %}" />

In this report, we look at all three categories in detail. Here is a very
simplified way of differentiating these flavors of Cloud Computing.

- SaaS applications are designed for end-users, delivered over the web
- PaaS is the set of tools and services designed to make coding and
deploying those applications quick and efficient
- IaaS is the hardware and software that powers it all – servers,
storage, networks, operating systems

To help understand how these 3 components are related, some have used
the following transportation analogy.

    *By itself, infrastructure isn’t useful - it just sits there waiting
    for someone to make it productive in solving a particular problem.
    Imagine the Interstate transportation system in the U.S. Even with all
    these roads built, they wouldn’t be useful without cars and trucks to
    transport people and goods. In this analogy, the roads are the
    infrastructure and the cars and trucks are the platform that sits on top
    of the infrastructure and transports the people and goods. These goods
    and people might be considered the software and information in the
    technical realm. <sup>6</sup>*

It is important to note that while for illustration purposes this
whitepaper draws a clear distinction between SaaS, PaaS and IaaS, the
differences between these categories of cloud computing, especially PaaS
and IaaS, have blurred in recent months and will continue to do so.<sup>7</sup>
Nevertheless, with a general understanding of how these components
interact with each other, we will turn our attention in more detail to
the top layer of the stack, SaaS.

### Software as a Service

Software as a Service (SaaS) is defined as:

"... software that is deployed over the internet... With SaaS, a provider
licenses an application to customers either as a service on demand,
through a subscription, in a “pay-as-you-go” model, or (increasingly) at
no charge when there is opportunity to generate revenue from streams other
than the user, such as from advertisement or user list sales."<sup>8</sup>

SaaS is a rapidly growing market as indicated in recent reports that
predict ongoing double digit growth <sup>9</sup>. This rapid growth indicates
that SaaS will soon become commonplace within every organization and
hence it is important that buyers and users of technology understand
what SaaS is and where it is suitable.

#### Characteristics of SaaS

Like other forms of Cloud Computing, it is important to ensure that
solutions sold as SaaS in fact comply with generally accepted
definitions of Cloud Computing. Some defining characteristics of SaaS
include;

- Web access to commercial software
- Software is managed from a central location
- Software delivered in a “one to many” model
- Users not required to handle software upgrades and patches
- Application Programming Interfaces (APIs) allow for integration
between different pieces of software

#### Where SaaS Makes Sense

Cloud Computing generally, and SaaS in particular, is a rapidly growing
method of delivering technology. That said, organizations considering a
move to the cloud will want to consider which applications they move to
SaaS. Here are particular solutions we consider prime candidate
for an initial move to SaaS:

- “Vanilla” offerings where the solution is largely undifferentiated. A
good example of a vanilla offering would include email where many times
competitors use the same software precisely because this fundamental
technology is a requirement for doing business, but does not itself
confer an competitive advantage
- Applications where there is significant interplay between the
organization and the outside world. For example, email newsletter
campaign software
- Applications that have a significant need for web or mobile access. An
example would be mobile sales management software
- Software that is only to be used for a short term need. An example
would be collaboration software for a specific project
- Software where demand spikes significantly, for example tax or billing
software used once a month

SaaS is widely accepted to have been introduced to the business world by
the Salesforce. <sup>10</sup> Customer Relationship Management (CRM) product. As
one of the earliest entrants it is not surprising that CRM is the most
popular SaaS application area <sup>11</sup>, however e-mail, financial
management, customer service and expense management have also gotten
good uptake via SaaS.

#### Where SaaS May Not be the Best Option

While SaaS is a very valuable tool, there are certain situations where
we believe it is not the best option for software delivery. Here are examples
where SaaS may not be appropriate include:

- Applications where extremely fast processing of real time data is
required
- Applications where legislation or other regulation does not permit
data being hosted externally
- Applications where an existing on-premise solution fulfills all of the
organization’s needs

Software as a Service may be the best known aspect of Cloud Computing,
but developers and organizations all around the world are leveraging
Platform as a Service, which mixes the simplicity of SaaS with the power
of IaaS, to great effect.


#### Case Study: SaaS Allows Groupon to Scale Customer Service <sup>12</sup>

Launched in November 2008, Groupon <sup>13</sup> features a daily deal on the
best stuff to do, see, eat and buy in more than 500 markets and 40
countries. The company has thousands of employees spread across its
Chicago and Palo Alto offices, regional offices in Europe, Latin
America, Asia and Africa with local account executives stationed in many
cities. Groupon seeks to sell only quality products and services, be
honest and direct with customers, and provide exceptional customer
service.

“Within a few months of our founding, our customer base exploded,” says
Joe Harrow, Director of Customer Service, Groupon. “At first, I was
spending 10 percent of my time responding to customer requests. It
gradually became a job for several agents. We realized we simply
couldn’t go on without a real ticketing solution.”

Convinced that Groupon’s rapid growth would continue, Harrow researched
several enterprise-level support solutions. But he didn’t find a good
fit.

“The enterprise-level solutions seemed complicated and difficult to set
up,” Harrow recalls. “They would have increased our efficiency, but at
the cost of hampering the customer experience.” Harrow then searched the
web for online support software and found Zendesk <sup>14</sup>. After a quick
evaluation of Zendesk, Harrow knew he had the right solution.

“Right off the bat, Zendesk was intuitive to use,” Harrow says. “It
seemed more powerful and robust than other online support solutions, and
it had been rated very highly in reviews we’d read. Plus, we knew that
because it was a web-based solution, it could easily scale to support
our increasing volume.”

Groupon now employs more than 150 customer support agents, who handle
nearly 15,000 tickets per day. Zendesk’s macros, which are predefined
answers to FAQs, are Groupon’s favorite Zendesk feature. These macros
help Groupon train its agents to deliver one of the company’s customer
service hallmarks: one-touch resolution.

Groupon has also found it easy to integrate Zendesk with other
solutions. By integrating Zendesk with GoodData, Groupon has extended
and enhanced its reporting – going well beyond the limits of its old
spreadsheets. As an example of the sort of scalability that SaaS brings,
Groupon recently processed its millionth customer ticket <sup>15</sup>.



### Platform as a Service

Platform as a Service (PaaS) brings the benefits that SaaS bought for
applications, but over to the software development world. PaaS can be
defined as a computing platform that allows the creation of web
applications quickly and easily and without the complexity of buying and
maintaining the software and infrastructure underneath it.

PaaS is analogous to SaaS except that, rather than being software
delivered over the web, it is a platform for the creation of software,
delivered over the web.

Utilizing a PaaS development environment has resulted in the creation of
these applications being significantly faster than would otherwise be
the case. In some examples, in the absence of PaaS, the cost of
developing the application would have been prohibitive.

PaaS is undoubtedly an exciting and powerful form of Cloud Computing
however in terms of market awareness it’s hard to look past
Infrastructure as a Service and the rapid growth it’s seeing in the
marketplace.

#### Characteristics of PaaS

There are a number of different takes on what constitutes PaaS but some
basic characteristics include <sup>16</sup>:

- Services to develop, test, deploy, host and maintain applications in
the same integrated development environment. All the varying services
needed to fulfil the application development process
- Web based user interface creation tools help to create, modify, test
and deploy different UI scenarios
- Multi-tenant architecture where multiple concurrent users utilize the
same development application
- Built in scalability of deployed software including load balancing and
failover
- Integration with web services and databases via common standards
- Support for development team collaboration – some PaaS solutions
include project planning and communication tools
- Tools to handle billing and subscription management

PaaS, which is similar in many ways to Infrastructure as a Service that
will be discussed below, is differentiated from IaaS by the addition of
value added services and comes in two distinct flavours:

1. A collaborative platform for software development, focused on
workflow management regardless of the data source being used for the
application. An example of this approach would be Heroku, a PaaS that
utilizes the Ruby on Rails development language.
2. A platform that allows for the creation of software utilizing
proprietary data from an application. This sort of PaaS can be seen as a
method to create applications with a common data form or type. An
example of this sort of platform would be the Force.com PaaS from
Salesforce.com which is used almost exclusively to develop applications
that work with the Salesforce.com CRM

#### Where PaaS Makes Sense

PaaS is especially useful in any situation where multiple developers
will be working on a development project or where other external parties
need to interact with the development process. As the case study below
illustrates, it is proving invaluable for those who have an existing
data source – for example sales information from a customer relationship
management tool, and want to create applications which leverage that
data. Finally PaaS is useful where developers wish to automate testing
and deployment services.

The popularity of agile software development, a group of software
development methodologies based on iterative and incremental
development, will also increase the uptake of PaaS as it eases the
difficulties around rapid development and iteration of software.

Some examples of PaaS include Google App Engine <sup>17</sup>, Microsoft Azure
Services <sup>18</sup>, and the Force.com <sup>19</sup> platform.

#### Where PaaS May Not be the Best Option

We contend that PaaS will become the predominant approach towards
software development. The ability to automate processes, use pre-defined
components and building blocks and deploy automatically to production
will provide sufficient value to be highly persuasive. That said, there
are certain situations where PaaS may not be ideal, such as the following
examples:

- Where the application needs to be highly portable in terms of where it
is hosted
- Where proprietary languages or approaches would impact on the
development process
- Where a proprietary language would hinder later moves to another
provider – concerns are raised about vendor lock-in <sup>20</sup>
- Where application performance requires customization of the underlying
hardware and software

#### Case Study: Menumate Uses PaaS to Serve Tasty Applications

Menumate <sup>21</sup> is a provider of point of sale hardware and software for
the hospitality industry across Australasia. Menumate has taken
advantage of the Force.com PaaS to migrate over time a series of legacy
applications used in the business.

Daniel Fowlie and Abhinav Keswani are Directors of development house
Trineo <sup>22</sup>  the company responsible for boutique development for
Menumate. Fowlie explains that the use of the Force.com platform has
allowed Menumate to centralise, modernise and integrate an otherwise
disparate in-house software toolkit.

Keswani feels that a more conventional development approach would
require significant infrastructure, connectivity, security and would
introduce uptime considerations - whereas the Force.com platform
inherently provides these non-functional requirements - allowing
Menumate and Trineo to focus purely on developing the needed
functionality. Additionally, utilizing a PaaS approach has meant Trineo
could take advantage of both existing integrations and automated
deployment tools - another example of PaaS easing the development
process.

Using PaaS, Trineo have been able to migrate over time a series of
legacy applications used in the business. Some of these applications
are:

**License Key Generation** - The Menumate software uses license keys to
activate the features that the customer has paid for. The power of the
PaaS programming language allowed Menumate to quickly port this code to
Force.com where the license keys are linked to the customer record in
the Salesforce.com CRM. This allows Sales and Support staff to quickly
see the status of licenses.

**Enhanced Case Management** - A lot of the support cases Menumate were
dealing with were orders for consumables. To handle this they had a
separate DOS based application that would allow the user to build up an
order and create an invoice. Menumate now can add products to a support
case and automatically send an invoice to their accounting software
using an existing integration product.

**Label Printing** - Another legacy application was for creating freight
labels for sending consumables and hardware to customers. Utilising the
PaaS technology, these can now be printed directly from the customer
record.


### Infrastructure as a Service

Infrastructure as a Service (IaaS) is a way of delivering Cloud
Computing infrastructure – servers, storage, network and operating
systems – as an on-demand service. Rather than purchasing servers,
software, datacenter space or network equipment, clients instead buy
those resources as a fully outsourced service on demand <sup>23</sup>.

As we detailed in a previous whitepaper <sup>24</sup>, within IaaS, there are
some sub-categories that are worth noting. Generally IaaS can be
obtained as public or private infrastructure or a combination of the
two. “Public cloud” is considered infrastructure that consists of shared
resources, deployed on a self-service basis over the Internet.

By contrast, “private cloud” is infrastructure that emulates some of
Cloud Computing features, like virtualization, but does so on a private
network. Additionally, some hosting providers are beginning to offer a
combination of traditional dedicated hosting alongside public and/ or
private cloud networks. This combination approach is generally called
“Hybrid Cloud”.

#### Characteristics of IaaS

As with the two previous sections, SaaS and PaaS, IaaS is a rapidly
developing field. That said there are some core characteristics which
describe what IaaS is. IaaS is generally accepted to comply with the
following:

- Resources are distributed as a service
- Allows for dynamic scaling
- Has a variable cost, utility pricing model
- Generally includes multiple users on a single piece of hardware

There are a plethora of IaaS providers out there from the largest Cloud
players like Amazon Web Services <sup>25</sup> and Rackspace <sup>26</sup> to
more boutique regional players.

As mentioned previously, the line between PaaS and IaaS is becoming more
blurred as vendors introduce tools as part of IaaS that help with
deployment including the ability to deploy multiple types of clouds <sup>27</sup>.

#### Where IaaS Makes Sense

IaaS makes sense in a number of situations, and these are closely related
to the benefits that Cloud Computing bring. Situations that are
particularly suitable for Cloud infrastructure include:

- Where demand is very volatile – any time there are significant spikes
and troughs in terms of demand on the infrastructure
- For new organizations without the capital to invest in hardware
- Where the organization is growing rapidly and scaling hardware would
be problematic
- Where there is pressure on the organization to limit capital
expenditure and to move to operating expenditure
- For specific line of business, trial or temporary infrastructural
needs

#### Where IaaS May Not be the Best Option

While IaaS provides massive advantages for situations where scalability
and quick provisioning are beneficial, there are situations where its
limitations may be problematic. Examples of situations where we would
advise caution with regards IaaS include:

- Where regulatory compliance makes the offshoring or outsourcing of
data storage and processing difficult
- Where the highest levels of performance are required, and on-premise
or dedicated hosted infrastructure has the capacity to meet the
organization’s needs

#### Case Study: Live Smart Helps Dieters by Taking an Infrastructure Diet

Live Smart Solutions is the parent company behind The Diet Solution
Program, (insert endnote - http://www.thedietsolutionprogram.com) a
company producing books and online diet programs. Beyond Diet <sup>28</sup> is
an interactive community site for individuals on their diet program.

Started in 2008, the company has seen rapid growth including a 50x
revenue jump in 2010. This translates to average daily site visits of
300,000 with spikes up to one million unique viewers. When deciding on a
strategy for their infrastructure, Beyond Diet needed something that was
both low-touch and highly scalable. It is important that Beyond Diet
have the ability to both scale up and down as their marketing strategy
sees large traffic spikes on a regular basis.

Rob Volk, CTO of Live Smart, reports that moving to Cloud infrastructure
has given him more peace of mind. Formerly Live Smart had a part-time
systems administrator working on their sites, and as Volk says,

It was not the best option for us. Now with Managed Cloud (an IaaS
service offered by cloud computing provider Rackspace), Rackspace is
basically acting as our Linux and Windows administrator. They’ll make
our changes as we need them, and respond to any downtime, 24 hours a
day. Within minutes, an engineer will log on to fix the problem.

The main drivers for Volk moving to Cloud were the ability to focus on
core business and leave day-to-day management of infrastructure to the
experts. The fact that Cloud providers offer multiple levels of
redundancy, fast configuring and high degrees of flexibility were
deciding factors. Interestingly, Volk never even considered running his
own physical servers. Rather, the decision was one of either hosted
servers or the Cloud.

The decision was made to go with Cloud because it provided reduced cost
and higher flexibility than corresponding dedicated server options.

Volk is using multiple Cloud providers: he has three web servers,
multiple database servers and a load balancer with Rackspace, while also
using Amazon’s S3 service.

The biggest benefit Volk sees with Cloud infrastructure is scalability.
As he explains,

After New Year’s, everyone goes on a diet. Our peak time is right after
New Year’s - we might get three times the traffic from January to March.
With Cloud Servers, we’re able to spin up new web front ends within a
matter of minutes, then take them back down once traffic goes down. We
have this elasticity in our farm that is only possible in a virtualized
environment.

### Conclusion

Cloud Computing is a term that doesn’t describe a single thing – rather,
it is a general term that sits over a variety of services from
Infrastructure as a Service at the base, through Platform as a Service
as a development tool and through to Software as a Service replacing
on-premise applications.

For organizations looking to move to Cloud Computing, it is important to
understand the different aspects of Cloud Computing and to assess their
own situation and decide which types of solutions are appropriate for
their unique needs.

Cloud Computing is a rapidly accelerating revolution within IT and will
become the default method of IT delivery moving into the future –
organizations would be advised to consider their approach towards
beginning a move to the clouds sooner, rather than later.


**About the Author Ben Kepes**
Ben is the founder and managing director of Diversity Limited, a
consultancy specializing in Cloud Computing/SaaS, Collaboration,
Business strategy and user-centric design. More information on Ben and
Diversity Limited can be found at http://diversity.net.nz

**Sources:**

<sup>1</sup> <http://csrc.nist.gov/groups/SNS/cloud-computing/>

<sup>2</sup> <http://csrc.nist.gov/groups/SNS/cloud-computing/cloud-def-v15.doc>

<sup>3</sup> Virtualization – The ability to increase computing efficiency
<http://broadcast.rackspace.com/hosting_knowledge/whitepapers/Revolution_Not_Evolution-Whitepaper.pdf>

<sup>4</sup> Scalability and fast provisioning – for IT at web scale -
<http://broadcast.rackspace.com/hosting_knowledge/whitepapers/Revolution_Not_Evolution-Whitepaper.pdf>

<sup>5</sup> From Water-wheel to Utility Power – An analogy for the Cloud -
<http://broadcast.rackspace.com/hosting_knowledge/whitepapers/Revolution_Not_Evolution-Whitepaper.pdf>

<sup>6</sup> <http://www.qrimp.com/blog/blog.The-Difference-between-IaaS-and-PaaS.html>

<sup>7</sup> <http://m.zdnet.com/blog/forrester/is-the-iaaspaas-line-beginning-to-blur/583>

<sup>8</sup> <http://en.wikipedia.org/wiki/Software_as_a_service>

<sup>9</sup> <http://www.readwriteweb.com/cloud/2010/07/sass-providers-challenge-the-k.php> and
<http://www.networkworld.com/news/2010/101810-saas-on-a-tear-says.html>

<sup>10</sup> <http://www.salesforce.com>

<sup>11</sup> <http://www.networkworld.com/news/2010/050610-gartner-saas-adoption-on-the.html>

<sup>12</sup> <http://www.zendesk.com/blog/groupon-defenders-of-the-customer-experience>

<sup>13</sup> <http://www.groupon.com>

<sup>14</sup> <http://www.zendesk.com>

<sup>15</sup> <http://www.zendesk.com/blog/hey-groupon-thanks-a-million>

<sup>16</sup> <http://en.wikipedia.org/wiki/Platform_as_a_service> and
<http://java.dzone.com/articles/what-platformservice-paas>

<sup>17</sup> <http://code.google.com/appengine/>

<sup>18</sup> <http://www.microsoft.com/windowsazure/>

<sup>19</sup> <http://www.salesforce.com/platform/>

<sup>20</sup> <http://www.zdnet.com/blog/saas/cogheads-demise-highlights-paas-lock-out-risk/668>

<sup>21</sup> <http://www.menumate.com/>

<sup>22</sup> <http://trineo.co.nz/>

<sup>23</sup> <http://diversity.net.nz/wp-content/uploads/2011/01/Moving-to-the-Clouds.pdf>

<sup>24</sup> <http://diversity.net.nz/wp-content/uploads/2011/01/Moving-to-the-Clouds.pdf>

<sup>25</sup> <http://aws.amazon.com/>

<sup>26</sup> <http://www.rackspace.com/>

<sup>27</sup> <http://m.zdnet.com/blog/forrester/is-the-iaaspaas-line-beginning-to-blur/583>

<sup>28</sup> <http://www.beyonddiet.com/BD/Categories/Fat-Burning-Foods>


