---
type: periodical
layout: periodical_old
title: "Revuo Periodical #4"
date: "2020-01-29T11:07:56-07:00"
issuenumber: 4
covering: "July 1 - December 31, 2019"
---

<h3>Table of Contents:</h3>
<ul class="contents">
    <li><a href="#welcome">Welcome</a></li>
    <li><a href="#coreteamupdate">Core Team & Structural Updates</a></li>
    <li><a href="#development">Development Update</a></li>
    <li><a href="#mrl">Monero Research Lab Update</a></li>
    <li><a href="#community">Community Update</a></li>
    <li><a href="#translations">Monero Outreach & Monero Localization Update</a></li>
    <li><a href="#mobile">Third-Party Apps & Services Update</a></li>
    <li><a href="#donate">Donate</a></li>
</ul>

<h3 id="welcome">Welcome</h3>

<p>Hello everyone and welcome to the fourth Monero periodical. In this issue we summarize the major developments of Monero from July 1st to December 31st of 2019. It’s been another amazing half year, and we feel it’s important to celebrate our accomplishments as a community. So without further ado...</p>

<h3 id="coreteamupdate">Core Team & Structural Updates</h3>

<p>First and foremost, we’d like to start this issue with the significant updates to some of Monero’s internal community structures outlined in a post on the <a href="https://web.getmonero.org/" target="_blank">getmonero.org</a> website on December 16, 2019.</p>

<p>The highlights of the post include fluffypony stepping down as lead maintainer of the Monero CLI software. He is replaced by Monero community member Snipa, though fluffypony will continue to be a backup maintainer. As well fluffypony is also stepping down as primary software builder and signer, replaced by various community members for different software. Lastly, there are some minor adjustments to who controls and has access to things like website and download servers as well as the General Fund. <a href="https://web.getmonero.org/2019/12/16/technical-responsibilities-update.html" target="_blank">Anyone is free to read the post for more details</a>.</p>

<h3 id="development">Development Update</h3>

<h5>Protocol Upgrade</h5>

<p>On November 30th, Monero successfully had its scheduled hard fork.</p>

<p>One of the most important features of the v0.15 is the implementation of the RandomX PoW algorithm. Mainly designed to eliminate the efficiency advantage of ASIC miners over consumer grade hardware, this new feature is set to keep processor mining more competitive. Accordingly, it ensures a better decentralization of the Monero network.</p>

<p>The Carbon Chamaeleon release also phased out long payment IDs, which helps to increase privacy and improve user experience. As a result, it drastically minimizes support tasks related to trading platforms and other services.</p>

<p>Last but not least is the protocol enforcement set to improve privacy for the users and the Monero network. Since the update, there is a requirement for a minimum of two outputs for transactions and ten-block lock time for incoming transactions.</p>

<h5>GUI Update</h5>

<p>The Monero GUI (Graphical User Interface) has undergone several changes and improvements over the second half-year period.</p>

<p>Picking up on the goal to make the Monero software as user-friendly as possible, the v0.15.0.0 release of the GUI offers more user-friendliness and performance improvement features. This is achieved all thanks to the hard work of volunteers and contributors.</p>

<p>Below are the major changes that were made over the past few months:</p>

<ul>
    <li>Tails: Better support and blank screen on startup fix;</li>
    <li>Trezor: Address is now shown on Trezor devices, and support on Linux fix;</li>
    <li>The Transaction History page was improved;</li>
    <li>Introduction of a Titlebar: wallet name and new icons;</li>
    <li>Introduction of a SimpleMode: automatic public nodes discovering and switching;</li>
    <li>The left panel and the sidebar menu have a new design;</li>
    <li>New blur background effect;</li>
    <li>Basic right-click context menu;</li>
    <li>Fix update notification hash;</li>
    <li>Persistent subaddress account selection;</li>
    <li>Various UI/UX improvements;</li>
    <li>Bug fixes, crash fixes, and performance improvements.</li>
</ul>

<h3 id="mrl">Monero Research Lab Update</h3>

<p>Since its creation, the Monero Research Lab has been contributing not only to Monero but the largest cryptography sphere and blockchain technology.</p>

<p>The MRL team constantly pushes the limits of transactions' confidentiality and security to keep Monero at the forefront of truly private, fungible and untraceable digital transactions.</p>

