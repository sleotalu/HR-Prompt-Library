# Prompt 04: Candidate Communication

## 1. Overview
This document records the iterative development of Prompt 04: Candidate Communication. Three versions were developed to improve the flexibility, structure and consistency of recruitment communications while ensuring messaged remain professional, respectful and appropriate for different recruitment stages.

## 2. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial candidate communication prompt created. | Establish the basic recruitment message generation structure. |
| V1.1 | Added different recruitment communication types and message structure. | Improve flexibility and relevance across recruitment stages. |
| V1.2 | Added privacy instructions, accuracy checks and HR approval requirements. | Reduce communication risks and maintain human oversight. |

## 3. Version Comparison Screenshot
This screenshot below demonstrates the development of Prompt 04 that highlight the improvements made to recruitment communication types, message structure and HR approval requirements. As it only allows to compare two checkpoints at a time, the following screenshot compares V1.0 and V1.2. 
(https://github.com/sleotalu/HR-Prompt-Library/blob/157031a14cbe5435ec07e08c5853e4fea68c9375/Evaluation-and-Iterative-Evidence/Prompt-04-Comparison-Version1.png)

(https://github.com/sleotalu/HR-Prompt-Library/blob/157031a14cbe5435ec07e08c5853e4fea68c9375/Evaluation-and-Iterative-Evidence/Prompt-04-Comparison-Version2.png)

## 4. Prompt Versions

### V1.0 - Initial Candidate Communication Prompt
``` text
You are an HR recruitment assistant responsible for preparing professional messages to job applicants.

Draft a recruitment communication message for [CANDIDATE_NAME] regarding the position of [JOB_TITLE] at [COMPANY_NAME].

Use the following information provided by HR:
- Candidate name: [CANDIDATE_NAME]
- Job title: [JOB_TITLE]
- Company name: [COMPANY_NAME]
- Recruitment update: [RECRUITMENT_UPDATE]

Create a message that clearly communicates the recruitment update to the candidate.

Requirements:
- Use the information provided by HR
- Address the candidate professionally
- Keep the message clear, polite and easy to understand
- ensure the communication is relevant to the recruitment process
- Do not invent recruitment information

Output: A professional recruitment communication message suitable for HR review.
```

### V1.1 - Structured Candidate Communication Prompt
``` text
You are an experienced HR recruitment communication assistant responsible for preparing professional and respectful messages to job applicants.

Draft a recruitment communication message for [CANDIDATE_NAME] regarding the position of [JOB_TITLE] at [COMPANY_NAME].

Use the following information provided by HR:
- Candidate name: [CANDIDATE_NAME]
- Job title: [JOB_TITLE]
- Company name: [COMPANY_NAME]
- Recruitment stage: [RECRUITMENT_STAGE]
- Communication purpose: [COMMUNICATION_PURPOSE]
- Recruitment update: [RECRUITMENT_UPDATE]
- Interview details: [INTERVIEW_DETAILS]
- HR contact details: [HR_CONTACT_DETAILS]

Requirements:
- Adapt the message to the relevant recruitment stage
- Use clear, professional and respectful language
- Include relevant recruitment information provided by HR
- Do not invent interview details or recruitment outcomes
- Ensure the message is appropriate for the candidate and communication purpose

Output: A structured recruitment message suitable for HR review.
```

### V1.2 - Final Candidate Communication Prompt
[View Final Prompt 04 - Candidate Communication] (https://github.com/sleotalu/HR-Prompt-Library/blob/9dc98500ac71990e738bcbb74256c303615623e9/Workflow-1-Recruitment/Prompt-04-Candidate-Communication.md)

## 5. Summary of Improvements

### V1.0 to V1.1
- Introduced different recruitment communication types
- Added recruitment stage and communication purpose
- Introduced a structured message format with subject line, greeting, main message and closing
- Improved flexibility across different recruitment stages

### V1.1 to V1.2
- Added candidate-specific recruitment information and reference details
- Connected candidate communication to the outputs of Prompts 01, 02, and 03
- Introduced confirmed recruitment decision requirements
- Added missing-information placeholders using [HR TO COMPLETE]
- Added safeguards against inventing interview details or recruitment outcomes
- Introduced confidentiality requirements
- Added HR review and approval requirements before messages are sent
- Improved accuracy, consistency and professionalism in candidate communication

## 6. Final Outcome
V1.2 was selected as the final prompt because it provides a more complete and controlled approach to recruitment communication. The final version supports different recruitment stages by generating clear, professional and respectful messages using HR-provided information. It also reduces the risk of inaccurate or unapproved communications by requiring confirmed recruitment outcomes, identifying missing information and ensuring all messages are reviewed and approved by HR before being sent.

## 7. Related Workflow Prompts
Prompt 04 uses information generated by the previous recruitment workflow prompts.

[View Prompt 01 - Job Description] (https://github.com/sleotalu/HR-Prompt-Library/blob/9dc98500ac71990e738bcbb74256c303615623e9/Workflow-1-Recruitment/Prompt-01-Job-Description.md)

[View Prompt 02 - Candidate Screening Support] (https://github.com/sleotalu/HR-Prompt-Library/blob/9dc98500ac71990e738bcbb74256c303615623e9/Workflow-1-Recruitment/Prompt-02-Candidate-Screening.md)

[View Prompt 03 - Interview Preparation] (https://github.com/sleotalu/HR-Prompt-Library/blob/9dc98500ac71990e738bcbb74256c303615623e9/Workflow-1-Recruitment/Prompt-03-Interview-Preparation.md)

[View Final Prompt 04 - Candidate Communication] (https://github.com/sleotalu/HR-Prompt-Library/blob/9dc98500ac71990e738bcbb74256c303615623e9/Workflow-1-Recruitment/Prompt-04-Candidate-Communication.md)
