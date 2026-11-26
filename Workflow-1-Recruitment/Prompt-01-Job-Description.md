# Prompt 01: Job Description Generator

## 1. Workflow
Recruitment and Candidate Management

## 2. Purpose
Automate the initial drafting of job descriptions to reduce HR administrative workload and improve consistency in recruitment.

## 3. Prompt
``` text
You are an HR recruitment assistant responsible for creating clear, professional and inclusive job descriptions.

Create a job description for the position of [JOB_TITLE] at [COMPANY_NAME].

Use the following information provided by HR:
- Job title: [JOB_TITLE]
- Company name: [COMPANY_NAME]
- Position overview: [POSITION_OVERVIEW]
- Key responsibilities: [KEY_RESPONSIBILITIES]
- Essential skills and qualifications: [ESSENTIAL_REQUIREMENTS]
- Desirable skills: [DESIRABLE_SKILLS]
- Reporting line: [REPORTING_LINE]
- Application instructions: [APPLICATION_INSTRUCTIONS]

Include the following sections:
1. Job title
2. Position overview (2-3 sentenced)
3. Key responsibilities (bullet points)
4. Essential skills and qualifications
5. Desirable skills
6. Reporting line (if provided)
7. Application instructions

Tone: professional, clear, welcoming and inclusive.

Requirements:
- Use gender-neutral language
- Avoid unnecessary selection criteria or discriminatory wording
- Make the job advertisement attractive to qualified applicants
- Ensure all responsibilities and requirements reflect the information provided

Do not invent company details, salary information, qualifications, responsibilities or job requirements. If information is missing, clearly identify it as [HR TO COMPLETE] rather than making assumptions.

Output: A structured, ready-to-review job description suitable for a recruitment advertisement.
```

**Placeholders to fill:**
| **Placeholder** | **Source** | **Example** |
|---|---|---|
| `[JOB_TITLE]` | HRIS position record / Job requisition | Retail Store Assistant |
| `[COMPANY_NAME]` | Company HR records | ABC Retail |
| `[POSITION_OVERVIEW]` | HR / Hiring Manager | Assist customers and support daily retail operations |
| `[KEY_RESPONSIBILITIES]` | Approved job description / Hiring Manager | Customer service, processing sales and restocking shelves |
| `[ESSENTIAL_REQUIREMENTS]` | Approved job requirements / Hiring Manager | Communication skills and customer service experience |
| `[DESIRABLE_SKILLS]` | Hiring Manager / Position requirements | Previous retail experience and POS system knowledge |
| `[REPORTING_LINE]` | HRIS organisational structure | Store Manager |
| `[APPLICATION_INSTRUCTIONS]` | Recruitment team / Careers portal | Submit resume and cover letter through the online careers portal |

## 4. Intended Task
Generate an initial draft of a job advertisement

## 5. Problem Being Solved
Writing job descriptions manually can be time-consuming and lead to inconsistent structure, wording and recruitment requirements.

## 6. Automation Potential
High. AI can generate a standardised first draft quickly, allowing HR staff to focus on reviewing requirements and selecting appropriate candidates.

## 7. Risks and Limitations
AI may generate unrealistic qualifications, biased language or incorrect job responsibilities. The output must be checked by HR before publication.

## 8. Testing and Evaluation
Test the prompt using different job positions. Evaluate accuracy, relevance, completeness, inclusive language and consistency. 

## 9. Version History
- v1.0 - Initial prompt created.
