---

title: Structure of the IETF Administrative Support Activity, Version 2.0
abbrev: IASA2
docname: draft-ietf-iasa2-rfc4071bis-latest
category: bcp
obsoletes: 4071, 4333, 7691

ipr: trust200902
area: General
keyword: Internet-Draft
wg: IASA2

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
  -
    ins: B. Haberman
    name: Brian Haberman
    organization: Johns Hopkins University
    email: brian@innovationslab.net
  -
    ins: J. Hall
    name: Joseph Lorenzo Hall
    organization: CDT
    email: joe@cdt.org
  -
    ins: J. Livingood
    name: Jason Livingood
    organization: Comcast
    email: jason_livingood@comcast.com

normative:
  I-D.ietf-iasa2-rfc2031bis:
  I-D.ietf-iasa2-rfc7437bis:
  
  IETF-LLC-A:
    title: Limited Liability Company Agreement of IETF Administration LLC
    author:
      org: The Internet Society
    date: 2018-08
    target: https://www.ietf.org/documents/180/IETF-LLC-Agreement.pdf

informative:
  RFC7691:
  RFC2026:
  RFC2850:
  RFC4071:
  RFC3710:
  RFC3233:
  RFC4333:
  I-D.ietf-mtgvenue-iaoc-venue-selection-process:
  I-D.haberman-iasa20dt-recs:
  I-D.ietf-iasa2-trust-update:

  ISOC:
    title: Amended and restated By-Laws of the Internet Society
    author:
      org: The Internet Society
    date: 2018-07
    target: https://www.internetsociety.org/about-internet-society/governance-policies/by-laws/

--- abstract

The IETF Administrative Support Activity (IASA) was originally
established in 2005.  In the years since then, the needs of the
IETF evolved in ways that required changes to its administrative
structure.  The purpose of this document is to document and describe 
the IASA 2.0 structure.

Under IASA 2.0, the work of the IETF's administrative and fundraising 
tasks is conducted by an administrative organization, the IETF Administration 
Limited Liability Company ("IETF LLC"). Under this structure, the IETF 
Administrative Oversight Committee (IAOC) was eliminated, and its oversight 
and advising functions transferred to the IETF LLC Board. 

The IETF LLC provides the corporate legal home for the IETF, the Internet 
Architecture Board (IAB), and the Internet Research Task Force (IRTF), and 
financial support for the operation of the RFC Editor.

This document describes the structure of the IETF Administrative
Support Activity, version 2 (IASA 2.0).  It defines the roles and
responsibilities of the IETF LLC Board, the IETF Executive Director,
and ISOC in the fiscal and administrative support of the IETF standards 
process.  It also defines the membership and selection rules for the IETF 
LLC Board.

This document obsoletes RFC 4071, RFC 4333, and RFC 7691.

--- middle

# Introduction

The IETF Administrative Support Activity (IASA) was originally
established in 2005.  In the years since then, the needs of the 
IETF evolved in ways that required changes to its administrative 
structure.  The purpose of this document is to document and describe
the IASA 2.0 structure. 

Under IASA 2.0, the work of the IETF's administrative and fundraising 
tasks is conducted by an administrative organization, the IETF Administration 
Limited Liability Company ("IETF LLC"). Under this structure, the Internet 
Administrative Oversight Committee (IAOC) is eliminated, and its oversight 
and advising functions transferred to the IETF LLC Board. 

The IETF LLC provides the corporate legal home for the IETF, the Internet 
Architecture Board (IAB), and the Internet Research Task Force (IRTF), and 
financial support for the operation of the RFC Editor.

{{I-D.haberman-iasa20dt-recs}} discusses the challenges facing the
original IASA structure as well as several options for reorganizing the
IETF's administration under different legal structures. This document
outlines how the chosen option is structured and describes how
the organization fits together with existing and new IETF
community structures.

Under IASA 2.0, most of the responsibilities that {{RFC4071}} assigned to 
the IETF Administrative Director (IAD) and the Internet Society (ISOC) were 
transferred to the IETF LLC and IETF Administration LLC Executive Director 
(IETF Executive Director). It is the job of the IETF LLC to meet the 
administrative needs of the IETF and to ensure that the IETF LLC meets the 
needs of the IETF community.

Eliminating the IAOC meant that changes were required in how
trustees could be appointed to the IETF Trust. The details of how this
is done are outside the scope of this document but are covered in
{{I-D.ietf-iasa2-trust-update}}.

This document obsoletes {{RFC4071}}, which specified the original IASA, 
{{RFC4333}}, which specified the selection guidelines and process for IAOC 
members and {{RFC7691}}, which specified terms for IAOC members.

