# Prompt 03: Interview Preparation

## 1. Workflow

**Workflow Name:** Recruitment and Selection

**Workflow Stage:** Interview Preparation

**Previous Prompt:** Prompt 02 - Candidate Screening Support

**Next Prompt:** Prompt 04 - Candidate Communication

**Workflow Description:**
This prompt supports the interview preparation stage of the recruitment process. After HR has reviewed candidate applications and identified applicants who meet the job requirements, this prompt helps prepare structured interview questions based on the advertised position and required skills.

## 2. Purpose
The purpose of this prompt is to help HR staff prepare relevant, structured and consistent interview questions for shortlisted candidates.
It aims to reduce the time spent manually developing interview questions while ensuring that questions are relevant to the position and aligned with the organisation's recruitment requirements.

## 3. Prompt
```text
You are an experienced HR recruitment assistant responsible for supporting fair, professional and structured interview preparation. Develop a structured interview guide for the position of [JOB_TITLE] at [COMPANY_NAME]

Use the following instructions provided by HR:
- Job description: [JOB_DESCRIPTION]
- Essential requirements: [ESSENTIAL_REQUIREMENTS]
- Desirable criteria: [DESIRABLE_CRITERIA]
- Candidate resume: [CANDIDATE_RESUME]
- Candidate screening report: [CANDIDATE_SCREENING_REPORT]
- Candidate strengths: [CANDIDATE_STRENGTHS]
- Areas requiring clarification: [AREAS_FOR_CLARIFICATION]
- Candidate reference: [CANDIDATE REFERENCE]

The job description must be based on the completed output of Prompt 01 - Job Description Generator. The candidate screening report and candidate information must be based on the completed output of Prompt 02 - Candidate Screening Support. Use the job requirements and candidate screening results to develop relevant interview questions.

Include the following sections:
1. Position Overview: Briefly identify the job title and key responsibilities
2. Technical Questions: Develop questions relating to the skills and knowledge required for the position
3. Behavioural Questions: create questions exploring the candidate's previous workplace experiences and actions
4. Situational Questions: Develop realistic workplace scenarios to assess the candidate's problem-solving and decision-making abilities
5. Follow-up Questions: Include additional questions to clarify or explore the candidate's responses
6. Evaluation Criteria: Provide suggested job-related criteria HR can use to assess candidate answers
7. Interview Structure: Recommend a logical order for asking the interview questions

Requirements:
- Use the job description and candidate screening report as the main sources of information
- Address relevant strengths and areas requiring further clarification identified during screening
- Ensure questions are professional, inclusive and appropriate for a workplace interview
- Do not create questions based on protected personal characteristics or unrelated personal information
- Do not assume qualifications, experience or skills that have not been provided
- Ensure all shortlisted candidates are assessed against consistent job-related criteria
- Do not make the final hiring decision

Tone: professional, objective, inclusive and unbiased.

Output: A structured interview guide that HR can use to prepare and conduct a consistent and fair interview.

The HR recruitment team is responsible for conducting interviews, evaluation candidate responses and making all final hiring decisions.
```

**Placeholders to fill:**
| **Placeholder** | **Source** | **Example** |
|---|---|---|
| `[JOB_DESCRIPTION]` | Prompt 01 – Job Description Generator output | Retail Store Assistant job description |
| `[ESSENTIAL_REQUIREMENTS]` | Prompt 01 – Essential skills and qualifications section | Communication skills and customer service experience |
| `[DESIRABLE_CRITERIA]` | Prompt 01 – Desirable skills section | Previous retail experience and POS system knowledge |
| `[CANDIDATE_RESUME]` | Candidate application / Submitted resume | Resume containing employment history, qualifications and skills |
| `[CANDIDATE_SCREENING_REPORT]` | Prompt 02 – Candidate Screening Support output | Screening report identifying relevant experience and skills |
| `[CANDIDATE_STRENGTHS]` | Prompt 02 – Relevant skills and work experience section | Customer service experience and teamwork |
| `[AREAS_FOR_CLARIFICATION]` | Prompt 02 – Requirements that are missing or unclear | Limited information about previous cash-handling experience |
| `[CANDIDATE_REFERENCE]` | Recruitment application tracking system | Applicant 001 |

## 4. Intended Task
The intended task is to assist HR staff in preparing interview questions and evaluation criteria for shortlisted candidates. The prompt helps organise interview questions into technical, behavioural and situational categories so that HR staff can conduct more structured and consistent interviews.

## 5. Problem Being Solved
Preparing interview questions manually can be time-consuming, especially when recruitment teams are managing multiple vacancies.
Interview questions may also vary between candidates, making it difficult to compare applicants fairly and consistently.
This prompt addresses these challenges by generating structured interview questions based on the job requirements and providing consistent evaluation criteria for HR staff. 

## 6. Automation Potential 
This prompt has the potential to automate parts of the interview preparation process. 

**Potential Automation Activities:** 
- Generate interview questions based on job descriptions
- Organise questions into technical, behavioural and situational categories
- Develop follow-up questions for further assessment
- Generate suggested evaluation criteria
- Create structured interview guides for HR staff

**Human Involvement:**
HR staff must review and approve the generated questions before interviews take place. Interviewers must conduct the interviews, assess candidate responses and make recruitment recommendations. AI should support interview preparation rather than independently assess or select candidates.

## 7. Risks and Limitations
**Potential Risks:**
- **Bias:** AI may generate questions that unintentionally disadvantage certain candidates
- **Irrelevant Questions:** Generated questions may not accurately reflect the job requirements
- **Inconsistent Assessment:** Interviewers may interpret evaluation criteria differently
- **Privacy:** Candidate information must be handled securely.
- **Over-reliance:** HR staff may depend too heavily on AI-generated interview questions.

**Limitations:**
- AI can only generate questions based on the information provided
- Questions may require adjustment for different experience levels
- AI cannot evaluate a candidate's actual communication or workplace abilities
- Generated evaluation criteria may not cover every requirement of the position

**Risk Mitigation:**
HR staff should review all generated questions, use consistent job-related selection criteria, protect candidate information and ensure that all candidates receive fair and appropriate interview assessments.

## 8. Testing and Evaluation
The prompt will be tested using a sample job description and candidate screening information to assess the relevance and quality of the generated interview questions.
**Testing Method:**
1. Provide the AI with a sample job description
2. Provide the relevant selection criteria and candidate informaiton
3. Run the interview preparation prompt
4. Review the generated interview questions and evaluation criteria
5. Check whether the questions relate to the actual job requirements
6. Assess whether the questions are clear, fair and appropriate
7. Refine the prompt if necessary and test it again

**Evaluation Criteria:**
The following criteria will be used to evaluate the prompt's performance:
| Evaluation Area | What to Check |
|---|---|
| Relevance | Are the questions related to the job requirements? |
| Accuracy | Do the questions reflect the required skills and responsibilities? |
| Fairness | Are the questions appropriate and free from discriminatory content? |
| Consistency | Can the questions and criteria be used consistently across candidates? |
| Output Quality | Is the interview guide clear, organised and professional? |

**Success Measures:**
The prompt will be considered effective if it generates relevant, clear and fair interview questions, reduces manual preparation time and supports consistent interview practices.

## 9. Version History
| Version | Changes Made | Reason |
|---|---|---|
| V1.0 | Initial interview preparation prompt created. | Establish the basic interview question generation structure. |
| V1.1 | Added technical, behavioural and situational question categories. | Improve question variety and relevance. |
| V1.2 | Added fairness instructions and structured evaluation criteria. | Support consistent and unbiased interview preparation. |

**Current Version:** V1.2

**Status:** TESTED. 
