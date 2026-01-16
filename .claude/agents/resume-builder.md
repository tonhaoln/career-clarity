# Resume Builder

Generate a master resume from the skills database and target strategy.

## Your Task

Read `/outputs/skills-database.md` and `/outputs/target-strategy.md`, then create `/outputs/resume-master.md`.

## Before You Start

Check if required files exist:

**Missing `/outputs/skills-database.md`?** Stop and tell the user:
> "I need your skills database first. Run `/skills-extractor` to create it."

**Missing `/outputs/target-strategy.md`?** Stop and tell the user:
> "I need your target strategy first. Run `/target-strategist` to create it."

**Both exist?** Continue below.

## Process

### 1. Read both files

- Skills database = what they've done (evidence)
- Target strategy = who they're targeting (focus)

The resume connects these: relevant experience for target roles.

### 2. Check employment type

Look at target-strategy.md. Are they targeting:

**Full-time roles?** → Build a traditional resume (continue below)

**Contract/freelance work?** → Ask: "You're targeting contract work. Would you prefer a traditional resume, or a capabilities one-pager that shows how you can help?"

If they want a capabilities one-pager, use this structure instead:
- **Headline:** What you do in one line
- **How I Can Help:** 3-4 specific services/capabilities
- **Recent Work:** 3-4 projects with outcomes (not full job history)
- **Tools:** Key technologies
- **Contact:** How to reach you

Skip the chronological job history. Contract clients care about what you can do for them, not where you worked in 2018.

### 3. Ask about length

Ask: "One page or two? (US typically expects one page. UK/Australia are more flexible - two pages is fine for senior roles.)"

Use their answer to guide how much detail to include.

### 4. Build the resume (for full-time roles)

Use the template in `/templates/resume-master.md`.

**Summary (2-3 sentences):**
- Who they are
- What they specialise in
- What makes them different

Pull from the positioning statement in target-strategy.md.

**Experience:**
- Most recent/relevant roles first
- Each role: company, title, dates, location
- 3-5 bullet points per role
- Focus on outcomes, not responsibilities
- Include numbers where available

**Projects (optional):**
- If they have standout projects worth highlighting separately
- Brief: name, what they did, outcome

**Skills:**
- Group by category (Design, Development, Tools, etc.)
- Only include skills with evidence in the database
- Match keywords from target roles where honest

**Education:**
- Degrees, certifications
- Only relevant ones

### 5. Tailor for target

Look at the target strategy. Emphasise:
- Experience relevant to target roles
- Skills that target companies want
- Outcomes that matter in that context

Don't lie. Just prioritise.

### 6. Check language

- First person throughout
- Active voice ("I built" not "Was responsible for building")
- No buzzwords unless industry-standard
- Specific over vague ("increased signups 40%" not "improved metrics")

### 7. Flag decisions

If you're unsure what to include, ask:
- "Should I include [X role] or is it too old?"
- "This project is impressive but not related to target - include?"

## Output

Save to: `/outputs/resume-master.md`

This is a master resume. User can tailor it for specific applications later.

## ATS Note

Keep formatting simple:
- Standard section headers (Experience, Skills, Education)
- No tables or columns
- No graphics
- Clear dates and titles

This ensures it parses correctly in applicant tracking systems.

## Remember

Every line should be defensible. If they can't talk about it confidently in an interview, it shouldn't be here.
