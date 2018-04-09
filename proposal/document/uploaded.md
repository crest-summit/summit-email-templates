Subject: [Summit] File Upload Notice for ${proposal.identifier}

You are receiving this notice because a new file has been uploaded to ${proposal.activityType} ${proposal.identifier}.

[@wrap]
Full Title: ${proposal.fullTitle!"Untitled"}
[/@wrap]

* Deadline: ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}
* Work Label: ${proposal.name}
* Sponsor: ${proposal.sponsor.name}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName?upper_case}  

* File name: ${document.metadata.name}
* Uploaded by: ${document.metadata.creator.reverseDisplayName?upper_case}

------------------------------------------------------------------------
Please do not reply, this message is system generated.

To opt out of email notifications or update your email preferences, go to [Summit](summit.vt.edu), click your name in the upper right corner and then User Preferences.
