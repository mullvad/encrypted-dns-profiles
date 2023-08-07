# encrypted-dns-profiles

This repository contains macOS and iOS .mobileconfig profiles to set up your device(s) to use our encrypted DNS service.

Anyone, regardless of whether you are a customer of Mullvad VPN or not, can use this service. There are options for HTTPS or TLS available.

Encrypted DNS is free for everyone.

## Features

- Vanilla (vanilla/): Encrypted DNS, no blocking. Currently pending signing (not committed here yet / dns.mullvad.net)
- Adblock (blocklists/): Encrypted DNS which includes Ad-blocking and Tracker blocking (adblock.dns.mullvad.net)
- Base (base/): Encrypted DNS which includes Ad-blocking, Tracker, and Malware blocking (base.dns.mullvad.net)
- Extended (extended/): Encrypted DNS which includes Ad-blocking, Tracker, Malware and Social Media blocking
- All (all/): Encrypted DNS which includes Ad-blocking, Tracker, Malware, Adult Content, Gambling and Social Media blocking (pending signing, not committed here yet / all.dns.mullvad.net)

The content filtering lists are [what is found here](https://github.com/mullvad/dns-blocklists)

To apply these profiles you need to use iOS, iPadOS, or macOS. They can be applied with human interaction using Safari or Apple Mail, or via an MDM.
