<!--lint disable no-unused-definitions-->
[comment]:<img src="https://badgen.net/badge/icon/awesome list/51A8E0?icon=awesome&label" height="18"/>
<!--lint enable no-unused-definitions-->

<div align="center">
  <br>
	<img width="500" src="media/logo/new.svg" alt="Awesome">
  <br>
  <br>
  <br>
  <br>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img alt="awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" /></a>
    <img src="https://img.shields.io/github/license/Marcin214/awesome-automotive"/>
    <a href="https://github.com/Marcin214/awesome-automotive/blob/master/contributing.md"><img alt="PullRequests Welcome" src="https://img.shields.io/badge/pull request-welcome-blue.svg" /></a>
    <a href="http://hits.dwyl.com/Marcin214/awesome-automotive"><img alt="HitCount" src="http://hits.dwyl.com/Marcin214/awesome-automotive.svg" /></a>
  </p>
  <hr>
</div>

<!--lint disable list-item-bullet-indent-->
## Contents

- [Autosar](#autosar)
- [Automotive SPICE](#automotive-spice)
- [Bus Systems](#bus-systems)
  - [Automotive Ethernet](#automotive-ethernet)
  - [CAN](#can)
  - [FlexRay](#flexray)
  - [LIN](#lin)
  - [MOST](#most)
- [Functional Safety](#functional-safety)
- [Cyber Security](#cyber-security)
- [Vehicle Diagnostics](#vehicle-diagnostics)
- [Requirements Engineering](#requirements-engineering)
- [Software Development](#software-development)
- [Testing](#testing)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Books](#books)
  - [Magazines](#magazines)
  - [Podcasts](#podcasts)
  - [Press releases](#press-releases)
  - [Videos](#videos)
  - [Miscellaneous](#miscellaneous)
<!--lint enable list-item-bullet-indent-->
<!--lint disable awesome-list-item-->
## Autosar

- [autosar.org](https://www.autosar.org/) - Official website.
  - [Classic Platform](https://www.autosar.org/standards/classic-platform/)
  - [Adaptive Platform](https://www.autosar.org/standards/adaptive-platform/)
- ["Introduction to Autosar"](https://elearning.vector.com/mod/page/view.php?id=437) - Vector e-learning module.
- [Artop](https://www.artop.org/) - The **A**UTOSA**R** **T**ool **P**latform is an implementation of common base functionality for AUTOSAR development tools.

## Automotive SPICE

- [ASPICE](http://www.automotivespice.com/download/) - Automotive SPICE® Process Assessment Model (PAM) and Process Reference Model (PRM).
- [Automotive SPICE: Ensuring ASPICE Compliance <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PL5VAskozuQ3DwQIE3A8dGKWIRKPeNBTCG) 

## Bus Systems

### Automotive Ethernet

- [Introduction to Automotive Ethernet](https://elearning.vector.com/mod/page/view.php?id=149) - Vector e-learning module.
- [A TCP/IP Tutorial <img src="media/icons/student.png" height="18"/>](https://tools.ietf.org/html/rfc1180) - RFC 1180, short overview on ethernet.
- [Automotive Grade Linux](http://opensig.org/about/specifications/) - Open software stack for the connected car.
- [OPEN Alliance. "Automotive Ethernet Specifications"](http://opensig.org/about/specifications/)
- [SOME/IP specification](http://some-ip.com/papers.shtml)
- [vsomeip in 10 minutes](https://github.com/GENIVI/vsomeip/wiki/vsomeip-in-10-minutes) - Introduction to SOME/IP based on GENIVI implementation.
- <details>
  <summary>Automotive Ethernet Stack - Click to expand !</summary>
  <table style="border-collapse:collapse;border-spacing:0;table-layout: fixed; height: 612px" class="tg"><colgroup><col style="height: 87px"><col style="height: 61px"><col style="height: 66px"><col style="height: 76px"><col style="height: 66px"><col style="height: 77px"><col style="height: 62px"><col style="height: 117px"></colgroup><tr><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:normal;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Use Case</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Audio<br>Video<br></th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Time<br> Sync</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Network <br>Managment</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Service <br>Control</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;borgit statusder-color:inherit;text-align:center;vertical-align:middle">Diagnostic</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Address <br>Config</th><th style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;font-weight:bold;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">Helper<br>Protocols</th></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Application</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" rowspan="2"><a href="http://read.pudn.com/downloads191/doc/899044/ISO+14229+(2006).pdf">UDS*</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Presentation</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Session</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" rowspan="3">IEEE<br>1722<br> <br>(AVTP)<br></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" rowspan="3">IEEE <br>802.1AS<br><br>(PTP)<br></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle">UDP-NM</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"><a href="http://some-ip.com/papers.shtml">SOME/IP</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"><a href="http://read.pudn.com/downloads721/ebook/2887987/BS%20ISO%2013400-2-2012.pdf">DoIP*</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"><a href="https://tools.ietf.org/html/rfc2131">DHCP</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Transport</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" colspan="4"><a href="https://tools.ietf.org/html/rfc793">TCP</a> and/or <a href="https://tools.ietf.org/html/rfc768">UDP</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Network<br></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" colspan="4"><a href="https://tools.ietf.org/html/rfc791">IPv4</a>/<a href="https://tools.ietf.org/html/rfc2460">IPv6</a></td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle"><a href="https://tools.ietf.org/html/rfc792">ICMP</a>, <a href="https://tools.ietf.org/html/rfc4443">ICMPv6</a>, <a href="https://tools.ietf.org/html/rfc826">ARP</a>, <a href="https://tools.ietf.org/html/rfc4861">NDP</a></td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Data Link</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" colspan="7">Ethernet MAC + VLAN (802.1Q)</td></tr><tr><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:12px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle">Physical</td><td style="font-family:Tahoma, Geneva, sans-serif !important;;font-size:14px;padding:6px 5px;border-style:solid;border-height:1px;overflow:hidden;word-break:normal;border-color:inherit;text-align:center;vertical-align:middle" colspan="7">Automotive Ethernet Physical <br>(Ethernet, <a href="http://opensig.org/about/specifications/">OPEN Alliance BroadR-Reach</a>, Reduced twisted-pair Gigabit Ethernet)</td></tr></table>
  (*) - superseded by newer version of standard
  </details>

### CAN

- [Bosch specification <img src="media/icons/pdf.png" height="18"/>](http://esd.cs.ucr.edu/webres/can20.pdf) - Specification superseded by the standard [ISO 11898](https://www.iso.org/standard/63648.html).
- [Bosch CAN FD specification Version 1.0 <img src="media/icons/pdf.png" height="18"/>](https://web.archive.org/web/20151211125301/http://www.bosch-semiconductors.de/media/ubk_semiconductors/pdf_1/canliteratur/can_fd_spec.pdf)
- [Controller Area Network (CAN) Schedulability Analysis: Refuted, Revisited and Revised](https://link.springer.com/article/10.1007%2Fs11241-007-9012-7)
- [Controller Area Network (CAN) Implementation Guide <img src="media/icons/pdf.png" height="18"/>](https://www.analog.com/media/en/technical-documentation/application-notes/AN-1123.pdf)
- [Introduction to CAN](https://elearning.vector.com/mod/page/view.php?id=333) - Vector e-learning module.
- [Controller Area Network <img src="media/icons/pdf.png" height="18"/>](http://inst.cs.berkeley.edu/~ee249/fa08/Lectures/handout_canbus1.pdf) - Presentation from UC Berkeley.
- [Understanding and Using the Controller Area Network <img src="media/icons/pdf.png" height="18"/>](http://inst.cs.berkeley.edu/~ee249/fa08/Lectures/handout_canbus2.pdf) -  UC Berkeley, CAN 2.0b.
- [CAN Protocol <img src="media/icons/student.png" height="18"/>](https://www.kvaser.com/course/can-protocol-tutorial/) - Tutorial prepared by Kvaser, company [site](https://www.kvaser.com/) with more resources.
- [CAN Newsletter magazine](https://can-newsletter.org/magazine)


### FlexRay

- [FlexRay Specification <img src="media/icons/pdf.png" height="18"/>](https://svn.ipd.kit.edu/nlrp/public/FlexRay/FlexRay%E2%84%A2%20Protocol%20Specification%20Version%203.0.1.pdf)
- [FlexRay Overview](https://www.ni.com/pl-pl/innovations/white-papers/06/flexray-automotive-communication-bus-overview.html) - From National Instruments.
- [Introduction to FlexRay](https://elearning.vector.com/mod/page/view.php?id=371) - Vector e-learning module.
- [The FlexRay Electrical Physical Layer Evolution <img src="media/icons/pdf.png" height="18"/>](https://web.archive.org/web/20150216112537/http://www.hanser-automotive.de/fileadmin/heftarchiv/FLEX_10_ONL_NXP-Y.pdf) - Lorenz Steffen, magazine Automotive 2010.


### LIN

- [Introduction to LIN](https://elearning.vector.com/mod/page/view.php?id=309) - Vector e-learning module.
- [LIN Supplier ID Registration Authority](https://www.lin-cia.org/id/) - Standardized in the ISO 17987 series.
- [The LIN Short Story <img src="media/icons/pdf.png" height="18"/>](https://www.nxp.com/files-static/training_pdf/29021_S08_SLIN_WBT.pdf) - From NXP.


### MOST

- [MOST Cooperation Website](https://www.mostcooperation.com/) - Technology overview and specifications.

## Functional Safety
- [ISO 26262-1:2011(en) (Road vehicles — Functional safety — Part 1: Vocabulary](https://www.iso.org/obp/ui/#iso:std:iso:26262:-1:ed-1:v1:en) - ISO Online Browsing Platform (OBP).
- [What is the ISO 26262 Functional Safety Standard ?](https://www.ni.com/pl-pl/innovations/white-papers/11/what-is-the-iso-26262-functional-safety-standard-.html#toc2) - National Instruments white paper.
- [Criticality categories across safety standards in different domains <img src="media/icons/pdf.png" height="18"/>](https://web1.see.asso.fr/erts2012/Site/0P2RUC89/1A-1.pdf) - ERTS2 Congress. Embedded Real Time Software and Systems.


## Cyber Security
- [The Car Hacker's Handbook - A Guide for the Penetration Tester <img src="media/icons/pdf.png" height="18"/><img src="media/icons/book.png" height="18"/>](https://docs.alexomar.com/biblioteca/thecarhackershandbook.pdf) - Craig Smith, 2016.
- [Awesome Vehicle Security <img src="media/icons/awesome.png" height="14"/>](https://github.com/jaredthecoder/awesome-vehicle-security) - Books, hardware, software, applications, people to follow, car hacking and tinkering. 

## Vehicle Diagnostics

- [ISO 14229-1:2006(E) <img src="media/icons/pdf.png" height="18"/>](http://read.pudn.com/downloads191/doc/899044/ISO+14229+(2006).pdf) - Unified Diagnostic Services (UDS) specification, superseded by the standard [ISO 14229-1:2013](https://www.iso.org/standard/55283.html).
- [ISO 13400-2:2012 <img src="media/icons/pdf.png" height="18"/>](http://read.pudn.com/downloads721/ebook/2887987/BS%20ISO%2013400-2-2012.pdf) - Road vehicles - Diagnostic communication over Internet Protoco (DoIP).
- [Information Post](https://automotive.softing.com/en/service/order-of-information-poster.html) - Posters from Softing Automotive about UDS, ODX, OTX, DoIP.

## Requirements Engineering
#### Polarion Software
- [Polarion Tutorial Videoss <img src="media/icons/student.png" height="18"/><img src="media/icons/video.png" height="18"/>](https://polarion.plm.automation.siemens.com/tutorials) 

#### Rational DOORS 
- [Getting started <img src="media/icons/student.png" height="18"/>](https://www.ibm.com/developerworks/rational/library/getting-started-ibm-rational-doors/index.html) - Tutorial for IBM Rational DOORS and IBM Rational DOORS Web Access.
- [Documentation](https://www.ibm.com/support/pages/node/594725) - Library pages contain documentation for earlier versions of Rational products.
- [Essentials <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLFB5C518530CFEC93) - Hands-on examples
- [Using DXL](https://www.ibm.com/support/knowledgecenter/SSYQBZ_9.5.0/com.ibm.doors.configuring.doc/topics/c_dxl.html) - The Rational® DOORS® eXtension Language (DXL) is an easy-to-learn scripting language that you can use to control and extend Rational DOORS functions.
- [The DXL Reference Manual](https://www.ibm.com/support/knowledgecenter/SSYQBZ_9.5.0/com.ibm.doors.requirements.doc/topics/dxl_reference_manual.pdf?view=kc)

## Software Development

#### EB tresos Studio
- [EB tresos®Studio documentation  <img src="media/icons/pdf.png" height="18"/>](http://read.pudn.com/downloads263/doc/1209805/EB_tresos_Studio_documentation_en.pdf)

#### Embedded C, C, C++
- [Modern Embedded Systems Programming <img src="media/icons/student.png" height="18"/><img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLPW8O6W-1chwyTzI3BHwBLbGQoPFxPAPM) - Series of short, focused, hands-on lessons that teach you how to program embedded microcontrollers in C.
- [Awesome C <img src="media/icons/awesome.png" height="14"/>](https://github.com/aleksandar-todorovic/awesome-c)
- [Awesome C++ <img src="media/icons/awesome.png" height="14"/>](https://github.com/fffaraz/awesome-cpp#readme)
- [Awesome Embedded <img src="media/icons/awesome.png" height="14"/>](https://github.com/nhivp/Awesome-Embedded)

#### Enterprise Architect
- [Sparx Systems](https://sparxsystems.com/products/ea/) - Official tool vendor page,c ontains: demo, tutorial, webinars, white papers, guides.

#### Matlab
- [Awesome MATLAB <img src="media/icons/awesome.png" height="14"/>](https://github.com/mikecroucher/awesome-MATLAB)

#### MULTI
- [MULTI Integrated Development Environment](https://www.ghs.com/products/MULTI_IDE.html)

#### Trace32 
- [Lauterbach GmbH](https://www.lauterbach.com/frames.html?home.html) - High-tech company for microprocessor development tools. Contains tutorials, webinars, publications.
- [Basic examples of usage <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLlgTI9rjcm35NUgKufepfqgn6Fd4zBe88) - From Lauterbach GmbH. 
- [Video: Debug your embedded systems <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PL1sbHjUq1DdqQSBlk-uM-EJ3O1iof0-IN) - From Nohau Solutions.

#### Unit tests
- [ARUnit](https://www.artop.org/arunit/) - Unit Testing of AUTOSAR Software Components, [Artop](https://www.artop.org) sub-project.
- [Google Test](https://github.com/google/googletest) - Google's C++ test framework.
- [Googletest Mocking (gMock) Framework](https://github.com/google/googletest/tree/master/googlemock) - Google's framework for writing and using C++ mock classes.
- [Fake Function Framework (fff)](https://github.com/meekrosoft/fff) - Micro-framework for creating fake C functions for tests. 

## Testing

##### General
- [Awesome Software Quality <img src="media/icons/awesome.png" height="14"/>](https://github.com/ligurio/awesome-software-quality#readme) - Free software testing resources.

##### Canoe and CAPL 
- [Programming with CAPL <img src="media/icons/pdf.png" height="18"/>](https://can-newsletter.org/assets/files/media/raw/a456e3078f907a0482182ce831912427.pdf)
- [Tips and Tricks for the Use of CAPL](https://kb.vector.com/entry/875/) - Three consecutive articles, for all levels of user knowledge [Part One](https://kb.vector.com/upload_551/file/CAPL_1_CANNewsletter_201406_PressArticle_EN.pdf), [Part Two](https://kb.vector.com/upload_551/file/CAPL_2_CANNewsletter_201409_PressArticle_EN.pdf), [Part Three](https://kb.vector.com/upload_551/file/CAPL_3_CANNewsletter_201411_PressArticle_EN.pdf).

## Resources

### Blogs
- [just auto](https://www.just-auto.com/) - Global automotive industry news, data and analysis. Recent information about OEMs and suppliers.
- [automotivetechis](https://automotivetechis.wordpress.com/)
- [automotive wiki](https://automotive.wiki/index.php/Main_Page) - From [SCHEID automotive GmbH](https://www.scheid-automotive.com/).

### Books
- [Technical Papers on the Development of Embedded Electronics <img src="media/icons/pdf.png" height="18"/><img src="media/icons/book.png" height="18"/><img src="media/icons/warning.png" height="24"/>](https://assets.vector.com/cms/content/know-how/_technical-articles/Pressbook_EN_2018.pdf) - Vector Informatik GmbH, 2018
- [Automotive Embedded Systems Handbook <img src="media/icons/pdf.png" height="18"/><img src="media/icons/book.png" height="18"/><img src="media/icons/warning.png" height="24"/>](https://d1.amobbs.com/bbs_upload782111/files_38/ourdev_629261ASTZIF.pdf) - Nicolas Navet, 2009.
- [Understanding Automotive Electronics Eighth Edition <img src="media/icons/pdf.png" height="18"/><img src="media/icons/book.png" height="18"/>](https://www.engbookspdf.com/uploads/pdf-books/UnderstandingAutomotiveElectronics8theditionbyWilliamB.Ribbens-1.pdf) - William B. Ribbens, 2017.
- [FMEA Handbook <img src="media/icons/pdf.png" height="18"/><img src="media/icons/book.png" height="18"/>](https://fsp.portal.covisint.com/documents/106025/14555722/FMEA%20Handbook%20v4.2/4c14da5c-0842-4e60-a88b-75c18e143cf7) - Ford, 2011.
- [XCP – The Standard Protocol for ECU Development <img src="media/icons/pdf.png" height="18"/><img src="media/icons/book.png" height="18"/>](https://assets.vector.com/cms/content/application-areas/ecu-calibration/xcp/XCP_ReferenceBook_V3.0_EN.pdf) - Andreas Patzer, Rainer Zaiser,
Vector Informatik GmbH, 2016.
- [The Car Hacker's Handbook - A Guide for the Penetration Tester <img src="media/icons/pdf.png" height="18"/><img src="media/icons/book.png" height="18"/>](https://docs.alexomar.com/biblioteca/thecarhackershandbook.pdf) - Craig Smith, 2016.
- [engineeringbookspdf <img src="media/icons/search.png" height="18"/>](https://www.engineeringbookspdf.com/automobile-engineering/) - Offers free access to about 150 automotive books.
- [engbookspdf <img src="media/icons/search.png" height="18"/>](https://www.engbookspdf.com/Automobile/) - Offers free access to about 35 automotive books.
- [engbookspdf <img src="media/icons/search.png" height="18"/>](http://www.engineering108.com/pages/Automobile_Engineering/Automobile-engineering-ebooks-free-download.html) - Offers free access to about 5 automotive books.
- [Free Programming Books <img src="media/icons/awesome.png" height="14"/>](https://github.com/sindresorhus/awesome) 
- [Free Software Testing Books <img src="media/icons/awesome.png" height="14"/>](https://github.com/ligurio/awesome-software-quality#readme) 

### Magazines

- [SAE Magazines <img src="media/icons/warning.png" height="24"/>](https://www.sae.org/publications/magazines) - set of free magazines from automotive industry.
- [Vehicle Electronics](https://vehicle-electronics.biz/) - Free monthly magazine for automotive electronics engineers.
- [CAN Newsletter magazine](https://can-newsletter.org/magazine)

### Podcasts

- [SAE Tomorrow Today <img src="media/icons/podcast.png" height="18"/>](https://www.sae.org/podcasts) - from SAE International, provides unique and dynamic perspectives from innovative industry leaders on the challenges of tomorrow.
- [Matrickz <img src="media/icons/podcast.png" height="18"/>](https://www.matrickz.de/en/podcasts.html) - From Matrickz GmbH mainly related to ASPICE, Security and ISO26262.

### Press releases

- [Continental AG](https://www.continental.com/en/press/press-releases)
- [Elektrobit (EB)](https://www.elektrobit.com/tech-corner/)
- [Renesas Electronics Corporation](https://www.renesas.com/us/en/solutions/automotive.html)
- [OPEN Alliance](http://opensig.org/news/press-releases/)
- [SAE International](https://www.sae.org/news/press-room)
- [Softing Automotive Electronics GmbH](https://automotive.softing.com/en/service/press-publications/press-releases.html)
- [Vector Informatik GmbH](https://www.vector.com/int/en/search/?tx_solr%5Bfilter%5D%5B0%5D=contentType%3Atx_solr_file&tx_solr%5Bsort%5D=datetime+desc&tx_solr%5BresultsPerPage%5D=10)

### Videos

- [Automotive Logistics <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/user/autologisticschannel)
- [Elektrobit <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/user/EBAutomotiveSoftware/featured)
- [MATLAB Videos and Webinars <img src="media/icons/video.png" height="18"/>](https://www.mathworks.com/videos.html)
- [Vector Consulting Services <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/channel/UC-yhIPWuNcXm-DRPPsC8wiA/featured)

### Miscellaneous

- [Vector Support & Downloads](https://www.vector.com/int/en/search/?tx_solr%5Bfilter%5D%5B0%5D=contentType%3Atx_solr_file&tx_solr%5Bsort%5D=datetime+desc&tx_solr%5BresultsPerPage%5D=10) - Over 1000 great materials: webinars, articles and more.
- [Vector Knowledge Base](https://kb.vector.com/) - Vector platform with examples and solutions for problems related to offered products.
- [TOP 100 OEM suppliers](https://www.autonews.com/assets/PDF/CA89220617.PDF)
- [Awesome Indexed <img src="media/icons/awesome.png" height="14"/><img src="media/icons/search.png" height="18"/>](https://awesome-indexed.mathew-davies.co.uk/) - Search the Awesome dataset.
- [Awesome Search <img src="media/icons/awesome.png" height="14"/><img src="media/icons/search.png" height="18"/>](https://awesomelists.top/) - Quick search for Awesome lists.
<!--lint enable awesome-list-item-->

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
