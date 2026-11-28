# Prompt 07: Employee Complaint Response

## 1. Workflow

**Workflow Name:** Employee Complaints

**Workflow Stage:** Complaint Response

**Previous Prompt:** Prompt 06 - HR Policy Review

**Next Prompt:** Workflow 3 - Performance Management

**Workflow Description:**
This prompt is used after an employee complaint has been categorised and reviewed against relevant organisational policies. It helps HR staff prepare a professional and appropriate response to the employee, outlining the next steps and explaining how the complaint will be handled.

## 2. Purpose
The purpose of this prompt is to assist HR staff in preparing clear, respectful and professional responses to employee complaints. It aims to improve the consistency and efficiency of complaint communication while ensuring employees receive appropriate acknowledgement, information about the complaint-handling process and guidance on the next steps.

## 3. Prompt
``` text
You are an experienced HR assistant responsible for preparing professional, fair and respectful responses to employee complaints.

Review the employee complaint, complaint categorisation report and relevant HR policy review findings. Use this information to draft an appropriate response that acknowledges the employee's concerns, explains the relevant next steps and provides information about the complaint-handling process.

Use the following information:
- Company name: [COMPANY_NAME]
- Employee name: [EMPLOYEE_NAME]
- Employee email address: [EMPLOYEE_EMAIL]
- Department: [DEPARTMENT]
- Date complaint received: [DATE_RECEIVED]
- Employee complaint: [EMPLOYEE_COMPLAINT]
- Complaint categorisation report: [COMPLAINT_CATEGORISATION_REPORT]
- HR policy review findings: [HR_POLICY_REVIEW_FINDINGS]
- Next steps identified by HR: [HR_NEXT_STEPS]
- Additional information required from employee: [ADDITIONAL_INFORMATION_REQUIRED]
- HR contact name: [HR_CONTACT_NAME]
- Available support information: [SUPPORT_INFORMATION]

Include the following sections:
1. Email subject line
2. Greeting
3. Acknowledgement of complaint
4. Brief summary of concerns
5. Explanation of relevant complaint-handling process
6. Information about the next steps HR intends to take, based on details provided
7. Any additional information or documentation required from the employee
8. Relevant contact or support information where provided
9. Professional closing

Tone: supportive, respectful and understanding

Output: Generate a structured employee complaint response in email format, with a clear subject line, professional greeting, organised paragraphs and appropriate closing.

Do not include: assumptions, promises about complaint outcomes or unconfirmed timeframes, confidential information about other employees, unsupported statements or conclusions that a final decision has been made.
```

**Placeholders to fill:**
| Placeholder | Source | Example (ABC Retail) |
|---|---|---|
| [COMPANY_NAME] | Organisation details | ABC Retail |
| [EMPLOYEE_NAME] | Employee complaint records | Sarah Mitchell |
| [EMPLOYEE_EMAIL] | Employee records | sarah.mitchell@example.com |
| [DEPARTMENT] | Employee records | Customer Service |
| [DATE_RECEIVED] | HR complaint records | 25 November 2026 |
| [EMPLOYEE_COMPLAINT] | Original employee complaint | Complaint about repeated public criticism by a supervisor and concerns about unequal workload distribution |
| [COMPLAINT_CATEGORISATION_REPORT] | Prompt 05 – Employee Complaint Categorisation | Workplace conflict, management concerns and potential bullying requiring further assessment |
| [HR_POLICY_REVIEW_FINDINGS] | Prompt 06 – HR Policy Review | Relevant Workplace Bullying and Harassment Policy and Employee Grievance Procedure identified for review |
| [HR_NEXT_STEPS] | HR review findings | Arrange a confidential discussion with the employee and review the reported incidents |
| [ADDITIONAL_INFORMATION_REQUIRED] | HR review findings | Specific dates, examples of incidents and any relevant supporting emails |
| [HR_CONTACT_NAME] | HR department contact details | Emily Carter |
| [HR_CONTACT_EMAIL] | ABC Retail HR contact details | hr@abcretail.example.com |
| [SUPPORT_INFORMATION] | ABC Retail employee support information | Employee Assistance Program (EAP), if available |