# Scope Limitation

The document does not propose any changes related to the
standards process as currently conducted
by the Internet Engineering Steering Group (IESG) and Internet
Architecture Board (IAB). In addition, no changes are made to the appeals 
chain, the process for making and confirming IETF and IAB appointments, 
the technical work of the Internet Research Task Force (IRTF), or to 
ISOC's membership in or support of other organizations.

# LLC Agreement with the Internet Society

The LLC Agreement between the IETF LLC and ISOC is available 
at {{IETF-LLC-A}}. This IASA2 structure, and thus this document, 
depends on the LLC Agreement and will refer to it to help 
explain certain aspects of the legal
relationship between the IETF LLC and ISOC. 

The LLC Agreement was developed
between legal representatives of the IETF and ISOC and includes all
critical terms of the relationship, while still enabling maximum
unilateral flexibility for the IETF LLC Board.  The LLC Agreement includes only basic
details about how the Board manages itself or manages IETF LLC staff,
so that the Board has flexibility to make changes without amending
the agreement. The Board can independently develop policy or procedures
documents that fill gaps.

# Definitions and Principles

## Terminology

Although most of the terms, abbreviations, and acronyms used in this
document are reasonably well known, first-time readers may find some 
terminology confusing.  This section therefore attempts to provide a
quick summary.

IAB: Internet Architecture Board (see {{RFC2026}}, {{RFC2850}}).

IAD: IETF Administrative Director, a role obsoleted by this document
and the ISOC/IETF LLC Agreement ({{IETF-LLC-A}}) and replaced by the
IETF LLC Executive Director.

IAOC: IETF Administrative Oversight Committee, a committee that oversaw 
IETF administrative activity. The IAOC is obsoleted by this document and
replaced by the IETF LLC Board.  The IETF Trust was formerly populated by 
IAOC members. Its membership is now distinct from that of the IETF LLC 
Board (See {{I-D.ietf-iasa2-trust-update}}).)

IASA: The IETF Administrative Support Activity, consists of the IETF 
LLC board, employees, and contractors. Uses of the term 'IASA' as 
a proper noun may imply a subset of these roles, or all of them.

IASA 2.0: Version 2.0 of the IETF Administrative Support Activity,
defined by this document.

IESG: Internet Engineering Steering Group (see {{RFC2026}},
{{RFC3710}}).

IETF: Internet Engineering Task Force (see {{RFC3233}}).

IETF Administration LLC: The legal entity - a disregarded Limited Liability Company 
(LLC) of The Internet Society - established to provide a corporate legal framework 
for facilitating current and future activities related to the IETF, IAB, and IRTF. 
It was established by the ISOC/IETF LLC Agreement ({{IETF-LLC-A}}) and is referred 
to as "IETF LLC."


IETF LLC Executive Director: the Executive Director for the IETF LLC, responsible 
for day-to-day administrative and operational direction (See {{staff-responsibilities}}).
Also referred to as "IETF Executive Director". 

IETF LLC Board: The Board of Directors of the IETF LLC. The IETF LLC
Board is formally a multi-member "manager" of the IETF LLC on behalf
of ISOC (See {{board-responsibilities}}).

ISOC: Internet Society (see {{I-D.ietf-iasa2-rfc2031bis}} and {{ISOC}}).

## Key Differences From the Old IASA Structure to IASA 2.0

* The IAOC and IAD roles defined in RFC 4071 are eliminated.

* The former ISOC and IAD responsibilities are assigned to a new
  organization, IETF Administration LLC.

* The Board of Directors of the IETF LLC -- formally a multi-member "manager" of the IETF LLC on behalf of ISOC -- assumes the oversight responsibilities of the IAOC.

* The Board of the IETF LLC is more focused on strategy and oversight than the IAOC was, with the IETF Executive Director and their team in charge of day-to-day operations.

* The IAD role is replaced with the IETF Executive Director role.

* The role that was previously referred to as "IETF Executive
  Director" in older documents such as {{RFC2026}} is now "Managing
  Director, IETF Secretariat".

## General IETF LLC Responsibilities {#llc-responsibilities}

The IETF LLC is established to provide administrative support to the IETF. It has no authority over the standards development activities of the IETF.

The responsibilities of the IETF LLC are:

* Operations. The IETF LLC is responsible for supporting the ongoing operations of the IETF, including meetings and non-meeting activities.

* Finances. The IETF LLC is responsible for managing the IETF's finances and budget.

* Fundraising. The IETF LLC is responsible for raising money on behalf of the IETF.

