Subject: [Summit] International Notice for ${proposal.activityType} ${proposal.identifier}

Greetings Proposal Team!

As a result of your team answering yes to the OESRC question "Will the research involve any International Organizations or Foreign Nationals who are NOT students or employees of VT?" you are receiving this email with a link to a document on OSP's website.  This document, [What You May Not Know About International Research Projects](https://www.research.vt.edu/osp/files/special-issues-international-projects.pdf), provides advance notice of special requirements you may encounter which could cause some delays in starting your research.  We strongly encourage you to follow this link and read this information.

------------------------------------------------------------------------

[@wrap]
Full Title: ${proposal.fullTitle!"Untitled"}
[/@wrap]

* Work Label: ${proposal.name}
* Sponsor: ${proposal.sponsor.name}
* Prime Sponsor: [#if (proposal.primeSponsor)??]${proposal.primeSponsor.name}[#else]NA[/#if]
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName?upper_case}
* Deadline: ${proposal.deadline?date}

[#if proposalLink??]
Click [${proposal.identifier}](${proposalLink}) to access the ${proposal.activityType} in Summit.
[#else]
To access this ${proposal.activityType}, go to [summit.vt.edu](http://summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.
