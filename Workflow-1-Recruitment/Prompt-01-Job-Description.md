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
**Potential Risks:**
- **Bias**: AI may generate biased or discriminatory wording that discourages certain groups from applying.
- **Inaccurate Information:** AI may include incorrect qualifications, responsibilities or employment requirements.
- **Inconsistent Requirements:** AI may misinterpret information provided by HR, resulting in job descriptions that do no accurately reflect the position.
- **Over-reliance:** HR staff may depend too heavily on AI-generated job descriptions without checking their accuracy,
- **Legal and Compliance:** Job advertisements may contain wording that does not comply with workplace discrimination and equal opportunity requirements.

**Limitations:**
- AI can only generate descriptions using the information provided by HR
- Missing information may result in incomplete job descriptions
- AI cannot independently verify whether job requirements are appropriate for the position
- Human judgement is required to ensure the job description reflects the organisation's needs and recruitment policies
- AI cannot guarantee that generated wording meets all legal and organisational requirements

**Risk Mitigation:**
HR staff must verify all job responsibilities, qualifications and selection criteria, review the language for potential bias, protect confidential organisational information and approve the final job description before publication.

## 8. Testing and Evaluation
The prompt will be tested using different job positions and sample recruitment information to assess its ability to generate accurate, relevant and inclusive job descriptions. 
**Testing Method:**
1. Provide the AI with sample job position information
2. Enter the required company details, responsibilities and qualifications
3. Run the job description generation prompt
4. Review the generated job description
5. Compare the output against the original information provided by HR
6. Identify inaccurate details, missing information or potentially discriminatory wording
7. Refine the prompt where necessary and test again

**Evaluation Criteria:** 
The following criteria will be used to evaluate the prompt's performance:
| **Evaluation Area** | **What to Check** |
| ------------------- | ------------------------------------------------------------- |
| Accuracy | Does the job description correctly reflect the information provided by HR? |
| Relevance | Are the responsibilities and qualifications appropriate for the advertised position? |
| Completeness | Does the output include all required sections? |
| Inclusiveness | Does the wording use gender-neutral and non-discriminatory language? |
| Consistency | Does the prompt produce a similar structure across different job positions? |
| Output Quality | Is the job description clear, professional and suitable for HR review? |

**Success Measures:**
The prompt should generate accurate, complete and inclusive job descriptions while reducing manual drafting time and maintaining consistency across recruitment advertisements. HR staff must review and approve all generated job descriptions before publication.

## 9. Version History
| **Version** | **Changes Made** | **Reason** |
| ----------- | ---------------- | ---------- |
| V1.0 | Initial job description generation prompt created with basic instructions to generate job descriptions using HR-provided information. | Establish a basic structure for automating job description drafting. |
| V1.1 | Added structured job description sections, including position overview, key responsibilities, essential qualifications and desirable skills. | Improve the organisation, completeness and consistency of generated job descriptions. |
| V1.2 | Added gender-neutral language requirements, instructions to avoid discriminatory wording, and safeguards against inventing missing company or job information. | Improve inclusiveness, accuracy and reliability of generated job descriptions. |

**Current Version:** v1.2

**Status:** Tested. 