* Compliance. The IETF LLC is responsible for establishing and enforcing policies to ensure compliance with applicable laws, regulations, and rules.

The manner by which these responsibilities under the IETF LLC are organized
is intended to address the problems described in Sections 3.1.1.,
3.1.2, and 3.1.3 of {{I-D.haberman-iasa20dt-recs}}.
Specifically, this is
intended to bring greater clarity around roles, responsibilities,
representation, decision-making, and authority.

In addition, by having the IETF LLC manage the IETF's finances and conduct the IETF's fundraising, confusion about who is responsible for representing the IETF to sponsors and who directs the uses of sponsorship funds should have been eliminated. Finally, having the IETF LLC reside in a defined, distinct legal entity, and taking responsibility for operations, enables the organization to execute its own contracts without the need for review and approval by ISOC.

## IETF LLC Working Principles {#principles}

The IETF LLC is expected to conduct its work according to the following principles:

* Transparency. The IETF LLC is expected to keep the IETF community informed about its work, 
subject to reasonable confidentiality concerns, and to engage with the community to obtain 
consensus-based community input on key issues and otherwise as needed. The IETF community expects 
complete visibility into the financial and legal structure of the IETF LLC. This includes information 
about the IETF LLC annual budget and associated regular financial reports, results of financial and any 
other independent audits, tax filings, significant contracts or other significant long-term financial 
commitments that bind the IETF LLC. Whatever doesn't have a specific 
justification for being kept confidential is expected to be made public. The Board is expected to develop 
and maintain a public list of confidential items, describing the nature of the information and the reason 
for confidentiality. The Board will also publish its operating procedures.

* Responsiveness to the community. The IETF LLC is expected to act consistently with the documented consensus of the IETF community, to be responsive to the community's needs, and to adapt its decisions in response to consensus-based community feedback.

* Diligence. The IETF LLC is expected to act responsibly so as to minimize risks to IETF participants and to the future of the IETF as a whole, such as financial risks.

* Unification: The IETF LLC provides the corporate legal home for the IETF, the Internet 
Architecture Board (IAB), and the Internet Research Task Force (IRTF), and 
financial support for the operation of the RFC Editor.

* Transfer or Dissolution: Consistent with {{IETF-LLC-A}}, the IETF LLC subsidiary may be transferred from ISOC to 
another organization, at the request of either party. Similarly, the IETF LLC may be dissolved if necessary. Should 
either event occur, the IETF community should be closely involved in any decisions and plans. Any transfer, 
transition, or dissolution should be conducted carefully and with minimal potential disruption to the IETF.

The transparency and responsiveness principles are designed to address the concern outlined in Section 3.3 of {{I-D.haberman-iasa20dt-recs}} about the need for improved timeliness of sharing of information and decisions and seeking community comments. The issue of increased transparency was important throughout the IASA 2.0 process, with little to no dissent.  It was recognized that there will naturally be confidentiality requirements about some aspects of contracting, personnel matters, and other narrow areas.

## Principles of the IETF and ISOC Relationship

The principles of the relationship between the IETF and ISOC are outlined in {{I-D.ietf-iasa2-rfc2031bis}}. 
In short, the IETF is responsible for the development of the Internet Standards and ISOC aids the IETF by 
providing it a legal entity within which the IETF LLC exists, as well as with financial support.

## Relationship of the IETF LLC Board to the IETF Leadership

The IETF LLC Board is directly accountable to the IETF community for the
performance of the IASA 2.0.  However, the nature of the Board's work
involves treating the IESG, IRTF, and IAB as major internal customers of the
administrative support services.  The Board and the IETF Executive Director should not
consider their work successful unless the IESG, IRTF, and IAB are also
satisfied with the administrative support that the IETF is receiving.

## Review of IETF Executive Director and IETF LLC Board Decisions
The IETF LLC Board is directly accountable to the IETF community for the performance of the IASA 2.0, including hiring and managing the IETF Executive Director. In extreme cases of dissatisfaction with the IETF LLC, the IETF community can utilize the recall process as noted in {{director-removal}}.

Anyone in the community of IETF participants may ask the Board for a formal review of a decision or action by the IETF Executive Director or Board if they believe this was not undertaken in accordance with IETF BCPs or IETF 
LLC Board policies and procedures.

A formal request for review must be addressed to the IETF LLC Board chair and must include a description of the decision or action to be reviewed, an explanation of how, in the requestor's opinion, the decision or action violates the BCPs or IASA 2.0 operational guidelines, and a suggestion for how the situation could be rectified.

