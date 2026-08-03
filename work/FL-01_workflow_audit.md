# FL-01 — AI Workflow Audit and Tool Setup

**Profile:** Student and ML-internship participant working on Python/data projects.

## Recurring workflow audit

| Recurring task | Classification | Why this is the right level of AI involvement |
|---|---|---|
| Plan my weekly study and internship work | Collaborate with AI | AI can turn deadlines and estimated effort into a draft plan, but I decide priorities and protect time for difficult work. |
| Read course notes and technical documentation | Just me | I need to build my own understanding and notice what I do not yet understand; a summary is not a substitute for reading. |
| Turn class notes into revision questions | Delegate to AI with review | AI can draft varied questions quickly; I check that each question reflects the source material and is at the right difficulty. |
| Solve graded coursework or assessments | Just me | The submitted reasoning must be mine, and using AI for answers would make it hard to know whether I learned the material. |
| Draft a first outline for an internship notebook | Collaborate with AI | I choose the research question and claims; AI helps structure sections and identify missing decisions or risks. |
| Load a CSV and calculate descriptive checks | Collaborate with AI | AI can suggest reproducible code, while I run it, inspect results, and verify the numbers against the data dictionary. |
| Debug a Python error | Collaborate with AI | AI can explain likely causes and propose a small fix; I supply the real error, test the fix, and keep only code I understand. |
| Write documentation and README updates | Delegate to AI with review | AI is useful for a clear first draft, but I verify commands, file paths, and claims before sharing it. |
| Search for library/API documentation | Delegate to AI with review | AI can point to relevant concepts or official pages; I check current primary documentation before using an API. |
| Review a notebook for leakage or unsupported claims | Collaborate with AI | AI can provide a checklist, but I decide feature timing, target definition, and whether the evidence supports the claim. |
| Commit completed project work to Git | Fully automate | After I inspect the diff and choose a message, a saved local command can consistently stage, commit, and report the result. |
| Back up project files and remove temporary outputs | Fully automate | A scheduled, scoped backup/cleanup routine is repeatable; it must exclude secrets and never delete source data without a reviewable rule. |
| Write messages for mentors, classmates, or recruiters | Delegate to AI with review | AI can improve clarity and tone, but I provide the facts and make the final message sound like me. |
| Decide which project direction to pursue | Just me | This decision depends on my interests, constraints, and responsibility for the outcome; AI may inform it but should not make it. |

## Three target tasks for FL-02 through FL-04

| Target task | Reuse plan | “Done well” definition |
|---|---|---|
| Turn a real Python error into a minimal, tested fix | In FL-02, write a prompt that includes the full traceback, relevant code, expected behavior, and request for the smallest explanation and patch. | The fix reproduces locally, changes only necessary files, passes the relevant check, and I can explain the root cause in my own words. |
| Audit a notebook claim against its data and validation | In FL-03, give AI the claim, evidence, target/feature timing, and request a claim-evidence-leakage checklist. | Every factual statement has evidence; current/proxy labels are named honestly; no future/label-derived feature is used; limitations are written plainly. |
| Produce a Git commit handoff after finishing a scoped task | In FL-04, automate the repeatable checks: show status/diff summary, run a specified validation command, and create a commit only after I approve it. | The workflow never stages unrelated files, stops on failed validation, makes one descriptive commit, and returns the commit hash plus a clean-status check. |

## Toolkit and evidence checklist

- [ ] ChatGPT account set up — add a screenshot or account confirmation.
- [ ] Claude account set up — add a screenshot or account confirmation.
- [x] Anthropic Academy: **AI Fluency: Framework & Foundations** completed (attach the completion/certificate evidence available in my account).
- [ ] Claude Project created — attach a screenshot showing the Project name and custom instructions, without exposing private data.

## Claude Project custom instructions

**Project name:** ML Internship Copilot

> I am a student completing an ML internship and Python/data projects. Help me learn rather than merely produce answers. Use clear, direct language and explain unfamiliar terms briefly. For coding, ask for the actual error or relevant file before assuming; propose the smallest safe change; then tell me exactly how to verify it. Never invent data, results, citations, or completed actions. Flag privacy risks, leakage, unsupported claims, and places where my judgment is required. Prefer a transparent baseline before a complex solution. Keep responses concise unless I ask for detail.

## Screenshot to attach before submission

1. Open Claude → **Projects** → **Create Project**.
2. Name it **ML Internship Copilot** and paste the custom instructions above.
3. Take one screenshot showing the Project name and instructions panel. Do not include personal email, passwords, private files, client data, or API keys.

## Reflection

The purpose of this audit is not to apply AI everywhere. I will keep ownership of learning, graded work, final decisions, and factual claims. I will use AI for drafts, structured review, repetitive checks, and debugging support, then validate the result before relying on it.
