---

title: Structure of the IETF Administrative Support Activity, Version 2.0
abbrev: IASA2
docname: draft-ietf-iasa2-struct-latest
category: bcp
obsoletes: RFC4071, RFC4333, RFC7691

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

informative:
  RFC7437:
  RFC8318:
  RFC2026:
  RFC2850:
  RFC4071:
  RFC2031:
  RFC3710:
  RFC3233:

  IETF-LLC-A:
    title: Limited Liability Company Agreement of IETF Administration LLC
    author:
      org: The Internet Society
    date: 2018-08
    target: https://www.ietf.org/documents/180/IETF-LLC-Agreement.pdf

  ISOC:
    title: Amended and restated By-Laws of the Internet Society
    author:
      org: The Internet Society
    date: 2018-07
    target: https://www.internetsociety.org/about-internet-society/governance-policies/by-laws/

  ML-memo:
    title: Options for New Organization to Conduct IETF Administrative Support Activities
    author:
      org: Morgan Lewis
    date: 2018-02
    target: https://mailarchive.ietf.org/arch/msg/iasa20/XT_3vfd3OWVFCW335mRrvWuusaI/

  ietf101-slides:
    title: IASA 2.0 IETF-101 Slides
    author:
      name: Joseph Lorenzo Hall
      ins: J.L. Hall
    dates: 2018-03-20
    target: https://datatracker.ietf.org/meeting/101/materials/slides-101-iasa20-dt-iasa-slides-00

  ietf102-slides:
    title: IASA 2.0 IETF-102 Slides
    author:
      name: Joseph Lorenzo Hall
      ins: J.L. Hall
    dates: 2018-07-18
    target: https://datatracker.ietf.org/meeting/102/materials/slides-102-iasa2-iasa2-structure-draft-00

--- abstract

The IETF Administrative Support Activity (IASA) was originally
established in 2005.  In the years since that time, the needs of the
IETF evolved in ways that required changes to its administrative
structure.  The purpose of this document is to describe the structure
of a IASA 2.0 and to document the decisions made by the IETF community
in making the transition from IASA to IASA 2.0.

In IASA 2.0, the IETF's administrative and fundraising tasks are conducted by
an administrative organization, the IETF Administration Limited
Liability Company (IETF LLC), a disregarded LLC of the Internet Society
(ISOC). Under the structure, the Internet Administrative Oversight
Committee (IAOC) and the IETF Administrative Director (IAD) position were
eliminated, and the corresponding oversight and administrative
functions transferred to the new IETF Administration LLC Board of
Directors (IETF LLC
Board) and the IETF LLC Executive Director (IETF Executive Director),
respectively.

This document describes the structure of the IETF Administrative
Support Activity, version 2 (IASA 2.0).  It defines the roles and
responsibilities of the IETF LLC Board, the IETF 
Executive Director, and ISOC in the fiscal
and administrative support of the IETF standards process.  It also
defines the membership and selection rules for the IETF LLC Board.

--- middle

# Introduction

The IETF Administrative Support Activity (IASA) was originally
established in 2005.  In the years since 2005, the needs of
the IETF evolved in ways that required changes to its
administrative structure.  The purpose of this document is to document
and describe
the IASA 2.0 structure. Under IASA 2.0, the work of
the IETF's administrative and fundraising tasks is conducted by an administrative organization, the IETF Administration Limited
Liability Company ("IETF LLC"). Under this structure, the Internet
Administrative Oversight Committee (IAOC) was eliminated, and its
oversight and advising functions transferred to the IETF LLC
Board. 

{{?I-D.haberman-iasa20dt-recs}} discusses the challenges facing the
original IASA structure as well as several options for reorganizing the
IETF's administration under different legal structures. This document
outlines how the chosen option is structured and describes how
the organization fits together with existing and new IETF
community structures.

The point of the IASA2 WG and process has been to solicit community
input about how to address the challenges identified in
{{?I-D.haberman-iasa20dt-recs}}, and included much debate on the IASA2
mailing list and the IASA2 working group meetings at IETF 101
{{ietf101-slides}} and IETF 102 {{ietf102-slides}}.

This document obsoletes RFC 4071, which specified the original IASA, and RFC 7691, which specified terms for IAOC members.

Under IASA 2.0, most of the
responsibilities that RFC 4071 assigned to the IETF
Administrative Director (IAD) and the Internet Society (ISOC) were transferred to the IETF LLC and IETF Administration LLC Executive
Director (IETF Executive Director).
It is the job of the IETF 
LLC to meet the administrative needs of the IETF and to ensure that the IETF LLC
meets the needs of the IETF community.

