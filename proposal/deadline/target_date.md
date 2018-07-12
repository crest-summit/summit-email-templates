Subject: [Summit] ${difference} Business Day Deadline Reminder for ${proposal.activityType} ${proposal.identifier}

[@wrap]
${proposal.activityType} ${proposal.identifier} is ${difference} business days from the target deadline date identified in this ${proposal.activityType}.
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
  ${investigator.reverseDisplayName?upper_case}[#sep];
  [#else] N/A
  [/#list]
  [/@wrap]

[#if proposalLink??]
To access this ${proposal.activityType}, click [here](${proposalLink}).
[#else]
To access this ${proposal.activityType}, log in to [summit.vt.edu](summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.

To opt out of email notifications or update your email preferences, go to [Summit](summit.vt.edu), click your name in the upper right corner and then User Preferences.
