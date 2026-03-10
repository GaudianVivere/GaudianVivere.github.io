---
title: "GenAI in Banking: Compliance Countdown to August 2026"
description: "Dirk Röthig explains how DORA, the EU AI Act, and CRR III are redefining GenAI compliance in banking by August 2026 — with an actionable framework for CROs."
tags: [ai-compliance, eu-ai-act, dora, financial-sector, regulation]
series: AI in Business
cover_image: https://images.unsplash.com/photo-1563013544-824ae1b704d3?w=1200
---

# GenAI in Banking: Compliance Countdown to August 2026

**By Dirk Röthig** | CEO, VERDANTIS Impact Capital | March 9, 2026

*For Chief Risk Officers and compliance leaders in financial institutions, 2026 is no ordinary year. With DORA already in force, the EU AI Act approaching its decisive deadline, and the CRR III package recalibrating capital requirements, a regulatory convergence is emerging that demands swift, strategic action — not abstract pilot projects.*

**Tags**: AI Compliance, EU AI Act, DORA, Financial Sector, Regulation

---

## Deadline August 2, 2026: Why Action Is Required Now

August 2, 2026 marks a regulatory turning point whose significance for the financial industry can hardly be overstated. From this date onward, the full compliance obligations of the EU AI Act for so-called "high-risk AI systems" take effect — and the financial sector is directly and intensely affected.

As Dirk Röthig, I observe that many financial institutions still treat the August deadline as an abstract future event. This is a strategic error. The EU AI Act is not the only regulatory framework creating pressure: DORA has been fully binding since January 17, 2025, and the CRR III/CRD VI package is simultaneously reshaping capital requirements for risk models. Three regulatory frameworks, one time window — those who fail to act now risk both regulatory sanctions and substantial implementation costs under time pressure.

This article is not aimed at strategists who wish to describe AI as a competitive advantage. It is aimed at CROs, compliance officers, and risk managers who need concrete answers to the question: What must be implemented by when?

---

## The Three-Pillar Architecture: EU AI Act, DORA, and CRR III

### Pillar 1: EU AI Act — High-Risk Classification Strikes at the Core of Banking

The EU AI Act (Regulation 2024/1689) explicitly classifies a range of AI applications as "high-risk systems" — and the financial sector appears multiple times in Annex III (European Parliament, 2024). Specifically affected are:

- **Creditworthiness assessment and credit scoring** for natural persons
- **AML risk models** (anti-money laundering transaction monitoring)
- **Automated decision-making systems** in lending and insurance premium calculation
- **Biometric identification systems** in customer authentication

For these systems, the AI Act mandates a comprehensive set of obligations from August 2, 2026 (EU AI Act, 2024). These include:

1. **Risk management framework**: Written risk analysis for each affected AI system
2. **Technical documentation**: Complete documentation of training data, architecture, and validation procedures
3. **Conformity assessment**: Either self-assessment or third-party audit, depending on the system category
4. **EU database registration**: Entry into the central EU database for high-risk AI systems
5. **Human oversight**: Demonstrable human supervision and intervention capabilities
6. **Monitoring and logging**: Comprehensive audit trails for all AI-based decisions

The financial risks for non-compliance are substantial: up to €35 million or seven percent of global annual turnover for prohibited AI practices, up to €15 million or three percent for other violations (EU AI Act, 2024). The extraterritorial scope must be noted: every institution serving EU customers falls within the scope of application — regardless of where the AI systems are operated.

More than half of affected organizations have not yet even created a basic AI inventory, according to current market analysis (Nortal, 2026). Meanwhile, compliance costs for high-risk systems at large institutions are estimated at $8 to $15 million per system — early planning is considerably more cost-efficient than last-minute implementation (Axis Intelligence, 2026).

### Pillar 2: DORA — The Foundation of Digital Operational Resilience

The Digital Operational Resilience Act (DORA, Regulation 2022/2554) is no longer a future scenario — it has been fully effective since January 17, 2025 (European Commission, 2023). Regulators are treating 2025 as a transitional phase during which they review frameworks and identify gaps before stricter enforcement measures follow.

For financial institutions deploying generative AI, DORA is relevant in multiple respects:

**Third-party risk management (TPRM):** Banks must maintain a complete register of all ICT third-party providers — including cloud providers, AI API vendors, and model infrastructure service providers. Generative AI predominantly runs on the infrastructure of a few large providers (Microsoft/Azure OpenAI, Google, Amazon), creating concentration and systemic risks that DORA explicitly addresses (Mayer Brown, 2025).

**Operational resilience:** Every AI-based process deemed critical to business operations must be tested for resilience. This means: business continuity planning for AI service outages, fallback procedures, and regular resilience testing (IBM, 2025).

**Contract adjustments:** DORA prescribes specific contractual clauses with ICT third-party providers — including audit rights, incident reporting obligations, and exit strategies. For many fintechs heavily reliant on external infrastructure, this entails significant negotiation and legal effort (Freshfields, 2025).

Sanctions for DORA violations: up to two percent of total annual turnover — with no threshold (European Commission, 2023). For Lead Overseers of critical ICT third-party providers, it is up to one percent of average global daily turnover.

