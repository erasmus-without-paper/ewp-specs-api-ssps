EWP Student Service Providers API
=================================

* [What is the status of this document?][statuses]
* [See the index of all other EWP Specifications][develhub]


Summary
-------

**NOTE: This is an unstable version.
If you decide to implement the client side of this API, be aware,
that until a stable version is released, this API can change to a large extent.**

This document describes the **Student Service Providers API**. This API provides
a structured overview about the available student services at the receiving institution.


Request method
--------------

 * Requests MUST be made with HTTP GET method. Servers SHOULD reject all other request methods.


Security
--------

This version of this API uses [standard EWP Authentication and Security, Version 2][sec-v2].
Server implementers choose which security methods they support by declaring them in their Manifest API entry.


Response
--------

Servers MUST respond with a valid XML document described by the
[response.xsd](response.xsd) schema. See the schema annotations for further
information.



[develhub]: http://developers.erasmuswithoutpaper.eu/
[sec-v2]: https://github.com/erasmus-without-paper/ewp-specs-sec-intro/tree/stable-v2
[statuses]: https://github.com/erasmus-without-paper/ewp-specs-management#statuses
