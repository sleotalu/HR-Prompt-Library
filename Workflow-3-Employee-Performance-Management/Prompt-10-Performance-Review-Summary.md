# Prompt 10: Performance Review Summary

## 1. Workflow

**Workflow Name:** Employee Performance Management

**Workflow Stage:** Performance Review Summary

**Previous Prompt:** Prompt 09 - Employee Development Plan

**Next Prompt:** None - Final stage of Workflow 3

**Workflow Description:**
This prompt is used after employee performance feedback has been prepared and an employee development plan has been created. It helps HR staff and managers consolidate employee performance information, feedback and development activities into a structured performance review summary.

## 2. Purpose
The purpose of this prompt is to assist HR staff and manager in preparing clear and organised employee performance review summaries. It aims to make the performance review process more efficient, structured and consistent by bringing together employee achievements, performance feedback, areas for improvement and development progress. It also helps managers maintain a clear record of employee performance and identify any follow-up actions required for continued employee development.

## 3. Prompt
``` text
You are an experienced HR performance management assistant responsible for helping managers prepare fair and professional employee performance review summaries.

Review the employee's performance feedback, development plan and progress. Summarise achievements, improvements and any remaining development needs.

Use the following information:
- Company name: [COMPANY_NAME]
- Employee name: [EMPLOYEE_NAME]
- Job title: [JOB_TITLE]
- Department: [DEPARTMENT]
- Manager name: [MANAGER_NAME]
- Review period: [REVIEW_PERIOD]
- Previous performance feedback: [PERFORMANCE FEEDBACK]
- Employee development plan: [DEVELOPMENT_PLAN]
- Progress and achievements: [PROGRESS_AND_ACHIEVEMENTS]
- Outstanding development areas: [OUTSTANDING_DEVELOPMENT_AREAS]
- Manager observations: [MANAGER_OBSERVATIONS]

Include the following sections:
1. Employee details and review period
2. Previous performance feedback summary
3. Progress against development goals
4. Key achievements and improvements
5. Outstanding development areas
6. Overall performance review summary
7. Recommend future development actions
8. Suggested next review arrangements

Tone: balanced, constructive, supportive and professional.

Output: Generate a structured performance review summary with numbered sections and a table where appropriate.

Do not include: invented achievements, assumptions, unsupported judgements or final employment, promotion or disciplinary deicions.

Important: Use only the information provided. Identify missing information and ensure managers and HR review the summary before discussing it with the employee.
```

**Placeholders to fill:**
| Placeholder | Source | Example (ABC Retail) |
|---|---|---|
| [COMPANY_NAME] | Organisation details | ABC Retail |
| [EMPLOYEE_NAME] | Employee records | James Wilson |
| [JOB_TITLE] | Employee records | Retail Sales Assistant |
| [DEPARTMENT] | Employee records | Sales Department |
| [MANAGER_NAME] | Management records | Emily Carter |
| [REVIEW_PERIOD] | Performance review schedule | 1 October – 31 December 2026 |
| [PERFORMANCE_FEEDBACK] | Prompt 08 – Performance Feedback | Positive customer service, with improvement needed in product knowledge |
| [DEVELOPMENT_PLAN] | Prompt 09 – Employee Development Plan | Product training and manager mentoring |
| [PROGRESS_AND_ACHIEVEMENTS] | Employee progress records | Completed product training and improved customer service confidence |
| [OUTSTANDING_DEVELOPMENT_AREAS] | Development progress records | Improve product knowledge and handling complex enquiries |
| [MANAGER_OBSERVATIONS] | Manager review notes | Demonstrates improved confidence and consistent customer service |

## 4. Intended Task
The intended task is to support the final performance review summary stage of the employee performance management process. HR staff and managers can use this prompt to consolidate employee performance information, feedback and development progress into one structured report. This helps organisations maintain consistent performance record, monitor employee development and identify appropriate follow-up actions for future performance reviews.

