# Implementation Guide: UX/Mendix/SaaS Skills

This guide explains how to implement and use your 12 specialized AI skills in **Claude Code** and **Claude Desktop**.

## Overview

You have **12 professional skills** organized in this repository:

1. **UX Designer** - Figma design, wireframes, prototypes
2. **Mendix UX Developer** - Mendix apps, Atlas UI, theming
3. **UX Researcher** - User research, personas, journey maps
4. **Design System Specialist** - HTML/CSS components, design tokens
5. **Mendix JavaScript Developer** - JavaScript Actions, Nanoflows
6. **Automation Tester** - Testing with free web-based tools
7. **NextJS + Tailwind Developer** - SaaS apps, mobile-first, TypeScript
8. **PDF Designer** - Branded PDFs, proposals, invoices, reports
9. **Dutch Business Text Writer** - Dutch correspondence (your style)
10. **English Business Text Writer** - English correspondence (your style)
11. **Contract Review & Legal Advisor** - Contract review, DBA compliance
12. **Project Scoping & Estimation** - Project estimates, pricing

---

## Part 1: Implementation in Claude Code

Claude Code has native **Agent Skills** support, which means Claude automatically discovers and uses your skills based on context.

### Prerequisites

- **Claude Code version 1.0 or later**
- Basic familiarity with terminal/command line
- Git (for syncing skills across machines)

---

### Step 1: Choose Your Implementation Strategy

You have two options:

#### Option A: Personal Skills (Recommended for Solo Use)
**Location**: `~/.claude/skills/`
- Available across **all your projects**
- Not shared with team
- Synced via your dotfiles (if you use dotfiles sync)

#### Option B: Project Skills (Recommended for Teams)
**Location**: `.claude/skills/` (in each project)
- Shared with team via git
- Project-specific
- Team members get skills automatically

**For your use case**, I recommend **Option A (Personal Skills)** since these are general-purpose skills you'll use across all projects.

---

### Step 2: Install Skills to Claude Code

#### Option A: Personal Skills Installation

```bash
# Navigate to your home directory
cd ~

# Create the Claude skills directory if it doesn't exist
mkdir -p .claude/skills

# Copy all skills from this repository
cp -r /path/to/your/skills/claude-skills/skills/* ~/.claude/skills/

# Verify installation
ls ~/.claude/skills/
```

**Expected output**:
```
ux-designer/
mendix-ux-developer/
ux-researcher/
design-system-specialist/
mendix-javascript-developer/
automation-tester/
nextjs-tailwind-developer/
pdf-designer/
dutch-business-writer/
english-business-writer/
contract-legal-advisor/
project-scoping-estimator/
```

#### Option B: Project Skills Installation (For Team Sharing)

If you want to share skills with your team on a specific project:

```bash
# Navigate to your project directory
cd /path/to/your/project

# Create project skills directory
mkdir -p .claude/skills

# Copy specific skills you want to share
cp -r /path/to/your/skills/claude-skills/skills/mendix-ux-developer .claude/skills/
cp -r /path/to/your/skills/claude-skills/skills/mendix-javascript-developer .claude/skills/

# Commit to git
git add .claude/skills/
git commit -m "Add Mendix development skills"
git push
```

Team members will automatically get these skills when they pull:
```bash
git pull  # Skills are now available
```

---

### Step 3: Verify Installation

Start Claude Code and ask:

```
What Skills are available?
```

or

```
List all available Skills
```

**Expected response**: Claude should list all 12 skills with their descriptions.

---

### Step 4: Test Your Skills

Skills are **model-invoked** (automatic) - Claude decides when to use them based on your request.

#### Test Examples

**Test UX Designer Skill:**
```
I need to organize my Figma file structure for a new design system. What's the best approach?
```

**Test Mendix UX Developer Skill:**
```
How do I create custom design properties for card components in Mendix with different variants?
```

**Test NextJS + Tailwind Developer Skill:**
```
Help me build a mobile-first calculator interface with form validation in NextJS
```

**Test Dutch Business Text Writer Skill:**
```
Schrijf een professionele offerte voor een Mendix project van 3 maanden
```

**Test Contract Review & Legal Advisor Skill:**
```
Review this contract and identify any DBA risks and red flags for a Dutch ZZP'er
```

If Claude uses the correct skill, you'll see context-aware responses based on the skill's knowledge.

---

### Step 5: Update Skills

When you update skills in this repository:

```bash
# Pull latest changes
cd /path/to/your/skills
git pull

# Update personal skills
cp -r claude-skills/skills/* ~/.claude/skills/

# Restart Claude Code to load updates
# Close and reopen Claude Code
```

**Note**: Claude Code must be restarted to load skill updates.

