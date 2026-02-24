# RESOLUTIONS OF THE CNCF GOVERNING BOARD

## Adopted on July 16, 2024

## **License Exception Requests for Flatcar**

WHEREAS, the prospective CNCF project Flatcar is requesting approval of license exceptions for several different categories of differences from the CNCF IP policy ([Issue \#623](https://github.com/cncf/foundation/issues/623)), as reviewed by the CNCF Legal Committee under the following category references:

* **1.1: Permissive Project License mismatches for forked projects** (BSD-2-Clause; BSD-3-Clause)  
* **1.2: Copyleft Project License mismatches for forked projects** (LGPL-2.1; GPL-2.0; GPL-3.0)  
* **1.3: Copyleft dependencies which subsequently relicensed to Apache-2.0** (LGPL-3.0 WITH LGPL-3.0-linking-exception; LGPL-2.1-only OR CDDL-1.0; LGPL (version unspecified))  
* **1.4: Ebuild scripts licensed under GPL-2.0** (GPL-2.0)  
* **1.6: Provision of Third Party Packages incorporated into the Flatcar Linux distribution** (various licenses, as indicated in [Addendum 1](https://docs.google.com/document/d/1MqDDG3fJFt1eS0W_WBb_UIoK1ujX483yDtQn9d3wDQ4/edit#heading=h.gnfdhjimsheq) to the May 21, 2024 Legal Committee writeup)

  WHEREAS, the Legal Committee recommends approving license exceptions for the foregoing, *except* that (1) the Legal Committee only recommended approval for the netperf component under the MIT license (which would be automatically subject to the CNCF Allowlist License Policy) rather than the custom netperf license; and (2) the Legal Committee did not recommend approving a license exception for Nmap’s NPSL-0.95 license.


  RESOLVED, that the Governing Board hereby approves the license exceptions set forth above, excluding the custom netperf and NPSL-0.95 licenses as set forth above.

## **Additional License Exception Request Received from Flatcar Maintainers**

WHEREAS, the prospective CNCF project Flatcar has additionally requested approval of a license exception for another repository ([https://github.com/flatcar/azure-vhd-utils](https://github.com/flatcar/azure-vhd-utils)) in a manner equivalent to category 1.1 above, but for the *MIT* license.

WHEREAS, the Legal Committee has not yet reviewed this exception due to the late request by the Flatcar maintainers; but CNCF outside legal counsel and internal legal counsel have indicated their belief that the Legal Committee would be very likely to recommend approval of this exception as effectively equivalent to those in category 1.1 above.

RESOLVED, that the Governing Board hereby approves the license exception described above for the forked repository under the *MIT* license.

## **Additional HashiCorp libraries under MPL-2.0**

WHEREAS, one or more CNCF projects have requested license exceptions for the following Golang packages, which are licensed under MPL-2.0, in unmodified form ([Issue \#624](https://github.com/cncf/foundation/issues/624), [Issue \#741](https://github.com/cncf/foundation/issues/741)):

* github.com/hashicorp/go-getter  
* github.com/hashicorp/go-safetemp  
* github.com/hashicorp/memberlist  
    
  WHEREAS, the Legal Committee recommends approving an exception to permit CNCF projects to use the Golang packages listed above in unmodified form under MPL-2.0.  
    
  RESOLVED, that the Governing Board hereby approves a license exception to permit CNCF projects to use the Golang packages listed above in unmodified form under MPL-2.0.


## **Amendments to CNCF Legal Committee Charter**

WHEREAS, in order to streamline and expedite review of license exception requests and otherwise improve the CNCF Legal Committee’s processes, the CNCF Legal Committee has recommended adoption of the amended CNCF Legal Committee Charter attached hereto as Exhibit A.

NOW, THEREFORE, BE IT RESOLVED, that the Governing Board hereby approves and adopts the amended CNCF Legal Committee Charter attached hereto as Exhibit A.

## **Streamlined Approval Process for Certain License Exceptions**

RESOLVED, that, in order to streamline and expedite review of certain types of license exception requests, the Governing Board hereby approves and adopts the Streamlined Review Process for License Exceptions attached hereto as Exhibit B.

# **Exhibit A**

## CNCF Legal Committee Charter

(a) The responsibilities of the Legal Committee include making recommendations to the Governing Board in response to questions submitted to the Legal Committee by the Governing Board.  For clarity, the Legal Committee does not represent CNCF and does not have an attorney-client relationship with CNCF.

(b) Participation on the Legal Committee is optional. The voting members of the Legal Committee will consist of attorney representatives from Platinum, Gold, and Silver Members who have appointed seats on the Governing Board.  Governing Board members appointed by such Platinum, Gold, and Silver Member companies who wish to participate on the Legal Committee may do so together with any attorney representative of their company.  Additionally, the Governing Board may designate one or more Governing Board members to attend Legal Committee meetings as non-voting liaison observers. 

(c) In the event that the attorney representative appointed by an eligible Member company is unable to attend a Legal Committee meeting, the Member company may send an alternate attorney representative to that meeting which alternate representative may participate in voting. 

(d) Decisions will be made based on consensus whenever practicable. If, however, any decision requires a vote to move forward, attorney representatives of the Member companies participating in the Legal Committee will vote on a one vote per Member company basis.  Actions and recommendations of the Legal Committee may be approved by the absence of sustained objection or an affirmative vote of a simple majority.  Abstentions will be excluded from the denominator for purposes of determining whether a majority has voted affirmatively; in other words, an action will be approved when the number of “FOR” votes exceeds the number of “AGAINST” votes.

(e) Except where a different quorum requirement is set forth in this charter, quorum for any vote shall require attendance or participation by at least fifty percent (50%) of active voting members of the Legal Committee. For purposes of calculating quorum for any meeting or vote, a committee member shall be deemed “active” if they or an alternate designated by their company have attended any meeting or participated in any vote (including the then-current meeting or vote) during the prior six (6) months. Any member who is not active shall be excluded from the denominator for purposes of calculating quorum. “Abstain” votes shall be counted as attendance or participation for purposes of determining quorum and determining whether a member is active or inactive.

(f) Legal Committee members shall be provided with notice of the date and time and proposed agenda of a regular meeting at least fourteen (14) calendar days in advance of the meeting.  If a vote will be held at the meeting, the matter to be voted upon must be included in the agenda for the meeting.  In the event the Governing Board determines it is necessary to call an emergency meeting of the Legal Committee, at least five (5) calendar days notice of the date and time and proposed agenda for the meeting shall be provided, and Legal Committee members will be given the option to vote either at the emergency meeting or by email or electronic ballot.

(g) Subject to the other requirements in this charter, voting may be conducted (i) during a meeting that complies with the notice requirements of paragraph (f) of this charter; (ii) by email, (iii) by written or electronic ballot; or (iv) a combination of the foregoing.  Votes cast at a duly called meeting, even if attendance at the meeting is less than a quorum, may be combined with votes cast by email or electronic ballot before or after the meeting. 

(h) Voting on license exceptions to the “[IP Policy” section of the CNCF Charter](https://github.com/cncf/foundation/blob/main/charter.md#11-ip-policy) may take place with or without a meeting. If such voting takes place entirely by email or electronic ballot without a meeting, the deadline for voting shall be not less than fourteen (14) calendar days after the vote is first solicited. If the votes on the matter (excluding abstentions) are unanimous and no legal committee member requests a meeting or objects to voting without a meeting, affirmative votes (excluding abstentions) from at least three (3) committee members shall constitute quorum; otherwise, the standard quorum requirements of paragraph (e) shall apply to a vote conducted without a meeting in accordance with this paragraph (h).

(i) For all matters other than license exceptions to the “[IP Policy” section of the CNCF Charter](https://github.com/cncf/foundation/blob/main/charter.md#11-ip-policy), a meeting that complies with the notice requirements of paragraph (f) of this charter shall be held to discuss the matter. 

(j) If a vote is conducted at a meeting that meets the notice requirements of paragraph (f) of this charter but a quorum of at least fifty percent (50%) of active voting members is not present at the meeting, additional votes may be solicited after the meeting, and the deadline for submitting additional votes by email or electronic ballot shall be not less than seven (7) calendar days after the meeting in the case of a non-emergency meeting, and not less than  four (4) calendar days after the meeting in the case of an emergency meeting. For any vote on license exceptions to the “[IP Policy” section of the CNCF Charter](https://github.com/cncf/foundation/blob/main/charter.md#11-ip-policy) conducted in accordance with the procedures set forth in this paragraph (j), quorum shall be reduced so that attendance at the meeting or participation in the vote by at least three (3) members of the Legal Committee (including abstentions) shall constitute quorum.

**Approval and Revision History**  
Approved by the CNCF Governing Board on March 30, 2023  
Amended by the CNCF Governing Board on \[\_\_\_\_\_\_\], 2024

# **Exhibit B**

## CNCF Governing Board

### Streamlined Review Process for License Exceptions

### Purpose and Background

[Section 11 (IP Policy)](https://github.com/cncf/foundation/blob/main/charter.md#11-ip-policy) of the [CNCF Charter](https://github.com/cncf/foundation/blob/main/charter.md) requires that any exceptions to CNCF’s standard license terms be approved by the Governing Board. Following initial review of license exception requests by CNCF staff and legal counsel, the CNCF Legal Committee makes recommendations to the Governing Board on whether to approve or disapprove such exception requests.

To ensure that CNCF projects’ license exception requests are addressed in a timely and efficient manner, the Governing Board has adopted the streamlined process described below for reviewing some types of requests.

### Streamlined Review Process

When the CNCF Legal Committee makes a recommendation within the scope of this document (see [Scope and Application](#scope-and-application) below) to approve or reject a license exception requested by a CNCF project, a CNCF staff member or CNCF legal counsel will notify the Governing Board by email of (i) the Legal Committee’s recommendation, (ii) the count of votes along with a summary of any objections or concerns expressed by Legal Committee members, (iii) whether CNCF legal counsel has any concerns or objections to following the Legal Committee’s recommendation, and (iv) ask if any Governing Board members have objections to following the Legal Committee’s recommendation, (v) and the date by which Governing Board members must share any objections they have, which must not be less than 7 calendar days after the date of such notification. If no Governing Board member replies with an objection within such objection period, such absence of objection will be deemed to constitute the Governing Board’s decision to follow the Legal Committee’s recommendation to approve or reject the requested license exception.

### Scope and Application

The streamlined process described in this document applies only to the Governing Board’s review and adoption of the following types of Legal Committee recommendations, provided that CNCF legal counsel confirms they have no objections to following such recommendation:

* Recommendation to approve any exception for use of a a third party dependency that is subject to a permissive or weak copyleft [OSI-approved open source license](https://opensource.org/licenses);  
* Recommendation to add any permissive [OSI-approved open source license](https://opensource.org/licenses) to the “Approved Licenses” list in the [CNCF Allowlist License Policy](http://allowed-third-party-license-policy.md); and  
* Recommendation to reject any exception for code or documentation that is not licensed under an [OSI-approved open source license](https://opensource.org/licenses).

All other matters shall be subject to the Governing Board’s standard processes and requirements for quorum, voting, and approval.  For clarity, “permissive” with respect to an OSI-approved open source license means that the license does not contain copyleft requirements or restrictions.

### Approval History

Approved by the CNCF Governing Board on \[\_\_\_\_\_\_\_\_\], 2024

