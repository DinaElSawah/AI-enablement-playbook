# Case Study: From Zero to Org-Wide Adoption

**Context:** A K-12 international school with several hundred students across multiple year groups, no existing AI policy, and a teaching staff ranging from AI-curious to AI-anxious.

## The challenge

Leadership wanted to adopt generative AI to support lesson planning, assessment, and administrative work — but there was no usage policy, no shared skill baseline among staff, and real (reasonable) concern about safety, data privacy, and consistency of quality if everyone was left to experiment on their own.

## The approach

1. **Needs assessment first.** Surveyed staff comfort and concerns before designing anything. The two loudest themes: fear of getting it "wrong" in front of students or parents, and uncertainty about what data was safe to use.
2. **Wrote the policy before the training.** An AI usage policy was authored and approved by leadership so every subsequent training session could point to a real, sanctioned standard — not an ad hoc one.
3. **Built a tiered curriculum**, matching the structure in this playbook: a Foundations session for all staff, a Practitioner track for those building lesson materials and assessments regularly, and an Advanced track for a small group who went on to help train others.
4. **Delivered hands-on, role-relevant training** — not generic AI literacy, but sessions built around real lesson-planning and assessment tasks staff already did weekly.
5. **Built structured, reusable workflows** (JSON-based prompt templates) so consistent, safe outputs didn't depend on each teacher's individual prompting skill.
6. **Evaluated quality continuously** — structured criteria for accuracy, coherence, and hallucination risk were used to stress-test the templates before they were rolled out school-wide.

## The results

- **70+ staff trained** across foundational and practitioner-level sessions
- A complete **AI & ML curriculum built for Years 3–9**, reaching **~240 students annually** across more than six year groups
- An organization-wide **AI usage policy** adopted and actively referenced by leadership for tool selection and governance decisions
- **Structured LLM workflows** deployed for lesson planning, assessment, and reporting — reducing manual turnaround time on routine documentation
- A small internal **champions group** capable of supporting colleagues without escalating every question back to one person

## What I'd tell someone starting this from scratch

Don't lead with the tool — lead with the fear. Every one of those 70+ staff had a real, specific concern before they had any curiosity. The training that worked wasn't the one with the best AI content; it was the one that named the fear out loud in the first five minutes and then spent the rest of the session proving it wasn't going to happen.

The templates and framework in this repo ([`01-needs-assessment.md`](./01-needs-assessment.md), [`02-tiered-curriculum.md`](./02-tiered-curriculum.md), [`03-facilitator-guide.md`](./03-facilitator-guide.md)) are the generalized version of what made this rollout work.
