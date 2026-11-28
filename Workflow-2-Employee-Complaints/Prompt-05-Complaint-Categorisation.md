# Prompt 05: Employee Complaint Categorisation

## 1. Workflow

**Workflow Name:** Employee Complaints

**Workflow Stage:** Complain Catgeorisation

**Previous Prompt:** Workflow 1 - Recruitment and Selection, Prompt 04 - Candidate Communication

**Next Prompt:** Prompt 06 - HR Policy Review

**Workflow Description:** 
This prompt is used when an employee submits a complaint to the HR department. It helps HR staff review the complaint, identify its main issue and categorise it according to the type of concern raised before reviewing relevant organisational policies.

## 2. Purpose
The purpose of this prompt is to assist HR staff in reviewing and categorising employee complaints based on the information provided. It aims to make the initial complaint-handling process more efficient, organised and consistent by identifying the nature of each complaint and determining which issues may require further investigation or escalation.

## 3. Prompt
``` text
You are an experienced HR assistant responsible for supporting the fair and consistent review of employee complaints.

Review and categorise an employee complaint submitted to [COMPANY_NAME] based on the information provided by the employee.

Use the following information:
- Employee name: [EMPLOYEE_NAME]
- Department: [DEPARTMENT]
- Date complaint received: [DATE_RECEIVED]
- Employee complaint: [INSERT_COMPLAINT_DETAILS]

Include the following sections:
1. Complaint summary
2. Main issues or concerns raised
3. Complaint category (e.g. bullying, discrimination, harassment, workplace conflict, workload, management concerns or workplace safety)
4. Relevant people, departments or work areas mentioned
5. Key events, dates and details identified
6. Missing or unclear information requiring clarification
7. Potential urgency or safety concerns requiring HR attention
8. Suggested next steps for HR review

Tone: neutral, respectful, confidential and professional.

Output: Generate a structured employee complaint categorisation report clearly numbered sections, concise explanations and bullet points where appropriate.
```

**Placeholders to fill**
| Placeholder | Source | Example (ABC Retail) |
|---|---|---|
| [COMPANY_NAME] | Organisation details | ABC Retail |
| [EMPLOYEE_NAME] | Employee complaint form | Sarah Mitchell |
| [EMPLOYEE_REFERENCE] | HR employee records | EMP-024 |
| [DEPARTMENT] | Employee records | Customer Service |
| [JOB_TITLE] | Employee records | Retail Sales Assistant |
| [DATE_RECEIVED] | HR complaint records | 25 November 2026 |
| [EMPLOYEE_COMPLAINT] | Employee complaint form | My supervisor has repeatedly criticised my work during team meetings and assigned me additional tasks compared with other team members. |
| [PEOPLE_INVOLVED] | Employee complaint form | Sarah Mitchell (employee), Store Supervisor |
| [WORK_AREA] | Employee complaint form | Melbourne Store |
| [KEY_EVENTS_AND_DATES] | Employee complaint form | Repeated incidents during the past few weeks |
| [SUPPORTING_INFORMATION] | Documents provided by the employee | Relevant emails and meeting records |
| [PREVIOUS_ACTIONS] | Employee complaint form or HR records | Employee previously raised concerns with their supervisor |
| [SAFETY_CONCERNS] | Employee complaint form | Employee reports feeling uncomfortable attending team meetings |
| [ADDITIONAL_INFORMATION] | Additional information provided to HR | Employee has requested HR assistance |

## 4. Intended Task
The intended task is to support the initial review and categorisation stage of the employee complaint-handling process. HR staff can use this prompt to organise incoming complaints, identify the main concerns and determine which organisations policies may need to be reviewed before deciding how to proceed. This helps HR manage complaints in a more structured and consistent way.

## 5. Problem Being Solved
Reviewing and organising multiple employee complaints can be time-consuming, particularly when complaints involve different workplace issues. HR staff. may find it difficult to identify the main concern when employees provide lengthy or unclear descriptions of their experiences. This prompt addresses these challenges by summarising and categorising complaint information into a consistent report, helping HR staff understand the issues raised and organise complaints for further review.

## 6. Automation Potential
This prompt has the potential to automate parts of the initial employee complaint-handling process. 

**Potential Automation Activities:**
- Summarise employee complaints
- Identify the main issues and concerns raised
- Categorise complaints based on their nature
- Extract relevant dates, events and people mentioned
- Identify missing or unclear information
- Highlight potential urgency or safety concerns
- Prepare structured reports for HR review

**Human Involvement:**
HR staff must review the categorisation, assess the seriousness of the complaint and determine the appropriate next steps. Sensitive or serious complaints must be handled by appropriately authorised personnel. AI should support the administrative process rather than independently investigation complaints, determine whether allegation are true or make disciplinary decisions.

## 7. Risks and Limitations 
**Potential Risks:**
- **Misclassification:** AI may place a complaint into the wrong category or overlook important details.
- **Bias:** AI may interpret complaints unfairly or reflect bias in the information provided.
- **Privacy:** Employee complaints may contain sensitive personal and workplace information that must be protected.
- **Inaccurate Interpretation:** AI may misunderstand the employee's concerns or remove important context when summarising the complaint.
- **Underestimating Seriousness:** AI may fail to recognise complaints involving serious misconduct, harassment, discrimination or workplace safety.
- **Over-reliance:** HR staff may depend too heavily on AI-generated categories instead of reviewing the original complaint.

**Limitations:**
- AI can only assess the information provided in the complaint
- Unclear or incomplete complaints may result in inaccurate categorisation
- AI cannot determine whether allegations are true
- AI cannot replace a formal workplace investigation
- Human judgement is required to assess sensitive complaints and determine appropriate action

**Risk Mitigation:**
Protect employee information, use neutral and consistent complaint categories, verify AI-generated summaries, prioritise urgent safety concerns and require authorised HR staff to review all complain reports before taking action.

## 8. Testing and Evaluation 
The prompt will be tested using sample employee complaints involving different workplace issues, such as bullying, discrimination, workplace conflict and workload concerns.
**Testing Method:**
1. Prepare sample employee complaints covering different workplace situations
2. Provide the complaint information to the AI
3. Run the employee complaint categorisation prompt
4. Review the generated complaint report
5. Compare the categorisation against the actual issues described in the complaint
6. Check whether important details or potential safety concerns have been identified
7. Identify errors, missing information or possible bias
8. Refine the prompt where necessary and test again

**Evaluation Criteria:**
| Evaluation Area | What to Check |
|---|---|
| Accuracy | Does the prompt correctly identify the main concerns raised? |
| Relevance | Does it assign an appropriate category to the complaint? |
| Consistency | Does it categorise similar complaints in a consistent way? |
| Fairness | Does it use neutral language and avoid making assumptions? |
| Privacy | Does it handle employee information appropriately? |
| Output Quality | Is the complaint report clear, organised and useful for HR review? |

**Success Measures:**
The prompt should produce accurate, relevant and consistent complaint reports while reducing repetitive administrative work and helping HR staff organise complaints for further review.

## 9. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial employee complaint categorisation prompt created. | Establish the basic complaint review structure. |
| V1.1 | Added complaint categories and instructions to use neutral language and avoid assumptions. | Improve consistency and fairness when reviewing complaints. |
| V1.2 | Added urgency identification, privacy safeguards and human review requirements. | Improve complaint handling and reduce risks associated with sensitive workplace issues. |

**Current Version:** V1.2

**Status:** TESTED.
