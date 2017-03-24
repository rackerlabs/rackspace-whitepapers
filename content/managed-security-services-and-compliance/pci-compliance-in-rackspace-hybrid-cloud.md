---
permalink: pci-compliance-in-rackspace-hybrid-cloud/
audit_date:
title: PCI Compliance in Rackspace Hybrid Cloud
type: whitepaper
created_date: '2013-08-06'
created_by: Rackspace Support
last_modified_date: '2017-03-14'
last_modified_by: Cat Lookabaugh
product: Managed Security Services and Compliance
product_url: managed-security-services-and-compliance
---

Authors:
Mahesh Gande, Senior Solutions Manager
Francis Ofungwu, Product Manager for Rackspace Security Solutions
Jarret Raim, Rackspace Cloud Security Product Manager
Lizetta Staplefoote, Online Content Strategist

### Introduction

Meeting Payment Card Industry – Data Security Standards (PCI-DSS) can be
a complex and costly exercise for the average e-commerce merchant. This
may explain why 96% of 2011 breach victims were not compliant as of
their last assessment or had never been validated<sup>1</sup>.

There is no one-size-fits-all approach to achieving and maintaining
compliance. Merchants without the expertise to execute an effective
compliance program should seek guidance from external partners to
supplement their knowledge gaps and infrastructure deficiencies.

### The 12 Requirements of PCI-DSS Compliance

PCI-DSS is a set of comprehensive requirements for enhancing payment
account data security. The standard was developed by the PCI Security
Standards Council, which includes American Express, Discover Financial
Services, JCB International, MasterCard Worldwide and Visa to help
facilitate the broad adoption of consistent data security measures on a
global basis.
*82% of breached operations weren't compliant with PCI-DSS standards for
protection of stored data<sup>2</sup>.*

PCI compliance is broken down into 12 steps across six categories of
protection:

#### 1.  Build and Maintain a Secure Network

-   **Requirement 1**: Install and maintain a firewall configuration to protect
cardholder data.

Establishes firewall and router configuration standards that mandate testing,
testing procedures, and a review of configuration rule sets every six months.

-   **Requirement 2**: Do not use vendor-supplied defaults for system passwords
and other security parameters.

Addresses password hygiene with respect to vendor-supplied passwords that if
combined with hacker tools able to show all of your networked devices can make
you a sitting duck for unauthorized entry.

#### 2.  Protect Cardholder Data

-   **Requirement 3**: Protect stored cardholder data.

Defines storage, encryption, and retention of cardholder data and authentication
data for required business uses. Also covers the documentation and protection of
the keys used to encrypt cardholder data.


<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/new1.png %}" width="434" height="211" />

-   **Requirement 4**: Encrypt transmission of cardholder data across open, public networks

Refers to the implementation of strong cryptography and security protocols such
as SSL/TLS, SSH or IPSec to safeguard sensitive cardholder data during
transmission over open, public networks (Internet and mobile). Additionally,
wireless networks transmitting cardholder data or connected to the cardholder
data environment must use industry best practices to implement strong encryption
for authentication and transmission.

#### 3.  Maintain a Vulnerability Management Program

-   **Requirement 5**: Use and regularly update anti-virus software or programs

Any system potentially affected by malware must be protected by anti-virus
software that is current, actively running, and generating audit logs.

-   **Requirement 6**: Develop and maintain secure systems and applications

Application code must adhere to secure coding guidelines including reviewing
custom application and third-party code to identify vulnerabilities.

#### 4.  Implement Strong Access Control Measures

-   **Requirement 7**: Limit access to system component and cardholder data to
only those individuals whose job requires such access

To protect critical data from access by unauthorized personnel inside and
outside of the business, systems and documented processes must exist to restrict
access to cardholder data using role-based access controls (RBAC) set to "deny
all" unless access to cardholder data and systems is specifically granted.

-   **Requirement 8**: Assign a unique ID

Any user granted access to cardholder data must have a unique identification so
that actions taken on critical data and systems are performed by, and can be
traced to, known and authorized users. This requirement also includes provisions
around using two-factor authentication via token and storage of user passwords.

-   **Requirement 9**: Restrict physical access to cardholder data

To safeguard against physical media containing cardholder data being removed or
compromised, areas where devices, data, systems, or hardcopies of cardholder
data must be restricted from general access. This applies to both electronic
systems for all online merchants and paper receipts and POS systems for brick
and mortal establishments.

#### 5.  Regularly Monitor and Test Network

-   **Requirement 10**: Track and monitor all access to network resources and cardholder data

Logging mechanisms and the ability to track user activities are critical for
effective forensics and vulnerability management. Logs should record specific
actions and create an audit trail including, at a minimum: user identification,
type of event, date and time, success or failure indication, origination of event,
and identity or name of affected data, system component or resource. These logs
should be reviewed daily and audit trails retained for at least a year.

-   **Requirement 11**: Regularly test security systems and processes

