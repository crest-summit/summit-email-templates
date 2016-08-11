Subject: [Summit] Action Required for Submission of Proposal ${proposal.identifier}


**Proposal ${proposal.identifier} has outstanding requirements, preventing submission.**


------------------------------------------------------------------------

${proposal.fullTitle!"Untitled Proposal"}


* Principal Investigator:
  ${proposal.principalInvestigator.displayName}
* Deadline: 
  ${proposal.deadline?string["EEE, MMM d, yyyy, hh:mm a zzz"]}
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
 

Please review the [Proposal Submission Procedure & Guildelines] (http://osp.vt.edu/sites/osp.vt.edu/files/osp-10-01-guidelines-for-timely-proposal-submission.pdf). 



**Please sign in to Summit to access this proposal, communicate with your Pre-Award Associate, and complete the outstanding requirements to ensure that this proposal is submitted in a timely manner.**


------------------------------------------------------------------------
This message is system generated. 
Please do not reply.
