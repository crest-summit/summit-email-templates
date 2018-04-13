Subject: [Summit] ${proposal.activityType} ${proposal.identifier} Initiated

${proposal.activityType} ${proposal.identifier} has been initiated.

* Deadline: ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}
* Work Label: ${proposal.name}
* Sponsor: ${proposal.sponsor.name}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName?upper_case}

[#if permalinkEnabled == true]
Your proposal can be accessed here: [${recipientLink}](${recipientLink})  
[/#if]

You may sign in to [Summit](summit.vt.edu) (summit.vt.edu) to access this ${proposal.activityType}.

------------------------------------------------------------------------
Please do not reply, this message is system generated.

To opt out of email notifications or update your email preferences, go to [Summit](summit.vt.edu), click your name in the upper right corner and then User Preferences.
