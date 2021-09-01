layout: true
.footer[
	- Max Moser / WiSe 2021/22 / Intro IT Security / 02 - Basics
]

---
class: title, smokescreen, shelf
background-image: url(static/t0.gif)

# Introduction to IT Security
### 02 - Basics

---
class: roomy
# Security ?
---
class: roomy
# Security

> The state of being free from danger or threat. \[[^1]\]

[^1]: https://en.oxforddictionaries.com/definition/security

---
class: roomy
# Vulnerability ?
---
class: roomy
# Vulnerability

> A **flaw or weakness in system** security procedures, design,
> implementation, or internal controls **that could \[…\] result in a
> security breach** or a violation of the system's security policy
> \[[^2]\]

[^2]: http://csrc.nist.gov/publications/nistpubs/800-30/sp800-30.pdf

---
class: roomy
# Exploit ?
---
class: roomy
# Exploit

> A piece of software, a chunk of data, or a sequence of commands that
> **takes advantage of a bug or vulnerability to cause unintended or
> unanticipated behavior** to occur on computer software, hardware, or
> something electronic (usually computerized) \[[^3]\]

[^3]: https://en.wikipedia.org/wiki/Exploit_(computer_security)

---
# Zero Day?

---
# Zero-Day

> **A zero day vulnerability** refers to a hole in software that **is
> unknown to the vendor**.
>
> This security hole is then **exploited by hackers before the vendor
> becomes aware** and hurries to fix it—this exploit is called a zero
> day attack. \[...\]
>
> The term **“zero day” refers to the unknown nature** of the hole to
> those outside of the hackers, specifically, the developers. Once the
> vulnerability becomes known, a race begins for the developer, who must
> protect users. \[[^4]\]

[^4]: https://web.archive.org/web/20170704035927/http://www.pctools.com/security-news/zero-day-vulnerability/

---

# Exercise 1.1 ??

## Brainstorming Attackers

1. Identify and describe possible **Attackers** and their motivation
2. Rate the danger posed by each attacker type (:skull: to
   :skull::skull::skull:)
3. Estimate the risk of your own employer being targeted by each
   identified attacker type (in %)
4. Which attacker types are likely to work together and how does this
   impact their danger rating?

---

# Advantage of the Attacker

* Attacker must **succeed once**
  * Defender must get it right _all the time_
* Attacker can choose the **weakest spot**
  * Defender must defend _all places_
* Attacker can leverage **zero-days**
  * Defender can only defend against _known attacks_
* Attacker can **play dirty**
  * Defender needs to _play by the rules_

---

# Case Studies

---

# Data Breaches

