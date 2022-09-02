# เป้าหมาย
ตัว repository นี้เป็นโครงงานกลุ่มในรายวิชา CN466 Internet of Things ปีการศึกษา 2565 ตามหลักสูตรวิศวกรรมคอมพิวเตอร์ คณะวิศวกรรมศาสตร์ มหาวิทยาลัยธรรมศาสตร์  เป้าหมายของเราคือ การนำ Gadgetbridge ซึ่งเป็นโมไบล์แอพพลิเคชันบน Android มาเพิ่มฟีเจอร์ในส่วน MQTT สำหรับรายงานข้อมูลแบบไร้สาย และปรับลดขอบเขตของฟีเจอร์และอุปกรณ์ให้เจาะจง mi band 6 เท่านั้น  เราคาดหวังว่าการดำเนินการตามนี้จะช่วยให้นักศึกษาเข้าใจการ maintain และ improve ซอฟต์แวร์ ซึ่งเป็นบทบาทที่จำเป็นในการทำงานเป็นนักพัฒนา  ทั้งนี้ เราได้คงเนื้อหาของ Gadgetbridge README เดิมโดยไม่แก้ไขในช่วงท้ายของเอกสารนี้ โดยหากมีเวลาจะแปลเป็นภาษาไทยต่อไป

## รายชื่อนักศึกษาและเนื้องานที่ได้ทำ
1. นาย ธัญพิสิฐ แกมทอง รับผิดชอบในส่วน X
1. นางสาว นัฏนันทน์ นวกิจบำรุง รับผิดชอบในส่วน X
1. นาย พัฒนา ทรัพย์พนาชัย รับผิดชอบในส่วน X
1. นาย สุเมต คงแก้ว รับผิดชอบในส่วน X
1. นาย ณัฐพงศ์ เชาวเจริญพงศ์ รับผิดชอบในส่วน X
1. นาย จิรพัฒน์ มาลีหวล รับผิดชอบในส่วน X
1. A รับผิดชอบในส่วน X
1. A รับผิดชอบในส่วน X
1. A รับผิดชอบในส่วน X
1. A รับผิดชอบในส่วน X
1. A รับผิดชอบในส่วน X

# การศึกษาโครงสร้าง Gadgetbridge

## การศึกษาส่วน user interface
Gadgetbridge เป็นโมไบล์แอพพลิเคชันบน Android โดยประกอบด้วยหน้าจอทั้งหมด X หน้าจอ ได้แก่
### หน้าจอหลัก
หน้าจอหลักของ Gadgetbridge 
<p><img src="/imgs/main_screen.jpg" height="480"></p>

## การศึกษาส่วนโค้ดที่เชื่อมกับ user interface
การศึกษาความสัมพันธ์ระหว่าง UI และส่วนโค้ดพบความสัมพันธ์ดังนี้

**TBD ตารางสรุป**

## การอธิบายโครงสร้างส่วนโค้ดด้วย UML
โครงสร้าง ตรรกะ และปฏิสัมพันธ์ภายในส่วนโค้ดสามารถอธิบายด้วยแผนภาพ UML ดังนี้

### แผนภาพ class diagram

### แผนภาพ state machine diagram

### แผนภาพ activity diagram

### แผนภาพ sequence diagram


# การพัฒนาส่วน MQTT
ตัว Gadgetbridge ถูกพัฒนาขึ้นให้ทำงานแบบออฟไลน์เป็นหลัก โดยโครงงานนี้ต้องการเปิดช่องทางสื่อสารผ่าน MQTT เพื่อให้ผู้ใช้สามารถนำข้อมูลมาแสดงผลหรือประมวลผลต่อได้

