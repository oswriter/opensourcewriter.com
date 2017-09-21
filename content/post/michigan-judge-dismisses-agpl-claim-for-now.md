+++
date = "2017-09-19"
title = "Michigan Judge Dismisses AGPL Claim (For Now)"
description = "Dutch programmer still faces U.S. lawsuit over alleged misappropriation of code."
categories = ["Copyright + Licensing"]
tags = ["Michigan", "Netherlands", "AGPL", "Lisp", "Python", "trade secrets"]
+++

Software development largely disregards national borders. Many open source projects have contributors in different countries, even different continents. But when legal disputes arise, borders suddenly matter again, since courts need to establish their jurisdiction over the parties involved.

## Did a Graduate Student Steal Software Company's "Trade Secrets"?

Recently, a federal judge in Michigan decided to exercise jurisdiction over a Dutch programmer accused of misappropriating a combination of open-source and proprietary code from a local software company. The judge also [denied the defendant's motion to dismiss the lawsuit](https://scholar.google.com/scholar_case?case=9866713133568797338). But the judge did, for the time being, dismiss one of the software company's claims that specifically relates to open-source licensing.

The plaintiff is a two-employee company based in Michigan. It produces "knowledge-based engineering software" written in Lisp. The open-source version of the software is published under the [GNU Affero General Public License version 3](https://opensource.org/licenses/AGPL-3.0) (AGPL). The company also publishes "professional" and "enterprise" versions of its software under a proprietary "software license agreement" (SLA).

The plaintiff licensed its proprietary software to a Dutch university, where the defendant was a graduate student. The defendant used the software under the terms of university's SLA. In 2010, he signed separate non-compete and contributor agreements that gave him additional access to the proprietary version's source code. In exchange, he agreed to treat the code as a "trade secret" and not use it to compete against the plaintiff.

About three years later, the defendant started to develop his own knowledge-based engineering software--this one written in Python rather than Lisp. Initially, the plaintiff and the defendant tried to work together on this new software, but the relationship quickly soured. The defendant subsequently formed his own company to develop and market his Python-based software.

While attending a conference in the United States last August, the defendant ran into one of the plaintiff's two employees. At this time, the defendant learned the plaintiff was developing its own Python-based software. And just before the defendant was scheduled to give his own presentation at the conference, the plaintiff served him with a lawsuit.

## Accessing "Michigan Resource" Under Non-Compete Agreement Binds Non-Citizen to U.S. Jurisdiction

The lawsuit revolves around the plaintiff's belief that the defendant stole its code to produce his own competing software. Specifically, the plaintiff's [amended complaint](https://www.scribd.com/document/359366592/Knowledge-Based-Solutions-v-Van-Dijk-Complaint) claims the defendant committed "breach of contract" by violating the terms of the non-disclosure and contributor agreements. The plaintiff further alleges the defendant violated the AGPL by using the code from the open-source version of its product to produce a "Derivative Work for which the parties are charged a license fee." Finally, the plaintiff alleges copyright infringement under both American and Dutch law, in addition to misappropriation of trade secrets under Michigan law.

The first question that [Judge Laurie J. Michelson](https://www.mied.uscourts.gov/index.cfm?pageFunction=chambers&judgeid=34) had to answer is whether or not the Court had "personal jurisdiction" over the defendant, who after all lives in the Netherlands. Michelson said it was a "close call," but the nature of the non-compete agreement favored jurisdiction on that part of the breach of contract claim.

While merely signing a contract is not enough to subject an out-of-state (or out-of-country) person to Michigan's jurisdiction, Michelson said the non-compete agreement here allowed the defendant to "repeatedly" access the plaintiff's proprietary source code--a "Michigan resource"--which he was then contractually obliged to keep secret. The non-compete agreement further contained a "choice-of-law" provision stating that its "terms will be governed by the laws of the State of Michigan."

Michelson then went a step further and exercised supplemental (or pendent) jurisdiction over most of the plaintiff's remaining claims, including the alleged breach of the AGPL. She dismissed the charge related to violations of U.S. copyright law, however, since the alleged infringement--the production of the rival Python-based software--occurred exclusively in the Netherlands. The plaintiff maintained the defendant's presentation at the conference constituted infringement within the United States, but Michelson said that was contrary to established law.

As for the alleged violation of Dutch copyright law, Michelson declined to exercise jurisdiction under the rule of *forum non conveniens* (inconvenient forum). As Michelson put it, "This Court has no familiarity with Dutch copyright law," and it simply made more sense to try that issue in the Netherlands. But Michelson's dismissal is conditional--if and when the plaintiff sues the defendant for copyright infringement in the Dutch courts, he must agree not to contest jurisdiction.

## Open-Source Claims Directed at Wrong Party

Finally, Michelson dismissed the plaintiff's claim for breach of the AGPL "without prejudice." She explained the AGPL claims were different than the other contract issues because of the nature of the alleged breach. As noted above, the plaintiff claims the defendant incorporated code from the open-source version of its product and then his company charged customers a licensing fee for its own software. If true, this would violate Section 10 of the AGPL, which states that a licensee cannot "impose a license fee, royalty, or other charge" when re-conveying a covered work to someone else.

But this also means the breach, if any, occurred when the defendant's *company* began selling its software--not when the defendant purportedly misappropriated the plaintiff's code. Consequently, Michelson said the plaintiff needed to sue the defendant's company rather than the defendant individually. Dismissal without prejudice affords the plaintiff the opportunity to amend and refile its complaint.

It remains to be seen whether the plaintiff will ultimately prevail on the merits of its case. But as these preliminary rulings illustrate, there are a number of complicating factors that may arise when there is licensing-related litigation across international boundaries. One thing to note is Judge Michelson only agreed to exercise supplemental jurisdiction over the AGPL claims only after establishing that Michigan law governed the non-compete agreement for the proprietary software. The AGPL (and similar open-source licenses) typically do not contain choice-of-law provisions. So in a hypothetical future case where a U.S. developer sues a non-U.S. party for purely open-source license violations--or vice-versa--it's unclear how a court might resolve any jurisdictional issues.