<p>In this section, we will take a look at the innovative research conducted by the MRL for the betterment of Monero and its privacy features.</p>

<h5>Triptych</h5>

<p>The MRL has been working on Triptych, a new linkable ring signature, based on earlier work by Groth and Kohlweiss and Bootle et al.</p>

<p>The preprint published on January 6th, 2020, laid down important theoretical foundations for enhancing Monero’s privacy and scalability.</p>

<p>The new scheme proposes a trustless logarithmic-size ring signature as an alternative to the current <a href="https://eprint.iacr.org/2015/1098" target="_blank">MLSAG</a> (Multilayer Linkable Spontaneous Anonymous Group Signatures) system.</p>

<p>The main innovation of Triptych is that the byte size of the ring signature could be scaled logarithmically with the number of decoys, rather than linearly, whereas the verification time remains linear. This would allow Monero's ring size to increase significantly without major performance problems. Thus, a transaction using a 512-ring would be processed in an average verification time of 45 milliseconds (including range proof-verification).</p>

<p>This represents a breakthrough compared to competitive solutions of the same type, which take an average of 100 milliseconds to process a transaction using a 128-ring.</p>

<p>The technology is still in the research phase. Other solutions are currently being considered by the Monero Research Lab, including <a href="https://eprint.iacr.org/2019/508" target="_blank">RingCT 3.0</a>, <a href="https://eprint.iacr.org/2019/654" target="_blank">CLSAG</a> , <a href="https://lelantus.io/lelantus.pdf" target="_blank">Lelantus</a> and <a href="https://eprint.iacr.org/2019/580.pdf" target="_blank">Omniring</a>.</p>

<h3 id="community">Community Update</h3>

<p>People from all around the world join their efforts and work relentlessly for the betterment of the Monero Project. In this section, we will focus on some of the projects and initiatives taken by the Monero community.</p> 

<table class="hted-head">
  <tbody><tr class="row1">
    <th>Monero Adoption</th>
  </tr>
</tbody></table>

<p>During the last half of 2019, Monero has been growing even more in popularity as a payment method. Several wallets, exchanges, businesses, and merchants now accept Monero. Below is a non-comprehensive list of related news:</p>

<h5>Wallets</h5>

<ul>
    <li>Exodus has added Monero to its mobile wallet. Furthermore, they put out a support page for Monero’s unique features, including its different key types.</li>
    <li>Abra Wallet now supports Monero withdraws via an exchange.</li>
    <li>Magnum Wallet has added support for Monero.</li>
    <li>Ownbit (BitBill) added Android support for Monero.</li>
</ul>

<h5>Exchanges</h5>

<ul>
    <li>VCC Exchange has listed Monero.</li>
    <li>BTSE has launched futures trading for Monero, and KYC-free XMR spot trading.</li>
    <li>Binance adds Monero to Binance Lending Products.</li>
    <li>FixedFloat has listed Monero.</li>
</ul>

<h5>Businesses/Other</h5>

<ul>
    <li>Travala partnered with Booking for a Crypto Travel Option. Monero is accepted.</li>
    <li>Virtual Private Server host BitVPS now accepts Monero.</li>
    <li>The Linux Mint Project now accepts Monero for donations.</li>
    <li>Bity added a new ATM supporting Monero in Basel, Switzerland.</li>
</ul>

<table class="hted-head">
  <tbody><tr class="row1">
    <th>Monero Ecosystem</th>
  </tr>
</tbody></table>

<p>The Monero Ecosystem’s goal is to gather all the community members’ relevant repositories in one place. Accordingly, finding useful Monero related projects, documents, resources, and tools have never been easier.</p>

<p>Below is a sample of the projects that joined the Monero Ecosystem in the past six months:</p>

