Subject: [Summit] International Notice for ${proposal.identifier}

${proposal.principalInvestigator.displayName},

**You are receiving this notice because the following ${proposal.activityType} had the OESRC International question marked "Yes". This notice contains important information and instructions related to the submission of your upcoming ${proposal.activityType} ${proposal.identifier}; please read this message in its entirety.**

------------------------------------------------------------------------

[@wrap]
Full Title: ${proposal.fullTitle!"Untitled"}
[/@wrap]

* Work Label: ${proposal.name}
* Sponsor: ${proposal.sponsor.name}
* Prime Sponsor: [#if (proposal.primeSponsor)??]${proposal.primeSponsor.name}[#else]NA[/#if]
* Deadline: ${proposal.deadline?date}

[#if proposalLink??]
Click [${proposal.identifier}](${proposalLink}) to access the ${proposal.activityType} in Summit.
[#else]
To access this ${proposal.activityType}, go to [summit.vt.edu](http://summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.
