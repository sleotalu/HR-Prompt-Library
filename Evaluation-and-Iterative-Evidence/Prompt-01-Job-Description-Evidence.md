# Prompt 01: Job Description Generator

## 1. Overview
This document records the iterative development of Prompt 01: Job Description Generator. Three versions were developed to improve the prompt's structure, consistency, accuracy and inclusiveness.

## 2. Version History
| **Version** | **Changes Made** | **Reason** |
| ----------- | ---------------- | ---------- |
| V1.0 | Initial job description generation prompt created with basic instructions to generate job descriptions using HR-provided information. | Establish a basic structure for automating job description drafting. |
| V1.1 | Added structured job description sections, including position overview, key responsibilities, essential qualifications and desirable skills. | Improve the organisation, completeness and consistency of generated job descriptions. |
| V1.2 | Added gender-neutral language requirements, instructions to avoid discriminatory wording, and safeguards against inventing missing company or job information. | Improve inclusiveness, accuracy and reliability of generated job descriptions. |

## 3. Version Comparison Screenshot
The screenshot below demonstrates the development of Prompt 01 between V1.0 and V1.2 (current), highlighting the improvements made.

[View Prompt 01 Version Comparison Screenshot] (https://github.com/sleotalu/HR-Prompt-Library/blob/0e1cc93f14370a37b1179b39274bbae56d828eba/Evaluation-and-Iterative-Evidence/Prompt-01-Version-Comparison.png) 

## 4. Prompt Versions

### V1.0 - Initial Job Description Generator
``` text
You are an HR recruitment assistant responsible for creating professional job descriptions.

Create a job description for the position of [JOB_TITLE] at [COMPANY_NAME].

Use the information provided by HR to describe the position, its main responsibilities and the skills required.

Ensure the job description is clear, professional and suitable for a recruitment advertisement.

Requirements:
- Use the information provided by HR
- Keep the language professional and easy to understand
- Make the job description relevant to the position
- Avoid adding information that has not been provided

Output: A professional job description suitable for HR review
```

### V1.1 - Structured Job Description Generator
``` text
You are an HR recruitment assistant responsible for creating clear and professional job descriptions.

Create a job description for the position of [JOB_TITLE] at [COMPANY_NAME].

Use the following information provided by HR:
- Job title: [JOB_TITLE]
- Company name: [COMPANY_NAME]
- Position overview: [POSITION_OVERVIEW]
- Key responsibilities: [KEY RESPONSIBILITIES]
- Essential skills and qualifications: [ESSENTIAL_REQUIREMENTS]
- Desirable skills: [DESIRABLE_SKILLS]

Include the following sections:
1. Job title
2. Position overview
3. Key responsibilities (bullet points)
4. Essential skills and qualifications
5. Desirable skills

Requirements:
- Use the information provided by HR
- Organise the information into the required sections
- Use clear and professional language
- Ensure responsibilities and qualifications are relevant to the position
- Do not invent company details, responsibilities or job requirements

Output: A structured job description suitable for a recruitment advertisement and HR review.
```

### V1.2 - Refined Job Description Generator
[View Final Prompt 01 - Job Description Generator] (https://github.com/sleotalu/HR-Prompt-Library/blob/1b697dc9e1a1c6fe557981bebb71657aa744acf2/Workflow-1-Recruitment/Prompt-01-Job-Description.md)

## 5. Summary of Improvements

### V1.0 to V1.1
- Introduced specific HR information fields
- Added structured job description sections
- Improved organisation and consistency

### V1.1 to V1.2
- Added reporting line and application instructions
- Introduced gender-neutral and inclusive language requirements
- Added [HR_TO_COMPLETE] placeholders for missing information
- Strengthened instructions to prevent invented responsibilities, qualifications and company details

## 6. Final Outcome
V1.2 was selected as the final prompt because it provides clearer instructions, a more complete job description structure and stronger safeguards for accuracy and inclusivity. It is suitable for producing consistent, ready-to-review recruitment advertisements.
