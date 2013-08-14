Title: XMPP Roundup 12
Date: 2009-09-16 15:04:30
Author: Nyco
Slug: xmpp-roundup-12
Category: post
Tags: 
Summary: description:
Link: http://xmpp.org/2009/09/xmpp-roundup-12/
post_id: 540


[Reporter: Nicolas Vérité, assisted by Peter Saint-Andre] This Roundup is the third "almost-monthly" review of the XMPP-sphere this summer. It shows again a lot of activity as you can see through these pointers to articles, software, services, and of course specifications, the core of our work here at the XSF. **Articles** _XMPP web project walk-through_ Boris Okner describes a weather [web application using ejabberd and strophe](http://rfid-ale.blogspot.com/2009/08/xmpp-web-project-walkthrough.html) over BOSH. You can [play with the demo](http://weazard.chirpber.com:8000/weazard.html) (username: shared, password: shared). _Scalable XMPP bots with erlang and exmpp_ ProcessOne has published a series of articles on how to build bots on top of the exmpp library (in Erlang). These come in three parts: [part I](http://www.process-one.net/en/blogs/article/scalable_xmpp_bots_with_erlang_and_exmpp_part_i/), [part II](http://www.process-one.net/en/blogs/article/scalable_xmpp_bots_with_erlang_and_exmpp_part_ii/) and [part III](http://www.process-one.net/en/blogs/article/scalable_xmpp_bots_with_erlang_and_exmpp_part_iii/). _Meet the Extensible Messaging and Presence Protocol (XMPP)_ IBM developerWorks has published [an article by Tim Jones introducing XMPP as a multipurpose instant messaging architecture](http://www.ibm.com/developerworks/xml/library/x-xmppintro/index.html?S_TACT=105AGX06&S_CMP=EDU) that is not only suited for chat applications. There is an example in Ruby using the xmpp4r library. _XMPP powering the “internet of things”?_ A few "internet of things" (or "IoT") projects are using [XMPP as a communication layer](http://www.process-one.net/en/blogs/article/xmpp_powering_the_internet_of_things/): this could well show an area of development for XMPP. **New and updated software** _Psi 0.13_ The verson 0.13 of Psi, the well-known free software Jabber client, has been [released by Justin Karneges on the 28th of July](http://lists.affinix.com/pipermail/psi-devel-affinix.com/2009-July/008770.html). Sorry for that miss on the previous Roundup. The main new feature a top-requested one: Jingle voice! A few days later, Justin announced the [0.14 plan](http://lists.affinix.com/pipermail/psi-devel-affinix.com/2009-August/008797.html), you can read the interesting follow-up. _Pidgin 2.6_ In yet another big advance for Jingle, the Pidgin team has released the version 2.6 of this multi-protocol IM client, with [Jingle voice and video](http://theflamingbanker.blogspot.com/2009/08/pidgin-260-its-about-time.html) for Linux and Mac OS X. Support for Jingle file transfer is also on the way. _Silent Diving Seagulls_ [Silent Diving Seagulls](http://blog.abi.sh/2009/silent-diving-seagulls/) is a multi-platform Firefox extension for desktop notifications. It is based on xmpp4moz. This article also points to [Yapper](http://github.com/progrium/yapper), an XMPP interface for the Growl notifier (for Mac OS X). _WideNoise_ [WideNoise](http://www.readwriteweb.com/archives/widenoise_monitor_noise_levels_iphone.php) is an iPhone application using XMPP and [OpenSpime](http://openspime.org/) to track noise: it will display decibel levels in maps. _ejabberd 2.1.0 beta_ ejabberd has been released in version 2.1 [beta1](http://www.process-one.net/en/blogs/article/ejabberd_2.1_beta1_has_been_released_for_testing_purposes/), [beta 2](http://www.process-one.net/en/blogs/article/annoucing_ejabberd_2.1.0_beta2/), and [rc1](http://www.process-one.net/en/blogs/article/ejabberd_2.1_rc1_has_been_released/) for testing purposes, providing a lot of PubSub improvements, and an experimental STUN server for NAT traversal. _eewdata_ [eewdata](http://github.com/skubota/eewdata/tree/master) is a simple Perl module for the Japanese [Earthquake Early Warning](http://en.wikipedia.org/wiki/Earthquake_Early_Warning_%28Japan%29), that has an XMPP example for real-time notification. _Sixties_ Clochix has extended the opensource library XMPPHP, which now talks PubSub (plus Jabber Search and Ad-Hoc Commands), under the GPL license of course, and the name [Sixties](https://labo.clochix.net/wiki/sixties) (related to XEP-0060). You can read this in a mention on this [blog post](http://www.clochix.net/post/2009/08/30/Nouveau-fan-des-Sixties) in French. _XMPP on Google App Engine_ Google has released the version 1.2.5 of their Java and Python SDK for the App Engine (or GAE), [including](http://googleappengine.blogspot.com/2009/09/app-engine-sdk-125-released-for-python.html) in fact [most current XMPP features](http://googleappengine.blogspot.com/2009/09/app-engine-sdk-125-released-for-python.html). _Orbited_ [Orbited](http://orbited.org/) is a Python library published under the MIT license, for real-time communication in the browser, including support for XMPP, IRC, and STOMP (ActiveMQ, RabbitMQ). _SocialVPN_ [SocialVPN](http://code.google.com/p/socialvpn/) is a free and open-source P2P Social Virtual Private Network (VPN). It integrates social networking and peer-to-peer networking to create a VPN. SocialVPN has XMPP as a backend. _Tinder 1.1.0_ Guus der Kinderen has announced the version 1.1.0 of the Tinder XMPP library fixing concurrency (threading) issues and other bugs. _ejabberd migration kit_ [ejabberd 2.1.0 supports XEP-0227](http://www.process-one.net/en/blogs/article/ejabberd_migration_kit/), a.k.a. PIEFXIS for Portable Import/Export Format for XMPP-IM Servers. **New and updated services** _Data synchro from Google_ Google has announced that [data synchronization from the browser is done through XMPP](http://arstechnica.com/open-source/news/2009/08/google-reveals-plans-for-chrome-cloud-synchronization.ars) in their Chrome browser. Opera Link and Mozilla Weave provide the same feature, but do not rely on XMPP (yet!). _Switchub_ [Switchub](http://switchub.com/) is a service for push notifications, using web hooks and XMPP. For now it is only available on invite. _Dispatch.io_ [Dispatch.io](http://www.dispatch.io/) is a notification service for Growl using XMPP. _Shion_ [Audacious Software](http://www.audacious-software.com/) has released [Shion](http://www.audacious-software.com/products/shion/), a home automation software for Mac OS X, that lets you remotely control and monitor your devices and appliances. _JabberHooks_ [JabberHooks](http://www.jabberhooks.com/) lets you receive XMPP messages via HTTP POST (aka [webhooks](http://webhooks.org/)). _PubSubHubbub to XMPP gateway_ Matt Mastracci has released a [PubSubHubbub to XMPP gateway](http://grack.com/blog/2009/09/09/pubsubhubbub-to-xmpp-gateway/) on [appspot](http://pubsubhubbub-xmpp.appspot.com/). _Mumbai Blood Bank Locator Agent_ The [Blood Bank Locator bot](http://iromin.wordpress.com/2009/09/16/mumbai-blood-bank-locator-agent/) is a small XMPP application written for and running on the Google App Engine, that enables you to locate blood banks in different areas in Mumbai. **New and updated specs** _XMPP Relay Nodes_ [XMPP relay nodes](http://xmppjingle.blogspot.com/2009/07/jingle-relay-nodes-full-description.html) are a technology that grew out of discussions at the XMPP Summit in Brussels earlier this year. They are much like supernodes in Skype, but slightly better: any XMPP client can become a relay peer for the rest of a P2P Jingle network, typically on an opt-in basis (e.g., anyone in your buddy list can borrow some of your bandwidth). This has not been proposed as an official XSF "XEP" yet. _Linked Process_

## Comments

**[nyco](#29 "2009-09-18 09:58:37"):** The spanish community has translated the Roundup: http://www.jabberes.org/node/1139 Many thanks!

**[nyco](#30 "2009-12-23 14:40:18"):** The french community has also done that translation here: http://news.jabberfr.org/?p=31