Eliminating the IAOC meant that changes were required in how
trustees could be appointed ro the IETF Trust. The details of how this
is done are outside the scope of this document but are covered in
{{?I-D.ietf-iasa2-trust-update}}.

# Scope Limitation

The document does not propose any changes to anything related to the
oversight or steering of the standards process as currently conducted
by the Internet Engineering Steering Group (IESG) and Internet
Architecture Board (IAB), the appeals chain, the process for making
and confirming IETF and IAB appointments, the IETF Nominating
Committee (NomCom), the Internet Research Task Force (IRTF), or ISOC's
memberships in or support of other organizations.

## LLC Agreement with the Internet Society

The LLC Agreement between the IETF LLC and ISOC {{IETF-LLC-A}}
is also out
of scope for this document, however this document depends on
the LLC Agreement and will refer to it for certain aspects of the legal
relationship between the IETF LLC and ISOC. The LLC Agreement was developed
between legal representatives of the IETF and ISOC and includes all
critical terms of the relationship, while still enabling maximum
unilateral flexibility for the IETF LLC Board.  The LLC Agreement includes only basic
details about how the IETF LLC Board manages itself or manages IETF LLC staff,
so that the IETF LLC Board has flexibility to make changes without amending
the agreement. The IETF LLC Board can independently develop policy or procedures
documents that fill gaps.

# Definitions and Principles

## Alphabet Soup

Although most of the terms, abbreviations, and acronyms used in this
document are reasonably well known, first-time readers may find this
alphabet soup confusing.  This section therefore attempts to provide a
quick summary.

IAB: Internet Architecture Board (see {{RFC2026}}, {{RFC2850}}).

IAD: IETF Administrative Director, a role obsoleted by this document
and the ISOC/IETF LLC Agreement ({{IETF-LLC-A}}) and replaced by the
IETF LLC Executive Director.

IAOC: IETF Administrative Oversight Committee, a committee that oversaw
IETF administrative activity, obsoleted by this document and replaced
by the IETF LLC Board.

IASA: The original IETF Administrative Support Activity, defined by
{{RFC4071}} and obsoleted by this document and the ISOC/IETF LLC
Agreement ({{IETF-LLC-A}}).

IASA 2.0: Version 2.0 of the IETF Administrative Support Activity,
defined by this document.

IESG: Internet Engineering Steering Group (see {{RFC2026}},
{{RFC3710}}).

IETF: Internet Engineering Task Force (see {{RFC3233}}).

IETF Administration LLC: The legal entity -- a disregarded Limited Liability Company

(LLC) of The Internet Society -- established to house IASA2, specified
by the ISOC/IETF LLC Agreement ({{IETF-LLC-A}}). Also referred to as "IETF LLC" or just the "LLC".

IETF LLC Executive Director: the executive director for the IETF
Administration Limited Liability Company, responsible for day-to-day administrative
and operational direction (See {{staff-responsibilities}}).
Also referred to as "IETF Executive Director".
(Note that
the title of "IETF Executive Director" in older documents such as
{{RFC2026}} is now "Managing Director, IETF Secretariat".)

IETF LLC Board: The Board of Directors of the IETF LLC -- formally a
multi-member "manager" of the IETF LLC on behalf of ISOC (See
{{board-responsibilities}}).

ISOC: Internet Society (see {{RFC2031}} and {{ISOC}}).

## Key Differences From the Old IASA Structure to IASA 2.0

* The IAOC and IAD roles defined in RFC 4071 were eliminated.

* The former ISOC and IAD responsibilities were assigned to a new
  organization, IETF Administration LLC.

* The Board of Directors of the IETF LLC -- formally a multi-member "manager" of the IETF LLC on behalf of ISOC -- assumed the oversight responsibilities of the IAOC.

* The Board of the IETF LLC is more focused on strategy and oversight than the IAOC was, with the IETF Executive Director and their team in charge of day-to-day operations.

* The IAD role was replaced with the IETF Executive Director role.

* The role that was previously referred to as "IETF Executive
  Director" in older documents such as {{RFC2026}} was replaced with "Managing
  Director, IETF Secretariat".

## General IETF LLC Responsibilities {#llc-responsibilities}

The IETF LLC was established to provide administrative support to the IETF. It has no authority over the standards development activities of the IETF.

