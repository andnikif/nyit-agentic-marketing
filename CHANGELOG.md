# Changelog

All notable changes to the NYIT Agentic Marketing Certification site.

---

## [2026-02-23] MS Synergy Integration — Scholarship Model, Expanded Curriculum, Course Mapping

**Context:** Dean Jai reviewed the official MS in Marketing Technology, AI and Analytics program doc alongside the certificates. He wanted them positioned as complementary (not overlapping), a recommendation on credit vs. scholarship (we recommend scholarship), and expanded curriculum detail.

### MS Program Name Correction
- Changed "MS in Marketing Technology & Social Media Analytics" → "MS in Marketing Technology, AI and Analytics" everywhere to match official program doc

### Scholarship Model (replaces course credit model)
- Replaced course credit model (1 credit/cert) with tuition scholarship model ($500/cert)
- Completing all 6 certificates = $3,000 scholarship toward MS tuition
- Added "Two Complementary Layers" explanation: Certificates = Applied Practitioner, MS = Analytical & Architectural

### Certificate-to-MS Mapping
- Added mapping table showing which MS courses each certificate prepares students for
- Added MS Curriculum Overview (Core 15cr + Specialized 15cr with course codes)
- Updated 3-step pathway cards for scholarship model ($1,500 → $3,000 → Enroll)

### Expanded Curriculum Detail (all 6 tracks)
- Added prerequisites block to each track (yellow left-bordered box)
- Added 3-5 learning objectives per module across all tracks
- Added tools & platforms tags per module (blue pill tags)
- Added deliverables per module (italic line)
- Added "MS Pathway Connection" block after each capstone (navy left-bordered box showing related MS courses)
- Increased module list max-height from 600px to 2000px for expanded content

### New CSS
- `.module-prereqs` — prerequisite boxes
- `.module-objectives` — learning objective lists
- `.tool-tag` — tool/platform pill tags
- `.module-deliverable` — deliverable descriptions
- `.track-ms-connection` / `.ms-course-tag` — MS pathway connection blocks

### Other Updates
- Hero tagline updated to mention MS pathway
- Next Steps step 4 updated for scholarship model
- Added ~80 lines of new CSS

---

## [2026-02-13] Simplify Language & Add MS Feeder Pathway

**Context:** Dean Jai's feedback — website language was too advanced/scary for faculty who will teach these certificates. Also added positioning of certificates as feeders into the upcoming MS in Marketing Technology & Social Media Analytics.

### Track Name Simplification
- Track 1: "AI-Driven Market Intelligence & Synthetic Consumer Insights" → "AI-Powered Market Research & Consumer Insights"
- Track 2: "Marketing Operations & Agentic Workflow Automation" → "Marketing Operations & AI Workflow Automation"
- Track 3: "Generative Brand Strategy & Content Governance" → "AI-Enhanced Brand Strategy & Content Management"
- Track 4: "Predictive Product Marketing & Lifecycle Architecture" → "AI-Powered Product Marketing & Campaign Planning"
- Track 5: "Revenue Enablement & Sales Intelligence Systems" → "Sales Enablement & AI-Powered CRM"
- Track 6: Kept as-is (already accessible)

### Curriculum Module Simplification (~20 edits)
- Core Foundation: replaced LLM/transformer jargon with practical descriptions (e.g., "How AI tools work: a practical overview...")
- Track 1: "Synthetic Consumer" → "AI-Simulated Consumer Research", "Conversational Data Interrogation" → "AI-Powered Data Analysis"
- Track 2: "Autonomous Workflows" → "Automated Workflows", "agents" → "automations/workflows"
- Track 3: "Brand Voice Fine-Tuning" → "Brand Voice Customization", "Multi-Modal Storytelling" → "Visual & Video Content Creation with AI", "Brand Bot" → "Brand Content Assistant"
- Track 4: "Competitive Intelligence Agents" → "AI-Powered Competitive Analysis", "Launch Simulation" → "AI-Powered Launch Planning"
- Track 5: "Dynamic Battlecards" → "Real-Time Sales Knowledge Bases", "Predictive Lead Scoring" → "AI-Enhanced Lead Qualification"

### Section-Level Language Simplification (~15 edits)
- "The Disruption Vector" → "How AI is Changing Marketing Roles"
- "The 'Hollow Middle' Phenomenon" → "The Mid-Career Skills Gap"
- Pain point solutions: "Computational Sensemaking" → "Data-Driven Decision Making", "Hybrid Creativity" → "Human + AI Content Creation", "Lifecycle Architecture" → "Integrated Campaign Planning", "Responsible AI Ops" → "AI Quality Assurance & Compliance"
- Personas: "The 'Frozen Middle'" → "Mid-Career Professionals", "The 'Data Migrant'" → "Data & Analytics Professionals", "The 'Tech-Forward Pivot'" → "Sales & CRM Professionals"
- Thesis banner: simplified "Copilot era to Agentic AI" → "simple AI assistance to fully automated AI workflows"
- Closing CTA: "Agentic Workflows" → "AI-Powered Workflows"

### New: MS Feeder Pathway Section
- Added new section (id="ms-pathway") between 6 Tracks and ROI
- Credit rationale: each certificate = 1 graduate credit toward the 30-credit MS
- 3-step visual pathway: Year 1 (3 certs, 3 credits) → Year 2 (3 more, 6 total) → Year 3+ (enroll with 20% done)
- Added "MS Pathway" nav link
- Added 4th Next Step: "Formalize the MS Pathway"
- Updated section numbering (ROI → Section 7, Next Steps → Section 8)

---

## [2025-12-20] Update Pricing to $1,499 with IRS Section 127 Rationale

- Changed per-certificate price from $995 to $1,499
- Replaced credit card financing rationale with IRS Section 127 employer reimbursement strategy
- 3 certs × $1,499 = $4,497, within the $5,250/year tax-free cap

---

## [2025-12-19] Initial Site Launch

- Initial NYIT Agentic Marketing certification site with 6 tracks, market data, competitive positioning, personas, ROI section, and pricing
