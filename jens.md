# UX/Mendix Skills Documentation

This document provides an overview of the specialized AI skills created for UX/Mendix development work.

## What Was Created

A comprehensive set of 12 specialized AI skills tailored for your workflow as a UX/Mendix developer/designer and ZZP'er, along with a quick reference guide. Includes personalized business writing skills, legal protection for contracts, project estimation tools, professional PDF design, and NextJS + Tailwind development.

### Files Created

```
claude-skills/skills/
├── ux-designer/
│   └── SKILL.md                    # UX Designer skill
├── mendix-ux-developer/
│   └── SKILL.md                    # Mendix UX Developer skill
├── ux-researcher/
│   └── SKILL.md                    # UX Researcher skill (with personas)
├── design-system-specialist/
│   └── SKILL.md                    # Design System Specialist skill
├── mendix-javascript-developer/
│   └── SKILL.md                    # Mendix JavaScript Developer skill
├── automation-tester/
│   └── SKILL.md                    # Automation Tester skill
├── dutch-business-writer/
│   └── SKILL.md                    # Dutch Business Text Writer skill (Jens's style)
├── english-business-writer/
│   └── SKILL.md                    # English Business Text Writer skill (Jens's style)
├── contract-legal-advisor/
│   └── SKILL.md                    # Contract Review & Legal Advisor skill (Dutch ZZP)
├── project-scoping-estimator/
│   └── SKILL.md                    # Project Scoping & Estimation Specialist skill
├── pdf-designer/
│   └── SKILL.md                    # PDF Designer skill (branded PDFs)
├── nextjs-tailwind-developer/
│   └── SKILL.md                    # NextJS + Tailwind Developer skill (SaaS focused)
└── skills.md                       # Quick reference overview
```

## The 12 Skills

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

### 2. Mendix UX Developer (`claude-skills/skills/mendix-ux-developer/SKILL.md`)

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

### 5. Mendix JavaScript Developer (`claude-skills/skills/mendix-javascript-developer/SKILL.md`)

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

### 6. Automation Tester (`claude-skills/skills/automation-tester/skill.md`)

**Purpose**: Expert in testing online tools and websites using free, web-based testing software

**Core Capabilities**:
- Accessibility testing (WCAG 2.1 AA compliance)
- Performance testing (Lighthouse, WebPageTest, GTmetrix)
- Cross-browser compatibility testing (BrowserStack, LambdaTest free tiers)
- Functional testing with browser automation (Selenium IDE, Katalon Recorder)
- API testing (Postman, Hoppscotch)
- Visual regression testing (Percy, BackstopJS)
- Mobile responsive testing
- Mendix application testing
- Bug reporting and test documentation

**When to Use**:
- Running accessibility audits (WAVE, axe DevTools, Lighthouse)
- Testing website performance and Core Web Vitals
- Validating cross-browser compatibility on real devices
- Creating automated test cases for functional testing
- Testing APIs and integrations
- Performing visual regression testing
- Testing Mendix applications end-to-end
- Creating comprehensive test plans and bug reports

**Free Tools Included**:
- **Browser Tools**: Chrome DevTools, Firefox Developer Tools, Lighthouse
- **Accessibility**: WAVE, axe DevTools, Accessibility Insights
- **Automation**: Selenium IDE, Katalon Recorder, Ghost Inspector (free tier)
- **Cross-Browser**: BrowserStack Live (free tier), LambdaTest (free tier)
- **Performance**: WebPageTest, GTmetrix (free tier), PageSpeed Insights
- **API Testing**: Postman (free tier), Hoppscotch
- **Visual Testing**: Percy (free tier), BackstopJS

**Key Constraint**: All tools must be free or have usable free tiers, and must be web-based (no local installations required)

---

### 7. Dutch Business Text Writer (`claude-skills/skills/dutch-business-writer/skill.md`)

**Purpose**: Expert in professional Dutch business correspondence for ZZP'ers and small businesses

**Core Capabilities**:
- Professional Dutch business writing (formal, semi-formal, informal)
- ZZP-specific correspondence (quotes, invoices, contracts, client emails)
- Payment reminders and collection communication
- Business announcements and networking
- Client acquisition and relationship management
- Professional boundary-setting language
- Complaint handling and customer service
- Dutch business culture and etiquette
- Legal compliance (AVG/GDPR, invoicing requirements)

