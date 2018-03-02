Subject: [Summit] Approval From ${organization.identifier} Needed for Proposal ${proposal.identifier}

[@wrap]
Proposal ${proposal.identifier} awaits your approval for submission to the sponsor.
[/@wrap]

Please sign in to [Summit](summit.vt.edu) (summit.vt.edu) to review this proposal.

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
