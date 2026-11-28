# Prompt 10: Performance Review Summary 

## 1. Overview
This document records the iterative development of prompt 10 - Performance Review Summary. The prompt was refined through three versions to improve the completeness, consistency and usefulness of employee performance review summaries.

The iterations focused on establishing a basic performance review structure, consolidating performance feedback and achievements, and improving the final prompt by including progress against development goals, outstanding development needs, future development actions and review arrangements.

## 2. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial performance review summary prompt created. | Establish the basic performance review summary structure. |
| V1.1 | Added instructions to consolidate performance feedback, achievements and development goals. | Improve the completeness and relevance of review summaries. |
| V1.2 | Added safeguards against inaccurate development progress, unsupported conclusions and privacy risks. | Improve reliability and ensure appropriate HR oversight. |

## 3. Version Comparison Screenshot
The screenshots below provide visual evidence of the prompt's development across two specific versions due to being limited to compare between two checkpoints at a time.

## 4. Prompt Versions
``` text
### Version 1.0 - Initial Performance Review Summary Prompt

You are an experienced HR assistant responsible for helping managers prepare fair and professional employee performance review summaries.

Review the employee's performance information and prepare a summary of their overall performance during the review period. Highlight key achievements, areas for improvement and recommended next steps.

Use the following information:
- Company name: [COMPANY_NAME]
- Employee name: [EMPLOYEE_NAME]
- Job title: [JOB_TITLE]
- Department: [DEPARTMENT]
- Manager name: [MANAGER_NAME]
- Review period: [REVIEW_PERIOD]
- Performance information: [PERFORMANCE_INFORMATION]
- Manager observations: [MANAGER_OBSERVATIONS]

Include the following sections:
1. Employee details and review period
2. Performance summary
3. Key achievements
4. Areas requiring improvement
5. Overall performance review
6. Recommended next steps

Tone: balanced, constructive, supportive and professional

Output: Generate a structured employee performance review summary using clear headings and concise explanations.

Do not include: invented achievements, unsupported assumptions or unfair judgements.
```

### Version 1.1 - Improved Prompt
``` text
You are an experienced HR performance management assistant responsible for helping managers prepare fair and professional employee performance review summaries.

Review and consolidate the employee's previous performance feedback, achievements and development goals. Summarise their progress, identify areas of improvement and highlight any remaining development needs.

Use the following information:
- Company name: [COMPANY_NAME]
- Employee name: [EMPLOYEE_NAME]
- Job title: [JOB_TITLE]
- Department: [DEPARTMENT]
- Manager name: [MANAGER_NAME]
- Review period: [REVIEW_PERIOD]
- Previous performance feedback: [PERFORMANCE_FEEDBACK]
- Development goals: [DEVELOPMENT_GOALS]
- Employee achievements: [ACHIEVEMENTS]
- Manager observations: [MANAGER_OBSERVATIONS]

Include the following sections:
1. Employee details and review period
2. Summary of previous performance feedback
3. Progress against development goals
4. Key achievements and improvements
5. Remaining development needs
6. Overall performance review summary
7. Recommended next steps

Tone: balanced, constructive, supportive and professional

Output: Generate a structured performance review summary with numbered sections and concise explanations.

Do not include: invented achievements, unsupported assumptions or judgements that are not supported by the information provided.
```

### Version 1.2 - Final Performance Review Summary Prompt
[Prompt 10 - Performance Review Summary] (https://github.com/sleotalu/HR-Prompt-Library/blob/96378758f1f19628cf069d17499d25eab65223a6/Workflow-3-Employee-Performance-Management/Prompt-10-Performance-Review-Summary.md)

## 5. Summary of Improvements

### V1.0 to V1.1
- Added instructions to consolidate previous performance feedback and development goals
- Included employee achievements to provide a more complete overview of performance
- Introduced progress against development goals to assess employee development
- Added remaining development needs to identify areas of requiring further attention
- Improved the relevance of the review by combining performance information from different sources

### V1.1 to V1.2
- Added the employee development plan to connect performance reviews with previous development activities
- Expanded the review to include progress and achievements
- Added outstanding development areas to identify goals that still require attention
- Introduced future development actions to support continued employee growth
- Added suggested next review arrangements to support ongoing performance monitoring
- Included a table where appropriate to organise review information clearly
- Added instructions to identify missing information and require manager and HR review before discussing summary with the employee
- Strengthened safeguards against invented achievements, unsupported judgements and final employment, promotion or disciplinary decisions

## 6. Final Outcome
Version 1.2 was selected as the final prompt because it provides a more complete and structured approach to employee performance reviews. It consolidates previous performance feedback, the employee development plan, progress and achievements to summarise the employee's performance during the review period. The final version also identifies outstanding development areas and recommends future development actions and review arrangements. This helps managers and HR understand employee progress and plan appropriate follow-up.

The prompt includes safeguards requiring the use of provided information, identification of missing details and manager and HR review before the summary is discussed with the employee. This supports fair, balanced and professional performance review summaries.

## 7. Related Workflow Prompts
Prompt 10 is the final prompt in Workflow 3 - Employee Performance Management. It builds on the previous performance feedback and employee development planning stages to provide an overall summary of employee progress and performance. 

[Prompt 08 - Performance Feedback] (https://github.com/sleotalu/HR-Prompt-Library/blob/96378758f1f19628cf069d17499d25eab65223a6/Workflow-3-Employee-Performance-Management/Prompt-08-Performance-Feedback.md)

[Prompt 09 - Employee Development Plan] (https://github.com/sleotalu/HR-Prompt-Library/blob/96378758f1f19628cf069d17499d25eab65223a6/Workflow-3-Employee-Performance-Management/Prompt-09-Employee-Development-Plan.md)

[Prompt 10 - Performance Review Summary] (https://github.com/sleotalu/HR-Prompt-Library/blob/96378758f1f19628cf069d17499d25eab65223a6/Workflow-3-Employee-Performance-Management/Prompt-10-Performance-Review-Summary.md)