The IETF LLC shall respond to such requests within a reasonable period, typically within 90 days, and shall publicly publish information about the request and the corresponding response and/or result.  

##  Termination and Change

Any major change to the IASA 2.0 arrangements shall require
community consensus and deliberation and shall be reflected by a
subsequent Best Current Practice (BCP) document.


# Structure of IASA2

## IETF Executive Director and Staff Responsibilities {#staff-responsibilities}

The IETF LLC is led by an IETF Executive Director chosen by the Board. The IETF Executive Director is responsible for managing the day-to-day operations of the IETF LLC, including hiring staff to perform various operational functions. The IETF Executive Director and any staff may be employees or independent contractors.

Allowing for the division of responsibilities among multiple staff members and contractors is designed to address some of the concerns raised in Section 3.2 (Lack of Resources) and Section 3.4 (Funding/Operating Model Mismatch and Rising Costs) of {{I-D.haberman-iasa20dt-recs}}.

Based on the amount of work previously undertaken by the IAD and others involved in the IETF administration, the design of the IETF LLC anticipated that the IETF Executive Director may need to hire multiple additional staff members. For example, resources to manage fundraising, to manage the various contractors that are engaged to fulfill the IETF's administrative needs, and to support outreach and communications were envisioned.

The IETF has historically benefitted from the use of contractors for accounting, finance, meeting planning, administrative assistance, legal counsel, tools, and web site support, as well as other services related to the standards process (RFC Editor and IANA). Prior to making the transition from IASA to IASA 2.0, the IETF budget reflected specific support from ISOC for communications and fundraising as well as some general support for accounting, finance, legal, and other services. The division of responsibilities between staff and contractors is at the discretion of the IETF Executive Director and their staff.

The IETF has a long history of community involvement in the execution of certain administrative functions, in particular development of IETF tools, the NOC's operation of the meeting network, and some outreach and communications activities conducted by the Education and Mentoring Directorate. The IETF LLC staff is expected to respect the IETF community's wishes about community involvement in these and other functions going forward as long as the staff feels that they can meet the otherwise-stated needs of the community. Establishing the framework to allow the IETF LLC to staff each administrative function as appropriate may require the IETF community to document its consensus expectations in areas where no documentation currently exists.

In summary, the IETF Executive Director, with support from the team that they alone direct and lead, is responsible for:

* Developing and refining an annual budget and other strategic financial planning documents at the direction of the Board.

* Executing on the annual budget, including reporting to the Board regularly with forecasts and actual performance to budget.

* Hiring and/or contracting the necessary resources to meet their goals, within the defined limits of the IETF 
Executive Director's authority and within the approved budget. This includes managing and leading any such 
resources, including performing regular performance reviews.

* Following the pre-approval guidelines set forth by the Board for contracts or other decisions that have financial costs that exceed a certain threshold of significance. Such thresholds are expected to be set reasonably high so that the need for such approvals is infrequent and only occurs when something is truly significant or otherwise exceptional. It is expected that the IETF Executive Director is sufficiently empowered to perform the job on a day-to-day basis, being held accountable for meeting high level goals rather than micromanaged.

* Regularly updating the Board on operations and other notable issues as reasonable and appropriate.

* Ensuring that all staff and/or other resources comply with any applicable policies established or approved by the Board, such as ethics guidelines and/or a code of conduct.


## IETF LLC Board Responsibilities {#board-responsibilities}

This section is intended to provide a summary of key IETF LLC Board responsibilities, 
but the precise and legally binding responsibilities are defined in the LLC Agreement 
{{IETF-LLC-A}} and applicable law. To the extent to which there are unintentional differences 
or other confusion between this document and these authoritative sources, these sources will 
control over this document.

Board members have fiduciary obligations imposed by the LLC Agreement and applicable law, 
including duties of loyalty, care and good faith. The Board is responsible to set broad strategic direction 
for the LLC, and adopt an annual budget, hire or terminate an 
IETF Executive Director (or amend the terms of their engagement), adopt any employee benefit plans, 
consult the relevant IETF communities on matters related to the LLC as appropriate, approve any 
changes to the LLC governance structure, incur any debt, and approve entering into agreements 
that meet a significant materiality threshold to be determined by the Board. The IETF LLC 
Board is expected to delegate management of day-to-day activities and related decision-making to staff.

Per Section 5(d) of the LLC Agreement and as also described in {{principles}}, the Board shall, 
as appropriate, act transparently and provide the IETF community with an opportunity to review 
and discuss any proposed changes to the IETF LLC structure prior to their adoption.