## 5. Problem Being Solved
Preparing performance review summaries can be time-consuming when managers need to gather information from different performance records, feedback reports and employee development plans. Important achievements, improvement areas or outstanding development activities may also be overlooked when information is recorded across multiple documents.
This prompt addresses these challenges by consolidating employee performance information into a structured summary, helping HR staff and managers maintain accurate records and make informed decisions about future employee development.

## 6. Automation Potential
This prompt has the potential to automate parts of the employee performance review summarisation process.

**Potential Automation Activities:**
- Consolidate information from employee performance feedback reports
- Summarise employee achievements and contributions
- Organise identified strengths and improvement areas
- Review documented progress against development goals
- Identify completed and outstanding development activities
- Generate structured employee performance review summaries
- Identify missing information requiring further review
- Prepare draft performance review records for manager approval

**Human Involvement:**
HR staff and managers must verify all information included in the performance review summary and confirm that development progress is supported by actual records. Managers must discuss the review with the employee, clarify any outstanding information and approve the final summary. AI should support performance review documentation rather than independently assess employees or make employment decisions.

## 7. Risks and Limitations
**Potential Risks:**
- **Inaccurate Summaries:** AI may misunderstand employee performance information or incorrectly summarise achievements and feedback.
- **Incorrect Development Progress:** AI may assume that development activities have been completed when supporting evidence has not been provided.
- **Bias:** AI may produce unfair or unbalanced summaries based on incomplete or subjective performance information.
- **Privacy:** Performance review records may contain confidential employee and employment information.
- **Missing Information:** AI may overlook important achievements, improvement areas or outstanding development goals.
- **Over-reliance:** Managers may depend too heavily on AI-generated summaries without checking the original performance records.

**Limitations:**
- AI can only summarise the employee information and records provided
- Incomplete performance records may result in an inaccurate or incomplete review summary
- AI cannot independently verify employee achievements or development progress
- AI cannot determine whether an employee has met workplace expectations without sufficient evidence
- Human judgement is rewuired to assess employee performance and make final employment-related decisions

**Risk Mitigation:**
Provide accurate and current employee performance records, verify all generated summaries against the original documents, protect confidential employe information and require authorised managers or HR staff to review and approve the final performance review summar.

## 8. Testing and Evaluation
The prompt will be tested using sample employee performance feedback, development plans and employee progress records.

**Testing Method:**
1. Prepare a sample employee performance feedback report generated using Prompt 08
2. Prepare a corresponding employee development plan generated using Prompt 09
3. Provide additional employee progress information, including completed and outstanding development activities
4. Run the Performance Review Summary prompt
5. Review the generated employee performance review summary
6. Compare the summary against the original performance feedback and development plant
7. Check whether employee achievements, improvement areas and development progress are accurately represented
8. Identify missing information, incorrect summaries or unsupported conclusions
9. Refine the prompt where necessary and test again

**Evaluation Criteria:**
| Evaluation Area | What to Check |
|---|---|
| Accuracy | Does the prompt correctly summarise the supplied performance information and development records? |
| Relevance | Does the summary focus on the employee's responsibilities, achievements and development goals? |
| Consistency | Does it organise performance review information consistently across different employees? |
| Completeness | Does it include achievements, improvement areas and development progress? |
| Reliability | Does it avoid inventing information or making unsupported conclusions? |
| Output Quality | Is the performance review summary clear, organised and useful for HR staff and managers? |

**Success Measures:**
The prompt should produce accurate, relevant and complete employee performance review summaries while reducing administrative workload and improving consistency in performance documentation.

## 9. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial performance review summary prompt created. | Establish the basic performance review summary structure. |
| V1.1 | Added instructions to consolidate performance feedback, achievements and development goals. | Improve the completeness and relevance of review summaries. |
| V1.2 | Added safeguards against inaccurate development progress, unsupported conclusions and privacy risks. | Improve reliability and ensure appropriate HR oversight. |

**Current Version:** V1.2

**Status:** Ready for testing and evaluation.
