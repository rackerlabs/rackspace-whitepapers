---
permalink: connecticut-public-broadcasting-delivers-college-basketball-with-ease-on-the-cloud/
audit_date:
title: Connecticut Public Broadcasting Delivers College Basketball with Ease on the Cloud
type: case_study
created_date: '2012-09-28'
created_by: Laurel Wamsley
last_modified_date: '2017-03-21'
last_modified_by: Cat Lookabaugh
product: White Paper
product_url: white-paper
---

<a href="http://cpbn.org/">
   <img src="{% asset_path UseCases/connecticut-public-broadcasting-delivers-college-basketball-with-ease-on-the-cloud/cpbn.png %}" width="300" height="118" />
</a>

**CUSTOMER’S BUSINESS:** A nationally recognized producer and presenter
of quality public television programming, including sports, original
documentaries, and educational programming

**CHALLENGES:** Online broadcasting of basketball games was interrupted,
due to unexpected heavy volume

**RACKSPACE<sup>&reg;</sup> SOLUTION:** [Cloud
Servers](http://www.rackspace.com/cloud/cloud_hosting_products/servers/),
[Cloud Load
Balancers](http://www.rackspace.com/cloud/cloud_hosting_products/loadbalancers/),
[Scalr’s auto-scaling platform](http://www.scalr.com/), CapCal Web
Performance Testing from [Grid Robotics](http://www.gridrobotics.com/)

**BUSINESS OUTCOME:** A website that handles peak loads easily and
quickly, allowing for satisfied global viewers and peace of mind for CPBN

[CLICK HERE TO DOWNLOAD CASE STUDY](http://c179631.r31.cf0.rackcdn.com/CaseStudy_CPBN.pdf)

### The Connecticut Public Broadcasting Network integrates Rackspace<sup>&reg;</sup> Cloud, Scalr, and Grid Robotics for a winning solution.


One way to take advantage of the elastic capacity of the Rackspace Cloud
is to use an auto-scaling platform like Scalr, along with a means to
test and verify triggers, such as [CapCal Web Performance
Testing](http://www.gridrobotics.com/solutions/capcal-web-performance-testing/).
Connecticut Public Broadcasting implemented solutions from Rackspace,
Scalr, and Grid Robotics, and since the new capabilities were
implemented, the broadcasting network says their online broadcast events
have gone off without a hitch.

CPTV is a media service of the Connecticut Public Broadcasting Network.
It is a locally and nationally recognized producer and presenter of
quality public television programming, including sports, original
documentaries, and educational programming.

The Connecticut Public Broadcasting Network (CBPN) also includes the
public radio station WNPR, which serves almost 240,000 listeners weekly
in Connecticut, New York and Rhode Island with news and information.
(For more information, visit [cptv.org](http://www.cpbn.org/).)

### Intense traffic and need for flexibility

For each of the last seven years, CPTV has streamed its television
broadcast of the college basketball season over the internet so that
alumni who are out of state or out of country can view the games live
and on demand. In the team’s final game last season, due to unexpected
heavy volume, the internet broadcast experienced a denial of service
interruption for the first hour and a half of the game. CPTV was
determined not to let this happen again.

Normal traffic can be easily handled by their [Rackspace dedicated
server](http://www.rackspace.com/managed_hosting/), but for peak loads,
CPBN chose [Rackspace Cloud](http://www.rackspace.com/cloud/) in
combination with Scalr and Grid Robotics. Scalr provisions new servers
on the fly while the Grid Robotics' CapCal Web Performance testing
solution provides the empirical data that demonstrates the complete
solution optimally handles the traffic—both expected and unexpected.

**<cite>“We anticipate at most a one-second response time even during
peak loads for most viewers."
Derrick Ellis, Director of Online and New Media at Connecticut Public
Broadcasting</cite>**

### Auto-scaling for extra capacity on demand

One of the hallmarks of [cloud
computing](http://www.rackspace.com/cloud/) is the ability to take
advantage of extra capacity on demand. Rackspace makes it easy and
affordable to add another server under a load balancer to handle
increased load, and to remove it when it is no longer needed.

Also improving performance is a concept called auto-scaling, which works
to efficiently balance workloads across a [Rackspace Cloud Load
Balancer](http://www.rackspace.com/cloud/cloud_hosting_products/loadbalancers/).
For their website, Connecticut Public Broadcasting Network chose Scalr
as their [auto-scaling solution](http://www.scalr.com/).

Scalr works to identify parameters or triggers for when an additional
server should be added. But the application must be customized for this
purpose and then tested and verified to make sure auto-scaling works as
intended.

### Solving the dreading user-generated DDOS

One specific case that CPBN has seen in the past is in handling what
Derrick Ellis, Director of Online and New Media at Connecticut Public
Broadcasting, refers to as a “user-generated DDOS” (distributed denial
of service), in which users continually hit the browser Refresh button,
not to actually create a denial of service attack, but under the
mistaken impression that it will cause the video to load faster. If the
site is slow already, this only exacerbates the problem and makes it
slower.

In testing, the CPBN team worked to simulate having multiple users hit
the same page over and over. This testing ensured that CPTV’s site would
be available and fast, and that Scalr would respond by adding new
servers to the Cloud Load Balancer in order to keep up with growing web
traffic.

Once the base web server was configured, it became evident that the
server took a little over five minutes to boot up and be added to the
load balancer. This meant that the auto-scaling triggers needed to take
this time into account so that the starting process was more immediate.
By analyzing the web logs from the previous event, CPBN determined that
as many as 2,500 users might log on within a five to ten minute period
and begin hitting refresh.

### A game-winning solution

CPBN’s basic auto-scaling test involved a rapid ramp-up from one to
3,500 users over a three-minute period, and holding that level for up to
15 minutes. Working with Scalr, Grid Robotics technicians set the
auto-scaling triggers so that when the average CPU of the [web
servers](http://www.rackspace.com/cloud/cloud_hosting_products/servers/)
exceeded 50 percent for two minutes, more servers were automatically
added to the mix. After a number of iterations over a couple days, it
was determined that the site could handle the kinds of load that were
expected.

**<cite>"With ten games under our belt so far this season, we are
providing superior service to our viewers with sub-second response
times. We anticipate at most a one-second response time even during peak
loads for most viewers."</cite>**

**<cite>Derrick Ellis, Director of Online and New Media at Connecticut
Public Broadcasting</cite>**



<img class="right" src="{% asset_path UseCases/connecticut-public-broadcasting-delivers-college-basketball-with-ease-on-the-cloud/scalrlogo.png %}" width="193" height="47" />
Scalr is an open source Cloud Management tool that brings automation to web
applications like none other. Auto-scaling, high availability, fault tolerance,
backups, multi-cloud deployments, and hybrid cloud bursting are all supported
out-of-the-box. For more information about Scalr, visit
[www.scalr.com](http://www.scalr.com/).

<img class="left" src="{% asset_path UseCases/connecticut-public-broadcasting-delivers-college-basketball-with-ease-on-the-cloud/gridrobotics.png %}" width="306" height="90" />
Grid Robotics LLC is a leading provider of PaaS (Platform as a Service)
solutions for development, testing, training, and collaboration for all the
major public and private clouds. Their innovative Windows<sup>&reg;</sup> and
Linux virtual appliances are optimized to run in today’s cloud and virtual
environments to provide virtualized solutions to real world problems. Contact
Grid Robotics today for a free trial by visiting
[www.gridrobotics.com](http://www.gridrobotics.com/).