The role of the Board is to ensure that the strategy and conduct of the IETF LLC is consistent with the IETF's needs -- both its concrete needs and its needs for transparency and accountability.  The Board is not intended to directly define the IETF's needs; to the extent that is required, the IETF community should document its needs in consensus-based RFCs (e.g., as the community did in {{I-D.ietf-mtgvenue-iaoc-venue-selection-process}}) and provide more detailed input via consultations with the Board (such as takes place on email discussion lists or at IETF meetings).

Key IETF LLC Board responsibilities include:

* Set broad strategic direction for the LLC.

* Hire or terminate an IETF Executive Director (or amending the terms of their engagement).

* Delegate management of day-to-day activities and related decision-making to staff.

* Adopt any employee benefit plans.

* Consult the relevant IETF communities on matters related to the LLC, as appropriate.

* Approve any changes to the LLC governance structure.

* Adopt an annual budget and, as necessary, incur any debt.

* Prepare accurate and timely financial statements for ISOC, and in accordance with generally 
accepted accounting principles.

* Provide assistance to help facilitate ISOC’s tax compliance, including but not limited to assistance related to preparing the Form 990 and responding to any IRS questions and audits.

* Approve entering into agreements that that meet a significant materiality threshold to be 
determined by the Board. 

* Limit its activities to the purposes as set forth in Section 4 of the LLC Agreement, in a manner 
consistent with ISOC's charitable purposes.

* Establish an investment policy.

* Use best efforts to conduct all of its activities in strict compliance with the LLC Agreement and all 
applicable laws, rules and regulations.

* Ensure that IETF LLC is run in a manner that is transparent and accountable to the IETF community;

* Develop policies, including those noted in {{llc-policies}}), procedures, and a compliance program. 

* Obtain Commercial General Liability and other appropriate insurance policies, with
agreed-upon coverage limits.

* Recruit new Directors for consideration in all of the various appointment processes.

## Board Design Goals {#board-design-goals}

A goal of this Board composition is to balance the need for the IETF LLC to be accountable to the IETF community with the need for this Board to have the expertise necessary to oversee a small non-profit company. The Board is smaller than the previous IAOC and the other leadership bodies of the IETF, in part to keep the Board focused on its rather limited set of strategic responsibilities as noted in {{board-responsibilities}}.

This board structure, with limited strategic responsibilities noted in {{board-responsibilities}} and limited size, together with the staff responsibilities noted in {{staff-responsibilities}}, is designed to overcome the challenges described in Section 3.1.4 of {{I-D.haberman-iasa20dt-recs}} concerning oversight. This establishes a clear line of oversight over staff performance: the IETF LLC Board oversees the IETF Executive Director's performance and has actual legal authority to remove a non-performing IETF Executive Director. The IETF Executive Director is responsible for the day-to-day operation of the IETF LLC.

Finally, the Board would be expected to operate transparently, to further address the concern raised in Section 3.3 of {{I-D.haberman-iasa20dt-recs}}. The default transparency rule arrived at during the IASA 2.0 design process is detailed above in {{principles}}. The Board will need to establish how it will meet that commitment.

# IETF LLC Board Membership, Selection and Accountability {#board}

The section outlines the composition of the IETF LLC Board, selection of IETF LLC Board Directors, and related details.

## Board Composition {#board-composition}

There is a minimum of 5 directors, expandable to 6 or 7.

* 1 IETF Chair or delegate selected by the IESG

* 1 Appointed by the ISOC Board of Trustees

* 3 Selected by the IETF NomCom, confirmed by the IESG

* Up to 2 Appointed by the IETF LLC board itself, on an as-needed basis, confirmed by the IESG

For the first slot listed above, the presumption is that the IETF
Chair will serve on the board. At the IESG's discretion, another area
director may serve instead, or exceptionally the IESG may run a
selection process to appoint a director. The goal of having this slot
on the board is to maintain coordination and communication between the
board and the IESG.

## IETF LLC-Appointed Directors {#llc-directors}

As noted above, a maximum of two Directors may be appointed by the IETF LLC Board. They can obviously choose to appoint none, one, or two. These appointments need not be on an exceptional basis, but rather be routine, and may occur at any time of the year since it is on an as-needed basis.

The appointment of a Board-appointed Director requires a two-thirds majority vote of the Directors then in office, and the appointee shall take office immediately upon appointment. The term of each appointment is designated by the Board, with the maximum term being three years, or until their earlier resignation, removal or death.  The Board may decide on a case-by-case basis how long each term shall be, factoring in the restriction for consecutive terms in {{term-length}}.

## Recruiting IETF LLC Board Directors {#director-recruitment}

