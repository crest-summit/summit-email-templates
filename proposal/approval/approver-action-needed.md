Subject: [Summit] Approval Needed for ${proposal.identifier}

Proposal ${proposal.identifier} awaits your approval for submission to the sponsor.

Please sign in to Summit to review this proposal.

------------------------------------------------------------------------
${proposal.fullTitle}

* Deadline: ${proposal.deadline}?string["EEE, MMM d, yyyy, hh:mm a '('zzz')'"]}
* Label: ${proposal.name}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName?upper_case}
* Co-Investigators: <@compress single_line=true>
<#list proposal.coInvestigators as investigator>
${investigator.reverseDisplayName?upper_case}<#sep>; 
<#else>
(none)
</#list>
</@compress>

------------------------------------------------------------------------
This message is system generated. 
Please do not reply.
