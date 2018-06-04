Subject: [Summit] File Version Upload Notice for ${proposal.identifier}

You are receiving this notice because a new file version has been uploaded to ${proposal.activityType} ${proposal.identifier}.

[@wrap]
Full Title: ${proposal.fullTitle!"Untitled"}
[/@wrap]

* Deadline: ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}
* Work Label: ${proposal.name}
* Sponsor: ${proposal.sponsor.name}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName?upper_case}
* File name: ${document.metadata.name}
* Uploaded by: ${document.metadata.creator.reverseDisplayName?upper_case}

[#if proposalLink??]
Click [${proposal.identifier}](${proposalLink}) to access the ${proposal.activityType} in Summit.
[#else]
To access this ${proposal.activityType}, go to [summit.vt.edu](summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.

To opt out of email notifications or update your email preferences, go to [Summit](summit.vt.edu), click your name in the upper right corner and then User Preferences.