**When to Use**:
- Writing quotes and proposals (offertes)
- Creating invoice correspondence
- Drafting payment reminders (friendly to assertive)
- Professional client emails
- Contracts and service agreements
- First contact with potential clients
- Setting professional boundaries
- Announcing business updates (rates, vacation, new services)
- Handling complaints and difficult situations
- Any Dutch business text needs

**Key Templates Included**:
- **Quotes**: Formal and informal project proposals
- **Invoices**: Professional invoice correspondence
- **Payment Reminders**: Three-tier approach (friendly, assertive, final)
- **Client Acquisition**: Cold outreach and networking follow-ups
- **Service Offers**: New service announcements to existing clients
- **Boundary Setting**: Scope creep and additional work communication
- **Business Updates**: Rate changes, vacation announcements
- **Rejections**: Professional project declinations

**Cultural Focus**:
- Dutch directness balanced with politeness
- Appropriate use of "u" vs "je"
- Efficient, clear communication
- Collaborative and egalitarian tone
- Professional but relatively informal style
- Transparent pricing and payment communication

---

### 8. English Business Text Writer (`claude-skills/skills/english-business-writer/skill.md`)

**Purpose**: Expert in professional English business correspondence using Jens's personal style

**Core Capabilities**:
- Professionally casual English business writing
- Freelancer/consultant-specific correspondence
- Proposals, invoices, and client emails
- Payment reminders and collection communication
- Business announcements and networking
- Professional boundary-setting language
- Complaint handling and customer service
- Natural, conversational English tone
- Strategic hedging and solution-oriented approach

**When to Use**:
- Writing proposals and quotes
- Creating invoice correspondence
- Drafting payment reminders (friendly to assertive)
- Professional client emails
- Contracts and agreements
- First contact with potential clients
- Setting professional boundaries
- Announcing business updates (rates, vacation)
- Handling complaints and difficult situations
- Any English business text needs

**Key Templates Included**:
- **Proposals**: Standard and informal versions
- **Invoices**: Professional invoice emails
- **Payment Reminders**: Three-tier approach (friendly → assertive → final)
- **Client Acquisition**: Cold outreach and networking follow-ups
- **Service Offers**: New service announcements
- **Boundary Setting**: Scope creep and additional work communication
- **Business Updates**: Rate changes, vacation notices
- **Declinations**: Professional ways to decline work

**Voice Characteristics**:
- "Hi [name]," openings (never "Dear")
- "Cheers," or "Thanks," closings
- Characteristic phrases: "Let me know", "The idea is to", "I ran into"
- Avoids corporate jargon completely ("leverage", "synergy")
- Strategic hedging: "probably", "likely", "as far as I know"
- Solution-oriented communication
- Natural imperfections make it feel human

---

### 9. Contract Review & Legal Advisor (`claude-skills/skills/contract-legal-advisor/skill.md`)

**Purpose**: Expert in Dutch freelance contract review, DBA compliance, and legal protection for ZZP'ers

**Core Capabilities**:
- Dutch ZZP legal landscape and DBA/VAR compliance
- Contract review and red flag identification
- Section-by-section analysis (scope, payment, liability, IP, etc.)
- DBA risk assessment and scoring system
- Negotiation strategies and scripts
- Model clauses in Dutch and English
- IP rights and ownership negotiation
- Liability protection guidance
- Understanding insurance requirements
- Clear guidance on when to hire a lawyer

**When to Use**:
- Reviewing client contracts before signing
- Assessing DBA/VAR risk (schijnzelfstandigheid)
- Understanding and negotiating liability clauses
- Reviewing IP rights and ownership terms
- Evaluating payment terms and conditions
- Checking termination clauses
- Negotiating contract terms with clients
- Identifying legal red flags
- Understanding insurance requirements
- Deciding whether legal help is needed

**Key Red Flags Identified**:
- **DBA Risk**: Fixed hours, exclusive relationship, hierarchical authority
- **Liability**: Unlimited liability, one-sided terms
- **IP Rights**: Transfer before payment, no portfolio rights
- **Payment**: Terms > 60 days, "payment when paid"
- **Non-Compete**: Without compensation, too broad
- **Termination**: Asymmetric terms, no payment for work done

