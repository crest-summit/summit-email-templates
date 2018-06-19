Subject: [Summit] IRB Notice for ${proposal.identifier}

You are receiving this notice because ${proposal.activityType} ${proposal.identifier} may involve IRB.

* Type of Work: ${proposal.activityType}
* Work Label: ${proposal.name}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName}
* Submitting Organization: ${proposal.submittingOrganization.name}
* Sponsor: ${proposal.sponsor.name}
* Prime Sponsor: [#if (proposal.primeSponsor)??]${proposal.primeSponsor.name}[#else]NA[/#if]
* Deadline: ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}

The following question "Does the work involve human subjects research (e.g., surveys, observation, lab or clinical research, analysis of existing data/specimens)?" was answered as "Yes".

[#if proposalLink??]
Click [${proposal.identifier}](${proposalLink}) to access the ${proposal.activityType} in Summit.
[#else]
To access this ${proposal.activityType}, go to [summit.vt.edu](http://summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.