### Pillar 3: CRR III / CRD VI — New Capital Requirements for AI-Driven Risk Models

The CRR III/CRD VI package represents the most comprehensive regulatory initiative for the European banking sector since Basel III and has been in force since 2025 (Basel Committee on Banking Supervision, 2024). For AI-based risk models, a dual relevance emerges:

First, banks must apply stricter methodologies when assessing real estate collateral and credit risk — making the use of AI forecasting models subject to tighter regulatory scrutiny. Second, the package mandates extended disclosure requirements for model risks, which are particularly challenging for generative AI systems whose decision pathways are often difficult to trace (BIS, 2024).

---

## The Explainability Gap: The Central Technical Challenge

When the three regulatory frameworks are reduced to a common denominator, they converge on the same technical problem: **Explainability**. The EU AI Act requires it for high-risk systems. DORA requires it for critical processes. CRR III requires it for risk models.

Generative AI models — particularly large language models (LLMs) — are, however, structurally difficult to explain. They are based on billions of parameters and generate outputs whose causal pathways are not trivially reconstructable (BIS FSI Paper, 2024). The Monetary Authority of Singapore (MAS) already noted in 2024 that there is "a general lack of established methods to explain GenAI outputs and assess their fairness" (MAS, 2024).

For compliance officers, this creates a concrete dilemma: they must provide both regulatory explanations ("Why did the model make this decision?") and customer-facing explanations ("Why was my loan application rejected?") — and satisfy both requirements simultaneously (Harvard Data Science Review, 2025).

Dirk Röthig recommends a pragmatic technology approach here: Retrieval-Augmented Generation (RAG) architectures, where the decision pathway becomes traceable through referenceable documents, combined with separate, interpretable classification models for highly regulated decisions. GenAI handles the analysis and synthesis — the rule-based decision remains with explainable system components.

---

## The Other Front: AI as a Tool for Criminals

The compliance debate in the financial sector must not be reduced to the internal governance problem. Generative AI is simultaneously transforming the external threat landscape fundamentally — and this aspect remains underrepresented in regulatory discussions.

The BioCatch Dark Economy Survey 2025, which surveyed 800 executives in fraud management, AML, and compliance across 17 countries, paints a sobering picture: 70 percent of surveyed experts stated that criminals use AI more effectively to commit financial crime than banks use it to prevent it (BioCatch, 2025). Particularly concerning are the following trends:

- **Deepfake-based identity fraud**: "We can no longer trust our eyes and ears to verify digital identities," stated BioCatch CMO Jonathan Daly (BioCatch, 2025)
- **Mule account networks at industrial scale**: BioCatch clients identified approximately 2.3 million mule accounts used for money laundering in 2024 alone (BioCatch, 2025)
- **AI-powered scam attacks**: More than half of surveyed institutions lost between $5 and $25 million to AI-powered attacks in 2023 (BioCatch, 2025)

Nasdaq estimates that $3.1 trillion in illicit funds flowed through the global financial system in 2023 (Nasdaq, 2023). AI systems for fraud detection are therefore not merely an efficiency measure — they are a regulatory and ethical necessity.

FINRA also emphasized in its 2026 Regulatory Oversight Report that financial institutions are beginning to deploy GenAI solutions focused on internal process efficiency — external threat defense is still lagging behind (FINRA, 2026).

---

## Five-Step Roadmap to AI Compliance

For CROs and compliance officers who want to act now, Dirk Röthig recommends a structured implementation plan:

**Step 1 — AI Inventory (immediately)**
Create a complete register of all deployed AI systems: provider, purpose, data basis, decision relevance. This inventory is a prerequisite for EU AI Act conformity assessments and DORA TPRM requirements.

**Step 2 — High-Risk Classification (Q1 2026)**
Assess each AI use case against the criteria of EU AI Act Annex III. Credit scoring, AML monitoring, and automated investment advisory are very likely to be high-risk relevant. For these systems: begin conformity assessment immediately.

**Step 3 — DORA Contract Adjustment (Q1–Q2 2026)**
Review all ICT third-party provider contracts for DORA compliance. If audit clauses, incident reporting obligations, or exit provisions are missing, renegotiation is required. Concentration risks from a small number of cloud AI providers must be assessed and documented.

**Step 4 — Explainability Infrastructure (Q2 2026)**
Implement technical solutions for traceable AI decisions: RAG architectures for document-grounded outputs, XAI layers for regulatory audit trails, separate validation models for credit decisions.

**Step 5 — EU Database Registration and Governance Documentation (by August 1, 2026)**
Complete quality management systems, risk frameworks, and technical documentation. Register affected high-risk systems in the EU database. Formally document human oversight mechanisms.

---

## Conclusion: Compliance as a Strategic Strength

August 2, 2026 is not an ending but a beginning. Financial institutions that build their AI governance now are not only creating regulatory certainty — they are developing a structural competency that constitutes a genuine competitive advantage in an increasingly regulated AI landscape.

Dirk Röthig therefore sees the regulatory challenge as a strategic opportunity: those who implement generative AI early and compliantly gain the trust of supervisory authorities, institutional partners, and customers. Those who wait pay twice — once for the rushed implementation, once for the potential sanctions.