[![Data Breaches by no. of records](static/01-motivation/worlds_biggest_data_breaches-by_no_records.png)](http://informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/)

---

# Marriot (November 2018)

> The hotel chain asked guests checking in for a treasure trove of
> personal information: credit cards, addresses and sometimes passport
> numbers. On Friday, consumers learned the risk. Marriott International
> revealed that hackers had breached its Starwood reservation system and
> had stolen the personal data of up to 500 million guests. \[[^5]\]

![Marriot logo](static/01-motivation/200px-Marriot_Logo.svg.png)

---

> \[...\] Starwood’s data has not popped up on the so-called dark web,
> according to Recorded Future, a cybersecurity firm, and Coalition, a
> cyber insurance provider, which suggested that the hotel attackers
> weren’t looking to sell what they took.
>
> “Usually when stolen data doesn’t appear, it’s a state actor
> collecting it for intelligence purposes,” \[...\] information could be
> fed, for example, into an analysis program run by a country’s state
> security apparatus \[...\]. Using “big data” technology similar to
> what marketers use in targeted advertising, the country could try to
> pinpoint the comings and going of intelligence agents from other
> nations. Did they stay, for example, in the same hotel as a potential
> source for that country? \[[^5]\]

_The intrusion went unnoticed for four years by Starwood._

[^5]: https://www.nytimes.com/2018/11/30/business/marriott-data-breach.html

---

# Equifax (September 2017)

> If you have a credit report, there’s a good chance that you’re one of
> the 143 million American consumers whose sensitive personal
> information was exposed in a data breach at Equifax, one of the
> nation’s three major credit reporting agencies. \[[^6]\]

![Equifax logo](static/01-motivation/281px-Equifax_Logo.svg.png)

---

> Here are the facts, according to Equifax. The breach lasted from
> mid-May through July. The hackers accessed people’s names, Social
> Security numbers, birth dates, addresses and, in some instances,
> driver’s license numbers. They also stole credit card numbers for
> about 209,000 people and dispute documents with personal identifying
> information for about 182,000 people. And they grabbed personal
> information of people in the UK and Canada too. \[[^6]\]

_Recommended steps for protection include "monitor your existing credit
card and bank accounts closely" but also "consider placing a credit
freeze" or "placing a fraud alert on your files"._

[^6]: https://www.consumer.ftc.gov/blog/2017/09/equifax-data-breach-what-do

---

# VTech (November 2015)

> \[...\] When it comes to our identities being leaked all over the
> place, it’s just another day on the web. **Unless it’s our children’s
> identities, that’s a whole new level.** When it’s hundreds of
> thousands of children including their names, genders and birthdates,
> that’s off the charts. \[[^7]\]

![VTech logo](static/01-motivation/VTechLogo.png)

---

> When it includes their parents as well – along with their home address
> – and you can link the two and emphatically say “Here is 9 year old
> Mary, I know where she lives and I have other personally identifiable
> information about her parents (including their password and security
> question)”, I start to run out of superlatives to even describe how
> bad that is. \[[^7]\]

_It later came out that head shots :camera: of kids and private chat
messages were also exposed. The total number of children exposed in the
incident is over 6.3 million._

[^7]: https://www.troyhunt.com/when-children-are-breached-inside

---

# CloudPets (February 2017)

> \[...\] There were a lot of news headlines about
> [how Germany had banned an internet-connected doll called "Cayla" over fears hackers could target children](http://www.telegraph.co.uk/news/2017/02/17/germany-bans-internet-connected-dolls-fears-hackers-could-target/).
>
> \[...\] Just before that, we had the
> [VTech data breach](#vtech-november-2015) which exposed a huge amount
> of very personal information.
>
> Which brings us to CloudPets \[...\] which is a toy that represents
> the nexus of both the problems discussed above. \[[^8]\]

![CloudPets logo](static/01-motivation/CloudPets_LogoNew.png)

---

> \[...\] Put yourself in the shoes of the average parent, that is one
> who's technically literate enough to know the wifi password but not
> savvy enough to understand how the "magic" of daddy talking to the
> kids through the bear (and vice versa) actually works. They don't
> necessarily realise that every one of those recordings – those
> intimate, heartfelt, extremely personal recordings – between a parent
> and their child is stored as an audio file on the web. They certainly
> wouldn't realise that in CloudPets' case, that data was stored in a
> MongoDB that was in a publicly facing network segment without any
> authentication required and had been indexed by Shodan (a popular
> search engine for finding connected things). \[[^8]\]

_Impacted parents were never notified by CloudPets._

[^8]: https://www.troyhunt.com/data-from-connected-cloudpets-teddy-bears-leaked-and-ransomed-exposing-kids-voice-messages

---

# Exercise 1.2 (_optional_ :pushpin:)

## Have I been pwned?

1. Visit <https://haveibeenpwned.com/>
2. Type in your email address
3. Hit the `pwned?` button
4. How many pwnages do you get for your private and/or business email?
   (:pushpin:)

![Good news - No pwnage found!](static/01-motivation/haveibeenpwned-green.png)
![Oh no - pwned!](static/01-motivation/haveibeenpwned-red.png)

---
class: img-left
# Cost of Cyber Crime

![](img/cost-of-cybercrime.png)

* cost of cyber crime is expected to increase constantly
* source: [embroker.com, 2021](https://www.embroker.com/blog/cyber-attack-statistics/)

---
class: img-left
# Ransomware Attacks

![](img/frequency-ransomware.png)

* frequency of ransomware attacks increases constantly
* source: [embroker.com, 2021](https://www.embroker.com/blog/cyber-attack-statistics/)

---
class: img-left compact
# BSI-Lagebericht IT-Sicherheit

[![](img/bsi-lage-it-sicherheit-2020.png# w-9-12th)](https://www.bsi.bund.de/DE/Service-Navi/Publikationen/Lagebericht/lagebericht_node.html)

> ... situation was once again dominated by Emotet ... enables a cascade of further malware attacks, including targeted ransomware attacks ...
> ... ransomware remains one of the biggest threats to companies, public authorities and other institutions, as well as private users
> ... trend toward targeted attacks on financially strong victims ... also lesser-known companies with high revenues were attacked as well as public administration institutions, universities, medical facilities

---
class: img-left compact
# BSI-Lagebericht IT-Sicherheit

[![](img/bsi-lage-it-sicherheit-2020.png# w-9-12th)](https://www.bsi.bund.de/DE/Service-Navi/Publikationen/Lagebericht/lagebericht_node.html)

> ... threat from data leaks has reached a new level with the disclosure of millions of patient records on the Internet ... databases containing highly sensitive medical data were discovered freely accessible on the Internet
>  ... Unlike in the case of data theft, this did not involve a technically complex attack, but rather inadequately secured or incorrectly configured databases were the cause of the data leak...

---
class: img-left compact
# BSI-Lagebericht IT-Sicherheit

[![](img/bsi-lage-it-sicherheit-2020.png# w-9-12th)](https://www.bsi.bund.de/DE/Service-Navi/Publikationen/Lagebericht/lagebericht_node.html)

> ... Furthermore, several vulnerabilities in software products again occurred in the reporting period, which attackers were able to exploit for malware attacks or data theft. In the process, attackers also increasingly used the "human" factor as a gateway for attacks that work with social engineering methods and, as it were, serve as a door opener for further attacks.

---
class: img-left compact
# BSI-Lagebericht IT-Sicherheit

[![](img/bsi-lage-it-sicherheit-2020.png# w-9-12th)](https://www.bsi.bund.de/DE/Service-Navi/Publikationen/Lagebericht/lagebericht_node.html)

> The fact that cyber criminals react quickly to socially relevant topics and trends is demonstrated by various attacks exploiting the COVID 19 pandemic. Here, for example, phishing campaigns, CEO fraud, and fraud attempts using IT means were observed. For example, fraudsters managed to abuse emergency aid measures by deceptively imitating the application websites of official bodies. The cyber criminals then used the company-related data that the applicants had entered on the fake pages to improperly apply for aid funds.

---
class: img-left
# Cyber Attacks on the Rise

![](img/von-angriffen-betroffen.png) ![](img/increase-cyber-attacks.png)

* significantly more companies experience cyber attacks
* source: [Bitkom, 2021](https://www.bitkom.org/sites/default/files/2021-08/bitkom-slides-wirtschaftsschutz-cybercrime-05-08-2021.pdf)

---
# Serious Increase of Height of Damage

![](img/schaeden.png)

* source: [Bitkom, 2021](https://www.bitkom.org/sites/default/files/2021-08/bitkom-slides-wirtschaftsschutz-cybercrime-05-08-2021.pdf)

---
# Serious Increase of Height of Damage

![](img/cyber-damage.png# w-8-12th)

* source: [statista, 2021](https://www.statista.com/statistics/267132/total-damage-caused-by-by-cyber-crime-in-the-us/)

---
# Legal Obligations

* example: [IT-Sicherheitsgesetz](https://www.bgbl.de/xaver/bgbl/start.xav?startbk=Bundesanzeiger_BGBl&jumpTo=bgbl121s1122.pdf)

[![](img/it-sicherheits-gesetz.png)](https://www.bgbl.de/xaver/bgbl/start.xav?startbk=Bundesanzeiger_BGBl&jumpTo=bgbl121s1122.pdf)
---
# Consequences on Reputation

[![](img/biggest-data-breaches.png)](https://informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/)

---
class: img-left
# Top Threats (Enisa)

[![](img/enisa-top-threats.png)](https://www.enisa.europa.eu/topics/threat-risk-management/threats-and-trends/enisa-threat-landscape-2020-top-15-threats)

---
class: img-left
# Cybersecurity as Competitive Advantage

[![](img/competitive-advantage.png)](https://www.capgemini.com/2018/05/cybersecurity-the-new-competitive-advantage-for-retailers/)

* more and more companies realize, that a proper cyber security setting gives them a competitive advantage