The responsibilities of the IETF LLC are:

* Operations. The IETF LLC is responsible for supporting the ongoing operations of the IETF, including meetings and non-meeting activities.

* Finances. The IETF LLC is responsible for managing the IETF's finances and budget.

* Fundraising. The IETF LLC is responsible for raising money on behalf of the IETF.

* Compliance. The IETF LLC is responsible for establishing and enforcing policies to ensure compliance with applicable laws, regulations, and rules.

The manner by which these responsibilities under the IETF LLC are organized
is intended to address the problems described in Sections 3.1.1.,
3.1.2, and 3.1.3 of {{?I-D.haberman-iasa20dt-recs}}.
Specifically, this is
intended to bring greater clarity around roles, responsibilities,
representation, decision-making, and authority.

In addition, by having the IETF LLC manage the IETF's finances and conduct the IETF's fundraising, confusion about who is responsible for representing the IETF to sponsors and who directs the uses of sponsorship funds should have been eliminated. Finally, having the IETF LLC reside in a defined, distinct legal entity, and taking responsibility for operations, enables the organization to execute its own contracts without the need for review and approval by ISOC.

## IETF LLC Working Principles {#principles}

The IETF LLC is expected to conduct its work according to the following principles, subject to any reasonable confidentiality obligations:

* Transparency. The IETF LLC is expected to keep the IETF community informed about its work and to engage with the community to obtain consensus-based community input on key issues and otherwise as needed. The IETF community expects complete visibility 
into the financial and legal structure of the IETF LLC. This includes information about the IETF LLC annual budget and associated regular financial reports, results of financial and any other independent audits, tax filings, significant contracts or other significant long-term financial commitments that bind the IETF LLC. As discussed in {{ietf101-slides}}, 
whatever doesn't have a specific justification for being kept confidential is expected to be made public. The IETF LLC Board 
is expected to develop and maintain a public list of confidential items, describing the nature of the information and the reason for confidentiality. 

* Responsiveness to the community. The IETF LLC is expected to act consistently with the documented consensus of the IETF community, to be responsive to the community's needs, and to adapt its decisions in response to consensus-based community feedback.

* Diligence. The IETF LLC is expected to act responsibly so as to minimize risks to IETF participants and to the future of the IETF as a whole, such as financial risks.

* Unification: The IETF IETF LLC is reponsible for providing unified legal, financial, and administrative support for 
operation of the IETF, IAB, IESG, IRTF, and RFC Editor.

* Transfer or Dissolution: Consistent with {{IETF-LLC-A}}, the IETF LLC subsidiary may be transferred from ISOC to 
another organization, at the request of either party. Similarly, the IETF LLC may be dissolved if necessary. Should 
either event occur, the IETF community should be closely involved in any decisions and plans, and any tranfer, 
transition, or dissolution conducted carefully and with minimal potential disruption to the IETF.

The transparency and responsiveness principles are designed to address the concern outlined in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}} about the need for improved timeliness of sharing of information and decisions and seeking community comments. The issue of increased transparency was important throughout the IASA 2.0 process, with little to no dissent.  It was recognized that there will naturally be a confidentiality requirement about some aspects of hotel contracting, personnel matters, and other narrow areas.

## Principles of the IETF and ISOC Relationship

ISOC and the IETF have historically been philosophically aligned. The principles of the relationship between the 
IETF and ISOC are outlined in {{?I-D.ietf-iasa2-rfc2031bis}}. ISOC's connection with the IETF community has always 
played an important role in its policy work. ISOC has always been an advocate for multistakeholder processes, which 
includes the technical community.  Open standards are an explicit part of one of the focus areas in ISOC's mission: Advancing the development and application of Internet infrastructure, technologies, and open standards.

On a practical level, the IETF LLC is a distinct entity (a disregarded entity) of ISOC. The IETF remains responsible 
for the development and quality of the Internet Standards.  ISOC aids the IETF by providing it a legal entity 
within which the IETF LLC exists, as well as with financial support. ISOC has no influence whatsoever on the 
technical content of Internet Standards.

## Relationship of the IETF LLC Board to the IETF Leadership

The IETF LLC Board is directly accountable to the IETF community for the
performance of the IASA 2.0.  However, the nature of the IETF LLC Board's work
involves treating the IESG and IAB as major internal customers of the
administrative support services.  The IETF LLC Board and the IETF Executive Director should not
consider their work successful unless the IESG and IAB are also
satisfied with the administrative support that the IETF is receiving.