**Negotiation Support**:
- Scripts for common scenarios
- What to say to clients
- Where to compromise vs. hold firm
- Alternative proposal language
- When to walk away

**Dutch Legal Context**:
- Opdrachtenovereenkomst best practices
- Understanding aansprakelijkheid
- Auteursrecht (copyright) under Dutch law
- Wettelijke rente for late payments
- Schijnzelfstandigheid prevention

---

### 10. Project Scoping & Estimation Specialist (`claude-skills/skills/project-scoping-estimator/skill.md`)

**Purpose**: Expert at scoping and estimating UX and Mendix projects to ensure accurate pricing and prevent underpricing

**Core Capabilities**:
- UX project estimation (research, wireframes, design, prototyping)
- Mendix development estimation (domain model, pages, logic, integrations)
- Work breakdown structure creation
- Specific time estimates per task type
- Multiple pricing models (hourly, fixed, phased, value-based)
- Dutch market rates (2024) for UX and Mendix roles
- Scope creep prevention strategies
- Risk assessment and buffer calculations
- Client discovery question templates
- Complete estimation templates

**When to Use**:
- Estimating new UX design projects
- Quoting Mendix development work
- Creating project proposals and quotes
- Breaking down complex projects into tasks
- Calculating fair and profitable pricing
- Preventing scope creep
- Defining clear project deliverables
- Assessing project risks
- Choosing the right pricing model
- Creating phased project plans

**Estimation Coverage**:
- **UX Tasks**: Discovery, research, IA, wireframes, visual design, prototyping, handoff
- **Mendix Tasks**: Setup, domain model, pages, microflows, integrations, security, theming, testing
- **Time Estimates**: Specific hour ranges per task type
- **Buffers**: 15-25% based on complexity
- **Communication Time**: 2-4 hours per week

**Pricing Models Included**:
- Hourly rate pricing
- Fixed price with risk factors
- Phased approach (discovery → design → development)
- Day rate calculations
- Value-based pricing strategies

**Dutch Market Rates (2024)**:
- Junior UX Designer: €50-70/hour
- Medior UX Designer: €70-95/hour
- Senior UX Designer: €95-130/hour
- Junior Mendix Dev: €60-80/hour
- Medior Mendix Dev: €80-110/hour
- Senior Mendix Dev: €110-150/hour
- **UX + Mendix combo**: €85-130/hour (premium for rare skillset)

**Scope Creep Prevention**:
- Clear IN/OUT of scope definitions
- Revision round limits
- Change request process
- Scripts for handling "just quickly" requests
- Written approval requirements

**Complete Templates**:
- Simple UX project (5-page website redesign)
- Simple Mendix app (CRUD with 5 entities)
- Full UX + Mendix project (new app with full UX process)

---

### 11. PDF Designer (`claude-skills/skills/pdf-designer/skill.md`)

**Purpose**: Expert in creating visually appealing, professional PDF documents that reflect brand identity through strategic use of brand colors, typography, and visual styling

**Core Capabilities**:
- PDF design principles (visual hierarchy, white space, grid systems)
- Brand color application in PDFs (60-30-10 rule)
- Typography and font pairing for PDFs
- Page layout and information architecture
- Multiple PDF generation approaches (Figma, Canva, HTML/CSS, Google Docs)
- Templates for common PDF types (proposals, invoices, reports, portfolios)
- Print vs. digital PDF optimization
- Accessibility in PDFs (WCAG compliance, tagged PDFs)
- Professional quality assurance checklist

**When to Use**:
- Designing business proposals and quotes (visual design)
- Creating branded invoices and financial documents
- Building professional reports and documentation
- Designing portfolio case studies and project showcases
- Creating marketing materials (one-pagers, brochures, lead magnets)
- Converting designs to PDF format
- Ensuring brand consistency across all PDF documents
- Optimizing PDFs for print or digital distribution

