Subject: [Summit] DoD Notice for ${proposal.identifier}

${proposal.principalInvestigator.displayName},

**You are receiving this notice because the following proposal involves Department of Defense (DoD) or DoD flow-through funds. This notice contains important information and instructions related to the submission of your upcoming proposal ${proposal.identifier}; please read this message in its entirety.**

------------------------------------------------------------------------

[@wrap]
Full Title: ${proposal.fullTitle!"Untitled"}
[/@wrap]

* Work Label: ${proposal.name}
* Sponsor: ${proposal.sponsor.name}
* Prime Sponsor: [#if (proposal.primeSponsor)??]${proposal.primeSponsor.name}[#else]NA[/#if]
* Deadline: ${proposal.deadline?date}

Please be advised that DoD funded research agreements are reviewed by the Office of Export and Secure Research Compliance (OESRC) due to the high risk of intersection with export control laws, particularly the International Traffic in Arms Regulations (ITAR).  Numerous criteria must be met to ensure that your project is unrestricted/fundamental research.  

------------------------------------------------------------------------

**ACTION REQUIRED:**  

* Review the [Attachment A: Memo to Faculty Proposing Research Funded by DoD](https://www.research.vt.edu/content/dam/research_vt_edu/oesrc/files/attachment_a_dod_memo.pdf)
[#if proposalLink??]
* Please answer the following questions in the OESRC compliance subsection of the ${proposal.activityType}.  Click [${proposal.identifier}](${proposalLink}) to access the ${proposal.activityType} in Summit.
[#else]
* Please answer the following questions in the OESRC compliance subsection of ${proposal.activityType} ${proposal.identifier} by going to [summit.vt.edu](http://summit.vt.edu).
[/#if]
* As defined in the OESRC Attachment A, Is this Fundamental Research?
* If you like to include the "dual use" developmental items language described in Attachment A, either add a requirement to the OESRC Requirements section to Include Dual Use Language in Cover Letter or make a comment in Summit requesting it.

------------------------------------------------------------------------

If you choose not to include this language, it is likely that your project will have export control requirements due to sponsor imposed agreement terms or U.S. Government regulations.  If you have any questions regarding export control or fundamental research, please [contact the OESRC](https://www.research.vt.edu/oesrc/contact-us.html) directly.

------------------------------------------------------------------------
Please do not reply, this message is system generated.
