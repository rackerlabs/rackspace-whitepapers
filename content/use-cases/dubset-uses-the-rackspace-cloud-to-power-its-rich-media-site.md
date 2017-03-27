---
permalink: dubset-uses-the-rackspace-cloud-to-power-its-rich-media-site/
audit_date:
title: Dubset Uses the Rackspace Cloud to Power Its Rich Media Site
type: whitepaper
created_date: '2012-09-28'
created_by: Laurel Wamsley
last_modified_date: '2017-03-22'
last_modified_by: Cat Lookabaugh
product: Use Cases
product_url: use-cases
---

<a href="http://dubset.com/">
   <img src="{% asset_path use-cases/dubset-uses-the-rackspace-cloud-to-power-its-rich-media-site/Dubset_logo_color_print1.png %}" width="376" height="101" />
</a>

**CUSTOMER'S BUSINESS:** Streaming online music, curated and mixed by DJs

**CHALLENGES:** Reliable and affordable computing, storage and streaming

**RACKSPACE<sup>&reg;</sup> SOLUTION:** [Cloud
Servers](http://www.rackspace.com/cloud/cloud_hosting_products/servers/)
for production, databases and development; [Cloud
Files](http://www.rackspace.com/cloud/cloud_hosting_products/files/)
with for streaming

**OUTCOME:** Growing fast and successfully streaming up to 2TB of data
per month

**[Click here to download the full case
study.](http://c1776742.r42.cf0.rackcdn.com/downloads/pdfs/CaseStudy_Dubset.pdf)**

### The company

Dubset is the next generation of internet radio, curated by the world's
top DJs. Users can discover new music recorded live at premier clubs and
exclusive events, find and follow new DJs, and create their own custom
channels.

The Brooklyn-based company is growing fast. Dubset aligns incentives
between DJs, recording artists and music fans. The company uses a
patent-pending technology called MixSCAN to fingerprint mixes uploaded
to Dubset.com enabling them to accurately monitor music found within
mixes, compensate artists and copyright holders for use of their
content, and make individual tracks available for download.

“All of these music startups out there try to outsource your playlist to
an algorithm,” says Charlie Robbins, Technology Director at Dubset. “But
we’ve crowdsourced it to real people — DJs. It’s going to be challenging
for a computer to ever get that good.”

### Streaming Media Via Cloud Files and the CDN-Powered by Akamai

Because Dubset’s business is streaming music, they needed a hosting
solution that could easily scale up, and that wouldn’t cost them
enormous bandwidth charges. Rackspace Cloud Files was the ideal
solution.

“We use a lot of Cloud Files, because we’re streaming to CDN,” says
Robbins. “We were on Slicehost for a while, literally serving this stuff
off the disk. But our traffic got to a point where we couldn’t even
backup the servers on Slicehost, because it was too big. If you get
above 50GB or so, it becomes a network storage issue.”

So Robbins and his team moved their data onto Rackspace Cloud Files.
“Cloud Files works great,” says Robbins. “It’s really simple, and it’s
cheap. We’re streaming 1.5-2TB a month — a huge amount of data. With
Cloud Files, we don’t have to worry about it, it just works.”

Cloud Files’ CDN powered by Akamai is a major advantage for Dubset, says
Robbins. “Most of our traffic is on CDN. By using Cloud Files, we’ve
offloaded a ton of the work that used to be done by the server onto the
CDN.”

### What They Needed: Flexibility and Computing Power

“I’ve been using the Rackspace Cloud for almost three years now,” says
Robbins. “I was a Slicehost user, and followed the acquisition by
Rackspace closely.”

For Robbins, the options allowed by the Rackspace Cloud were a major
selling point. “One things about the Rackspace Cloud that I like is you
can get really small slices,” he says. “Other providers have sizes that
are too big for a lot of applications. If you want to take full
advantage of virtual servers, you want to have ones that are small
enough for low traffic sites.”

“When you’re developing, most of the time you want to turn on a server
and leave it on, especially in dev mode,” explains Robbins. “You’re just
testing; it’s not live traffic. If you need five servers, why spin up
five full-size servers elsewhere for $75 for a month, when you could
spin up five Rackspace servers for $10 a month?”
Robbins also appreciates the reliability he has found with Rackspace:
“We’re a platform built on Rackspace. We had 100 percent uptime last
year.”

### A Straightforward — and Powerful — Architecture

Dubset’s network architecture is relatively straightforward. They use
about ten Cloud Servers, including a Ruby on Rails front-end server, a
MySQL database server, two Node.js servers running MixSCAN (a RESTful
job-based API), and two CouchDB servers in replication. The rest of
their servers are used for development.

“We run MixSCAN in both production and development with separate
databases in the same CouchDB,” explains Robbins. “Interestingly,
because of one of our software vendors we have to run two different
operating systems: both CentOS and Ubuntu. Cloud Servers made the setup
of a default CentOS image painless, even though none of our dev team had
ever used it before.”

For Robbins, the attraction of the Rackspace Cloud was both the Cloud
Servers and Cloud Files API. “They are modern, RESTful, JSON-based APIs
that are easy to work with.”

Furthermore, says Robbins, “Creating images is super easy on the
Rackspace Cloud. To backup Cloud Servers, I can literally make that call
for the Rackspace API — that whatever’s on this machine right now,
that’s an image. That goes in Cloud Files, and it’s really easy and
friction-free. That’s far more appealing than the process for creating
images on other hosting providers.”

### The Difference is Fanatical Support<sup>&reg;</sup>

Though their business has grown, Dubset’s choice for hosting continues
to be Rackspace. “It’s [the ***fanatical
support<sup>&reg;</sup>****](http://www.rackspace.com/whyrackspace/support/),
really,” explains Robbins. “There are times when I’m in the chat pretty
regularly; the guys in there know me. I’ve heard nightmares from people
about other providers’ support, which can be self-service to a fault.”

As Dubset grows, they’ll consider using dedicated servers, as well. “At
some point we will use a combo of cloud and dedicated,” says Robbins.
“And Rackspace would be the first we look at. It makes sense for the
company I’m getting hosting from to have hosting as their primary
business.”
