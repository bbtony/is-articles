# is-articles
# Go-malwares-history

Репозиторий содержит ссылки на статьи и переводы, интересных материалов по и malware-reverse/development. Преимущественно 
написанных на Golang. Может быть полезна исследователям, различным сотрудникам по ИБ, пентестерам.

**Malwares (переводы):**
* ```noname``` - malware без имени 
* ```-``` - отсутствие перевода


| Name           | Publication date | Original | Translation                               | Description                |
|:---------------|:-----------------| :------- |:------------------------------------------| :------------------------- |
| r2r2 			 | -       			| [ENG](https://www.guardicore.com/labs/operation-prowli-traffic-manipulation-cryptocurrency-mining/) | -                                         ||
| Analog Zebrocy | 30.01.2019       | [ENG](https://blog.malwarebytes.com/threat-analysis/2019/01/analyzing-new-stealer-written-golang/) | -                                         ||
| GoBrut 		 | 06.03.2019       | [ENG](https://www.fortinet.com/blog/threat-research/new-stealth-worker-campaign-creates-a-multi-platform-army-of-bru) | -                                         ||
| Rocke 		 | 15.03.2019       | [ENG](https://www.anomali.com/blog/rocke-evolves-its-arsenal-with-a-new-malware-family-written-in-golang) | - ||
| Zebrocy        | 03.06.2019       | [ENG](https://securelist.com/zebrocys-multilanguage-malware-salad/90680/) | -                                         ||
| <b>noname</b>  | 02.07.2019       | [ENG](https://www.f5.com/labs/articles/threat-intelligence/new-golang-malware-is-spreading-via-multiple-exploits-to-mine-mo) | -                                         ||
| GoBotKR		 | 08.07.2019       | [ENG](https://www.welivesecurity.com/2019/07/08/south-korean-users-backdoor-torrents/) | -                                         ||
| <b>noname</b>		 | 08.10.2019       | [ENG](https://www.fortinet.com/blog/threat-research/new-golang-ransomware-targeting-linux-systems) | -                                         |ransomware|
| Snake (EKANS) #1| 02.03.2020       | [ENG](https://www.dragos.com/blog/industry-news/ekans-ransomware-and-ics-operations/) | -                                         |ransomware|
| Kaiji   		 | 04.05.2020       | [ENG](https://www.intezer.com/blog/research/kaiji-new-chinese-linux-malware-turning-to-golang/) | -                                         |ботнет, брут ssh, ddos|
| Glupteba       | 24.06.2020       | [ENG](https://news.sophos.com/en-us/2020/06/24/glupteba-report/) | -                                         | - |
| Golang PlugX   | 23.11.2020       | [ENG](https://www.proofpoint.com/us/blog/threat-insight/ta416-goes-ground-and-returns-golang-plugx-malware-loader) | -                                         ||
| Blackrota      | 24.11.2020       | [ENG](https://blog.netlab.360.com/blackrota-a-heavily-obfuscated-backdoor-written-in-go/) | [RU](./translations/malware/blackrota.md) |бэкдор, эксплуатация ошибки конфигурации Docker, написан на Go. |
| <b>noname</b>  | 29.12.2020       | [ENG](https://www.intezer.com/blog/research/new-golang-worm-drops-xmrig-miner-on-servers/) | - |"червь", майнер, постэксплуатация. |
| ElectroRAT     | 05.01.2021       | [ENG](https://www.intezer.com/blog/research/operation-electrorat-attacker-creates-fake-companies-to-drain-your-crypto-wallets/) | -                                         ||
| Ezuri          | 07.01.2021       | [ENG](https://www.bleepingcomputer.com/news/security/linux-malware-authors-use-ezuri-golang-crypter-for-zero-detection/) | -                                         ||
| SUNSHUTTLE     | 04.03.2021       | [ENG](https://www.mandiant.com/resources/blog/sunshuttle-second-stage-backdoor-targeting-us-based-entity) | -                                         ||
| KlingonRAT     | 17.06.2021       | [ENG](https://www.intezer.com/blog/malware-analysis/klingon-rat-holding-on-for-dear-life/) | -                                         ||
| Kinsing        | 03.09.2021       | [ENG](https://www.cyberark.com/resources/threat-research-blog/kinsing-the-malware-with-two-faces) | -                                         ||
| Capoae         | 16.09.2021       | [ENG](https://www.akamai.com/blog/security/capoae-malware-ramps-up-uses-multiple-vulnerabilities-and-tactics-to-spread) | -                                         ||
| DECAF          | 28.10.2021       | [ENG](https://blog.morphisec.com/decaf-ransomware-a-new-golang-threat-makes-its-appearance)      | -                                         ||
| BotenaGo       | 11.11.2021       | [ENG](https://cybersecurity.att.com/blogs/labs-research/att-alien-labs-finds-new-golang-malwarebotenago-targeting-millions-of-routers-and-iot-devices-with-more-than-30-exploits) | [RU](./translations/malware/botenago.md)  | ботнет, VT распознается как вариант Mirai, большой вектор атак на устройства. |
| Linux_AVP      | 18.11.2021       | [ENG](https://sansec.io/research/ecommerce-malware-linux-avp) | -                                         ||
| TellYouThePass | 11.01.2022       | [ENG](https://www.crowdstrike.com/blog/tellyouthepass-ransomware-analysis-reveals-modern-reinterpretation-using-golang/) | -                                         | |
| DoNot Go       | 18.01.2022       | [ENG](https://www.welivesecurity.com/2022/01/18/donot-go-do-not-respawn/) | -                                         | |
| Next BotenaGo  | 26.01.2022       | [ENG](https://cybersecurity.att.com/blogs/labs-research/botenago-strike-again-malware-source-code-uploaded-to-github) | -                                         | |
| Kraken         | 16.02.2022       | [ENG](https://www.zerofox.com/blog/meet-kraken-a-new-golang-botnet-in-development/) | -                                         | |
| PartyTicket    | 25.02.2022       | [ENG](https://www.zscaler.com/blogs/security-research/technical-analysis-partyticket-ransomware) |-||
| njRAT    		 | 08.03.2022       | [ENG](https://asec.ahnlab.com/en/32450/) |-||
| Go Elephant    | 01.04.2022       | [ENG](https://blog.malwarebytes.com/threat-intelligence/2022/04/new-uac-0056-activity-theres-a-go-elephant-in-the-room/) | -                                         | |
| Denonia        | 06.04.2022       | [ENG](https://www.cadosecurity.com/cado-discovers-denonia-the-first-malware-specifically-targeting-lambda/) | [RU](./translations/malware/denonia.md)                                         | |
| Hive           | 19.04.2022       | [ENG](https://www.cadosecurity.com/cado-discovers-denonia-the-first-malware-specifically-targeting-lambda/) | - | ransomware |
| BlackByte      | 03.05.2022       | [ENG](https://www.zscaler.com/blogs/security-research/analysis-blackbyte-ransomwares-go-based-variants) |-| RaaS  |
| oRat           | 09.05.2022       | [ENG](https://www.sentinelone.com/blog/from-the-front-lines-unsigned-macos-orat-malware-gambles-for-the-win/) | -                                         ||
| Nerbian RAT    | 11.05.2022       | [ENG](https://www.proofpoint.com/us/blog/threat-insight/nerbian-rat-using-covid-19-themes-features-sophisticated-evasion-techniques) | -                                         ||
| Panchan        | 15.06.2022       | [ENG](https://www.akamai.com/blog/security/new-p2p-botnet-panchan) |-| Botnet  |
| YamaBot        | 07.07.2022       | [ENG](https://blogs.jpcert.or.jp/en/2022/07/yamabot.html) |-|   |
| H0lyGh0st      | 14.07.2022       | [ENG](https://www.microsoft.com/security/blog/2022/07/14/north-korean-threat-actor-targets-small-and-midsize-businesses-with-h0lygh0st-ransomware/) |-|   |
| Backdoorit / Caligula | 13.07.2022       | [ENG](https://decoded.avast.io/davidalvarez/go-malware-on-the-rise/) |-| ransomware |
| Manjusaka      | 02.08.2022       | [ENG](https://blog.talosintelligence.com/2022/08/manjusaka-offensive-framework.html) |-| |
| Snake (EKANS) #2| 03.08.2022       | [ENG](https://www.0ffset.net/reverse-engineering/analysing-snake-ransomware/) |-| ransomware |
| LOLI Stealer   | 03.08.2022       |[ENG](https://blog.cyble.com/2022/08/03/loli-stealer-golang-based-infostealer-spotted-in-the-wild/)  |-| stealer|
| Orchard        | 05.08.2022       | [ENG](https://blog.netlab.360.com/a-new-botnet-orchard-generates-dga-domains-with-bitcoin-transaction-information/) |-| botnet |
| Servhelper     | 12.08.2022       | [ENG](https://blog.talosintelligence.com/2021/08/raccoon-and-amadey-install-servhelper.html) |-| golang dropper |
| BianLian       | 18.08.2022       | [ENG](https://blog.cyble.com/2022/08/18/bianlian-new-ransomware-variant-on-the-rise/) |-| ransomware |
| Agenda         | 25.08.2022       | [ENG](https://www.trendmicro.com/en_us/research/22/h/new-golang-ransomware-agenda-customizes-attacks.html) |-| ransomware |
| ModernLoader   | 30.08.2022       | [ENG](https://blog.talosintelligence.com/2022/08/modernloader-delivers-multiple-stealers.html) |-| miner |
| Go webbfuscator | 31.08.2022       | [ENG](https://www.securonix.com/blog/golang-attack-campaign-gowebbfuscator-leverages-office-macros-and-james-webb-images-to-infect-systems) |-| |
| Chaos | 28.09.2022       | [ENG](https://blog.lumen.com/chaos-is-a-go-based-swiss-army-knife-of-malware/) |-| |
| Alchimist | 13.10.2022       | [ENG #1](https://blog.talosintelligence.com/alchimist-offensive-framework/) [ENG #2](https://socradar.io/new-alchimist-framework-targets-windows-macos-and-linux-systems)[ENG #3](http://blog.talosintelligence.com/2022/10/alchimist-offensive-framework.html)|-| offensive framework|
| HackHound IRC Bot | 11.11.2022       | [ENG](https://asec.ahnlab.com/en/41806/) |-| |
| Octocrypt | 22.11.2022       | [ENG](https://blog.cyble.com/2022/11/18/axlocker-octocrypt-and-alice-leading-a-new-wave-of-ransomware-campaigns/) |-| RaaS |

Не являются Go-malwares, но интересные примеры и техники:

| Name | Publication date | Original | Translation                               | Description                |
|:-----|:-----------------| :------- |:------------------------------------------| :------------------------- |
| Pink | 29.10.2021       | [ENG](https://blog.netlab.360.com/pink-en/) | [RU](./translations/malware/pink.md)      |ботнет, гибридное управление, обновляемая конфигурация. |
| CronRAT        | 24.11.2021       | [ENG](https://sansec.io/research/cronrat) | -                                         ||
