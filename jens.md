# UX/Mendix Skills Documentation

This document provides an overview of the specialized AI skills created for UX/Mendix development work.

## What Was Created

A comprehensive set of 5 specialized AI skills tailored for your workflow as a UX/Mendix developer/designer, along with a quick reference guide.

### Files Created

```
claude-skills/skills/
├── ux-designer/
│   └── skill.md                    # UX Designer skill
├── mendix-developer/
│   └── skill.md                    # Mendix Developer skill
├── ux-researcher/
│   └── skill.md                    # UX Researcher skill (with personas)
├── design-system-specialist/
│   └── skill.md                    # Design System Specialist skill
├── javascript-developer/
│   └── skill.md                    # Mendix JavaScript Developer skill
└── skills.md                       # Quick reference overview
```

## The 5 Skills

### 1. UX Designer (`claude-skills/skills/ux-designer/skill.md`)

**Purpose**: Expert in user-centered design, Figma mastery, and design thinking

**Core Capabilities**:
- Advanced Figma proficiency (components, auto-layout, variants, prototyping)
- Design-to-code workflows
- Wireframing and prototyping
- Visual design (typography, color theory, layout)
- Accessibility-first design (WCAG 2.1 AA)
- Responsive and mobile-first design
- Design system architecture

**When to Use**:
- Designing user interfaces and experiences
- Creating Figma components and design systems
- Building wireframes and prototypes
- Establishing visual design patterns
- Optimizing designs for development handoff
- Setting up design file organization

---

### 2. Mendix Developer (`claude-skills/skills/mendix-developer/skill.md`)

**Purpose**: Expert in Mendix low-code development with focus on UX/UI customization

**Core Capabilities**:
- Mendix Studio Pro expertise
- Atlas UI framework customization
- SASS/CSS theming for Mendix apps
- Custom design properties (.json + .scss)
- Modular design systems in Mendix 9.6+
- Responsive multi-device applications
- Performance optimization

**When to Use**:
- Building Mendix applications
- Customizing Atlas UI themes
- Creating custom design properties
- Implementing design systems in Mendix
- Converting Figma designs to Mendix layouts
- Writing SASS/CSS for Mendix apps
- Creating reusable page templates

---

### 3. UX Researcher (`claude-skills/skills/ux-researcher/skill.md`)

**Purpose**: Expert in user research, customer personas, and data-driven insights

**Core Capabilities**:
- Research-backed persona development (behavioral segments)
- Multi-source data analysis (CRM, support tickets, surveys, interviews)
- Pattern analysis across hundreds of data points
- Interactive artifact creation (explorable persona visualizations)
- Journey mapping with friction points and customer quotes
- Revenue opportunity analysis
- Quick win identification from support tickets
- AI-augmented research with Extended Thinking

**When to Use**:
- Developing 3-4 customer personas based on actual behavior
- Planning and conducting user interviews
- Creating user journey maps
- Analyzing research data for patterns
- Synthesizing research into actionable insights
- Presenting findings to stakeholders
- Identifying revenue opportunities by segment

**Special Feature - Claude Persona Methodology**:
This skill includes the complete Claude approach to building customer personas:
1. Data collection from multiple sources
2. Pattern analysis with Extended Thinking
3. Behavioral segmentation (3-4 customer types)
4. Interactive artifact creation
5. Actionable insights (revenue opportunities, quick wins)
6. Multiple deliverable formats (interactive + written reports)

---

### 4. Design System Specialist (`claude-skills/skills/design-system-specialist/skill.md`)

**Purpose**: Expert in HTML/CSS component libraries and design tokens (no frameworks)

**Core Capabilities**:
- Pure HTML/CSS solutions (no JavaScript frameworks)
- Modern CSS (Grid, Flexbox, Custom Properties, Container Queries)
- Design token architecture with CSS Variables
- CSS architecture (BEM, CUBE CSS, OOCSS)
- WCAG 2.1 AA accessibility compliance
- Mobile-first responsive design
- Component documentation and style guides
- Performance optimization

**When to Use**:
- Creating design token systems with CSS Variables
- Building accessible, responsive component libraries
- Converting Figma designs to HTML/CSS
- Implementing multi-theme systems (light/dark mode)
- Establishing CSS architecture and naming conventions
- Creating fluid, responsive layouts
- Building typography and color systems

---

### 5. Mendix JavaScript Developer (`claude-skills/skills/javascript-developer/skill.md`)

**Purpose**: Expert in creating JavaScript Actions for Nanoflows and Mendix Client API

**Core Capabilities**:
- JavaScript Actions for Nanoflows
- Mendix Client API expertise (mx.data, mx.ui, mx.session, mx.parser)
- Working with MxObjects and entity data
- Promise-based async patterns (wrapping Mendix callbacks)
- Browser API integration (geolocation, localStorage, camera)
- Offline-first logic for mobile apps
- JSDoc documentation for Studio Pro
- Vanilla ES6+ JavaScript (no external libraries)

**When to Use**:
- Creating JavaScript Actions for Nanoflows
- Complex client-side calculations and validations
- Browser API integration
- Third-party integrations (payment gateways, maps, analytics)
- Custom business logic that Nanoflows can't handle
- Real-time client-side validation
- Working with Mendix objects programmatically

