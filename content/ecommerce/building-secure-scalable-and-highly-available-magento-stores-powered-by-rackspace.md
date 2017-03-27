---
permalink: building-secure-scalable-and-highly-available-magento-stores-powered-by-rackspace-solutions/
audit_date:
title: 'Building Secure, Scalable and Highly Available Magento Stores, Powered by Rackspace Solutions'
type: whitepaper
created_date: '2013-05-17'
created_by: Rackspace Support
last_modified_date: '2017-03-16'
last_modified_by: Cat Lookabaugh
product: Ecommerce
product_url: ecommerce
---

By:

Mahesh Gandhe, Sr. Solutions Manager for Ecommerce and SaaS/ISV
R. J. Rowntree, Commerce Channel Manager
John Engates, Chief Technology Officer

### Abstract

**A Closer Look at Ecommerce Reference Architectures**

Magent offers flexible, scalable [ecommerce
solutions](http://www.rackspace.com/ecommerce-hosting/) designed to help
businesses grow and succeed online. The Magento platform is trusted by
more than 150,000 businesses, including some of the world’s leading
brands. Magento Enterprise delivers its best performance on an
infrastructure optimized to its exacting requirements. Simply running
Magento on generic servers risks performance issues that translate into
abandoned shopping carts, slow loading pages and lost revenue. With over
1,000 Magento deployments globally ranging from SMB to Fortune 500
customers, Rackspace has developed core competencies and expertise in
Magento infrastructures. Rackspace now hosts a greater percentage of the
world’s Magento deployments than any other hosting provider.<sup>1</sup>
["Rackspace ecommerce hosting solutions for
Magento"](http://www.rackspace.com/ecommerce-hosting/magento) delivers
an infrastructure honed to meet Magento’s requirements. It uses proven,
optimized and scalable infrastructure components to deliver unsurpassed
performance and reliability. It’s all backed by a team made up of
infrastructure experts capable of supporting configurations tailored to
your specific needs. The end result is a fast, rock-solid and
problem-free Magento site that performs exceptionally and, in turn,
delivers that fast user experience that your shoppers expect.

Based on deep expertise of Magento deployments, this white paper
provides guidance and reference architecture for building word-class
ecommerce websites on the Magento platform.

### 1. Introduction

Whether you are launching your first online store on Magento’s ecommerce
platform or you are re-architecting it with Magento Enterprise, you need
a cloud or hybrid partner that is seasoned in hosting Magento platforms
to build secure, scalable and highly available online stores.

With Rackspace, you are in the hands of a proven [Magento Hosting
Partner](http://www.rackspace.com/ecommerce-hosting/magento/) dthat has
helped more than 1,000 customers globally, ranging from SMBs to Fortune
500 companies. According to a study from ecommerce publishing authority
Internet Retailer, Rackspace is currently ranked the number one hosting
provider for the Internet Retailer Top 1,000 websites. Rackspace now
hosts [a greater percentage of the world's Magento deployments than any
other hosting provider](http://trends.builtwith.com/shop/Magento). In
order to support you as a team, Rackspace has entered into the Magento
Hosting Partner program as a Platinum level partner.

“Rackspace ecommerce hosting solutions for Magento,” here after referred
as “the solution,” is a [Magento ecommerce platform optimized by
Rackspace Hosting](http://www.rackspace.com/ecommerce-hosting/magento/).
This solution is a combination of multiple product offerings from
Rackspace including dedicated hosting, cloud hosting, hybrid hosting and
additional services meant to augment performance.

### 2. Use Cases

Ecommerce commonly refers to the buying and selling process of various
products and services through the online environment. Ecommerce websites
are in most cases well designed websites with high amounts of traffic,
while ecommerce hosting enables ecommerce websites to be hosted on
shared or dedicated server hardware. Rackspace ecommerce hosting for
Magento supports the following most common ecommerce hosting use cases:

1.  **100% Uptime** – When your website is your cash register, it has to be open
for business — always. Thus, ecommerce websites are required to be highly
available. The solution can guarantee 100% production uptime, provided a
recommended topology is deployed.
2.  **Page Load Times Less Than Two Seconds** – Loading ecommerce web pages
within two seconds, even during peak load time, is an industry norm. The
solution supports faster page loads.
3.  **Security of Sensitive Data** – Ecommerce sites requires very secure
infrastructure for managing sensitive data on the server collected from the
users of the website, including credit card information. The solution helps
customers in PCI compliance using PCI compliant dedicated infrastructure and
third party payment gateways for cloud infrastructure.
4.  **Scalability** – The ability to handle sudden and/or seasonal spikes in
demand for holiday seasons is the most important use case for ecommerce websites.
The solution supports this use case using cloud infrastructure to make your
infrastructure feel virtually unlimited.

**In summary, we help merchants architect and deploy secure, scalable
and highly available Magento ecommerce stores on Rackspace Infrastructure.**

### 3. Factors Influencing Solution Design

Various factors influence your choice of hardware for your online
ecommerce store. Some of the most important factors to consider
include:

#### 3.1 WHICH MAGENTO EDITION IS RIGHT FOR YOU?

You can choose between “Magento Community” and “Magento Enterprise” to
develop your solution. To decide which edition is right for you, simply
[click here](http://magento.com/products/overview) to view descriptions
of the Magento Community, Enterprise and Go editions.

#### 3.2 WHERE TO STORE CREDIT CARD DATA AND HOW DO YOU TRANSMIT IT?

A few other important factors to consider are where you want to store
credit card data and how do you transmit it.

**3.2.1 OPTIONS AVAILABLE FOR STORAGE**
You can store credit card data in a Rackspace data center or use a
third-party payment gateway to store credit card information using APIs.
The third-party payment gateway is most common since it offloads much of
your PCI burden to that provider. That being said, should you require
credit card info and other sensitive data to be housed within your
environment, we can architect solutions to [help you meet PCI
compliance](http://www.rackspace.com/ecommerce-hosting/pci/).

**3.2.2 HOW DO YOU DECIDE WHICH OPTION IS RIGHT FOR YOU?**
One way to determine which option is right for your business is to
compare the cost of using a third-party payment gateway with the cost of
storing credit card information in a data center. If you process a
smaller number of credit card transactions, you might find that using a
third-party payment gateway is more economical and the best option,
provided it fits within your company policies. If credit card
transaction volume is very high, you may find it more cost-efficient to
store credit card information in a Rackspace data center and undergo PCI
compliance audits. Your company policies and credit card transaction
volume, along with other factors not discussed here, can help determine
where to store credit card data.

When you choose the option of transmitting credit card information from
server side using APIs, your server infrastructure becomes part of PCI
compliance. On the other hand, using APIs from client browsers, excludes
your server infrastructure from the scope of PCI compliance.

#### 3.3 MAXIMUM NUMBER OF CONCURRENT USERS

This is the number of customers that can log into your online store
simultaneously and place orders without encountering issues related to
resource allocation. This is an important consideration when choosing
the reference architecture for your company. We recommend designing your
system for 1.5 times the peak load that you anticipate in your
day-to-day transactions.

#### 3.4 OTHER FACTORS

In addition to the factors discussed above, the following business
parameters will also influence your reference architecture design
choices:

-   Size of catalog
-   Average browsing time per user, (i.e. 5 minutes, 20 minutes, 30 minutes)
-   Average and peak visitors per day
-   Average orders per day
-   Peak orders per hour and per day
-   Peak orders per hour and per day during the holiday season
-   Number of concurrent users on admin panel
-   Amount of SKUs/product records in catalog
-   Amount of categories
-   Administrative users: Over six admin users will require separation of this
function to its own environment
-   Payment Bridge: This offering from Magento can help with PCI/DSS and requires
additional infrastructure

As a rule of thumb, please remember that number of concurrent users and
transactions help to size web servers. The number of SKUs for sale on
the website helps to size the database server.

### 4. Overview of Reference Architectures

Based on our expertise of serving thousands of Magento customers in the
past, we have developed following four [reference
artitectures](http://www.rackspace.com/ecommerce-hosting/reference_architectures/)
as starting points:

#### 4.1 MAGENTO COMMUNITY EDITION - BASIC REFERENCE ARCHITECTURE

This configuration is ideal for the retailer that is looking to get
started on a smaller budget, deploying Magento Community edition or an
entry level Magento Enterprise Edition. Cost of entry to this solution
is very low with a tremendous upside for rapid growth.

This is a pure cloud configuration in which web server and database both
reside in the cloud. In this architecture, we propose cloud network
segmentation between web and database servers for security reasons. In
this topology, you can add web and database servers for scalability. It
is recommended to store customer credit card information outside the
Rackspace network using third-party payment gateways when deploying to
the public cloud.

<img src="{% asset_path ecommerce/building-secure-scalable-and-highly-available-magento-stores-powered-by-rackspace-solutions/magento-4.png %}" width="499" height="401" />

**Configuration Details:**

*1 Cloud Load Balancer (public)*

-   SSL
-   Fewer than 100 concurrent connections
-   50GB bandwidth

*2 Cloud Servers for web*

-   16GB, 6 vCPUs, 620GB storage
-   HTTPS Cloud Monitoring checks
-   Varnish for caching

*2 Cloud Servers for database (master/slave)*

-   Memcached
-   8GB, 4 vCPUs, 320GB dstorage
-   Cloud Backup
-   TCP Port Cloud Monitoring check
-   Cloud Block Storage SSD 100GB
-   Isolated Cloud Networks with connectivity only to web servers

*Cloud Files and the Akamai CDN*

-   50GB capacity
-   50GB bandwidth

*Service Recommendations:*

-   Choose a [Managed Cloud Account](http://www.rackspace.com/cloud/managed_cloud/overview_b/)
and save time by letting us manage your infrastructure and deploy your servers.

#### 4.2 MAGENTO ENTERPRISE EDITION - INTERMEDIATE REFERENCE ARCHITECTURE

This is an ideal solution for emerging Enterprise Edition retailers. It
combines low cost of entry with more resources allocated to the
individual servers and can be scaled to meet growing demands.

This configuration is built using dedicated servers for both web and
database servers. Single web and database server are segmented behind
physical firewall. In this topology, customer credit card information is
stored using the third-party payment gateway.

<img src="{% asset_path ecommerce/building-secure-scalable-and-highly-available-magento-stores-powered-by-rackspace-solutions/magento-6.png %}" width="499" height="379" />

**Configuration Details:**

*1 ASA 5510 Security Plus firewall*

-   1 site-to-site VPN, 5 client VPNs
-   RackConnect for Cloud Files

*1 enhanced Two Silver database server (DMZ segment)*

-   Red Hat<sup>&reg;</sup> Enterprise Linux<sup>&reg;</sup> 6
-   Dual Quad Core CPU, 24 GBRAM
-   2x 146GB RAID 1 (OS), 4x 146 B RAID 10 (data)
-   Sophos A/V
-   Base Backup Agent

*1 enhanced Two Silver database server (Inside segment)*

-   Red Hat<sup>&reg;</sup> Enterprise Linux<sup>&reg;</sup> 6
-   MySQL
-   Memcached
-   Dual Quad Core CPU, 24 GB RAM
-   2x 146GB RAID 1 (OS), 4x 146GB RAID 10 (data)
-   Base Backup and MySQL Agent

*Cloud Files and the Akamai CDN*

-   50GB capacity
-   50GB bandwidth

*Mailgun – express base package*

#### 4.3 MAGENTO ENTERPRISE EDITION - ADVANCED REFERENCE ARCHITECTURE

This configuration is for an established retailer with higher traffic
that warrants a load balanced solution for unpredictable traffic
patterns. This solution also offers retailers the ability to burst into
the cloud for traffic spikes. Retailers running promotions frequently
through fire sales, marketing pushes, and social media blitzes can
benefit from this solution.

This configuration is a [Hybrid
configuration](http://www.rackspace.com/hosting_solutions/hybrid_hosting/)
built using
[RackConnect<sup>&reg;</sup>](http://www.rackspace.com/cloud/hybrid/dedicated_cloud/rackconnect/).
It uses dedicated servers for database and web servers. Holiday spikes
or sudden increase in load can be burst into cloud servers, with Magento
Peak Demand Licenses. Dual web and database servers are segmented behind
physical firewall. Customer credit card information is stored in the
third-party payment gateway.

<img src="{% asset_path ecommerce/building-secure-scalable-and-highly-available-magento-stores-powered-by-rackspace-solutions/magento-8.png %}" width="498" height="376" />

**Configuration Details:**

*1 ASA 5510 Security Plus firewall*

-   1 site-to-site VPN, 5 client VPNs

*F5 1600 Local Traffic Manager*

-   RackConnect<sup>&reg;</sup> for Cloud Files bursting with Magento Peak Demand
    Licenses

*2 enhanced Two Silver web servers (DMZ segment)*

-   Red Hat<sup>&reg;</sup> Enterprise Linux<sup>&reg;</sup> 6
-   Dual Quad Core CPU, 24GB RAM
-   2x 146GB RAID 1 (OS), 4x 146GB RAID 10 (data)
-   Sophos A/V
-   Base Backup Agent

*2 enhanced Two Silver database servers (Inside segment)*

-   Red Hat<sup>&reg;</sup> Enterprise Linux<sup>&reg;</sup> 6
-   MySQL
-   Memcached
-   Dual Quad Core CPU, 24GB RAM
-   2x 146GB RAID 1 (OS), 4x 146GB RAID 10 (data)
-   Base Backup and MySQL Agent

*4 Cloud Servers for web (landing page & catalog logic)*

-   4GB, 2 vCPUs, 160GB storage
-   HTTPS Cloud Monitoring checks

*Cloud Files and the Akamai CDN*

-   50GB cpacity
-   50GB bandwidth

*Mailgun – express base package*

**Service Recommendations:**

-   Choose a [Managed Cloud Service
    Level](http://www.rackspace.com/cloud/service-levels/managed/) and
    save time by letting us manage your infrastructure.
-   Work with our [Advisory
    Services](http://www.rackspace.com/enterprise_hosting/advisory_services/)
    team to play your seamless journey to the cloud.

#### 4.4 MAGENTO ENTERPRISE EDITION - PREMIER REFERENCE ARCHITECTURE

This configuration is designed for retailers for supporting the highest
number of online transactions compared to other configurations.
Rackspace can deliver a resilient, highly available infrastructure with
failover capabilities at every layer of the solution. Rackspace can also
provide guidance on PCI compliance for storing credit card information
securely.

This also is a hybrid configuration built using RackConnect as it uses
[dedicated servers](http://www.rackspace.com/managed_hosting/dedicated_servers/)
for database and hosting web servers. Holiday spikes or sudden increase
in load can be burst into [Rackspace Cloud
Servers](http://www.rackspace.com/cloud/), with Magento Peak Demand
Licenses. It uses HA configurations for dedicated firewalls and F5 load
balancers. This topology allows storing customer credit card information
within the Rackspace network on dedicated servers. It achieves PCI
compliance with help from the third party products of Symantec and Alert
Logic.

<img src="{% asset_path ecommerce/building-secure-scalable-and-highly-available-magento-stores-powered-by-rackspace-solutions/magento-9ent2.png %}" width="500" height="408" />

**Configuration Details:**

*2 ASA 5520 Security Plus high-availability firewalls*

-   1 site-to-site VPN
-   10 client VPNs

2 F5 1600 high-availability Local Traffic Managers

-   RackConnect<sup>&reg;</sup> for Cloud Files bursting with Magento Peak
Demand License
-   Alert Logic Threat Manager IDS + Alert Logic Log Manager
-   SSL, 51-100MB throughput
-   10 log sources

*Imperva<sup>&reg;</sup> high-availability Web Application Firewall*

-   Gold SLA
-   RSA SecurlD<sup>&reg;</sup> 130
-   10 tokens
-   veriSign SSL certificate
-   1 domain

*2 enhanced Two Silver shopping cart servers (DMZ segment)*

-   Red Hat^®^ Enterprise Linux<sup>&reg;</sup> 6
-   Dual Quad Core CPU, 24GB RAM
-   2x 146 GB RAID 1 (OS), 4x 146 GB RAID 10 (data)
-   Sophos A/V
-   Base Backup Agent

*2 Performance One Silver database servers (active/passive multi-master)*

-   Red Hat<sup>&reg;</sup> Enterprise Linux<sup>&reg;</sup> 6
-   MySQL
-   Memcached
-   Dual Hex Core CPU, 64GB RAM
-   2x 300GB RAID 1 (OS), 4x 300GB RAID 10 (data)
-   Base Backup and MySQL Agent

*4 Cloud Servers for web (landing page & catalog logic)*

-   4 GB, 2 vCPUs, 160GB storage
-   HTTPS Cloud Monitoring checks

*Cloud Files and the Akamai CDN*

-   100GB capacity
-   100GB bandwidth

*Mailgun – express base package*

*Service Recommendations:*

-   Choose a [Managed Cloud Account](http://www.rackspace.com/cloud/managed_cloud/overview_b/)
and save time by letting us manage your infrastructure.
-   Select [Critical Application Services](http://www.rackspace.com/enterprise_hosting/critical_applications/)
for a super-aggressive SLA with a 100% production platform uptime guarantee and
a 2x service level credit.
-   Work with our [Advisory Services](http://www.rackspace.com/enterprise_hosting/advisory_services/)
team to plan your seamless journey to the cloud.

### 5. Flowchart for Choosing a Reference Architecture

The following flowchart provides guidance for deciding which reference
architecture is right for your business needs. Alternatively, the
Rackspace support team can help you in deciding the right topology for
your needs.

<img src="{% asset_path ecommerce/building-secure-scalable-and-highly-available-magento-stores-powered-by-rackspace-solutions/magento-10flowchrt.png %}" width="497" height="400" />

Please note: the recommendation provided above for choosing the right
reference architecture based on the number of concurrent users stems
from our experience of helping 1000+ customers in deployment.

<http://www.magentocommerce.com/product/overview-compare?utm_source=magentocommerce&utm_medium=topnav>

### 6. Why We Are a Leader in Magento Hosting

Our customers trust us with their Magento hosting needs for the
following reasons:

-   **Broad Product Portfolio** – We offer dedicated hosting, public, private
and hybrid cloud, linked by our unique RackConnect hybrid technology so that
you can “buy the base, rent the spike.”
-   **Our Magento Knowledge** – With Rackspace, you are in the hands of a proven
Magento hosting partner that can guide you through architecting your Magento
solution and tuning it for optimal performance.
-   **Relationships with top Magento SIs** – Our key alliances with top Magento
Solution Partners allow us to provide end-to-end support for a complete experience.
-   **PCI Compliance** – Providing you with infrastructure and solutions
requirements that can help reduce the scope and complexity of your compliance
efforts.
-   **IT expertise** – An on-staff team of security, database, networking,
application and infra- structure specialists available every day, all day.
-   ***Fanatical Support <sup>&reg;</sup>***– From strategic development
assistance offered by our Advisory Services team to custom architectural design
from our Solutions Architects, we provide full end-to-end ecommerce solutions,
all backed 24x7x365 by our legendary
[***Fanatical Support***](http://www.rackspace.com/whyrackspace/support/).

### 7. Overview of Rackspace Solutions for Online Retail

In addition to providing solutions for ecommerce hosting, Rackspace can
help retailers in their journey to the next generation retail experience
by providing the following solutions:

-   **Mobile Commerce** – In addition to powering your ecommerce website,
Rackspace also supports hosting of [mobile commerce websites](http://www.rackspace.com/mobile-cloud/).
-   **Building Custom Applications** – As an industry-leading SaaS hosting
provider, Rackspace offers deep hosting expertise and a variety of products and
services for [building custom applications](http://www.rackspace.com/enterprise_hosting/saas/).
-   **Campaign Pages** – Rackspace provides hosting infrastructure for
[building microsites](http://www.rackspace.com/enterprise_hosting/campaigns/)
to supporting your marketing initiatives.
-   **Corporate Website Hosting** – Your corporate site is often the first and
primary interaction that your customers - and the world - have with your product,
service and brand. Rackspace can help you with
[hosting your corporate website](http://www.rackspace.com/hosting_solutions/websites/).
-   **Test & Dev** – [Isolated compute environments used to develop](http://www.rackspace.com/hosting_solutions/testdev/),
QA and test a new application/site or changes to an existing application/site
are available.
-   **Big Data Analytics** – Through our partnership with Hortonworks, the
premiere open-sourced Apache Hadoop, enterprise distribution, we offer three
different deployment models to solve your
[Big Data needs](http://www.rackspace.com/big-data/) based on the size and
complexity of your workloads on dedicated and cloud servers.
-   **Hosted email** – [Rackspace Email Hosting](http://www.rackspace.com/email-hosting/)
gives you the power to securely manage email from any web browser or the device
of your choice – no licenses to keep track of or soft- ware to download.
-   **Hosted SharePoint^®^** – We offer dedicated and multi-tenant
[SharePoint hosting services](http://www.rackspace.com/enterprise_hosting/sharepoint/)
for collaborating within your organization.

<img src="{% asset_path ecommerce/building-secure-scalable-and-highly-available-magento-stores-powered-by-rackspace-solutions/magento-chapt8.png %}" width="501" height="350" />

### 8. Summary

Magento Enterprise offers an innovative open source technology and is
one of the fastest growing ecommerce platforms. Because of its level of
sophistication, it can require advanced expertise when it comes to an
enterprise’s hosting environment. Based on its long-standing
relationship and over 1,000 Magento implementations, Rackspace Hosting
has excellent experience with Magento environments. That history has
given Rackspace deep technical experience with Magento Enterprise. Add
to that Fanatical Support and a hybrid infrastructure, Rackspace is a
highly qualified provider of dedicated hosting for enterprise ecommerce
sites using Magento Enterprise.

**ABOUT MAGENTO**

Magento offers flexible, scalable ecommerce solutions designed to help
businesses grow and succeed online. The Magento platform is trusted by
more than 150,000 businesses, including some of the world’s leading
brands. Customers choose Magento because our cost-effective solutions –
built on open source technology – enable businesses of all sizes to
control and customize the look and feel, content, and functionality of
their online stores. We offer a range of resources, support, and
consulting services to help our customers get the most from their
Magento deployments, including education, training, and developer
certification programs. Our global community of partners and developers
gives customers access to robust third-party extensions and certified
professional integration help. Magento is owned by eBay Inc., a global
leader in commerce technology. Our relationship enables us to offer our
customers, partners, and community members a wealth of experience and
resources in commerce-related technologies, as well as access to
world-class, branded capabilities from eBay Marketplaces, PayPal, GSI
Commerce, and others. If you’re new to working with Magento, welcome. We
look forward to helping you grow your business.

**References:**

<sup>1</sup> Magento Usage Statistics – <http://trends.builtwith.com/shop/Magento>

<sup>2</sup> <http://www.magentocommerce.com/>, as of 29/03/2013

<sup>3</sup> <http://www.magentocommerce.com/product/enterprise-edition>, as of
29/03/2013
