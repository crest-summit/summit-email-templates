Subject: [Summit] No Approvers on Proposal - ${proposal.identifier}

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
This message is system generated.
Please do not reply.
