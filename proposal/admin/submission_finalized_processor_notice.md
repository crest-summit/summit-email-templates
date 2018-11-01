Subject: [Summit] Processor Notice for ${proposal.identifier}

You are receiving this notice because ${proposal.activityType} ${proposal.identifier} has transitioned from Open to Awaiting Banner and now requires the attention of the Processors.

* Work ID: ${proposal.identifier}
* Type of Work: [#if parentProposal.identifier == "Proposal"] Proposal (Revision) [else] ${proposal.activityType} [/#if]
* Comment: ${comment!"N/A"}
* Comment BY: ${commentBy}

[#if parentProposal??]
* Parent ID: ${parentProposal.identifier}
* Parent Type of Work: ${parentProposal.activityType}
* Parent Work Label: ${parentProposal.name}
[/#if]

* Assigned Pre Award: ${proposal.assignee.displayName}
* Sponsor: ${proposal.sponsor.name}
* Principal Investigator: ${proposal.principalInvestigator.displayName}
* Sponsor Keywords: ${proposal.sponsor.keywords}

[#if proposalLink??]
Click [${proposal.identifier}](${proposalLink}) to access the ${proposal.activityType} in Summit.
[#else]
To access this ${proposal.activityType}, go to [summit.vt.edu](http://summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.