---

## Part 2: Implementation in Claude Desktop

Claude Desktop **does not have native Skills support** (as of November 2024). However, you can still use your skills effectively.

### Strategy: Manual Skill Activation

In Claude Desktop, you **manually reference** skills at the start of your conversation.

---

### Step 1: Keep Skills Accessible

Store this repository somewhere accessible:

```bash
# Clone or update the repository
cd ~/Documents
git clone [your-repo-url] skills

# Or keep it in an easy-to-find location
```

---

### Step 2: Reference Skills in Conversations

#### Method 1: Explicit Skill Reference (Recommended)

Start conversations by telling Claude which skill to use:

```
As a Mendix UX Developer, help me customize the Atlas UI theme with custom SASS variables
```

```
Using the UX Researcher skill, help me create 3 customer personas for a travel booking app
```

```
As a Dutch Business Text Writer, help me write a professional quote for a new web design project
```

#### Method 2: Paste Skill Content (For Complex Tasks)

For complex tasks, paste the relevant section of the skill:

1. Open the skill file (e.g., `claude-skills/skills/mendix-ux-developer/SKILL.md`)
2. Copy the relevant section
3. Paste into your conversation with context

**Example:**
```
I need help with Mendix SCSS customization. Here's the relevant skill section:

[paste SCSS examples from SKILL.md]

Now, help me customize the form inputs with our brand colors.
```

#### Method 3: Upload Skill Files (Projects Feature)

If you have Claude Desktop with Projects feature:

1. Create a new Project
2. Add the relevant skill files to the Project knowledge
3. Claude will reference them automatically in that Project

---

### Step 3: Create Conversation Templates

Save common conversation starters in a text file for quick reference:

**File: `~/Documents/skills/conversation-templates.txt`**

```txt
=== UX DESIGN ===
As a UX Designer, help me with [task]

=== MENDIX DEVELOPMENT ===
As a Mendix UX Developer, help me with [task]

=== NEXTJS DEVELOPMENT ===
As a NextJS + Tailwind Developer, help me with [task]

=== BUSINESS COMMUNICATION (DUTCH) ===
As a Dutch Business Text Writer, help me with [task]

=== BUSINESS COMMUNICATION (ENGLISH) ===
As an English Business Text Writer, help me with [task]

=== CONTRACT REVIEW ===
As a Contract Review & Legal Advisor, help me with [task]

=== PROJECT ESTIMATION ===
As a Project Scoping & Estimation Specialist, help me with [task]
```

Copy and paste the relevant template when starting a conversation.

---

## Part 3: Best Practices (Both Platforms)

### 1. Be Specific When Invoking Skills

**Good:**
```
As a Mendix UX Developer, help me create custom design properties for
card components with different variants using the FMO Design System
```

**Too vague:**
```
Help me with Mendix
```

---

### 2. Combine Multiple Skills

For complex workflows, use multiple skills in sequence:

**Example: Complete Project Flow**
```
First, as a UX Researcher, help me create 3 customer personas.

Then, as a UX Designer, design the interface based on these personas.

Finally, as a Mendix UX Developer, show me how to implement this
design in Atlas UI.
```

---

### 3. Reference Production Code Examples

The skills contain real production code. Reference specific sections:

**Example:**
```
As a Mendix JavaScript Developer, I need to create a snackbar system
similar to the JS_ShowSnackbar example in the skill. Show me the pattern.
```

---

### 4. Use Skills for Learning

Ask skills to explain concepts:

```
As a NextJS + Tailwind Developer, explain the "no over-engineering"
philosophy and when I should use vanilla patterns vs libraries
```

---

## Part 4: Troubleshooting

### Claude Code Issues

#### Issue: "Claude doesn't use my skill"

**Solution 1: Check skill description**
```bash
# View the skill's frontmatter
head -n 10 ~/.claude/skills/mendix-ux-developer/SKILL.md
```

Ensure the description includes trigger keywords relevant to your request.

**Solution 2: Be more explicit**
Instead of: "Help me with forms"
Try: "Help me style Mendix form inputs with SCSS"

**Solution 3: Verify file location**
```bash
# Check skills are in the right place
ls -la ~/.claude/skills/*/SKILL.md
```

**Solution 4: Restart Claude Code**
Close and reopen Claude Code to reload skills.

#### Issue: "Skill has errors"

**Check YAML syntax:**
```bash
# View frontmatter
head -n 10 ~/.claude/skills/skill-name/SKILL.md

# Ensure:
# - Line 1 is "---"
# - YAML is valid (no tabs, correct indentation)
# - Closing "---" before Markdown content
```

**Run in debug mode:**
```bash
claude --debug
```

