# Spooky Software

2023-10-21

Well, it is October, the month that some people celebrate "Halloween" and dress up spooky. While I do not really like the those celebrations and don't participate I will use the "Spooky Month" excuse to talk about spooky software.

## What is "Spooky Software"?

Spooky Software is any application, service, or other software that does not respect the user's privacy. Most spooky software is proprietary, but there is open source spooky software. Some examples of spooky software would be: Google Chrome, TikTok, YouTube, Discord, etc. These apps are not only proprietary, but proven to spy on their users. That is spooky! 👻 

## What Do I Do About Spooky Software?

If you are reading this, I likely don't need to explain why you should not want to be spied on. If you are still ok with being spied on, this post will not address that belief specifically. I do want to understand that thought process, so I am researching it and I will write about it when I finish. Anyway, the best answer is to *stop using it*, however, that is not always possible. There are two options to handle your spooky software:

1. Find an alternative
2. Leverage tools to stay safe while still using the spooky software

The former is generally easier and the most recommended way, however, sometimes you just have to use the spooky software for work or for a given hobby. I don't think you should quit work or give up a hobby in the name of privacy in most cases.

### Finding an Alternative

One of the things I have liked about switching to Linux is learning there are other ways to do what I need to do on computers. Used to, I thought Microsoft Word was the only way to do my school. Partly because I had never used anything else, and partly because they said to use it. While I understand that there are *some* people who cannot switch to an operating system that respects their privacy, almost everyone can find privacy respecting alternatives to some of the software they use. A really good resource for this is [AlternativeTo](https://alternativeto.net/). 

AlternativeTo has a search bar that lets you search for almost any tool you can think of, and they list other tools that do the same or similar thing. For example, searching "Microsoft Word" returns LibreOffice Writer, Apache OpenOffice Writer, Google Docs, etc. They have tags that indicate weather the software is open source or proprietary, free or payed, and what operating systems it supports. There are also user reviews where there is discussion about ease of use or software stability. Most of the time you can use privacy friendly alternatives without leaving your current operating system or changing your current workflow. 

### Protecting Yourself From Spooky Software

Sometimes you just can't stop using spooky software. I don't need to give examples of this because if you are in this unfortunate situation you know how it feels. For me personally, I can't uninstall Google services from my mobile phone because my school forces me to have Duo for two factor authentication (even though it is an objectively worse way to do 2FA then rolling codes). 

The best way to protect yourself from spooky software is sandboxing. Sandboxing is forcing the software to run in an environment that keeps it separate from the rest of your system. When software is sandboxed, it can't access other processes, data, or sensors unless it is explicitly allowed. On GrapheneOS, Google Play apps are sandboxed by default, making it difficult for them to do system-wide spying. On Linux, you can use simply use the [Flatpak](https://www.flatpak.org/) version of a given software. [Flatseal](https://flathub.org/apps/com.github.tchx84.Flatseal) is an application that lets you have very fine control over each of your Flatpak apps. Flatpaks run in a sandbox by default, and some app developers only support Flatpaks as it makes their workflow easier. If you are using an unoffical Flatpak packaging, make sure you trust the person doing the packaging. 

When Bing AI first came out I wanted to use it, but it was only available in Microsoft Edge. Since I didn't want to use Edge on my PC (because it is a privacy nightmare) I used the Flatpak version. Using Flatseal, I was able to lock down the permissions it had so I could use it without too much tracking. 

Other things you can do is running applications in a VM, which gives your a lot of protection since malware to escape hypervisors is very expensive and sought after. One good way to do this system-wide is [QubesOS](https://www.qubes-os.org/). I have personally never used it, but I really want to and plan to review it at some point. QubesOS has the endorsement of Edward Snowden, Let's Encrypt, and many dark web users, which is good enough for me to call it good. 

## Conclusion

So, in conclusion, there is actually a lot you can do to be more private online. If you are feeling trapped or just getting started on privacy, I hope this guide can point you in the right direction. There are also some good things you can do to remain slightly more anonymous online like using a VPN, but this should be done with caution and only when you fully understand how VPNs work. I personally recommend [Mullvad VPN](https://mullvad.net/), but you should still research them on your own. Remember, privacy is not a destination, it is a journey. I encourage anyone to just start where they are and take small steps! 

I am still getting started on this website, but I want to have a lot of resources for people who are interested in privacy and security. I am making some really cool resources I can't wait to share, so subscribe to the [RSS](https://mnsr.win/atom.xml) feed and stay tuned! 