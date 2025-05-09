# Table of Contents

1. [TL;DR](#tldr)
2. [Reduce Digital Footprint](#reduce-digital-footprint)
3. [Web Browsing](#web-browsing)
4. [Artificial Intelligence (AI)](#artificial-intelligence-ai)
5. [Phones](#phones)
6. [Computers](#computers)
7. [Email](#email)
8. [Resources](#resources)

---

Your personal information is worth a lot of money. That information is often gathered without your fully informed consent through complex terms & conditions, features such as personalized recommendations, location tracking, activity habits, and more. These tactics ensure you don’t understand the breadth of data being collected, how it’s being used, or who gets access to it.

As we’ve seen, data collected by corporations often ends up in data breaches; [AT&T](https://www.cnet.com/tech/mobile/at-t-data-breach-what-is-at-t-doing-for-the-73-million-accounts-breached/), [Change Healthcare](https://techcrunch.com/2024/02/21/change-healthcare-cyberattack/), and [Ticketmaster](https://www.pcmag.com/news/ticketmaster-confirms-user-email-addresses-phone-numbers-stolen-in-hack) to name a few. Why should we trust them to dutifully care for our information, when there aren’t consequences when they lose it? Mozilla has an ongoing list of [data breaches](https://monitor.mozilla.org/breaches).

You deserve to control access to your personal information - who gets it, when it’s given, how it’s used, and for how long. This guide will help you take back some control. If you want a more thorough guide, check out [The Hitchhiker’s Guide to Online Anonymity](https://anonymousplanet.org/guide.html).

***Disclaimer: I’m not an expert on every topic here - there are gaps in my knowledge. It’s up to you to understand the tools you use.***

# TL;DR
There's a lot of information here, so below are some best practices and recommendations. I think the following will have the largest impact on improving your privacy and security:

| Action | Recommendation |
| --- | --- |
| Privacy-focused<br>browser & search engine | <ul> <li>**popular:** Firefox with DuckDuckGo</li> <li>**best for privacy:** Tor with DuckDuckGo</li> </ul> |
| “No user logs” VPN | <ul> <li>**user-friendly:** NordVPN or Proton</li> <li>**best for privacy:** Mullvad</li> </ul> |
| Password manager | Stop reusing passwords. The best option is to use randomly generated, long, complex passwords. A password manager will help<br><ul> <li>**user-friendly:** NordPass or 1Password</li> <li>**offers free tier:** Bitwarden</li> </ul> |
| MFA / 2FA | Enable for everything |
| Social media | <ul> <li>**best:** delete them</li> <li>**good:** remove personal information, make accounts private, opt out of third party sharing</li> </ul> |
| Website privacy settings | Opt out of third party cookies, AI training, website tracking, and data & location services for everything |
| Data brokers | Remove your personal information from data broker databases |
| Apps & software | Use applications/software that have end to end encryption (E2EE) |
| Google | Stop using it - [how to de-Google your life](https://proton.me/blog/how-to-de-google) |

# Reduce Digital Footprint
Try Googling yourself and look at the results. What did you find?

Publicly available information about you can be used:
- in targeted ads
- to [dox you](https://en.wikipedia.org/wiki/Doxing#:~:text=Doxing%20or%20doxxing%20is%20the,Internet%20and%20without%20their%20consent.)
- to stalk or harass you
- against you politically or socially
  - your sexual orientation, political affiliation, or gender identity
 
| Topic | Action |
| --- | --- |
| Social media | Social media sites are basically information-harvesting tools. Your personal information, activity, enagement, and attention are worth billions. You can combat this by deleting your social media accounts, which is my recommendation. I understand that's very unappealing, so instead, there are some actions you can take that will reduce how much of your information they harvest.<br><br> <ul> <li>remove personal details such as your employer, full name, relatives, gender identity, etc, from your profile</li> <li>avoid sharing detailed personal information in social media comments</li> <li>opt out of (third party) data sharing - this may be framed as "personalization"</li> <li>block access to your location</li> <li>block access to your address book</li> <li>disable cross-website tracking</li> <li>disable third party cookies</li> <li>make your profile private</li> <li>don't use "Sign in with Google/Facebook/etc" on websites - sign up with an email address instead</li> <li>specific instructions for Facebook / Meta will be below</li> </ul> |
| [Google account](https://myaccount.google.com) | If you have a gmail account, then this applies to you. Google has a lot of settings and features that are designed to track your activity. Here are some suggestions to get you started.<br><br ><ul> <li>turn off [search personalization](https://www.google.com/search-personalization/?continue=https://myaccount.google.com/data-and-privacy&hl=en)</li> <li>turn off [personalized ads](https://myadcenter.google.com)</li> <li>turn off [web & app activity](https://myactivity.google.com/activitycontrols) - additionally, delete stored activity data</li> <li>turn off [YouTube history](https://myactivity.google.com/activitycontrols)</li> </ul>Some more ways to [de-Google your life](https://proton.me/blog/how-to-de-google). |
| [Prescreen offers](https://consumer.ftc.gov/articles/prescreened-credit-insurance-offers) | You can opt out of prescreen offers [here](https://www.optoutprescreen.com/). You may want to consider freezing your credit with the 3 major credit bureaus as well. Info on that can be found [here](https://www.usa.gov/credit-freeze). |
| Public records | Depending on your location and situation, you may request your public records be hidden from public-facing websites run by local, county, and state-wide entities. |
| Privacy settings | Outside of social media, most websites you have an account with have privacy settings. There is no easy way to do this, but you will need to visit each website you have an account with and manually change your privacy settings to opt out of persaonization, diagnostic data sharing, third party data sharing, and anything else that could link your information or activity to you (whether it's anonymized or not). |
| Unused accounts | If you have accounts on websites that you’re no longer active on, deactivate or delete them. Before deletion, you may need to request your information be removed from their database. Deleting unused accounts will shrink your digital footprint. |
| Photo metadata | Photos have metadata that can contain lots of information about what device was used to take the photo, location data, and more. Remove photo metadata using [ExifTool](https://exiftool.org/). There are other tools out there that don't use the command line, like ExifCleaner, however, ExifCleaner hasn't been updated in 3 years. |
| Data brokers | Data brokers are entities who collect information about you to sell. They exist in different forms and buy/sell different types of data to build profiles on you, the consumer. For example, people finder sites are a type of [data broker](https://consumer.ftc.gov/articles/what-know-about-people-search-sites-sell-your-information). Removing your information from data broker databases is a multi-step process that will take a lot of effort to accomplish, but is well-worth the energy to reduce who has access to your data. There are plenty of reasons to delete your information from these databases and prevent future information from being sold. One example is that US government agencies have been found to be [buying your location data](https://www.theverge.com/2024/12/3/24312313/ftc-bans-sensitive-location-data-brokers-gravy-analytics-venntel-mobilewalla) from brokers. |
| End to end encryption (E2EE) | Encryption is meant to keep prying eyes from accessing data without permission. For example, if you send an unencrypted text message to your friend, it could be intercepted and read by an unknown third party. Think of encryption as a process that scrambles the content of your message, so even if a third party snags the text, your message would be unreadable. Not all encryption is created equal, and here is a guide (TBD) I wrote about it. Prioritize apps and software that utlize E2EE. Encrypt your phone and computers (more details in their respective sections). |
| Internet of Things (IoT) devices | For the love of all things holy, you do **not** need a bluetooth toothbrush that tells you your brushing habits! Nearly ALL smart devices and activity & wellness apps sell usage data to advertisers. |

## Meta (Facebook, Instagram, Whatsapp)
Meta is just here to get your data and make money. Here are some tips to fix that.

## Data brokers
This [YouTube video](https://www.youtube.com/watch?v=iX3JT6q3AxA) is a great starting point to help you understand the breadth and depth of information gathered on you. The best thing you can do for your privacy is:
- opt out of third party data sharing on everything
- delete unnecessary apps
- reduce the amount of IoT devices you use
- verify the type of data your smart devices gather and share with third parties (and opt out where possible)

### Manual data removal
| Pros | Cons |
| --- | --- |
| free | time-consuming |
| most effective | requires regular follow up |
| you control the information<br> shared with the data brokers | not 100% effective |

These resources will help:
- [IntelTechniques Data Removal Guide](https://inteltechniques.com/workbook.html)
- [Big Ass Data Broker Opt Out LIst Github](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List)
- [Privacy Guides | Data Removal Services](https://www.privacyguides.org/en/data-broker-removals/)

### Paid data removal
| Pros | Cons |
| --- | --- |
| significantly less<br> time-consuming | ongoing subscription |
| regular reporting | limited scope<br> & still requires manual work |

Some popular providers:

- [DeleteMe](https://joindeleteme.com/)
- [Incogni](https://incogni.com/)
- [EasyOptOuts](https://easyoptouts.com/)
- [Kanary](https://www.kanary.com/)
- [Optery](https://www.optery.com/)

### IoT and Smart Devices
Here are some well-known examples of devices that share user data. I recommend finding alternatives and/or researching your options for reducing what informaton is shared by them. I will get into apps in the Phones section.

| Device | Information shared |
| --- | --- |
| Fitbit | tbd |
| Ring | tbd |
| tbd | tbd |

# Web Browsing
Your ISP (internet service provider), phone apps, cellular provider, web browser, and websites all see some amount of information about you when you use their services.

| Action | Priority | Explanation |
| --- | --- | --- |
| Privacy-focused browser | tbd | tbd |
| Privacy-focused search engine | tbd | tbd |
| VPN | tbd | tbd |
| Password manager | tbd | tbd |
| Extensions | tbd | tbd |
| Cookies | tbd | tbd |
| Third party tracking | tbd | tbd |
| tbd | tbd | tbd |
| tbd | tbd | tbd |

## Browsers
Chrome is not recommended for privacy. Google [harvests vast swaths of data](https://www.wired.com/story/google-chrome-browser-data/), and Chrome has [disabled ad blockers](https://www.theverge.com/2024/10/15/24270981/google-chrome-ublock-origin-phaseout-manifest-v3-ad-blocker) with manifest v3.

| Browser | Explanation |
| --- | --- |
| [Tor](https://www.torproject.org/download/) | Tor [mitigates fingerprinting](https://tb-manual.torproject.org/anti-fingerprinting/). |
| [Firefox](https://www.mozilla.org/en-US/firefox/) | tbd |
| [Brave](https://brave.com/) | Brave [mitigates fingerprinting](https://brave.com/privacy-updates/3-fingerprint-randomization/). |
| [DuckDuckGo](https://start.duckduckgo.com/) | tbd |

## Fingerprinting

## Search engines
Google is one of the worst offenders when it comes to surveillance capitalism.

| Search engine | Explanation |
| --- | --- |
| [DuckDuckgo](https://duckduckgo.com/) | tbd |
| [Start Page](https://www.startpage.com/en/) | tbd |
| [Brave](https://search.brave.com/) | tbd |
| [Kagi](https://kagi.com/) | tbd |

## Extensions & add-ons
Be aware that extensions and add-ons can compromise your security. Thoroughly research extensions before installing.

### uBlock Origin
- blocks ads
- advanced mode can block scripts and is customizable
- supports filters that prevent website tracking from sites like Facebook
- uBlock Origin, along with other ad blockers, will be disabled when Chrome manifest v3 is released

### uBlock Origin Lite
- only use if uBlock Origin is unavailable

### ClearURLs

## Website cookies
Think of cookies as identifiers that tie your browsing activity to you. There are browser settings and extensions that will block third party cookies automatically. When a website asks you to accept cookies, choose “reject” or “necessary cookies only.”

## VPNs
**What:** A VPN is a virtual private network that can encrypt your internet traffic and masks your IP address.

**Why:** VPNs are useful when using public wifi or when you wish to mask your IP address while browsing the web. [Reasons to mask your IP address](https://usa.kaspersky.com/resource-center/preemptive-safety/how-to-hide-ip).

**What to look for:** Whether the VPN service logs/saves your activity and their reputation.

Select a VPN provider that does not log your activity. Confirm they don’t save user logs by checking if they’ve been independently audited. Avoid using free VPNs (except for Proton) or you might end up with spyware on your phone (hint: [Facebook Onavo](https://www.techradar.com/computing/cyber-security/facebooks-onavo-vpn-used-to-wiretap-competitor-data-court-filings-reveal)) Here are some providers who have been third party verified (based on this post) and are popular:

| VPN | Details |
| --- | --- |
| [NordVPN](https://nordvpn.com/) | tbd |
| [Proton](https://protonvpn.com/) | Accepts cash payments, which will reduce the amount of information linked to you directly. |
| [Mullvad](https://mullvad.net/en) | Mullvad accounts are randomly generated without your personal details, and they accept cash payment, meaning your account can’t easily be tied to you. |
| [Surfshark](https://surfshark.com/) | tbd |
| [ExpressVPN](https://www.expressvpn.com/) | tbd |
| [PIA](https://www.privateinternetaccess.com/) | tbd |

**Important:** A VPN does *not* keep your online activity completely anonymous.

**Consider this:** You post from a fake account on a forum, but you’re on a VPN, so your IP address is masked. However, you then place an online order for pizza delivery while still logged into the VPN. That IP address is now directly tied to your address and forum post.

**Takeaway:** A VPN masks your IP address but can still be linked to you based on your online activity. This is why disabling things like tracking and third party cookies is useful. If anonymity is your goal, check out [The Hitchhiker’s Guide](https://anonymousplanet.org/guide.htmlw).

## Passwords
For more information, see CISA's [best practices guide](https://www.cisa.gov/secure-our-world/use-strong-passwords).

| Action | Priority | Explanation |
| --- | --- | --- |
| Strong passwords | Highest | tbd |
| Unique Passwords | Highest | tbd |
| Passkeys | Highest | tbd |
| Password manager | Highest | tbd |
| MFA / 2FA | Highest | tbd |

### Passkeys

If setting up a passkey is an option, choose it over a password. More information [here](https://www.passkeys.com/passkey-vs-password).

## Password Managers
**What:** Password managers store login credentials, contact details, secure notes, and more in an encrypted “vault.”

**Why:** They enable you to save a lot of unique passwords that you don’t have to memorize.

**What to look for:** Reputation, features, and recent security breaches.

Apple and Google Passwords are secure if that’s your preference. The downside is if you lose access to your Apple ID or Google account, you’ll lose access to all of your passwords.

Some popular password managers:

- [Bitwarden](https://bitwarden.com/)
- [LastPass](https://www.lastpass.com/)
- [NordPass](https://nordpass.com/)
- [1Password](https://1password.com/)

## MFA / 2FA
**What:** Multi-factor (MFA) and 2-factor (2FA) authentication are an extra step to verifying your identity when you log into something.

**Why:** These measures help prevent unauthorized access to your accounts by requiring additional steps to log into an account.

**TL;DR:** Enable MFA and 2FA for everything.

There are four **types** of authentication, and a variety of **methods** to achieve each type.

| Type | Method(s) |
| --- | --- |
| something you know | password, PIN, security questions |
| something you have | one time password (OTP), authenticator app | 
| something you are | biometrics such as face ID or fingerprint | 
| somewhere you are | geolocation | 

Your username and password fall under the “something you know” authentication **type**.

**2FA** requires you to present one (1) additional authentication **method** along with your username and password. 2FA allows you to use the same **type** of method (e.g. something you know, like a PIN or security question).

**MFA** requires you to present at least one (1) additional authentication **method** along with your username and password. However, the additional method cannot be the same **type**. For example, if you log in with a username/password, you cannot use a PIN, but you can use an authenticator app or biometrics.

MFA is more secure than 2FA, and both are more secure than single-factor authentication (just a username and password). Always choose MFA over 2FA if it's available.

# Artificial Intelligence (AI)
If no AI haters exist, then I’m dead.

- [privacy concerns](https://iapp.org/news/a/shaping-the-future-a-dynamic-taxonomy-for-ai-privacy-risks)
- [steals from artists/creatives](https://www.latimes.com/opinion/story/2024-06-18/artificial-intelligence-openai-media-manager-apple)
- [unsustainable resource consumption](https://www.vox.com/climate/2024/3/28/24111721/climate-ai-tech-energy-demand-rising)
- [generative AI uses more resources than task-specific tools](https://www.rwdigital.ca/blog/how-much-energy-do-google-search-and-chatgpt-use/)

AI can be a useful tool to those with disabilities, so abandoning it entirely is not an option for everyone. When most people think of AI, they think of generative AI, but narrow AI has been around for years. Generative AI poses a large risk to privacy. [Here’s the difference](https://www.forbes.com/sites/bernardmarr/2023/07/24/the-difference-between-generative-ai-and-traditional-ai-an-easy-explanation-for-anyone/).

What you can do to protect your privacy:

- opt out of AI training
  - this [Wired guide](https://www.wired.com/story/how-to-stop-your-data-from-being-used-to-train-ai/) is a good place to start
- never provide personal information to AI tools like ChatGBT
- disable unused AI features on your devices

# Phones
**Important:** Police may legally compel you to use biometrics to unlock your phone. Some courts currently consider the use of biometrics as a “nontestimonial act.”

**Testimonial act:** Providing a password or PIN is considered a testimonial act because it involves revealing potentially incriminating information. Testimonial acts are protected by the 5th amendment.

**Nontestimonial act:** Using a fingerprint or facial recognition relies on physical characteristics instead of personal knowledge, and is therefore considered (in at least some recent court cases) a nontestimonial act. Nontestimonial acts are **not** protected by the 5th amendment.

With this in mind:

- leave your phone and smartwatch at home when attending protests
- consider manually disabling face ID / fingerprint when you’re outside of the home
- if you are stopped by police, and it’s safe to do so, turn off your phone
  - turning off your phone may prevent police from breaking into it with [Cellebrite](https://discuss.privacyguides.net/t/claims-made-by-forensics-companies-their-capabilities-and-how-grapheneos-fares/18445)
- for the safety of Black folks and other POC, you need your phone available to record police interactions
  - you may want to disable face ID / fingerprint instead
- on iOS, quickly [disable face ID](https://www.phonearena.com/news/How-to-force-iPhone-to-require-passcode-quickly-temporarily-disable-Face-ID_id121758) by triggering the “power off” screen, then canceling
  - this will also work if you rapidly hit the power button 5 times
- on Android, you can [enable lockdown mode from the lock screen](https://www.androidcentral.com/apps-software/how-to-disable-biometrics-on-your-android-phone-from-the-lock-screen)

| Action | Explanation |
| --- | --- |
| Daily restart | tbd |
| Automatic updates | Regular software updates patch vulnerabilities. The latest versions may foil tools like Cellebrite and GrayKey | 
| Public activity | Turn off your public activity on apps like Venmo. There's no good reason for your transations to be public. This activity can be used to tie you to others. [Instructions](https://www.wikihow.com/Delete-Venmo-History) | 
| Tracking | tbd |
| Location services | tbd |
| Phone number masking | tbd |
| Biometrics | tbd |
| tbd | tbd |

## Phone Number Masking
Alternative to giving your actual phone number out. This Proton [blog post](https://protonvpn.com/blog/protect-your-privacy-with-second-phone-number-app/) offers tips on what to look for.

Some examples:

- [Firefox Relay](https://relay.firefox.com/)
- [Google Voice](https://voice.google.com/u/0/about)

## iPhone Settings
| Action | Explanation |
| --- | --- |
| [Advanced Data Protection](https://support.apple.com/en-us/108756) | tbd |
| Push notifications | Consider turning off push notifications. Push alerts from apps can be [tied to your identity](https://www.washingtonpost.com/technology/2024/02/29/push-notification-surveillance-fbi/). If you leave them turned on, you should [turn off notification previews while your phone is locked](https://www.lifewire.com/turn-off-message-preview-iphone-4175842) |
| [Enable 2FA](https://support.apple.com/guide/iphone/use-two-factor-authentication-iphd709a3c46/ios) | tbd |
| [Account Recovery](https://support.apple.com/en-us/109345) | tbd |
| Face ID | tbd |
| Passcode | tbd |
| Screen Time | tbd |
| Find My | Enable Find My device tracking even when the device is turned off. [Instructions](https://www.theverge.com/22697218/iphone-apple-ios-15-find-my-how-to). |
| Location Services | tbd |
| [Allow Apps to Request to Track](https://support.apple.com/guide/iphone/control-app-tracking-permissions-iph4f4cbd242/ios) | tbd |
| [Stolen device protection](https://support.apple.com/en-us/120340) | tbd |
| Airdrop | tbd |

### Face ID / Passcode Settings
- [use a 6 digit passcode instead of 4](https://support.apple.com/en-us/119586)
- [Turn on ‘Face ID Attention’](https://support.apple.com/guide/iphone/change-face-id-and-attention-settings-iph646624222/ios)
- [Disable control center when the phone is locked](https://www.tomsguide.com/how-to/how-to-disable-control-center-on-a-locked-iphone)

### Screen Time Settings
- [turn off ‘Allow changes to: Passcode & Face ID’](https://www.techbout.com/prevent-others-from-changing-iphone-passcode-87736/)
  - this disables the ability to make changes to Passcode or Face ID and hides the option from your settings
  - to increase the effectiveness of this setting, you should set a Screen Time passcode and make sure it’s different from your iPhone passcode
  - note: to make changes to Passcode & Face ID, you must turn this setting back on

### Turn off ‘Location Services’
Toggle off for any app that does not require your location for functionality and use “while using app” for everything else. Location data brokers.
- [instructions](https://support.apple.com/en-us/102647)

### Turn off Airdrop
Or set to “Contacts Only.”
- [instructions](https://support.apple.com/en-us/119857)

## Android Settings
Start [here](https://veepn.com/blog/10-android-privacy-settings/) to understand the privacy and security settings available to you.

| Action | Explanation |
| --- | --- |
| Notifications | tbd |
| Web & App Activity | tbd |
| Location | tbd |
| Personalization | tbd |
| Enable 2FA | tbd |
| Permission manager | tbd |
| tbd | tbd |

### Notifications
Don’t show any notifications or Hide silent conversations and notifications. Turn off sensitive notifications when locked.
- [instructions](https://support.google.com/android/answer/9079661?hl=en)

### Turn off ‘Web & App Activity’
- [instructions](https://support.google.com/accounts/answer/54068?hl=en&co=GENIE.Platform%3DAndroid)

### Location
Deny anything that doesn’t need your location, and turn on “while in use” for apps that need your location sometimes.
- [instructions](https://support.google.com/accounts/answer/3467281?hl=en)

### Turn off personalization
- [instructions](https://support.google.com/My-Ad-Center-Help/answer/12155656?hl=en&co=GENIE.Platform%3DAndroid#turn-on-or-off-personalized-ads)

### Enable 2FA
- [instructions](https://support.google.com/accounts/answer/185839?hl=en&co=GENIE.Platform%3DAndroid)

### Device admin apps
Disable admin privileges for apps that don’t require it.
- [instructions](https://support.google.com/android/answer/9431959?hl=en)

### Permission manager
Use this to review individual app permissions.
- [same link as above](https://support.google.com/android/answer/9431959?hl=en)

## Useful Apps
- [Privacy.com](https://www.privacy.com/)
- [Signal](https://signal.org/download/)
  - turn on vanishing messages
- [Threema](https://threema.ch/en)
- [Session](https://getsession.org/)
- [Telegram](https://telegram.org/)
- [Briar](https://briarproject.org/)
  - turn on vannishing messages

## Apps to Avoid
- Temu
  - [it’s basically malware](https://arstechnica.com/tech-policy/2024/06/shopping-app-temu-is-dangerous-malware-spying-on-your-texts-lawsuit-claims/)
- Period trackers
- DeepSeek
  - [awful security practices](https://www.forbes.com/sites/torconstantino/2025/02/04/4-warnings-about-deepseek-you-need-to-know-before-using-it/)
- Basically all health & wellness apps, including [mental health apps](https://www.mozillafoundation.org/en/blog/top-mental-health-and-prayer-apps-fail-spectacularly-at-privacy-security/)

There is concern that data from period tracker apps could be used against someone who received an abortion. Even the Stardust app has been [guilty of sharing user data](https://techcrunch.com/2022/06/27/stardust-period-tracker-phone-number/). Here’s a 2022 [Wired article](https://www.wired.com/story/period-tracking-apps-flo-clue-stardust-ranked-data-privacy/) that covers the concern around period tracker privacy. Clue scored the highest, but doesn’t support local storage, which is a key privacy feature you should look for.

Period tracker apps that store your data on your phone instead of the cloud:
- [Euki](https://eukiapp.org/)
- [Drip](https://bloodyhealth.gitlab.io/)

# Computers
Most of you are probably not going to use Linux. I think Linux is the best option for security and usability. Consider [Debian](https://www.debian.org/) or [Ubuntu](https://ubuntu.com/). This [TechRadar article](https://www.techradar.com/news/best-linux-distro-privacy-security) has some additional OS recommendations.

## MacOS Settings

### FileVault
Full disk encryption prevents someone from exfiltrating data on your hard drive in the event your computer is seized or stolen. You must save your recovery key in a safe place that’s not on your computer’s hard drive.
- [instructions](https://support.apple.com/guide/mac-help/protect-data-on-your-mac-with-filevault-mh11785/mac)

### Antivirus
MacOS has built-in protection tools that help prevent malware from being installed. Here’s an [explanation](https://www.macworld.com/article/670537/do-macs-need-antivirus.html) of those features and their shortfalls.

Some options available for MacOS:

- [NordVPN Threat Protection Pro](https://nordvpn.com/features/threat-protection/)
- [Bitdefender](https://www.bitdefender.com/en-us/)
- [Malwarebytes](https://www.malwarebytes.com/)
- [Surfshark One](https://surfshark.com/one)

### Updates
Regular software updates patch vulnerabilities.
- [instructions](https://support.apple.com/guide/mac-help/keep-your-mac-up-to-date-mchlpx1065/mac)

## Windows Settings

### BitLocker
Full disk encryption prevents someone from exfiltrating data on your hard drive in the event your computer is seized or stolen. You must save your recovery key in a safe place that’s not on your computer’s hard drive.
- [instructions](https://support.microsoft.com/en-us/windows/bitlocker-drive-encryption-76b92ac9-1040-48d6-9f5f-d14b3c5fa178)

### Turn off ‘Diagnostic data’
- [instructions](https://learn.microsoft.com/en-us/windows/privacy/configure-windows-diagnostic-data-in-your-organization#diagnostic-data-settings)

### Turn off ‘Improve inking and typing’
- [instructions](https://support.microsoft.com/en-us/windows/speech-voice-activation-inking-typing-and-privacy-149e0e60-7c93-dedd-a0d8-5731b71a4fef)

### Turn off ‘Tailored experiences’
- [instructions](https://windowsloop.com/change-privacy-settings-in-windows-11/)

### Antivirus
Windows Defender is built-in and enough for 99% of people. You may wish to supplement it if you’re torrenting or downloading unofficial software.

Some options available for Windows:

- [NordVPN Threat Protection Pro](https://nordvpn.com/features/threat-protection/)
- [Bitdefender](https://www.bitdefender.com/en-us/)
- [Malwarebytes](https://www.malwarebytes.com/)
- [Surfshark One](https://surfshark.com/one)

### Automatic Updates
Regular software updates patch vulnerabilities.

## Cloud Storage
The safest place your data can be stored is locally on your physical devices. If that’s not an option, it’s possible to improve cloud storage security.

**What to look for:** End to end encryption and what information could be handed over if subpoenaed.

iCloud, Google Drive, and OneDrive are considered safe, but you may want to activate advanced security settings. This [Wired guide](https://www.wired.com/story/9-tips-cloud-storage-security/) is a good starting point.
- [iCloud security overview](https://support.apple.com/en-us/102651)
- [Google Drive key security controls](https://cloud.google.com/docs/security/overview/whitepaper#key_security_controls)
- [OneDrive security overview](https://learn.microsoft.com/en-us/sharepoint/onedrive-privacy-security-overview)

These companies are required to comply with local regulations if subpoenaed. Consider manually encrypting sensitive files/folders. Use a long, complex password and store it in a fire safe AND password manager.
- [encrypt on Windows](https://support.microsoft.com/en-us/windows/how-to-encrypt-a-file-1131805c-47b8-2e3e-a705-807e13c10da7)
- [encrypt using 7zip](https://info.lse.ac.uk/staff/divisions/dts/help/guides-faqs/software/using-7-Zip-to-encrypt-and-decrypt-files)
- [encrypt on MacOS](https://support.apple.com/guide/mac-help/protect-your-mac-information-with-encryption-mh40593/mac)

# Email
To start, do not use email to engage in sensitive conversations. Email was not designed to be secure. Engage in sensitive conversations in person or over secure messaging apps like Signal.

| Action | Explanation |
| --- | --- |
| Email masking | tbd |
| Newsletters | tbd |
| Multiple accounts | tbd |
| Privacy-focused options | tbd |
| Temporary options | tbd |

### Email masking
- [Firefox Relay](https://relay.firefox.com/)
- [Apple iCloud+ Hide My Email](https://support.apple.com/guide/iphone/create-and-manage-hide-my-email-addresses-iphcb02e76f7/ios)
- Startmail

### Use multiple accounts
I recommend one email address to use professionally (resume, job apps, etc). Then use other email accounts for everything else.

### Privacy-focused options
- [ProtonMail](https://mail.proton.me/)

### Temporary email options
- [Emailnator](https://www.emailnator.com/)
- [10 minute mail](https://10minutemail.com/)

# Resources
Here are some great resources if you’d like to learn more.
- [Electronic Frontier Foundation](https://www.eff.org/)
- [Privacy Rights Clearinghouse](https://privacyrights.org/)
- [The Digital Standard](https://thedigitalstandard.org/)
- [Surveillance Technology Oversight Project](https://www.stopspying.org/)
- [Kaspersky](https://usa.kaspersky.com/)
- [IntelTechniques](https://inteltechniques.com/)
- [Privacy Guides](https://www.privacyguides.org/en/)

## What else can I do?
There are many, many reasons to contact the politicians who represent you. Stronger privacy laws could have a significant impact on reducing the amount of our personal information gets sold to advertisors. Find your federal and state elected officials [here](https://www.usa.gov/elected-officials/).