**Key Patterns Included**:
- Basic JavaScript Action template with error handling
- Working with Mendix objects (get, set, commit, retrieve)
- XPath data retrieval
- Geolocation and localStorage integration
- Date formatting with mx.parser
- Validation logic (email, phone)
- List sorting and manipulation

---

## Quick Reference Guide (`claude-skills/skills/skills.md`)

A comprehensive overview document that includes:
- Descriptions of all 5 skills
- When to use each skill
- Skill selection guide (by task type)
- Technology stack overview
- Design-to-development workflow integration
- Example usage prompts
- Getting started instructions

## How It Works

### Using the Skills

To use a skill in your Claude conversations, simply reference it when asking for help:

**Examples**:

```
Using the UX Researcher skill, help me create 3 customer personas
for a travel booking app
```

```
As a Mendix Developer, help me customize the Atlas UI theme with
our brand colors
```

```
Using the Design System Specialist skill, create a button component
with CSS variables
```

```
As a Mendix JavaScript Developer, create a JavaScript Action to
validate email addresses for Nanoflows
```

```
Using the UX Designer skill, help me organize my Figma file
structure for a design system
```

### Combining Skills

You can combine multiple skills for complex workflows:

```
Using the UX Designer skill, create a card component in Figma.
Then, as a Design System Specialist, convert it to HTML/CSS.
Finally, as a Mendix Developer, show me how to integrate it into
Atlas UI.
```

### Skill Selection by Task

**Design Work**:
- UI/UX Design → **UX Designer**
- User Research & Personas → **UX Researcher**
- Figma to Code → **UX Designer** or **Design System Specialist**

**Mendix Development**:
- Mendix Apps → **Mendix Developer**
- Mendix Theming → **Mendix Developer**
- Mendix + Figma → **UX Designer** + **Mendix Developer**

**Front-End Development**:
- HTML/CSS Components → **Design System Specialist**
- Mendix JavaScript Actions → **Mendix JavaScript Developer**
- Design Systems → **Design System Specialist**
- Nanoflows + JavaScript → **Mendix JavaScript Developer**

**Research & Strategy**:
- Customer Personas → **UX Researcher**
- User Interviews → **UX Researcher**
- Journey Mapping → **UX Researcher** or **UX Designer**

## Your Technology Stack

The skills are optimized for:

- **Design**: Figma
- **Development Platform**: Mendix (low-code)
- **Styling**: HTML, CSS, SASS/SCSS
- **Client-Side Logic**: Nanoflows + JavaScript Actions
- **Mendix API**: mx.data, mx.ui, mx.session, mx.parser
- **Scripting**: Vanilla JavaScript (ES6+, no external libraries)
- **Design Systems**: CSS Variables, BEM, component architecture
- **Accessibility**: WCAG 2.1 AA compliance

## Typical Workflow

### 1. Research Phase
**Use**: UX Researcher skill
- Develop personas from customer data
- Conduct user interviews
- Create journey maps

### 2. Design Phase
**Use**: UX Designer skill
- Create Figma designs
- Build component library
- Design prototypes

### 3. Development Phase
**Use**: Multiple skills
- **Mendix Developer**: Build Mendix app structure and theming
- **Design System Specialist**: Create HTML/CSS components
- **Mendix JavaScript Developer**: Create JavaScript Actions for Nanoflows

### 4. Integration Phase
**Use**: Mendix Developer
- Integrate design system into Mendix
- Customize Atlas UI theme
- Implement responsive behavior

## Key Features

### All Skills Emphasize:
- ✅ WCAG 2.1 AA accessibility compliance
- ✅ Modern best practices (2024)
- ✅ Web standards over frameworks
- ✅ Performance and maintainability
- ✅ Comprehensive documentation

### Special Features:

**UX Researcher**:
- Claude's official "Build Customer Personas" methodology
- Extended Thinking for pattern analysis
- Interactive artifacts with clickable journey stages
- Revenue opportunity analysis

**Mendix JavaScript Developer**:
- Production-ready JavaScript Action templates
- Mendix Client API patterns (mx.*)
- BEGIN USER CODE / END USER CODE markers
- JSDoc for Studio Pro integration
- No npm packages (Mendix constraint)

**Design System Specialist**:
- No JavaScript frameworks (pure HTML/CSS)
- Modern CSS features (Grid, Flexbox, Container Queries)
- Design token architecture
- BEM methodology examples

## Git Information

**Branch**: `claude/add-ux-skills-personas-011CV2En9mJ9cttaNCGx2tVc`

**Commits**:
1. Initial creation of 5 specialized skills
2. Enhanced UX Researcher with Claude persona-building methodology
3. Refocused JavaScript Developer for Mendix Nanoflows

**Status**: All changes committed and pushed ✅

## Quick Start

1. **Read the overview**: Start with `claude-skills/skills/skills.md`
2. **Pick a skill**: Choose based on your current task
3. **Reference it**: Mention the skill in your Claude conversation
4. **Combine as needed**: Use multiple skills for complex workflows

## Support

Each skill file contains:
- Core competencies
- Best practices (2024)
- Code examples and patterns
- Common use cases
- Output style guidelines
- Integration notes

---

**Created**: November 11, 2024
**Skills Version**: 1.0
**Last Updated**: November 11, 2024
