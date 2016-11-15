# Practical Everyday Counter-Surveillance Workshop Notes
_Wednesday, November 16th_

Notes and resources from the Practical Everyday Counter-surveillance workshop.

Feel free to make any edits or changes! Just [fork](https://help.github.com/articles/fork-a-repo/) this repository, make your changes, then [send a pull request](https://help.github.com/articles/about-pull-requests/).


## Articles & Essays mentioned or quoted

* ["Passing the Baton"](https://www.jacobinmag.com/2016/11/donald-trump-barack-obama-surveillance-national-security-drones-foreign-policy/) -- Branko Marcetic (such a cool name)
* [EFF's Surveillance Self-Defense Guides](https://ssd.eff.org/) -- Threat modeling and other useful, in-depth guides
* ["This World Of Ours"](https://scholar.harvard.edu/files/mickens/files/thisworldofours.pdf) -- "Mossad/Not Mossad"
* ["The Process of Security"](https://www.schneier.com/essays/archives/2000/04/the_process_of_secur.html) -- Bruce Schneier

## Other Useful Bits (hahaha get it because it's the internet)
* [A story about how Tor doesn't protect you from being stupid](http://www.dailydot.com/crime/tor-harvard-bomb-suspect/)
* ["Multi-factor authentication for busy people"](https://phiffer.org/writing/multi-factor-authentication-for-busy-people/)
* 

## Cleaning Up After Yourself
* [Facebook Linked Apps](https://www.facebook.com/settings?tab=applications)
* [Facebook Advertiser Preferences](https://www.facebook.com/ads/preferences/)
* [Google Activity](https://myactivity.google.com/myactivity)
  * [Google Location History](https://www.google.com/locationhistory)
  * ["More Activity"](https://myactivity.google.com/more-activity)
  * [Google Services used](https://myaccount.google.com/dashboard)
  * [Export your data](https://takeout.google.com/settings/takeout)
* The Labyrinth of [Google Settings](https://myaccount.google.com)
  * [Login settings](https://myaccount.google.com/security#signin)
  * [Authenticated devices and locations](https://myaccount.google.com/security#activity)
  * [Authorized apps](https://myaccount.google.com/security#connectedapps)
  * [Personal info](https://myaccount.google.com/privacy#personalinfo)
  * [Change what Google activities they track](https://myaccount.google.com/activitycontrols)
  * **[Change Google advertising preferences](https://www.google.com/settings/ads)**
    * **Make sure you check out the "anonymous" advertisement settings also!!!111one**
  * [Google Search settings](https://www.google.com/preferences)
  
  

## Tools recommended
### Browser extensions
| Name | Link to Firefox Extension | Link to Chrome Extension |
|---|---|---|
|[Privacy Badger](https://www.eff.org/privacybadger) | [Firefox Install](https://addons.mozilla.org/firefox/downloads/latest/privacy-badger-firefox/addon-506646-latest.xpi?src=dp-btn-primary)|[Chrome Web Store](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp?hl=en-US) |
|[uBlock Origin](https://github.com/gorhill/uBlock) | [Firefox Install](https://addons.mozilla.org/firefox/downloads/latest/ublock-origin/addon-607454-latest.xpi?src=dp-btn-primary) | [Chrome Web Store](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) |
|[HTTPS Everywhere](https://www.eff.org/https-everywhere) | [Firefox Install](https://addons.mozilla.org/firefox/downloads/latest/https-everywhere/addon-229918-latest.xpi?src=ss) | [Chrome Web Store](https://chrome.google.com/webstore/detail/gcbommkclmclpchllfjekcdonpmejbdp) |

### Mobile Tools
| Name | Link to Google Play | Link to Apple App Store |
|---|---|---|
|Signal|[Google Play](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms)|[App Store](https://itunes.apple.com/us/app/signal-private-messenger/id874139669?mt=8)|

## Good tools intentionally not covered, and why
### PGP and GPG
PGP (for "Pretty Good Privacy") is a system for public-key cryptography. The most commonly-used implementation of PGP is the free and open-source [GPG](https://www.gnupg.org/) (for "GNU Privacy Guard", do you see what they did there?). 
Public-key crypto, also known as asymetric-key cryptography, allows sending email and other communication with a very high level of privacy, as well as authentication -- that is, if you publish a public key, people can send you messages securely, and they can make sure any messages they receive from you actually came from you.

Unfortunately, GPG is not at all easy to use and manage. GPG is not so much the swiss-army knife of public-key cryptography as it is the chainsaw. It's big, it's ugly, it's confusing and complicated, and it can really ruin your day if you use it wrong. A good overview of the problems with PGP from the main developer of Signal is [here](https://moxie.org/blog/gpg-and-me/).

This is not to discourage its use in the right situations -- I (Ryan) use it every day to secure my passwords and authorize code commits. If you think you need this level of security, you **need** to really read up and learn this tool in depth before you even think about relying on it for sensitive information. If you're sure you want to start down this road, the Riseup collective has published a [comprehensive guide](https://riseup.net/en/security/message-security/openpgp/best-practices) to GPG best practices.

### VPNs
There's a lot of well-meant but bad advice floating about recommending VPNs as a surefire way to circumvent surveillance and secure your internet. On the modern Internet, where companies and intelligence organizations have eyes everywhere, VPNs have very limited and specific uses. For most people, they're only really useful for these scenarios: 

1. to punch through restrictive firewalls or filters, such as China's Great Firewall
2. to secure internet traffic traversing hostile, open, public networks, such as any coffee shop networks...or BardWireless...
3. to access secure resources on a private network remotely. (Some schools use this method to enable off-campus access to library resources, for example.)

A VPN on its own will not prevent Facebook from tracking you. A VPN on its own will not prevent the NSA from reading your emails.
A VPN on its own will not prevent the MPAA from catching your torrenting.

Furthermore, many VPN services are essentially scams. It's very easy to promise increased security, especially given the stature of VPNs in the public mind -- but it's basically impossible to validate without auditing. (Just because they **say** they don't keep logs, doesn't mean they **don't** keep logs.)

Overall, VPNs are not worth the trouble. If you're sure you want one, set one up on a remote server yourself. If you can't do that...maybe don't use a VPN.

### Tor
Keeps things anonymous. People in between know you're using Tor. Slow. Use something like Tor Browser Bundle. Or Tails, depending on how secret you want to keep things.
