Subject: [Summit] No Approvers on ${proposal.activityType} - ${proposal.identifier}

[@wrap]
Proposal ${proposal.identifier}, ${proposal.principalInvestigator.displayName}, ${proposal.name}, ${proposal.sponsor.name} does not have approvers on it. Please verify that the approval chain is correct on this proposal.
[/@wrap]

Please sign in to Summit to review this proposal.

------------------------------------------------------------------------

[#if data.organizationMissingApprovers?size == 1]
${data.organizationMissingApprovers?first.displayName} has no approver
[#else]
The following organizations have no approvers:
[#list data.organizationMissingApprovers]
[#items as unit]
${unit.displayName}[#sep];[/#sep]
[/#items]
[/#list]
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.

To opt out of email notifications or update your email preferences, go to [Summit](summit.vt.edu), click your name in the upper right corner and then User Preferences.
