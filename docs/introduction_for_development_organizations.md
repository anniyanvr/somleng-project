# Introduction to Somleng

By David Wilkie, CEO and Founder, Somleng

Last updated: . Previous diffs and versions are available [here](https://github.com/somleng/somleng-project/commits/master/docs/introduction_for_development_organizations.md). Improvements [welcome](https://github.com/somleng/somleng-project/pulls).

## Cambodia

### The Early Warning System

Cambodia is a country consistently ranked as one of the most vulnerable to the effects of natural disasters.

In order to deliver timely and potentially lifesaving information to people in disaster prone areas an Early Warning System (EWS) was conceived by the organization [People In Need (PIN)](https://www.clovekvtisni.cz/en/what-we-do/humanitarian-aid-and-development/cambodia) <sup>[1](#footnote-ews-article)</sup>.

[PIN](https://www.clovekvtisni.cz/en/what-we-do/humanitarian-aid-and-development/cambodia) realized that the EWS needs to be accessible to all Cambodians, regardless of literacy and Internet connectivity issues.

They decided to look into solution which uses voice based messaging for alerts and [(IVR)](https://en.wikipedia.org/wiki/Interactive_voice_response) for registration. In collaboration with [UNICEF](https://www.unicef.org/cambodia), they decided to use [RapidPro](http://rapidpro.io/), an open-source platform of applications that delivers rapid and vital real-time information, to manage the registration of users into the system.

With help from the Royal Cambodian Government, the [Telecommunication Regulator of Cambodia (TRC)](https://www.trc.gov.kh) and the [National Committee for Disaster Management (NCDM)](http://www.ncdm.gov.kh/) regulated that the Early Warning System must be provided free of charge by the [Mobile Network Operators (MNOs)](https://en.wikipedia.org/wiki/Mobile_network_operator) in Cambodia.

With the pieces of the puzzle coming together the problems that still remained were:

1. How to connect RapidPro to the MNOs for user registration?
2. How to send out automated alerts to people in at risk in the event of an emergency?

### Introduction to Somleng

[Somleng](http://www.somleng.org/) is an [Open Source](https://en.wikipedia.org/wiki/Open-source_software) implementation of [Twilio](https://www.twilio.com/). Unlike Twilio, Somleng gives you complete control over where it's connected to. Somleng can connect to [MNOs](https://en.wikipedia.org/wiki/Mobile_network_operator), [Telcos](https://en.wikipedia.org/wiki/Telephone_company), Aggregators or even your [own hardware](https://en.wikipedia.org/wiki/SIM_box).

Because [Somleng's REST API](https://github.com/somleng/twilreapi) is an open source implementation of [Twilio's REST API](https://www.twilio.com/docs/api/rest) you can swap Twilio out for Somleng in your existing applications seamlessly.

There's no monthly or per-minute fees for using Somleng and all the code is Open Source and available on [Github](https://github.com/somleng).

### Registrations through RapidPro and Somleng

People in Need (PIN) use RapidPro to design callflows for registering for the Early Warning System. RapidPro connects to Somleng out of the box and Somleng connects to the MNOs to handle inbound registrations through the short code 1294.

### Automated Alerts through Somleng Simple Call Flow Manager

[Somleng Simple Call Flow Manager (Somleng SCFM)](https://github.com/somleng/somleng-scfm) is an Open Source call flow manager specifically designed for queuing, retrying, scheduling and analysis of calls. It comes complete with it's own REST API for managing contacts, callouts and phone calls. Flood sensors which detect water level heights are connected to Somelng SCFM, which then triggers automated alerts thorugh Somleng.

### Results

Somleng collects [Real Time Data](http://rtd.somleng.org) from the Early Warning System and other projects which is available at [http://rtd.somleng.org](http://rtd.somleng.org).

Since the beginning of the project Somleng has processed around [113 K calls (229 K minutes)](http://rtd.somleng.org) for inbound registrations and [79.9 K calls (81.1 K minutes)](http://rtd.somleng.org) for outbound alerts, resulting in a total cost saving of around [$8,105.19](http://rtd.somleng.org) if [compared with Twilio](https://www.twilio.com/voice/pricing/kh).

### More Info

Our [technical write up](https://github.com/somleng/somleng-project/blob/master/docs/case_study_ews.md) contains more information about the project from a technical perspective.

## Somalia

In Somalia returnee households from Dadaab refugee camp in Kenya and vulnerable households in Bay and Bakool received emergency unconditional cash-based transfer assistance package to help them meet their needs during the current drought period.

In order to share information and get feedback about the program, a voice-based messaging solution was proposed. Voice messages were recorded in the [Somali language](https://en.wikipedia.org/wiki/Somali_language) and call flows were designed using [RapidPro](http://rapidpro.io/) by [Africa's Voices Foundation (AVF)](http://www.africasvoices.org/) in collaboration with [UNICEF Somalia](https://www.unicef.org/somalia/).

The price for terminating a call through [Twilio](https://www.twilio.com/) in Somalia is a whopping [$0.7680 per minute](https://www.twilio.com/voice/pricing/so) which would put the total cost at [$31,144.70](http://rtd.somleng.org)

### More Info

Our [technical write up](https://github.com/somleng/somleng-project/blob/master/docs/case_study_africas_voices.md) contains more information about the project from a technical perspective.

* Communication
* Cost
* Integration with Existing systems

## Solution

* Somleng (plugs into RapidPro and Somleng SCFM)
* Cost savings

## Pilots

* Somalia
* Cambodia

## Results

## Numbers

## Comparison with Twilio

* problem
* solution
* pilots
* results
* numbers
* comparison

<a name="footnote-ews-article"><sup>1</sup></a> [New innovations protecting lives in flood-prone Cambodia](http://unicefstories.org/2017/06/20/new-innovations-protecting-lives-in-flood-prone-cambodia/)

<a name="footnote-somleng-rtd"><sup>2</sup></a> [Somleng Real Time Data](http://rtd.somleng.org)