# Original contents
Gadgetbridge is now hosted on [codeberg.org](https://codeberg.org/Freeyourgadget/Gadgetbridge/).

<a href="https://codeberg.org/Freeyourgadget/Gadgetbridge/">
    <img alt="Get it on Codeberg" src="https://get-it-on.codeberg.org/get-it-on-blue-on-white.png" height="60">
</a>

Gadgetbridge
============

Gadgetbridge is an Android (4.4+) application which will allow you to use your
Pebble, Mi Band, Amazfit Bip and HPlus device (and more) without the vendor's closed source application
and without the need to create an account and transmit any of your data to the
vendor's servers.

[Homepage](https://gadgetbridge.org) - [Blog](https://blog.freeyourgadget.org) - [Wiki](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki) - <a rel="me" href="https://social.anoxinon.de/@gadgetbridge">Mastodon</a>

[![Donate](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/Gadgetbridge/donate)


[![Code Quality: Java](https://img.shields.io/lgtm/grade/java/g/Freeyourgadget/Gadgetbridge.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Freeyourgadget/Gadgetbridge/context:java)
[![Total Alerts](https://img.shields.io/lgtm/alerts/g/Freeyourgadget/Gadgetbridge.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Freeyourgadget/Gadgetbridge/alerts)
[![Translate](https://hosted.weblate.org/widgets/freeyourgadget/-/gadgetbridge/svg-badge.svg)](https://hosted.weblate.org/projects/freeyourgadget/gadgetbridge)

## Download

[<img src="https://f-droid.org/badge/get-it-on.png" alt="Get it on F-Droid" height="80">](https://f-droid.org/app/nodomain.freeyourgadget.gadgetbridge)

[List of changes](https://codeberg.org/Freeyourgadget/Gadgetbridge/src/master/CHANGELOG.md)

## Supported Devices
**(WARNING: Some of them WIP and some of them without maintainer)**

- Amazfit
	- [Band 5](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Mi-Band-5) [**\[!\]**](#special-pairing-procedures)
	- [Bip](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-Bip)
	- [Bip Lite](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-Bip-Lite), [Bip S](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-Bip-S), [Bip U](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-Bip-U) [**\[!\]**](#special-pairing-procedures)
	- [Cor](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-Cor), [Cor 2](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-Cor-2)
	- [GTR](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-GTR), [GTR 2/2e](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-GTR) [**\[!\]**](#special-pairing-procedures)
	- [GTS](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-GTS), [GTS 2/2e](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-GTS) [**\[!\]**](#special-pairing-procedures) 
	- [Neo](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-Neo) [**\[!\]**](#special-pairing-procedures) 
	- T-Rex [**\[!\]**](#special-pairing-procedures)
	- Verge Lite [**\[!\]**](#special-pairing-procedures)
	- [X ](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Mi-Band-5) [**\[!\]**](#special-pairing-procedures)
- [Bangle.js](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Bangle.js)
- BFH-16
- [Casio](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Casio)
    - Casio GB-X6900B
    - Casio GB-6900B
    - Casio GB-5600B
    - Casio STB-1000
    - Casio GBX-100
    - Casio GBD-100
    - Casio GBD-200
    - Casio GBD-H1000
- [FitPro](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/FitPro)
- Fossil
	- [Hybrid HR](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Fossil-Hybrid-HR) [**\[!\]**](#special-pairing-procedures)
	- Q Hybrid
- [Galaxy Buds](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Galaxy-Buds)
    - [Galaxy Buds](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Galaxy-Buds#user-content-galaxy-buds)
    - [Galaxy Buds Live](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Galaxy-Buds#user-content-galaxy-buds-live)

- [HPlus Devices (e.g. ZeBand)](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/HPlus)
- ID115
- [iTag](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/iTag)
- JYou Y5
- Lefun
- Lenovo
	- Watch 9
	- [Watch X (Plus)](https://codeberg.org/mamutcho/Gadgetbridge/wiki)
- Liveview
- Makibes HR3
- Mi
	- [Band, Band 1A, Band 1S](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Mi-Band), [Band 2](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Mi-Band-2), [Band 3](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Mi-Band-3)
	- [Band 4](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Mi-Band-4), [Band 5](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Mi-Band-5), [Band 6](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Mi-Band-6) [**\[!\]**](#special-pairing-procedures)
	- Scale 2 (Currently only displays a toast after stepping on the scale)
- [MyKronoz ZeTime](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/MyKronoz-ZeTime)
- NO.1 F1
- [Nothing Ear (1)](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Nothing-Ear-%281%29)
- [Nut Mini 3, Nut 2 and possibly others](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Nut)
- Pebble
	- [Pebble, Steel, Time, Time Steel, Time Round, 2](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Pebble)
- PineTime (InfiniTime Firmware)
- Roidmi, Roidmi 3, Mojietu 3 (Bluetooth FM Transmitters)
- [SMA](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/SMA) Q2 (SMA-Q2-OSS Firmware)
- [Sony WH-1000XM3, WH-1000XM4, WF-SP800N, WF-1000XM3](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Sony-Headphones)
- Teclast H10, H30
- TLW64
- Vibratissimo (Experimental)
- Wasp-OS devices
- XWatch (Affordable Chinese Casio-like smartwatches)
- [Zepp E](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Amazfit-GTR) [**\[!\]**](#special-pairing-procedures)


### Special Pairing Procedures

Some Huami / Amazfit / Mi / Zepp devices can only be paired with Gadgetbridge using a secret key that has to be obtained once using the proprietary app with an account. Detailed instructions in the wiki: [Huami Server Pairing](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Huami-Server-Pairing)

The Fossil Hybrid HR also requires using the proprietary app, but with a more complicated procedure. Details in the wiki: [Hybrid HR](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Fossil-Hybrid-HR).

## Features

Please see [FEATURES.md](https://codeberg.org/Freeyourgadget/Gadgetbridge/src/master/FEATURES.md)

## Authors
### Core Team (in order of first code contribution)

* Andreas Shimokawa
* Carsten Pfeiffer
* Daniele Gobbetti
* Petr Vaněk

### Additional device support
* João Paulo Barraca (HPlus)
* Vitaly Svyastyn (NO.1 F1)
* Sami Alaoui (Teclast H30)
* "ladbsoft" (XWatch)
* Sebastian Kranz (ZeTime)
* Vadim Kaushan (ID115)
* "maxirnilian" (Lenovo Watch 9)
* "ksiwczynski", "mkusnierz", "mamutcho" (Lenovo Watch X Plus)
* Andreas Böhler (Casio)
* Jean-François Greffier (Mi Scale 2)
* Johannes Schmitt (BFH-16)
* Lukas Schwichtenberg (Makibes HR3)
* Daniel Dakhno (Fossil Q Hybrid, Fossil Hybrid HR)
* Gordon Williams (Bangle.js)
* Pavel Elagin (JYou Y5)
* Taavi Eomäe (iTag)
* Erik Bloß (TLW64)
* Yukai Li (Lefun)

## Contribute

Contributions are welcome, be it feedback, bug reports, documentation, translation, research or code. Feel free to work
on any of the open [issues](https://codeberg.org/Freeyourgadget/Gadgetbridge/issues);
just leave a comment that you're working on one to avoid duplicated work.

[Developer documentation](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Developer-Documentation) - [Support for a new Device](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/Support-for-a-new-Device) - [New Device Tutorial](https://codeberg.org/Freeyourgadget/Gadgetbridge/wiki/New-Device-Tutorial)

Translations can be contributed via https://hosted.weblate.org/projects/freeyourgadget/gadgetbridge/

## Community

If you would like to get in touch with other Gadgetbridge users and developers outside of Codeberg, you can do so via:
* Matrix: [`#gadgetbridge:matrix.org`](https://matrix.to/#/#gadgetbridge:matrix.org)

## Do you have further questions or feedback?

Feel free to open an issue on our issue tracker, but please:
- do not use the issue tracker as a forum, do not ask for ETAs and read the issue conversation before posting
- use the search functionality to ensure that your question wasn't already answered. Don't forget to check the **closed** issues as well!
- remember that this is a community project, people are contributing in their free time because they like doing so: don't take the fun away! Be kind and constructive.
- Do not ask for help regarding your own projects, unless they are Gadgetbridge related

## Having problems?

0. Phone crashing during device discovery? Disable Privacy Guard (or similarly named functionality) during discovery.
1. Open Gadgetbridge's settings and check the option to write log files
2. Reproduce the problem you encountered
3. Check the logfile at /sdcard/Android/data/nodomain.freeyourgadget.gadgetbridge/files/gadgetbridge.log
4. File an issue at https://codeberg.org/Freeyourgadget/Gadgetbridge/issues/new/choose and possibly provide the logfile

Alternatively you may use the standard logcat functionality to access the log.