## IETF LLC Board Decision Making

The IETF LLC Board attempts to reach consensus on all decisions.  If the
IETF LLC Board cannot achieve a consensus decision, then the IETF LLC Board may
decide by voting.

The IETF LLC Board decides the details about its decision-making rules,
including its rules for quorum (see {{quorum}}), conflict of interest
(see {{conflict-of-interest}}), and breaking of ties. These rules
are expected to be public.

All IETF LLC Board decisions are expected to be recorded in IETF LLC Board minutes, and
IETF LLC Board minutes are expected to be published in a timely fashion.

## Review and Appeal of IETF Executive Director and IETF LLC Board Decisions

The IETF LLC Board is directly accountable to the IETF community for the
performance of the IASA 2.0.  In order to achieve this, the IETF LLC Board and IETF Executive Director
are expected to ensure that guidelines are developed for regular operational
decision making.  Where appropriate, these guidelines should be
developed with public input.  In all cases, they must be made public.

If a member of the IETF community questions whether a decision or
action of the IETF Executive Director or the IETF LLC Board has been undertaken in accordance with
IETF BCPs or IASA 2.0 operational guidelines, or questions whether the IETF LLC has created and maintained appropriate guidelines, he or she may
ask the IETF LLC Board for a formal review of the decision or action.

The request for review should be addressed to the IETF LLC Board chair and
should include a description of the decision or action to be reviewed,
an explanation of how, in the requestor's opinion, the decision or
action violates the BCPs or operational guidelines, and a suggestion
for how the situation could be rectified.  All requests for review
shall be posted publicly, and the IETF LLC Board is expected to respond publicly to these
requests within a reasonable period, typically within 90 days.  It is
up to the IETF LLC Board to determine what type of review and response is
required, based on the nature of the review request.  Based on the
results of the review, the IETF LLC Board may choose to overturn their own
decision, to change their operational guidelines to prevent further
misunderstandings, to take other action as appropriate, or just to
publish the review result and take no other action.

If a member of the community is not satisfied with the IETF LLC Board's response
to his or her review request, he or she may escalate the issue by
appealing the decision or action to the IAB, using the appeals
procedures outlined in {{RFC2026}}.  If he or she is not satisfied
with the IAB response, he or she can escalate the issue to the ISOC
Board of Trustees, as described in {{RFC2026}}. 

The reviewing body (the IAB or ISOC Board of Trustees) shall review
the decision of the IETF Executive Director or IETF LLC Board to determine whether it was made in
accordance with existing BCPs and operational guidelines.  As a result
of this review, the reviewing body may recommend to the community that
the BCPs governing IETF LLC Board actions should be changed.  The reviewing body
may also advise the IETF LLC Board to modify existing operational guidelines to
avoid similar issues in the future and/or it may advise the IETF LLC Board to
re-consider their decision or action.  It may also recommend that no
action be taken, based on the review.

In exceptional cases, when no other recourse seems reasonable, the
reviewing body may overturn or reverse a non-binding decision or
action of the IETF LLC Board.  This should be done only after careful
consideration and consultation with the IETF LLC Board regarding the
ramifications of this action.  In no circumstances may the IAB or ISOC
Board of Trustees overturn a decision of the IETF LLC Board that involves a
binding contract or overturn a personnel-related action (such as
hiring, firing, promotion, demotion, performance reviews, salary
adjustments, etc.).

## Community Consensus and Grant of Authority

The IETF is a consensus-based group, and authority to act on behalf of
the community requires a high degree of consensus and the continued
consent of the community.  After a careful process of deliberation, a
broad-based community consensus emerged to house the administration of the 
IETF within the IETF LLC as a disregarded entity of the Internet Society. 
This document reflects that consensus.

##  Termination and Change

Any major change to the IASA 2.0 arrangements shall require a similar level of
community consensus and deliberation and shall be reflected by a
subsequent Best Current Practice (BCP) document.


# Structure of the IASA2

## IETF Executive Director and Staff Responsibilities {#staff-responsibilities}

The IETF LLC is led by an IETF Executive Director chosen by the Board. The IETF Executive Director is responsible for managing the day-to-day operations of the IETF LLC, including hiring staff to perform various operational functions. The IETF Executive Director and any staff may be employees or independent contractors.
(Note: The is the Executive Director of the IETF LLC, not the "IETF Executive Director" mentioned in some older documents (e.g., {{RFC2026}}), which is currently known as "Managing Director, IETF Secretariat.")

