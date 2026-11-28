# Prompt 08: Performance Feedback

## 1. Workflow

**Workflow Name:** Employee Performance Management 

**Workplace Stage:** Performance Feedback

**Previous Prompt:** Workflow 2 - Employee Complaints, Prompt 07 - Employee Complaint Response

**Next Prompt:** Prompt 09 - Employee Development Plan

**Workflow Description:** 
This prompt is used after employee performance information has been collected and reviewed. It helps HR staff and managers prepare constructive performance feedback by identifying employee strengths, achievements and areas requiring improvement.

## 2. Purpose
The purpose of this prompt is to assist HR staff and managers in preparing clear, balanced and constructive employee performance feedback. It aims to make the performance feedback process more efficient, structured and consistent by recognising employee contributions, identifying areas for improvement and providing practical suggestions to support employee development.

## 3. Prompt
``` text
You aren’t e an experienced HR performance management assistant responsible for helping manager prepare fair, constructive and professional employee feedback.

Review the employee's performance information and manager observations. Identify strengths, achievements and areas requiring improvement. Provide constructive feedback and practical recommendations to support employee development.

Use the following information:
- Company name: [COMPANY_NAME]
- Employee name: [EMPLOYEE_NAME]
- Job title: [JOB_TITLE]
- Department: [DEPARTMENT]
- Manager name: [MANAGER_NAME]
- Review period: [REVIEW_PERIOD]
- Job responsibilities: [JOB_RESPONSIBILITIES]
- Performance goals: [PERFORMANCE_GOALS]
- Achievements: [ACHIEVEMENTS]
- Manager observations: [MANAGER_OBSERVATIONS}
- Improvement areas: [IMPROVEMENT_AREAS]
- Supporting information: [SUPPORTING_INFORMATION]

Include the following sections:
1. Employee role and review period summary
2. Key strengths and achievements
3. Areas of good performance
4. Areas requiring improvement
5. Constructive performance feedback
6. Practical improvement recommendations
7. Suggested training and development opportunities
8. Overall performance summary
9. Recommend next steps for manager and HR

Tone: fair, balances, supportive and professional

Output: Generate a structured performance feedback report with numbered sections and concise explanations.

Do not include: unsupported judgements, assumptions, invented achievements or final employment, promotion or disciplinary decisions.

Important: Use only the information provided. Identify any missing evidence and ensure managers and HR review the feedback before communicating it to the employee.
```

**Placeholders to fill:**
| Placeholder | Source | Example (ABC Retail) |
|---|---|---|
| [COMPANY_NAME] | Organisation details | ABC Retail |
| [EMPLOYEE_NAME] | Employee records | James Wilson |
| [JOB_TITLE] | Employee records | Retail Sales Assistant |
| [DEPARTMENT] | Employee records | Sales Department |
| [MANAGER_NAME] | Management records | Emily Carter |
| [REVIEW_PERIOD] | Performance review schedule | 1 July – 30 September 2026 |
| [JOB_RESPONSIBILITIES] | Employee job description | Customer service, sales transactions and store presentation |
| [PERFORMANCE_GOALS] | Employee performance plan | Improve customer service and achieve sales targets |
| [ACHIEVEMENTS] | Employee performance records | Positive customer feedback and organised product displays |
| [MANAGER_OBSERVATIONS] | Manager review notes | Demonstrates a positive attitude and helpful customer service |
| [IMPROVEMENT_AREAS] | Manager observations | Improve product knowledge and confidence when handling enquiries |
| [SUPPORTING_INFORMATION] | Performance records | Customer feedback and sales reports |

## 4. Intended Task
The intended task is to support the performance management process. HR staff and manager can use this prompt to prepare structured feedback based on employee achievements, workplace performance and areas requiring improvement. This helps managers communicate performance expectations more effectively while providing employee with a clearer understanding of their strengths and opportunities for professional growth.

