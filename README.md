# CR-Unblocker-iOS
Tricks the iOS Crunchyroll app into thinking you are based in the US without having downsides

# How to use
**This is a profile for [sing-box](https://apps.apple.com/us/app/sing-box-mt/id6785326793)**
Once you have installed sing-box you can download the **BPF** file included in the repository and open it with sing-box.
From this point onward everything is pretty straightforward, you turn the sing-box service on and you wait a couple of seconds so that it may properly connect to the proxy,
afterwards, you open Crunchyroll as normal.

# FAQ
*What is the advantage of this over a regular VPN?*
The core advantage of this little profile is that it ONLY routes very specific Crunchyroll requests thru the US proxy, this means that everything else on your phone
will be unaffected, not even Crunchyroll's video streams themselves are routed meaning you won't have any sort of buffering/connection issues that would be caused by
a normal VPN. Another thing is that it's completely free forever thanks to [Meganeko's US Proxy Server](https://community-proxy.meganeko.dev/), meaning there are no hard caps for bandwidth, or anything of the sorts. It's also really lightweight and uses next to no CPU resources meaning it's also battery-friendly :)

*I get a connection error when I launch the app*
Close Crunchyroll entirely and restart the sing-box service, if this doesn't help; it is possible that the Proxy Server itself might be experiencing issues, in which case you can take a look at the Uptime Monitor [here](https://stats.uptimerobot.com/4xslGNY0Gi).

# Special Thanks
Special Thanks to [Meganeko](https://github.com/MeGaNeKoS), whom I took heavy inspiration specifically from his [GeoBypasser](https://github.com/MeGaNeKoS/GeoBypasser) Firefox extension, and therefore also used his [Community Proxy Server](https://community-proxy.meganeko.dev/#introduction).
