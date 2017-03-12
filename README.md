osx-security-awesome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)[![Travis](https://travis-ci.org/kai5263499/osx-security-awesome.svg?branch=master)](https://travis-ci.org/kai5263499/osx-security-awesome)
========================

A collection of OSX/iOS security related resources

## News

1. [The Safe Mac](http://www.thesafemac.com/)
* [Mac Virus](https://macviruscom.wordpress.com)
* [Mac Security](http://macsecurity.net/news/)
* [OSX Daily](http://osxdaily.com/) - Not secutiy-specific but it contains jailbreaking information which has security implications
* [Intego Mac Security Blog](https://www.intego.com/mac-security-blog/)

## Hardening

1. [Launchd](http://www.launchd.info/) - Everything you need to know about lunachd
* [OSX startup sequence](http://osxbook.com/book/bonus/ancient/whatismacosx/arch_startup.html)
* [Gogle OSX hardening](https://www.usenix.org/conference/lisa13/os-x-hardening-securing-large-global-mac-fleet)
* [Run any command in a sandbox](https://www.davd.eu/os-x-run-any-command-in-a-sandbox/)
* [OSX El Capitan Hardening Guide](https://github.com/ernw/hardening/blob/master/operating_system/osx/10.11/ERNW_Hardening_OS_X_EL_Captain.md)
* [Hipster DFIR on OSX](https://speakerdeck.com/sroberts/hipster-dfir-on-osx-bsidescincy)
* [OSX application hardening scorecard](http://cyber-itl.org/blog-1/2016/9/12/a-closer-look-at-the-osx-continuum)
* [Hardening hardware and choosing a good BIOS](https://media.ccc.de/v/30C3_-_5529_-_en_-_saal_2_-_201312271830_-_hardening_hardware_and_choosing_a_goodbios_-_peter_stuge) - Protecting against evil maid attacks

## Malware sample sources

1. [Alien Vault](https://www.alienvault.com/blogs/labs-research/os-x-malware-samples-analyzed)
* [Objective-See](https://objective-see.com/malware.html)
* [Contagio malware dump](http://contagiodump.blogspot.com/2013/11/osx-malware-and-exploit-collection-100.html)
* [Manwe Mac malware feed](http://macmalware.manwe.io) - Regularly updated fresh mac malware feed
* [exploit-db.com](https://www.exploit-db.com) - Great place to look for local and remote exploits

## Forensics

1. [Artefacts for Mac OSX](http://sud0man.blogspot.fr/2015/05/artefacts-for-mac-os-x.html?m=1) - Locations of sensitive files
* [Pac4Mac](https://github.com/sud0man/pac4mac) - Forensics framework
* [Inception](https://github.com/carmaa/inception) - Physical memory manipulation
* [Volafox](https://github.com/n0fate/volafox) - Memory analysis toolkit
* [Mac4n6](https://github.com/pstirparo/mac4n6) - Collection of OSX and iOS artifacts
* [Keychain analysis with Mac OSX Forensics](https://forensic.n0fate.com/wp-content/uploads/2012/07/Keychain-Analysis-with-Mac-OS-X-Memory-Forensics.pdf)
* [OSX Collector](https://github.com/Yelp/osxcollector) - Forensics utility developed by Yelp
* [OSX incident response](https://www.youtube.com/watch?v=gNJ10Kt4I9E) - OSX incident response at GitHub
* [iOS Instrumentation without jailbreaking](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2016/october/ios-instrumentation-without-jailbreak/) - How to debug an iOS application that you didn't create
* [Certo](https://www.certosoftware.com/) - Paid service for analyzing the iTunes backup of your iOS device

## Reverse engineering

1. [New OS X Book](http://www.newosxbook.com/)
* [Collection of OSX reverse engineering resources](https://github.com/michalmalik/osx-re-101)
* [The iPhone Wiki](https://www.theiphonewiki.com/wiki/Main_Page)
* [Reverse engineering OSX](https://reverse.put.as/)
* [OSX crackmes](https://reverse.put.as/crackmes/) - A collection of puzzles to test your reverse engineering skills
* [Solving crackmes with LDPRELOAD](http://radare.today/posts/solving-crackmes-with-ldpreload/)
* [Introduction to Reverse Engineering Cocoa Applications](https://www.fireeye.com/blog/threat-research/2017/03/introduction_to_reve.html)

## Presentations and Papers
1. [Writing Bad @$$ Malware for OSX](https://www.slideshare.net/Synack/writing-bad-malware-for-os-x) - [Video](https://www.youtube.com/watch?v=fv4l9yAL2sU) and [another related video](https://www.youtube.com/watch?v=oT8BKt_0cJw)
* [Methods of Malware Persistence on OSX](https://www.youtube.com/watch?v=rhhvZnA4VNY)
* [Hack Mac OSX](https://dl.dropboxusercontent.com/u/31995154/HackMACOS-PUB/prez/HackMacOSX-GSDays2012.pdf)
* [Advanced Mac OSX Rootkits](https://www.blackhat.com/presentations/bh-usa-09/DAIZOVI/BHUSA09-Daizovi-AdvOSXRootkits-SLIDES.pdf)
* [The Python Bytes Your Apple](https://speakerdeck.com/flankerhqd/the-python-bites-your-apple-fuzzing-and-exploiting-osx-kernel-bugs) - Fuzzing and exploiting OSX kernel bugs
* [Breaking iOS Code Signing](https://papers.put.as/papers/ios/2011/syscan11_breaking_ios_code_signing.pdf)
* [The Apple Sandbox - 5 years later](http://newosxbook.com/files/HITSB.pdf)
* [Practical iOS App Hacking](https://papers.put.as/papers/ios/2012/Mathieu-RENARD-GreHACK-Practical-iOS-App-Hacking.pdf)
* [Behavioral Detection and Prevention of Malware on OS X](https://www.virusbulletin.com/blog/2016/september/paper-behavioural-detection-and-prevention-malware-os-x/)
* [Security on OSX and iOS](https://www.youtube.com/watch?v=fdxxPRbXPsI) - [Slides](https://www.slideshare.net/nosillacast/security-on-the-mac)
* [Thunderstrike](https://trmm.net/Thunderstrike_31c3) - [Video](https://www.youtube.com/watch?v=5BrdX7VdOr0), hacking Mac's extensible firmware interface (EFI)
* [Direct Memory Attack the Kernel](https://github.com/ufrisk/presentations/blob/master/DEFCON-24-Ulf-Frisk-Direct-Memory-Attack-the-Kernel-Final.pdf)
* [Don't trust your eye, Apple graphics is compromised](https://speakerdeck.com/marcograss/dont-trust-your-eye-apple-graphics-is-compromised), security flaws in IOKit's graphics acceleration that lead to exploitation from the browser
* [Fuzzing and Exploiting OSX Vulnerabilities for Fun and Profit Complementary Active & Passive Fuzzing](https://www.slideshare.net/PacSecJP/moony-li-pacsec18?qid=15552f01-6655-4555-9894-597d62fd803c)
* [Strolling into Ring-0 via I/O Kit Drivers](https://speakerdeck.com/patrickwardle/o-kit-drivers)
* [Juice Jacking](https://www.youtube.com/watch?v=TKAgemHyq8w)
* [Attacking OSX for fun and profit tool set limiations frustration and table flipping Dan Tentler](https://www.youtube.com/watch?v=9T_2KYox9Us) - [Follow-up from target](https://www.youtube.com/watch?v=bjYhmX_OUQQ)
* [Building an EmPyre with Python](https://www.youtube.com/watch?v=79qzgVTP3Yc)
* [PoisonTap](https://www.youtube.com/watch?v=Aatp5gCskvk)

## Virus and exploit writeups
1. [Flashback](https://www.cnet.com/news/more-than-600000-macs-infected-with-flashback-botnet/) - [Detailed analysis](https://www.intego.com/mac-security-blog/more-about-the-flashback-trojan-horse/)
* [Flashback pt 2](https://www.intego.com/mac-security-blog/flashback-botnet-is-adrift/)
* [iWorm](http://www.thesafemac.com/iworm-method-of-infection-found/) - [Detailed analysis](https://www.intego.com/mac-security-blog/iworm-botnet-uses-reddit-as-command-and-control-center/)
* [Thunderbolt](http://www.theregister.co.uk/2015/01/08/thunderstrike_shocks_os_x_with_first_firmware_bootkit/) - Firmware bootkit
* [Mokes](http://thehackernews.com/2016/09/cross-platform-malware.html)
* [MacKeeper](http://www.cultofmac.com/170522/is-mackeeper-really-a-scam/)
* [OpinionSpy](http://www.thesafemac.com/opinionspy-is-back/)
* [Elanor](https://blog.malwarebytes.com/cybercrime/2016/07/new-mac-backdoor-malware-eleanor/)
* [Mac Defender](http://macsecurity.net/view/79/)
* [Wire Lurker](http://researchcenter.paloaltonetworks.com/2014/11/wirelurker-new-era-os-x-ios-malware/)
* [KeRanger](https://techcrunch.com/2016/03/07/apple-has-shut-down-the-first-fully-functional-mac-os-x-ransomware/) - First OSX ransomware
* [Proof-of-concept USB attack](http://www.ehackingnews.com/2016/09/a-usb-device-can-steal-credentials-from.html)
* [Dark Jedi](https://reverse.put.as/2015/05/29/the-empire-strikes-back-apple-how-your-mac-firmware-security-is-completely-broken/) - EFI attack that exploits a vulnerability in suspend-resume cycle [Sentinel One write-up](https://sentinelone.com/blogs/reverse-engineering-mac-os-x/)
* [XAgent Mac Malware Used In APT-28](https://labs.bitdefender.com/2017/02/new-xagent-mac-malware-linked-with-the-apt28/) - [Samples](http://contagiodump.blogspot.com/2017/02/russian-apt-apt28-collection-of-samples.html)
* [Juice Jacking](https://www.howtogeek.com/166497/htg-explains-what-is-juice-jacking-and-how-worried-should-you-be/)
* [Root a Mac with a Rubber Ducky](http://patrickmosca.com/root-a-mac-in-10-seconds-or-less/)
* [Hacking Mac with Empyre](http://www.lukeager.com/hacking-mac-empyre/)
* [Local Privilege Escalation for macOS 10.12.2 and XNU port Feng Shui](https://jaq.alibaba.com/community/art/show?articleid=781)

## Useful tools and guides
1. [jrswizzle](https://github.com/rentzsch/jrswizzle) - method interface exchange
* [MacDBG](https://github.com/blankwall/MacDBG) - C and Python debugging framework for OSX
* [bitcode_retriever](https://github.com/AlexDenisov/bitcode_retriever) - store and retrieve bitcode from Mach-O binary
* [machotools](https://github.com/enthought/machotools) - retrieve and change information about mach-o files
* [onyx-the-black-cat](https://github.com/gdbinit/onyx-the-black-cat) - kernel module for OSX to defeat anti-debugging protection
* [create-dmg](https://github.com/andreyvit/create-dmg) - CLI utility for creating and modifying DMG files
* [dmg2iso](https://sourceforge.net/projects/dmg2iso/?source=typ_redirect) - convert dmg to iso
* [Infosec Homebrew](https://github.com/kai5263499/homebrew-infosec) - Homebrew tap for security-related utilities
* [Awesome OSX Command Line](https://github.com/herrbischoff/awesome-osx-command-line) - Collection of really useful shell commands
* [Keychain dump](https://github.com/juuso/keychaindump) - Dump keychain credentials
* [KnockKnock](https://objective-see.com/products/knockknock.html) - Listing startup items. Also includes VirusTotal information
* [Lingon-X](https://www.peterborgapps.com/lingon/) - GUI for launchd
* [Hopper](https://www.hopperapp.com/) - Excellent OSX debugger (requires license)
* [Symhash](https://github.com/threatstream/symhash) - Python utility for generating imphash fingerprints for OSX binaries
* [KisMac2](https://igrsoft.com/en/kismac2/) - Wireless scanning and packet capturing
* [Passive fuzz framework](https://github.com/SilverMoonSecurity/PassiveFuzzFrameworkOSX) - Framework is for fuzzing OSX kernel vulnerability based on passive inline hook mechanism in kernel mode
* [Platypus](http://sveinbjorn.org/platypus) - GUI for generating .app bundles
* [createOSXinstallPkg](https://github.com/munki/createOSXinstallPkg) - CLI for generating .pkg installers
* [PoisonTap](https://github.com/samyk/poisontap)
* [Chipsec](https://github.com/chipsec/chipsec) - System firmware checker by Intel

## Remote Access Toolkits
1. [Empyre](https://github.com/EmpireProject/EmPyre)
* [Bella](https://github.com/manwhoami/Bella)
* [Stitch](https://nathanlopez.github.io/Stitch/)
* [Pupy](https://github.com/n1nj4sec/pupy)

## Worth following on Twitter
1. [@patrickwardle](https://twitter.com/patrickwardle)
* [@objective_see](https://twitter.com/objective_see)
* [@0xAmit](https://twitter.com/0xAmit)
* [@Morpheus______](https://twitter.com/Morpheus______)
* [@osxreverser](https://twitter.com/osxreverser)
* [@liucoj](https://twitter.com/liucoj)
* [@osxdaily](https://twitter.com/osxdaily)
