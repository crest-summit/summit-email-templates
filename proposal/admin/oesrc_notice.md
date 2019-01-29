Subject: [Summit] OESRC email for ${proposal.identifier}

You are receiving this notice because an OESRC question was marked "Yes" on ${proposal.activityType} ${proposal.identifier}.  

* Work ID: ${proposal.identifier}
* Type of Work: ${proposal.activityType}
* Work Label: ${proposal.name}
* Target Date: ${proposal.targetDate}
* Sponsor Deadline: ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName}
* Pre Award Assignee: ${proposal.assignee.displayName}
* Submitting Organization: ${proposal.submittingOrganization.name}
* Sponsor: ${proposal.sponsor.name}

International Org Or Person: [#if internationalOrgOrPerson??]${internationalOrgOrPerson}[#else]N/A[/#if]  
[#list internationalOrgOrPersonComments as comment]
    ${comment.author.displayName} - ${comment.creationDate}
    ${comment.text}   

[/#list]

Tangible Item Export: [#if tangibleItemExport??]${tangibleItemExport}[#else]N/A[/#if]  
[#list tangibleItemExportComments as comment]
    ${comment.author.displayName} - ${comment.creationDate}
    ${comment.text}  

[/#list]

[#if proposalLink??]
Click [${proposal.identifier}](${proposalLink}) to access the ${proposal.activityType} in Summit.
[#else]
To access this ${proposal.activityType}, go to [summit.vt.edu](http://summit.vt.edu).
[/#if]

------------------------------------------------------------------------
Please do not reply, this message is system generated.
