# GitHub Profile README Design

## Goal
Create a professional GitHub Profile README that balances academic credibility and engineering depth for PhD/RA applications, ML/AI roles, and general personal branding.

## Audience
- PhD / RA reviewers
- ML / AI hiring managers
- Open-source collaborators
- General visitors to the GitHub profile

## Design Direction
A balanced professional profile: academic/professional in tone, with selective technical depth. The README should read like a compact research-and-engineering portfolio rather than a decorative landing page.

## Current Repository Context
- Existing profile README is at `README.md`
- Current version overemphasizes confidential Huawei research projects that should not be displayed publicly
- Repository is minimal and dedicated to the profile README

## Content Strategy
The README should focus on public, non-confidential work and separate personal projects from open-source contributions.

### Section 1: About Me
Purpose: establish identity and positioning quickly.

Content:
- Name
- Current affiliation: NTU Singapore
- Short positioning statement combining research and engineering interests
- Focus areas: Computer Vision, LLM systems, Agentic AI

Tone:
- concise
- credible
- technical but not overloaded

### Section 2: Selected Projects
Purpose: showcase public projects you directly own or lead.

Projects to feature:
- `oc-loop`
- `ai-interview-agent`
- `Paper-Reader`

For each project, describe:
- what problem it solves
- what kind of system it is
- the technical angle or differentiator

Presentation format:
- compact project cards or a clean markdown table
- emphasis on clarity over decoration

Recommendation:
Use a markdown table if the project summaries can stay short and punchy; otherwise use short bullet blocks per project.

### Section 3: Open Source Contributions
Purpose: demonstrate ability to contribute upstream, debug real systems, and collaborate in public codebases.

Repositories to feature:
- `paperclipai/paperclip`
- `LiuMengxuan04/MiniCode`
- `coding-kitties/investing-algorithm-framework`

Narrative style:
- mention the problem area
- mention contribution type such as bug fix, platform compatibility, configuration improvement, or Windows/encoding support
- highlight merged PRs where applicable

This section should communicate engineering maturity and practical problem-solving.

### Section 4: Research & Engineering Interests
Purpose: replace the current loose “quick facts” section with a sharper intellectual profile.

Include themes such as:
- multimodal AI
- computer vision
- LLM systems / inference infrastructure
- agentic systems
- applied ML engineering

This section should be short and directional, not a long list.

### Section 5: Tech Stack
Purpose: give recruiters and collaborators a quick view of tools.

Group into a few categories:
- Languages
- Frameworks / Libraries
- Systems / Platforms
- Tooling

Keep only technologies you want to be associated with.

### Section 6: GitHub Signals
Purpose: provide lightweight activity proof without clutter.

Recommendation:
- keep 1–2 stats widgets only
- remove overly busy visual elements if they distract from the profile narrative
- prefer GitHub stats and top languages over a crowded activity graph

### Section 7: Contact
Purpose: provide clean professional contact options.

Keep:
- email
- LinkedIn

Optional:
- personal site or blog if it supports your profile

Remove:
- phone number
- unnecessary social links if not actively used for professional identity

## Approaches Considered

### Approach A: Minimal academic profile
Pros:
- very clean
- strong for faculty viewers

Cons:
- underplays engineering execution
- weaker for AI engineer hiring

### Approach B: Balanced professional profile
Pros:
- strongest fit for current goals
- supports both academic and industry audiences
- lets projects and contributions reinforce each other

Cons:
- requires careful curation to avoid sounding generic

### Approach C: Technical showcase profile
Pros:
- strongest engineering impression
- more memorable for developer audiences

Cons:
- can feel noisy or self-promotional
- less suitable for academic review

## Chosen Approach
Approach B: Balanced professional profile.

## Recommended Information Architecture
1. About Me
2. Selected Projects
3. Open Source Contributions
4. Research & Engineering Interests
5. Tech Stack
6. GitHub Signals
7. Contact

## Writing Principles
- No confidential Huawei research details
- Prefer concrete project descriptions over vague self-praise
- Keep every section skimmable
- Avoid too many badges or decorative widgets
- Optimize for credibility and readability on first glance

## Visual / Layout Principles
- clean markdown hierarchy
- restrained emoji use, if any
- generous whitespace via section breaks
- no fancy banners required
- professional and technical appearance

## Scope Boundaries
Included:
- README structure
- section purpose
- featured project selection
- contribution positioning
- content direction

Not included:
- implementation of final README copy in this spec
- non-README personal website work
- visual mockups
