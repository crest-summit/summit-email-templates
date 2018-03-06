Subject: [Summit] Proposal ${proposal.identifier} Returned for Correction

[#if isApprover != true]
**To Proposal Team Members & Staff:**

${proposal.approval.disposition.authority.displayName} returned for correction proposal ${proposal.identifier} for the following reason: "${proposal.approval.disposition.comment}"

Note: Please sign in to [Summit](summit.vt.edu) (summit.vt.edu) to make the necessary corrections and re-route the proposal for review and approvals.
[#else]
**To Approvers:**

${proposal.approval.disposition.authority.displayName} returned for correction proposal ${proposal.identifier} for the following reason: "${proposal.approval.disposition.comment}"

Note: Once the proposal has been routed after corrections have been made, approvers will need to approve the modified version of the original proposal.
[/#if]

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