**PDF Types Covered**:
- **Business Proposals**: Cover pages, sections, CTAs with brand styling
- **Reports**: Title pages, TOC, headers/footers, data visualization
- **Invoices & Quotes**: Professional layouts with clear financial tables
- **Portfolios**: Project pages with before/after comparisons
- **Marketing**: One-pagers, brochures, presentations

**Tool Approaches**:
- **Figma → PDF**: Pixel-perfect design control
- **Canva**: Fast templates with brand kit customization
- **HTML/CSS to PDF**: Automated, repeatable generation (Puppeteer, wkhtmltopdf)
- **Google Docs/Slides**: Collaborative, familiar tools
- **Microsoft Office**: Word/PowerPoint with brand styling

**Brand Application**:
- Primary color (60%): Large backgrounds, headers, section dividers
- Secondary color (30%): Subheadings, accent bars, table headers
- Accent color (10%): CTAs, highlights, key numbers
- Neutral colors: Body text, backgrounds, borders
- Contrast checking for WCAG AA compliance

**Professional Templates Included**:
- Business proposal template (cover + interior pages)
- Invoice template (Dutch and English versions)
- Portfolio case study template
- Professional report template
- Marketing one-pager template

**Quality Checklist**:
- Visual quality (colors, fonts, images, alignment)
- Content quality (no typos, accurate information)
- Technical quality (file size, compatibility, metadata)
- Accessibility (contrast, structure, alt text)

**Integration with Other Skills**:
- Combine with **Business Text Writers** for content + visual design
- Use **Project Scoping** pricing, then design the quote PDF
- Apply **UX Designer** principles to PDF layouts
- Generate PDFs from **Mendix UX Developer** applications

---

### 12. NextJS + Tailwind Developer (`claude-skills/skills/nextjs-tailwind-developer/SKILL.md`)

**Purpose**: Expert in building production-grade SaaS applications with NextJS 14+ App Router and Tailwind CSS, emphasizing mobile-first design, simplicity, and no over-engineering

**Core Capabilities**:
- NextJS 14+ with App Router architecture
- Tailwind CSS 3.4+ with JIT compiler and custom configuration
- Server Components and Client Components patterns
- Mobile-first responsive design (375px base, scale up)
- Type-safe development with TypeScript
- PostgreSQL with Drizzle ORM
- Authentication and authorization patterns
- API Routes with consistent structure
- SEO optimization (metadata API, structured data, sitemaps)
- Performance optimization (Core Web Vitals, bundle analysis)
- Security best practices (validation, rate limiting, headers)
- Form handling and validation (vanilla patterns before libraries)
- Error handling and loading states
- Production deployment strategies

**When to Use**:
- Building SaaS applications from scratch
- Creating landing pages and marketing sites
- Developing web applications with NextJS
- Implementing mobile-first responsive designs
- Setting up authentication flows
- Creating API endpoints and server actions
- Optimizing for performance and SEO
- Building type-safe applications with TypeScript
- Working with PostgreSQL and Drizzle ORM
- Implementing form validation and error handling

**Philosophy - No Over-Engineering**:
- Start with React state before Redux or Zustand
- Use vanilla form validation before React Hook Form
- Fetch API before tanstack-query unless pagination/caching needed
- CSS Modules or Tailwind before CSS-in-JS libraries
- Simple patterns before complex abstractions
- Extract components only when reused 3+ times
- Prove the need before adding libraries

**Key Patterns Included**:
- **Mobile-First Design**: 375px starting point, semantic breakpoints
- **Form Validation**: Field-level validation with touched state tracking
- **API Routes**: Consistent structure (IP check → rate limit → validate → process)
- **Error Handling**: User-friendly messages, logging, fallback UI
- **Server Components**: Default to server, client only when needed
- **Type Safety**: Strict TypeScript configuration with Drizzle types
- **Performance**: Web Vitals tracking, bundle analysis, image optimization

**Real-World Production Patterns**:
Based on actual production code from togwaarde and flesvoedingcalculator projects:
- Custom form validation without libraries
- Mobile-first calculator interfaces
- Type-safe database queries with Drizzle
- Server-side data fetching patterns
- Client-side state management
- Error boundaries and loading states
- SEO-optimized metadata
- Accessibility considerations

