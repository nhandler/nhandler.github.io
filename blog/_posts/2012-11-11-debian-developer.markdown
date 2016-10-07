---
layout:     post
title:      "Debian Developer"
published:  true
date:       2012-11-11
categories: ["planet-debian", "planet-ubuntu"]
tags:       ["Debian Developer"]
---

Today, I officially got approved by the Debian Account Managers as a Debian Developer (still waiting on keyring-maint and DSA). Over the years, I have seen many people complain about the New Member Process. The most common complaint was with regards to the (usually) long amount of time the process can take to complete. I am writing this blog post to provide one more perspective on this process. Hopefully, it will prove useful to people considering starting the New Member Process.

The most difficult part about the New Member Process for me had to do with getting my GPG key signed by Debian Developers. I have not been able to attend any large conferences, which are great places to get your key signed. I also have not been able to meet up with the few Debian Developers living in/around Chicago. As a result, I was forced to patiently wait to start the NM process. This waiting period lasted a couple of years. It wasn't until this October, at the [Association for Computing Machinery at Urbana-Champaign's Reflections | Projections Conference], that this changed. [Stefano Zacchiroli][2] was present to give a [talk][3] about Debian. [Asheesh Laroia][4] was also present to lead an [OpenHatch Workshop][5] about contributing to open source projects. Both of these Developers were more than willing to sign my key when I asked. If you look at my [key][6], you will see that these signatures were made on October 7 and October 9, 2012.

With the signatures out of the way, the next step in the process was to actually apply. Since I did not already have an account in the system, I had to send an email to the Front Desk and have them enter my information into the system. Details on this step, along with a sample email are available [here][7].

Once I was in the system, the next step was to get some Debian Developers to serve as my advocates. Advocates should be Debian Developers you have worked closely with, and usually include your sponsor(s). If these people believe you are ready to become a Debian Developer, they write a message describing the work you have been doing with them and why they feel you are ready. [Paul Tagliamonte][8] had helped review and sponsor a number of my uploads. I had been working with him for a number of years, and he really helped encourage and help me to reach this milestone. He served as my first advocate. [Gregor Herrmann][9] is responsible for getting me started in contributing to Debian. When I first tried to get involved, I had a hard time finding sponsors for my uploads and bugs to work on. Eventually, I discovered the [Debian Perl Group][10]. This team collectively maintains most of the Perl modules that are included in the Debian repositories. Gregor and the other Debian Developers on the team were really good about reviewing and sponsoring uploads in a very timely manner. This allowed me to learn quickly and make a number of contributions to Debian. He served as my second advocate.

With my advocations taken care of, the next step in the process was for the Front Desk to assign me an Application Manager and for the Application Manager to accept the appointment. [Thijs Kinkhorst][11] was appointed as my Application Manager. He also agreed to take on this task. For those of you who might not know, the Application Manager is in charge of asking the applicant questions, collecting information, and ultimately making a recommendation to the Debian Account Managers about whether or not they should accept the applicant as a Developer. They can go about this in a variety of ways, but most choose to utilize a set of [template questions][12] that are adjusted slightly on a per-applicant basis.

Remember that period of waiting to get my GPG key signed? I had used that time to go through and prepare answers to most of the template questions. This served two purposes. First, it allowed me to prove to myself that I had the knowledge to become a Debian Developer. Second, it helped to greatly speed up the New Member process once I actually applied. There were some questions that were added/removed/modified, but by answering the template questions befrehoand, I had become quite familiar with documents such as the [Debian Policy][13] and the [Debian Developer's Rerference][14]. These documents are the basis for almost all questions that are asked. After several rounds of questions, testing my knowledge of Debian's philosophy and procedures as well as my technical knowledge and skills, some of my uploads were reviewed. This is a pretty standard step. Be prepared to explain any changes you made (or chose not to make) in your uploads. If you have any outstanding bugs or issues with your packages, you might also be asked to resolve them. Eventually, once your Application Manager has collected enough information to ensure you are capable of becoming a Debian Developer, they will send their recommendation and a brief biography about you to the [debian-newmaint mailing list][15] and forward all information and emails from you to the Debian Account Managers (after the Front Desk checks and confirms that all of the important information is present).

The Debian Account Managers have the actual authority to approve new Debian Developers. They will review all information sent to them and reach their own decision. If they approve your application, they will submit requests for your GPG key to be added to the [Debian Keyring][16] and for an account to be created for you in the Debian systems. At this point, the New Member process is complete. For me, it took exactly 1 month from the time I officially applied to become a Debian Developer until the time of my application being approved by the Debian Account Managers. Hopefully, it will not be long until my GPG key is added to the keyring and my account is created. I feel the entire process went by very quickly and was pain-free. Hopefully, this blog post will help to encourage more people to apply to become Debian Developers.

[1]: http://www.acm.uiuc.edu/conference/2012/index.php
[2]: http://upsilon.cc/~zack/
[3]: http://youtu.be/huAREHKaUDE
[4]: http://www.asheesh.org/
[5]: http://openhatch.org/
[6]: http://keyserver.ubuntu.com:11371/pks/lookup?search=0x0A75C877&fingerprint=on&op=vindex
[7]: https://nm.debian.org/public/newnm
[8]: http://pault.ag/
[9]: http://info.comodo.priv.at/
[10]: http://pkg-perl.alioth.debian.org/
[11]: http://thijs.kinkhorst.nl/
[12]: http://anonscm.debian.org/viewvc/nm/trunk/nm-templates/
[13]: http://www.debian.org/doc/debian-policy/
[14]: http://www.debian.org/doc/manuals/developers-reference/
[15]: http://lists.debian.org/debian-newmaint/2012/11/msg00000.html
[16]: http://keyring.debian.org/
