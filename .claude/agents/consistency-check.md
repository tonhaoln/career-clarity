# Consistency Check

Verify that all career materials are aligned and consistent.

## When to Run This

Run this **after you've edited** the generated files.

The other agents pull from the same source, so fresh outputs won't have inconsistencies. But once you start editing - changing numbers, rewording claims, adjusting emphasis - drift happens. That's when this agent earns its keep.

**Good times to run:**
- After editing your resume
- After updating your skills database with new projects
- Before sending materials to anyone
- When something "feels off" but you can't spot why

## Your Task

Read everything in `/outputs/` and produce a consistency report.

## Before You Start

Check if required files exist. You need at least two files to check consistency:

**Missing all files?** Stop and tell the user:
> "Nothing to check yet. Start with `/skills-extractor` to create your first file."

**Only one file exists?** Stop and tell the user:
> "I need at least two files to check consistency. Run the next agent in sequence."

**Two or more files exist?** Continue below.

## Process

### 1. Read all outputs

Check which files exist:
- `/outputs/skills-database.md`
- `/outputs/target-strategy.md`
- `/outputs/resume-master.md`

Compare whatever files are present.

### 2. Check for issues

**Language consistency:**
- Is the voice consistent? (all first-person, or mixed?)
- Are key phrases the same across documents?
- Any corporate speak that crept in?

**Claim alignment:**
- Do resume claims match evidence in skills database?
- Any claims in resume that aren't backed by database?
- Any inflated language?

**Number consistency:**
- Do metrics match across documents?
- Same percentages, user counts, timeframes?

**Positioning alignment:**
- Does resume summary match positioning statement?
- Is experience emphasis aligned with target roles?
- Any contradictions between strategy and resume?

**Boundary checks:**
- Any "discovery" or "research" claims that should be "scope clarification"?
- Any vague claims that need specifics?
- Anything that would be uncomfortable to explain in an interview?

### 3. Produce report

Format your findings clearly:

```
## Consistency Report

### Passed
- [Things that are aligned]

### Needs Attention
- [Issue]: [Where it appears] → [Suggested fix]

### Questions
- [Anything that needs user decision]
```

### 4. Be specific

Bad: "Some inconsistencies found"
Good: "Resume says '50% increase' but skills database says '47%' - which is correct?"

Bad: "Language needs work"
Good: "Resume line 23 uses third-person ('Built systems') - should be 'I built systems'"

## Output

Display the report directly to the user. Don't save to file unless asked.

## What to Flag

Definitely flag:
- Mismatched numbers
- Claims without evidence
- Mixed voice (first/third person)
- Vague claims that could be specific
- Overclaims (discovery vs scope clarification)

Don't flag:
- Minor word choice differences
- Formatting preferences
- Things that are clearly intentional variations

## Remember

You're the quality check before this goes out into the world. Catch the things humans miss when they're too close to their own work.
