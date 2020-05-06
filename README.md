# The Somleng Project

![Somleng](https://github.com/dwilkie/somleng-project/raw/gh-pages/images/talking_in_the_factory.jpg "Credit: Fani Llaurado")

## What is The Somleng Project?

The Somleng Project is a collection of open source telephony tools which can be used to build powerful Voice applications. The goal of the project is to break down the economic and accessibility barriers to building telephony applications. Read more about Somleng [here](https://github.com/somleng/somleng-project/blob/master/docs/what_is_somleng.md)

## Who's using it?

Check out [Somleng's Real Time Data](http://somleng-rtd.herokuapp.com) to see who's currently using Somleng. You can also read about our case studies in the [Introduction to Somleng article](https://github.com/somleng/somleng-project/blob/master/docs/introduction_for_development_organizations.md).

## How can I use it?

Follow the [GETTING STARTED](https://github.com/somleng/somleng-project/blob/master/docs/GETTING_STARTED.md) guide to get started.

You can also connect Somleng to Call Flow Managers such as [RapidPro](https://www.rapidpro.io/) or [Somleng Simple Call Flow Manager (Somleng SCFM)](https://github.com/somleng/somleng-scfm) or connect it your own application using any of [Twilio's Open Source libraries](https://www.twilio.com/docs/libraries).

## Project Resources

The various open source tools that make up The Somleng Project are listed below. More detailed information about each technology can be found in the individual project repositories.

The diagram below shows how each technology is connected together. Depending on your specific needs you may choose to use all or just some of the open source tools described below.

![Somleng-Overview](https://docs.google.com/drawings/d/e/2PACX-1vSMYTP8Rk_N_I6BWrc4QWhRl6EaAOEyWJTzeXRoKmPWzdqIiQyzSH9YWz3wzCin2H227GT0CSkkop9K/pub?w=1478&h=728)


### Twilreapi

[Twilreapi](https://github.com/dwilkie/twilreapi) is an Open Source implementation of [Twilio's REST API](https://www.twilio.com/docs/api/rest). You can use [Twilreapi](https://github.com/dwilkie/twilreapi) to create accounts, enqueue calls and SMS and view your dashboard.

### Somleng-Adhearsion

[Somleng-Adhearsion](https://github.com/dwilkie/somleng) is an [Adhearsion](https://github.com/adhearsion/adhearsion) application which can handle the delivery of outbound calls and the processing of inbound calls. You can connect [Somleng-Adhearsion](https://github.com/dwilkie/somleng) to [Twilreapi](https://github.com/dwilkie/twilreapi) to process your outbound calls and respond to inbound calls.

### Adhearsion-Twilio

[Adhearsion-Twilio](https://github.com/dwilkie/adhearsion-twilio) is an [Adhearsion](https://github.com/adhearsion/adhearsion) Plugin which talks [TwiML](https://www.twilio.com/docs/api/twiml). [Adhearsion-Twilio](https://github.com/dwilkie/adhearsion-twilio) is used in [Somleng-Adhearsion](https://github.com/dwilkie/somleng) in order to process [TwiML](https://www.twilio.com/docs/api/twiml) returned from the client application.

### Somleng FreeSWITCH Configuration

[Somleng FreeSWITCH configuration](https://github.com/dwilkie/freeswitch-config) is a set of [FreeSWITCH](https://freeswitch.org/) configuration optimized for Adhearsion applications. It can be used to configure your [FreeSWITCH](https://freeswitch.org/) installation to connect to [Somleng-Adhearsion](https://github.com/dwilkie/somleng).

### Somleng-RTD

[Somleng-RTD](http://rtd.somleng.org), ([Github](https://github.com/dwilkie/somleng-rtd)) is a Real Time Data (RTD) collection API for The Somleng Project. The API provides Real Time Data on various projects that use Somleng. The data includes project information, number of phone calls made, number of SMS messages sent and total cost savings.

### Somleng Simple Call Flow Manager (SCFM)

[Somleng Simple Call Flow Manager (SCFM)](https://github.com/somleng/somleng-scfm) can be used to enqueue, throttle, update, and process calls through Somleng (or Twilio). [Somleng SCFM](https://github.com/somleng/somleng-scfm) can be used as a replacement of [RapidPro](https://community.rapidpro.io/) for enqueuing calls and handling inbound call flows.

### Somleng Demo

A demo application that shows The Somleng Project in action. Coming Soon.

### The Somleng Project Website

The [repository](https://github.com/dwilkie/somleng-project) for [this website](http://www.somleng.org).

### TwiML-SM (Open Institute)

[TwiML-SM](https://github.com/somleng/twiml-sm) is a State Machine which simplifies building call flows for PHP applications. This package is being developed by the [Open Institute](http://www.open.org.kh/en).

### RapidPro2TwiMLSM (Open Institute)

[RapidPro2TwimLSM](https://github.com/somleng/rapidpro2twimlsm) is a tool which can export call flows from [RapidPro](https://www.rapidpro.io/) to a TwiML State Machine. This package is being developed by the [Open Institute](http://www.open.org.kh/en).

## Who's sponsoring The Somleng Project?

[The Somleng Project](http://www.somleng.org) is among the first 5 start-ups to received investment from the the [UNICEF Innovation Fund](http://www.unicefstories.org/2016/11/14/somleng-open-source-telephony).

## What does Somleng mean?

Somleng (សំឡេង) means Voice in Khmer.