## 4. Intended Task
The intended task is to support the complaint response stage of the employee complaint-handling process. HR staff can use this prompt to prepare responses after reviewing and categorising a complaint and checking the relevant organisational policies. This helps ensure employees receive consistent communication, understand the next steps and know how their concerns will be handled.

## 5. Problem Being Solved
Responding to employee complaints can be challenging, particularly when complaints involve sensitive workplace issues or require careful communication. HR staff may also spend considerable time preparing individual responses while ensuring that messages remain professional, respectful and consistent with organisations procedures.
This prompt addresses these challenges by generating structured responses based on the complaint details and relevant policy review findings. It helps reduce repetitive administrative work while supporting clear and consistent communication with employees.

## Automation Potential
This prompt has the potential to automate parts of the employee complaint response process.

**Potential Automation Activities:**
- Draft complaint acknowledgement emails
- Summarise the employee's concerns in a response
- Prepare explanations of complaint-handling procedures
- Generate messages outlining the next steps
- Identify additional information that may be required
- Prepare consistent and professional response templates
- Include relevant contact and support information supplied by HR

**Human Involvement:** 
HR staff must review the complaint, confirm the accuracy of the response and determine the appropriate communication approach. Sensitive or serious complaints must be handled by authorised HR personnel. AI should assist with drafting responses rather than independently investigating complaints, making disciplinary decisions or determining complaint outcomes.

## 7. Risks and Limitations
**Potential Risks:**
- **Inappropriate Communication:** AI may produce wording that sounds insensitive or dismissive of the employee's concerns.
- **Inaccurate Information:** AI may provide incorrect details about policies, procedures or complaint-handling timeframes.
- **Privacy:** Employee complaints may contain confidential or sensitive personal information that must be protected.
- **Confidentiality Breaches:** AI may include information about other employees that should not be disclosed.
- **Unrealistic Promises:** AI may suggest outcomes or timeframes that HR has not confirmed.
- **Over-reliance:** HR staff may depend too heavily on AI-generated responses without checking their suitability.

**Limitations:**
- AI can only use the complaint details and policy information provided
- Missing information may result in incomplete responses
- AI cannot determine whether allegations are true
- AI cannot independently resolve workplace disputes or conduct formal investigations
- Human judgement is required when responding to sensitive or complex complaints

**Risk Mitigation:**
Use accurate and approved information, protect employee confidentiality, avoid promising unconfirmed outcomes, verify all policy references and require authorised HR staff to review and approve responses before sending them.

## 8. Testing and Evaluation
The prompt will be tested using sample employee complaints, complaint categorisation reports and relevant HR policy review findings.

**Testing Method:**
1. Prepare a sample complaint
2. Complete the complaint categorisation process using Prompt 05
3. Review the complaint against relevant HR policies using Prompt 06
4. Provide the complaint details and policy review findings to the AI
5. Run the employee complaint response prompt
6. Review the generated response for accuracy, professionalism and clarity
7. Check whether the response explains the next steps without making unsupported promises or disclosing confidential information
8. Refine the prompt where necessary and test again

**Evaluation Criteria:**
| Evaluation Area | What to Check |
|---|---|
| Accuracy | Does the response correctly reflect the complaint and HR findings? |
| Relevance | Does the message address the employee's concerns and the appropriate next steps? |
| Professionalism | Is the response respectful, supportive and appropriate? |
| Confidentiality | Does it avoid disclosing private or unnecessary information? |
| Consistency | Does it follow the organisation's complaint-handling procedures? |
| Output Quality | Is the response clear, organised and suitable for HR review? |

**Success Measures:**
The prompt should produce accurate, professional and consistent complaint responses while reducing repetitive administrative work and supporting clear communication between HR and employees.

## 9. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial employee complaint response prompt created. | Establish the basic complaint response structure. |
| V1.1 | Added instructions to use complaint categorisation and HR policy review findings. | Improve relevance and consistency of responses. |
| V1.2 | Added confidentiality safeguards, communication requirements and mandatory HR approval. | Reduce communication risks and ensure appropriate human oversight. |

**Current Version:** V1.2

**Status:** TESTED.
