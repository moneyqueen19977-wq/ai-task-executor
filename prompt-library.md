# Prompt Library

This is a starter set of reusable prompts. Each prompt is designed to reduce vague task descriptions and improve execution quality.

## 1) Task Framing Prompt

Use this when you need to turn a rough idea into a usable brief.

Prompt:

"I have an idea and I want to turn it into a high-quality AI execution brief. Please help me define this task clearly before I start any work. Ask me for the missing details, but keep the process efficient. I want a structured output that includes: objective, scope, inputs, constraints, success criteria, best AI choice, prompt, workflow, and validation plan."

## 2) AI Routing Prompt

Use this when you want the AI to choose the right tool or workflow.

Prompt:

"Given this task, decide which AI or workflow is best. Consider whether this is research, coding, writing, planning, debugging, or multi-step execution. Recommend the best AI, the best prompt style, the need for an agent, and the most efficient execution process. Explain why this choice is better than a generic assistant."

## 3) Code Implementation Prompt

Use this when the task is code-related.

Prompt:

"Review the repository and implement the requested change. First provide a brief plan with assumptions and risks. Then make the necessary edits. Keep the scope tight. Do not add unnecessary features. Validate the result with the smallest relevant tests or checks. If you are unsure about the intended behavior, call out the ambiguity and propose the safest option."

## 4) Debugging Prompt

Use this when you need code triage.

Prompt:

"I am experiencing a failure in this repo. Review the error logs, identify the root cause, and propose the smallest safe fix. Explain the reason for the bug, outline the fix plan, and verify the result with the most relevant validation step. Make sure to preserve existing behavior outside the issue being fixed."

## 5) Research Prompt

Use this when you need analysis or benchmarking.

Prompt:

"Research this topic and provide a concise but complete analysis. Include the key trade-offs, important considerations, and practical recommendations. Cite or reference your sources where possible. Separate facts from assumptions. Highlight missing or uncertain information and propose what to validate next."

## 6) Planning Prompt

Use this when you need structure before execution.

Prompt:

"Create a practical plan for this task. Include goals, assumptions, milestones, risks, dependencies, and validation checkpoints. Recommend the best order of operations. Keep it actionable and specific enough to hand to a human or AI agent without further clarification."

## 7) Documentation Prompt

Use this when you need docs or communication.

Prompt:

"Write documentation for this task or topic for the specified audience. Keep the output clear, concise, and actionable. Include a summary, goals, required context, technical notes, and any caveats. Use the tone and format appropriate to the audience."

## 8) Multi-Step Agent Prompt

Use this when you need a workflow instead of a one-shot answer.

Prompt:

"Break this task into phases and execute it in a disciplined order. Start with a plan, then proceed through implementation in logical milestones. After each milestone, validate the result and proceed only if it meets the defined criteria. Keep a short record of decisions, risks, and follow-up items."

## 9) Validation Prompt

Use this when you need the AI to verify correctness.

Prompt:

"Review the output for correctness, completeness, and edge cases. Check whether it matches the original instructions, constraints, and success criteria. Identify issues, propose fixes, and rank any remaining risks. Keep the validation focused and actionable."

## 10) Prompt for Reducing Context Waste

Use this when you want the AI to work more efficiently.

Prompt:

"Use the minimum required context to complete this task correctly. Do not ask for unnecessary clarifications or re-explain the task unless it is required. Assume I want efficient execution, not chatty back-and-forth. If there is ambiguity, state the ambiguity succinctly and propose the safest assumption."

## Quick Prompt Formula

Use this formula when creating your own prompts:

"Task: [what needs to be done]
Goal: [outcome]
Constraints: [rules, stack, deadlines]
Deliverables: [exact output]
Success criteria: [how we know it is done]
Preferred workflow: [research / code / writing / planning / agent]
Validation: [how to check]
"

## Best practice

Always include:
- what to do
- what success looks like
- what constraints apply
- what should not happen
- how validation works

This is the difference between a vague ask and an execution-ready task.