Allowing for the division of responsibilities among multiple staff members and contractors is designed to address some of the concerns raised in Section 3.2 (Lack of Resources) and Section 3.4 (Funding/Operating Model Mismatch and Rising Costs) of {{?I-D.haberman-iasa20dt-recs}}.

Based on the amount of work previously undertaken by the IAD and others involved in the IETF administration, the design of the IETF LLC anticipated that the IETF Executive Director may need to hire multiple additional staff members. For example, resources to manage fundraising, to manage the various contractors that are engaged to fulfill the IETF's administrative needs, and to support outreach and communications were envisioned.

The IETF has historically benefitted from the use of contractors for accounting, finance, meeting planning, administrative assistance, legal counsel, tools, and web site support, as well as other services related to the standards process (RFC Editor and IANA). Prior to making the transition from IASA to IASA 2.0, the IETF budget reflected specific support from ISOC for communications and fundraising as well as some general support for accounting, finance, legal, and other services. The division of responsibilities between staff and contractors is at the discretion of the IETF Executive Director and his or her staff.

The IETF has a long history of community involvement in the execution of certain administrative functions, in particular development of IETF tools, the NOC's operation of the meeting network, and some outreach and communications activities conducted by the Education and Mentoring Directorate. The IETF LLC staff is expected to respect the IETF community's wishes about community involvement in these and other functions going forward as long as the staff feels that they can meet the otherwise-stated needs of the community. Establishing the framework to allow the IETF LLC to staff each administrative function as appropriate may require the IETF community to document its consensus expectations in areas where no documentation currently exists.

In summary, the IETF Executive Director, with support from the team that they alone direct and lead, is responsible for:

* Developing and refining an annual budget and other strategic financial planning documents at the direction of the IETF LLC Board.

* Executing on the annual budget, including reporting to the IETF LLC Board regularly with forecasts and actual performance to budget.

* Hiring and/or contracting the necessary resources to meet their goals, within the defined limits of their authority and within the approved budget. This includes managing and leading any such resources, including performing regular performance reviews.

* Following the pre-approval guidelines set forth by the IETF LLC Board for contracts or other decisions that have financial costs that exceed a certain threshold of significance. Such thresholds are expected to be set reasonably high so that the need for such approvals is infrequent and only occurs when something is truly significant or otherwise exceptional. It is expected that the IETF Executive Director is sufficiently empowered to perform their job on a day-to-day basis, being held accountable for meeting high level goals rather than micromanaged.

* Regularly updating the IETF LLC Board on operations and other notable issues as reasonable and appropriate.

* Ensuring that all staff and/or other resources comply with any applicable policies established or approved by the IETF LLC Board, such as ethics guidelines and/or a code of conduct.


## IETF LLC Board Responsibilities {#board-responsibilities}

The IETF LLC Board is responsible for conducting oversight of the IETF LLC's execution of its responsibilities, as described in {{llc-responsibilities}}.  They have duties of loyalty, care, and good faith. This includes the responsibility to:

* provide strategic direction for the IETF LLC to the IETF Executive Director;

* hire, supervise, and manage the employment of the role of the IETF Executive Director of the IETF LLC, including tasks such as hiring, termination, performance review, amendment of employment terms, the award of compensation and other requisite employment benefits or decisions;

* adopting any employee benefit plans;

* approving any changes to the IETF LLC governance structure;

* exercising a fiduciary duty to ensure that IETF LLC has the financial and business stability that it needs to be able to meet the needs of the IETF, including adopting an annual budget, and as necessary incurring any debt or making other financial arrangements;

* approving or entering into agreements that meet a significant materiality threshold;

* exercising a legal duty to ensure that the IETF LLC complies with any applicable tax and other laws;

* ensuring that IETF LLC is run in a manner that is transparent and accountable to the IETF community;

* recruiting new Directors, for consideration in all of the various appointment processes.

The IETF LLC Board is an oversight body, with responsibilities limited to those listed above. It does not directly conduct any of the IETF's administrative work, which is the day-to-day job of the IETF Executive Director and their team.

The role of the IETF LLC Board is to ensure that the strategy and conduct of the IETF LLC is consistent with the IETF's needs -- both its concrete needs and its needs for transparency and accountability.  The Board is not intended to directly define the IETF's needs; to the extent that is required, the IETF community should document its needs in consensus-based RFCs (e.g., as the community did in {{?I-D.ietf-mtgvenue-iaoc-venue-selection-process}}) and provide more detailed input via consultations with the IETF LLC Board (such as takes place on email discussion lists or at IETF meetings).

