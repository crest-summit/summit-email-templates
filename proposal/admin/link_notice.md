Subject: [Summit] LINK Notice for ${proposal.identifier}

You are receiving this notice because ${proposal.activityType} ${proposal.identifier} involves sponsor or prime sponsor associated with the "LINK" keyword.

* Work Label: ${proposal.name}
* Type of Work: ${proposal.activityType}
* Principal Investigator: ${proposal.principalInvestigator.reverseDisplayName}
* Submitting Organization: ${proposal.submittingOrganization.name}
* Sponsor: ${proposal.sponsor.name}
* Prime Sponsor: [#if (proposal.primeSponsor)??]${proposal.primeSponsor.name}[#else]NA[/#if]
* Deadline: ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}

* Is there a solicitation?: ${proposal.opportunity.solicitation}
* Is there a master agreement?: ${proposal.hasMasterAgreement}
* Is this a limited submission?: ${proposal.opportunity.limitedSubmission}
* Is this an unauthorized submission?: ${proposal.submission.unauthorized?string('Yes', 'No')}

Please sign in to [Summit](http://summit.vt.edu) (summit.vt.edu) to review this ${proposal.activityType}.

------------------------------------------------------------------------
Please do not reply, this message is system generated.