The Board itself is expected to take an active role in recruiting potential new Directors, regardless of the process that may be used to appoint them. In particular, the NomCom is primarily focused on considering requirements expressed by the Board and others, reviewing community feedback on candidates, conducting candidate interviews, and ultimately appointing Directors. The  Board and others can recruit potential Directors and get them into the consideration process of the NomCom or into open considerations processes of the other appointing bodies if those bodies choose to use such processes.

## IETF LLC Board Director Term Length {#term-length}

The term length for a Director is three years. The exceptions to this
guideline are:

* For the terms for some Directors during the first full formation of
  the IETF LLC Board in order to establish staggered terms and for any
  appointments to fill a vacancy.

* The Director slot occupied by the IETF Chair ex officio or a
  delegate selected by the IESG will serve a two-year term. This
  applies regardless of whether the appointed individual is on the
  IESG, rotates off the IESG during the two-year term, or is not on
  the IESG. This makes the term length for this slot the same as the
  term lengths established in [I-D.ietf-iasa2-rfc7437bis], Section
  3.4.

## IETF LLC Board Director Limit {#term-limit}

A director may serve no more than two consecutive terms. 
A director cannot serve a third term until three years have 
passed since their second consecutive term. An
exception is if a Director role is occupied by the IETF Chair ex
officio, since that person’s service is governed instead by the term
lengths established in {{I-D.ietf-iasa2-rfc7437bis}}, Section 3.4.

An exception to the two consecutive term rule is for an IETF LLC-appointed Director. For such a Director, they may serve only one term via this appointment method, after which any subsequent terms would be occur via other appointment or selection processes (such as via the NomCom process).

Lastly, partial terms of less than three years for the initial appointments to the first full board, for which some Directors will have terms of one or two years, do not count against the term limit.

The limit on consecutive terms supports the healthy regular introduction of new ideas and energy into the Board and mitigates potential long-term risk of ossification or conflict, without adversely impacting the potential pool of director candidates over time.

## Staggered Terms {#staggered-terms}

The Internet Society Board of Trustees, the IESG, the Nominating Committee, and the
Board are expected to coordinate with each other to ensure that
collectively their appointment or selection processes provide for no
more than three Directors’ terms concluding in the same year.

## IETF LLC Board Director Removal {#director-removal}

NomCom-appointed and IESG-appointed Directors may be removed with or without cause. A vote in favor of
removal must be no fewer than the number of Directors less two.  So
for example, if there are seven directors, then five votes are
required. Directors may also be removed via the IETF recall process
defined in {{I-D.ietf-iasa2-rfc7437bis}}, Section 7.

## Filling an IETF LLC Board Director Vacancy {#director-vacancy}

It shall be the responsibility of each respective body that appointed or selected a Director that vacates the Board 
to appoint a new Director to fill the vacancy.  For example, if a Director selected by the NomCom departs the Board 
prior to the end of their term for whatever reason, then it is the responsibility of the NomCom (using its mid-term 
rules, as specified in {{I-D.ietf-iasa2-rfc7437bis}}, Section 3.5) as the original appointing body to designate a 
replacement that will serve out the remainder of the term of the departed Director.  However, this obligation will 
not apply to vacancies in Board-appointed positions. 

## Quorum {#quorum}

At all meetings of the Board, two-thirds of the Directors then in office shall constitute 
a quorum for the transaction of business. Unless a greater affirmative vote is expressly required for 
an action under applicable law, the LLC Agreement, or an applicable Board policy, the affirmative vote of 
two-thirds of the Directors then in office shall be an act of the Board. 

## Board Voting {#voting}

Board decisions may be made either by vote communicated in a meeting of the Board (including telephonic and video), 
or via an asynchronous written (including electronic) process. Absentee voting and voting by proxy 
shall not be permitted. If a quorum is not present at any meeting of the Board, the Directors present may 
adjourn the meeting from time to time, without notice other than announcement at the meeting, until a quorum 
is present. Voting thresholds for Director removal are described in {{director-removal}}.

## Interim Board {#interim-board}

An initial interim Board was necessary in order to legally form and bootstrap the IETF LLC. As a result, an Interim Board was formed on a temporary basis until the first full board was constituted.

The interim Board was comprised of:

* The IETF chair, ex officio

* The IAOC chair, ex officio

* The IAB chair, ex officio

* One ISOC trustee, selected by the ISOC Board of Trustees

## Board Positions {#board-positions}

Following the formation of the first permanent Board, and annually thereafter, the Directors shall 
elect a Director to serve as Board Chair by majority vote. The IETF, IAB and IRTF chairs, and the 
chair of ISOC's Board, will be ineligible for this Board Chair role. The Board may also form committees 
of the Board and/or define other roles for Board Directors as necessary.