As part of the responsibilities outlined above the Board is expected to work to ensure that IETF LLC:

* Acts consistently with ISOC’s 501(c)(3) status;

* Provides accurate financial statements to ISOC on a timely basis;

* Prepares its financial reports in accordance with generally accepted accounting principles;

* Provides assistance to help facilitate ISOC’s tax compliance, including but not limited to assistance related to preparing the Form 990 and responding to any IRS questions and audits;

* Obtains appropriate insurance, including commercial general liability insurance with appropriate limits;

* Implements risk management and compliance processes in a manner consistent with industry norms.

The description below outlines the composition of the IETF LLC Board, selection of IETF LLC Board Directors, and related details.

## Board Design Goals {#board-design-goals}

A goal of this Board composition is to balance the need for the IETF LLC to be accountable to the IETF community with the need for this Board to have the expertise necessary to oversee a small non-profit corporation. The Board is smaller than the previous IAOC and the other leadership bodies of the IETF, in part to keep the Board focused on its rather limited set of strategic responsibilities as noted in {{board-responsibilities}}.

This board structure, with limited strategic responsibilities noted in {{board-responsibilities}} and limited size, together with the staff responsibilities noted in {{staff-responsibilities}}, is designed to overcome the challenges described in Section 3.1.4 of {{?I-D.haberman-iasa20dt-recs}} concerning oversight. This establishes a clear line of oversight over staff performance: the IETF LLC Board oversees the IETF Executive Director's performance and has actual legal authority to remove a non-performing IETF Executive Director. The IETF Executive Director is responsible for the day-to-day operation of the IETF LLC.

Finally, the IETF LLC Board would be expected to operate transparently, to further address the concern raised in Section 3.3 of {{?I-D.haberman-iasa20dt-recs}}. The default transparency rule arrived at during the IASA 2.0 design process is detailed above in {{principles}}. The Board will need to establish how it will meet that commitment.

# IETF LLC Board Membership, Selection and Accountability {#board}

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

The appointment of an IETF LLC Board-appointed Director requires a 2/3rd-majority vote of the Directors then in office, and the appointee shall take office immediately upon appointment. The term of each appointment is designated by the Board, with the maximum term being three years, or until their earlier resignation, removal or death.  The Board may decide on a case-by-case basis how long each term shall be, factoring in the restriction for consecutive terms in {{term-length}}.

## Recruiting IETF LLC Board Directors {#director-recruitment}

The IETF LLC Board itself is expected to take an active role in recruiting potential new Directors, regardless of the process that may be used to appoint them. In particular, the NomCom is primarily focused on considering requirements expressed by the Board and others, reviewing community feedback on candidates, conducting candidate interviews, and ultimately appointing Directors. The IETF LLC Board and others can recruit potential Directors and get them into the consideration process of the NomCom or other appointing bodies.

## IETF LLC Board Director Term Length {#term-length}

The term length for a Director is three years in length. The exceptions to this guideline will be for the terms for some Directors during the first full formation of the IETF LLC Board in order to establish staggered terms and for any appointments to fill a vacancy. The final exception is if a Director role is occupied by the IETF Chair ex officio, since that person’s term length is governed instead by the term lengths established in {{RFC7437}} (BCP10), Section 3.4.

## IETF LLC Board Director Limit {#term-limit}

A director may serve no more than two consecutive terms, with at least one full term prior to the start of any additional terms. An exception is if a Director role is occupied by the IETF Chair ex officio, since that person’s service is governed instead by the term lengths established in {{RFC7437}} (BCP10), Section 3.4.

An exception to the two consecutive term rule is for an IETF LLC-appointed Director. For such a Director, they may serve only one term via this appointment method, after which any subsequent terms would be occur via other appointment or selection processes (such as via the NomCom process).

Lastly, partial terms of less than three years for the initial appointments to the First Full Board {{first-full-board}}, for which some Directors will have terms of one or two years, do not count against the term limit.

The limit on consecutive terms supports the healthy regular introduction of new ideas and energy into the Board and mitigates potential long-term risk of ossification or conflict, without adversely impacting the potential pool of director candidates over time.

## Staggered Terms {#staggered-terms}

ISOC, the IESG, the Nominating Committee, and the Board are expected to coordinate with each other to ensure that collectively their appointment or selection processes provide for no more than three Directors’ terms concluding in the same year.

