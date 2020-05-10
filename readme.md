<!--lint disable no-unused-definitions-->
[comment]:<img src="https://badgen.net/badge/icon/awesome list/51A8E0?icon=awesome&label" height="18"/>
<!--lint enable no-unused-definitions-->

<div align="center">
  <br>
	<img width="500" src="media/logo/new.svg" alt="Awesome">
  <br>

  <p align="center">
    <hr>
    <sup>
    We all know that automotive engineering is awesome, but here's a list of especially awesome things related to that world.<br><br>Let's help make this list really awesome:&emsp;&emsp;&emsp;&emsp;<br>
     ✅ perform review and leave a comment <strong><a href="https://github.com/Marcin214/awesome-automotive/issues/2">here</a></strong><br>
     ✅ add new awesome record like <strong><a href="https://github.com/Marcin214/awesome-automotive/blob/master/contributing.md">here</a></strong>&emsp;&emsp;&nbsp;&emsp;<br>&emsp;&emsp;&emsp;
     ✅ if sth needs to be improved, create an issue <strong><a href="https://github.com/Marcin214/awesome-automotive/issues">here</a></strong>&nbsp;&nbsp;
    </sup>
    <br>
    <br><br>
    <a href="https://github.com/sindresorhus/awesome"><img alt="awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" /></a>
    <img src="https://img.shields.io/github/license/Marcin214/awesome-automotive"/>
    <a href="https://github.com/Marcin214/awesome-automotive/blob/master/contributing.md"><img alt="PullRequests Welcome" src="https://img.shields.io/badge/pull request-welcome-blue.svg" /></a>
    <a href="https://github.com/Marcin214/awesome-automotive/issues"><img src="https://img.shields.io/github/issues/Marcin214/awesome-automotive?color=yellow"/></a>
    <a href="http://hits.dwyl.com/Marcin214/awesome-automotive"><img alt="HitCount" src="http://hits.dwyl.com/Marcin214/awesome-automotive.svg" /></a>
  </p>
  <hr>
</div>


<!--lint disable list-item-bullet-indent-->
## Contents

