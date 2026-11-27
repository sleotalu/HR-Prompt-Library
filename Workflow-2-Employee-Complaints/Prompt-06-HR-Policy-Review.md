# Prompt 06: HR Policy Review

## 1. Workflow

**Workflow Name:** Employee Complaints

**Workflow Stage:** HR Policy Review

**Previous Prompt:** Prompt 05 - Employee Complaint Categorisation

**Next Prompt:** Prompt 07 - Complaint Response

**Workflow Description:** 
This prompt is used after an employee complaint has been reviewed and categorised. It helps HR staff identify and examine relevant organisational policies, procedures and workplace guidelines to determine which requirements may apply to the complaint. 

## 2. Purpose
The purpose of this prompt is to assist HR staff in reviewing employee complaints against relevant organisational policies and procedures. It aims to make the policy review process more efficient, structures and consistent by identifying relevant policy requirements, highlighting possible areas of concern and helping HR determine the appropriate next steps.

## 3. Prompt
``` text
You are an experienced HR policy assistant responsible for supporting the review of workplace complaints against organisational policies and procedures.

Review the employee complaint categorisation report and compare the issues raised against the relevant HR policies, procedures and workplace guidelines provided by [COMPANY_NAME].

Use the following information:
- Company name: [COMPANY_NAME]
- Employee name: [EMPLOYEE_NAME]
- Department: [DEPARTMENT]
- Date complaint received: [DATE_RECEIVED]
- Employee complaint categorisation report: [COMPLAINT_CATEGORISATION_REPORT]
- Relevant HR policies and procedures: [HR_POLICIES_AND_PROCEDURES]
- Supporting documents or evidence: [SUPPORTING_DOCUMENTS]

Include the following sections:
1. Summary of the employee complaint
2. Main workplace issues identified
3. Relevant HR policies and procedures
4. Specific policy requirements that may apply
5. Explanation of how the complaint relates to the identified policies
6. Potential areas of non-compliance or concern requiring further review
7. Missing information or evidence needed for assessment
8. Suggested next steps for HR staff
9. Recommendations for appropriate HR follow-up

Tone: neutral, objective, respectful and professional

Output: Generate a structured HR policy review report with clearly numbered sections, concise explanations and bullet points where appropriate.

Do not include: invented policy requirements, assumptions, legal conclusions, final determinations that a policy has been breaches, or conclusions that an employee is responsible for misconduct.
```

**Placeholders to fill:**
| Placeholder | Source | Example (ABC Retail) |
|---|---|---|
| [COMPANY_NAME] | Organisation details | ABC Retail |
| [EMPLOYEE_NAME] | Employee complaint records | Sarah Mitchell |
| [DEPARTMENT] | Employee records | Customer Service |
| [DATE_RECEIVED] | HR complaint records | 25 November 2026 |
| [COMPLAINT_CATEGORISATION_REPORT] | Prompt 05 – Employee Complaint Categorisation | Complaint involving repeated public criticism by a supervisor and concerns about unequal workload distribution |
| [HR_POLICIES_AND_PROCEDURES] | ABC Retail HR policy documents | Workplace Bullying and Harassment Policy, Employee Grievance Procedure and Equal Employment Opportunity Policy |
| [SUPPORTING_DOCUMENTS] | Documents provided by the employee or HR | Relevant emails, meeting records and previous complaint correspondence |

## 4. Intended Task
The intended task is to support the HR policy review stage of the employee complaint-handling process. HR staff use this prompt to compare the issues identified in an employee complaint against relevant organisational policies and procedures. This helps HR understand which workplace requirements may apply before preparing an appropriate response or deciding whether further investigation is necessary. 

## 5. Problem Being Solved
Reviewing employee complaints against multiple organisational policies can be time-consuming and difficult, particularly when complaints involve several workplace issues. HR staff may also overlook policy requirements or interpret workplace procedures inconsistently. This prompt addresses these challenged by organising relevant policy information into a structured report, helping HR staff identify applicable requirements and areas that need further attention. 

## 6. Automation Potential
This prompt has the potential to automate parts of the HR policy review process.

**Potential Automation Activities:**
- Identify relevant HR policies and procedures from supplied documents
- Compare complaint details against policy requirements
- Extract relevant sections of organisational policies
- Highlight possible areas of concern or non-compliance
- Identify missing information required for further assessment
- Generate structured policy review reports
- Suggest appropriate next steps for HR consideration

**Human Involvement:**
HR staff must verify the relevant policies, assess the complaint and determine whether further investigation or action is required. Serious or sensitive complaints may require involvement from senior HR staff or other appropriately qualified professionals. AI should support policy review rather than independently determine policy breaches or make disciplinary decisions. 

## 7. Risks and Limitations
**Potential Risks:** 
- **Incorrect Policy Interpretation:** AI may misunderstand policy wording or apply a policy incorrectly to the complaint.
- **Outdated Information:** AI may rely on outdated policy documents if the organisation does not provide the latest versions.
- **Inaccurate Conclusions:** AI may incorrectly suggest that a policy has been breached without sufficient evidence.
- **Privacy:** Employee complaints and supporting documents may contain confidential or sensitive personal information.
- **Overlooking Relevant Policies:** AI may fail to identify a policy that is important to the complaint.
- **Over-reliance:** HR staff may depend too heavily on AI-generated policy reviews without checking the original documents.

**Limitations:**
- AI can only review the policies and information provided
- Missing or outdated policy documents may result in incomplete assessments
- AI cannot independently verify whether a workplace incident occurred
- AI cannot replace formal HR investigations or professional legal advice
- Human judgement is required to interpret policies in the context of individual circumstances

**Risk Mitigation:**
Provide current and approved organisational policies, verify all policy references against the original documents, protect employee information and require HR staff to review the findings before making decisions.

## 8. Testing and Evaluation
The prompt will be tested using sample employee complaints and relevant organisational HR policies.

**Testing Method:** 
1. Prepare a sample employee complaint and its categorisation report from Prompt 05
2. Provide the relevant organisational HR policies and procedures
3. Run the HR policy review prompt
4. Review the generated policy review report
5. Compare the identified policies and requirements against the actual policy documents
6. Check whether the prompt correctly identifies relevant requirements and areas needing further review
7. Identify incorrect interpretations, missing policy references or unsupported conclusions
8. Refine the prompt where necessary and test again

**Evaluation Criteria:**
| Evaluation Area | What to Check |
|---|---|
| Accuracy | Does the prompt correctly identify information from the supplied policies? |
| Relevance | Are the identified policies relevant to the employee complaint? |
| Consistency | Does it apply policy requirements consistently across similar complaints? |
| Completeness | Does it identify important policy requirements and missing information? |
| Reliability | Does it avoid making unsupported conclusions about policy breaches? |
| Output Quality | Is the policy review report clear, organised and useful for HR staff? |

**Success Measures:**
The prompt should produce accurate, relevant and consistent policy review reports while reducing the time HR staff spend locating and reviewing policy information.

## 9. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial HR policy review prompt created. | Establish the basic policy review structure. |
| V1.1 | Added instructions to compare complaints against supplied policies and identify relevant requirements. | Improve policy relevance and assessment consistency. |
| V1.2 | Added safeguards against unsupported conclusions, outdated information and privacy risks. | Improve reliability and ensure appropriate HR oversight. |

**Current Version:** V1.2

**Status:** Ready for testing and evaluation.
