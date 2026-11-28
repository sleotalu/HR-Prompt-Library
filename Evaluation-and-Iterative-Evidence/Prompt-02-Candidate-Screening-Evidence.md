# Prompt 02: Candidate Screening Support 

## 1. Overview
This document records the iterative development of Prompt 02: Candidate Screening. Three versions were developed to improve the fairness, accuracy, consistency and reliability of candidate screening. 

## 2. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial candidate screening prompt created. | Establish the basic screening structure. |
| V1.1 | Added instructions to use job-related criteria and avoid assumptions. | Improve fairness and accuracy. |
| V1.2 | Added structured screening reports and human review requirements. | Improve output consistency and reduce recruitment risks. |

## 3. Version Comparison Screenshot
The screenshot below demonstrates the development of Prompt 02, highlighting the improvements made to candidate screening fairness, accuracy and consistency.


## 4. Prompt Versions

### V1.0 - Initial Candidate Screening Prompt
``` text
You are an HR recruitment assistant responsible for supporting candidate screening.

Review the candidate's resume against the provided job description for the position of [JOB_TITLE] at [COMPANY_NAME].

Use the following information: 
- Candidate resume: [CANDIDATE_RESUME]
- Job description: [JOB_DESCRIPTION]
- Candidate reference: [CANDIDATE_REFERENCE]

Identify the candidate's relevant qualifications, skills and work experience.

Provide a brief summary of how the candidate's background relates to the job requirements.

Requirements:
- Review the resume against the job description
- Identify relevant qualifications, skills and experience
- Use clear and professional language
- Highlight relevant information for HR review

Output: A candidate screening summary to support the recruitment process.
```

### V1.1 - Fair and Criteria-Based Candidate Screening Prompt
``` text
You are an experienced HR recruitment assistant responsible for supporting fair and consistent candidate screening.

Review the candidate's resume against the provided job description.

Use the following information:
- Candidate resume: [CANDIDATE_RESUME]
- Job description: [JOB_DESCRIPTION]
- Essential requirements: [ESSENTIAL_REQUIREMENTS]
- Desirable criteria: [DESIRABLE_CRITERIA]
- Candidate reference: [CANDIDATE_REFERENCE]

Compare the candidate's qualifications, skills and experience against essential and desirable job requirements.

Requirements:
- Assess candidates using job-related criteria only
- Base finding on evidence provided in the resume and job description
- Do not make assumptions about missing qualifications, skills or experience
- Identify requirements that are met, missing or unclear
- Avoid assessing candidates based on personal characteristics unrelated to the job
- Use clear, objective and professional language

Output: A structured candidate screening summary that supports fair and accurate HR assessment.
```

### V1.2 - Final Candidate Screening Prompt
[View Final Prompt 02 - Candidate Screening Support] (https://github.com/sleotalu/HR-Prompt-Library/blob/d5f2850eccb022dcdfb2cb4e2f30abdc6d0e0f84/Workflow-1-Recruitment/Prompt-02-Candidate-Screening.md)

## 5. Summary of Improvements

### V1.0 to V1.1
- Introduced job-related screening criteria
- Added essential and desirable requirements
- Included instructions to avoid assumptions about candidate qualifications and experience
- Improved fairness and accuracy in candidate screening

### V1.1 to V1.2
- Introduced a structured candidate screening report
- Added clear categories for requirements met, missing or unclear
- Included suggested questions for further assessment
- Added safeguards against assessning protected personal characteristics
- Established human review requirements for all final recruitment decisions
- Connected candidate screening to the job description and criteria established in Prompt 01

## 6. Final Outcome
V1.2 was selected as the final prompt because it provides a more structured and consistent approach to candidate screening while supporting fairness, accuracy and transparency. The final version helps HR staff compare candidate qualifications, skills and experience against established job requirements. It also ensures that AI-generated screening findings support, rather than replace, human judgement and final recruitment decisions. 

## 7. Related Workflow Prompt
The final candidate screening process uses the job description and selection criteria established in Prompt 01.

[View Prompt 01 - Job Description] (https://github.com/sleotalu/HR-Prompt-Library/blob/cee0b1efd68134474ea8db9134c18168b6954f52/Workflow-1-Recruitment/Prompt-01-Job-Description.md)

[View Final Prompt 02 - Candidate Screening Support] (https://github.com/sleotalu/HR-Prompt-Library/blob/cee0b1efd68134474ea8db9134c18168b6954f52/Workflow-1-Recruitment/Prompt-02-Candidate-Screening.md)