- [Autosar](#autosar)
- [Automotive SPICE](#automotive-spice)
- [Autonomous Driving](#autonomous-driving)
- [Bus Systems](#bus-systems)
  - [Automotive Ethernet](#automotive-ethernet)
  - [CAN](#can)
  - [FlexRay](#flexray)
  - [LIN](#lin)
  - [MOST](#most)
- [Functional Safety](#functional-safety)
- [Cyber Security](#cyber-security)
- [Vehicle Diagnostics](#vehicle-diagnostics)
- [Software Development Process](#software-development-process)
  - [Requirements](#requirements)
  - [Design](#design)
  - [Implementation](#implementation)
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

- [AUTOSAR](https://www.autosar.org/) - (**AUT**omotive **O**pen **S**ystem **AR**chitecture) is a worldwide development partnership of vehicle manufacturers, suppliers, service providers and companies from the automotive electronics, semiconductor and software industry.
- [Artop](https://www.artop.org/) - The **A**UTOSA**R** **T**ool **P**latform is an implementation of common base functionality for AUTOSAR development tools.
- [About AUTomotive Open System ARchitecture (AUTOSAR)](https://www.renesas.com/us/en/solutions/automotive/technology/autosar.html) - From Renesas Electronics, overview on key AUTOSAR features.
- [AUTOSAR Development Tools](https://www.renesas.com/us/en/solutions/automotive/manual-softtools.html) - From Renesas Electronics, overview AUTOSAR toolse from different suppliers.
- [How the concepts of the Automotive standard "AUTOSAR" are realized in new seamless tool-chains <img src="media/icons/pdf.png" height="18"/>](http://web1.see.asso.fr/erts2010/Site/0ANDGY78/Fichier/PAPIERS%20ERTS%202010/ERTS2010_0002_final.pdf) - Dr. Stefan Voget, P. Favrais, article.
- [Introduction to Autosar](https://elearning.vector.com/mod/page/view.php?id=437) - From Vector Informatik, e-learning module.
- [automotive software(OSEK & AUTOSAR) and its tool-chain <img src="media/icons/github.png" height="18"/>](https://github.com/autoas/as).
- <details>
  <summary>Suppliers of AUTOSAR standard software - Click to expand <img src="media/icons/warning.png" height="18"/>
  </summary><div><table><thead><tr><th>Supplier</th><th>MCAL</th><th>BSW/OS/RTE</th><th>Tools</th></tr></thead><tbody><tr><td><a href="https://www.comasso.org/" target="_blank" rel="noopener noreferrer">COMASSO</a></td><td></td><td><a href="https://www.comasso.org/comasso_downloads" target="_blank" rel="noopener noreferrer">BSW</a></td><td><a href="https://www.comasso.org/comasso_downloads" target="_blank" rel="noopener noreferrer">BSWDT</a></td></tr><tr><td><a href="https://www.elektrobit.com/" target="_blank" rel="noopener noreferrer">Elektrobit</a></td><td></td><td><a href="https://www.elektrobit.com/products/ecu/eb-tresos/autocore/" target="_blank" rel="noopener noreferrer">EB tresos AutoCore</a> <br></td><td><a href="https://www.elektrobit.com/products/ecu/eb-tresos/studio/" target="_blank" rel="noopener noreferrer">EB tresos Studio</a></td></tr><tr><td><a href="https://www.etas.com/" target="_blank" rel="noopener noreferrer">ETAS</a></td><td></td><td><a href="https://www.etas.com/en/products/rta_software_products.php" target="_blank" rel="noopener noreferrer">RTA</a></td><td><a href="https://www.etas.com/en/products/ascet-developer.php" target="_blank" rel="noopener noreferrer">ACET</a><br><a href="https://www.etas.com/en/products/isolar.php" target="_blank" rel="noopener noreferrer">ISOLAR</a><br><a href="https://www.etas.com/en/products/software_products.php" target="_blank" rel="noopener noreferrer">and more ...</a></td></tr><tr><td><a href="https://www.hitex.com/" target="_blank" rel="noopener noreferrer">Hitex</a></td><td><a href="https://www.hitex.com/tools-components/software-components/mcal-and-complex-drivers/mcal-drivers-for-autosar-projects/" target="_blank" rel="noopener noreferrer">MC-ISAR</a></td><td></td><td></td></tr><tr><td><a href="https://www.infineon.com/cms/en/" target="_blank" rel="noopener noreferrer">Infineon Technologies AG</a></td><td><a href="https://www.infineon.com/cms/en/product/microcontroller/32-bit-tricore-microcontroller/" target="_blank" rel="noopener noreferrer">MCAL</a></td><td></td><td></td></tr><tr><td><a href="https://www.kpit.com/" target="_blank" rel="noopener noreferrer">KPIT</a></td><td></td><td><a href="https://www.kpit.com/solutions/autosar/" target="_blank" rel="noopener noreferrer">K-SAR Suite</a></td><td><a href="https://www.kpit.com/workimpact/with-k-sar-editor-tool-engineers-configure-complete-ecus-intuitively-and-comfortably/" target="_blank" rel="noopener noreferrer">K-SAR Editor</a></td></tr><tr><td><a href="https://mentor.com/" target="_blank" rel="noopener noreferrer">Mentor</a></td><td></td><td><a href="https://www.mentor.com/embedded-software/autosar/software" target="_blank" rel="noopener noreferrer">VSTAR</a><br></td><td><a href="https://www.mentor.com/embedded-software/autosar/tools" target="_blank" rel="noopener noreferrer">VSTAR Tools</a></td></tr><tr><td><a href="https://www.nxp.com/" target="_blank" rel="noopener noreferrer">NXP Semiconductors</a></td><td><a href="https://www.nxp.com/design/automotive-software-and-tools/autosar-:AUTOSAR-HOME#developer" target="_blank" rel="noopener noreferrer">MCAL</a></td><td><a href="https://www.nxp.com/design/automotive-software-and-tools/autosar-:AUTOSAR-HOME#developer" target="_blank" rel="noopener noreferrer">OS</a></td><td></td></tr><tr><td><a href="https://www.opensynergy.com/" target="_blank" rel="noopener noreferrer">OpenSynergy</a></td><td></td><td><a href="https://www.opensynergy.com/autosar/" target="_blank" rel="noopener noreferrer">COQOS</a></td><td><a href="https://www.opensynergy.com/autosar/" target="_blank" rel="noopener noreferrer">COQOSAReasy</a><br></td></tr><tr><td><a href="https://www.renesas.com/us/en/" target="_blank" rel="noopener noreferrer">Renesas Electronics</a></td><td><a href="https://www.renesas.com/us/en/solutions/automotive/technology/autosar.html" target="_blank" rel="noopener noreferrer">MCAL</a></td><td></td><td></td></tr><tr><td><a href="https://www.st.com/content/st_com/en.html" target="_blank" rel="noopener noreferrer">STMicroelectronics</a></td><td><a href="https://www.st.com/en/embedded-software/spc5-autosar-mcal.html" target="_blank" rel="noopener noreferrer">MCAL</a></td><td></td><td></td></tr><tr><td><a href="https://www.vector.com/" target="_blank" rel="noopener noreferrer">Vector Informatik</a></td><td></td><td><a href="https://www.vector.com/pl/en/products/products-a-z/embedded-components/microsar/" target="_blank" rel="noopener noreferrer">MICROSAR</a></td><td><a href="https://www.vector.com/pl/en/products/products-a-z/software/davinci-developer/" target="_blank" rel="noopener noreferrer">DaVinci Developer</a><br><a href="https://www.vector.com/pl/en/products/products-a-z/software/davinci-configurator-pro/" target="_blank" rel="noopener noreferrer">DaVinci Configurator</a><br><a href="https://www.vector.com/pl/en/products/products-a-z/software/" target="_blank" rel="noopener noreferrer">and more ...</a><br></td></tr></tbody></table><sup></sup></div>
</details>

## Automotive SPICE

- [ASPICE](http://www.automotivespice.com/download/) - Automotive SPICE® Process Assessment Model (PAM) and Process Reference Model (PRM).
- [Automotive SPICE: Ensuring ASPICE Compliance <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PL5VAskozuQ3DwQIE3A8dGKWIRKPeNBTCG) 

## Autonomous Driving
- [Awesome Autonomous Driving <img src="media/icons/awesome.png" height="14"/>](https://github.com/autonomousdrivingkr/Awesome-Autonomous-Driving)
- [Awesome Autonomous Vehicles <img src="media/icons/awesome.png" height="14"/>](https://github.com/manfreddiaz/awesome-autonomous-vehicles)
- [Awesome Self-Driving Cars <img src="media/icons/awesome.png" height="14"/>](https://github.com/philbort/awesome-self-driving-cars)


## Bus Systems

### Automotive Ethernet

- [Introduction to Automotive Ethernet](https://elearning.vector.com/mod/page/view.php?id=149) - Vector e-learning module.
- [Vector Automotive Ethernet Symposium 2019: Lectures <img src="media/icons/video.png" height="18"/>](https://elearning.vector.com/mod/page/view.php?id=149) - On 2th of April 2019. In 7 presentations - by Infineon, NXP, TÜV-Nord and Vector - the speakers showed the current status and solutions for the upcoming challenges.
- [A TCP/IP Tutorial <img src="media/icons/student.png" height="18"/>](https://tools.ietf.org/html/rfc1180) - RFC 1180, short overview on ethernet.
- [Automotive Grade Linux](http://opensig.org/about/specifications/) - Open software stack for the connected car.
- [OPEN Alliance. "Automotive Ethernet Specifications"](http://opensig.org/about/specifications/)
- [SOME/IP specification](http://some-ip.com/papers.shtml)
- [vsomeip in 10 minutes](https://github.com/GENIVI/vsomeip/wiki/vsomeip-in-10-minutes) - Introduction to SOME/IP based on GENIVI implementation.
- <details>
  <summary>Automotive Ethernet Stack - Click to expand <img src="media/icons/warning.png" height="18"/></summary><div class="tg-wrap"><table><thead><tr><th>Use Case</th><th>Audio<br>Video<br></th><th>Time <br>Sync</th><th>Network <br>Managment</th><th>Service <br>Control</th><th>Diagnostic </th><th>Address <br>Config</th><th>Helper<br>Protocols</th></tr></thead><tbody><tr> <td align="center">Application</td> <td align="center"></td> <td align="center"></td> <td align="center"></td> <td align="center"></td><td align="center" rowspan="2"><a href="http://read.pudn.com/downloads191/doc/899044/ISO+14229+(2006).pdf">UDS*</a></td> <td align="center"></td> <td align="center"></td></tr><tr> <td align="center">Presentation</td> <td align="center"></td> <td align="center"></td> <td align="center"></td> <td align="center"></td> <td align="center"></td> <td align="center"></td></tr><tr> <td align="center">Session</td><td align="center" rowspan="2">IEEE 1722<br>(AVTP)<br></td><td align="center" rowspan="2">IEEE 802.1AS <br>(PTP)<br></td> <td align="center">UDP-NM</td> <td align="center"><a href="http://some-ip.com/papers.shtml">SOME/IP</a></td> <td align="center"><a href="http://read.pudn.com/downloads721/ebook/2887987/BS%20ISO%2013400-2-2012.pdf">DoIP*</a></td> <td align="center"><a href="https://tools.ietf.org/html/rfc2131">DHCP</a></td> <td align="center"></td></tr><tr> <td align="center">Transport</td><td align="center" colspan="4"><a href="https://tools.ietf.org/html/rfc793">TCP</a> and/or <a href="https://tools.ietf.org/html/rfc768">UDP</a></td> <td align="center"></td></tr><tr> <td align="center">Network<br></td> <td align="center"></td> <td align="center"></td><td align="center" colspan="4"><a href="https://tools.ietf.org/html/rfc791">IPv4</a>/<a href="https://tools.ietf.org/html/rfc2460">IPv6</a></td> <td align="center"><a href="https://tools.ietf.org/html/rfc792">ICMP</a>, <a href="https://tools.ietf.org/html/rfc4443">ICMPv6</a>,<br><a href="https://tools.ietf.org/html/rfc826">ARP</a>, <a href="https://tools.ietf.org/html/rfc4861">NDP</a><br></td></tr><tr> <td align="center">Data Link</td><td align="center" colspan="7">Ethernet MAC + VLAN (802.1Q)</td></tr><tr> <td align="center">Physical</td><td align="center" colspan="7">Automotive Ethernet Physical <br>(Ethernet, <a href="http://opensig.org/about/specifications/">OPEN Alliance BroadR-Reach</a>, Reduced twisted-pair Gigabit Eth)</td></tr></tbody></table><sup>(*) - superseded by newer version of standard</sup></div>
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
- [Vector Cybersecurity Symposium 2016: Lectures <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLLKv-zcGiHJHdtX4Vmw8n8DBFuDlmQCQy) - On 23rd June 2016.
- [Vector Cybersecurity Symposium 2017: Lectures <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLLKv-zcGiHJGvyWfoPaTMw0QN3306wTPm)
- [Vector Cybersecurity Symposium 2019: Lectures <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLLKv-zcGiHJHxvK3v0sRYO9Kpnpb-Thz9) - On April 3rd 2019.
- [Awesome Vehicle Security <img src="media/icons/awesome.png" height="14"/>](https://github.com/jaredthecoder/awesome-vehicle-security) - Books, hardware, software, applications, people to follow, car hacking and tinkering. 

## Vehicle Diagnostics

- [ISO 14229-1:2006(E) <img src="media/icons/pdf.png" height="18"/>](http://read.pudn.com/downloads191/doc/899044/ISO+14229+(2006).pdf) - Unified Diagnostic Services (UDS) specification, superseded by the standard [ISO 14229-1:2013](https://www.iso.org/standard/55283.html).
- [ISO 13400-2:2012 <img src="media/icons/pdf.png" height="18"/>](http://read.pudn.com/downloads721/ebook/2887987/BS%20ISO%2013400-2-2012.pdf) - Road vehicles - Diagnostic communication over Internet Protoco (DoIP).
- [Information Posters](https://automotive.softing.com/en/service/order-of-information-poster.html) - From Softing Automotive about UDS, ODX, OTX, DoIP.
- [Diagnostics and Flashing <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLLKv-zcGiHJFZ0ueLgYRZfSa6l-eTcwBh) - From Vector Informatik GmbH, read more [here](https://vctr.it/2B8hbJh).

## Software Development Process
### Requirements
<div><sup>Polarion Software</sup></div>

- [Polarion Tutorial Videoss <img src="media/icons/student.png" height="18"/><img src="media/icons/video.png" height="18"/>](https://polarion.plm.automation.siemens.com/tutorials) 
- [Vector Polarion Connection Utility <img src="media/icons/video.png" height="18"/>](https://elearning.vector.com/mod/page/view.php?id=149) - Add-on tool for Vector vTESTstudio that serves to integrate Siemens Polarion ALM into the Vector testing tool chain.

<div><sup>Rational DOORS</sup></div>

- [Getting started <img src="media/icons/student.png" height="18"/>](https://www.ibm.com/developerworks/rational/library/getting-started-ibm-rational-doors/index.html) - Tutorial for IBM Rational DOORS and IBM Rational DOORS Web Access.
- [Documentation](https://www.ibm.com/support/pages/node/594725) - Library pages contain documentation for earlier versions of Rational products.
- [Essentials <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLFB5C518530CFEC93) - Hands-on examples.
- [IBM Rational Rhapsody tips and tricks <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLaBR7gZA1IOjxthOjpG3aAKeyRt04Wlhd) - Hands-on examples.
- [Using DXL](https://www.ibm.com/support/knowledgecenter/SSYQBZ_9.5.0/com.ibm.doors.configuring.doc/topics/c_dxl.html) - The Rational® DOORS® eXtension Language (DXL) is an easy-to-learn scripting language that you can use to control and extend Rational DOORS functions.
- [The DXL Reference Manual](https://www.ibm.com/support/knowledgecenter/SSYQBZ_9.5.0/com.ibm.doors.requirements.doc/topics/dxl_reference_manual.pdf?view=kc)


### Design

- [Enterprise Architect](https://sparxsystems.com/products/ea/) - Official tool vendor Sparx Systems website. Contains demo, tutorials and more.
- [Awesome Software Architecture <img src="media/icons/awesome.png" height="14"/>](https://github.com/simskij/awesome-software-architecture)

### Implementation
<div><sup>Programming</sup></div>

- [Guidelines for the use of the C++14 language in critical and safety-related systems <img src="media/icons/pdf.png" height="18"/>](https://www.autosar.org/fileadmin/user_upload/standards/adaptive/17-03/AUTOSAR_RS_CPP14Guidelines.pdf) - AUTOSAR standard.
- [MISRA](https://www.misra.org.uk/Publications/tabid/57/Default.aspx) - Publications from world-leading best practice guidelines for the safe and secure application.
- [Modern Embedded Systems Programming <img src="media/icons/student.png" height="18"/><img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLPW8O6W-1chwyTzI3BHwBLbGQoPFxPAPM) - Series of hands-on lessons about embedded microcontrollers in C.
- [SEI CERT Coding Standards](https://wiki.sei.cmu.edu/confluence/display/c/SEI+CERT+C+Coding+Standard) - Languages such as C, C++, Java, and Perl, and the Android™ platform.
- [Awesome C <img src="media/icons/awesome.png" height="14"/>](https://github.com/aleksandar-todorovic/awesome-c)
- [Awesome C++ <img src="media/icons/awesome.png" height="14"/>](https://github.com/fffaraz/awesome-cpp#readme)
- [Awesome Embedded <img src="media/icons/awesome.png" height="14"/>](https://github.com/nhivp/Awesome-Embedded)

<div><sup>Configuration</sup></div>

- [EB tresos®Studio documentation  <img src="media/icons/pdf.png" height="18"/>](http://read.pudn.com/downloads263/doc/1209805/EB_tresos_Studio_documentation_en.pdf)
- [Awesome MATLAB <img src="media/icons/awesome.png" height="14"/>](https://github.com/mikecroucher/awesome-MATLAB)

<div><sup>Debugging</sup></div>

- [MULTI Integrated Development Environment](https://www.ghs.com/products/MULTI_IDE.html)
- [Trace32 Lauterbach GmbH](https://www.lauterbach.com/frames.html?home.html) - High-tech company for microprocessor development tools. 
- [Trace32 basic examples of usage <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLlgTI9rjcm35NUgKufepfqgn6Fd4zBe88) - From Lauterbach GmbH. 
- [Trace32: Debug your embedded systems <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PL1sbHjUq1DdqQSBlk-uM-EJ3O1iof0-IN) - From Nohau Solutions.

### Testing

<div><sup>Unit tests</sup></div>

- [ARUnit](https://www.artop.org/arunit/) - Unit Testing of AUTOSAR Software Components, [Artop](https://www.artop.org) sub-project.
- [Google Test <img src="media/icons/github.png" height="18"/>](https://github.com/google/googletest) - Google's C++ test framework.
- [Googletest Mocking (gMock) Framework <img src="media/icons/github.png" height="18"/>](https://github.com/google/googletest/tree/master/googlemock) - Google's framework for writing and using C++ mock classes.
- [Fake Function Framework (fff) <img src="media/icons/github.png" height="18"/>](https://github.com/meekrosoft/fff) - Micro-framework for creating fake C functions for tests. 
- [Unit Testing C Code <img src="media/icons/stackoverflow.png" height="18"/>](https://stackoverflow.com/questions/65820/unit-testing-c-code?page=1&tab=votes#tab-top) - Discussion with overview on available C unit test frameworks.

<div><sup>CANoe and CAPL </sup></div>

- [CANoe: Product Videos <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PL9EA087B9E8301D23)
- [Programming with CAPL <img src="media/icons/pdf.png" height="18"/>](https://can-newsletter.org/assets/files/media/raw/a456e3078f907a0482182ce831912427.pdf)
- [Tips and Tricks for the Use of CAPL](https://kb.vector.com/entry/875/) - Three consecutive articles, for all levels of user knowledge [Part One](https://kb.vector.com/upload_551/file/CAPL_1_CANNewsletter_201406_PressArticle_EN.pdf), [Part Two](https://kb.vector.com/upload_551/file/CAPL_2_CANNewsletter_201409_PressArticle_EN.pdf), [Part Three](https://kb.vector.com/upload_551/file/CAPL_3_CANNewsletter_201411_PressArticle_EN.pdf).

<div><sup>Other</sup></div>

- [Software Testing Symposium 2018: Lectures <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLLKv-zcGiHJHCmgtUcp5YOfmNkEgiXERd)
- [Vector Testing Symposium 2017: Lectures <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLLKv-zcGiHJEpfR5iAZBNjpl1NIpRA7Gw)
- [Vector Testing Symposium 2018: Lectures <img src="media/icons/video.png" height="18"/>](https://www.youtube.com/playlist?list=PLLKv-zcGiHJFxt_WSazEXShViv_jnlu0K)
- [Awesome Software Quality <img src="media/icons/awesome.png" height="14"/>](https://github.com/ligurio/awesome-software-quality#readme) - Free software testing resources.

## Resources

### Blogs
- [just auto](https://www.just-auto.com/) - Global automotive industry news, data and analysis. Recent information about OEMs and suppliers.
- [automotivetechis](https://automotivetechis.wordpress.com/)
- [automotive wiki](https://automotive.wiki/index.php/Main_Page) - From [SCHEID automotive GmbH](https://www.scheid-automotive.com/).

### Books
- [Technical Papers on the Development of Embedded Electronics <img src="media/icons/pdf.png" height="18"/><img src="media/icons/book.png" height="18"/><img src="media/icons/warning.png" height="18"/>](https://assets.vector.com/cms/content/know-how/_technical-articles/Pressbook_EN_2018.pdf) - Vector Informatik GmbH, 2018
- [Automotive Embedded Systems Handbook <img src="media/icons/pdf.png" height="18"/><img src="media/icons/book.png" height="18"/>](https://d1.amobbs.com/bbs_upload782111/files_38/ourdev_629261ASTZIF.pdf) - Nicolas Navet, 2009.
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

- [SAE Magazines <img src="media/icons/warning.png" height="18"/>](https://www.sae.org/publications/magazines) - set of free magazines from automotive industry.
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