The question for compliance officers is therefore not: "Must we do this?" The question is: "How do we use this transformation to become better?"

---

## More Articles by Dirk Röthig

- [AI in the Mittelstand: How to Calculate ROI — Sector Benchmarks 2026](https://dev.to/dirkroethig-verdantis/ki-im-mittelstand-roi-richtig-berechnen-sektor-benchmarks-2026-4e6p) — Structured ROI calculation models for CFOs and controllers
- [Demographic Change and AI — Automation Against Labor Shortages 2026](https://dev.to/dirkroethig-verdantis/demografischer-wandel-und-ki-automatisierung-gegen-arbeitskraftemangel-2026-11p7) — How AI cushions demographic pressures in day-to-day business
- [Biodiversity in Agriculture — Mixed Cropping and Agroforestry as Solutions](https://dev.to/dirkroethig-verdantis/biodiversitat-in-der-landwirtschaft-mischanbau-und-agroforst-als-losungsansatz-5gg8) — Strategies for regenerative agriculture and carbon credits

---

## References

1. Axis Intelligence (2026): *EU AI Act News 2026: Compliance Requirements & Deadlines*. Available at: https://axis-intelligence.com/eu-ai-act-news-2026/

2. Basel Committee on Banking Supervision (BCBS) (2024): *Digitalisation of Finance: Risks Associated with Generative AI*. Bank for International Settlements. Available at: https://www.bis.org/publ/othp100.pdf

3. BioCatch (2025): *Dark Economy Survey 2025: Insights into the Invisible — Perspectives on Evolving Fraud and AML Challenges*. Available at: https://www.biocatch.com/dark-economy-survey-2025

4. BIS Financial Stability Institute (2024): *Regulating AI in the Financial Sector: Recent Developments*. FSI Insights on Policy Implementation No. 63. Available at: https://www.bis.org/fsi/publ/insights63.pdf

5. BIS Financial Stability Institute (2024): *How Regulators Can Address AI Explainability*. FSI Papers No. 24. Available at: https://www.bis.org/fsi/fsipapers24.pdf

6. European Commission (2023): *Regulation (EU) 2022/2554 — Digital Operational Resilience Act (DORA)*. Official Journal of the European Union. Available at: https://www.eiopa.europa.eu/digital-operational-resilience-act-dora_en

7. European Parliament (2024): *Regulation (EU) 2024/1689 — Artificial Intelligence Act*. Annex III: High-Risk AI Systems. Available at: https://artificialintelligenceact.eu/annex/3/

8. FINRA (2026): *2026 Regulatory Oversight Report*. Financial Industry Regulatory Authority. Available at: https://www.finra.org/media-center/newsreleases/2025/finra-publishes-2026-regulatory-oversight-report-empower-member-firm

9. Financial Stability Board (FSB) (2025): *Monitoring Adoption of Artificial Intelligence in Financial Services*. Available at: https://www.fsb.org/uploads/P101025.pdf

10. Freshfields Bruckhaus Deringer (2025): *Digital Operational Resilience Act (DORA)*. Freshfields Tech, Data and AI. Available at: https://www.freshfields.com/en/our-thinking/campaigns/tech-data-and-ai-the-digital-frontier/eu-digital-strategy/digital-operational-resilience-act-dora

11. Harvard Data Science Review (2025): *The Future of Credit Underwriting and Insurance Under the EU AI Act: Implications for Europe and Beyond*. Volume 7.3. Available at: https://hdsr.mitpress.mit.edu/pub/19cwd6qx

12. IBM (2025): *What Is the Digital Operational Resilience Act (DORA)?* IBM Think. Available at: https://www.ibm.com/think/topics/digital-operational-resilience-act

13. Mayer Brown (2025): *Cybersecurity in the Financial Sector: EU's Digital Operational Resilience Act Takes Effect*. Available at: https://www.mayerbrown.com/en/insights/publications/2025/01/cybersecurity-in-the-financial-sector-eus-digital-operational-resilience-act-takes-effect

14. Monetary Authority of Singapore (MAS) (2024): *Cited in: BIS FSI Insights No. 63 — Regulating AI in the Financial Sector*. Available at: https://www.bis.org/fsi/publ/insights63.pdf

15. Nasdaq (2023): *Nasdaq Annual Global Financial Crime Report 2024*. Estimate of illicit financial flows 2023. Available at: https://www.biocatch.com/dark-economy-survey-2025

16. Nortal (2026): *2026 EU Financial Services Compliance: Key Regulations & Technology*. Available at: https://nortal.com/insights/eu-financial-services-compliance

---

**About the Author**: Dirk Röthig is CEO of VERDANTIS Impact Capital, headquartered in Zug, Switzerland. As an investor and entrepreneur at the intersection of impact finance, technology, and sustainable agriculture, Röthig guides institutional and private investors in navigating complex regulatory and strategic challenges. VERDANTIS Impact Capital focuses on nature-based investment solutions — carbon credits, agroforestry, and nature-based solutions. More articles and contact: [www.verdantiscapital.com](https://www.verdantiscapital.com)