**Technology Stack**:
- **Framework**: NextJS 14+ (App Router)
- **Styling**: Tailwind CSS 3.4+
- **Language**: TypeScript (strict mode)
- **Database**: PostgreSQL with Drizzle ORM
- **Deployment**: Vercel (recommended) or similar platforms
- **Testing**: Playwright for E2E, Vitest for unit tests
- **Validation**: Zod for schema validation
- **Forms**: Start vanilla, use react-hook-form if needed
- **State**: React state/context, add zustand only if necessary

**Design Principles**:
- Mobile-first always (375px → 768px → 1024px → 1280px)
- Utility-first CSS with Tailwind
- Strong design sense and visual polish
- Accessibility built-in (semantic HTML, ARIA when needed)
- Fast page loads and Core Web Vitals optimization
- SEO-friendly from the start
- Type safety everywhere
- Simple, maintainable code

**Integration with Other Skills**:
- Completely separate from **Mendix UX Developer** work
- Can use **UX Designer** for Figma designs → NextJS implementation
- Apply **Design System Specialist** CSS patterns in Tailwind
- Use **PDF Designer** for generating PDFs from NextJS apps
- Combine with **Business Text Writers** for content and copy

**When NOT to Use This Skill**:
- Mendix projects (use **Mendix UX Developer** instead)
- Pure HTML/CSS sites (use **Design System Specialist**)
- WordPress or other CMS work
- Backend-only API development
- Mobile native apps (React Native is different)

---

## Quick Reference Guide (`claude-skills/skills/skills.md`)

A comprehensive overview document that includes:
- Descriptions of all 12 skills
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
As a Mendix UX Developer, help me customize the Atlas UI theme with
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

```
As an Automation Tester, create a test plan for accessibility
testing our Mendix application using free tools only
```

```
Using the Automation Tester skill, help me test cross-browser
compatibility with BrowserStack free tier
```

```
As a Dutch Business Text Writer, help me write a professional quote
for a new web design project
```

```
Using the Dutch Business Text Writer skill, create a friendly payment
reminder for an invoice that's 10 days overdue
```

```
As an English Business Text Writer, help me write a proposal for
UX consulting services for a new client
```

```
Using the English Business Text Writer skill, create a second payment
reminder for a client who's 30 days overdue
```

```
As a Contract Review & Legal Advisor, review this client contract
and identify DBA risks and red flags
```

```
Using the Contract Review & Legal Advisor skill, help me negotiate
better liability terms in this MSA
```

```
As a Project Scoping & Estimation Specialist, estimate a Mendix app
with 15 entities, 30 pages, and 2 REST integrations
```

```
Using the Project Scoping & Estimation Specialist skill, create a
detailed quote for redesigning a 10-page Mendix application
```

```
As a NextJS + Tailwind Developer, help me build a mobile-first
calculator interface with form validation
```

```
Using the NextJS + Tailwind Developer skill, create an API route
with rate limiting and validation for a contact form
```

```
As a NextJS + Tailwind Developer, help me set up Drizzle ORM with
PostgreSQL for a SaaS application
```

### Combining Skills

You can combine multiple skills for complex workflows:

```
Using the UX Designer skill, create a card component in Figma.
Then, as a Design System Specialist, convert it to HTML/CSS.
Finally, as a Mendix UX Developer, show me how to integrate it into
Atlas UI.
```

### Skill Selection by Task

**Design Work**:
- UI/UX Design → **UX Designer**
- User Research & Personas → **UX Researcher**
- Figma to Code → **UX Designer** or **Design System Specialist**

**Mendix Development**:
- Mendix Apps → **Mendix UX Developer**
- Mendix Theming → **Mendix UX Developer**
- Mendix + Figma → **UX Designer** + **Mendix UX Developer**

**NextJS/SaaS Development**:
- SaaS Applications → **NextJS + Tailwind Developer**
- Landing Pages → **NextJS + Tailwind Developer**
- Mobile-First Web Apps → **NextJS + Tailwind Developer**
- API Routes & Server Actions → **NextJS + Tailwind Developer**
- TypeScript + Drizzle ORM → **NextJS + Tailwind Developer**
- Form Validation & Handling → **NextJS + Tailwind Developer**
- SEO & Performance Optimization → **NextJS + Tailwind Developer**

