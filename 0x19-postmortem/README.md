# `Postmortem`

![poster image](https://miro.medium.com/v2/resize:fit:640/format:webp/1*hHFxZZ6_iy3zH8dDEq8IIQ.jpeg)

**Duration**
January 23, 2024, from 09:00 AM to 12:30 PM (UTC).

**Impact**
The outage affected our main web application, resulting in a complete unavailability of services for approximately 30% of our users.

**Root Cause**
The outage was triggered by a misconfiguration in the load balancer settings, causing an overload on one of the backend servers.
