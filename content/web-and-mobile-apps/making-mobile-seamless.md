---
permalink: making-mobile-seamless/
audit_date:
title: Making Mobile Seamless
type: whitepaper
created_date: '2014-06-30'
created_by: Garrett Heath
last_modified_date: '2017-03-03'
last_modified_by: Cat Lookabaugh
product: Web and Mobile Apps
product_url: web-and-mobile-apps
---

### Introduction

With advancements in technology infrastructure, WiFi availability and
application performance, the mobile web is faster than ever. In spite of
these improvements, mobile devices sometimes hit dead zones where data
access is not available. This can be frustrating, not only for users,
but also for businesses who have taken the time to build their mobile
app on [high performing cloud servers](http://www.rackspace.com/cloud/). But
even with an uninterrupted signal from the tower, there are still challenges
with creating a solid user experience. Put simply, mobile experience
differs greatly from its desktop counterpart. As you begin to craft a
mobile application, consider these seven strategies to help provide the
best end-user experience.

### Creating the Effect of Always Being Connected

#### 1. Sync Offline Actions When Back Online

One strategy is to create the effect of an instant response, even when
the device has lost connection to the carrier. This allows the
application to continue delighting users without an active network
connection. Instagram<sup>&reg;</sup> was one of the first major applications
to understand this phenomenon.<sup>1</sup>

Instagram users are still able to “Like” or comment on a photo when
their mobile device isn’t connected to a network. Clicking the heart
button changes it from white to red, creating the effect that the “Like”
is immediately recorded. Users can comment on their friend’s photos, and
the comments will be synced when the app connects back to the web. While
many apps hang if they can’t connect, adopting a workflow where data can
be synced once the smartphone connects back to the tower can improve
the overall user experience.

Inside your team, consider what pieces of data aren’t critical. Allow
users to control those aspects when the device is offline and then find
a way to update the data when the device is reconnected.

#### 2. Process Data Locally When It Makes Sense

With the iPhone<sup>&reg;</sup> 3G, a user could simply say, “Call Joe,” and
the phone would call their friend, even without a data connection present.
Only a couple of bars of voice service are needed to make a phone
call—all of the voice recognition and processing was done locally on the
phone.

Fast forward to Siri<sup>&reg;</sup> and the iPhone5. A user is now required to
have a data connection when using the voice command to make a call. The
request leaves the phone, it’s processed on a server and then Joe is
called. The functionality doesn’t work if the user is in a data dead
zone—even if there are enough bars for voice service to actually make a
call.

Combat this frustration by designing a mobile experience that allows
some tasks to be completed on the device itself. Processing actions
locally may do more than speed up response times when a tower connection
is present, it might mean getting the task completed altogether if
there’s not a network connection.

#### 3. Predict and Preload

Finding a way to predict and preload desired information can make a
dropped connection a small bump in the road instead of a major issue.
Google<sup>&reg;</sup> does this well in their Chrome browser. As the user
searches for information, Google loads the site in the background for the URL
that is most likely to be clicked. When a user clicks that URL, the
website appears instantly on the screen. The heavy lifting was completed
in the background, in advance.

Look to this idea when developing mobile apps. Whether it’s preloading a
map based on the user’s location, or even a group of products this
customer is likely to view next, predicting user behavior and
downloading data in advance can result in an uninterrupted experience.

### Maximizing a Mobile Connection

#### 4. Transfer the Smallest Amount of Data Possible

While technologies like LTE have improved the throughput of cellular
networks, latency is still a factor. You rarely see the performance of a
physical internet connection. For this reason, mobile applications
should aim to transfer the smallest amount of data possible to the end
device.

Deliver data faster to mobile devices by shrinking images, reducing
video quality and compressing data within API calls. By understanding
the device behind the incoming request, the app can serve up the
particular content that makes the most sense for its particular screen
size. This is the ethos behind the “mobile first”
development movement.<sup>2</sup>

#### 5. Adopt a CDN for Storing Data

A [content delivery network (CDN)](http://www.rackspace.com/cloud/files/features/?page=cdn#cdn)
is a grouping of geographically dispersed servers that stores multiple copies
of data in specific locations. The CDN then delivers the data from a
server physically closer to the person making the request. For example,
a user in London would receive a file from a server in the U.K. rather
than from one in the United States.

Much has been made about how this feature of the CDN can speed up the
delivery of data to the end user. However, the real value of the CDN for
mobile apps is that it creates many copies of the data, which can enable
a highly requested item to remain available online. Whereas a popular
file can overtax a server from a flood of requests, replicating files
across the CDN ensures they are always accessible, without overburdening
your web servers.

There are indeed some speed advantages to using a CDN, but the biggest
beneficiaries are the low latency, high throughput network connections
(such as physically plugging into the web with an Ethernet cord). “It’s
true that a CDN might shave off 30ms of load time. However, it isn’t
going to matter as much to the person on a smartphone who has to wait
600ms for the data to hop between the tower and their device,” Major
Hayden, Rackspace Engineer, says.

But this doesn’t mean that you should abandon the CDN for storing files
needed in your mobile application. While the mobile app may not gain
much in terms of speed, you do gain plenty in terms of reliability.

### Handling High Growth and Securing the App

#### 6. Prepare for Horizontal Scaling

You never know if your mobile application is a success or a bust.
However, a deluge of users requires a massive amount of compute power.
One way to handle the mounting traffic is to enable your application to
scale out horizontally. For each piece of your environment—storage, web
or database nodes—make sure that you can acquire more as needed. Scaling
up vertically (using larger and larger nodes with more resources)
is only a short-term fix and isn’t sustainable.

While manually scaling can be a pain, there are many different DevOps
tools that can help you with this process. Infrastructure automation
tools like Chef and
[Rackspace<sup>&reg;</sup> Auto Scale](http://www.rackspace.com/cloud/auto-scale/)
are just a couple ofoptions. Furthermore, by taking advantage of the
[Rackspace Hybrid Cloud](http://www.rackspace.com/cloud/hybrid/) you can employ
both dedicated and cloud servers. The hybrid cloud gives you a combination of
physical infrastructure to handle the day-to-day load with the ability
to burst in the cloud as your mobile app takes off. But it is key
to integrate these tools into the application from the start.

#### 7. Secure Your Mobile-Only APIs

Mobile applications often have an API designed specifically for
smartphone and tablet interaction. It’s tempting for developers to relax
security measures, since devices without a command prompt typically hit
this particular API. After all, there’s no way for a user to inspect
those API calls on their iPhone, right?

Wrong.

By setting up a proxy between a smartphone and the web service, users
are able to view API calls and identify potential weaknesses. When a
soft spot is found, a malicious user can send malevolent API calls while
pretending to be a valid mobile device, wreaking havoc within your
application. Remember this motto: All traffic is a threat. By not
trusting any type of user input—even if it should be from a mobile
device—you can put adequate security measures in place to keep your app
available users safe.

### Conclusion

As our society becomes more mobile, the demand for mobile applications
to work seamlessly increases. Yet even with the bedrock of high
performance hardware, mobile apps are often at the mercy of the cellular
provider. Additionally, there are unique challenges for mobile
applications, even when there is a constant cellular data connection.

The infrastructure powering the cellular network is evolving and
improving. And while cellular speeds and reliability will continue to
increase, we can’t yet expect these advancements for a present day
mobile application. Adopting some of these best practices and looking at
mobile applications differently from desktop apps, you are able to
create a more seamless experience for your users.

**Sources**

<sup>1</sup> <http://getting-real.com/blog/the-secret-to-instagrams-blazing-fast-mobile-design/>
<sup>2</sup> <http://www.rackspace.com/blog/embracing-mobile-first-design/>
