# RBI IT Governance Directions for NBFCs (2026): What Replaced the 2023 Master Direction, and a Control Checklist by Layer

By Gayatri Chakrabarty ([LinkedIn](https://www.linkedin.com/in/gayatri-chakrabarty/)), Blue Copper Technologies · Last updated 2 November 2026

For NBFCs, the RBI Master Direction on IT Governance, Risk, Controls and Assurance Practices (2023) no longer applies. On 31 July 2026 the Reserve Bank of India replaced it with the Non-Banking Financial Companies Cybersecurity, Technology: Risk, Resilience and Assurance Framework Directions, 2026. They came into force with immediate effect and apply to every NBFC, with one chapter per layer: Chapter III for Base Layer NBFCs below ₹500 crore and Core Investment Companies, Chapter IV for Base Layer NBFCs of ₹500 crore and above, and Chapter V for Middle, Upper and Top Layer NBFCs.

This guide explains what changed, which chapter applies to you, and what to check and keep as evidence. Every requirement below is quoted or summarised from the RBI text, with paragraph numbers so your team can check the source.

## Does the RBI IT Governance Master Direction 2023 still apply to NBFCs?

No. Paragraph 155 of the 2026 Directions says the existing directions, instructions and guidelines “relating to Information Technology Framework and IT Governance as applicable to Non-Banking Financial Companies stand repealed.”

The repeal was made through circular RBI/DoS/2026-27/221 of 31 July 2026, “Consolidation of Supervisory Instructions: Repeal of Circulars”. It released 64 consolidated Directions and repealed 628 circulars with immediate effect. Its annex lists three NBFC technology instructions that are now repealed:

- Master Direction on Information Technology Governance, Risk, Controls and Assurance Practices (7 November 2023)
- Master Direction, Information Technology Framework for the NBFC Sector, DNBS.PPD.No.04/66.15.001/2016-17 (8 June 2017)
- Streamlining of Internal Compliance monitoring function, leveraging use of technology (31 January 2024)

Two points matter in practice:

- There is no transition period. The Directions say they “shall come into force with immediate effect”, and the text sets no comply-by date.
- Past actions stay valid. The repeal circular says actions taken under the repealed instructions continue to be governed by them. Your 2025 IS audit, for example, is still judged against the rules in force when it was done.

Many pages that rank for this topic, and some AI assistants, still describe the 2023 Direction as current. If your policies, board papers or vendor contracts cite the 2023 Direction or the 2017 IT Framework, update the references.

The new Directions carry the reference RBI/DoS/2026-27/461, DoS.CO.CSITEG.55/31.01.015/2026-27, dated 31 July 2026. You can read them on the RBI Directions page or in the official PDF.

## Which chapter of the 2026 Directions applies to your NBFC?

Paragraph 3 decides it, using the layers in the Scale Based Regulation Directions, 2025. Chapter II (the Board’s role) applies to every NBFC.

| Your NBFC | Chapter that applies | What it looks like |
| --- | --- | --- |
| Base Layer, asset size below ₹500 crore | Chapter III (paras 7 to 9) | A Board approved IT / IS policy built on nine basic standards |
| Core Investment Company (any size) | Chapter III (paras 7 to 9) | Same as above |
| Base Layer, asset size ₹500 crore and above | Chapter IV | IT Strategy Committee, a designated CIO, IT operations, IS audit, BCP and DR, IT outsourcing |
| Middle, Upper or Top Layer (excluding CICs) | Chapter V | Full governance, CISO, VA/PT cycles, DR drills, IS audit function, incident response |

Housing Finance Companies are covered too, because paragraph 3(1) includes NBFCs registered under the National Housing Bank Act, 1987. Under paragraph 141, they report cyber incidents to the NHB.

## What the 2023 Direction required, and what carried over

For Middle, Upper and Top Layer NBFCs, Chapter V keeps most of the 2023 requirements, often with the same numbers. Comparing the two texts:

| Requirement | 2023 Master Direction | 2026 Directions, Chapter V |
| --- | --- | --- |
| IT Strategy Committee | At least 3 directors; independent chair with substantial IT expertise (7 years); meets at least quarterly | Same (paras 70 to 73) |
| Head of IT Function | Aligns IT projects to policy; organisational structure; DR and BCP; first line of defence | Same duties (paras 78 to 80) |
| VA and PT | VA every 6 months, PT every 12 months for critical and DMZ systems; cloud “may” be included | Same cycle; cloud systems “shall” be included (paras 121 to 126) |
| DR drills | At least half-yearly for critical systems; at least a full working day on the DR site; minimal RTO, near zero RPO | Same (paras 127 to 138) |
| IS audit | IS Audit Policy approved by the Audit Committee of the Board and reviewed at least annually; risk-based; continuous auditing where possible | Same (paras 149 to 154) |
| Coverage | Middle, Upper and Top Layer only; CICs excluded | Every NBFC, in three tiers; CICs brought in under Chapter III |

What is different:

- Every NBFC is now covered by one text. Base Layer NBFCs and CICs were outside the 2023 Direction. They now have Chapters III and IV.
- Cloud is explicitly in scope for VA and PT. The 2023 wording said the VA/PT approach “may also apply” to systems hosted in the cloud. The 2026 wording says “This shall also apply to the NBFC’s information systems hosted in a cloud environment.”
- Incident reporting names the channel and the clock. Paragraphs 28 (Chapter IV) and 141 (Chapter V) require reporting to RBI “within six hours of detection” on DAKSH, the Reserve Bank’s Advanced Supervisory Monitoring System. Chapter V NBFCs must also “pro-actively notify” CERT-In. CERT-In’s own Directions of 28 April 2022 set a six-hour window for reportable incidents, so build one process that serves both.

[EXPERT QUOTE PLACEHOLDER: one or two sentences from a named BCT compliance lead on what NBFCs most often miss when moving from the 2023 Direction to the 2026 text. Gayatri decides; delete if none.]

## Control checklist for Middle, Upper and Top Layer NBFCs (Chapter V)

### Board and committees

- The Board approves strategies and policies for IT, information assets, business continuity, information security and cybersecurity, including incident response and cyber crisis management, and reviews them at least annually (paras 68 and 69).
- A Board-level IT Strategy Committee with at least three directors. The chair is an independent director with at least seven years of IT expertise. It meets at least quarterly and reviews BCP and DR adequacy at least annually (paras 70 to 73).
- An IT Steering Committee of senior IT and business management that meets quarterly.
- An Information Security Committee under the ITSC’s oversight, headed from the risk management vertical, with the CISO as a member. It reviews cyber incidents and IS audit observations (para 77).

### People

- A Head of IT Function (CTO or CIO) responsible for aligning IT projects to policy, the IT organisation, and the DR setup and BCP (paras 78 to 80).
- A CISO who is senior (preferably General Manager rank), does not report directly to the Head of IT, has no business targets and has a reasonable minimum term. The CISO manages the SOC, is a permanent invitee to the ITSC and the IT Steering Committee, reports to an Executive Director or equivalent overseeing risk management, and reviews cyber risk before the Board, the Risk Management Committee or the ITSC at least quarterly (paras 81 and 82).

### Testing and resilience

- Vulnerability assessment at least every six months and penetration testing at least every 12 months for critical systems and DMZ systems with a customer interface, including cloud-hosted systems. Testing also happens before and after implementation and after major changes, by trained and independent experts, with a documented approach that includes a scoring method such as CVSS and time-bound fixes (paras 121 to 126).
- DR drills for critical systems at least half-yearly, running at least a full working day on the DR site. Issues found are fixed and retested. Backups are restored periodically to check they work (paras 127 to 138).
- RTO and RPO defined for every critical system, with a minimal RTO approved by the ITSC and a near zero RPO. Where RPO is not zero, a documented reconciliation method (paras 127 to 138 and 147).
- DC and DR sites “geographically well separated”, with identical configurations and patches.
- Resilience testing with critical vendors and partners.

### Incidents, vendors and logs

- An incident response and recovery policy, root cause analysis, and reporting to RBI on DAKSH within six hours of detection, plus proactive notice to CERT-In (paras 139 to 144).
- For critical applications, source code or an escrow arrangement, and a vendor certificate that the application is free of known vulnerabilities, malware and covert channels, renewed on material changes (paras 104 to 106).
- A vendor risk assessment for third parties outside the outsourcing Directions, covering concentration risk, conflicts of interest, single points of failure, customer data, availability and supply chain risk (para 117).
- Audit logging for systems that handle critical or sensitive information, detailed enough for forensics and disputes, with regular review. Privileged users are supervised and their activity logged and reviewed (paras 109 to 111).

### IS audit

- An IS Audit Policy approved by the Audit Committee of the Board and reviewed at least annually, a separate IS audit function or skilled staff in Internal Audit, risk-based planning, and continuous auditing for critical systems where possible (paras 149 to 154).

## Control checklist for Base Layer NBFCs (Chapters III and IV)

### Base Layer below ₹500 crore, and CICs (Chapter III)

Chapter III is short. Paragraph 8 asks for a Board approved IT / IS policy built on nine standards. The IT systems must have:

- Physical and logical access controls and a well-defined password policy.
- Well-defined user roles.
- Maker-checker controls.
- Robust information security and cybersecurity controls.
- Rules for Digital Signature Certificates, Mobile Financial Services and Social Media (Chapter IV paras 31, 33 and 34 apply).
- System generated MIS reports for senior management on financial position, segment cost benefit and cost of funds.
- The ability to file regulatory returns with RBI.
- A Board approved BCP policy, with reports to the Board at least once a year.
- Data backup with periodic testing.

Paragraph 7 asks you to prioritise basic IT systems that digitise and secure your main business databases. Paragraph 9 asks you to scale IT up as the business grows. Chapter III sets no rules on an IT Strategy Committee, a CISO, VA/PT frequency, DR drills, IS audit or incident reporting. A Base Layer NBFC that is growing towards ₹500 crore should still plan for Chapter IV.

### Base Layer of ₹500 crore and above (Chapter IV)

- IT Strategy Committee: chaired by an independent director, with the CIO and CTO as members, and “not more than six months should elapse between two meetings”. It approves the IT strategy and policy and reviews IT risk, and its deliberations go to the Board (paras 15 and 16).
- CIO: a senior executive designated as CIO or in charge of IT operations. Chapter IV does not require a CISO.
- Vulnerability management: a process covered in the cybersecurity policy. Chapter IV sets no VA/PT frequency.
- BCP: a Board approved BCP policy, a business impact analysis, a recovery strategy and backup sites. The BCP is tested “at least annually and whenever significant IT or business changes occur”, with results and gap analysis reported to the CIO and the Board.
- IS audit: part of Internal Audit, under a framework approved by the Audit Committee of the Board, done “at least once in a year” and preferably before the statutory audit (paras 55 to 57).
- Incidents: reported on DAKSH within six hours of detection (para 28).
- IT outsourcing: a risk assessment before any outsourcing (para 60), and contracts that cover monitoring, data protection, access to books and records, right to audit, RBI access, and service provider logs of administrative activity that the NBFC can access.
- Audit trails for IT assets that support audit, forensics and dispute resolution, including records of unauthorised user activity.
- Returns and MIS: regulatory returns system-driven from the MIS, with read-only MIS access for RBI supervisors (para 46).

## What evidence will an RBI inspection ask for?

The Directions do not list evidence, but each requirement above leaves a record that a supervisor can ask to see. Keep these current and dated:

- Board minutes approving the technology and cybersecurity policies, and the annual review.
- ITSC, IT Steering Committee and Information Security Committee minutes that show the meeting frequency.
- The CISO’s appointment letter, reporting line and quarterly cyber risk papers (Chapter V).
- VA/PT reports with scores, owners, fix dates and retest results, including cloud systems.
- DR drill reports showing a full working day on the DR site, the RTO and RPO achieved, and retests of failed items.
- BCP test reports and the gap analysis sent to the Board.
- The IS Audit Policy, the audit plan, the IS audit report and Audit Committee minutes.
- DAKSH incident submissions, with detection and reporting times side by side, and CERT-In notices.
- Vendor contracts with audit rights, log access and RBI access clauses, plus vendor risk assessments.
- Audit trail and privileged access review records.

The Directions do not set a retention period for audit trails. Set one in your policy and apply it consistently.

## How continuous controls monitoring keeps this ready all year

Most of this checklist is periodic: quarterly committees, six-monthly VA and DR drills, yearly IS audits and Board reviews. NBFCs usually fall behind in the months between cycles. A drill slips by a month, a VA finding stays open, or a committee misses a quarter, and nobody sees it until the inspection.

[Continuous controls monitoring fixes](http://../continuous-controls-monitoring/) this by testing each control on a schedule, sending failures to a named owner and storing the evidence as it is created. [VControl](https://bluecoppertech.com/products/vcontrol?utm_source=github-pages&utm_medium=referral&utm_campaign=batch8-ghpages-rbi-nbfc), Blue Copper Technologies’ continuous compliance product, tracks RBI and CERT-In requirements alongside the DPDP Act, ISO 27001 and SOC 2 from one control set. [See the full list of supported compliance frameworks](https://bluecoppertech.com/products/vcontrol/compliance-frameworks?utm_source=github-pages&utm_medium=referral&utm_campaign=batch8-ghpages-rbi-nbfc).

## Limitations

This guide summarises the Directions. It does not reproduce every paragraph, and Chapter IV and Chapter V contain more detail than the checklists show.

RBI had published no FAQs or amendments to these Directions by 25 November 2026. Check the RBI page for later changes.

Your NBFC’s layer can change with asset size and RBI’s annual classification. Recheck which chapter applies after each change.

## FAQ

- What was the Master Direction, Information Technology Framework for the NBFC Sector? It was RBI’s 2017 IT rulebook for NBFCs (DNBS.PPD.No.04/66.15.001/2016-17, 8 June 2017). The repeal circular of 31 July 2026 lists it as repealed, and the 2026 Directions now cover the same ground.
- What is the difference between a master circular and a master direction? A master circular gathers RBI’s existing circulars on one subject into a single reference document. A master direction is the consolidated set of rules on a subject, and RBI updates it when the rules change. The 2026 NBFC text is issued as Directions in RBI’s new consolidated format.
- Is there a deadline to comply with the 2026 Directions? No separate deadline. They came into force with immediate effect on 31 July 2026.
- Do Base Layer NBFCs need a CISO under the 2026 Directions? Chapters III and IV do not require one. Chapter IV requires a senior executive designated as CIO or in charge of IT operations. Chapter V requires a CISO.
- How fast must an NBFC report a cyber incident to RBI? Within six hours of detection, on the DAKSH platform (paras 28 and 141). Housing Finance Companies report to the NHB.
- How often must an NBFC run an IS audit? Chapter IV says at least once a year, preferably before the statutory audit. Chapter V sets no fixed frequency. It requires a risk-based IS Audit Policy approved and reviewed at least annually by the Audit Committee of the Board.

## Next step

If you want to check your NBFC against the chapter that applies to it, [book a 30-minute call](https://calendly.com/bct-marketing-bluecoppertech/30min?utm_source=github-pages&utm_medium=referral&utm_campaign=batch8-ghpages-rbi-nbfc) with our team, or write to us through the [contact page](https://bluecoppertech.com/contact?utm_source=github-pages&utm_medium=referral&utm_campaign=batch8-ghpages-rbi-nbfc).

About the author. Gayatri Chakrabarty writes about continuous compliance, data protection and security operations at Blue Copper Technologies. See her profile on the [Blue Copper Technologies team page](https://bluecoppertech.com/company/team?utm_source=github-pages&utm_medium=referral&utm_campaign=batch8-ghpages-rbi-nbfc) or connect on [LinkedIn](https://www.linkedin.com/in/gayatri-chakrabarty/).

About Blue Copper Technologies. Founded in 2012 and headquartered in Kolkata, India, with an office in Gurugram, Blue Copper Technologies has delivered more than 300 solutions to over 150 customers in India, the USA, the UK, Europe and the Middle East. Its continuous compliance product, VControl, helps organisations stay audit-ready across global and Indian frameworks. The company is certified to ISO/IEC 27001:2022 and ISO 9001:2015.

Sources: [RBI NBFC Cybersecurity, Technology: Risk, Resilience and Assurance Framework Directions, 2026](https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=13592); [Repeal circular RBI/DoS/2026-27/221](https://www.rbi.org.in/scripts/BS_CircularIndexDisplay.aspx?Id=13663); [RBI Master Direction on IT Governance, Risk, Controls and Assurance Practices, 2023](https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=12562); [CERT-In Directions of 28 April 2022](https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf).

This guide is general information and is not legal advice. Check the current RBI text for your situation.
