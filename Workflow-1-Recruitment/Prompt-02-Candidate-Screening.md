# Prompt 02: Candidate Screening Support

## 1. Workflow

**Workflow Name:** Recruitment and Selection

**Workflow Stage:** Candidate Screening

**Previous Prompt:** Prompt 01 - Job Description Generator

**Next Prompt:** Prompt 03 - Interview Preparation

**Workflow Description:** 
This prompt is used after a job description has been created and applications have been received. It helps HR review candidate resumes against the advertised job requirements.

## 2. Purpose
The purpose of this prompt is to assist HR staff in reviewing candidate applications by identifying relevant qualifications, skills and work experience. It aims to make the initial screening process more efficient, structured and consistent.

## 3. Prompt
```text
You are an experienced HR recruitment assistant responsible for supporting fair and consistent candidate screening.

Review the candidate's resume against the provided job description.

Candidate information:
- Candidate resume: [CANDIDATE_RESUME]
- Job description: [JOB_DESCRIPTION]
- Essential requirements: [ESSENTIAL_REQUIREMENTS]
- Desirable criteria: [DESIRABLE_CRITERIA]
- Candidate reference: [CANDIDATE_REFERENCE]

Compare the candidate's resume against the job requirements.

Include the following sections in your screening report:
1. Candidate's relevant qualifications
2. Relevant skills and work experience
3. Essential job requirements met
4. Requirements that are missing or unclear
5. Desirable criteria demonstrated
6. Overall alignment with the job requirements
7. Suggested questions for further assessment

Tone: clear, objective, professional and impartial.

Requirements:
- Use only the information provided in the candidate's resume and job description
- Do not make assumptions about missing qualifications, skills or experience
- Do not assess candidates based on protected personal characteristics
- Clearly distinguish between requirements that are met, not demonstrated or unclear
- Base all finding on evidence from the supplied information
- Do not make the final recruitment decision
- Use the job description generated in Prompt 01 - Job Description Generator as the basis for candidate screening
- Use the essential and desirable criteria established in Prompt 01 when assessing the candidate's resume

Output: A structured candidate screening report that supports fair and consistent HR recruitment assessment.

The HR recruitment team must review the findings and make all final recruitment decisions.
```

**Placeholders to fill:**
| **Placeholder** | **Source** | **Example** |
|---|---|---|
| `[CANDIDATE_RESUME]` | Candidate application / Submitted resume | Resume containing previous employment, qualifications and skills |
| `[JOB_DESCRIPTION]` | Approved job advertisement / HR recruitment records | Retail Store Assistant job description |
| `[ESSENTIAL_REQUIREMENTS]` | Approved job description / Hiring Manager | Communication skills and customer service experience |
| `[DESIRABLE_CRITERIA]` | Approved job description / Hiring Manager | Previous retail experience and POS system knowledge |
| `[CANDIDATE_REFERENCE]` | Recruitment application tracking system | Applicant 001 |

## 4. Intended Task
The intended task is to support the initial candidate screening stage of the recruitment process. 
HR staff can use this prompt to compare candidate resumes against the job description and organise relevant information before progressing suitable applicants to the interview stage.

## 5. Problem Being Solved
Manually reviewing multiple candidate resumes can be time-consuming and may lead to inconsistent assessments. 
HR staff may also find it difficult to compare different applicants against the same selection criteria. 
This prompt addresses these challenges by organising candidate information into a consistent screening report, helping HR staff review applications more efficiently

## 6. Automation Potential
This prompt has the potential to automate parts of the initial resume screening process.

**Potential Automation Activities:**
- Extract relevant qualifications and skills from resumes
- Compare candidate information against job requirements
- Organise candidate details into structured reports
- Identify missing or unclear information
- Generate suggested interview questions

**Human Involvement:**
HR staff must verify the information, assess candidate suitability and make final recruitment decisions. AI should support the process rather than independently reject or select applicants.

## 7. Risks and Limitations
**Potential Risks:**
- **Bias:** AI may produce unfair assessments if it reflections biased information or selection criteria.
- **Inaccurate Information:** AI may misinterpret qualifications, employment history or skills.
- **Privacy:** Candidate resumes contain personal information that must be handled securely.
- **Over-reliance:** HR staff may depend too heavily on AI-generated screening results.

**Limitations:**
- AI can only assess the information provided
- Missing resume information may result in incomplete assessments
- AI cannot reliably determine a candidate's actual workplace performance
- Human judgement is required to evaluate the full suitability of applicants

**Risk Mitigation:**
Use consistent, job-related selection criteria, protect candidate information, verify Ai-generated findings and require human review before recruitment decisions.

## 8. Testing and Evaluation
The prompt will be tested using sample candidate resumes and a sample job description.
**Testing Method:**
1. Provide the AI with a job description
2. Upload a sample candidate resume
3. Run the candidate screening prompt
4. Review the generated screening report
5. Compare the output against the actual resume and job requirements
6. Identify errors, missing information or potential bias
7. Refine the prompt where necessary and test again

**Evaluation Criteria:**
The following criteria will be used to evaluate the prompt's performance:
| Evaluation Area | What to Check |
|---|---|
| Accuracy | Does the output correctly identify qualifications and skills? |
| Relevance | Does the assessment match the job requirements? |
| Consistency | Does it apply the same criteria to different candidates? |
| Fairness | Does it avoid irrelevant personal characteristics? |
| Output Quality | Is the screening report clear and organised? |

**Success Measures:**
The prompt should produce accurate, relevant and consistent screening reports while reducing repetitive administrative work.

## 9. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial candidate screening prompt created. | Establish the basic screening structure. |
| V1.1 | Added instructions to use job-related criteria and avoid assumptions. | Improve fairness and accuracy. |
| V1.2 | Added structured screening reports and human review requirements. | Improve output consistency and reduce recruitment risks. |

**Current Version:** V1.2

**Status:** TESTED.
