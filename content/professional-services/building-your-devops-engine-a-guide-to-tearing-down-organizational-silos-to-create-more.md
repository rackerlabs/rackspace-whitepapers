---
permalink: building-your-devops-engine-a-guide-to-tearing-down-organizational-silos-to-create-more/
audit_date:
title: 'Building your DevOps Engine - A Guide to Tearing Down Silos'
type: whitepaper
created_date: '2013-10-24'
created_by: Rackspace Support
last_modified_date: '2015-07-27'
last_modified_by: Stephanie Fillmon
product: Professional Services
product_url: professional-services
---

### Executive Summary

Modern enterprise IT organizations must adapt to a number of radical
changes in technology, user expectations and business objectives.
[DevOps](http://www.rackspace.com/devops/) — a new way of thinking about
the relationship between Development and Operations — offers a solution
to this challenge.

This white paper gives enterprise IT decision-makers a comprehensive
overview of the DevOps model and the value it provides. It examines:

-   The challenges modern IT organizations must address
-   Why traditional IT processes are inadequate
-   Why DevOps represents a compelling alternative
-   Rackspace’s successful use of DevOps
-   Give IT decision-makers a set of recommendations for implementing DevOps
within their own organizations.

### Introduction: What Is DevOps?

There’s a new approach to software development that is transforming the
modern enterprise IT organization. It’s a new way of working, of
thinking and of doing business. It’s an approach that has as much to do
with process and
[culture](http://www.rackspace.com/devops/the-devops-mindset/) as it
does with tools and technology.

Welcome to the world of DevOps.

DevOps is an IT organizational model in which system administrators work
side-by-side with developers in a single, coordinated, agile
environment. DevOps brings together functions that once worked by
emphasizing the role that communication, collaboration, and integration
play in delivering solid, stable business applications. DevOps also
breaks down organizational walls, and it promotes a fundamentally
different way of solving IT problems.

This change has been a long time coming. The rise of cloud computing,
and the pressures on enterprise IT to change how it works with business
users, has forced both groups to rethink this approach.

In practice, DevOps requires developers to pay closer attention to
deployment scripts, configuration files, load and performance testing,
and other activities usually associated with an Operations group.
Developers also pay more attention to how the code they write will
perform in a distributed, cloud-based environment. It’s an important and
necessary evolution, as developers face more platform options than ever
before and more pressure to build high-quality, user-focused
applications that deliver immediate business value.

As the name suggests, however, DevOps is a two-way street: Operations
gives the developers constant feedback, troubleshooting information, and
other data from the production environment that shows how code performs
in real-world conditions. Operations provides critical knowledge about
an application’s impact on the business and end-user experience, and it
works hand-in-hand with Development to resolve problems and deliver a
quality product. This allows each party to learn more about the other’s
job.

“DevOps is about building a support structure for collaboration between
your Development and Operations functions so that you’re now
communicating more closely,” said Brian Jawalka, Manager, Strategy and
Architecture, [Enterprise Cloud Solutions at
Rackspace](http://www.rackspace.com/enterprise-cloud-solutions/).
“They’re aligned to similar goals and really working toward the same
outcomes. That means Operations gets a deeper understanding of what the
applications requires, and developers understand how what they’re doing
impacts infrastructure. We believe that collaboration incites
innovation, and DevOps is the key to making that possible.”

#### A new view of IT collaboration.

Agile methodologies (see sidebar) are key to being successful with the DevOps
model. Combined, they can focus on rapid, incremental releases; gather feedback,
correct problems quickly, focus on quick wins and move on to the next release
cycle. Most IT organizations are already familiar with Agile methods and
principles, and it’s a logical next step to apply these methods to a single,
tightly integrated DevOps process.

Yet DevOps is not simply another exercise in Agile methods. It is also a
major cultural shift for many IT organizations. It requires Developers
and Operations specialists to rethink their day-to-day working
relationships. **DevOps also demands strong leadership from IT
executives who are committed to breaking down the silos that used to
separate Development and Operations.**

In this white paper, we explore the evolution of DevOps and the IT
challenges that it is designed to address. Then we delve into the relationship
between the cloud computing revolution and the emergence of DevOps and
see how both contribute to a new business model for today’s enterprise IT
organizations. Finally, we examine the Rackspace approach to DevOps and
discuss some key lessons that other IT organizations can adapt to their
own DevOps initiatives.

### The Evolution Of DevOps

Traditionally, software development and IT operations weren’t just
different jobs. They were different organizations with their own goals,
priorities and points of view:

-   Developers embrace change. In fact, developers often encourage change by
constantly looking for new and better ways to do things, and they embrace new
tools and platforms. This approach encourages innovation, but it often plays
down objectives such as scalability, reliability and repeatability.
-   Operations focuses on stability. A system administrator gets paid to keep
things running and protect the business against unplanned downtime. While
Operations professionals aren’t opposed to innovation, they are wary of changes
that introduce uncertainty and risk.

Development and Operations don’t just have different priorities. They
use different tools and methodologies; production environments are often
very different than those used for development and QA activities.
Developers and sys admins report to different managers, and in many
cases they even work at different locations.

#### The traditional approach to writing and running code.

What happens when these two groups go through a traditional application release
cycle? The process often looks something like this:

1.  Developers write and test new code in their Dev/QA environment. When it’s
ready, they toss it “over the wall” to Operations to deploy.
2.  Operations discovers that the deployment scripts and configuration files do
not work in the current production environment. They’re forced to make a number
of unplanned changes to adapt the release for production use.
3.  Some of these changes crash production systems when they’re deployed, and
there’s a mad scramble to fix the deployment and get things running again.
4.  Each side blames the other for yet another painful, time-consuming release
cycle.

“Developers build the application, and then it gets tossed over the
fence for the Operations to run, but there’s little communication,” said
Jawalka. “Developers say ‘I’m going to write whatever is most efficient
for us to write,’ and Operations doesn’t have a deep understanding of
the application.”

<img src="{% asset_path professional-services/building-your-devops-engine-a-guide-to-tearing-down-organizational-silos-to-create-more/DevOps-1.png %}" width="577" height="342" />

### Coping With Change In Today’s Enterprise IT Organization

When virtualization technology came on the scene a little over a decade
ago, this dynamic between Development and Operations shifted.

Operations could consolidate physical computing assets for more
efficiency. Virtualized platforms also made it easier for Development
and Operations to build and deploy applications in more standardized
environments. Because the virtualization layer only impacts
infrastructure, not the development platform, Development and Operations
remained islands.

With the introduction of cloud computing, three unique traits were added
to the enterprise IT mix: a new application platform, a new model for
consuming IT services, and a foundation for new business models. Now,
Development and Operations are rethinking their approach to
collaboration, to align their goals and priorities, and to adopt shared
toolsets.

In the cloud, the entire infrastructure stack, from storage to
networking to servers, can be virtualized. Software plays a vital role
in managing these virtual environments. As a result, the entire IT
organization must take collective ownership of managing this automation.
“Many of the traditional Operations activities have to be built into the
code,” observes Jawalka in assisting Rackspace IT with their cloud
transformation.

#### Changing the business of enterprise IT.

User expectations are rising; they need applications to evolve quickly and to
deliver new features almost on demand. IT organizations have the opportunity to
evolve from cost centers into business enablers. To do so, enterprise IT must:

-   Learn how to become a service provider to its business users;
-   Move quickly — in many cases instantly — to meet changing business
    requirements;
-   Enable a self-service approach to selecting and provisioning IT
    services;
-   Create security “guard rails” for a self-service approach to IT
    through the use of service catalogs;
-   Do more with less, even as the demand for IT services continues to
    increase.

Accomplishing this transformation requires a new approach to how
Development and Operations collaborate using shared goals and
methodologies: the DevOps model.

### How DevOps Accelerates Application Delivery

How can DevOps make it possible for an enterprise IT organization to
evolve and adapt to this new reality? Here are some key considerations
for Development and Operations:

-   **Scalable applications.** It’s no longer enough to develop and test
applications using a single-server environment. Applications must be able to
scale in distributed environments with hundreds or even thousands of servers.
The ability to deploy these applications must be automated, reproducible and
programmatic.
-   **Stateless applications.** Stateful applications, able to retain session
data within the application regardless of what infrastructure serves the
application, are difficult to scale, often lack portability and require more
network bandwidth to operate. This requires the ability to manage user
sessions — and maintain a high user experience — across virtualized,
multi-server environments.
-   **Continuous learning.** It’s not enough for Development and Operations to
agree to work together. They must also agree on the processes for experimentation
and continuous improvement in delivering new applications and deploying updates
to existing applications. DevOps works together to select and implement which
platforms provide the best foundation for key activities — such as automation
and self-service delivery models.
-   **Platform-based development.** Platform as a service (PaaS) cloud computing
services provide the entire infrastructure — from hardware and operating systems
to databases and middleware — required to develop and run applications. Developers
can build applications faster and cheaper using a platform-based approach, but
doing so requires the right tools and the right understanding of how to adapt
their code to a PaaS environment.
-   **Automation.** Faster release cycles, combined with massively scalable cloud
environments, demand the ability to automate every aspect of the release process.
Tools such as Puppet and Chef eliminate manual processes and replace them with
simpler, standardized and highly repeatable software deployment methods.
-   **Scripting and coding.** Many system administrators are already comfortable
using tools like Perl, a tool that was actually developed as a programming
language for automating system administration. Today, the ability to use a wide
range of scripting and coding tools is even more important, given the role these
play in automating software release cycles and creating scalable IT management
processes.
-   **Infrastructure via APIs.** Infrastructure APIs give Operations a standard
framework for provisioning and configuring cloud-based infrastructure components.
By offering access to these components, infrastructure APIs simplify the process
of deploying and managing cloud-based applications allowing programmatic changes
to the infrastructure.

As Jawalka points out, all of these considerations serve a single
purpose. “Within our group, we found that in order for us to build truly
cloud-aware applications, many of the usual things that are considered
by the typical applications support team post-deployment would have to
be factored into the design of the code itself,” he said. “This includes
self-provisioning, auto-scaling, self-healing and recovery, and
API-based monitoring mechanisms. In order to factor all of these
capabilities into the design of the application, you need a very high
degree of collaboration and integration between the Development and
Operations.”

“We’re not necessarily saying that the developers are now running
infrastructure or the infrastructure guys are writing code,” added
Jawalka. “But there’s awareness and understanding of how they work
together.”

### DevOps In Action at Rackspace

The Rackspace IT story offers a great example of why DevOps is so
important to transforming the business of enterprise IT. Rackspace IT
also faced challenges around serving a fast-growing business using a
traditional dedicated infrastructure model, along with a traditional
division of labor between separate Developer and Operations groups.

This model left Rackspace IT at a disadvantage for several reasons:

-   IT had a limited ability to deploy software releases; each release cycle was
a separate process that might require months to complete.
-   The release process did not scale effectively, relying heavily on manual,
non-standard processes.
-   The resulting long lead times hindered Rackspace’s ability to innovate and
to compete in a fast-moving business environment.
-   Heavy CapEx expenditures were consuming scarce resources and limiting
investment in potentially promising new applications.

A shift to a DevOps model played a critical role in allowing Rackspace
IT to reposition itself as a business-focused organization and to use
the Open Cloud as a platform for innovation. This included:

-   Adopting a continuous delivery model that supports fast, incremental
software releases, as well as constant feedback on software functionality and
features.
-   Deploying new cloud-based services almost instantly, enabling a self-service
IT model.
-   Driving down IT delivery costs with a utility pricing model.

“We’re now able to do releases every hour,” said Jawalka. “Instead of a
single new release every month, we’re doing 15 releases a day to our
public cloud. We’re improving the quality of our applications, moving
more quickly to address new business needs and ultimately delivering a
better product to our customers. All of this is possible because of the
collaboration that is really enabled through DevOps.”

According to Jawalka, the shift to DevOps is critical to the company’s
long-term success. “Rackspace is growing at a tremendous pace. IT is an
enabler — we need to keep up with the business and help drive growth,”
he explained.

“The traditional model was really not adequate for us to keep up with
the company’s business needs. We had to get to a model where we could go
from, say, doing a release drop a week to multiple drops a day. Now,
we are partnering with the business and getting instant feedback.”

<img src="{% asset_path professional-services/building-your-devops-engine-a-guide-to-tearing-down-organizational-silos-to-create-more/DevOps-2.png %}" width="679" height="342" />

### Building Your DevOps Engine: Keys To Success

A growing number of enterprises understand how DevOps works in theory,
but what does it take to implement and run a successful DevOps model in
practice? The Rackspace IT team found several considerations that stand
out:

**Set a long-term strategy.** “In my opinion, this is the number one
thing necessary for success,” said Jawalka. “Where do we want to be in
12 or 18 months? Without that, we don’t have a way to outline a roadmap
or to start working on organizational alignments.”

**Focus on organizational alignment.** According to Jawalka, the most
successful DevOps models focus on organizational issues, including
leadership. “They have Operations and Development functions that are
really all reporting to the same managers,” he said. “They’ve split up
Operations so that they have a few Operations personnel on each
Development project, allowing them to share knowledge and really foster
collaboration.”

Mark Majewski, Architect, Enterprise Cloud Solutions at Rackspace, added
that successful DevOps make collaboration a part of their organizational
DNA: “It’s not just the cross-pollination of talent but that cultural
mind shift, that willingness to share experiences.”

**Leverage internal talent.** Does your IT organization need to acquire
the talent required to implement a DevOps model? According to Jawalka,
it’s often easier and more efficient to identify members that already
have the right skills to build a DevOps engine. Server and storage
infrastructure support personnel, for example, are probably already
well-versed in the scripting, configuration management and automation
skills required to drive the “ops” side of DevOps.

**Create a continuous feedback loop.** In order to support continuous
delivery and integration of applications, DevOps must also put the
processes in place to collect and implement feedback – and not just from
IT staff. “We want to have feedback from the business users,” said
Jawalka.

“We put the tools and processes into place to enable continuous
integration and delivery so that we can have that instant feedback from
our customers.”

<img src="{% asset_path professional-services/building-your-devops-engine-a-guide-to-tearing-down-organizational-silos-to-create-more/DevOps-3.png %}" width="650" />

### Conclusion: What Will Your Organization Accomplish With DevOps?

Cloud computing gives your enterprise IT organization the ability to
rethink how it serves and adds value the business. DevOps, in turn,
makes it possible to build software development, deployment and
improvement processes that take full advantage of the cloud’s efficiency
and productivity benefits.

In fact, according to Majewski, implementing DevOps is an essential
piece of a cloud-enabled IT business model. “It’s a mind shift around
not only how applications and services are consumed, but also around how
the infrastructure itself operates and how the applications interact
with that infrastructure.” Without DevOps to provide a foundation for
this shift, it’s impossible for IT organizations to realize the full
value of cloud computing — or to meet the growing expectations placed
upon them by their business users.

Find more DevOps-related resources from Rackspace:

-   DevOps-related information and insights: [DevOps Blog](devops.rackspace.com)
-   Tools and guidance for developers using Rackspace products: [Rackspace Developers Center](http://developer.rackspace.com/)
-   Webinar and presentation on building your DevOps engine: [Preparing for Dev/Ops Success](http://www.rackspace.com/blog/enterprise-cloud-forum-recap-prepare-for-devops-success/)
-   Connect with other technophiles to get advice, share your genius, or solve problems: [Rackspace Open Cloud Community](https://community.rackspace.com/)
-   Whitepapers, videos, and webinars around managing enterprise cloud management: [Enterprise Cloud Services resources](http://www.rackspace.com/enterprise-cloud-solutions/resources/)
