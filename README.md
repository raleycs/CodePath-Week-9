# Project 9 - Honeypot

## Honeypot deployed: Dionaea over HTTP

## Issues: Initially I couldn't load the external IP of the admin VM in my browser. When I typed in the IP address and tried to load the page, it resulted in a timeout since it was taking too long. Fortunately, I read a post on the discussion section where a user had a similar issue as mine. I was able to resolve this issue by going into the browser and manually editing the firewall settings for mhn-admin. The reasoning behind this was that by default the firewall blocked all HTTP traffic, so I allowed TCP 80 to be allowed since HTTP uses that port. Other than this, everything else went smoothly.

## Summary: According to the Attacks page on the MHN server, there are approximately 6500 attacks on the honey pot. The interesting that the Assignment page touched upon was that it was not only the attacks of my own that were detected. There were multiple attacks detected from other countries such as Russia, Indonesia, Bulgaria, etc. It was difficult to obtain any malware samples (most likely due to the type of honey pot). The number of attacks only increase at a very fast rate, I was able to get 3000 attacks within a matter of minutes.

## Unresolved questions: Why exactly are there attacks coming from those countries? Do they have network scanners where they just try to brute force every single possible IP address, and hence that's why we are receiving those attacks?
