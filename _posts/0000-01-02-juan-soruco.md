---
layout: slide
title: "Welcome to our second slide!"
---
The second decision that needs to be made is whether your requirements require HTTPS end-to-end, or whether you will simply terminate the HTTPS connection at the proxy and allow the proxy to relay over HTTP. For all but the smallest operations, re-encryption is the better option. It allows for more secure direct access for clients internal to your network, and protects against bad actors who are already running arbitrary code inside your datacenter and attempting to escalate privilege. While you will be configuring your own CA for issuing client-certificates, you will still want your external access endpoints to be protected via a publicly signed and trusted CA such as GeoTrust or RapidSSL.
Use the left arrow to go back!