<ul>
    <li><a href="https://xmrnotify.com/" target="_blank">MoneroNotify</a>: u/Monerobby has created a paid service for users to be notified of incoming transactions to their view-only wallets.</li>
    <li>Moneromooo has released a new <a href="https://github.com/moneromooo-monero/monero-update" target="_blank">Monero Updater software</a>, that would automatically check, verify, and download the correct version of Monero for your platform.</li>
    <li>Github user dan-da has made a <a href="https://github.com/dan-da/subaddress-derive-xmr" target="_blank">CLI utility that allows for offline Monero address generation</a>, as well as subsequent subaddress generation, without the need for core Monero software installation.</li>
    <li>Community members Rottensox and Anhdres (from Monerujo) have started a Spanish podcast about Monero. <a href="https://anchor.fm/elmonero/episodes/1-El-Hack-e97q4f/a-a1367he" target="_blank"></a> Available on Anchor.</li>
    <li><a href="https://github.com/monero-ecosystem/monero-python/releases/tag/v0.6.2" target="_blank">Monero Python Module 0.62</a> has been released, with optimized ed25519 code, leading to about 100x faster subaddress generation and seed operations.</li>
    <li>A <a href="https://github.com/monero-ecosystem/telegram-monerotipbot" target="_blank">Monero Tip Bot for Telegram</a> has joined the ecosystem.</li>
    <li>An <a href="https://github.com/monero-ecosystem/go-xmrto-client" target="_blank"></a>XMRr.to client written in Go was added to the Monero Ecosystem.</li>
    <li>u/fullmetalscience has opened up their domain <a href="https://xmr.id/" target="_blank">xmr.id</a> for the public to register their OpenAlias accounts on.</li>
    <li>Tevador, the principal author of RandomX, has created a <a href="https://github.com/tevador/randomx-sniffer" target="_blank">RandomX Sniffer tool</a> to help users detect if RandomX is running on their computer.</li>
</ul>

<p>Note that all the repositories in the Monero Ecosystem are maintained by community members and not by the Monero Core Team. Thus, we encourage everyone to do their own research before using any projects stored in these repositories.</p>

<table class="hted-head">
  <tbody><tr class="row1">
    <th>Monero Coffee Chat & Monero Talk</th>
  </tr>
</tbody></table>

<p>Once a month, Justin Ehrenhofer and Diego Salazar host the Monero Coffee Chat, during which developers, researchers, and community members join a live conversation stream to discuss the latest Monero related news, development, ongoing projects and events that have occurred.</p>

<p>The Coffee Chat recordings are an excellent way to keep up with everything Monero related on a monthly basis. You can view them on the <a href="https://www.youtube.com/channel/UCKxLNPJeEjPXOke55i5AIXA" target="_blank">Monero Community Workgroup Youtube channel</a>.</p>

<p>During the past six months, the Monero Talk has conducted several in-depth interviews with people of interest about Monero related topics and development, but not only. Below is a sample of interviewees and topics discussed:</p>

<ul>
    <li><a href="https://youtu.be/UgqYeVbeCjA" target="_blank">Snipa's interview as the new main lead maintainer of Monero</a>.</li>
    <li><a href="https://youtu.be/pa0RlyH92Ns" target="_blank">C3 interviews with Riccardo “fluffypony” Spagni and Joel Gugger</a>.</li>
    <li><a href="https://youtu.be/ao-I1PkPFNM" target="_blank">Matthias Tarasiewicz on RIAT, Monero & Chaos Communication Congress 36C3</a>.</li>
    <li><a href="https://youtu.be/2wDekBAGydg" target="_blank">Andreas M. Antonopoulos on fungibility, privacy, Monero & the future of true digital cash</a>.</li>
    <li><a href="https://youtu.be/ZDr9XgLjXaQ" target="_blank">Lucas, creator of MoneroMixer - a tool that helps you anonymously transact or mix XMR & other coins</a>.</li>
</ul>

<table class="hted-head">
  <tbody><tr class="row1">
    <th>International Community Events</th>
  </tr>
</tbody></table>

<p>Monero had a major presence at both DEFCON in August, and 36C3 in December.</p>

<p>DEFCON saw fit to bring Monero back with its own village, and this year we had more space to play around with. The community funded more equipment (which can be used in subsequent years) and sponsored several volunteers to go to Las Vegas, where we were able to host talks, workshops, give out swag, and sell merchandise. All who took part thought that the Monero Village was a great success. You can view the speeches given on <a href="https://www.youtube.com/playlist?list=PL9fPq3eQfaaBiCOF12ZYejtj21sI1jm0I" target="_blank">DEFCON’s Youtube channel playlist</a>.</p>

