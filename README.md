# CR Unblocker for iOS
Routes specific Crunchyroll Traffic to trick the app into thinking you are in the US without any drawbacks. Based on the [CR-Unblocker](https://github.com/MeGaNeKoS/CR-Unblocker) Firefox Extension.

# How to use
**This is a profile for [sing-box](https://apps.apple.com/us/app/sing-box-mt/id6785326793)**. 
Once you have installed sing-box you can download the **BPF** file included in the repository and open it with sing-box.
From this point, everything is pretty straightforward, you turn sing-box on and give it a couple of seconds so that it may properly initialize,
afterwards, you open Crunchyroll as you would.

# FAQ
***What is the advantage of this over a regular VPN?***
- The core advantage of this is, that unlike a normal VPN which proxies all requests, this *only* routes very specific Crunchyroll requests thru a US proxy, this means that everything else on your phone
will be unaffected, not even Crunchyroll's video streams themselves are routed meaning you won't have any sort of buffering/connection issues that would be caused by
a normal VPN. Another thing is that it's completely free forever thanks to [Meganeko's US Proxy Server](https://community-proxy.meganeko.dev/), there are no hard caps for bandwidth, or anything of the sorts. It's also really lightweight and uses next to no CPU resources, meaning it's also battery-friendly :)

***I get a connection error when I launch CR with the Proxy on***
- Close Crunchyroll entirely and restart the sing-box profile, if this doesn't help; it is possible that the Proxy Server itself might be experiencing issues, in which case you can take a look at the Uptime Monitor [here](https://stats.uptimerobot.com/4xslGNY0Gi).

***Is there a way to hide the VPN Icon in the Control Panel?***
- Yes! There actually is, and I recommend hiding it unless you're forgetful and might leave it on 24/7. To hide it, go into Sing-Box's **Settings > Profile Override > Hide VPN Icon**

***Is this safe?***
- In short, yes. I don't believe anyone has been banned for this sort of stuff, however, in the rare event that you do get banned, **I do not take any responsibility**.

# Special Thanks
Special Thanks to [Meganeko](https://github.com/MeGaNeKoS), whom I took heavy inspiration from, specifically from his [CR-Unblocker](https://github.com/MeGaNeKoS/CR-Unblocker) Firefox extension, and his [Community Proxy Server](https://community-proxy.meganeko.dev/#introduction).
