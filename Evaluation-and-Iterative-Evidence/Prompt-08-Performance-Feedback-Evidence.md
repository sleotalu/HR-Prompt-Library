# Prompt 08: Performance Feedback

## 1. Overview
This document records the iterative development of Prompt 08: Performance Feedback. Three versions were developed to improve the structure, relevance and consistency of employee performance feedback. The improvements focus on identifying employee strengths, achievements and areas requiring improvement while providing constructive recommendations and supporting fair, balanced and evidence-based performance reviews.

## 2. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial performance feedback prompt created. | Establish the basic performance feedback structure. |
| V1.1 | Added instructions to identify employee strengths, achievements and improvement areas using supplied performance information. | Improve feedback relevance and consistency. |
| V1.2 | Added safeguards against bias, unsupported judgements and privacy risks. | Improve reliability and ensure appropriate HR oversight. |

## Version Comparison Screenshot
The screenshots below demonstrate the development of Prompt 08, highlighting the improvements made to performance feedback structure, identification of employee strengths and improvement areas, and practical development recommendations. As it only allows comparison of two checkpoints at a time, the following screenshots compare V1.0 and V1.2 involving their prompt inputs and outputs.

V1.0 prompt output: (https://github.com/sleotalu/HR-Prompt-Library/blob/b37c35ec75b20d63dab017001dbbe81ff1581a56/Evaluation-and-Iterative-Evidence/Prompt-08-Comparison-Version-V1.0.png)

V1.2 prompt output: (https://github.com/sleotalu/HR-Prompt-Library/blob/b37c35ec75b20d63dab017001dbbe81ff1581a56/Evaluation-and-Iterative-Evidence/Prompt-08-Comparsion-Version-V1.2.png)

V1.0 and V1.2 prompt input: (https://github.com/sleotalu/HR-Prompt-Library/blob/b37c35ec75b20d63dab017001dbbe81ff1581a56/Evaluation-and-Iterative-Evidence/Prompt-08-Comparison-Version3.png)

## 4. Prompt Versions

### V1.0 - Initial Performance Feedback Prompt
``` text
You are an HR assistant responsible for helping managers prepare professional employee performance feedback.

Review the employee's performance information and prepare a summary of their performance during the review period.

Use the following information:
- Company name: [COMPANY_NAME]
- Employee name: [EMPLOYEE_NAME]
- Job title: [JOB_TITLE]
- Review period: [REVIEW_PERIOD]
- Manager observations: [MANAGER_OBSERVATIONS]

Include the following sections:
1. Employee role and review period
2. General performance summary
3. Key observations
4. Suggested areas for improvement
5. Recommended next steps for the manager

Requirements:
- Use the information provided by the manager.
- Keep the feedback clear and professional.
- Ensure the summary is relevant to the employee's role.
- Do not invent performance information or achievements.

Tone: Professional and constructive

Output: A structured employee performance feedback summary suitable for manager review.
```

### V1.1 - Structured Performance Feedback Prompt
``` text
You are an experienced HR performance management assistant responsible for helping managers prepare fair and constructive employee feedback.

Review the employee's performance information and manager observations. Identify the employee's strengths, achievements and areas requiring improvement.

Use the following information:
- Company name: [COMPANY_NAME]
- Employee name: [EMPLOYEE_NAME]
- Job title: [JOB_TITLE]
- Department: [DEPARTMENT]
- Review period: [REVIEW_PERIOD]
- Job responsibilities: [JOB_RESPONSIBILITIES]
- Performance goals: [PERFORMANCE_GOALS]
- Achievements: [ACHIEVEMENTS]
- Manager observations: [MANAGER_OBSERVATIONS]
- Improvement areas: [IMPROVEMENT_AREAS]

Include the following sections:
1. Employee role and review period summary
2. Key strengths and achievements
3. Areas of good performance
4. Areas requiring improvement
5. Constructive performance feedback
6. Suggested improvement recommendations
7. Overall performance summary

Requirements:
- Use the supplied performance information and manager observations
- Identify strengths and achievements relevant to the employee's role and performance goals
- Clearly identify areas requiring improvement
- Provide constructive and practical feedback
- Do not make assumptions or invent achievements
- Keep the feedback fair, balanced and professional

Tone: Fair, supportive and professional

Output: A structured performance feedback report to support consistent employee performance reviews.
```

### V1.2 - Final Performance Feedback Prompt
[View Final Prompt 08 - Performance Feedback] (https://github.com/sleotalu/HR-Prompt-Library/blob/108ee8041af37ebc034504159db5260de1f35d56/Workflow-3-Employee-Performance-Management/Prompt-08-Performance-Feedback.md)

## 5. Summary of Improvements

### V1.0 to V1.1
- Introduced employee strengths and achievements as key parts of the performance review
- Added job responsibilities and performance goals to provide more relevant assessment information
- Introduced seperate sections for areas of good performance and areas requiring improvement
- Added constructive feedback and suggested improvement recommendations
- Introduced instructions to use supplied performance information and avoid unsupported assumtopns
- Improved the structure and consistency of employee performance feedback reports

### V1.1 to V1.2
- Added company, employee, department and manager information
- Introduced supporting information to provide additional evidence for the review
- Expanded the report to include practical improvement recommendations and training and development opportunities
- Added an overall performance summary and recommended next steps for managers and HR
- Introduced safeguards against unsupported judgements, assumptions and invented achievements
- Added restrictions against making final employment, promotion or disciplinary decisions
- Introduced instructions to identify missing evidence
- Required managers and HR to review the feedback before communicating it to employees
- Improved the fairness, accuracy and usefulness of performance feedback

## 6. Final Outcome
V1.2 was chosen as the final prompt because it provides a more complete and structured approach to preparing employee performance feedback. The final version uses employee performance information, job responsibilities, performance goals and manager observations to identify strengths, achievements and areas requiring improvement. It also provides practice recommendations and suggested training and development opportunities to support employee growth.

The final prompt reduces the risk of unfair or unsupported feedback by requiring the use of supplied information, identifying missing evidence and preventing invented achievements or unsupported judgements. It also ensures managers and HR review the feedback before it is communicated to employees. 

## 7. Related Workflow Prompts
Prompt 08 is the first stage of Workflow 3 - Employee Performance Management. It established the employee's performance strengths and improvement areas, which can support the development planning and performance review stages.

[View Final Prompt 08 - Performance Feedvack] (https://github.com/sleotalu/HR-Prompt-Library/blob/108ee8041af37ebc034504159db5260de1f35d56/Workflow-3-Employee-Performance-Management/Prompt-08-Performance-Feedback.md)

[View Prompt 09 - Employee Development Plan] (https://github.com/sleotalu/HR-Prompt-Library/blob/108ee8041af37ebc034504159db5260de1f35d56/Workflow-3-Employee-Performance-Management/Prompt-09-Employee-Development-Plan.md)

[View Prompt 10 - Performance Review Summary] (https://github.com/sleotalu/HR-Prompt-Library/blob/108ee8041af37ebc034504159db5260de1f35d56/Workflow-3-Employee-Performance-Management/Prompt-10-Performance-Review-Summary.md)