# IETF LLC Funding

The IETF LLC must function within a budget of costs balanced against limited revenues. The IETF community expects 
the IETF LLC to work to attain that goal, in order to maintain a viable support function that provides the 
environment within which the work of the IETF, IAB, IRTF, and RFC Editor can remain vibrant and productive.

The IETF LLC was generating income from a few key sources at the time that this document was written, as enumerated below. Additional sources of income may be developed in the future, within the general bounds noted in {{fundraising-practices}}, and some of these may decline in relevance or go away. As a result this list is subject to change over time and is merely an example of the primary sources of income for the IETF LLC at the time of this writing:

1.  ISOC support
2.  IETF meeting revenues
3.  Sponsorships (monetary and/or in-kind)
3.  Donations (monetary and/or in-kind)

## Financial Statements

As noted in {{board-responsibilities}}, the IETF LLC must comply with relevant tax laws, such as filing an annual
IRS Form 990. Other official financial statements may also be required. 

In addition to these official financial statements and forms, the IETF LLC is also expected to report on a regular basis 
to the IETF community on the current and future annual budget, budget forecasts vs. actuals over the course of a fiscal 
year, and on other significant projects as needed. This regular reporting to the IETF community is expected to be 
reported in the form of standard financial statements that reflect the income, expenses, assets, and liabilities of the 
IETF LLC.

## Bank and Investment Accounts

The IETF LLC maintains its own bank account, separate and distinct from ISOC. The IETF LLC 
may at its discretion create additional accounts as needed. Similarly, the IETF LLC may as needed create investment 
accounts in support of its financial goals and objectives.
   
## Financial Audits

The IETF LLC is expected to retain and work with an independent auditor. Reports from the auditor are expected to be shared with the IETF community and other groups and organizations as needed or as required by law.

## ISOC Financial Support

ISOC currently provides significant financial support to the IETF LLC. Exhibit B of the {{IETF-LLC-A}} 
summarizes the financial support from ISOC for the foreseeable future. It is expected that this support 
will be periodically reviewed and revised, via a cooperative assessment process between ISOC and 
the IETF LLC.

## IETF Meeting Revenues

Meeting revenues are another important source of funding that supports the IETF, coming mainly from the fees paid 
by IETF meeting participants. The IETF Executive Director sets those meeting fees, in consultation with other IETF 
LLC staff and the IETF community, with approval by the IETF LLC Board. Setting these fees and projecting the number 
of participants at future meetings is a key part of the annual budget process.  

## Sponsorships and Donations to the IETF LLC

Sponsorships and donations are an essential component of the financial support for the IETF. Within the general 
bounds noted in {{fundraising-practices}}, the IETF LLC is responsible for fundraising activities in order 
to establish, maintain, and grow a strong foundation of donation revenues. This can and does include both 
direct financial contributions as well as in-kind contributions, such as equipment, software licenses, and services. 

Sponsorships and donations to the IETF LLC do not (and must not) convey to sponsors and donors any special oversight 
or direct influence over the IETF's technical work or other activities of the IETF or IETF LLC. This helps 
ensure that no undue influence may be ascribed to those from whom funds are raised, and so helps to maintain 
an open and consensus-based IETF standards process.

To the extent that the IETF LLC needs to undertake any significant special projects for the IETF, the IETF LLC 
may need to fundraise distinctly for those special projects. As a result, the IETF LLC may conduct fundraising to support 
the IETF in general as well as one or more special fundraising efforts (which may also be accounted for distinctly and be held in a separate bank account or investment, as needed).

## Focus of Funding Support

The IETF LLC exists to support the IETF, IAB, and IRTF.  Therefore, the IETF LLC's funding and all revenues, 
in-kind contributions, and other income that comprise that funding shall be used solely to support activities 
related to the IETF, IAB, IRTF, and RFC Editor, and for no other purposes.

## Charitable Fundraising Practices {#fundraising-practices}

When the IETF LLC conducts fundraising, it substantiates charitable
contributions on behalf of ISOC -- meaning that according to US tax
law, the IETF LLC must send a written acknowledgment of contributions
to donors. The IETF LLC evaluates and facilitates state, federal, and
other applicable law and regulatory compliance for ISOC and/or the LLC
with respect to such fundraising activities. In addition, the IETF LLC
ensures that all fundraising activities are conducted in compliance
with any policies developed by the IETF LLC, including but not limited
to those noted in {{llc-policies}}.

## Operating Reserve