## IETF LLC Board Director Removal {#director-removal}

Directors may be removed with or without cause. A vote in favor of removal must be no fewer than the number of Directors less two.  So for example, if there are seven directors, then five votes are required. Directors may also be removed via the IETF recall process defined in {{RFC7437}} (BCP10), Section 7.

## Filling an IETF LLC Board Director Vacancy {#director-vacancy}

It shall be the responsibility of each respective body that appointed or selected a Director that vacates the Board to appoint a new Director to fill the vacancy.  For example, if a Director selected by the NomCom departs the Board prior to the end of their term for whatever reason, then it is the responsibility of the NomCom (using its mid-term rules, as specified in {{RFC8318}}, Section 3.5) as the original appointing body to designate a replacement that will serve out the remainder of the term of the departed Director.  However, this obligation will not apply to vacancies in Board-appointed positions. 

## Quorum {#quorum}

At all meetings of the Board, at least 2/3 of the Directors then in office constitute a quorum for the transaction of business. If a quorum is not be present at any meeting of the Board, the Directors present thereat may adjourn the meeting without notice other than announcement at the meeting, until a quorum is present.

## Board Voting {#voting}

The Board can hold votes during synchronous live meetings of the Board (including telephonic and video) or via asynchronous written (including electronic) means. Decisions on regular IETF LLC matters require a 2/3 majority vote in favor, with the exception of removal of a Director as specified in {{director-removal}}. Absentee voting and voting by proxy are not permitted.

## Interim Board {#interim-board}

An initial interim Board was necessary in order to legally form and bootstrap the IETF LLC. As a result, an Interim Board was formed on a temporary basis until the first full board was constituted. The Interim Board was expected to conclude no later than the end of the 104th meeting of the IETF, in March 2019.

The interim Board was comprised of:

* The IETF chair, ex officio

* The IAOC chair, ex officio

* The IAB chair, ex officio

* One ISOC trustee, selected by the ISOC Board of Trustees

## Board Positions {#board-positions}

Following the formation of the first full IETF LLC Board, and at each subsequent annual meeting of the IETF LLC Board, the Directors are expected to elect by a majority vote of the IETF LLC Board a Director to serve as Board Chair. The Board may also form committees of the Board and/or define other roles for IETF LLC Board Directors as necessary.

# IETF LLC Funding

The IETF LLC must function within a budget of costs balanced against limited revenues.  The IETF community expects the IETF LLC to work to attain that goal, in order to maintain a viable IETF support function that prodvides the environment within which the IETF's technical work can remain vibrant and productive. 

The IETF LLC generates income from a few key sources at the time that this document was written, as enumerated below. Additional sources of income may be developed in the future, within the general bounds noted in {{fundraising-practices}}, and some of these may decline in relevance or go away. As a result this list is subject to change over time and is merely an example of the primary sources of income for the IETF LLC at the time of this writing:

1.  ISOC support
2.  IETF meeting revenues
3.  Donations to the IETF LLC (monetary and/or in-kind)

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

ISOC currently provides significant financial support to the IETF LLC. Exhibit B of the {{IETF-LLC-A}} summarizes the one-time and on-going financial support from ISOC for the forseeable future. It is envisioned that this support will be periodically reviewed and revised, via a cooperative assessment process between ISOC and the IETF LLC. 

## IETF Meeting Revenues

Meeting revenues are another important source of funding that supports the IETF, comining mainly from the fees paid 
by IETF meeting participants. The IETF Executive Director sets those meeting fees, in consultation with the IETF LLC and 
the IETF community, with formal approval by the IETF LLC. Setting these fees and projecting the number of participants 
at future meetings is a key part of the annual budget process.  

## Donations to the IETF LLC

Donations are an essential component of the financial support for the IETF. Within the general bounds noted in 
{{fundraising-practices}}, the IETF LLC is responsible for fundraising activities in order to establish, maintain, 
and grow a strong foundation of donation revenues. This can and does include both direct financial contributions as well 
as in-kind contributions, such as equipment, software licenses, and services. 

Donations to the IETF LLC shall not convey to donors any special oversight or direct influence over the IETF's 
technical work or other activities of the IETF or IETF LLC. This helps ensure that no undue influence may be 
ascribed to those from whom funds are raised, and so helps to maintain an open and consensus-based IETF standards process.

To the extent that the IETF LLC needs to undertake any significant special projects for the IETF, the IETF LLC 
may need to fundraise distinctly for those special projects. As a result, the IETF LLC may conduct fundraising to support 
the IETF in general as well as one or more special fundraising efforts (which may also be accounted for distinctly and be held in a separate bank account or investment, as needed).