**Front-End Development**:
- HTML/CSS Components → **Design System Specialist**
- Mendix JavaScript Actions → **Mendix JavaScript Developer**
- Design Systems → **Design System Specialist**
- Nanoflows + JavaScript → **Mendix JavaScript Developer**
- NextJS Components → **NextJS + Tailwind Developer**

**Research & Strategy**:
- Customer Personas → **UX Researcher**
- User Interviews → **UX Researcher**
- Journey Mapping → **UX Researcher** or **UX Designer**

**Testing & Quality Assurance**:
- Accessibility Testing → **Automation Tester**
- Performance Testing → **Automation Tester**
- Cross-Browser Testing → **Automation Tester**
- Functional Testing → **Automation Tester**
- API Testing → **Automation Tester**
- Mendix App Testing → **Automation Tester**
- Visual Regression Testing → **Automation Tester**

**Business Communication (ZZP/Dutch)**:
- Quotes & Proposals → **Dutch Business Text Writer**
- Invoices & Payment Reminders → **Dutch Business Text Writer**
- Client Emails → **Dutch Business Text Writer**
- Contracts & Agreements → **Dutch Business Text Writer**
- Professional Networking → **Dutch Business Text Writer**
- Setting Boundaries → **Dutch Business Text Writer**
- Any Dutch Business Text → **Dutch Business Text Writer**

**Business Communication (English/Freelance)**:
- Proposals & Quotes → **English Business Text Writer**
- Invoices & Payment Reminders → **English Business Text Writer**
- Client Emails → **English Business Text Writer**
- Contracts & Agreements → **English Business Text Writer**
- Professional Networking → **English Business Text Writer**
- Setting Boundaries → **English Business Text Writer**
- Any English Business Text → **English Business Text Writer**

**Business & Legal (ZZP/Freelance)**:
- Contract Review → **Contract Review & Legal Advisor**
- DBA Risk Assessment → **Contract Review & Legal Advisor**
- Liability Clauses → **Contract Review & Legal Advisor**
- IP Rights Negotiation → **Contract Review & Legal Advisor**
- Payment Terms Review → **Contract Review & Legal Advisor**
- Contract Negotiation → **Contract Review & Legal Advisor**
- Legal Red Flags → **Contract Review & Legal Advisor**

**Project Management & Pricing**:
- Project Estimation → **Project Scoping & Estimation Specialist**
- Creating Quotes → **Project Scoping & Estimation Specialist**
- Scope Definition → **Project Scoping & Estimation Specialist**
- Preventing Scope Creep → **Project Scoping & Estimation Specialist**
- Pricing Strategy → **Project Scoping & Estimation Specialist**
- Time Estimates → **Project Scoping & Estimation Specialist**
- Risk Assessment → **Project Scoping & Estimation Specialist**

## Your Technology Stack

The skills are optimized for:

### Mendix Stack
- **Design**: Figma
- **Development Platform**: Mendix (low-code)
- **Styling**: HTML, CSS, SASS/SCSS
- **Client-Side Logic**: Nanoflows + JavaScript Actions
- **Mendix API**: mx.data, mx.ui, mx.session, mx.parser
- **Scripting**: Vanilla JavaScript (ES6+, no external libraries)
- **Design Systems**: CSS Variables, BEM, component architecture
- **Accessibility**: WCAG 2.1 AA compliance
- **Testing**: Free, web-based tools (Lighthouse, WAVE, Selenium IDE, Postman, BrowserStack free tier)

### NextJS/SaaS Stack
- **Framework**: NextJS 14+ (App Router)
- **Styling**: Tailwind CSS 3.4+
- **Language**: TypeScript (strict mode)
- **Database**: PostgreSQL with Drizzle ORM
- **Deployment**: Vercel or similar platforms
- **Testing**: Playwright (E2E), Vitest (unit tests)
- **Validation**: Zod for schema validation
- **State Management**: React state/context, zustand when needed
- **Design Approach**: Mobile-first (375px → 768px → 1024px → 1280px)
- **Philosophy**: No over-engineering, simple patterns first

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
- **Mendix UX Developer**: Build Mendix app structure and theming
- **Design System Specialist**: Create HTML/CSS components
- **Mendix JavaScript Developer**: Create JavaScript Actions for Nanoflows

