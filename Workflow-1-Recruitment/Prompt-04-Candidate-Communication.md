# Prompt 04: Candidate Communication

## 1. Workflow

**Workflow Name:** Recruitment and Selection

**Workflow Stage:** Candidate Communication

**Previous Prompt:** Prompt 03 - Interview Preparation

**Next Workflow:** Workflow 2 - Employee Complaints

**Workflow Description:**
This prompt supports the candidate communication stage of the recruitment process. After candidates have been shortlisted and interviews have been prepared or conducted, HR staff need to communicate important recruitment updates and decisions to applicants. This prompt helps HR generate professional, clear and appropriate messages for different stages of the recruitment process.

## 2. Purpose
The purpose of this prompt is to assist HR staff in preparing professional and consistent communications with job applicants. It aims to reduce the time spent writing individual recruitment emails while ensuring that candidates receive clear, respectful and relevant information throughout the recruitment process.

## 3. Prompt
``` text
You are an experienced HR recruitment communication assistant responsible for preparing professional, respectful and clear messages to job applicants.

Draft a recruitment communication message for [CANDIDATE_NAME] regarding the position of [JOB_TITLE] at [COMPANY_NAME].

Use the following information provided by HR:
- Candidate name: [CANDIDATE_NAME]
- Job title: [JOB_TITLE]
- Company name: [COMPANY_NAME]
- Candidate reference: [CANDIDATE_REFERENCE]
- Recruitment stage: [RECRUITMENT_STAGE]
- Communication purpose: [COMMUNICATION_PURPOSE]
- Candidate screening outcome: [SCREENING_OUTCOME]
- Interview details: [INTERVIEW_DETAILS]
- Interview location: [INTERVIEW_LOCATION]
- Additional information: [ADDITIONAL_INFORMATION}
- Response deadline: [RESPONSE_DEADLINE]
- Recruitment update: [RECRUITMENT_UPDATE]
- Confirmed recruitment decision: [CONFIRMED_RECRUITMENT_DECISION]
- HR contact name: [HR_CONTACT_NAME]
- HR contact details: [HR_CONTACT_DETAILS]

The job and recruitment information should be consistent with the completed outputs of:
- Prompt 01 - Job Description Generator
- Prompt 02 - Candidate Screening Report
- Prompt 03 - Interview Preparation

Identify the recruitment stage and communication purpose before drafting the message.

The communication may relate to:
1. Application acknowledgement
2. Interview invitations
3. Interview confirmations and reminders
4. Requests for additional information
5. Recruitment process updates
6. Successful application notifications
7. Unsuccessful application notifications

Include the following sections:
1. Subject line: Create a clear and relevant email subject
2. Greeting: Address the candidate professionally
3. Purpose: Clearly explain the reason for the communication
4. Main message: Provide the relevant recruitment information or update
5. Next steps: Explain any action required from the candidate, including deadlines if provided
6. Closing: End the message in a professional and respectful manner
7. HR review reminder: Identify any missing information HR must confirm before sending

Requirements:
- Use only the information provided by HR
- Adapt the message to the relevant recruitment stage
- Do not invent interview dates, times, locations, job offers or recruitment decisions
- Do not disclose confidential information about other candidates or internal recruitment discussions
- Use professional, friendly, respectful and inclusive language
- Only communicate recruitment outcomes that have been confirmed and approved by HR
- Clearly identify missing information as [HR TO COMPLETE]
- Do not send messages automatically
- HR staff must review and approve all communications before sending them to candidates

Tone: professional, friendly, clear and respectful.

Output: A complete recruitment communication message ready for HR review and approval before being sent to the candidate.
```

**Placeholders to fill:**
| **Placeholder** | **Source** | **Example** |
|---|---|---|
| `[CANDIDATE_NAME]` | Candidate application / Recruitment records | Emily Johnson |
| `[JOB_TITLE]` | Prompt 01 – Job Description Generator output | Retail Store Assistant |
| `[COMPANY_NAME]` | Prompt 01 – Job Description Generator output | ABC Retail |
| `[CANDIDATE_REFERENCE]` | Recruitment application tracking system | Applicant 001 |
| `[RECRUITMENT_STAGE]` | HR recruitment tracking system | Interview Invitation |
| `[COMMUNICATION_PURPOSE]` | HR recruitment team | Invite candidate to an interview |
| `[SCREENING_OUTCOME]` | Prompt 02 – Candidate Screening Support / HR-approved outcome | Shortlisted for interview |
| `[INTERVIEW_DETAILS]` | Prompt 03 – Interview Preparation / Confirmed HR arrangements | Tuesday 31 March 2026, 10:00 AM |
| `[INTERVIEW_LOCATION]` | HR recruitment team / Confirmed interview arrangements | ABC Retail, Melbourne Office |
| `[ADDITIONAL_INFORMATION]` | HR recruitment team | Request additional employment references |
| `[RESPONSE_DEADLINE]` | HR recruitment team | Friday 27 March 2026 |
| `[RECRUITMENT_UPDATE]` | HR recruitment team | Interview process has been extended by one week |
| `[CONFIRMED_DECISION]` | HR-approved recruitment decision | Successful application |
| `[HR_CONTACT_NAME]` | HR team roster | Michael Thompson |
| `[HR_CONTACT_DETAILS]` | Official company contact information | recruitment@abcretail.com |

