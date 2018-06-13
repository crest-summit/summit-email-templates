Subject: [Summit] ${proposal.activityType} ${proposal.identifier} Initiated

${proposal.activityType} ${proposal.identifier} has been initiated.

* Deadline: ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}
* Work Label: ${proposal.name}
* Sponsor: ${proposal.sponsor.name}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName?upper_case}

[#if proposalLink??]
Click [${proposal.identifier}](${proposalLink}) to access the ${proposal.activityType} in Summit.
[#else]
To access this ${proposal.activityType}, go to [summit.vt.edu](http://summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.

To opt out of email notifications or update your email preferences, go to [Summit](http://summit.vt.edu), click your name in the upper right corner and then User Preferences.