## 5. Problem Being Solved
Preparing employee performance feedback can be time-consuming, particularly when managers need to review different performance indicators, identify improvement areas and communicate feedback professionally. Managers may also provide inconsistent feedback or struggle to balance positive recognition with constructive criticism.
This prompt addresses these challenges by organising employee performance information into a structured feedback report, helping managers recognise achievements, communicate improvement areas and provide practical recommendations.

## 6. Automation Potential
This prompt has the potential to automate parts of the employee performance feedback process.

**Potential Automation Activities:**
- Organise employee performance information
- Identify employee strengths and achievements from supplied evidence
- Highlight areas requiring improvement
- Generate constructive performance feedback
- Suggest practical performance improvement actions
- Identify potential training and development needs
- Generate structured employee performance feedback reports
- Prepare draft feedback for manager review

**Human Involvement:**
Managers and HR must verify the accuracy of the generated feedback, ensure that it is fair and supported by evidence, and make any necessary adjustments before communicating it to the employee. Sensitive performance concerns may require additional HR involvement. AI should support feedback preparation rather than independently evaluate employees or make employment decisions.

## 7. Risks and Limitations
**Potential Risks:**
- **Bias:** AI may generate unfair or biased feedback if supplied performance information is incomplete or subjective.
- **Inaccurate Information:** AI may misunderstand manager observations or generate unsupported statements about employee performance.
- **Privacy:** Employee performance records may contain confidential personal and employment information.
- **Lack of context:** AI may not understand workplace circumstances that have affected an employee's performance.
- **Inconsistent Feedback:** AI may produce different feedback for employees with similar performance if the information provided varies.
- **Over-reliance:** Managers may depend too heavily on AI-generated feedback without applying their own judgement.

**Limitations:**
- AI can only assess the performance information and observations provided
- Incomplete performance records may result in inaccurate or insufficient feedback
- AI cannot independently verify employee achievements or workplace incidents
- AI cannot fully understand individual employee circumstances or workplace relationships
- Human judgement is required to assess performance fairly and communicate appropriately

**Risk Mitigation:**
Provide accurate and relevant employee performance information, protect confidential employee records, review all AI-generated feedback against actual evidence and require authorised managers or HR staff to approve the final feedback before sharing it with employees.

## 8. Testing and Evaluation
This prompt will be tested using sample employee performance information, workplace goals and manager observations.

**Testing Method:**
1. Prepare sample employee performance information, including job responsibilities, achievements and performance goals
2. Provide manager observations identifying employee strengths and areas requiring improvement
3. Run the Performance Feedback Generator prompt
4. Review the generated feedback against the original employee information
5. Check whether the prompt correctly identifies achievements and improvement areas
6. Identify unsupported statements, biased language or missing recommendations
7. Refine the prompt where necessary and test again

**Evaluation Criteria:**
| Evaluation Area | What to Check |
|---|---|
| Accuracy | Does the prompt correctly reflect the employee performance information provided? |
| Relevance | Is the feedback relevant to the employee's job responsibilities and performance goals? |
| Consistency | Does it produce balanced feedback for employees with similar performance information? |
| Completeness | Does it identify important strengths, achievements and improvement areas? |
| Reliability | Does it avoid unsupported judgements and invented performance information? |
| Output Quality | Is the feedback clear, constructive, professional and useful for managers? |

**Success Measures:**
The prompt should produce accurate, relevant and constructive performance feedback while reducing the time managers spend preparing employee reviews and improving consistency in workplace feedback.

## 9. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial performance feedback prompt created. | Establish the basic performance feedback structure. |
| V1.1 | Added instructions to identify employee strengths, achievements and improvement areas using supplied performance information. | Improve feedback relevance and consistency. |
| V1.2 | Added safeguards against bias, unsupported judgements and privacy risks. | Improve reliability and ensure appropriate HR oversight. |

**Current Version:** V1.2 

**Status:** TESTED.