Run internal and external network vulnerability scans at least quarterly and
after any significant change in the network or infrastructure, application
upgrade or modification. After passing the initial compliance scan, merchants
must pass four more consecutive quarterly scans by an Approved Scanning Vendor
(ASV) as a requirement for compliance. This provision also includes the use of
up-to-date network intrusion detection systems (IDS) and file integrity
monitoring tools to check for and alert to system compromise or unauthorized
modification of critical files.

*Only 6% of breached organizations report having regular security systems testing
and processes<sup>3</sup>.*

#### 6.  Maintain an Information Security Policy

-   **Requirement 12**: Maintain a policy that addresses information security for all personnel

Establish, publish, update, and disseminate a security policy that addresses
compliance requirements. This policy should include an annual review process for
identifying vulnerabilities and formally assessing risks. Defined usage policies
for employee screening, remote access, wireless, removable electronic media,
laptops, tablets, handheld devices, email and internet are also required.

### Who Needs PCI-DSS Compliance?

If your business meets either of these criteria, you should have a
PCI-DSS strategy in place pertaining to Cardholder data (such as PAN
(Primary Account Number) plus cardholder name, expiration date, service code):

-   Do you store, process, or transmit Cardholder data?
-   Do you provide services to merchants who process, store, or transmit
    Cardholder data?

#### Understanding PCI-DSS Merchant Levels And Validation Types

The process and frequency of validating compliance with these 12 steps
is determined by your merchant level and security assessment types
below:

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/pci2a.png %}" width="499" height="195" />

Your validation type determines which SAQ you need to complete.

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/pci3a.png %}" width="502" height="220" />

***This is an example of VISA card brand classifications. Other industry standards exist.***

#### Why is Compliance Important?

Non-compliance to PCI-DSS could lead to:

-   Loss of reputation
-   Increased costs for accepting credit card transactions
-   Substantial fines associated with security breaches and
    non-compliance

Should a breach occur as a result of non-compliance, there are discovery
and containment costs for investigating the incident, remediation
expenses, and attorney and legal fees in addition to:

-   Loss of customer confidence
-   Lost sales and revenue
-   Brand degradation or drop in public stock value
-   Fines and penalties for non-compliance with PCI-DSS
-   Termination of the ability to accept payment cards
-   Fraud losses
-   Cost of reissuing new payment cards
-   Dispute resolution costs
-   Cost of legal settlements or judgments

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/pci4a.png %}" width="551" height="369" />

#### Partnering for PCI-DSS Compliance

Because of the complexity and necessity of maintaining PCI-DSS, many
merchants opt to enlist solutions partners to provide the tools needed
to build compliant infrastructure elements.

Even with partners involved, PCI-DSS compliance is a dual responsibility
shared by you and your provider. Hosting with a provider that offers
PCI-DSS compliant infrastructure doesn't automatically make you
compliant. For example, a simple coding mistake can still leave a
business open to an exploit even with strong hosting and security
partners. As you can see below, each entity bears responsibility:

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/PCI23.png %}" width="502" height="276" />

### Achieving PCI-DSS Compliance

#### Questions to ask:

1.  Has your bank contacted you about PCI-DSS or stipulated a date when they
require compliance?

*Why this is important: May determine how aggressive your compliance timeline needs to be.*

2.  Have you contacted your Acquirer about PCI-DSS compliance?

*Why this is important: The Acquirer is typically responsible for merchant compliance.*

3.  What payment brand compliance program (AMeX, Discover, JCB, Master-Card,
Visa) will you subscribe to?

*Why this is important: Each payment brand has it's own validation requirements.*

4.  What Self-Assessment Questionnaire will you complete?

*Why this is important: Seek assistance from a Qualified Security Advisor (QSA)
to determine which
[PCI Data Security Standard Self-Assessment](https://www.pcisecuritystandards.org/merchants/self_assessment_form.php)
questionnaire fits your business processes.*

5.  Are you a Service Provider, Merchant, or both?

*Why this is important: To determine which validation requirements apply to your business.*

6.  Do you have the in-house resources to drive compliance?

*Why this is important: To identify gaps and assess where partnerships bring the most value.*

#### Options available:

The cornerstone of PCI-DSS is data protection. Your company policies and
credit card transaction volume, along with other business factors not
discussed here, should guide where you decide to store this data and how
you protect it. Options to explore:

-   Store credit card data at a provider offering PCI-DSS compliant infrastructure.
-   Store credit card information using a third-party payment gateway transmitting
data server side using APIs. They collect the data and send it encrypted to your
servers.

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/pci5a.png %}" width="499" height="103" />

    How it works:

    1.  Upon the customer's request to checkout, a form is displayed to your
    customer to collect the required payment information. When the customer
    submits the form, the data is encrypted and then sent to your servers.
    2.  Using a client library, a server-to-server (S2S) call to payment gateway
    is made to complete the processing of the transaction.
    3.  The payment gateway processes the transaction and returns a response to
    your server.
    4.  This response can be used to display relevant data to the customer in
    the browser, such as the status of the transaction.


