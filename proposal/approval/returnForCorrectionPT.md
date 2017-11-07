Subject: [Summit] Proposal ${proposal.identifier} has been Returned for Correction By ${proposal.authority}

[@wrap]
Proposal ${proposal.identifier} was returned for correction by ${proposal.authority} for the following reason:
[/@wrap]

[@wrap]
${proposal.dispositionComment}
[/@wrap]

Note: Please sign in to Summit (summit.vt.edu) to make the necessary corrections and re-route the proposal for review and approvals.

------------------------------------------------------------------------
[@wrap]
${proposal.fullTitle!"Untitled Proposal"}
[/@wrap]

* Deadline:
  ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}
* Proposal Label:
  ${proposal.name}
* Principal Investigator:
  ${proposal.principalInvestigator.reverseDisplayName?upper_case}
* Co-Investigators:
  [@wrap left=2 right=72]
  [@compress single_line=true]
  [#list proposal.coInvestigators as investigator]
  ${investigator.reverseDisplayName?upper_case}[#sep];
  [#else] N/A
  [/#list]
  [/@compress]
  [/@wrap]

------------------------------------------------------------------------
This message is system generated.
Please do not reply.