### 4. Integration Phase
**Use**: Mendix UX Developer
- Integrate design system into Mendix
- Customize Atlas UI theme
- Implement responsive behavior

### 5. Testing Phase
**Use**: Automation Tester skill
- Run accessibility tests (WAVE, axe, Lighthouse)
- Perform cross-browser testing (BrowserStack, LambdaTest)
- Execute functional test cases (Selenium IDE)
- Test responsive behavior on devices
- Validate performance metrics (WebPageTest, GTmetrix)
- Test APIs with Postman
- Document bugs and test results

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
- **Feedback log** for continuous improvement

---

## Feedback System

Each skill includes a built-in feedback mechanism to enable continuous improvement.

### How It Works

At the end of each skill file, there's a **Skill Feedback Log** section where agents (or humans) can report:

- **Bugs**: Issues with skill instructions or incorrect guidance
- **Documentation Gaps**: Missing examples, unclear explanations
- **Enhancements**: Suggestions for improvement
- **Success Stories**: What worked well
- **Questions**: Areas needing clarification

### Feedback Template

```yaml
---
date: YYYY-MM-DD
agent: [agent identifier or "human"]
type: [bug|documentation|enhancement|success|question]
priority: [high|medium|low]
status: [open|in-progress|resolved|wontfix]
description: |
  Clear description of the issue, gap, or suggestion.
  Be specific about what didn't work or what's missing.
context: |
  What were you trying to accomplish?
  What did you expect vs what happened?
resolution: |
  [Leave empty initially, fill when resolved]
  How was this addressed?
---
```

### Why This Matters

**All in One Package**: Feedback is stored directly with the skill, not in a separate system. This keeps everything together and makes it easy to review and iterate.

**Agent-Friendly**: Different agents may interpret instructions differently. By logging their experiences, you can identify patterns and improve clarity.

**Continuous Improvement**: As you use these skills, you'll discover gaps, edge cases, and opportunities for enhancement. The feedback log captures this knowledge.

**Version History**: The git commits combined with feedback entries create a complete history of how each skill evolved.

### Using Feedback to Improve Skills

1. **Review Regularly**: Check feedback logs periodically
2. **Identify Patterns**: Multiple agents reporting similar issues indicates priority
3. **Update Skills**: Address feedback by improving documentation or examples
4. **Mark as Resolved**: Update feedback entries with resolution details
5. **Track Metrics**: Feedback statistics show overall skill health

### Current Feedback Status

Each skill has started with sample feedback entries:

- **UX Designer**: Enhancement request for Figma plugin recommendations
- **UX Researcher**: Success story about Claude persona methodology integration
- **Mendix UX Developer**: Enhancement request for design property examples
- **Design System Specialist**: Enhancement request for modern CSS examples
- **Mendix JavaScript Developer**: Success story about Nanoflow refocus
- **Automation Tester**: Enhancement request for automated test script examples

---

**Created**: November 11, 2024
**Skills Version**: 2.2
**Last Updated**: November 19, 2024

### Recent Updates

**Version 2.2 (November 19, 2024)**:
- Added **NextJS + Tailwind Developer** skill (#12) for SaaS development
- Updated **Mendix UX Developer** skill with real-world SCSS patterns (FMO Design System)
- Updated **Mendix JavaScript Developer** skill with production JavaScript Actions examples
- Updated **PDF Designer** skill with ReportLab Python script and improvement recommendations
- Restructured all skills with proper YAML frontmatter for Claude Code compatibility
- Changed all filenames from `skill.md` to `SKILL.md` per Claude Code requirements

**Version 2.1 (November 18, 2024)**:
- Enhanced UX Researcher skill with Claude's official persona-building methodology
- Added comprehensive persona development process (7 steps)
- Integrated Extended Thinking for pattern analysis

**Version 2.0 (November 11, 2024)**:
- Added business writing skills (Dutch and English)
- Added Contract Review & Legal Advisor skill
- Added Project Scoping & Estimation Specialist skill
- Added PDF Designer skill
- Expanded from 6 to 11 skills

**Version 1.0 (Initial Release)**:
- Core UX and Mendix development skills
