Subject: [Summit] ${proposal.activityType} ${proposal.identifier} Approval Discarded

[#if isApprover != true]
**To Proposal Team Members & Staff:**

${proposal.approval.disposition.authority.displayName} discarded approval of ${proposal.activityType} ${proposal.identifier} for the following reason: "${proposal.approval.disposition.comment}".

Note: Please sign in to [Summit](summit.vt.edu) (summit.vt.edu) to make the necessary corrections and re-route the ${proposal.activityType} for review and approvals.
[#else]
**To Approvers:**

${proposal.approval.disposition.authority.displayName} discarded approval of ${proposal.activityType} ${proposal.identifier} for the following reason: "${proposal.approval.disposition.comment}".

Note: Once the ${proposal.activityType} has been routed after corrections have been made, approvers will need to approve the modified version of the original ${proposal.activityType}.
[/#if]

------------------------------------------------------------------------
[@wrap]
Full Title: ${proposal.fullTitle!"Untitled"}
[/@wrap]

* Deadline: ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}
* Work Label: ${proposal.name}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName?upper_case}
* Co-Investigators:
  [@wrap left=2 right=72]
  [#list proposal.coInvestigators as investigator]
  ${investigator.reverseDisplayName?upper_case}[#sep];
  [#else] N/A
  [/#list]
  [/@wrap]

------------------------------------------------------------------------
Please do not reply, this message is system generated.

To opt out of email notifications or update your email preferences, go to [Summit](summit.vt.edu), click your name in the upper right corner and then User Preferences.