This shows skill loading errors.

---

### Claude Desktop Issues

#### Issue: "Claude doesn't follow the skill instructions"

**Solution**: Be more explicit about which skill to use:

Instead of:
```
Help me write a Dutch quote
```

Use:
```
As a Dutch Business Text Writer, help me write a professional quote
for a Mendix project. Use the formal tone and structure from the skill.
```

#### Issue: "Response doesn't match skill style"

**Solution**: Reference specific sections:

```
As an English Business Text Writer, write a proposal using the
"professionally casual" tone described in the skill. Start with
"Hi [name]," and close with "Cheers," as shown in the examples.
```

---

## Part 5: Syncing Skills Across Machines

### Option 1: Personal Skills with Dotfiles (Recommended)

If you use dotfiles management (like chezmoi, yadm, or git bare repo):

1. Add `~/.claude/skills/` to your dotfiles
2. Commit and push
3. On new machines, your dotfiles sync will install skills automatically

### Option 2: Git Repository (This Approach)

Keep skills in this git repository:

**On Machine 1:**
```bash
cd ~/Documents/skills
git pull
cp -r claude-skills/skills/* ~/.claude/skills/
```

**On Machine 2:**
```bash
cd ~/Documents/skills
git pull
cp -r claude-skills/skills/* ~/.claude/skills/
```

### Option 3: Symbolic Link

Create a symlink from Claude's skills directory to your git repo:

```bash
# Remove default skills directory if it exists
rm -rf ~/.claude/skills

# Create symlink to your git repo
ln -s ~/Documents/skills/claude-skills/skills ~/.claude/skills

# Now updates to the git repo automatically update Claude Code
```

**Benefit**: Changes sync automatically when you `git pull`.

---

## Part 6: Updating Skills

### When to Update

Update skills when:
- You add new production code examples
- Best practices change
- You discover better approaches
- Team members provide feedback

### How to Update

**Step 1: Edit in Git Repo**
```bash
cd /path/to/skills
code claude-skills/skills/mendix-ux-developer/SKILL.md
# Make your changes
```

**Step 2: Test Locally**
```bash
# If using symlink, changes are immediate
# If copying, update:
cp -r claude-skills/skills/* ~/.claude/skills/
```

**Step 3: Restart Claude Code**
Close and reopen to load changes.

**Step 4: Commit and Push**
```bash
git add -A
git commit -m "Update Mendix UX Developer skill with new SCSS patterns"
git push
```

---

## Part 7: Quick Reference

### Command Cheat Sheet

```bash
# List installed skills
ls ~/.claude/skills/

# View a specific skill
cat ~/.claude/skills/mendix-ux-developer/SKILL.md

# Update all skills from git repo
cd /path/to/skills && git pull
cp -r claude-skills/skills/* ~/.claude/skills/

# Check skill frontmatter (first 10 lines)
head -n 10 ~/.claude/skills/skill-name/SKILL.md

# Remove a skill
rm -rf ~/.claude/skills/skill-name

# Debug Claude Code with skills
claude --debug
```

---

### Conversation Starters by Task

| Task | Conversation Starter |
|------|---------------------|
| **Figma Design** | "As a UX Designer, help me [task]" |
| **Mendix Development** | "As a Mendix UX Developer, help me [task]" |
| **NextJS Development** | "As a NextJS + Tailwind Developer, help me [task]" |
| **User Research** | "As a UX Researcher, help me [task]" |
| **JavaScript Actions** | "As a Mendix JavaScript Developer, help me [task]" |
| **Testing** | "As an Automation Tester, help me [task]" |
| **Dutch Communication** | "As a Dutch Business Text Writer, help me [task]" |
| **English Communication** | "As an English Business Text Writer, help me [task]" |
| **Contract Review** | "As a Contract Review & Legal Advisor, help me [task]" |
| **Project Estimation** | "As a Project Scoping & Estimation Specialist, help me [task]" |
| **PDF Design** | "As a PDF Designer, help me [task]" |

---

## Part 8: Team Collaboration

### Sharing Skills with Your Team

#### Option 1: Project Skills (Recommended for Teams)

**Setup once per project:**
```bash
cd /path/to/project
mkdir -p .claude/skills

# Copy relevant skills
cp -r ~/path/to/skills/claude-skills/skills/mendix-ux-developer .claude/skills/
cp -r ~/path/to/skills/claude-skills/skills/mendix-javascript-developer .claude/skills/

# Commit
git add .claude/skills/
git commit -m "Add Mendix development skills for team"
git push
```

**Team members get skills automatically:**
```bash
git pull  # Skills are now available in Claude Code
```

#### Option 2: Shared Repository

