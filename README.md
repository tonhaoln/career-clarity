# Career Clarity

Turn your scattered career history into aligned positioning.

---

## What This Does

You have years of work spread across LinkedIn, old resumes, project notes, and your head. This tool pulls it together into one clear foundation:

1. **Skills Database** - Everything you've done, structured and searchable
2. **Target Strategy** - Who you're targeting and how you'll position yourself
3. **Master Resume** - Built from your actual work, not a template

No hype. No inflation. Just clarity.

---

## Requirements

- [Claude Code](https://claude.ai/code) installed
- Your career materials (LinkedIn, old resume, portfolio, anything)

**New to Claude Code?**

[5-minute setup guide](https://code.claude.com/docs/en/quickstart) - install, login, done.

---

## Quick Start

### 1. Get your materials ready

Drop everything into the `/inputs/` folder:
- LinkedIn profile (copy-paste the text, or PDF export)
- Old resume (any format)
- Portfolio link
- Project notes, case studies, anything relevant

More input = better output. Don't overthink it.

### 2. Run the agents

Navigate to this folder in terminal and run `claude`:

```bash
cd /path/to/your/career-clarity
claude
```

Then tell Claude to run each agent. Example:

```
> please run the skills extractor
```

Claude will ask you questions as you go - just answer like you would in a normal chat. Check your outputs in `/outputs/`, edit as needed, done.

**Run in order:**

1. `/skills-extractor` - Creates your skills database
2. `/target-strategist` - Defines your positioning
3. `/resume-builder` - Generates your resume from the database + strategy

### 3. Edit and refine

Review each output. Edit freely - these are starting points, not final drafts.

### 4. Check consistency (after editing)

Once you've made changes, tell Claude to run the `/consistency-check`:

```
> please run the consistency check
```
Catches drift between documents - mismatched numbers, mixed voice, claims that don't align.

### 5. Export

Your finished materials are in `/outputs/`. Copy them wherever you need.

---

## Time

3-4 hours for a complete foundation. Compare that to days of staring at a blank resume.

---

## Philosophy

This isn't a resume template. Templates start with someone else's structure and ask you to fill in blanks.

This starts with YOUR actual work and translates it into consistent positioning.

Every claim must be defensible. If you can't explain it in an interview, it shouldn't be on your resume.

---

## Tips

- **Be honest with the agents.** They'll ask clarifying questions. Answer them.
- **Review each output before moving on.** You know your career better than any AI.
- **Edit freely.** The outputs are starting points, not final drafts.
- **No inputs? No problem.** The skills-extractor can interview you directly if your folder is empty.
- **See an example.** Check `/examples/skills-database-example.md` to see what a finished database looks like.

---

## Questions?

This tool was built for people with scattered careers who struggle to explain their value on demand.

If that's you, it should help. If you get stuck, the problem is usually in the inputs - add more context.

---

## Been meaning to try Claude Code?

If you've been curious about Claude Code but haven't had a reason to try it - this is a good excuse.

You'll clone a repo, run some agents, and actually get something useful at the end. Not a tutorial output. Your actual career materials.

Practical way to learn.

---

*Built with Claude Code. No email gate. No signup. Just use it.*
