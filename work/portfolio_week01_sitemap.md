# Portfolio Build — Week 1: Draw the Path

## Working proof statement

> I can turn content search-performance data into a transparent, evidence-backed page-review priority queue.

**One person:** a content analytics manager hiring a junior data/ML analyst for a search or content team.
**One action:** invite me to an interview for a junior data/ML analyst role.

## Small sitemap

```text
Home (/)
├── Work (/work)
│   └── Case study detail pages (only when a project has evidence)
├── About (/about)
└── Contact (/contact)
```

| Page | What it must prove | How it moves the visitor to the one action |
|---|---|---|
| Home | The proof statement, a concise introduction, and featured evidence from one or two projects. | Makes the promise clear immediately; “View my work” and “Contact me” buttons provide the next step. |
| Work | Each case study shows the problem, method, evidence, limitations, and outcome—not just tools used. | Gives a hiring manager reasons to believe the claim, with a contact call-to-action after the work. |
| About | The short human context behind the work: current learning focus, values, and working style. | Builds trust without repeating the résumé; links directly to contact. |
| Contact | A simple email/contact method and a one-sentence invitation to discuss roles or projects. | Removes friction at the one desired action. |

**Pages deliberately excluded:** a blog, separate skills page, gallery, testimonials page, and extra landing pages. They do not yet add enough proof for the single action; skills and short updates can appear on Home or Work when supported by real evidence.

## Sketch to draw and photograph

On paper, draw four boxes in this order and connect them with arrows:

```text
[ HOME ] ── View evidence ──> [ WORK ] ── Believe claim ──> [ CONTACT ]
     │                             │
     └──────── Learn who I am ─> [ ABOUT ] ────────────────┘
```

Write the proof statement above the Home box and **“Contact me about an ML/data opportunity”** below the Contact box. Take one clear photo of your own sketch for the assignment.

## Claude Project setup

**Project name:** ML/Data Portfolio Build — Eight Weeks

**Custom instructions to paste into Claude:**

> My portfolio must prove: “I can turn content search-performance data into a transparent, evidence-backed page-review priority queue.” My primary visitor is a content analytics manager hiring a junior data/ML analyst for a search or content team. The one action I want is: invite me to an interview for a junior data/ML analyst role. Act as a patient tutor, not a ghostwriter. Ask me for real evidence before making claims; flag vague language, unsupported results, privacy risks, and unnecessary pages. Help me make the smallest portfolio that earns trust. Explain your reasoning in simple language and give me checks I can perform myself.

## First Claude prompt: pressure-test the sitemap

**Prompt to run in the Project:**

> Pressure-test this sitemap against my proof statement and one action. For every page, say whether it earns its place. Identify missing proof, duplicate content, or pages I should remove. Recommend the smallest change that would make the path from Home to Contact clearer. Do not invent project results.  
>  
> Sitemap: Home → Work (case studies) → About → Contact. The Home page has “View my work” and “Contact me” calls to action. Work case studies include problem, method, evidence, limitations, and outcome. My proof statement is: “I can turn content search-performance data into a transparent, evidence-backed page-review priority queue.” My one action is: “Invite me to an interview for a junior data/ML analyst role.”

## Saved pressure-test response (draft)

The map is appropriately small and each page can support the claim. The Work page is the central proof: it should lead with concrete evidence rather than a long tools list. About earns its place only if it adds useful context such as learning focus and working principles; keep it short. Contact should be reachable from every page, not only after Work. A separate skills or blog page is not justified until it contains evidence that strengthens the claim.

**Change I will make:** Add a persistent **Contact** link/button in the site header and on every case-study page. On the Work page, use an evidence-and-limitations section so the portfolio does not overclaim.

## Evidence to attach before submission

- [ ] Photo of the hand-drawn sitemap using the sketch above.
- [ ] Screenshot of the Claude Project named **ML/Data Portfolio Build — Eight Weeks**, showing the custom instructions.
- [ ] Screenshot of the pressure-test prompt and its actual Claude output.
- [ ] Personal evidence that Claude, ChatGPT, Gemini, and Perplexity accounts are set up. Do not share passwords or private account information.
