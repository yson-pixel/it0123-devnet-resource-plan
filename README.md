# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: Mark Jayson Cadano
- Section: TN36
- Repository name: `it0123-devnet-resource-plan`

## Purpose

Selecting correct DevNet resources matters becuase this ensures your workstation to match the task requirements. It also helps developers to choose appropriate resource before test cases.

## Validated Resource Decisions

Summarize your four selections from `student_plan.json`. For each use case, state the selected resource, the most important requirement, and the official Cisco evidence used.
**UC1 - always-on-sandboxes** - An immediate shared access without the administrative access is the main requirement. In cisco website it confirms that always-on-sandboxes are shared, no reservation needed, and major administrative access.
**UC2 - reservation-sandbox** - It is a private configuration testing with admnistrative access. The reservation sandboxes support changes but require setup, scheduling and VPN connectivity.
**UC3 - learning-lab** - The structured step by step instruction for beginners. Cisco descrives learning labs as resources for guided learning and practical skill development.
**UC4 - code-exchange** - Just like Github, code-exchange works as a collection of code repositories of cisco and community.

## AI Evaluation

None, because I carefully prompted AI to follow the rules and requirements and also I checked every response according to the cisco sites to make sure that the output is correct.

## Validation Evidence

- Validator result: VALIDATION COMPLETE 9/9 checks passed.
  <img width="758" height="319" alt="image" src="https://github.com/user-attachments/assets/b96032c1-0274-4b7f-9d5b-221590e77a5d" />
  
- Command used:
- I am selecting a Cisco DevNet resource for a fictional classroom use case.
Use case: [A student team needs immediate access to a shared Cisco environment to practice safe read-only API requests. Administrative changes are not required, and the team cannot wait for provisioning.]
Choose exactly one: learning-lab, always-on-sandbox,
reservation-sandbox, or code-exchange.
Explain which requirement drove your choice. State any access, isolation,
setup, or privilege claim that I should verify in official Cisco documentation.
Do not invent a sandbox product name, URL, account, or credential.

- I am selecting a Cisco DevNet resource for a fictional classroom use case.
Use case: [A development team must test configuration changes with administrative access in a private environment. The team can schedule access, use a VPN, and accept setup time.]
Choose exactly one: learning-lab, always-on-sandbox,
reservation-sandbox, or code-exchange.
Explain which requirement drove your choice. State any access, isolation,
setup, or privilege claim that I should verify in official Cisco documentation.
Do not invent a sandbox product name, URL, account, or credential.

- I am selecting a Cisco DevNet resource for a fictional classroom use case.
Use case: [A beginner needs structured, step-by-step learning content before attempting an independent API activity. The immediate goal is guided practice rather than access to administrative devices.]
Choose exactly one: learning-lab, always-on-sandbox,
reservation-sandbox, or code-exchange.
Explain which requirement drove your choice. State any access, isolation,
setup, or privilege claim that I should verify in official Cisco documentation.
Do not invent a sandbox product name, URL, account, or credential. 

- I am selecting a Cisco DevNet resource for a fictional classroom use case.
Use case: [A developer wants to examine community and Cisco-maintained code repositories for an existing network-automation use case before designing a new solution.]
Choose exactly one: learning-lab, always-on-sandbox,
reservation-sandbox, or code-exchange.
Explain which requirement drove your choice. State any access, isolation,
setup, or privilege claim that I should verify in official Cisco documentation.
Do not invent a sandbox product name, URL, account, or credential. 

- Official Cisco pages reviewed:
- https://developer.cisco.com/docs/sandbox/getting-started/#what-is-devnet-sandbox
- https://developer.cisco.com/learning/labs/learning-labs/
- https://developer.cisco.com/codeexchange/
  
## Git Evidence

- Initial commit message: Initializing DevNet resources
- Validation commit message: Complete Validated Student Plan
- Output of `git log --oneline`:
- <img width="708" height="235" alt="image" src="https://github.com/user-attachments/assets/a8319ff2-a15d-44b5-8519-a6d6c490c739" />


## AI-Use Disclosure

State the AI tool used, the type of assistance received, what was independently checked, and what you revised.
I used ChatGPT/Codex to help classify complex technical terms. It also helped me draft coding materials. With that I indepedently checked and verified the recommendations using the Cisco documentation and revised the the summary of ChatGPT.
