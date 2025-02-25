# Table of Contents

1. [Purpose](#purpose)
2. [TL;DR](#tldr)
3. [Reduce Public Data](#reduce-public-data)
   1. [Social Media](#social-media)
   2. [Public Records](#public-records)
   3. [Data Sharing](#data-sharing)
   4. [Unused Accounts](#unused-accounts)
   5. [Data Brokers](#data-brokers)
   6. [Manual Data Removal](#manual-data-removal)
   7. [Paid Data Removal](#paid-data-removal)
4. [Web Browsing](#web-browsing)
   1. [Browsers](#browsers)
   2. [Search Engines](#search-engines)
   3. [Extensions & Add-ons](#extensions--add-ons)
   4. [Website Cookies](#website-cookies)
   5. [VPNs](#vpns)

# Purpose
Corporations, through surveillance capitalism, harvest your personal information for profit. That data is often gathered without your explicit informed consent through complex terms & conditions, features such as personalized recommendations, and more. These tactics ensure you don’t understand the breadth of data being collected, how it’s being used, or who gets access to it.

As we’ve seen, data collected by corporations often ends up in data breaches; AT&T, Change Healthcare, and Ticketmaster to name a few. Why should we trust them to dutifully care for our information, when there aren’t consequences when they lose it?

You deserve to control access to your personal information - who gets it, when it’s given, how it’s used, and for how long. This guide will help you get started. If you want a more thorough guide, check out The Hitchhiker’s Guide to Online Anonymity.

***Disclaimer: I’m not an expert on every topic here - there are gaps in my knowledge. It’s up to you to understand the tools you use.***

# TL;DR
I think the following will have the largest impact on improving your privacy and security:

- Privacy-focused browser
  - **user-friendly:** Firefox with DuckDuckGo & uBlock Origin
  - **best for privacy:** Tor with DuckDuckGo
    - VPNs and extensions are not recommended with Tor
- “No user logs” VPN
  - **user-friendly:** NordVPN or Proton
  - **best for privacy:** Mullvad
- Password manager
  - **user-friendly:** NordPass or 1Password
  - **offers free tier:** Bitwarden
- Enable MFA / 2FA on everything
- Social media
  - **best:** delete them
  - **good:** remove personal information & make accounts private
- Remove your personal information from data broker databases
- Opt out of third party cookies, AI training, website tracking, and data & location services
- Use applications/software that have end to end encryption (E2EE)

# Reduce Public Data
Try Googling yourself and look at the results. What did you find?

Publicly available information about you can be used:

- in targeted ads
- to dox you
- to stalk or harass you
- against you politically or socially
  - your sexual orientation, political affiliation, or gender identity

## Social Media
Here are some suggestions you can apply to all of your social media accounts:

- remove personal details such as your employer, full name, relatives, gender identity, significant others, sexual orientation, etc
- avoid sharing detailed personal information in social media comments
- opt out of data sharing
- block access to your location
- block access to your address book
- disable cross-website tracking
- disable third party cookies
- make your profiles private

## Public Records
Depending on your location and situation, you may request your public records be hidden from public-facing websites run by local, county, and state-wide entities. This guide provides tools to help you get started.

## Data sharing
Outside of social media, most websites you have an account with have privacy settings. For sites that allow it, opt out of third-party data sharing.

## Unused accounts
If you have accounts on websites that you’re no longer active on, deactivate or delete them. Before deletion, you may need to request your information be removed from their database. Deleting unused accounts will shrink your digital footprint.

## Data brokers
Data brokers collect information about you to sell. People finder sites are a type of data broker. You can manually request your information be deleted or pay for a removal service to contact them on your behalf. US government agencies buy your location data from brokers.

Most, if not all, people finder sites include a “known associates” section of your user profile, meaning the personal details of close friends, significant others, housemates, and others can easily be linked to you.

Start here:

- modify your Google Activity settings
- Google Account
  - turn off YouTube history
  - turn off personalization
  - turn off location tracking
- opt out of prescreen offers

## Manual data removal
**Pros:** 
- free
- most effective
- you control the information you share with the data brokers

**Cons:** 
- time-consuming
- requires regular follow up
- not 100% effective

These resources will help:

- IntelTechniques Data Removal Guide
- Big Ass Data Broker Opt Out LIst Github
- Privacy Guides | Data Removal Services

## Paid data removal

**What to look for:** How many data brokers they contact, reputation, and reporting.

**Pros:** 
- significantly less time-consuming
- most offer regular reporting

**Cons:**
- ongoing subscription
- you will likely have to manually reach out to some data brokers anyway
- service may unintentionally provide data brokers too much of your information

Some popular providers:

- DeleteMe
- Incogni
- EasyOptOuts
- Kanary
- Optery
  - concerns around OpenAI use

# Web Browsing
Your ISP (internet service provider), phone apps, cellular provider, web browser, and websites all see some amount of information about you when you use their services.

## Browsers

### Chrome
Chrome is not recommended for privacy. Google harvests vast swaths of data, and Chrome will disable ad blockers with manifest v3.

If you use Chrome, here are some recommendations:

- use a VPN
- turn off everything related to ads and tracking
- change the default search engine to DuckDuckGo or another of your preference
- turn on secure browsing
- advanced security settings
- uBlock Origin Lite extension once uBlock Origin is disabled
- use a password manager
- block / reject third party cookies

### Safari
Apple does not allow you to uninstall Safari. If you want to use another browser, you only need to change the default browser in your settings.

If you use Safari, here are some recommendations:

- use a VPN
- change the default search engine to DuckDuckGo or another of your preference
- turn off everything related to ads and tracking
- block / reject third party cookies
- turn on hide your IP
- uBlock Origin
- use a password manager

Many privacy settings can be found here.

### Edge
Much like Apple with Safari, Microsoft does not allow you to uninstall Edge. If you use another browser, I recommend the following:

- change the browser used in taskbar search: https://www.youtube.com/watch?v=tSIyvUFdoyc
- disable Edge background services
- disable startup features
- block tracking you while you use other browsers: 

If you use Edge, here are some recommendations:

- turn on tracking prevention
- turn on send “do not track” requests
- turn off optional diagnostic data
- you need to have optional diagnostic data turned off in your Windows settings
- turn off personalization & advertising
- use uBlock Origin
- change the default search engine to DuckDuckGo or another of your preference
- use a VPN
- password manager (instead of saving them in the browser)

More settings and information can be found here.

### Tor Browser
**Pros:**
- best for privacy
- best for anonymity
- doesn’t require a VPN (in fact a VPN is not recommended)
- mitigates fingerprinting

**Cons:**
- add-ons/extensions not recommended, they might break the browser or compromise your privacy
- slower performance

### Firefox
**Pros:**
- good choice for privacy
- user friendly
- near feature parity with Chrome
- supports many add-ons and extensions

**Cons:**
- smaller selection of extensions than Chrome
- can use a lot of RAM
- less user friendly than Chrome

### Brave
**Pros:**
- great for privacy
- blocks ads by default
- mitigates fingerprinting

**Cons:**
- crypto settings turned on by default
- small selection of extensions
- websites might break due to its strict privacy and ad blocking features

### DuckDuckGo
**Pros:**
- user friendly
- good for privacy

**Cons:**
- lack of extension support
- DDG search engine pulls from Bing, which some users dislike

## Search engines
Google is one of the worst offenders when it comes to surveillance capitalism.

### DuckDuckGo (DDG)
- most popular privacy-focused search engine
- doesn’t link your IP address to your identity
- blocks most third party cookies and trackers by default
- aggregates search results from Bing and DDG’s own indexing

### Start Page

### Brave

### Kagi
- paid service

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

### Password manager

### VPN

## Website cookies
Think of cookies as identifiers that tie your browsing activity to you. There are browser settings and extensions that will block third party cookies automatically. When a website asks you to accept cookies, choose “reject” or “necessary cookies only.”

## VPNs
**What:** A VPN is a virtual private network that can encrypt your internet traffic and masks your IP address.

**Why:** VPNs are useful when using public wifi or when you wish to mask your IP address while browsing the web. Reasons to mask your IP address.

**What to look for:** Whether the VPN service logs/saves your activity and their reputation.

Select a VPN provider that does not log your activity. Confirm they don’t save user logs by checking if they’ve been independently audited. Here are some providers who have been third party verified (based on this post) and are popular:

- NordVPN
- Surfshark
- ExpressVPN
- Proton
- Mullvad
- PIA

Mullvad accounts are randomly generated without your personal details, and they accept cash payment, meaning your account can’t easily be tied to you. Proton also accepts cash.

**Important:** People have the false impression that a VPN will keep them completely anonymous regardless of their online activity. This is incorrect.

**Consider this:** You post from a fake account on a forum, but you’re on a VPN, so your IP address is masked. However, you then place an online order for pizza delivery while still logged into the VPN. That IP address is now directly tied to your address and forum post.

**Takeaway:** A VPN masks your IP address but can still be linked to you based on your online activity. This is why disabling things like tracking and third party cookies is useful. If anonymity is your goal, check out The Hitchhiker’s Guide.

## Passwords
Passwords saved in an encrypted app, extension, or software that requires login credentials and 2FA/MFA are safer than in your browser. Always change default passwords and avoid reusing passwords. CISA best practices guide.

### Passkeys

If setting up a passkey is an option, choose it over a password. More information here.

## Password managers
**What:** Password managers store login credentials, contact details, secure notes, and more in an encrypted “vault.”

**Why:** They enable you to save a lot of unique passwords that you don’t have to memorize.

**What** to look for: Reputation, features, and recent security breaches.

Apple and Google Passwords are secure if that’s your preference. The downside is if you lose access to your Apple ID or Google account, you’ll lose access to all of your passwords.

Some popular password managers:

- Bitwarden
- LastPass
- NordPass
- 1Password

## MFA / 2FA
**What:** Multi-factor (MFA) and 2-factor (2FA) authentication are an extra step to verifying your identity when you log into something.

**Why:** These measures help prevent unauthorized access to your accounts by requiring additional steps to log into an account.

**TL;DR:** Enable MFA and 2FA for everything.

There are four **types** of authentication, and a variety of **methods** to achieve each type.

| Type | Method(s) |
| ----------- | ----------- |
| something you know | password, PIN, security questions |
| something you have | one time password (OTP), authenticator app | 
| something you are | biometrics such as face ID or fingerprint | 
| somewhere you are | geolocation | 

Your username and password fall under the “something you know” authentication **type**.

**2FA** requires you to present one (1) additional authentication **method** along with your username and password. 2FA allows you to use the same **type** of method (e.g. something you know, like a PIN or security question).

**MFA** requires you to present at least one (1) additional authentication **method** along with your username and password. However, the additional method cannot be the same **type**. For example, if you log in with a username/password, you cannot use a PIN, but you can use an authenticator app or biometrics.

MFA is considered more secure than 2FA, and both are more secure than single-factor authentication (just a username and password).

# Artificial Intelligence (AI)
If no AI haters exist, then I’m dead.

- privacy concerns
- steals from artists/creatives
- unsustainable resource consumption
- generative AI uses more resources than task-specific tools

AI can be a useful tool to those with disabilities, so abandoning it entirely is not an option for everyone. When most people think of AI, they think of generative AI, but narrow AI has been around for years. Generative AI poses a large risk to privacy. Here’s the difference.

What you can do to protect your privacy:

- opt out of AI training
  - this Wired guide is a good place to start
- never provide personal information to AI tools like ChatGBT
- disable unused AI features on your devices

# Phones
**Important:** Police are allowed to ask you to use biometrics to unlock your phone. Courts currently consider the use of biometrics as a “nontestimonial act.”

**Testimonial act:** Providing a password or PIN is considered a testimonial act because it involves revealing potentially incriminating information.

**Nontestimonial act:** Using a fingerprint or facial recognition relies on physical characteristics instead of personal knowledge, and is therefore considered a nontestimonial act.

With this in mind:

- leave your phone and smartwatch at home when attending protests
- consider disabling face ID / fingerprint when you’re outside of the home
- if you are stopped by police, and it’s safe to do so, turn off your phone
  - turning off your phone may prevent police from breaking into it with Cellebrite
- for the safety of Black folks and other POC, you need your phone available to record police interactions
  - you may want to disable face ID / fingerprint instead
- on iOS, quickly disable face ID by triggering the “power off” screen, then canceling
- on Android, you can enable lockdown mode from the lock screen

### Phone Number Masking
Alternative to giving your actual phone number out. This Proton blog post offers tips on what to look for.

Some examples:

- Mozilla Relay
- Google Voice

### Automatic Updates
Turn on automatic updates.

- regular software updates patch vulnerabilities.
- the latest versions may foil tools like Cellebrite and GrayKey

### Restart Daily

## iPhone Settings

### Turn on Advanced Data Protection

### Push Notifications
Push alerts from apps can be tied to your identity.
- turn off notification previews while your phone is locked

### Turn on Two-Factor Authentication (2FA)

### Set up Account Recovery
Save your key in a safe location like a fire safe or password manager. Do not save it on any of your Apple devices.

### Face ID / Passcode Settings
- Passcode
  - use a 6 digit passcode instead of 4
  - consider using a password instead as it’s more secure
- Turn on ‘Face ID Attention’
- Turn on ‘Require passcode outside of your home’
- Disable control center when the phone is locked

### Screen Time Settings
- Set up ‘Allow changes to: Passcode & Face ID’
  - This disables the ability to make changes to Passcode or Face ID and hides the option from your settings. To increase the effectiveness of this setting, you should set a Screen Time passcode and make sure it’s different from your iPhone passcode.

### Enable Find My tracking when the phone is turned off

### Turn off ‘Location Services’
Toggle off for any app that does not require your location for functionality and use “while using app” for everything else. Location data brokers.

### Turn off ‘Allow Apps to Request to Track’

### Set up ‘Stolen device protection’

### Turn off Airdrop
Or set to “Contacts Only.”

## Android Settings
Start here to understand the privacy and security settings available to you.

### Notifications
Don’t show any notifications or Hide silent conversations and notifications. Turn off sensitive notifications when locked.

### Turn off ‘Web & App Activity’

### Location
Deny anything that doesn’t need your location, and turn on “while in use” for apps that need your location sometimes.

### Turn off personalization

### 2FA

### Device admin apps
Disable admin privileges for apps that don’t require it.

### Permission manager
Use this to review individual app permissions.

### Android updates
Regular software updates patch vulnerabilities.

## Useful Apps
- Privacy.com
- Signal
- Threema
- Session
- Telegram

## Apps to Avoid
- Temu
  - It’s probably malware.
- Period trackers
There is valid concern that data from period tracker apps will be used against someone who received an abortion. Even the Stardust app has been guilty of sharing user data. Here’s a 2022 Wired article that covers the concern around period tracker privacy. Clue scored the highest, but doesn’t support local storage, which is a key privacy feature you should look for.

Tracker apps that store your data on your phone instead of the cloud:
- Euki
- Drip

# Computers
Most of you are probably not going to use Linux. I think Linux is the best option for security and usability. Consider Debian or Ubuntu. This TechRadar article has some additional OS recommendations.

## MacOS Settings

### FileVault
Full disk encryption prevents someone from exfiltrating data on your hard drive in the event your computer is seized or stolen. You must save your recovery key in a safe place that’s not on your computer’s hard drive.

### Antivirus
Not generally recommended. MacOS has built-in protection tools that help prevent malware from being installed. Here’s an explanation of those features and their shortfalls.

### Updates
Regular software updates patch vulnerabilities.

## Windows Settings

### BitLocker
Full disk encryption prevents someone from exfiltrating data on your hard drive in the event your computer is seized or stolen. You must save your recovery key in a safe place that’s not on your computer’s hard drive.

### Turn off ‘Diagnostic data’

### Turn off ‘Improve inking and typing’

### Turn off ‘Tailored experiences’

### Antivirus
Windows Defender is built-in and enough for 99% of people. You may wish to supplement it if you’re torrenting or downloading unofficial software.

### Updates
Regular software updates patch vulnerabilities.

## Cloud Storage
The safest place your data can be stored is locally on your physical devices. If that’s not an option, it’s possible to improve cloud storage security.

**What to look for:** End to end encryption and what information could be handed over if subpoenaed.

iCloud, Google Drive, and OneDrive are considered safe, but you may want to activate advanced security settings. This Wired guide is a good starting point.
- iCloud security overview
- Google Drive key security controls
- OneDrive security overview

These companies are required to comply with local regulations if subpoenaed. Consider manually encrypting sensitive files/folders. Use a long, complex password and store it in a fire safe AND password manager.
- encrypt on Windows
- encrypt using 7zip
- encrypt on MacOS

# Email

### Email masking
- Firefox Relay

### Use multiple accounts
I recommend one email address to use professionally (resume, job apps, etc). Then use other email accounts for everything else.

### Privacy-focused options
- ProtonMail

### Temporary email options
- Emailnator
- 10 minute mail

# Resources
Here are some resources if you’d like to learn more.
- Electronic Frontier Foundation
- Privacy Rights Clearinghouse
- The Digital Standard
- Surveillance Technology Oversight Project
- Kaspersky
- IntelTechniques
- Privacy Guides