## 4. Intended Task
The intended task is to support HR staff in drafting recruitment-related communications for job applicants. The prompt can be used to prepare emails and messages for interview invitations, application acknowledgements, recruitment updates and employment application outcomes. It helps ensure that candidates receive timely, clear and professional communication throughout the recruitment process.

## 5. Problem Being Solved
Recruitment teams often manage multiple candidates and vacancies at the same time. Writing individual emails for every applicant can be repetitive and time-consuming. Inconsistent communication may also create confusion or negatively affect the candidate experience. This prompt addresses these challenges by generating structured recruitment messages that HR staff can review, personalise and approve before sending. 

## 6. Automation Potential
This prompt has the potential to automate parts of the recruitment communication process. 

**Potential Automation Activities:**
- Draft application acknowledgement emails
- Generate interview invitations and reminders
- Prepare recruitment progress updates
- Draft requests for additional candidate information
- Generate successful and unsuccessful application notifications
- Adapt communication tone and structure to different recruitment stages

**Human Involvement:**
HR staff must verify candidate details, confirm recruitment decisions and check all dates, times and other information before sending messages. All employment decisions and final candidate communications must remain under human oversight. AI should assist with drafting communications rather than independently making recruitment decisions or sending messages.

## 7. Risks and Limitations
**Potential Risks:**
- **Incorrect Information:** AI may generate incorrect dates, times and recruitment details.
- **Privacy:** Candidate personal information may be exposed if handled through unapproved AI systems.
- **Inappropriate Tone:** Generated messaged may sound impersonal or unsuitable for sensitive recruitment situations.
- **Miscommunication:** Incorrect wording may create confusion about interview arrangements or recruitment outcomes.
- **Over-reliance:** HR staff may send AI-generated messaged without properly checking them.

**Limitations:**
- AI can only use the information provided by HR staff
- It cannot independently confirm recruitment decisions
- It may not understand the full context of sensitive candidate situations
- Generated messaged may require personalisation before sending

**Risk Mitigation:** 
HR staff should verify all candidate details, use approved AI tools, protect confidential information and review messages before sending. Sensitive recruitment communications should receive additional human review.

## 8. Testing and Evaluation
The prompt will be tested using fictional recruitment scenarios to assess the quality, accuracy and professionalism or generated candidate communications.
**Testing Method:**
1. Provide the AI with a fictional recruitment scenario
2. Identify the type of communication required
3. Provide the relevant candidate communication prompt
4. Run the candidate communication prompt
5. Review the generated message for accuracy, tone and relevance
6. Check that no information has been invented or omitted
7. Refine the prompt if necessary and test it again using different recruitment scenarios

**Evaluation Criteria:**
The following criteria will be used to evaluate the prompt's performance:
| Evaluation Area | What to Check |
|---|---|
| Accuracy | Does the message correctly use the information provided? |
| Relevance | Does the message match the recruitment stage and purpose? |
| Professionalism | Is the communication respectful and appropriate? |
| Clarity | Is the information easy for candidates to understand? |
| Privacy | Does the message avoid disclosing confidential information? |
| Output Quality | Is the message well-structured and ready for HR review? |

**Success Measures:**
The prompt will be considered effective if it generates accurate, professional and clear recruitment communications, reduces repetitive administrative work and supports a positive candidate experience. 

## 9. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial candidate communication prompt created. | Establish the basic recruitment message generation structure. |
| V1.1 | Added different recruitment communication types and message structure. | Improve flexibility and relevance across recruitment stages. |
| V1.2 | Added privacy instructions, accuracy checks and HR approval requirements. | Reduce communication risks and maintain human oversight. |

**Current Version:** V1.2

**Status:** Ready for testing and evaluation.
