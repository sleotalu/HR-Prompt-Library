# HR Prompt Library: Workflow Automation

> **Assessment 1 | Generative AI for Business**\
> Student: Suli Sina Sandra Leota Lu\
> Business Field: Human Resources (HR) Operations\
> Model tested on: ChatGPT\
> Last updated: 27 November 2026

## What This Library Does
This prompt library supports workflow automation in **Human Resources (HR) operations**. It contains 10 documented prompts organised into three business workflows: Recruitment, Employee Complaints, and Employee Performance Management.

Each prompt entry follows a consistent structure:
- The exact prompt text, including placeholders to fill
- The workflow task it supports
- The problem it aims to solve
- Its automation potential
- Known risks and recommended mitigations
- Version history and testing evidence, where available

The library is designed to improve consistency, reduce repetitive HR administration and support decision-making while maintaining appropriate human oversight. 

## Folder Structure
``` text
HR-Prompt-Library/
│
├── README.md
│
├── Workflow-1-Recruitment/
│   ├── README.md
│   ├── Prompt-01-Job-Description-Generator.md
│   ├── Prompt-02-Candidate-Screening.md
│   ├── Prompt-03-Interview-Preparation.md
│   └── Prompt-04-Candidate-Communication.md
│
├── Workflow-2-Employee-Complaints/
│   ├── README.md
│   ├── Prompt-05-Employee-Complaint-Categorisation.md
│   ├── Prompt-06-HR-Policy-Review.md
│   └── Prompt-07-Employee-Complaint-Response.md
│
└── Workflow-3-Employee-Performance-Management/
    ├── README.md
    ├── Prompt-08-Performance-Feedback.md
    ├── Prompt-09-Employee-Development-Plan.md
    └── Prompt-10-Performance-Review-Summary.md
```

## Library Summary Table
| **ID** | **Prompt Name** | **Workflow** | **Automation Level** | **Risk Level** | **Status** |
|---|---|---|---|---|---|
| P01 | Job Description Generator | Recruitment and Selection | High | Medium | 📝 Documented |
| P02 | Candidate Screening | Recruitment and Selection | Medium | High | 📝 Documented |
| P03 | Interview Preparation | Recruitment and Selection | High | Medium | 📝 Documented |
| P04 | Candidate Communication | Recruitment and Selection | High | Medium | 📝 Documented |
| P05 | Employee Complaint Categorisation | Employee Complaints | Medium | High | 📝 Documented |
| P06 | HR Policy Review | Employee Complaints | Medium | High | 📝 Documented |
| P07 | Employee Complaint Response | Employee Complaints | High | High | 📝 Documented |
| P08 | Performance Feedback | Employee Performance Management | Medium | High | 📝 Documented |
| P09 | Employee Development Plan | Employee Performance Management | High | Medium | 📝 Documented |
| P10 | Performance Review Summary | Employee Performance Management | High | Medium | 📝 Documented |

**Automation Levels:**
- **Very High:** Most preparation tasks can be automated with limited editing
- **High:** AI can generate structured drafts with human review
- **Medium:** AI assists with analysis and recommendations but require careful human assessment
- **Low:** AI provides limited assistance and most work requires human input

**Risk Levels:**
- **High:** Requires careful human review due to potential impacts on employees, privacy or organisations decisions
- **Medium:** Requires review to ensure accuracy, fairness and suitability
- **Low:** Can be automated with routine checks and monitoring

*Note: Automation and risk levels are indicative assessments of each prompt's intended use, not measured performance results. Human review remains necessary for HR decisions.*

## Prompt Chaining Map
The prompts in this library are organised into three connected workflows. Outputs from earlier prompts provide information for the next stafe.
``` text
WORKFLOW 1 — RECRUITMENT AND SELECTION

Recruitment Requirement
        ↓
P01 (Job Description Generator)
        ↓
P02 (Candidate Screening)
        ↓
P03 (Interview Preparation)
        ↓
P04 (Candidate Communication)


WORKFLOW 2 — EMPLOYEE COMPLAINTS

Employee Submits Complaint
        ↓
P05 (Employee Complaint Categorisation)
        ↓
P06 (HR Policy Review)
        ↓
P07 (Employee Complaint Response)


WORKFLOW 3 — EMPLOYEE PERFORMANCE MANAGEMENT

Employee Performance Review
        ↓
P08 (Performance Feedback)
        ↓
P09 (Employee Development Plan)
        ↓
P10 (Performance Review Summary)
```

## Prompting Strategies Used
| **Strategy** | **Prompts** | **Why Chosen** |
|---|---|---|
| RACE framework (Role–Action–Context–Expected Output) | P01–P10 | Provides a consistent structure and clear instructions for each HR task. |
| Input placeholders | P01–P10 | Allows HR staff to reuse prompts by entering different employee and organisational information. |
| Grounding constraints (use only information provided) | P02, P05, P06, P08, P10 | Reduces unsupported assumptions and inaccurate conclusions. |
| Structured output and numbered sections | P01–P10 | Makes AI-generated results easier to review, compare and use in HR workflows. |
| Table-based output | P02, P03, P09, P10 | Organises candidate information, interview preparation and employee development activities. |
| Human review and approval requirements | P01–P10 | Helps manage risks involving recruitment, employee complaints and performance decisions. |

## Iteration Evidence
The prompts are organised into individual Markdown files so that changes can be documented and tracked throughout development.

GitHub commit history can be used as a version log, showing changes made to prompt instructions, input placeholders, output requirements and risk controls. 

| **Prompt Group** | **Prompts** | **Areas for Improvement and Testing** |
|---|---|---|
| Recruitment and Selection | P01–P04 | Refine job description requirements, candidate screening criteria, interview questions and candidate communication. |
| Employee Complaints | P05–P07 | Improve complaint categorisation, policy alignment, confidentiality and response recommendations. |
| Employee Performance Management | P08–P10 | Improve performance feedback, development goals, progress monitoring and review summaries. |

**Version Control:** Use GitHub commits to record prompt changes and explain why each improvement was made. 

**Testing Evidence:** Record test inputs, generated outputs, identified issues and improvements in the relevant prompt files. Do not report performance improvements or time savings unless they have been measured.

## Risks and Responsible AI Considerations
The library uses generative AI to assist with HR administration, but AI-generated content must not replace professional HR judgement. 

Key risks and recommended controls include:
- **Bias:** Review recruitment and performance outputs to ensure fair and consistent treatment of employees and candidates.
- **Hallucinations:** Require prompts to use supplied information and identify missing evidence rather than inventing details.
- **Privacy and confidentiality:** Avoid entering sensitive employee or candidate information into unapproved AI tools.
- **Inaccurate policy interpretation:** Require HR to verify policy references and assess whether findings are appropriate.
- **Over-reliance on AI:** Ensure managers and HR review and approve outputs before taking action or communicating with employees.

## Conclusion
This HR Prompt Library demonstrates how generative AI can support three important HR workflows through structured and reusable prompts. By connecting the prompts into workflow sequences, the library aims to improve administrative efficiency, consistency and communication while maintaining human oversight, confidentiality and responsible AI use.
