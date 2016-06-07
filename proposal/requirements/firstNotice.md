Subject: [Summit] Action Required for Submission of Proposal ${proposal.identifier}

[@wrap]
Proposal ${proposal.identifier} has outstanding requirements, preventing submission.
[/@wrap]

[@wrap]
Please review the [Proposal Submission Policy & Guildelines] (http://osp.vt.edu/sites/osp.vt.edu/files/osp-10-01-guidelines-for-timely-proposal-submission.pdf). 
[/@wrap]

[@wrap]
Please sign in to Summit to access this proposal, communicate with your Pre-Award Associate, and complete the outstanding requirements to ensure that this proposal is submitted in a timely manner.
[/@wrap]

------------------------------------------------------------------------
[@wrap]
${proposal.fullTitle!"Untitled Proposal"}
[/@wrap]

* Principal Investigator:
  ${proposal.principalInvestigator.reverseDisplayName?upper_case}
* Target Date: 
  ${proposal.targetDate} 
* Sponsor Deadline: 
  ${proposal.dueDate}
* Proposal Label: 
  ${proposal.name}
* Co-Investigators:
  [@wrap left=2 right=72]
  [@compress single_line=true]  
  [#list proposal.coInvestigators as investigator]
  ${investigator.reverseDisplayName?upper_case}[#sep];
  [#else] N/A
  [/#list]
  [/@compress]
  [/@wrap]

------------------------------------------------------------------------
This message is system generated. 
Please do not reply.
