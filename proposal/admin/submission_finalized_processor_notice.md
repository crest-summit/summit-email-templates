Subject: [Summit] Processor Notice for ${proposal.identifier}

You are receiving this notice because ${proposal.activityType} ${proposal.identifier} has transitioned from Open to Awaiting Banner and now requires the attention of the Processors.

* Work ID: ${proposal.identifier}
* Type of Work: ${proposal.activityType}
* Work Label: ${proposal.name}
* Sponsor Keywords: ${proposal.sponsor.keywords}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName}
* Submitting Organization: ${proposal.submittingOrganization.name}
* Sponsor: ${proposal.sponsor.name}
* Comment: ${comment}
* Comment BY: ${commentBy}
* Assigned Pre Award: ${proposal.assignee.displayName}

[#if parentProposal??]
* Parent ID: ${parentProposal.identifier}
* Parent Type of Work: ${parentProposal.activityType}
* Parent Work Label: ${parentProposal.proposalLabel}
[/#if]

[#if proposalLink??]
Click [${proposal.identifier}](${proposalLink}) to access the ${proposal.activityType} in Summit.
[#else]
To access this ${proposal.activityType}, go to [summit.vt.edu](http://summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.
