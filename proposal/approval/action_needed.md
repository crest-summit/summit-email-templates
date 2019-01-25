Subject: [Summit] Approval From ${organization.identifier} Needed for ${proposal.activityType} ${proposal.identifier}

[@wrap]
${proposal.activityType} ${proposal.identifier} awaits your approval for submission to the sponsor.
[/@wrap]

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
  * ${investigator.reverseDisplayName?upper_case}
  [#else] N/A
  [/#list]
  [/@wrap]  
  
* Budget Totals:
  * Direct Costs: $${proposal.budget.totalDirectCost}
  * Indirect Costs: $${proposal.budget.totalIndirectCost}
  * Cost Share: $${proposal.budget.totalCostShare}  

[#if approvalLink??]
Click [${proposal.identifier}](${approvalLink}) to access this ${proposal.activityType}'s approval in Summit.
[#else]
To access this ${proposal.activityType}, go to [summit.vt.edu](http://summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.

To opt out of email notifications or update your email preferences, go to [Summit](http://summit.vt.edu), click your name in the upper right corner and then User Preferences.
