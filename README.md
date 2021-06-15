# rtiwebintegrationservice-examples
This repository includes examples that illustrate how to use _RTI Web
Integration Service_, an out-of-the-box solution for integrating web-based
applications and services with _RTI Connext™ DDS_.

##  RTI Web Integration Service
Traditionally, web-based applications and services have relied on non-standard
interfaces to participate as first-class citizens in the DDS Global Data Space.
_Web Integration Service_ leverages the
[Web-Enabled DDS OMG standard (DDS-WEB)](http://www.omg.org/spec/DDS-WEB) to provide
a simple generic standards-based interface that provides a transparent bridge
between web-based services and unmodified DDS applications.

Simply set up _Web Integration Service_ to create DDS entities associated with
web-based client applications. No changes are required in the _Connext DDS_
applications.

![Web Integration Service Overview](https://community.rti.com/static/documentation/connext-dds/6.0.1/doc/manuals/web_integration_service/_images/WebDDSOverview.png)

The key benefits of Web Integration Service are:
* It reduces the time and effort spent integrating web-based protocols with
_Connext DDS_ applications, providing a standards-based generic out-of-the-box
solution.
* It supports disconnected or stateless clients that would otherwise need to
join a domain, discover remote entities, and ensure that subscribers receive
the information they sent.
* It enables interoperability between applications written in different
programming languages and operating systems for which there is no available Connext DDS SDK.
* It provides access control mechanisms to ensure that only authorized
applications can access the DDS Global Data Space.

In this repository you will find some examples illustrating the most important
features of RTI Web Integration Service, including support for different
languages such as Javascript and Python and different protocols such as HTTP
and WebSockets. For more information, please refer to the [RTI Web Integration
Service User's
Manual](https://community.rti.com/static/documentation/connext-dds/current/doc/manuals/web_integration_service/index.html).
