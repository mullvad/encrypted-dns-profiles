# encrypted-dns-profiles

This repository contains macOS and iOS .mobileconfig profiles to set up your device(s) to use our encrypted DNS service.

Anyone, regardless of whether you are a customer of Mullvad VPN or not, can use this service. There are options for HTTPS or TLS available, and for "base" which is encrypted DNS without any content filtering, or "blocking" which specifies content filtering based on type.

The content filtering lists are [what is found here](https://github.com/mullvad/dns-blocklists)

To apply these profiles you need to use iOS, iPadOS, or macOS. They can be applied with human interaction using Safari or Apple Mail, or via an MDM.