## Funding Supports the IETF

The IETF LLC exists to support the IETF.  Therefore, the IETF LLC's funding and all revenues, in-kind contributions, 
and other income that comprise that funding shall be used solely to support IETF-related activities and for no 
other purposes.

## Charitable Fundraising Practices {#fundraising-practices}

When the IETF LLC conducts fundraising, it substantiates charitable contributions on behalf of ISOC. The IETF LLC evaluates and facilitates state, federal, and other applicable law and regulatory compliance for ISOC and/or the LLC with respect to such fundraising activities. In addition, the IETF LLC ensures that all fundraising activities are conducted in compliance with any policies developed by the IETF LLC, including but not limited to those noted in {{llc-policies}}.

## Operating Reserve

As an initial guideline and in normal operating circumstances, the IETF LLC is expected to have an operating reserve for 
its activities sufficient to cover (1) at least 6 months of non-meeting operational expenses, plus (2) at least 
two times the recent average for meeting contract guarantees.  The IETF LLC, in cooperation with ISOC and the 
IETF community, is expected to establish a financial target for this reserve fund, in accordance with prudent planning 
and as part of the annual budget process and at other appropriate times.

Should the IETF LLC generate an annual budget surplus, it may choose to direct all or part of the surplus towards 
the growth of the operating reserve.

## Annual Budget Process

As noted in {{#llc-responsibilities}}, the IETF LLC is responsible for managing the IETF's finances and budget. 
A key part of this responsibility is establishing, maintaining, and successfully meeting an annual budget. This 
is essential to the continued operation and vibrancy of the IETF's technical activities and establishes trust 
with ISOC and donors that funds are being appropriately spent, and that financial oversight is being conducted 
properly. This is also essential to the IETF LLC meeting applicable legal and tax requirements and is a core part of 
the IETF LLC Board's fiduciary responsibilities. 

As explained in {{#staff-responsibilities}}, the IETF Executive Director is expected to develop, execute, and report on the 
annual budget. Regular reporting is expected to include monthly and quarterly forecast vs. budget statements, including updated projections of income and expenses for the full fiscal year. 

The IETF LLC Board, as explained in {{#board-responsibilities}}, is expected to review and approve the 
budget, as well as to provide ongoing oversight of the budget and of any other significant financial matters. 

The annual budget is expected to be developed in an open, transparent, and collaborative manner, in accordance with 
{{#principles}}. The specific timeline for the development, review, and approval of the IETF LLC annual budget is established by the IETF LLC Board and may be revised as needed. 

# IETF LLC Policies {#llc-policies}

The Board is expected to maintain policies as necessary to achieve the goals of the IETF LLC, meet transparency expectations of the community, comply with applicable laws or regulations, or for other reasons as appropriate. All policies are expected to be developed with input from the IETF community. Some policies provided by ISOC may provide a useful starting point for the Board to consider.

## Conflict of Interest Policy {#conflict-of-interest}

The Board is expected to maintain a Conflict of Interest policy for the IETF LLC. While the details are determined by the Board, at a minimum such policy is expected to include the following:

* The IETF, ISOC Board, IAB, or IRTF chair cannot be chair of this IETF LLC Board, though they may serve as a Director.

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

The IETF LLC is expected report to ISOC on the implementation of its compliance plan on an annual basis.

# Three-Year Assessment

The IETF LLC, with the involvement of the community, shall conduct and complete an assessment of the structure, processes, and operation of IASA 2.0 and the IETF LLC. This should be presented to the community after a period of roughly three years of operation. The assessment may potentially include recommendations for improvements or changes to the IASA2 and/or IETF LLC.

# Security Considerations

This document describes the structure of the IETF's Administrative
Aupport Activity (IASA), version 2 (IASA2).  It introduces no security considerations
for the Internet.

# IANA Considerations

This document has no IANA considerations in the traditional sense.
However, some of the information in this document may affect how the
IETF standards process interfaces with the IANA, so the IANA may be
interested in the contents.

# Acknowledgments

Thanks to Jari Arkko, Richard Barnes, Brian E Carpenter, Alissa
Cooper, John C Klensin, Bob Hinden, Jon Peterson, Sean Turner and the
IASA2 Working Group for discussions of possible structures, and to the
attorneys of Morgan Lewis and Brad Biddle for legal advice.