-   Store credit card information using a third-party payment gateway transmitting
data from the client browser before reaching your server.

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/pci6a.png %}" width="311" height="287" />

    How it works:

    1.  Upon the customer's request to checkout, a form is displayed to your
    customer to collect the required payment information. When the customer
    submits the form, the data is posted directly to the payment gateway over
    an SSL connection.
    2.  The payment gateway then stores the data. Because the payment gateway
    redirects the customer back to your site without displaying any content,
    the customer never knows that they've even left your site.
    3.  The customer's browser requests the redirected URL from your site. The
    query string for the request URL contains a token that identifies the stored
    data from Step 1.
    4.  Using the client library, you make a server-to-server (S2S) call to
    payment gateway is made to complete the processing of the request. This step
    confirms that if the customer doesn't complete the redirect back to your
    site, the payment gateway will not complete the transaction.
    5.  After receiving the confirmation request, the payment gateway will run
    the transaction and send a response.


#### Deciding between storing data in-house or using payment gateway

Compare the cost of using a third-party payment gateway with the cost of
storing credit card information in your data center or a provider's data
center. Compare these calculations to guide your decision:

-   Calculate the cost of additional products/services required to store credit
card data in-house per month. Rackspace can help you create sample configurations
and provide estimates about cost.
-   Calculate the cost of using a third-party payment gateway per month = number
of transactions * cost of transaction charged by payment gateway + online
revenue * % of revenue to be paid to payment gateway vendor.

If you find storing data on-site is more expensive than the gateway,
consider moving to a gateway. If using the payment gateway is more
expensive or a third party gateway is incompatible with other company
policies, consider storing data in a PCI-DSS compliant data center on
dedicated servers.

#### Deciding between transmitting data from the server or browser

Using APIs from client browsers excludes your server infrastructure from
the scope of PCI-DSS compliance as all sensitive data is transmitted
between the user and the payment gateway.

When you choose to transmit credit card information from the server side
using third party payment gateway APIs, your server infrastructure
becomes part of PCI-DSS compliance since sensitive data crosses your
infrastructure.

#### PCI-DSS compliant solution for Rackspace Dedicated Hosting

Example of PCI-DSS compliant reference architecture without a payment
gateway:

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/security-sample-architecture.png %}" />

Use the following table to align your PCI-DSS compliance needs with
Rackspace services:

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/pci7a-chart1b.png %}" />

#### PCI compliant solutions for Rackspace Cloud Hosting

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/pci-compliance.gif %}" width="324" height="153" />

When you host your environment with Rackspace, you may also
sign up with a separate payment processor to provide
tokenization—replacing credit card data with meaningless numbers or
"tokens." When you accept a payment, non-PCI-DSS data routes to your
Rackspace-hosted environment, while the tokenized credit card data
routes to your payment processor.

Since your customers’ credit card data does not route to your Rackspace
hosted infrastructure—only the payment processor—your Rackspace
environment stays out of the scope of your PCI-DSS requirements.

### Conclusion

A key step to a successful compliance program is the establishment of
continuous management of the people, processes and technology. It is a
common misconception for many small and large organizations that
investing solely in technologies will solve their security and
compliance requirements. Technologies like firewalls, Intrusion
Detection Systems (IDS) and log management appliances are only as
effective as the people and processes in place to install and manage
them.

This is a lesson that Transport for London (TFL), responsible for
managing transport services across England’s capital city, learned while
trying to achieve PCI-DSS compliance for its travel payment system.
Their system was handling up to 40,000 visits per day with over 2.5
million registered users. Being a 24-hour business, 365 days of the
year, they couldn’t risk a breach or other outage disrupting operations.
They turned to Rackspace for the pieces of the puzzle they needed [to
become fully compliant](http://www.rackspace.com/security/domains/#pci).
"It is probably true to say that without the considerable amount of help
from Rackspace we could not have passed the exceptionally stringent
PCI-DSS audit. Rackspace certainly went above and beyond their remit to
ensure that everything was perfect for us," says Aingaran
Somaskandarajah, Technical Lead, Oyster Card.

Let Rackspace be your trusted partner in the PCI-DSS journey. We can
help you navigate the maze with infrastructure and solution requirements
to help reduce the scope and complexity of your compliance efforts.
[Contact us today to discuss your needs or explore PCI-DSS Compliance
services now](http://www.rackspace.com/ecommerce-hosting/pci/).

<img src="{% asset_path managed-security-services-and-compliance/pci-compliance-in-rackspace-hybrid-cloud/pci8a.png %}" />
[Rackspace Ecommerce Hosting](http://www.rackspace.com/ecommerce-hosting/)

**References:**

<sup>1</sup> [http://www.verizonenterprise.com/resources/reports/rp_data-breach-investigations-report-2012_en_xg.pdf](http://www.verizonenterprise.com/resources/reports/rp_data-breach-investigations-report-2012_en_xg.pdf%20)

<sup>2</sup> ibid.