An initial target operating reserve has been specified in Exhibit B of the {{IETF-LLC-A}}.  That says that the IETF LLC 
should maintain an operating reserve equal to the IETF LLC’s budgeted Net Loss for 2019 multiplied times three. The IETF 
LLC, in cooperation with ISOC, may regularly review the financial target for this reserve fund, as noted in the {{IETF-LLC-A}} or as otherwise necessary.

Should the IETF LLC generate an annual budget surplus, it may choose to direct all or part of the surplus towards 
the growth of the operating reserve.

## Annual Budget Process

As noted in {{llc-responsibilities}}, the IETF LLC is responsible for managing the IETF's finances and budget. 
A key part of this responsibility is establishing, maintaining, and successfully meeting an annual budget. This 
is essential to the continued operation and vibrancy of the IETF's technical activities and establishes trust 
with ISOC, sponsors, and donors that funds are being appropriately spent, and that financial oversight is being conducted 
properly. This is also essential to the IETF LLC meeting applicable legal and tax requirements and is a core part of 
the Board's fiduciary responsibilities. 

As explained in {{staff-responsibilities}}, the IETF Executive Director is expected to develop, execute, and report on the 
annual budget. Regular reporting is expected to include forecast vs. budget statements, including updated projections of income and expenses for the full fiscal year. 

The Board, as explained in {{board-responsibilities}}, is expected to review and approve the 
budget, as well as to provide ongoing oversight of the budget and of any other significant financial matters. 

The annual budget is expected to be developed in an open, transparent, and collaborative manner, in accordance with 
{{principles}}. The specific timeline for the development, review, and approval of the IETF LLC annual budget is established by the Board and may be revised as needed. 

# IETF LLC Policies {#llc-policies}

The Board is expected to maintain policies as necessary to achieve the
goals of the IETF LLC, meet transparency expectations of the
community, comply with applicable laws or regulations, or for other
reasons as appropriate. All policies are expected to be developed with
input from the IETF community. Some policies provided by ISOC and
past policies developed by the previous IAOC may
provide a useful starting point for the Board to consider.

## Conflict of Interest Policy {#conflict-of-interest}

The Board is expected to maintain a Conflict of Interest policy for the IETF LLC. While the details are determined by the Board, at a minimum such policy is expected to include the following:

* The IETF, ISOC Board, IAB, or IRTF chair cannot be chair of the IETF LLC Board, though they may serve as a Director.

* A Director cannot be a paid consultant or employee of the IETF Executive Director or their sub-contractors, nor a paid consultant or employee of ISOC.

## Other Policies {#other-policies}

The Board is expected to maintain additional policies for the IETF LLC as necessary, covering Directors, employees, and contractors, concerning issues such as:

* Acceptance of gifts and other non-cash compensation;

* Travel and expense reimbursement;

* Anti-bribery;

* Code of conduct;

* Anti-harassment;

* Non-discrimination;

* Whistleblower;

* Document retention;

* Export controls;

* Anti-terrorism sanctions;

* Data protection and privacy;

* Social media

## Compliance {#compliance}

The IETF LLC is expected to implement a compliance program to ensure its compliance with all applicable laws, rules and regulations, including without limitation laws governing bribery, anti-terrorism sanctions, export controls, data protection/privacy, as well as other applicable policies noted in {{llc-policies}}. In addition, actions and activities of the IETF LLC must be consistent with 501(c)(3) purposes.

The IETF LLC is expected report to ISOC and the IETF community on the implementation of its compliance plan on an annual basis.

# Three-Year Assessment

The IETF LLC, with the involvement of the community, shall conduct and complete an assessment of the structure, processes, and operation of IASA 2.0 and the IETF LLC. This should be presented to the community after a period of roughly three years of operation. The assessment may potentially include recommendations for improvements or changes to the IASA2 and/or IETF LLC.

# Security Considerations

This document describes the structure of the IETF's Administrative
Support Activity (IASA), version 2 (IASA2).  It introduces no security considerations
for the Internet.

# IANA Considerations

This document has no IANA considerations in the traditional sense.
However, some of the information in this document may affect how the
IETF standards process interfaces with the IANA, so the IANA may be
interested in the contents.

# Pronouns

This document has used "they" and "their" as a non-gender-specific pronoun to refer to a single individual.

# Acknowledgments

Thanks to Jari Arkko, Richard Barnes, Brian E Carpenter, Alissa
Cooper, John C Klensin, Bob Hinden, Jon Peterson, Sean Turner and the
IASA2 Working Group for discussions of possible structures, and to the
attorneys of Morgan Lewis and Brad Biddle for legal advice.
