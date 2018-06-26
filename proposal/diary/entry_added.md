Subject: [Summit] New Comment on ${proposal.identifier} 

You are receiving this notice because a new comment has been shared on ${proposal.activityType} ${proposal.identifier}. 

[@wrap] 
Full Title: ${proposal.fullTitle!"Untitled"} 
[/@wrap] 

* Deadline: ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]} 
* Work Label: ${proposal.name} 
* Sponsor: ${proposal.sponsor.name} 
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName?upper_case} 
* Comment by: ${commentBy} 
* Comment: ${comment} 

[#if proposalLink??] 
To access this ${proposal.activityType}, click [here](${proposalLink}). 
[#else] 
To access this ${proposal.activityType}, log in to [summit.vt.edu](summit.vt.edu). 
[/#if] 

------------------------------------------------------------------------ 
Please do not reply, this message is system generated. 

To opt out of email notifications or update your email preferences, go to [Summit](summit.vt.edu), click your name in the upper right corner and then User Preferences. 
