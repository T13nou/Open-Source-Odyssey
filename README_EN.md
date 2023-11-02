# Open-Source-Odyssey
My 100% Open Source Life: A Digital Odyssey towards Freedom and Collaboration

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/banner.png" width="1000" height="434">

## Summary
1. [Introduction](#introduction)
2. [Why Open Source?](#why)
3. [Setting up the Open Source infrastructure](#infra)
4. [Open Source Operating Systems](#os)
5. [Open Collaboration and the Power of Community](#collab)
6. [Let's spread the message!](#message)
7. [This is not a conclusion](#continue)
8. [Questions/Answers](#q&a)
9. [My progress](#progress)

# I. Introduction <a name="introduction"/>

Welcome to my page dedicated to my 100% open source adventure.  Here I share my personal journey towards exclusively using open source tools in my daily life.  My approach revolves around open collaboration, the power of community and my commitment to computer privacy and digital hygiene.

At the heart of my journey, I set up an infrastructure at home, including an open source router, a NAS server dedicated solely to open source productivity tools, and even converted my gaming PC using Arch Linux, as well as a portable game console running under the same distribution.  I have chosen to no longer use any proprietary products, and I strive to share my experience and encourage those around me to understand this philosophy.

Furthermore, I chose to put this article on GitHub which seems to me to be an appropriate place to share my approach with the community and allow everyone to contribute to it.

What this article is not a technical guide, others already do, but I would direct you to very specialized and relevant resources on the different subjects that I address.

Join me to discover how open source can not only offer an alternative to proprietary software, but also promote digital freedom, the security of our data, and collective innovation.  Together, we will explore the benefits of open source, its transformative potential, and the joys of living a more transparent digital life that respects our individual rights.  Welcome to my 100% open source world!

## Who am I ?

As I journey towards exclusively using open source tools and explore open collaboration, it is essential to understand the context and experience that led me to this journey.  Here is an overview of who I am, my professional journey, and what drives me in this adventure towards a more open and collaborative digital world.

|  My profile... |  ... in brief |
|  --- |  --- |
|  <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/avatar.512.png"> |  A Journey Focused on Collaboration: For more than 15 years, I have devoted myself to collaborative topics, whether within my professional career or my personal projects.  My journey has been built on the conviction that collaboration is a key to innovation and progress.  I sought to promote cooperation, knowledge sharing and collective creation |

My training as an electronics/computer engineer gave me solid technical skills, while allowing me to understand the complex aspects of technology and computing.  This combination of skills inspired me to explore how technology can be used to foster collaboration and openness.

You can learn more about my professional background by consulting my profile [LinkedIn](https://www.linkedin.com/in/etienneblanchet/)

My passion for open source and open collaboration is rooted in a deep conviction: technology can be used to bring people together, facilitate the sharing of ideas and solve complex problems collectively.  My career has led me to work on various projects, from the design of electronic solutions to the implementation of open source frameworks within my company.

Today, I apply these principles of openness and collaboration in my personal and professional life.  My commitment to open source and open collaboration is based on the belief that these approaches can transform the way we work, innovate and build a better digital future for all.

# II.  Why Open Source?  <a name="why"/>

Open source software is less likely to become obsolete or abandoned by its publisher because the responsibility for its development rests with the community rather than a single company.  This ensures the sustainability of open source solutions, which is crucial for long-term projects.

While writing this article I asked myself the question of *forks* and whether the most popular projects or those which are no longer maintained were regularly forked.  GitHub maintains its [Top-100](https://github.com/EvanLi/Github-Ranking/blob/master/Top100/Top-100-forks.md) of the most *forked* projects and surprise, some do have been more than 100,000 times.  The community is active!  ⚙️

### 💡Continuous Innovation

Open source encourages continuous innovation.  By allowing anyone to contribute to and improve software, open source promotes a rapid cycle of innovation.  Many open source projects are driving new ideas and technologies that impact the entire industry.

### 🔒 Respect for Privacy

With privacy concerns on the rise, open source offers a way to keep data confidential.  You have greater control over what is collected and shared, which is essential to protect your personal and sensitive information.

These cumulative benefits illustrate why open source has become much more than just an alternative to proprietary software.  It embodies a philosophy of collaboration, transparency and respect for individual freedom, while offering powerful and sustainable technological solutions.  My journey to open source has convinced me that these benefits are essential to shaping a more promising digital future.

I invite you to explore the subject with the channel of [Rob Braxman](https://www.youtube.com/@robbraxmantech), defining himself as an *Internet Privacy Evangelist*, an evangelist for respect for privacy. privacy on the Internet.  His proposal is assumed to be extreme: he uses one device per use case (public, private), lives on a boat and regularly warns of the dangers of our technological environment.  He applies the *off the grid* principle of life to himself.  To be taken with a grain of salt but I agree with most of his articles.

# III.  Setting up the Open Source infrastructure <a name="infra"/>

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/build.png" width="1000" height="250">

The creation of a fully open source infrastructure was marked by the search for "quick wins", these small initial victories which reinforce the conviction that the chosen approach is the right one.  My journey began with inspiration from an article by Larry Sanger, co-founder of Wikipedia, where he shared his thoughts on privacy and digital hygiene.

However, to consolidate my first steps, I sought to cross-check this information with other trusted sources, in order to build a solid foundation for my open source infrastructure.  Among the resources that guided my choices, here are some of the most influential:

## 🥼 Reference sites for homelabing and “Privacy” oriented tools

|  Channel |  Content |
|  ------------- |  ------------- |
|  PrivacyTools.io <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/sites/th-2200279595.jpg" width="140" height="140"> |  This website has become a benchmark for online privacy protection.  Regularly updated, it offers a multitude of tools and recommendations to meet various use cases, from secure web browsing to password management and email confidentiality.  It has become an essential starting point for anyone looking to boost their online privacy.  |
|  homelabing.com <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/sites/homelabing_icon-1.png" width="140" height="140"> |  Optimize your Homelab capabilities through self-hosting and utilizing open-source solutions |
|  servethehome.com <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/sites/STH-Logo-180px.png" width="140" height="140" > |  ServeTheHome is the IT professional's guide to high-end servers, storage, networking, and workstation hardware, as well as great open source projects.  |
|  homenetworkguy.com <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/sites/m53vjCup_400x400-2937981742.jpg" width="140" height="140"> |  The website aims to provide a user-friendly resource with advice, troubleshooting tips and shared experiences to help others build their own advanced home networks.  |

## 📹 Channels dedicated to Homelabing on YouTube:

|  Channel |  Content |
|  ------------- |  ------------- |
|  Techno Tim [![Watch the video](https://yt3.googleusercontent.com/ytc/APkrFKa_0lAyGQzwuWn77xGeWQqXpOypgXqFHNZ3GL91Vg=s176-ck-c0x00ffffff-no-rj)](https://www.youtube.com/@TechnoTim) |  Techno Tim has become an invaluable source of information on building a homelab, offering how-to guides and demonstrations of open source technologies.  |
|  NetworkChuck [![Watch the video](https://yt3.googleusercontent.com/ytc/APkrFKb728FaC4SPqir0jCVxhY0NTgnHD-iP2MqbSIrj9g=s176-ck-c0x00ffffff-no-rj)](https://www.youtube.com/@NetworkChuck) |  NetworkChuck explores a wide range of technology topics, including open source solutions for networks and servers.  |
|  Wolfgang's Channel [![Watch the video](https://yt3.googleusercontent.com/ytc/APkrFKYVoDrnSDACycgSJNnTkac6M6HROYVgJIfxAu6-ug=s176-ck-c0x00ffffff-no-rj)](https://www.youtube.com/@WolfgangsChannel ) |  Wolfgang delves into the technical aspects of homelabing, providing detailed information on using open source tools.  |
|  Christian Lempa [![Watch the video](https://yt3.googleusercontent.com/YO4Re8Kv_C0uC-WjtAh0W93Tfv6kJ0Ri7ENCUVWjJwIaBTTbly_-g6525UkqqvKmLv1ME9pBOg=s176-ck-c0x00ffffff-no-rj)](https://www.youtube.com/@christ ianlempa ) |  Christian Lempa's channel focuses on self-hosted IT infrastructures, exploring open source solutions to improve personal digital lives.  |
|  Adrien Linuxtricks [![Watch the video](https://yt3.googleusercontent.com/ytc/APkrFKYE_aERPU37zbKhTQUpPLeX6wpntPDj-ftpJN6uww=s176-ck-c0x00ffffff-no-rj)](https://www.youtube.com/@AdrienLinuxtricks ) |  AdrienLinuxtricks is a YouTube channel focused on Linux and open source software.  You'll find tutorials, tips, reviews of Linux distributions, and guides to maximize your experience with open source technologies.  This channel is ideal for Linux enthusiasts, whether beginners or experienced users, looking to explore and master the world of open source.  |
|  Chris Titus Tech [![Watch the video](https://yt3.googleusercontent.com/R_rSQnTYQkL-rbtTA7djVbXLjU8Bwgua8GHJz6Ollsbyx_txdu0qVDBudCqvpzaxRQfVp2F4=s176-ck-c0x00ffffff-no-rj)](https://www.youtube.com/@ChrisTitus Tech) |  ChrisTitusTech is a YouTube channel that covers a wide range of technology topics, from computing and software to productivity tips and hardware reviews.  Host Chris shares his expertise in an accessible way, offering practical guides and recommendations.  This channel is suitable for everyone who is interested in technology and looking for advice and information on various IT topics.  |

By drawing on these resources, I was able to lay the foundation for my open source infrastructure and strengthen my understanding of the tools and practices that ensure my privacy and security online.  These first steps helped me build a solid foundation for the rest of my journey towards exclusively using open source tools, focused on privacy, transparency and innovation."

## 🌐 Use an open-source web browser

The first step in my journey to an open source digital experience began with searching for an alternative to Google Chrome.  Although Chrome is a popular and efficient browser, I was increasingly aware of concerns around privacy and data collection.  So I set out to find an open source solution that could meet my web browsing needs.

After extensive research, Mozilla Firefox quickly became the solution of choice.  Mozilla, as a nonprofit organization, is strongly committed to online privacy.  Firefox is an open source browser that embodies these values, offering full transparency over its source code and open philosophy.  It’s a choice that perfectly suited my approach in favor of open source.

For managing my passwords, I opted for the Bitwarden extension, an open source password manager.  The advantage of Bitwarden is its compatibility with my self-hosted installation of Bitwarden on my NAS server.  This integration allows me to manage my passwords securely and store them locally, strengthening my online security.

When it comes to managing website, ad and malware filtering, I delegated this task to my OPNsense router.  This open source router is equipped with a DNS module based on filtering lists, similar to a Pi-Hole.  This solution allows me to actively block ads, trackers, and malicious websites at a central level, protecting all devices on my home network.  This not only enhances my privacy, but also the security of my online activities.

## 📫 Use a Privacy-Concerned Email Service

One of the first areas I wanted to address was email.  Choosing a suitable messaging service is of crucial importance as it affects the confidentiality of communications and the security of personal data.

I was particularly attentive to several aspects in my quest for an email service concerned with privacy:

1. Content Monetization: One of my main concerns was to avoid email providers that monetize their users' content.  Many large email platforms generate revenue by analyzing email content and displaying targeted advertisements.  This practice is contrary to my values ​​of privacy and respect for confidentiality.

2. Encryption at the Source: Email encryption is essential to prevent unauthorized interception of messages.  I looked for a provider that encrypts emails from the start, ensuring that only the sender and recipient have access to the content.  Encryption at the source is a fundamental element in guaranteeing the confidentiality of communications.

3. Hosted in Europe: As a privacy-conscious user, choosing the location of email servers is of crucial importance.  I opted for an email service hosted in Europe, which allows for strict data protection and privacy standards.  This adds an extra layer of security to my communications.

4. Avoiding “Vendor Lock-In”: The idea of ​​remaining tied to a single email provider was contrary to my vision of an open and flexible digital environment.  I looked for a provider that didn't impose lock-in on a proprietary ecosystem, providing the ability to migrate to other services if necessary.

Among the options available to me
- Self-host my own email server: tricky to configure because it relies on security and antispam technologies that I have little control over :) Furthermore, email delivery requires a reliable connection available 365 days a year (or use a gateway most often paid).
- Use a paid solution from a third-party provider.

For my part, I only use email a little and what I receive is not critical, so I decided to make a compromise by making my life easier and choosing a provider who seems reliable and meets the above criteria. .

After looking at many options, I finally chose Soverin.net as my email provider.  While Soverin.net isn't necessarily perfect, it addresses several of my core concerns.  It does not monetize the content of my emails, offers robust encryption, is hosted in Europe, and does not "lock" me into a proprietary ecosystem.

This approach to electronic messaging is part of my overall approach to respecting privacy and promoting open source.  It ensures that my communications remain confidential, secure and under my control, while avoiding the intrusive practices and restrictions often associated with traditional email providers.  As part of my journey towards exclusively using open source tools, this decision reflects my commitment to computer privacy and digital hygiene.

The service is paid (~25€/$ per year) but it is an easy first step in my approach.

## 🚧 Control my data by hosting my own NAS server - The Beginning of HomeLabing

My journey to a fully open source infrastructure has also led me to rethink how I store and manage my data.  Initially, I used a proprietary NAS solution from Synology.  Although this option offered some stability, I quickly realized its limitations.  The environment was underperforming, and adding additional services was often complicated or impossible.

So I set out to research alternatives, considering various open source solutions.  I explored options like TrueNAS Core, Open Media Vault, and Unraid, each with their pros and cons.  After careful analysis, I finally opted for TrueNAS Scale, a solution based on a Debian base that I cherish for its openness and stability.

[TrueNAS Scale](https://www.truenas.com/truenas-scale/) won me over with its ZFS-based storage environment.  This file system offers many advantages, including the ability to create snapshots, its robustness, data deduplication, and compression.  These features are essential to guarantee the integrity of my data while optimizing storage space.

One of the strengths of TrueNAS Scale is its application catalog, which offers a variety of services, all in a containerized environment.  I have the choice between Docker and Kubernetes to deploy and manage my applications.  Additionally, TrueNAS Scale has KVM-based hypervisor functionality, which in my opinion remains a safe bet when it comes to virtualization.

Thanks to TrueNAS Scale, my NAS server now hosts a set of applications essential to my digital life.  NextCloud lets me store and sync my files securely, PhotoPrism manages my photo collection in an organized way, PleX gives me access to my media library, and Bitwarden takes care of managing my passwords securely.

However, I made the decision not to centralize everything on my NAS server.  Critical IT services, such as the OPNsense router, HAProxy reverse proxy, Let's Encrypt certificate management, as well as all services for securing my network and access to applications, are installed on dedicated hardware.  This approach ensures effective management of these crucial elements and strengthens the security of my network.  In the following chapters, I will detail the implementation of these essential services in more detail.

Here is the configuration I opted for in order to accomplish my goal
- Box: Kolink Satellite
- CPU: Intel 12100T
- Motherboard: Asrock Z690M-ITX/ax
- Ram: 2x 32GB Crucial
- Boot storage (boot-pool): 2 x 500GB Crucial MX500 SSD
- Main storage (data): 8 x 4TB Crucial MX500 SSD + LSI HBA 9300-8i
- Secondary storage (applications): 2 x 1TB Crucial P5 Nvme SSD

|  The assembled server |  The entrails |
|  ------------- |  ------------- |
|  <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/homelab/23-10-30%2014-25-46%207881.jpg" width="500" height="375"> |  <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/homelab/Screenshot_20231030_165231.png" width="500" height="375"> |

The dashboard
<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/homelab/Screenshot_20231030_165300.png" width="1000" height="390">

## 🔑 Have password hygiene and host them on my infrastructure

Like many of us, I once used a common password for most online services I signed up for.  This practice, although common, carries considerable online security risks.  Realizing these dangers prompted me to look for more secure and effective ways to manage my passwords.

My first attempt to remedy this situation was to use the password managers built into web browsers.  However, over time, I realized that I could not completely trust these managers, especially when it came to the security and control of my sensitive data.

So I adopted Keepass, an open source password manager.  Keepass has been with me for years, providing a secure solution for storing my passwords.  I even opted for cloud storage of my Keepass database, which allowed me to access my passwords from any of my devices.

However, over time I found that Keepass's approach became more and more tedious.  Managing local databases and synchronizing between devices required considerable effort.  That's when I seriously considered [Bitwarden](https://bitwarden.com/), an open source password manager, offering a more fluid and flexible solution.

One of the key advantages of Bitwarden is the ability to self-host your own password server.  This option allowed me to maintain full control of my sensitive data, without having to trust third parties.  Bitwarden apps are available for a multitude of operating systems, from desktop to mobile, making it much easier to manage passwords across all my devices.  In addition, these applications are designed to guarantee security even in the event of a connection loss, by caching and encrypting my password database.

The TrueNAS App Catalog also offers [VaultWarden](https://github.com/dani-garcia/vaultwarden), a community-run alternative implementation of Bitwarden.  Since 2019, I have used this service smoothly and without major concerns.  My passwords are stored securely and easily accessible.  This approach to password hygiene and self-hosting has been an essential component of my journey to a more secure and transparent digital experience.  It shows that open source solutions can offer robust and flexible alternatives for online security needs, which evolve over the years.

## 📆 Take back control of my contact list and calendar

My professional journey has led me to work in the field of Digital Workplace, where collaboration, the adoption of tools and means of communication are essential pillars of collective success.  In this context, I had the opportunity to work with systems such as Google Workspace and Microsoft 365, which offer a range of productivity and collaboration tools.  However, alongside these giants of the sector, I also discovered a more modest player, NextCloud, which aims to compete with the behemoths by offering an open source and self-hosted alternative.

My curiosity led me to explore this solution, even though in its first versions, NextCloud could be tricky to install and maintain.  My goal was clear: regain control of my contact list, my calendar, and my data, freeing myself from closed ecosystems such as Google Drive and Google Docs.

Several years have passed since my first steps with NextCloud, and the platform has evolved considerably.  It now offers various installation methods, making it more accessible for residential users.  It is compatible with many NAS, whether proprietary or open source.  For my part, I opted for a [NextCloud All-in-one](https://github.com/nextcloud/all-in-one) installation on a virtual machine, which provides me with all the services I need. I need.

My personal NextCloud includes an email client, a CalDAV-enabled calendar, a CardDAV-enabled contact list, note-taking tools, a Kanban board, Doodle-like functionality, and most importantly, a file manager.  This last point is essential, because it allows me to access my information, whether from home, on the move, or by collaborating with other people.

NextCloud also offers an iOS client, which automates the upload of all my photos to my NextCloud server.  This feature adds an extra layer of security by ensuring that my memories are stored privately on my own server.

In addition, NextCloud has an integrated word processor, spreadsheet, and presentation tool, allowing us to work simultaneously on the same document, while preserving control of our data. Using NextCloud has become a habit in my family, with each member using it to collaborate and access their files remotely.  This transition to a self-hosted open source solution has increased my confidence in managing my personal data, while providing a smooth and secure collaboration experience.

## 🛂 Establish a reliable and secure network

The home network, by default, is often insecure and offers few features to facilitate self-hosting.  This is why, when I decided to commit to self-hosting my services, I quickly understood that I had to manage all aspects related to connectivity, security, and implementation. available to my online services.

Self-hosting your services involves making them available on the Internet, while guaranteeing their security.  That's when I started looking for a comprehensive solution to manage all of these aspects, including DNS, DHCP, security, and setting up a VPN. .

After testing different products, including routers from ASUS, Mikrotik, and pfSense, I finally settled on [OPNsense](https://opnsense.org/).  OPNsense is an open source router/firewall solution that offers additional packages to enable the features I needed.  Its flexibility and customization capabilities convinced me.

PhasedLogix has an excellent playlist to get started with the solution.  The guy is clear and knows how to make a relatively austere solution accessible 🥇
[Learn OPNSense Firewall](https://www.youtube.com/watch?v=gLA1a7Xn924&list=PLCQ7UEq6XQ1GRtKpOkfxW6Oc_2VxkmRVc)
<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/homelab/OPNsense.png" width="1000" height="408">

To ensure the reliability and security of my network, I chose to install OPNsense on bare metal hardware, meaning the software runs directly on dedicated hardware rather than in a virtual machine.  This decision was crucial, because the router/firewall plays an essential role in the security of my network.  Among the available options, I opted for hardware from the [ProtectLI](https://eu.protectli.com/) brand, which offers quality products with an open source BIOS, [CoreBoot](https:/ /www.coreboot.org/), in line with my open source philosophy.

|  The front view |  The back view |
|  ------------- |  ------------- |
|  <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/homelab/VP2420_back_1600x1600-600x600.jpg" width="500" height="500"> |  <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/homelab/VP2420_angle-1-600x600.jpg" width="500" height="500"> |

Exposing my services on the Internet requires the use of a domain name, as well as subdomains to make each service individually accessible.  To manage this, I set up a reverse proxy [HAProxy](https://www.haproxy.com/fr), which redirects requests based on the subdomain to the corresponding service.

Managing SSL/TLS certificates is essential to ensure secure connections.  Fortunately, there is a free certificate authority, Let's Encrypt, that allows you to obtain SSL/TLS certificates in an automated way.  OPNsense makes this easy by using the ACME plugin, which automatically renews certificates, whether wildcard or not, for all my subdomains.  So each service, whether it's NextCloud, Bitwarden, Plex, and many others, is accessible via a secure subdomain.

Internal DNS also plays a key role in resolving domain names inside my network.  I chose to use the unbound service on OPNsense, using spam domain filtering lists, similar to Pi-Hole.  The result is a browsing experience free of ads and intrusive windows across my entire home network.

So, establishing a reliable and secure network has become an essential part of my journey towards an open source-based digital experience, ensuring that my services are securely accessible, both from within and from outside. outside my home network.

I really like the way in which TechnoTim was able to popularize and explain security for Homelabing very well.  We cover the subjects of firewalls, reverse proxy, network segmentation, etc.

[Self-Hosting Security Guide for your HomeLab](https://www.youtube.com/watch?v=Cs8yOmTJNYQ&t=185s)
<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/security.png" width="1000" height="516">

## 🌳 Ensuring ecological impact via a greenLabing approach

When committing to self-hosting your services, it is important to consider the ecological impact of this approach.  Indeed, the establishment of a personal infrastructure can lead to electricity consumption and expenditure on IT equipment, which must be balanced with an environmentally friendly approach.

With this in mind, I designed my self-hosting approach with energy efficiency and sustainability in mind.  Each of the devices I use was chosen for its low power consumption and longevity.  By combining these two factors, I was able to reduce the environmental impact of my infrastructure as much as possible.

All of my devices, three in number, consume a total of only 60 watts, the equivalent of what an older generation bulb would consume.  This low consumption is the result of careful selection of equipment and its sizing to guarantee optimal performance while limiting energy expenditure.

Additionally, some of my devices have been deliberately oversized to extend their lifespan and ensure compatibility with future technologies.  This technology-agnostic approach avoids frequent device replacements, thereby reducing the amount of electronic waste.

A real-world example of this approach is managing my wired and Wi-Fi network. I have deliberately separated the two devices, the router and the Wi-Fi access point, because Wi-Fi standards are evolving rapidly.  So when the next generation of Wi-Fi standard becomes available, I will only need to replace the access point, thereby preserving my router and avoiding unnecessary replacement of all equipment.

By ensuring the ecological impact of my self-hosting approach, I seek to reconcile the benefits of controlling my data and services with a commitment to sustainability and reducing my environmental footprint.  This approach is part of the GreenLabing philosophy, which consists of combining technology and respect for the planet for more responsible IT.

Interesting resources on the subject
[How to save power in a Homelab?  5 Tips!](https://www.youtube.com/watch?v=MDtbNxeHCYg)
[Answering Your Power Efficiency Questions!  |  Homelab Power Optimization Q&A ](https://www.youtube.com/watch?v=zE-COCPdyEY&t=465s)


#IV.  Open Source Operating Systems <a name="os"/>

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/bureau.png" width="1000" height="250">

One of the biggest milestones in my journey to exclusively using open source tools was my move to an open source operating system for my workstation.  This change happened thanks to a click, a revelation that came in the form of a gaming device: the [Steam Deck](https://www.steamdeck.com/fr), a portable gaming console based on Arch Linux.

As a video game enthusiast, I was impressed by the commitment of the company [Valve](https://fr.wikipedia.org/wiki/Valve_(company)) to make an impressive number of games compatible, originally intended for Windows, with Linux.  This bold move caught my attention and aroused my curiosity.

This is how I felt the desire to learn more about this operating system, to dive into the world of Linux, and to see if it could meet my needs beyond gaming. My journey naturally led me to join the [Gaming Linux FR](https://www.gaminglinux.fr/) community, where I was able to find help and advice to ease my transition from Windows to Linux.

What struck me most about this experience was the open-mindedness, the willingness to share and the dedication of the open source community to helping as many people as possible make this transition.  I quickly realized that the open source philosophy was ingrained in the DNA of this community.  Everyone was ready to share their knowledge, solve problems and make Linux accessible to everyone.

After testing different Linux distributions, including Debian, Fedora and OpenSUSE, I finally found my sweet spot with [Arch Linux](https://archlinux.org/).  This open source operating system matched my needs 100%.  It offered me the flexibility and customization I needed to tailor my work environment to my preferences.

* You want an overview of existing distributions, the reference remains [DistroWatch](https://distrowatch.com/)!
* You want to try the distributions without installing them (or even booting from a Live ISO) [DistroSea](https://distrosea.com/) will allow you to test in a VM within your browser :)

With Arch Linux, I was able to work efficiently using only open source applications, while retaining some [*Progressive Web Apps*](https://fr.wikipedia.org/wiki/Progressive_web_app) of the Microsoft applications that were essential.  This transition showed me that open source was not only a viable option, but could also meet any need, whether it was productivity, entertainment, or any other aspect of digital life.

My adventure with Arch Linux has reinforced my belief that open source is much more than an alternative to proprietary software.  It is an open, collaborative and dedicated community, ready to support users in their exploration of a freer and more transparent digital future.

I attended with great interest the [Interview with an Arch Linux packager](https://www.youtube.com/watch?v=qXvzGRm9iFs) where I was able to get a more precise idea of ​​the care taken by the community to deliver a satisfactory experience to its users and minimizing instabilities and other bugs.

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/Desktop.png" width="1000" height="562">

## Performances de Jeu au Top

| CyberPunk 2077  | CS:GO | Forza Horizon 5 |
| ------------- | ------------- | ------------- |
| <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/Screenshot_20231030_122544.png" width="320" height="177"> | <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/Screenshot_20231030_122613.png" width="320" height="177"> | <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/Screenshot_20231030_122639.png" width="320" height="177"> |

# V. Open Collaboration and the Power of Community <a name="collab"/>

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/community.png" width="1000" height="250">

One of the most inspiring aspects of my journey to exclusively using open source tools is discovering open collaboration and the tremendous power of community that comes with it.  In this chapter, we will explore the benefits of open collaboration, collective innovation and community strength, highlighting the principles of this approach.

The Foundations of Open Collaboration

Open collaboration is a philosophy based on sharing, cooperation and openness.  It promotes collaboration between individuals and groups in a transparent, free and often decentralized manner.  This approach has profound implications, not only in the open source world, but also in the professional world.

## Decentralized collaboration and the richness of multicultural perspectives

One of the most exciting aspects of open collaboration is the opportunity to work with people from diverse countries, cultures and languages.  As a follower of this philosophy, I have had the opportunity to collaborate with individuals from all over the world, using languages ​​I am fluent in such as French, English and Spanish.  This cultural diversity brings an infinite wealth of points of view, experiences and expertise.  It reinforces the idea that innovation is born from diversity.

“Collaboration is an opportunity to discover new perspectives, to push the limits of creativity and to enrich our ideas thanks to the diversity of contributors.  » - [Quote from Linus Torvalds, creator of Linux]

## The power of asynchronous collaboration

One of the key strengths of open collaboration is the flexibility it offers through asynchronous working.  Working with individuals spread across different time zones means that collaboration can continue 24 hours a day. Contributions can be made based on each person's availability, creating a continuous working dynamic.  This allows you to take full advantage of available talent, regardless of geographic location.

Some training courses exist and are very enriching.  I followed them and try to integrate the key concepts into my daily life.
- Limit the use of emails and encourage the use of a single repository for writing, documenting and interacting.  It is a “single source of truth” which facilitates information, onboarding and avoids dispersion.
- Use persistent chats so that whatever the geographical area of ​​an individual, they can learn about exchanges during their working hours.  Many tools exist: Discord, Teams, Slack, NextCloud Chat.
- Develop your relationships remotely: virtual cafés, cross-country projects, peer reviews between geographic areas, all these solutions form a solid basis for asynchronous collaboration.

I cannot recommend GitLab's work on the subject highly enough.  Gitlab has thoroughly developed its All-Remote strategy and, as they apply their principles well, everything is documented on "GitLab's Guide to All-Remote"

The training provided by GitLab is excellent.  This requires practice and returning to it regularly to refocus on its application.

|  Training |  Content |
|  ------------- |  ------------- |
|  [Remote Team Management](https://www.coursera.org/learn/remote-team-management#modules)|  Leading in a Remote Environment, Building a Remote Organizational Culture and Practices, Assessing Teams' and Managers' Readiness for Remote Work, Creating a Baseline Strategy for Implementing a Remote Transformation |
|  [TeamOps](https://about.gitlab.com/teamops/) |  Focuses on finding solutions to the following challenges: Delays in decision making, Meeting fatigue, Poor internal communication, Slow transfers and delays in work flow Cell |

## Free software in the professional world

My experience in the open source world has also led me to apply these principles in my professional work.  I developed an open source framework within my company, which is accessible to all employees.  Knowledge sharing, comprehensive documentation and open access to information are key elements of this approach.  This promotes transparency, innovation and collaboration, while removing barriers to communication within the company.

“Open source within companies helps create an innovation ecosystem where each individual can contribute to the improvement of processes and the growth of the company.  » - [Quote from Eric S. Raymond, open source thinker]

## The example of Arch Linux: a strong community

My transition to Arch Linux allowed me to fully experience the power of the open source community.  Arch Linux is not only a Linux distribution, but also an active and dedicated community.  Users and developers collaborate to maintain a robust and flexible operating system.

“Open source is not just about sharing code, but about sharing knowledge, skills and building lasting relationships in a strong community.  » - [Quote from Linus Torvalds]

Benefits of Open Collaboration and the Power of Community

Open collaboration and the strength of the community open the door to multiple advantages:
- Collective Innovation: The diversity of contributors and perspectives stimulates constant innovation.
- Knowledge Sharing: Open source promotes knowledge sharing, encouraging continuous learning.
- Transparency and Trust: Open collaboration builds trust and transparency within the community.
- Flexibility and Agility: Asynchronous and decentralized collaboration allows greater flexibility in work.

## Open-Source Contributions

Interaction with the open source community is an essential component of my approach.  What makes this interaction even more enriching is that it is bi-directional.  Indeed, just as the open source community provides me with exceptional tools and solutions, I strive to contribute to this same community, to the extent of my skills and means, in order to give back.

The ways to participate in the free software community are varied, and everyone can find their own way to contribute.  Contributions can take many forms:
- Bug reporting
- Suggestions for improvements or new features
- Code writing
- Review of the participations of other contributors,
- Translation
- Presentation
- Pedagogy (Videos, Articles, participation in associations)
- Support via forums, reddit, discord channels

Personally, I actively engage in several open source projects, depending on my skills and interests.  My contributions include reporting bugs and proposing improvements for solutions such as OPNsense and NextCloud.  I also contributed by creating YAML descriptors for TrueNAS, doing translations for Arch Linux and Cardiac's [Architect](https://github.com/Cardiacman13/Architect) project, as well as working on the implementation in good shape to develop the Architect project, which aims to simplify the use of Arch Linux for desktop users.

During the year 2023, I have modestly made around 200 contributions to these different open source projects.  My involvement in the free software community is a way of thanking and supporting the developers and contributors who have enabled the creation of the tools I rely on every day.  It is also a way of participating in the continuous improvement of this software and of giving back to the community what it has offered me in terms of freedom, transparency, and reliability.

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/GitHub%20contribs.PNG" width="1000" height="301">

#VII.  Let's spread the message!  <a name="message"/>

My commitment to open source is not limited to personal or professional use, it goes well beyond.  This is a deep conviction that I hold with passion, and one of my missions is to inform, share and educate around the benefits of open source and the philosophy that accompanies it.

## 📖 Information instead of conversion 
It is essential to clarify that my objective is not to convert, but above all to inform.  I believe that open source is an approach that deserves to be better understood and appreciated.  That's why I strive to share information, explain the benefits, and shed light on the philosophy behind this approach.  I want everyone to be able to make informed decisions when it comes to technology.

## 🐧 The Open Source Community 
The open source community is one of the jewels of this approach.  It is made up of passionate, curious and welcoming people, ready to share their knowledge and welcome new people every day.  This vibrant community is an invaluable source of knowledge and inspiration.  It embodies the values ​​of open source, such as collaboration, transparency and generosity.

## 🧠 More than a question of tools 
Open source is not only a question of technical or technological tools, it is also a question of state of mind.  This encompasses transparency, a taste for transmission and sharing of knowledge.  I believe that open source is an invitation to continuous learning, collaborative creation and constant improvement.

## 👨‍👨‍👧‍👦 Education for kids 
One of my priorities is to inform young people about the dark side of social networks and to make them aware of the importance of being careful online.  I strive to transmit values ​​of vigilance, not to expose oneself too much on the Internet and not to share anything too important.  These fundamental lessons are essential to protecting privacy and digital security.  My own children are the primary beneficiaries, and it's gratifying to see them understand the importance of these messages in their own way, like the simple "It's cool Linux" uttered by my oldest.

LinkedIn as a Vector of Communication: LinkedIn, the professional platform, also plays a key role in my approach to evangelizing open source.  It's a space where I can interact with enthusiasts, remembrancers and Linuxians from all walks of life.  I observe with satisfaction the growth of this community day after day.  It is an ideal vector for communicating and informing.  I am aware that my job requires a certain reserve, but I believe that curiosity has never hurt anyone.  Sharing knowledge and encouraging constructive discussions about open source helps broaden horizons and promote more informed use of technology.

Ultimately, open source evangelism is a mission close to my heart.  It is a way of contributing to the dissemination of essential values ​​such as freedom, transparency and collaboration, and of ensuring that open source finds its place in a constantly evolving digital world.

# VIII.  This is not a conclusion <a name="continue"/>

This article was an opportunity to share my journey towards exclusively using open source tools and taking a deep approach to open source in my daily life.  It is essential to remember that my approach and this article are above all informative.  I'm not here to impose dogma, but to encourage thought and discussion about the benefits of open source, transparency, and the philosophy behind them.

My journey has given me a deeper understanding of open source and its benefits.  It’s a process that can be rewarding, even if it doesn’t require as profound a transformation as mine.  Applying some key concepts of open source philosophy in your daily life can be an interesting experience.  If you're used to silos, lack of information, and a "one-size-fits-all" approach, experience transparency.  You will be surprised how your loved ones, peers and colleagues can return it to you.

There are many ways to get involved in the world of open source, whether through QA (quality assurance), translation, sharing experiences, sharing discoveries, testing, failures, feedback, collaboration on projects or innovation alone or in a group.  In recent years, I have enjoyed contributing to the projects and tools I use on a daily basis.  This manifests itself through bug reports, translations, or even my active participation in projects such as "Architect", which aims to make Arch Linux more user-friendly for a full desktop experience.

If you're interested in a transformation of this magnitude, keep in mind that the learning curve can be steep at first.  However, with perseverance, it becomes smoother and smoother as you progress.  Today, I continue to learn, but maintaining my open source environment requires little time.  This journey to open source is an invitation to continuous learning, innovation and collaboration.  It’s a journey that can bring both personal and professional benefits, and I encourage you to discover it in your own way.  The open source philosophy is an invaluable resource, and it is within reach of anyone who wishes to embark on this rewarding path.

#IX.  Questions/Answers <a name="q&a"/>

Do not hesitate to ask me questions in the form of Issues on GitHub or Reddit, I would be happy to answer them and publish our discussions in this article.

# X. My progress <a name="progress"/>

- [x] Use an open-source web browser
- [x] Use a privacy-conscious search engine
- [x] Use a Privacy-Concerned Email Service
- [x] Control my data by hosting my own NAS server
- [x] Have password hygiene and host them on my infrastructure
- [x] Take back control of my contact list and calendar
- [x] Establish a reliable and secure network
- [ ] Ensuring ecological impact via a greenLabing approach - In progress
- [x] Switch my main PC to Linux
- [x] Host my VPN to ensure a secure connection when I'm traveling/on vacation
- [ ] Use free applications on my mobile - In progress
- [ ] Lists my uses and services on the Internet, find free alternatives - Not started
































# IV. Systèmes d'exploitation Open Source <a name="os"/>

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/bureau.png" width="1000" height="250">

L'une des étapes les plus marquantes de mon voyage vers l'utilisation exclusive d'outils open source a été mon passage à un système d'exploitation open source pour mon poste de travail. Ce changement s'est produit grâce à un déclic, une révélation qui est venue sous la forme d'un appareil de jeu : le [Steam Deck](https://www.steamdeck.com/fr), une console de jeu portative basée sur Arch Linux.

En tant que passionné de jeux vidéo, j'ai été impressionné par l'engagement de la société [Valve](https://fr.wikipedia.org/wiki/Valve_(entreprise)) pour rendre compatible un nombre impressionnant de jeux, à l'origine prévus pour Windows, avec Linux. Cette démarche audacieuse a attiré mon attention et a suscité ma curiosité.

C'est ainsi que j'ai ressenti le désir d'en apprendre davantage sur ce système d'exploitation, de plonger dans le monde de Linux, et de voir s'il pouvait répondre à mes besoins au-delà du jeu. Mon parcours m'a naturellement conduit à rejoindre la communauté [Gaming Linux FR](https://www.gaminglinux.fr/), où j'ai pu trouver de l'aide et des conseils pour faciliter ma transition de Windows à Linux.

Ce qui m'a le plus marqué dans cette expérience, c'est l'ouverture d'esprit, la volonté de partage et le dévouement de la communauté open source à aider le plus grand nombre à opérer cette transition. J'ai rapidement réalisé que la philosophie de l'open source était ancrée dans l'ADN de cette communauté. Chacun était prêt à partager ses connaissances, à résoudre des problèmes et à faire en sorte que Linux devienne accessible à tous.

Après avoir testé différentes distributions Linux, notamment Debian, Fedora et OpenSUSE, j'ai finalement trouvé mon point de chute avec [Arch Linux](https://archlinux.org/). Ce système d'exploitation open source correspondait à 100% à mes besoins. Il m'offrait la flexibilité et la personnalisation dont j'avais besoin pour adapter mon environnement de travail à mes préférences.

Vous voulez un panorama des distributions existantes,la référence reste [DistroWatch](https://distrowatch.com/) !
Vous voulez essayer les distributions sans pour autant les installer (ni même booter sur une ISO Live) [DistroSea](https://distrosea.com/) vous permettra de tester dans une VM au sein de votre navigateur :)

Avec Arch Linux, j'ai pu travailler efficacement en utilisant uniquement des applications open source, tout en conservant certaines [*Progressive Web Apps*](https://fr.wikipedia.org/wiki/Progressive_web_app) des applications Microsoft qui s'avéraient incontournables. Cette transition m'a montré que l'open source n'était pas seulement une option viable, mais qu'il pouvait également répondre à tous les besoins, qu'il s'agisse de productivité, de divertissement ou de tout autre aspect de la vie numérique.

Mon aventure avec Arch Linux a renforcé ma conviction que l'open source est bien plus qu'une alternative aux logiciels propriétaires. C'est une communauté ouverte, collaborative et dévouée, prête à accompagner les utilisateurs dans leur exploration d'un avenir numérique plus libre et transparent.

J'ai assisté avec beaucoup d'intérêt à l'[Interview d'un packager Arch Linux](https://www.youtube.com/watch?v=qXvzGRm9iFs) où j'ai pu me faire une idée plus précise du soin aporté par la communauté à livrer une expérience satisfaisante à ses utilisateurs et minimisant les instabilités et autres bugs.

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/Desktop.png" width="1000" height="562">


## Performances de Jeu au Top

| CyberPunk 2077  | CS:GO | Forza Horizon 5 |
| ------------- | ------------- | ------------- |
| <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/Screenshot_20231030_122544.png" width="320" height="177"> | <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/Screenshot_20231030_122613.png" width="320" height="177"> | <img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/Screenshot_20231030_122639.png" width="320" height="177"> |


# V. L'Open Collaboration et la Puissance de la Communauté <a name="collab"/>

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/community.png" width="1000" height="250">

L'un des aspects les plus inspirants de mon voyage vers l'utilisation exclusive d'outils open source est la découverte de l'open collaboration et de la formidable puissance de la communauté qui l'accompagne. Dans ce chapitre, nous explorerons les avantages de l'open collaboration, de l'innovation collective et de la solidité de la communauté, en mettant en lumière les principes de cette approche.

Les Fondements de l'Open Collaboration

L'open collaboration est une philosophie qui repose sur le partage, la coopération et l'ouverture. Elle favorise la collaboration entre individus et groupes de manière transparente, libre et souvent décentralisée. Cette approche a des implications profondes, non seulement dans le monde de l'open source, mais aussi dans le monde professionnel.

## La collaboration décentralisée et la richesse des perspectives multiculturelles

L'un des aspects les plus stimulants de l'open collaboration est la possibilité de travailler avec des personnes de divers pays, de cultures et de langues différentes. En tant qu'adepte de cette philosophie, j'ai eu l'opportunité de collaborer avec des individus de partout dans le monde, en utilisant des langues que je maîtrise telles que le français, l'anglais et l'espagnol. Cette diversité culturelle apporte une richesse infinie de points de vue, d'expériences et d'expertises. Elle renforce l'idée que l'innovation naît de la diversité.

« La collaboration, c'est l'occasion de découvrir de nouvelles perspectives, de repousser les limites de la créativité et d'enrichir nos idées grâce à la diversité des contributeurs. » - [Citation de Linus Torvalds, créateur de Linux]

## Le pouvoir de la collaboration asynchrone

L'un des atouts clés de l'open collaboration est la flexibilité qu'elle offre grâce au travail asynchrone. Travailler avec des individus répartis sur différentes zones horaires signifie que la collaboration peut se poursuivre 24 heures sur 24. Les contributions peuvent se faire en fonction des disponibilités de chacun, créant une dynamique de travail continue. Cela permet de tirer pleinement parti des talents disponibles, indépendamment de la localisation géographique.

Quelques formations existent et sont très enrichissantes. Je les ai suivi et essaye d'intégrer les concepts clés dans mon quotidien.
- Limiter l'utilisation des emails et favoriser l'utilisation d'un référentiel unique pour écrire, documenter et intérragir. Il s'agit d'une "single source of truth" qui facilite l'information, l'onboarding et évite de se disperser.
- Utiliser des chats persistants pour que quelque soit la zone géographique d'un individu, il puisse prendre connaissance des échanges durant ses heures de travail. De nombreux outils existent : Discord, Teams, Slack, NextCloud Chat.
- Développer son relationel à distance : les cafés virtuels, les projets cross-countries, les peer reviews entre zone géographiques, toutes ces solutions forment une base solide à la collaboration asynchrone.

Je ne saurais que trop conseiller le travail de GitLab sur le sujet. Gitlab a développé à fond sa stratégie All-Remote et, comme ils appliquent bien leurs principes, tout est documenté sur le ["*GitLab's Guide to All-Remote*https://handbook.gitlab.com/handbook/company/culture/all-remote/guide/)

Les formations dispensées par GitLab sont excellentes. Cela demande de la mise en pratique et d'y revenir régulièrement pour se recentrer sur son application

| Formation  | Contenu |
| ------------- | ------------- |
| [Remote Team Management](https://www.coursera.org/learn/remote-team-management#modules)| Diriger dans un environnement distant, Instaurer une culture et des pratiques organisationnelles à distance, Évaluer l'état de préparation des équipes et des responsables au travail à distance, Créer une stratégie de base pour la mise en œuvre d'une transformation à distance   |
| [TeamOps](https://about.gitlab.com/teamops/) | Se concentre sur trouver des solutions aux challenges suivants : les Retards dans la prise de décision, Fatigue des réunions, Mauvaise communication interne, Lenteur des transferts et retards dans le déroulement du travail Cell  |


## Le libre dans le monde professionnel

Mon expérience dans le monde de l'open source m'a également conduit à appliquer ces principes dans mon travail professionnel. J'ai développé un framework open source au sein de mon entreprise, qui est accessible à tous les employés. Le partage des connaissances, la documentation exhaustive et l'accès ouvert à l'information sont des éléments clés de cette approche. Cela favorise la transparence, l'innovation et la collaboration, tout en éliminant les barrières à la communication au sein de l'entreprise.

« L'open source au sein des entreprises permet de créer un écosystème d'innovation où chaque individu peut contribuer à l'amélioration des processus et à la croissance de l'entreprise. » - [Citation d'Eric S. Raymond, penseur de l'open source]

## L'exemple d'Arch Linux : une communauté Solide

Ma transition vers Arch Linux m'a permis de vivre pleinement la force de la communauté open source. Arch Linux est non seulement une distribution Linux, mais aussi une communauté active et dédiée. Les utilisateurs et les développeurs collaborent pour maintenir un système d'exploitation robuste et flexible.

« L'open source ne consiste pas seulement à partager du code, mais à partager des connaissances, des compétences et à construire des relations durables dans une communauté solide. » - [Citation de Linus Torvalds]

Avantages de l'Open Collaboration et de la Puissance de la Communauté

L'open collaboration et la solidité de la communauté ouvrent la porte à de multiples avantages :
- Innovation Collective : La diversité des contributeurs et des perspectives stimule l'innovation constante.
- Partage de Connaissances : L'open source favorise le partage des connaissances, encourageant l'apprentissage continu.
- Transparence et Confiance : La collaboration ouverte construit la confiance et la transparence au sein de la communauté.
- Flexibilité et Agilité : La collaboration asynchrone et décentralisée permet une plus grande flexibilité dans le travail.

## Contributions Open-Source

L'interaction avec la communauté open source est une composante essentielle de ma démarche. Ce qui rend cette interaction d'autant plus enrichissante, c'est qu'elle est bi-directionnelle. En effet, tout comme la communauté open source me fournit des outils et des solutions exceptionnelles, je m'efforce de contribuer à cette même communauté, dans la mesure de mes compétences et de mes moyens, afin de donner en retour.

Les façons de participer à la communauté du logiciel libre sont variées, et chacun peut trouver sa propre manière de contribuer. Les contributions peuvent prendre de nombreuses formes :
- Signalement de bogues
- Suggestions d'améliorations ou nouvelles fonctionnalités
- Rédaction de code
- Revue des participations des autres contributeurs,
- Traduction
- Présentation
- La  pédagogie (Vidéos, Articles, participations à des associations)
- L'entraide via les forums, reddit, les channels discord

Personnellement, je m'engage activement dans plusieurs projets open source, en fonction de mes compétences et de mes centres d'intérêt. Mes contributions incluent le signalement de bogues et la proposition d'améliorations pour des solutions telles qu'OPNsense et NextCloud. J'ai également contribué en créant des descripteurs YAML pour TrueNAS, en effectuant des traductions pour Arch Linux et le projet [Architect](https://github.com/Cardiacman13/Architect) de Cardiac, ainsi qu'en travaillant sur la mise en forme pour développer le projet Architect, qui vise à simplifier l'utilisation d'Arch Linux pour les utilisateurs desktop.

Au cours de l'année 2023, j'ai modestement réalisé environ 200 contributions à ces différents projets open source. Mon engagement dans la communauté du logiciel libre est une manière de remercier et de soutenir les développeurs et les contributeurs qui ont permis la création des outils sur lesquels je compte au quotidien. C'est aussi une façon de participer à l'amélioration continue de ces logiciels et de rendre à la communauté ce qu'elle m'a offert en termes de liberté, de transparence, et de fiabilité.

<img src="https://github.com/T13nou/Open-Source-Odyssey/blob/main/pictures/GitHub%20contribs.PNG" width="1000" height="301">

# VII. Passons le message ! <a name="message"/>

Mon engagement en faveur de l'open source ne se limite pas à une utilisation personnelle ou professionnelle, il va bien au-delà. Il s'agit d'une conviction profonde que je porte avec passion, et l'une de mes missions est d'informer, partager et éduquer autour des avantages de l'open source et de la philosophie qui l'accompagne.

## 📖 Informations au lieu de conversion 
Il est essentiel de préciser que mon objectif n'est pas de convertir, mais avant tout d'informer. Je crois que l'open source est une approche qui mérite d'être mieux comprise et appréciée. C'est pourquoi je m'efforce de partager des informations, d'expliquer les avantages, et de mettre en lumière la philosophie qui sous-tend cette démarche. Je souhaite que chacun puisse prendre des décisions éclairées en matière de technologie.

## 🐧 La Communauté Open Source 
La communauté open source est l'un des joyaux de cette approche. Elle est composée de personnes passionnées, curieuses et accueillantes, prêtes à partager leurs connaissances et à accueillir de nouveaux venus chaque jour. Cette communauté dynamique est une source inestimable de connaissances et d'inspiration. Elle incarne les valeurs de l'open source, telles que la collaboration, la transparence et la générosité.

## 🧠 Plus qu'une question d'outils 
L'open source n'est pas uniquement une question d'outils techniques ou technologiques, c'est aussi une question d'état  d'esprit. Cela englobe la transparence, le goût de la transmission et le partage des connaissances. J'estime que l'open source est une invitation à l'apprentissage continu, à la création collaborative et à l'amélioration constante.

## 👨‍👨‍👧‍👦 De la pédagogie pour les kids 
L'une de mes priorités est d'informer les plus jeunes sur le côté sombre des réseaux sociaux et de les sensibiliser à l'importance de la prudence en ligne. Je m'efforce de transmettre des valeurs de vigilance, de ne pas trop s'exposer sur Internet et de ne rien partager de trop important. Ces leçons fondamentales sont essentielles pour protéger la vie privée et la sécurité numérique. Mes propres enfants en sont les premiers bénéficiaires, et il est gratifiant de les voir comprendre l'importance de ces messages à leur manière, comme le simple "C'est cool Linux" prononcé par mon plus grand.

LinkedIn comme Vecteur de Communication : LinkedIn, la plateforme professionnelle, joue également un rôle clé dans ma démarche d'évangélisation de l'open source. C'est un espace où je peux interagir avec des convaincus, des souvenairistes et des Linuxiens de tous horizons. J'observe avec satisfaction la croissance de cette communauté jour après jour. C'est un vecteur idéal pour communiquer et informer. Je suis conscient que mon métier impose une certaine réserve, mais je considère que la curiosité n'a jamais fait de mal à personne. Partager des connaissances et encourager les discussions constructives sur l'open source est une démarche qui contribue à élargir les horizons et à promouvoir une utilisation plus éclairée de la technologie.

En fin de compte, l'évangélisation de l'open source est une mission qui me tient à cœur. C'est une façon de contribuer à la diffusion de valeurs essentielles telles que la liberté, la transparence et la collaboration, et de s'assurer que l'open source trouve sa place dans un monde numérique en constante évolution.

# VIII. Ceci n'est pas une conclusion <a name="continue"/>

Cet article a été une opportunité de partager mon voyage vers une utilisation exclusive d'outils open source et une approche profonde de l'open source dans ma vie quotidienne. Il est essentiel de rappeler que mon approche et cet article sont avant tout informatifs. Je ne suis pas ici pour imposer un dogme, mais pour encourager la réflexion et la discussion sur les avantages de l'open source, de la transparence et de la philosophie qui les sous-tendent.

Mon parcours m'a apporté une compréhension plus profonde de l'open source et de ses avantages. C'est une démarche qui peut être gratifiante, même si elle ne nécessite pas une transformation aussi profonde que la mienne. Appliquer quelques concepts clés de la philosophie open source dans sa vie quotidienne peut être une expérience intéressante. Si vous êtes habitués aux silos, au manque d'information, et à l'approche du "pré carré", faites l'expérience de la transparence. Vous serez surpris de la manière dont vos proches, pairs et collègues peuvent vous le rendre.

Il existe de nombreuses façons de s'impliquer dans le monde de l'open source, que ce soit par la QA (assurance qualité), la traduction, le partage d'expériences, le partage de découvertes, les tests, les échecs, les retours d'expérience, la collaboration sur des projets ou l'innovation en solitaire ou en groupe. Ces dernières années, j'ai pris plaisir à contribuer aux projets et aux outils que j'utilise au quotidien. Cela se manifeste par des rapports de bugs, des traductions, ou même par ma participation active à des projets tels qu'"Architect", qui vise à rendre Arch Linux plus convivial pour une expérience de bureau complète.

Si une transformation de cette ampleur vous intéresse, gardez à l'esprit que la courbe d'apprentissage peut être abrupte au début. Cependant, avec persévérance, elle devient de plus en plus douce au fur et à mesure de votre progression. Aujourd'hui, je continue d'apprendre, mais la maintenance de mon environnement open source nécessite peu de temps. Ce voyage vers l'open source est une invitation à l'apprentissage continu, à l'innovation et à la collaboration. C'est un voyage qui peut apporter des avantages tant personnels que professionnels, et je vous encourage à le découvrir à votre manière. La philosophie open source est une ressource inestimable, et elle est à la portée de tous ceux qui souhaitent s'engager sur cette voie enrichissante.

Pour ma part, dans une logique d'aprentissage et d'innovation continue, l'aventure continue et vos commentaires sont les bienvenus pour faire progresser ce petit monde 🤟

# IX. Questions/Réponses <a name="q&a"/>

N'hésitez pas à me poser des questions sous formes d'Issues sur GitHub ou Reddit, je me ferais un plaisir d'y répondre et de publier nos échanges au sein de cet article.

# X. Ma progression <a name="progress"/>

- [x] Utiliser un navigateur web open-source
- [x] Utiliser un moteur de recherche soucieux de la vie privée
- [x] Utiliser un Service Mail Soucieux de la Vie Privée
- [x] Maîtriser mes données en hébergeant mon propre serveur NAS
- [x] Avoir une hygiène de mots de passe et héberger ceux-ci sur mon infrastructure
- [x] Reprendre le contrôle de ma liste de contacts et de mon calendrier
- [x] Mettre en place un réseau fiable et sécurisé
- [ ] Veiller à l'impact écologique via une approche de greenLabing - En cours
- [x] Basculer mon PC principal sous Linux
- [x] Héberger mon VPN pour assurer une connexion sécurisée lorsque je suis en déplacement/vacances
- [ ] Utiliser des applications libres sur mon mobile - En cours
- [ ] Listes mes usages et services sur Internet, trouver des alternatives libres - Pas démarré

