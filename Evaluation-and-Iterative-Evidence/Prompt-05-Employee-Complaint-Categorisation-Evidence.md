# Prompt 05 - Employee Complaint Categorisation

## 1. Overview
This document records the iterative development of Prompt 05: Employee Complaint Categorisation. Three versions were developed to improve the structure, consistency and fairness of employee complaint reviews while helping HR identify the nature of complaints, relevant concerns and matters requiring further attention.

## 2. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial employee complaint categorisation prompt created. | Establish the basic complaint review structure. |
| V1.1 | Added complaint categories and instructions to use neutral language and avoid assumptions. | Improve consistency and fairness when reviewing complaints. |
| V1.2 | Added urgency identification, privacy safeguards and human review requirements. | Improve complaint handling and reduce risks associated with sensitive workplace issues. |

## 3. Version Comparison Screenshot
The screenshot below demonstrates the development of Prompt 05, highlighting the improvements made to complaint categorisation, neutral language, information clarification and identification of potential urgency or safety concerns.

(https://github.com/sleotalu/HR-Prompt-Library/blob/304a7d689132220ef2328452afd6b303aa26e256/Evaluation-and-Iterative-Evidence/Prompt-05-Comparison-Version1.png)

(https://github.com/sleotalu/HR-Prompt-Library/blob/304a7d689132220ef2328452afd6b303aa26e256/Evaluation-and-Iterative-Evidence/Prompt-05-Comparison-Version2.png)

(https://github.com/sleotalu/HR-Prompt-Library/blob/304a7d689132220ef2328452afd6b303aa26e256/Evaluation-and-Iterative-Evidence/Prompt-05-Comparison-Version3.png)

## 4. Prompt Versions

### V1.0 - Initial Employee Complaint Categorisation Prompt
``` text
You are an HR assistant responsible for reviewing employee complaints.

Review an employee complaint submitted to [COMPANY_NAME] using the information provided.

Use the following information:
- Employee name: [EMPLOYEE_NAME]
- Department: [DEPARTMENT]
- Date complaint received: [DATE_RECEIVED]
- Employee complaint: [INSERT_COMPLAINT_DETAILS]

Include the following sections:
1. Complaint summary
2. Main issues raised
3. Relevant people or departments mentioned
4. Important details identified
5. Suggested next steps for HR review

Requirements:
- Use the information provided by the employee
- Identify the main concerns raised in the complaint
- Keep the summary clear and easy to understand
- Ensure the report is relevant to HR complaint review
- Do not invent complaint details

Tone: Professional and respectful

Output: A structured employee complaint summary to help HR understand the concerns raised.
```

### V1.1 - Structured Employee Complaint Categorisation Prompt
``` text
You are an experienced HR assistant responsible for supporting the fair and consistent review of employee complaints.

Review and categorise an employee complaint submitted to [COMPANY_NAME] based on the information provided.

Use the following information:
- Employee name: [EMPLOYEE_NAME]
- Department: [DEPARTMENT]
- Date complaint received: [DATE_RECEIVED]
- Employee complaint: [INSERT_COMPLAINT_DETAILS]

Include the following sections:
1. Complaint summary
2. Main issues or concerns raised
3. Complaint category (e.g. bullying, discrimination, harassment, workplace conflict, workload, management concerns or workplace safety)
4. Relevant people or departments mentioned
5. Key events and details identified
6. Suggested next steps for HR review

Requirements:
- Use only the information provided in the employee complaint
- Do not make assumptions or draw conclusions about the complaint
- Use neutral language when describing the employee's concerns
- Categorise the complaint based on the issues raised
- Clearly identify the main concerns reported by the employee

Tone: Neutral, respectful and professional

Output: A structured employee complaint categorisation report to support consistent and fair HR review.
```

### V1.2 - Final Employee Complaint Categorisation Prompt
[View Final Prompt 05 - Employee Complaint Categorisation] (https://github.com/sleotalu/HR-Prompt-Library/blob/15cb100fab3f09e8b0f29d36e83c9ce45d1efd5a/Workflow-2-Employee-Complaints/Prompt-05-Complaint-Categorisation.md)

## 5. Summary of Improvements

### V1.0 to V1.1
- Introduced complaint categories, including bullying, discrimination, harassment, workplace conflict, workload, management concerns and workplace safety
- Added instructions to categorise complaints based on the issues raised
- Introduced neutral language when describing employee concerns
- Added requirements to use only the information provided and avoid assumptions
- Improved the structure and consistency of complaint categorisation reports

### V1.1 to V1.2
- Expanded the complaint report to identify relevant people, departments and work areas
- Added key events, dates and details to support a clearer understanding of the complaint
- Introduced a section for missing or unclear information requiring clarification
- Added identification of potential urgency and workplace safety concerns requiring HR attention
- Expanded the suggested next steps for HR review
- Introduced a confidential and professional tone
- Improved the completeness and usefulness of complaint categorisation reports for HR review

## 6. Final Outcome
V1.2 was selected as the final prompt because it provides a more complete and structured approach to employee complaint categorisation. The final version supports HR by identifying the main issues raised, assigning relevant complaint categories and highlighting missing information or potential urgency and safety concerns. It also encourages neutral and confidential reporting by focusing on the information provided by the employee without making assumptions or drawing conclusions about the complaint.
The generated report supports HR review and helps identify appropriate next steps while leaving any investigation findings and final decisions to the responsible HR staff.

## 7. Related Workflow Prompts
Prompt 05 is the first stage of Workflow 2 - Employee Complaints. It provides a structured complaint categorisation report that can support the subsequent HR policy review and complaint response stages.

[View Final Prompt 05 - Employee Complaint Categorisation] (https://github.com/sleotalu/HR-Prompt-Library/blob/15cb100fab3f09e8b0f29d36e83c9ce45d1efd5a/Workflow-2-Employee-Complaints/Prompt-05-Complaint-Categorisation.md)

[View Prompt 06 - HR Policy Review] (https://github.com/sleotalu/HR-Prompt-Library/blob/15cb100fab3f09e8b0f29d36e83c9ce45d1efd5a/Workflow-2-Employee-Complaints/Prompt-06-HR-Policy-Review.md)

[View Prompt 07 - Complaint Response] (https://github.com/sleotalu/HR-Prompt-Library/blob/15cb100fab3f09e8b0f29d36e83c9ce45d1efd5a/Workflow-2-Employee-Complaints/Prompt-07-Complaint-Response.md)
