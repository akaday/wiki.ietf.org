---
title: PCE WG - Path Computation Element
description: Welcome to the PCE WG Wiki
published: true
date: 2024-10-15T11:25:44.289Z
tags: wg
editor: markdown
dateCreated: 2022-07-23T18:39:51.941Z
---

# Welcome to the PCE WG Wiki

This Wiki contains additional information for the IETF [PCE](https://datatracker.ietf.org/wg/pce/about/) working group. Refer [datatracker](https://datatracker.ietf.org/wg/pce/documents/) for the latest state of any draft. 

Also, see 
- [Implementation  Policy](/group/pce/ImplementationPolicy)
- [Guidelines to contributing to this Wiki](https://wiki.ietf.org/en/home#contributing-to-this-wiki)
- [Coordination with other WG/RG](/group/pce/coordination)


## Individual documents that authors consider ready for WG Adoption

Once the chairs have concluded, the document would move to the actual WG adoption queue. 

| Draft | Remarks |
|---|---| 
|draft-zhang-pce-resource-sharing | Authors request for the 2nd adoption call during 106, support in the room; Expired, a new update is needed | 


## WG Adoption Call Queue

This is a queue of Individual I-D for which the WG adoption call is to be issued. This is maintained to give visibility to the WG on how the document will be progressing. 

| Draft | State | Remarks | Responsible Chair |
| --- | --- | --- | --- |
| draft-peng-pce-stateful-pce-autobw-update | pending | in progress - IPR 3/3 | Julien |
| [draft-dhody-pce-pcep-extension-pce-controller-p2mp](https://datatracker.ietf.org/doc/draft-dhody-pce-pcep-extension-pce-controller-p2mp) | Pending | - | Julien |
| [draft-koldychev-pce-operational](https://datatracker.ietf.org/doc/draft-koldychev-pce-operational/) | Expired | Chairs have asked to break the document into informational and standards tracks ; pending on authors | - |  
| draft-chen-pce-sr-mpls-sid-verification | Pending | Coordinate with SRv6 draft for IANA allocation | - |
| draft-chen-pce-sr-ingress-protection | Pending | - | - |
|draft-dong-pce-pcep-nrp|Pending| - | - |
|draft-fizgeer-pce-pcep-bfd-parameters|Pending |-|-|
| draft-wang-pce-vlan-based-traffic-forwarding | - |Authors have moved VLAN forwarding details to an independent I-D | - |


## Recently Adopted Documents

| Draft |  Remarks | Responsible Chair |
| --- | --- | --- |
| [draft-ietf-pce-pcep-ls](https://datatracker.ietf.org/doc/draft-ietf-pce-pcep-ls) | - | Was Julien |
| [draft-ietf-pce-controlled-id-space](https://datatracker.ietf.org/doc/draft-ietf-pce-controlled-id-space) | Pending comments received during adoption | Was Dhruv |
| [draft-ietf-pce-iana-update](https://datatracker.ietf.org/doc/draft-ietf-pce-iana-update) | Merged with draft-farrel-pce-experimental-error. Expediting process. | Was Julien |


## Other WG I-Ds

| Draft | Remarks |Action|
| --- | --- | --- |
| [draft-ietf-pce-sr-path-segment](https://datatracker.ietf.org/doc/draft-ietf-pce-sr-path-segment) | -11 posted on 2024-09-14 | Nearing WGLC? |
| [draft-ietf-pce-sr-bidir-path](https://datatracker.ietf.org/doc/draft-ietf-pce-sr-bidir-path) | -14 posted on 2024–08-11  | Nearing WGLC? |
| [draft-ietf-pce-stateful-interdomain](https://datatracker.ietf.org/doc/draft-ietf-pce-stateful-interdomain) | -05 posted on 2024-07-03  | Question on using draft-ietf-pce-enhanced-errors |
| [draft-ietf-pce-multipath](https://datatracker.ietf.org/doc/draft-ietf-pce-multipath) | -11 posted on 2024-04-08  | Comments from 117 are not handled yet! IANA early allocation expiry is coming up |
| [draft-ietf-pce-sr-p2mp-policy](https://datatracker.ietf.org/doc/draft-ietf-pce-sr-p2mp-policy) | -09 posted on 2024-08-01 | More review requested, IANA early code points allocated |
| [draft-ietf-pce-pcep-l2-flowspec](https://datatracker.ietf.org/doc/draft-ietf-pce-pcep-l2-flowspec) | -06 posted on 2024-06-19 |  this I-D relies on the processing rules as per RFC 9168 |
| [draft-ietf-pce-pcep-pmtu](https://datatracker.ietf.org/doc/draft-ietf-pce-pcep-pmtu/) | -06 posted on 2024-07-08  | waiting for spring adoption |
| [draft-ietf-pce-pcep-ifit](https://datatracker.ietf.org/doc/draft-ietf-pce-pcep-ifit) | -05 posted on 2024-07-05 | | - |
| draft-ietf-pce-pcep-srv6-yang |  -05 posted on 2024-03-18 | Expired! |
| draft-ietf-pce-pcep-extension-pce-controller-srv6 | -03 posted on 2024-08-18 | Adoption comments from Adrian are handled |
|draft-ietf-pce-bier-te | -00 posted on 2023-11-04 | Expired |
| draft-ietf-pce-enhanced-errors | Parked WG I-D | Chairs concluded to park this document until we have implementations and mechanism using this approach |

## WG documents that authors consider ready for LC

Once the chairs have concluded the document would move to the actual WG LC queue. 

|Draft|Imp Sec|Remarks|Action|
| --- | --- | --- | ---|
|draft-ietf-pce-sr-path-segment|Y|Has Normative dependencies|-|
|draft-ietf-pce-circuit-style-pcep-extensions|Y|-|-|
| draft-ietf-pce-entropy-label-position |N| - | - |
| [draft-ietf-pce-pcep-ls](https://datatracker.ietf.org/doc/draft-ietf-pce-pcep-ls) |Y| - | - |



## WG Last Call Queue 

This is a queue of PCE WG I-Ds, to be last called. This is maintained to give visibility to the WG on how the documents are progressing.  

|Draft | Imp Sec | State | Remarks | Responsible Chair | Shepherd |
| --- | --- | --- | --- | --- | --- |
| [draft-ietf-pce-flexible-grid](https://datatracker.ietf.org/doc/draft-ietf-pce-flexible-grid) | Y | -09 version posted on 2023-03-07 | - | Julien | Julien |
| [draft-ietf-pce-state-sync](https://datatracker.ietf.org/doc/draft-ietf-pce-state-sync) | Y | -07  posted on 2024-03-17 | Missing support for Open message forwarding discussed during WGLC & IETF 119. <br> IANA pre-meeting review : update registry namings | - | - |
| [draft-ietf-pce-pcep-extension-pce-controller-sr](https://datatracker.ietf.org/doc/draft-ietf-pce-pcep-extension-pce-controller-sr) | Y | -08 posted on 2024-01-01 | - | - | - |
| [draft-ietf-pce-sid-algo](https://datatracker.ietf.org/doc/draft-ietf-pce-sid-algo) | Y | -13 posted on 2024-08-12 | Early directorate, outstanding OpsDir comments | - | - |
|draft-ietf-pce-sr-bidir-path|Y|-|-|-|-|


## Post WG LC Queue  

This is a queue of documents after WG LC and before being sent to the IESG.

| Draft| State| Remarks| Shepherd|
| --- | --- | --- | --- |
| [draft-ietf-pce-pcep-color](https://datatracker.ietf.org/doc/draft-ietf-pce-pcep-color) | Waiting for authors to handle the WGLC comments, pending | - | Andrew |
| [draft-ietf-pce-iana-update](https://datatracker.ietf.org/doc/draft-ietf-pce-iana-update) | Waiting for Shepherd Review | - | Dhruv |




## Drafts with the IESG

|Draft| State| Remarks| Shepherd|AD|
| --- | --- | --- | --- | --- |
| [draft-ietf-pce-stateful-pce-optional](https://datatracker.ietf.org/doc/draft-ietf-pce-stateful-pce-optional) | Submitted to IESG for Publication on 2024-04-16 | In Last Call (ends 2024-10-03) | Dhruv | Roman |
| [draft-ietf-pce-pcep-yang](https://datatracker.ietf.org/doc/draft-ietf-pce-pcep-yang/) | Submitted to IESG for Publication on 2024-05-22 | RtgDir,SecDir, Yang doctor early review done | Julien | Gunter |
| [draft-ietf-pce-segment-routing-policy-cp](https://datatracker.ietf.org/doc/draft-ietf-pce-segment-routing-policy-cp) | Submitted to IESG for Publication on 2024-07-05 | AD Evaluation::Revised I-D Needed | Dhruv | Roman |
| [draft-ietf-pce-stateful-pce-vendor](https://datatracker.ietf.org/doc/draft-ietf-pce-stateful-pce-vendor) | Submitted to IESG for Publication on 2024-08-28 | In Last Call (ends 2024-10-10) | Dhruv | Roman |


[AD's Document Queue](https://datatracker.ietf.org/doc/ad/john.scudder)


## Documents in RFC Editor Queue

|Draft|State|Remarks|Shepherd|
| --- | --- | --- | --- |
| [draft-ietf-pce-pceps-tls13](https://datatracker.ietf.org/doc/draft-ietf-pce-pceps-tls13/) |MISSREF|Pending on draft-ietf-tls-rfc8446bis [C496](https://www.rfc-editor.org/cluster_info.php?cid=C496) | Andrew |
| [draft-ietf-pce-pcep-extension-native-ip](https://datatracker.ietf.org/doc/draft-ietf-pce-pcep-extension-native-ip) | MISSRED | Pending on draft-ietf-pce-iana-update | Dhruv |

## Recent RFCs

|RFC|Remarks|Shepherd|
| --- | --- | --- |
| RFC9504 | Published 2023-12; Was draft-ietf-pce-pcep-stateful-pce-gmpls| Dhruv |
| RFC 9603 | Published 2024-07; Was draft-ietf-pce-segment-routing-ipv6 | Hari | 
| RFC 9604 | Published 2024-08; Was draft-ietf-pce-binding-label-sid | Julien | 


## Other Useful Information

### Candidate for early IANA Allocations
This is a queue of PCE WG I-Ds that have a requirement for early codepoint allocation because of the need to interoperate. 

|Draft|State|Remarks|
| --- | --- | --- |
| draft-ietf-pce-sr-path-segment-06 | WG I-D | Authors requested early allocation on 2022-08-19; dependent on PCEP-SRv6 / PCECC-SR  |

<br>

### Early IANA Allocations

|Draft|State|Remarks|IANA 1st|Renewal|Expiry|
| --- | --- | --- | --- | --- | --- |
|draft-ietf-pce-multipath|WG I-D| various |2022-05-09|2024-04-25|2025-05-09|
|draft-ietf-pce-segment-routing-ipv6| WG I-D | various<br><br>Error-Type 10 : Value 44 was dropped 2024-07-25 |2022-01-12|2023-12-14|2025-01-12|
|draft-ietf-pce-segment-routing-policy-cp| WG I-D |[1]ASSOCIATION Type & TLV<br><br>[2]PCEP TLV Type, PCEP-ERROR types, TE-PATH-BINDING|[1]2021-03-30<br><br>[2]2024-02-13|[1]2024-02-16<br><br>[2] -|[1]2025-03-30<br><br>[2]2025-02-13| 
|draft-ietf-pce-pcep-extension-native-ip| WG I-D |- CCI Object-Type<br>- BGP Peer Info Object-Type<br>- Explicit Peer Route Object-Type<br>- Peer Prefix Advertisement Object-Type<br>- PCEP-ERROR Object Error Type<br>- Path Setup Type<br>- PCECC-Capability sub-TLV<br><br> Nearing expiration, chair and AD approved extension, pending|2023-08-14|-|2024-08-14| 
|draft-ietf-pce-sid-algo|WG I-D| 5 allocation done.<br><br>Bandwidth related |2023-09-13<br><br>2024-07-30|2024-07-23<br><br> |2025-09-13<br><br>2025-07-30|
|draft-ietf-pce-pcep-color|WG I-D| 3 allocations done |2023-10-30|-|2024-10-30|
|draft-ietf-pce-sr-bidir-path |WG I-D|ASSOCIATION Type code point 8|2023-11-30|-|2024-11-30|
|draft-ietf-pce-circuit-style-pcep-extensions |WG I-D|STATEFUL-PCE-CAPABILITY TLV Flag<br>LSP-EXTENDED-FLAG TLV Flag<BR>PCEP TLV TYPE|2024-02-23|-|2025-02-23|
|draft-ietf-pce-sr-p2mp-policy |WG I-D|- ASSOCIATION Type<br>- Generalized Endpoint Types<br>- SR-P2MP-POLICY-CAPABILITY<br>- IPV4-SR-P2MP-INSTANCE-ID<br>- IPV6-SR-P2MP-INSTANCE-ID<br>- CCI Object Type - SR P2MP Policy|2024-08-27|-|2025-08-27|
  
### Recent Errata

|RFC|Errata ID|Type|Reported By|State|Chairs suggestion|Remarks|
| --- | --- | --- | --- | --- | --- | --- |


[Any Pending Errata](https://www.rfc-editor.org/errata_search.php?rec_status=2&area_acronym=rtg&wg_acronym=pce&presentation=table)
  
### Liaison
  
[To PCE](https://datatracker.ietf.org/liaison/posted/?text=&source=&destination=pce&start_date=&end_date=)
[From PCE](https://datatracker.ietf.org/liaison/posted/?text=&source=pce&destination=&start_date=&end_date=) 

### Individual documents that failed WG Adoptions 

This is a queue of Individual I-D for which WG adoption call was issued in the past, but did not get adopted. The authors may request adoption call again once they have some more support for the work. 

|Draft | Remarks |
| --- | --- |
| draft-lazzeri-pce-residual-bw | Adoption closed on 2019-02-11 because of limited response |
| draft-zhang-pce-resource-sharing |  Adoption closed on 2018-10-13 because of limited response |

---