Create a shared team repository:

```bash
# Create shared repo
git clone [team-skills-repo] ~/team-skills

# Each team member:
ln -s ~/team-skills/claude-skills/skills ~/.claude/skills
```

---

## Part 9: Advanced Configuration

### Custom Skill for Your Workflow

Create a meta-skill that combines multiple skills:

**File: `~/.claude/skills/jens-workflow/SKILL.md`**

```yaml
---
name: jens-workflow
description: Complete workflow for UX/Mendix projects combining design, development, and business tasks. Use when starting a new project or handling full project lifecycle.
---

# Jens Complete Workflow

## Project Phases

### 1. Discovery & Estimation
- Use **Project Scoping & Estimation** skill for quotes
- Use **UX Researcher** for user research if needed
- Use **Contract Review & Legal Advisor** for contract review

### 2. Design Phase
- Use **UX Designer** skill for Figma designs
- Use **Design System Specialist** for HTML/CSS if needed

### 3. Development Phase
- Use **Mendix UX Developer** for Mendix apps
- Use **Mendix JavaScript Developer** for custom logic
- Use **NextJS + Tailwind Developer** for SaaS projects

### 4. Testing & QA
- Use **Automation Tester** for accessibility and testing

### 5. Communication & Invoicing
- Use **Dutch Business Text Writer** or **English Business Text Writer**
- Use **PDF Designer** for professional proposals/invoices

## Quick Commands

Ask me to:
- "Start a new Mendix project" → I'll guide through all phases
- "Review a contract" → Contract Review skill
- "Create a quote" → Estimation skill
- "Write an invoice email" → Business Writer skill
```

Now you can say:
```
Using the jens-workflow skill, help me start a new Mendix project
```

---

## Part 10: FAQ

### Q: Do I need both Claude Code and Claude Desktop?

**A**: No. Choose based on your workflow:
- **Claude Code**: For development work, coding, file operations (has native Skills support)
- **Claude Desktop**: For general conversations, research, writing (manual skill reference)

### Q: Can I use these skills in the Claude web app?

**A**: Not automatically. The web app doesn't have Skills support. Use the "manual reference" method (explicitly state which skill to use).

### Q: How do I know which skill Claude is using?

**A**: In Claude Code, Claude will mention the skill when it activates. In Claude Desktop, you explicitly choose by stating it.

### Q: Can I modify the skills?

**A**: Yes! Edit the SKILL.md files directly. Remember to restart Claude Code after changes.

### Q: What if two skills conflict?

**A**: Be specific in your request. Instead of "help with forms", say "help with Mendix form styling using SCSS" (triggers Mendix UX Developer skill).

### Q: Can I share skills outside my organization?

**A**: Yes! These skills are in your git repository. You can share the repository or individual skills with others.

---

## Part 11: Maintenance

### Monthly Maintenance Checklist

- [ ] Update skills with new production code examples
- [ ] Review skill descriptions for accuracy
- [ ] Test skills with recent Claude Code versions
- [ ] Update version numbers in SKILL.md files
- [ ] Commit and push changes
- [ ] Notify team of significant updates

### Version Control

Track skill versions in each SKILL.md:

```markdown
### Version History
- v2.2.0 (2024-11-19): Added production SCSS examples
- v2.1.0 (2024-11-18): Enhanced with real code patterns
- v2.0.0 (2024-11-11): Initial release
```

---

## Summary

### ✅ Claude Code Setup (5 minutes)

```bash
# 1. Copy skills to Claude directory
cp -r /path/to/skills/claude-skills/skills/* ~/.claude/skills/

# 2. Verify
ls ~/.claude/skills/

# 3. Test
# Open Claude Code and ask: "What Skills are available?"
```

### ✅ Claude Desktop Setup (Ongoing)

- Reference skills explicitly: "As a [Skill Name], help me with [task]"
- Keep skill files accessible for reference
- Use conversation templates

### ✅ Team Setup (Optional)

```bash
# Add skills to project
mkdir -p .claude/skills
cp -r ~/skills/claude-skills/skills/mendix-* .claude/skills/
git add .claude/skills/ && git commit -m "Add skills" && git push
```

---

## Need Help?

**Skill Issues**:
- Check YAML syntax in SKILL.md frontmatter
- Verify file location: `~/.claude/skills/skill-name/SKILL.md`
- Restart Claude Code
- Run `claude --debug` to see errors

**Questions**:
- Review USAGE.md for skill-specific usage examples
- Check jens.md for complete skill documentation
- Ask Claude: "Explain how to use the [Skill Name] skill"

---

**Version**: 1.0
**Last Updated**: November 19, 2024
**Skills Version**: 2.2