<p>The Chaos Communication Congress (C3) was held in Leipzig for the 36th year, and the Monero community once again joined forces with our friends from RIAT to host the Critical Decentralisation Cluster (CDC), which itself hosted several other privacy and FOSS focused assemblies. The entirety of the CDC was funded by Monero’s CCS, and only made possible by these donations. We had our own stage, and held talks and workshops, and worked on cementing ourselves into becoming a staple in the C3 ecosystem. All talks were streamed and recorded and can be <a href="https://www.youtube.com/playlist?list=PLsSYUeVwrHBn07zTBg7fGHRW5Kn_Z3FJL" target="_blank">found on the Monero Community youtube channel</a>.</p>

<p>DEFCON is the biggest hacker convention in the world, and C3 is the biggest one in Europe. Monero’s presence at both, for the second year in a row, especially when other projects are turned away, show its decentralized, hacker roots, and commitment to its grassroots ideals, and exposes Monero to the right audience. These two events, along with Monero’s Konferenco reported on in the last Revuo show the project as a budding force in both the privacy and FOSS worlds.</p>

<h3 id="translations">Monero Outreach & Monero Localization Update</h3>

<p>The Monero Outreach has been keeping up the good work of promoting Monero worldwide, through original content. Several guides, articles, designs, talk transcriptions, and other resources are available to view on their <a href="https://www.monerooutreach.org/" target="_blank">website</a>.</p>

<p>These promotional materials have been translated into different languages with the help of the Localization workgroup led by ErCiccione. Also, the workgroup has, for the sake of practicality, moved from Pootle to Weblate.</p>

<h3 id="mobile">Third-Party Apps & Services Update</h3>

<p>Monero counts numerous third-party applications and services, each tailored to a specific need. In this section, we will focus on the most used ones that community members consider most trustworthy.</p>

<h5>Cake Wallet</h5>

<p><a href="https://cakewallet.io" target="_blank">Cake Wallet</a> hit a new milestone in its journey of offering the Monero community with a safe light wallet to store their XMR; The App has reached over 20,000 unique downloads on the App Store. The open-source Monero wallet for iOS is now also available for Android devices.</p>

<h5>Monerujo</h5>

<p><a href="https://monerujo.io" target="_blank">Monerujo</a> has also had its share of improvements. The Android Wallet for Monero now supports currency conversion for BTC payments using kraken + ECB rates and xmr.to payments with subaddresses. Other features include the possibility to scan only for v0.15 nodes and UI improvements.</p>

<h5>XMR.to</h5>

<p>To make privately exchanging Monero to Bitcoin even more convenient, <a href="https://xmr.to/" target="_blank">XMR.to</a> has introduced some new features which include the possibility to specify an amount directly in XMR, and the ability to complete an incomplete order in one click. You can also check their Monero network map for more information about the distribution of Monero nodes across the world, their protocol version and more.</p>

<h5>Local Monero / AgoraDesk</h5>

<p>The team behind <a href="https://localmonero.co">LocalMonero.co</a> launched <a href="https://agoradesk.com">AgoraDesk</a>, the world's first P2P OTC cryptocurrency options exchange. They support XMR and BTC contracts, as well as generally adding Bitcoin to their typical local OTC acquisitions platform with the launch of the product. As usual there is no KYC/AML or other verification performed to use the site and their services.</p>

<h3 id="donate">Donate</h3>

<p markdown="1">If you enjoy this publication and want to support it, we encourage you to donate to the Monero General Fund, using the following address:</p>

<p class="address" markdown="1">44AFFq5kSiGBoZ4NMDwYtN18obc8AemS33DBLWs3H7otXft3XjrpDtQGv7SqSsaBYBb98uNbr2VBBEt7f2wfn3RVGQBEP3A</p>

<!--p><a href="monero:44AFFq5kSiGBoZ4NMDwYtN18obc8AemS33DBLWs3H7otXft3XjrpDtQGv7SqSsaBYBb98uNbr2VBBEt7f2wfn3RVGQBEP3A" class="qr"><img src="/img/donate-monero.png"></a></p-->

Comments, criticism, complaints or corrections? Please contact rehrar at **rehrar** at **tuta.io**. Say rehrar sent you.
