---
layout: default
title: Enterprise Tech, Data & AI Job Architecture Report
---
Enterprise Job Architecture, Role Taxonomies, and Leveling Frameworks for Software, Data, and AI Talent Across the Top 100 Technology, FinTech, and Financial Services Organizations
Structural Mechanics of Modern Technical Job Architecture
Enterprise job architecture operates as the foundational classification system that defines, groups, and levels work across an organization independently of its reporting hierarchy. While an organizational chart maps reporting relationships and cost centers, a job architecture establishes the role taxonomy required to govern internal pay equity, external market benchmarking, career progression, talent mobility, and regulatory compliance under mandates such as the European Union Pay Transparency Directive and United States state-level salary disclosure laws. Without a governed taxonomy, organizations suffer from severe title proliferation, inconsistent leveling across business units, and misaligned compensation bands that take years to unwind.   

In modern Human Capital Management (HCM) and Human Resource Information Systems (HRIS) such as Workday, SAP SuccessFactors, Oracle HCM Cloud, and ServiceNow Talent Development Core, technical talent classification is governed by a strict relational hierarchy of data objects. Each layer of the taxonomy serves a distinct operational and analytical purpose, progressing from macro-level functional groupings down to specific employee seats.   

Architectural Layer	HCM / HRIS System Object	Structural Definition	Technical Domain Example (Software, Data & AI)	Primary HR & Compensation Governance Function
Job Function / Group	Job Family Group (Workday) / Function (Radford)	
The broadest operational domain categorizing work by primary business activity and executive reporting line.

Engineering & Technology; Information Technology; Data & Analytics.

Determines executive budget roll-ups and primary external compensation survey source selection.

Job Family	Job Family (Workday / Mercer)	
A cluster of roles sharing core technical capabilities, foundational academic requirements, and lateral mobility pathways.

Software Engineering; Data Science; Machine Learning Engineering; Infrastructure / DevOps.

Establishes baseline career ladders and applies family-wide market pay premiums (e.g., +15% to +25% for AI/ML).

Job Sub-Family / Discipline	Sub-Family / Specialization (Mercer) / Role Specialty (ServiceNow)	
A granular technical specialization within a job family reflecting specific technology stacks or product lifecycles.

Backend Engineering; Client-End Software Development; Applied NLP / RL; Analytics Engineering.

Differentiates skill profiles, technical interview rubrics, and niche market pricing cuts.

Career Stream / Track	Management Level (Workday) / Career Band (WTW)	
The bifurcation of progression pathways by nature of contribution and organizational authority.

Individual Contributor (IC / P), Management (M), Technical Support (T), Executive (E).

Separates technical execution and architectural leadership from people management and hire/fire authority.

Job Level / Grade	Job Level (sn_skills_int_job_level in ServiceNow) / Global Grade	
The vertical tier within a career track measuring scope, autonomy, complexity, and business impact.

P1–P7 / IC1–IC6 / ICT2–ICT6 / L3–L10 / Global Grades GG8–GG17.

Anchors salary bands, target bonus percentages, and long-term incentive (equity) grant guidelines.

Job Profile	Job Profile (Workday / TalentGuard)	
The standardized master role object combining Job Family, Sub-Family, Track, and Level.

Data Scientist IC3; Senior Software Engineer (L5); Machine Learning Engineer 4.

Acts as the single source of truth (SSoT) for job descriptions, exempt status, and country restrictions.

Job Code	Job Code / Survey Match Code	
The unique alphanumeric string identifying a specific Job Profile in the HRIS and linking it to external survey databases.

TECH-SWE-L4 (Internal); EN.SODE.P4 / 5174 (Radford); ENS.03.061.P30 (Mercer).

Automates HRIS-to-survey compensation benchmarking and pay equity audit joins.

Position & Working Title	Position (Workday) / Working Title	
A single budgeted seat occupied by one worker (Position) and its external-facing business label (Working Title).

Staff GenAI Architect (Working Title) mapped to Software Engineer P5 (Job Profile).

Allows recruitment marketing flexibility without corrupting underlying compensation governance.

  
A fundamental transformation occurring between 2024 and 2026 is the shift from static, title-bound job descriptions to dynamic, skills-indexed job profiles. Traditional job architectures struggled to keep pace with rapid technological shifts because static job descriptions age faster than annual review cycles, while skills obsolescence in software and data science can shift market premiums materially within a twelve-month window. Modern implementations attach five to ten explicit priority skills to each Workday Job Profile—integrating external ontologies such as Aon's SkillsGraph, Mercer's Skills Library, or SAP's Talent Intelligence Hub (TIH)—so that machine learning algorithms can infer role adjacency, automate internal talent marketplaces, and trigger skill-validated band progression rather than relying on time-in-role.   
<iframe src="./pay-progression.html" width="100%" height="880" style="border:none; overflow:hidden;"></iframe>

HR Consulting & Compensation Survey Frameworks: Public Availability and Taxonomy Mechanics
A central question in workforce taxonomy research is whether major human resources consulting firms—specifically Aon (Radford), Mercer, Willis Towers Watson (WTW), and Korn Ferry—make their job architecture catalogs and job codes publicly available. Officially, these firms treat their job catalogs and leveling matrices as proprietary intellectual property governed by strict "give-to-get" survey participation agreements and annual enterprise subscriptions ranging from $10,000 to over $40,000 per year. Under this commercial model, participating employers must submit their internal employee compensation records mapped to the provider's job library in order to purchase market data cuts.   

Despite these commercial restrictions, extensive portions of the consulting firms' underlying taxonomies, job code syntaxes, and leveling rubrics are publicly reconstructable through four primary documentary channels. First, transparent, remote-first technology companies such as GitLab and Sourcegraph publish their complete compensation philosophies, leveling rubrics, and exact Radford job code mappings in public GitHub and handbook repositories. Second, United States Department of Labor H-1B Labor Condition Application (LCA) disclosures require employers using private compensation surveys (Non-OES prevailing wage sources) to declare the exact survey name, survey job code, and survey job title on public filings, such as Qualcomm certifying Radford Job Code 5174, Machine Learning Engineer 4. Third, public sector universities (including the University of Washington and Arizona State University) and regulated utilities publish salary survey cross-walks, proxy statements, and Workday career architecture guides to comply with public record mandates. Fourth, academic and public document repositories host full or partial editions of the 2022 Radford GCD Job Family Descriptions, the 2022 Radford GCD Job Leveling Chart, the 2025 RMCD All Modules Job Catalog, the Mercer Job Library (MJL) Job Matching Booklets, and WTW Global Grading System (GGS) user guides.   

Aon Radford (Radford Global Compensation Database & Radford McLagan RMCD)
The Aon Radford framework—historically known as the Radford Global Technology Survey (RGTS) and Radford Global Compensation Database (GCD), and unified into the Radford McLagan Compensation Database (RMCD)—is the dominant benchmarking standard for technology, semiconductor, life sciences, and FinTech companies. While finance roles are frequently benchmarked to Mercer and financial services roles to McLagan or WTW, engineering and technical roles are primarily benchmarked to Radford. The RMCD aggregates validated, non-crowdsourced compensation data from more than 8,700 participating organizations covering over 30 million employees across 115+ countries, including more than 4,900 private venture-backed and private-equity-backed firms.   

Radford utilizes two interconnected job coding conventions across client HRIS platforms. Historically, the Radford Global Technology Survey identified roles via a 4-digit numeric root code where the first three digits denoted the job family and sub-family and the fourth digit denoted the job level (1 through 6 for Individual Contributors). For example, 5174 designates Machine Learning Engineer 4 (Senior/Advanced IC), establishing the 517x series (5171 to 5176) for the Machine Learning Engineering individual contributor track. For clients integrating directly with HRIS platforms, Aon also maintains backward compatibility with a standardized 16-character job code syntax so automated HRIS pipelines do not experience syntax changes during catalog upgrades.   

In the unified Radford Global Compensation Database (GCD) and RMCD catalog, every role is mapped to a structured three-part alphanumeric dot-delimited code formatted as [Function].[Sub-Family].[Track+Level]. The first segment is a two- to four-letter Function Code identifying the macro functional domain, such as EN (Engineering), IT or IN (Information Technology), DEVO (DevOps), HR (Human Resources), BP (Business Process Outsourcing), BC (Broadcast / Media & Gaming), or BS (Business Operations). In the 2025 RMCD catalog, industry modules are additionally categorized by three-letter module codes including LSC (Life Sciences), MFG (Manufacturing), MNG (Mining), MBK (Mortgage Banking), PEQ (Private Equity), and REA (Real Estate). The second segment is a three- to four-letter Job Family/Sub-Family code pinpointing the technical specialization, such as AYDS (Analytics - Data Scientist), GEN (Generalist / Multi-discipline), GLBP (Global Business Partner), or BPBE (Broadcast Production Engineering). The final two characters explicitly define the career track (S for Support, P for Professional Individual Contributor, M for Management, and E for Executive) and the numerical seniority level. Consequently, HR.GLBP.P1 designates a Level 1 Individual Contributor, HR.GLBP.M4 designates a Level 4 Manager (Director), BP.AYDS.M1-6 spans Management levels 1 through 6 for Data Science Analytics, and DEVO.GEN.P7 designates a Level 7 Principal/Fellow DevOps Engineer with 20+ years of experience or equivalent recognition.   

Within the RMCD Private and Global Technology modules, technical roles are separated across Software Engineering/Development, Hardware Engineering/Development, Quality Assurance, and Information Technology. Under the broader Engineering and Technology umbrella, Radford delineates core families for Software Engineer (distinguishing Systems software from Applications software), Hardware Engineer, Data Scientist, Machine Learning Engineer, Cloud Engineer, and Cybersecurity Specialist.   

However, the rapid emergence of generative AI and foundation model engineering between 2023 and 2026 strained traditional survey taxonomies. Aon's North America Artificial Intelligence Study Report (conducted in Q4 2024 and published in February 2025) revealed substantial classification fragmentation when surveying companies on how they reported AI-focused R&D incumbents to the Radford McLagan Compensation Database. With multiple selections permitted, 35% of participating organizations reported AI R&D talent to Machine Learning Engineer / Manager job codes, 31% reported them to general Software Development Engineer / Manager job codes, 11% reported them to Research Scientist / Manager job codes, and 5% reported them to other codes. Because nearly a third of employers were blending AI engineers into baseline Software Development codes—obscuring the 15% to 25% market compensation premium that AI/ML and Cybersecurity job families command above general technology roles—Aon launched dedicated AI enhancements to the Radford McLagan Compensation Database on March 31, 2026. This 2026 release established AI-specific job families and benchmarks explicitly differentiating Machine Learning Engineers, Applied Data and Research Scientists, and AI Engineers, while integrating AI-assisted job matching and Workday SkillsGraph badged connectivity.   

This structural pay divergence is also reflected in modern skills-based compensation band models implemented across the technology sector in 2026, where movement between bands is triggered by verified capability validation rather than tenure. In software engineering, skill-validated base salary bands progress from Band 1 Foundational Engineer ($75,000–$95,000, requiring foundational Python or JavaScript, version control, and basic API integration) and Band 2 Developing Engineer ($95,000–$125,000, requiring two intermediate languages, foundational AWS/GCP/Azure cloud deployment, and CI/CD pipelines) to Band 3 Proficient Engineer ($125,000–$160,000, requiring full-stack proficiency, intermediate cloud architecture, system design, and independent feature ownership), Band 4 Senior Engineer ($160,000–$210,000, requiring distributed systems expertise, advanced cloud architecture, and cross-project technical leadership), and Band 5 Principal Engineer ($210,000–$280,000+, requiring expert architecture design, cross-team technical strategy, and AI/ML integration). By contrast, parallel Data Analytics base salary bands run approximately 15% to 22% lower at each tier, progressing from Band 1 Analyst I ($60,000–$78,000, intermediate SQL and foundational visualization) and Band 2 Analyst II ($78,000–$100,000, intermediate Python/R, Tableau/Power BI proficiency, and A/B testing) to Band 3 Senior Analyst ($100,000–$130,000, foundational ML, intermediate statistical modeling, and dashboard automation), Band 4 Lead Analyst ($130,000–$165,000, intermediate-to-advanced ML and predictive modeling), and Band 5 Principal / Head of Analytics ($165,000–$220,000+, advanced analytics and AI integration).   


Mercer (Mercer Job Library & International Position Evaluation - IPE)
While technology-native firms rely primarily on Radford for engineering benchmarks, global conglomerates, financial services institutions, and corporate finance functions frequently anchor their enterprise-wide job architecture to the Mercer Job Library (MJL) and Mercer International Position Evaluation (IPE) methodology. Serving as the global taxonomy for Mercer's Total Remuneration Surveys (TRS) and Mercer WIN (Workforce Intelligence Network), the Mercer Job Library encompasses over 26,000 standardized positions structured across 30 Job Families, more than 200 Sub-families, and nearly 3,000 Specializations. Complementing the job catalog is the Mercer Skills Library (and workflow tool Skills Map), which maps over 4,000 curated skills—mined from millions of online job descriptions—to over 10,000 MJL jobs, using Mercer Data Connector's AI-driven algorithm to match internal company job titles directly to MJL codes.   

In the Mercer Job Library, every position is defined by two orthogonal dimensions: the Nature of Work (Family, Sub-family, Specialization) and the Hierarchy of Work (Career Stream and Career Level). These two dimensions combine into a standardized 10-character dot-delimited job code formatted as AAA.NN.NNN.SL0. The first segment (AAA) is a three-letter alphabetical Job Family code, such as IT / ITS (IT, Telecom & Internet), ENS (Engineering & Science), SMP (Sales, Marketing & Product Management), FIN (Finance), QLT (Quality Management), or PSK (Production & Skilled Trades). The second segment (NN) is a two-digit numeric Sub-family code denoting the functional division within that family. Within ENS (Engineering & Science), for example, sub-families are numbered 01 (Joint Engineering & Science Technical Leadership), 02 (Technical Product Development / Research Operations), 03 (Engineering), 04 (Engineering Technologists / Technical Professionals), 05 (Engineering Technicians), and 06 (Engineering Design). Within IT, Telecom & Internet, sub-families include Software Product Engineering, Software Engineering, and Application Development. The third segment (NNN) is a three-digit numeric Specialization code pinpointing the exact technical discipline, such as 061 (Electronics Product Design Engineering), Client-End Software Development, or Systems Software Engineering. The fourth segment (SL0) is a three-character Career Stream and Level code combining the stream letter (P for Professional, M for Management, T for Technical/Para-professional, E for Executive) with a two-digit level index, such as P30 (Senior Professional, Level P3) or M40 (Manager, Level M4). Thus, the Mercer code ENS.03.061.P30 uniquely encodes Electronics Product Design Engineering - Senior Professional (P3).   

To link diverse job families into a unified internal grade structure across borders, Mercer's International Position Evaluation (IPE) methodology sizes organizations along three value-chain dimensions—Headcount, Economic Volume, and Complexity—and evaluates every job across five weighted compensable factors: Impact (depth and breadth of organizational influence), Communication (audience and purpose of required communication), Innovation (complexity of problem solving, design, and development), Knowledge (technical skills, people management, and geographic context), and Risk (nature of mental and physical risk exposure). The resulting point total converts into an IPE Class (typically ranging from Class 40 for entry support roles to Class 48–59 for professional software and data scientists, and Class 60–75+ for Directors, VPs, and C-suite executives).   

Willis Towers Watson (WTW Career Map & Global Grading System - GGS)
Willis Towers Watson (WTW), which holds deep market penetration in financial services, professional services, insurance, and global enterprise IT departments, utilizes an integrated leveling architecture that merges its Career Map framework with the Global Grading System (GGS). In WTW's modernized survey taxonomy, the legacy terms "Job Family" and "Subfamily" were replaced by Function (such as Function Code AIT for IT Administration) and Discipline (such as Systems Software Engineering), and WTW job codes are constructed as a combination of Discipline or Executive Benchmark, Career Level, and Global Grade.   

WTW's Career Map organizes the workforce into six distinct Career Bands representing progressive modes of expected contribution, each spanning four to six Career Levels. The Professional Career Band (P1–P6) spans Global Grades GG8–GG17 and governs Software Engineers, Data Scientists, and AI Researchers. The Supervisory/Management Career Band (M1–M5) spans Global Grades GG10–GG17, progressing from M1 Supervisor through M4 Group Manager to M5 Senior Group Manager. Customer-facing technical architects and sales engineers map to the Customer/Client Management and Sales Band (S1–S6), which spans GG8–GG17 (S3 Career, S4 Expert, S5 Senior Expert, S6 Elite Expert). Non-degreed or operational technicians map to the Technical Support Band (T1–T4) spanning GG5–GG10 (T1 Entry, T2 Intermediate, T3 Senior, T4 Lead/Advanced), while administrative and production roles map to Business Support (U1–U4, GG4–GG9) and Production/Operations (W1–W4, GG2–GG7). Crucially, while WTW survey submissions in North America match primarily to Career Levels (P1–P6, M1–M5), international survey participants and global leveling architectures rely on Global Grades (GG1–GG20+) to account for company size—determined by selecting the lower of two Global Grade breakpoints for organizational Revenue and FTE headcount—at senior and executive levels.   

Korn Ferry (Hay Group) and Next-Generation Real-Time Platforms
Korn Ferry (incorporating the legacy Hay Group methodology) remains widely deployed in traditional banking (such as Goldman Sachs) and industrial organizations. The Hay method evaluates roles across Know-How, Problem Solving, and Accountability to assign Hay Points and Reference Levels, which are frequently operationalized through Job Family Modeling. In a standard 10-level Hay IT Job Family Model—spanning tracks such as Systems Operations, Technology Engineering, Applications, End User Services, Business Analysis, and Solutions/Project Management—any position matching 80% or more of the benchmark descriptors is slotted into Levels 1 through 10 (e.g., Level 4–5 Associate Analyst/Specialist, Level 6 Technology Analyst/Specialist, Level 7 Senior Applications/Technology Analyst, Level 8 Product Architect Level 3 / Senior Systems Analyst / Team Lead, Level 9 Technical/Systems Architect or Senior Manager, and Level 10 Director).   

Because legacy consulting surveys require labor-intensive annual manual job matching and charge separately for regional country modules, high-growth technology and FinTech firms increasingly supplement or replace them with real-time, HRIS-integrated compensation platforms. Platforms such as Pave (dominant in US venture-backed startups) and Ravio (strong in European and global tech, with 1,600+ contributing companies across 50+ countries and 300+ roles) connect directly via API to client HRIS platforms to ingest live base salary, variable pay, and equity data. Rather than forcing HR teams to re-match hundreds of job codes every year, Ravio maps a company's roles once during onboarding to a unified level framework. Concurrently, specialized tech surveys like Culpepper ($3,000–$15,000 annually) provide quarterly and semi-annual peer-group benchmarks for mid-market software and SaaS firms, while job architecture governance platforms like Compensation IQ and CompBldr provide pre-mapped translation matrices across 30+ external frameworks—linking Mercer IPE, Korn Ferry Hay, WTW GGS, Radford McLagan, Culpepper, Figures, Pave, Ravio, and Workday Job Profiles in a single platform.   

Cross-Framework Leveling and Grade Equivalency Matrix
To demonstrate how these consulting frameworks align with internal corporate grading systems, the table below maps the full Individual Contributor (P) and Management (M) spectrum across Radford, WTW, Mercer, Korn Ferry Hay, and open-source tech implementations.   

Standardized Seniority Tier	Aon Radford (GCD / RMCD) Level & Code Suffix	WTW Career Map Level & Global Grade (GG)	Mercer Job Library (MJL) & IPE Class	Korn Ferry Hay Family Model Level	Public Tech Handbook Alignment (Sourcegraph / GitLab)	Defining Scope, Autonomy & Technical Impact
Entry / New Grad IC	
P1 (Entry / Developing) ...P1

[cite: 20, 67]

P1 Entry (GG8–GG9)

P10 (Entry Professional) IPE 46–47

Level 4–5 (Associate Analyst / Specialist)

IC1 / Associate Engineer

Performs routine assignments with limited discretion to vary from established procedures; requires BS/MS degree or equivalent.

Intermediate / Mid-Level IC	
P2 (Developing / Proficient) ...P2

[cite: 67, 70]

P2 Intermediate (GG10)

P20 (Experienced Professional) IPE 48–50

Level 6 (Analyst / Technology Specialist)

IC2 / Intermediate Engineer

Working knowledge in own discipline; completes straightforward engineering or analytical tasks with moderate guidance.

Career / Experienced IC	
P3 (Career) ...P3

[cite: 67, 70]

P3 Career (GG11–GG12)

P30 (Senior Professional) IPE 51–53

Level 7 (Senior Analyst / Systems Analyst)

IC3 / Senior Engineer (Early Band)

In-depth knowledge in own discipline and basic knowledge of related fields; independently owns features and services.

Senior / Advanced IC	
P4 (Advanced) ...P4 (e.g., 5174)

P4 Specialist (GG13–GG14)

P40 (Lead / Specialist) IPE 54–56

Level 8 (Product Architect L3 / Team Lead)

IC4 / Senior Software Engineer

Recognized internal expert in own area; solves complex distributed systems or ML problems; leads functional project teams.

Staff / Expert IC	
P5 (Expert) ...P5

[cite: 42, 67]

P5 Master (GG15)

P50 (Principal / Guru) IPE 57–59

Level 9 (Technical / Systems Architect)

IC5 / Staff Engineer

Solves unique, multi-team problems with broad business impact; anticipates internal/external architectural challenges.

Principal IC	
P6 (Principal) ...P6

[cite: 42, 67]

P6 Renowned Expert (GG16–GG17)

P60 (Fellow / Senior Principal) IPE 60–62

Level 10 (Senior Technical Architect)

IC6 / Principal Engineer

Recognized external thought leader; shapes multi-year enterprise technical and AI strategy across large global organizations.

Distinguished / Fellow IC	
P7 (Fellow / 20+ yrs) ...P7 (e.g., DEVO.GEN.P7)

GG18+ (Executive Technical Equivalence)

E1–E2 Technical Equivalent IPE 63+

Executive Technical Fellow

Distinguished Engineer / Engineering Fellow (VP Equiv.)

Individual contributor equivalent to VP of Engineering; defines industry-wide standards and frontier architectures.

Supervisor / Team Lead	
M1 (Supervisor) ...M1

[cite: 23, 42]

M1 Supervisor (GG10–GG11)

M10 (Team Leader) IPE 50–52

Level 7–8 (Supervisor / Team Lead)

Associate Manager

Provides immediate supervision to a unit; assigns tasks and monitors schedules while performing hands-on work.

Manager	
M2 (Manager) ...M2

[cite: 42, 52]

M2 Manager (GG12–GG13)

M20 (Manager) IPE 53–55

Level 8–9 (Manager)

M3 (Engineering Manager)

Directs a single discipline or engineering squad; holds full performance review, pay review, and hire/fire authority.

Senior Manager / Assoc. Director	
M3 (Sr. Manager) ...M3

[cite: 20, 42]

M3 Senior Manager (GG14)

M30 (Senior Manager) IPE 56–58

Level 9 (Senior Manager / Program Mgr)

M4 (Senior Engineering Manager)

Manages two or more disciplines or multiple sections through subordinate supervisors or senior ICs.

Director	
M4 (Director) ...M4

[cite: 20, 42]

M4 Group Manager (GG15)

M40 (Director) IPE 59–61

Level 10 (Director)

M5 (Director of Engineering)

Directs a functional area or multiple departments through subordinate managers; translates strategy into operational plans.

Senior Director / VP	
M5–M6 / E1–E5 (Sr. Director to CEO)

M5 Sr. Group Mgr (GG16–GG17) / Exec GG18+

[cite: 22, 24]

M50 / E1–E3 (E2S Subsidiary, E2D Division)

Executive Band

M6 (Sr. Director / VP of Development)

Leads major functional areas or multi-profit-center divisions through subordinate directors; sets corporate policy.

  
Career Site Faceted Search and ATS Metadata Exposure
Company career portals frequently expose internal job architecture metadata through their user interface filters (faceted search), URL routing structures, and underlying API responses. However, the granularity of exposed metadata depends directly on the Applicant Tracking System (ATS) or HCM recruiting module powering the portal.   

Workday Recruiting (myworkdayjobs.com) is the most widely deployed enterprise HRIS among Fortune 500 technology, semiconductor, and financial services firms, powering the career portals of NVIDIA, Salesforce, Adobe, Netflix, Workday, JPMorgan Chase, Morgan Stanley, Citigroup, Bank of America, and Capital One. When a candidate searches a Workday-hosted career site, the browser queries Workday's Candidate Experience Service (wday/cxs/<tenant>/<site>/jobs), such as /wday/cxs/nvidia/NVIDIAExternalCareerSite/job/US.... Workday's JSON API schema explicitly exposes jobFamilyGroup (and optionally jobFamily) inside the facets array of the search payload, which renders on the career site sidebar as "Job Category," "Job Family," or "Department". Although Workday restricts internal Job Profile names and Management Level hierarchies from external display by default, two common implementation patterns leak this internal architecture. First, when recruiters generate a requisition in Workday without manually overriding the URL slug, Workday concatenates the internal Job Profile, corporate officer grade, working title, and requisition ID directly into the public URL—as seen in Morgan Stanley's URL .../job/Bengaluru-India/Lead-Software-Eng--Vice-President--Software-Engineer_PT-JR043381, which reveals that the internal Job Profile is Lead Software Eng, the corporate officer rank is Vice President, and the job family is Software Engineer. Second, Workday job requisition templates frequently inject {Job Family Description based on Job Profile} or internal grade band descriptors directly into the footer of the job posting to satisfy statutory pay transparency requirements.   

Hyperscalers operating proprietary career portals expose even richer slices of their internal talent taxonomy. Amazon's custom portal (amazon.jobs) exposes 26 standardized JOB CATEGORY facets that mirror its internal job families, explicitly separating Software Development, Data Science, Applied Science, and Project/Program/Product Management--Technical from Project/Program/Product Management--Non-Tech. Furthermore, Amazon's requisition titles systematically append internal sub-organization codes—such as MADS (Measurement, Ad Tech, and Data Science), D:SE (AWS Marketing, Data Science & Engineering), OCM (Omnichannel Metrics), and Amazon Leo Data Science Platform. Meta's custom portal (metacareers.com) utilizes a two-tier Teams and Sub-teams facet system paired with role tags displayed beneath the job title (Engineering, Software Engineering, Data Engineering, Data Science, Analytics), while parenthetical title suffixes expose both functional specialization and internal AI org structures, such as Data Engineer, Analytics (Ranking, AI), Data Engineer, Analytics (Technical Leadership) (indicating IC6+ Staff/Principal scope), and Data Engineer, Meta Superintelligence Labs within the Products & Applied Research (PAR) team. Alphabet's portal (careers.google.com) exposes a strict three-part title syntax—[Level Prefix + Base Role], [Technical Specialization], [Product Area / Division] (e.g., Senior Staff Software Engineer, Unified Traffic Engineering, Infrastructure or Evals Engineer, Polaris, DeepMind)—alongside a visual seniority badge (bar_chartMid for L3–L4 and bar_chartAdvanced for L5–L7).   

In contrast, high-growth SaaS and frontier AI labs utilizing Greenhouse (boards.greenhouse.io), Ashby (jobs.ashbyhq.com), or Lever (jobs.lever.co) expose a customizable Department or Team facet. At frontier AI labs like Anthropic and OpenAI, these facets bypass traditional HR job families altogether and instead expose exact research pods and mission teams—such as RL, RL Engineering, RL Velocity, Domain RL (Code, Chip Design, Cybersecurity, Computer Use), Pre-training and Scaling, Post-training and Evaluations, Interpretability, Alignment Science, Safeguards and Biological Safety, and Discovery and Life Sciences. Meanwhile, enterprises deploying Talent Intelligence portals such as Eightfold AI or Phenom People (including Microsoft, NVIDIA, Cisco, and American Express) parse candidate resumes against internal skills taxonomies and expose Profession (Macro Family) and Discipline (Sub-family) facets directly in the search interface.   

Detailed Review of the Top 20 Technology Companies
To provide a granular architectural reference, this section examines the Top 20 Technology Companies, mapping how each organization classifies its Software, Data, and AI talent across job families and functional tracks, internal job codes and grade levels, and standardized individual contributor and management job titles.

Summary Comparison of the Top 20 Technology Companies
Rank & Company	Primary Career Portal / HRIS Stack	Exposed Career Site Facets (Software, Data & AI)	Core Technical Job Families & Tracks	IC Grade Scale (Entry to Fellow)	Management Grade Scale (Mgr to VP)	Distinct AI / Data Classification Nuance
1. Alphabet (Google)	Custom (careers.google.com) + Workday	
Category + Experience Badge (Mid, Advanced)

SWE, SRE, Research Scientist, Data Scientist, Developer Relations, Forward Deployed Eng

L3 to L11 (Senior Fellow)	L5 (M1 TLM) to L10 (SVP)	
Distinguishes Software Developer, AI/ML GenAI (Cloud), Research Scientist, and DeepMind Evals Engineer.

2. Amazon	Custom (amazon.jobs) + PeopleSoft/Internal	
26 JOB CATEGORY filters (Software Development, Data Science, Applied Science)

SDE, SysDE, Data Engineer, Data Scientist, Applied Scientist, Research Scientist, BIE

L4 to L10 (Distinguished)	L5 (M1) to L10 (VP)	
Applied Scientist requires both PhD/MS ML theory and production SDE coding bar; highest pay multiplier.

3. Meta Platforms	Custom (metacareers.com) + Workday	
Teams & Role Tags (Engineering, Data Engineering, Analytics, Data Science)

SWE (General / ML), Production Eng, Data Eng (Analytics), Data Scientist (Product), Research Scientist

E3 (IC3) to E9 (IC9)	M1 (E6 equiv) to D2 / VP	
Reorganized frontier AI under Meta Superintelligence Labs and Products & Applied Research (PAR).

4. Apple	Custom (jobs.apple.com) + Workday	Teams and Sub-Teams (Software and Services, Machine Learning and AI)	
Software Engineering (Apps/Systems), ML Engineer, ML Researcher, Data Science & Analytics

ICT2 to ICT6 + Fellow

M1 to M5 (Sr. Director / VP)	
Unified ICT (Individual Contributor Technical) scale (ICT2–ICT6) governs SWE, Hardware, and ML.

5. Microsoft	Eightfold / Custom + SAP/SuccessFactors	Profession (Engineering, Research) & Discipline (Software Engineering, Data & Applied Science)	Software Engineering, Data & Applied Science, Research Sciences, Technical Program Mgmt, Product Mgmt	L59 to L80 (Technical Fellow)	M1 (L63–64) to CVP (L70+)	Merges Data Science and ML Engineering into a single Data & Applied Scientist discipline across two-level bands.
6. NVIDIA	
Workday (wday/cxs/nvidia) + Eightfold

jobFamilyGroup: Engineering - Software, Engineering - Hardware, Research

[cite: 75]

System Software, GPU Architecture, Deep Learning / AI Eng, Autonomous Vehicles, Applied Research	IC1 to IC9 (Fellow)	M2 to M7+ (VP/SVP)	
Heavily weights systems/kernel SWE (CUDA, TensorRT) inside the Engineering - Software family.

7. OpenAI	Ashby (openai.com/careers) + Workday	
Team/Org Facets (Research, Applied AI, Safety Systems, Scaling)

Member of Technical Staff (MTS), Applied AI Engineer, Software Engineer, Research Scientist

L2 to L7+ (Flat MTS Title)	Eng Manager / Research Lead to VP	
Shifted from PPUs (Profit Participation Units) to RSUs with no vesting cliff in Jan 2026; uses unified MTS title.

8. Anthropic	Greenhouse + Workday	
Research Pod Facets (RL, Pretraining, Interpretability, Alignment Science)

Research Engineer, Research Scientist, AI Engineer, Security / Safeguards Engineer

Flat MTS (Internal L3–L7 calib.)	Team Lead to Head of Function	
Organizes hiring around 8 specialized RL, Scaling, and Safety pods requiring strong SWE + PyTorch/JAX.

9. Netflix	Workday + Eightfold (jobs.netflix.com)	Teams (Core Engineering, Data & Insights, Machine Learning)	Software Engineer, Data Engineer, Analytics Engineer, Machine Learning Scientist/Engineer	Single Band (Senior SWE) or L3–L7 (2024–26)	Manager, Director, VP	Introduced calibrated L3–L7 leveling across SWE and Data Engineering to govern market-top all-cash bands.
10. Salesforce	Workday (myworkdayjobs.com)	Job Category: Software Engineering, Data Science & Analytics, AI Research	MTS (SWE), SMTS, LMTS, PMTS, Architect, AI Research Scientist, Data Scientist	Grade 5 (AMTS) to Grade 12+ (Chief Architect)	Grade 8 (Mgr) to Grade 12+ (SVP)	Uses classic Silicon Valley academic titles (AMTS, MTS, SMTS, LMTS, PMTS) mapped to numeric grades.
11. Oracle	
Oracle HCM Cloud (careers.oracle.com)

Job Category: Software Development, Product Development, Information Technology	Applications Developer, Systems/Cloud Developer (OCI), Principal/Consulting MTS, Data Scientist	IC1 to IC6 (Architect / Fellow)	M1 to M6 (VP)	Uses Consulting Member of Technical Staff (IC5) between Principal (IC4) and Architect (IC6).
12. Adobe	Workday (myworkdayjobs.com)	Category: Engineering & Product, Data Science & Machine Learning, Research	Computer Scientist (SWE), Machine Learning Engineer, Research Scientist, Data Engineer	P10 (CS1) to P80 (Fellow)	M30 (Mgr) to E-Band (VP)	Historic title for Software Engineer is Computer Scientist (CS1–CS2, Sr. CS1–CS2, Principal Scientist).
13. IBM	Custom / BrassRing / Workday	
Category: Software Engineering, Data & Analytics, Research, Client Engineering

[cite: 91]

Software Developer, Data Scientist, AI Engineer (watsonx), Research Staff Member (RSM), Client Eng

Band 6 to Band 10 + Band D/C (DE/Fellow)	Band 7–10 to Executive Band D–A	
Features dual innovation honors: Distinguished Engineer (Band D), IBM Fellow, and Master Inventor.

14. Cisco Systems	Phenom + Workday	Area of Interest: Engineer - Software, Data & Analytics, AI/ML	Software Engineer, Network/Embedded SWE, Machine Learning Engineer, Data Scientist	Grade 4 to Grade 13 (Fellow)	Grade 10 (Mgr) to VP	Uses even numbers primarily (Grade 4, 6, 8, 10, 11, 12, 13) for core SWE progression.
15. ServiceNow	
SmartRecruiters + ServiceNow HRSD

Category: Engineering, Cloud Operations, AI & Data, Product	
Software Engineer, Machine Learning Engineer, AI Research Scientist, Site Reliability Engineer

IC1 to IC7 (Distinguished)

M1 to M6 (VP)	
Dogfoods its own Talent Development Core (sn_skills_int_job_level) to map Role Groups and Specialties.

16. Workday	
Workday (myworkdayjobs.com)

Job Family Group: Product & Technology, Engineering

[cite: 8, 93]

Software Application Eng, Systems Eng, ML Engineer, Data Scientist, Product Management	
P1 to P6 + Fellow (P7)

M1 to M6 (VP)

Reference implementation of Job Family Group -> Job Family -> Job Profile with ML seniority matching.

17. GitLab	
Greenhouse + Public Handbook

Department: Engineering, Product, Security, Enterprise Data

[cite: 69, 94, 95]

Backend, Frontend, Fullstack, Infra/SRE, ML Eng, Data Scientist, Analytics Engineer, AI Security

Grade 5 (Assoc) to 11 (Fellow)

Grade 8 (EM) to 12 (VP)

Completed early-2026 job re-architecture; added Analytics Engineer and AI Security job families.

18. Palantir	Lever + Workday	
Team: Software Engineering, Forward Deployed Software Engineering, Product

[cite: 96]

Software Engineer (Core Product), Forward Deployed Software Engineer (FDSE / Delta), AI/ML Eng

Flat Title (Internal L1–L5 Tenure/Impact)	Lead / Group Lead	
Pioneered the Forward Deployed Software Engineer (FDSE) family, now adopted by Google and OpenAI.

19. Uber	iCIMS / Custom + Workday	Team: Engineering -> Backend, Data, Machine Learning, Mobile	Software Engineer, Systems Engineer, Applied Scientist, Data Scientist, Data Engineer	L3 (SWE I) to L8 (Uber Fellow)	L5a (EM I) to L8+ (VP)	Splits L5 into L5a (Senior SWE I) and L5b (Senior SWE II) as a bridge to L6 Staff SWE.
20. Databricks	Greenhouse + Workday	Department: Engineering, Mosaic Research, Field Engineering, Product	Software Engineer (Distributed Systems), Research Scientist (Mosaic AI), Solutions Architect	L3 to L8 (Distinguished)	M3 (L5 equiv) to VP	Isolates frontier LLM pre-training under Mosaic Research while core DB engine sits in Engineering.
  
In-Depth Architectural Reviews of the Top 20 Technology Companies
1. Alphabet (Google & Google DeepMind)
Alphabet's career portal categorizes technical talent across distinct functional ladders, notably Software Engineering (SWE), Site Reliability Engineering (SRE) (bifurcated into SWE-SRE and Systems-SRE), Research Scientist, Data Scientist (historically titled Quantitative Analyst), Machine Learning Engineer, and customer-facing technical families including Forward Deployed Engineering and Cloud Learning Services. Requisitions in 2026 reflect specialized generative AI sub-families and external titles, such as Senior Software Developer, AI/ML GenAI, Google Cloud AI, Staff Forward Deployed Engineer, GenAI, Google Cloud, AI Outcome Engineer, Forward Deployed Engineering, Senior AI Solution Builder, and within Google DeepMind, Evals Engineer, Polaris, DeepMind. Hardware and custom silicon AI roles are classified under RTL Design Engineer, Machine Learning Accelerators.   

Internally, Google's technical leveling scale runs from L3 (Entry SWE II / New Grad) through L11 (Senior Google Fellow). On external job postings, Google exposes a visual experience indicator where Mid (bar_chartMid) corresponds to L3–L4, Advanced (bar_chartAdvanced) corresponds to L5–L7, and Director+ corresponds to L8+. Along the Individual Contributor track, titles progress from Software Engineer II (L3) and Software Engineer III (L4) to Senior Software Engineer (L5) (often paired with a Tech Lead role designation, such as Senior Software Engineer, Tech Lead, Android Studio), Staff Software Engineer (L6), Senior Staff Software Engineer (L7), Principal Engineer (L8), Distinguished Engineer (L9), Google Fellow (L10), and Senior Google Fellow (L11). People management begins at L5 as a Tech Lead Manager (TLM) or formally at L6 (M1, Software Engineering Manager, e.g., Software Engineering Manager, YouTube Ads Machine Learning), advancing to L7 (M2, Senior Software Engineering Manager, e.g., Senior Software Engineering Manager, Google Cloud Storage Semantic Search), L8 (M3, Director of Engineering), L9 (Senior Director), and L10 (Vice President).   

2. Amazon (Amazon.com, AWS, & Amazon Leo)
Amazon operates one of the most structured and transparent job family architectures in the global technology sector, exposed directly via 26 JOB CATEGORY filters on amazon.jobs. Amazon strictly separates software, data, and science roles into distinct job families with independent interview loops and compensation multipliers. The Software Development (SDE) family governs engineers building distributed systems, cloud-native microservices, APIs, and embedded RTOS firmware—with requisitions frequently appending internal business unit acronyms such as Software Development Engineer, AWS Data Services, Software Development Engineer, AWS Analytics Engineering (focusing on multi-agent AI systems and autonomous agent orchestration), Software Development Engineer, Leo Data Science Platform, Software Development Engineer, AWS Marketing, Data Science & Engineering (D:SE), and Software Development Engineer, Measurement, Ad Tech, and Data Science (MADS).   

In the data and AI domains, Amazon distinguishes four specialized families. Applied Science (AS) is Amazon's highest-compensated AI/ML family (e.g., Senior Applied Scientist, Amazon Leo Data Science Platform), requiring candidates to pass both a graduate-level machine learning theory loop (deep learning, multi-modal learning, numerical optimization) and the production SDE coding bar. Data Science (DS) focuses on statistical inference, experimental design, sampling methodology, and large-scale predictive modeling in Python, R, and SQL (e.g., Data Science Manager, Procurement). Data Engineering (DE) and Business Intelligence (BIE) govern petabyte-scale data platform pipelines (Spark, AWS services) and enterprise metrics reporting (SQL, Tableau, Excel VBA), respectively. Across all families, Amazon applies a universal L1–L12 grading system (omitting L9). Salaried technical IC roles begin at L4 (Software Development Engineer I / Software Engineer I / Data Scientist I), advancing to L5 (SDE II / Applied Scientist II), L6 (Senior SDE / Senior Applied Scientist / Software Development Manager / Data Science Manager), L7 (Principal SDE / Principal Applied Scientist / Senior SDM), L8 (Senior Principal SDE / Director), and L10 (Distinguished Engineer / Vice President).   

3. Meta Platforms (Core Family of Apps & Meta Superintelligence Labs)
Meta classifies technical talent into four primary pillars visible on metacareers.com. The Software Engineering (SWE) pillar encompasses both general systems/product engineers and specialized Machine Learning SWEs who architect recommendation systems—such as the Ranking AI organization within Meta's Monetization group. The Data Engineering (DE) pillar sits under the Analytics and Data Engineering tags (Data Engineer, Analytics and Data Engineer, Product Analytics), requiring Python/C++/Scala, custom ETL design, dimensional schema modeling, and cross-functional product influence across Facebook, Instagram, Messenger, WhatsApp, Reality Labs, and Threads. The Data Science (DS) pillar operates through centralized and embedded product analytics teams (Data Scientist, Product Analytics) that establish analytical standards and drive experimentation. For frontier AI, Meta consolidated its breakthrough product-focused research in 2025–2026 under Meta Superintelligence Labs and the Products & Applied Research (PAR) team alongside Fundamental AI Research (FAIR), employing specialized Research Scientists, AI Engineers, and Data Engineers.   

To preserve a flat organizational culture, Meta omits seniority prefixes ("Senior", "Staff", "Principal") from external IC job titles, instead using parenthetical scope modifiers such as Data Engineer, Analytics (Technical Leadership) to signal Staff/Principal-level requisitions requiring 12+ years of experience. Internally, all technical ICs are graded on the E3 to E9 (or IC3 to IC9) scale: E3 (Entry), E4 (Mid-level, requiring 4+ years of experience or 2+ years with a PhD), E5 (Senior/Career anchor level, requiring 7+ years of experience), E6 (Staff / Technical Leadership, requiring 12+ years of experience), E7 (Senior Staff), E8 (Principal), and E9 (Distinguished). Engineering and Data Science Management tracks run from M1 (Software Engineering Manager / Data Science Manager, equivalent in band to E6) and M2 (Senior Manager, managing multiple teams and subordinate managers) to D1 (Director), D2 (Senior Director), and VP.   

4. Apple
Apple structures its career portal around functional Teams and Sub-Teams, primarily Software and Services (OS, iOS, Cloud Infrastructure, Applications), Machine Learning and AI (Core ML, Natural Language, Computer Vision, Foundation Models), and Hardware (Silicon and SoC Architecture). Within these teams, roles map to Software Engineer, Machine Learning Engineer, Machine Learning Researcher, and Data Scientist. Internally, Apple applies a unified ICT (Individual Contributor Technical) grading scale ranging from ICT2 to ICT6 across all software, hardware, data, and machine learning roles. ICT2 represents entry-level engineers (0–2 years of experience), while ICT3 encompasses mid-level Software Engineers, Machine Learning Engineers, and ML Researchers (typically 2–5 years of experience, subdivided internally into low, mid, and "high ICT3" offer bands). Senior Software Engineers and Senior Machine Learning Engineers sit at ICT4 and above, with ICT5 serving as Apple's Staff/Principal equivalent and ICT6 serving as its Distinguished Engineer equivalent below Apple Fellow. Management tracks run from M1 (Engineering Manager) and M2 (Senior Engineering Manager) to M3 (Director), M4 (Senior Director), and M5 / VP.   

5. Microsoft
Microsoft organizes its global job architecture into Professions (Job Family Groups), Disciplines (Job Families), and Roles (Specializations). Within the Engineering Profession, the two primary technical disciplines are Software Engineering and Data & Applied Science, alongside Product Management and Technical Program Management, whereas foundational AI exploration in Microsoft Research sits under the Research Profession (Research Sciences discipline). Rather than separating Data Scientists and Machine Learning Engineers into competing families, Microsoft merged them into the unified Data & Applied Scientist discipline. Internally, Microsoft uses a granular numeric leveling system from L59 to L80, where every standard IC title spans two numerical grades to allow internal promotion and compensation progression without a title change: L59–L60 (Software Engineer / Data & Applied Scientist), L61–L62 (Software Engineer II / Data & Applied Scientist II), L63–L64 (Senior Software Engineer / Senior Data & Applied Scientist / M1 Engineering Manager), L65–L66 (Principal Software Engineer / Principal Data & Applied Scientist / M2 Principal Group Engineering Manager), L67 (Partner Software Architect / Partner Director of Engineering), L68–L69 (Distinguished Engineer / General Manager), L70 (Corporate Vice President), and L80 (Technical Fellow).

6. NVIDIA
Operating on Workday (wday/cxs/nvidia/NVIDIAExternalCareerSite) paired with an Eightfold AI frontend, NVIDIA exposes jobFamilyGroup facets including Engineering - Software, Engineering - Hardware, Research, and Information Technology. Because NVIDIA's AI platform (CUDA, cuDNN, TensorRT, NeMo) is tightly integrated with GPU silicon architecture, a large share of its AI workforce is classified within Engineering - Software as System Software Engineer, Deep Learning Software Engineer, Math Libraries / Compiler Engineer, or Autonomous Vehicles Software Engineer, while foundational model researchers sit in Research as Applied Research Scientist. Internally, NVIDIA utilizes an IC1 to IC9 Individual Contributor track and M2 to M7+ Management track in Workday, progressing from IC1 (Junior Engineer / New College Grad), IC2 (Software Engineer), IC3 (Senior Software Engineer), and IC4 (Senior Software Engineer II / Lead) to IC5 (Principal Software Engineer), IC6 (Senior Principal Engineer), IC7 (Distinguished Engineer), and IC8–IC9 (Senior Distinguished Engineer / NVIDIA Fellow).   

7. OpenAI
OpenAI classifies its technical workforce across three primary operational domains on its Ashby career portal: Research (Pre-training, Post-training, Reinforcement Learning, Reasoning, Multimodal), Applied AI (ChatGPT, API Platform, Enterprise Products, Forward Deployed AI Engineering), and Safety & Alignment. To prevent status silos between distributed systems engineers and machine learning researchers, OpenAI classifies virtually all technical ICs in Research and Core Engineering under the single unified title Member of Technical Staff (MTS), while product-facing roles use Software Engineer, Applied AI or AI Engineer. Internally, compensation and scope are calibrated across L2 to L7+ (L3 Mid, L4 Senior, L5 Staff, L6 Principal, L7 Distinguished). In a major total rewards shift effective January 2026, OpenAI transitioned its equity compensation model from Profit Participation Units (PPUs—a variant of Profit Interest Units vesting over four years) to Restricted Stock Units (RSUs) and eliminated its equity vesting cliff for new offers.   

8. Anthropic
Anthropic's Greenhouse career portal organizes technical hiring directly into specialized research and engineering pods rather than broad HR job families. Analysis of Anthropic's technical requisitions shows roles clustered into eight core teams: RL, RL Engineering, RL Velocity (10 roles), Domain RL (Code, Chip Design, Cybersecurity, Computer Use, Vision, Knowledge) (7 roles), Pre-training and Scaling (5 roles), Safety (Interpretability, Alignment Science, Safeguards and Biological Safety) (5 roles), Post-training and Evaluations (3 roles), and Discovery and Life Sciences. Like OpenAI, Anthropic uses flat external titles—primarily Research Engineer, Research Scientist, AI Engineer, and Member of Technical Staff—while evaluating all technical candidates on a unified software engineering and ML bar emphasizing CodeSignal assessments, PyTorch, JAX, Kubernetes, Rust, C++, Go, and collaborative pair programming ("balance research exploration with engineering implementation"). Internally, offers are slotted into calibrated compensation bands (L3 through L7).   

9. Netflix
Netflix's Workday and Eightfold career portal categorizes technical talent into Core Engineering (Cloud Platform, Media Encoding, UI, Client/Device Ecosystems), Data & Insights (Data Engineering, Analytics Engineering, Data Science), and Machine Learning (Personalization, Ads ML, Media Algorithms). While Netflix historically classified all experienced individual contributors under a single flat Senior Software Engineer title with top-of-market all-cash compensation, the organization rolled out a calibrated L3 to L7 leveling architecture between 2024 and 2026 to govern early-career pipelines and global engineering hubs: L3 (Software Engineer L3 / New Grad), L4 (Software Engineer L4), L5 (Senior Software Engineer / Senior Data Engineer), L6 (Staff Software Engineer / Staff ML Engineer), and L7 (Principal Software Engineer).

10. Salesforce
Salesforce's Workday portal exposes Software Engineering, Data Science & Analytics, AI Research (Salesforce AI Research / Agentforce), and Security. Internally, Salesforce maps its engineering hierarchy to numeric Workday grades (Grade 5 to Grade 12+) paired with classic Bell Labs academic titles: Grade 5 (Associate Member of Technical Staff - AMTS), Grade 6 (Member of Technical Staff - MTS), Grade 7 (Senior Member of Technical Staff - SMTS), Grade 8 (Lead Member of Technical Staff - LMTS / Software Engineering Manager), Grade 9 (Principal Member of Technical Staff - PMTS / Senior Engineering Manager), Grade 10 (Architect / Principal Architect / Director of Engineering), and Grade 11–12 (Senior Principal Architect / Distinguished Architect / SVP).

11. Oracle
Operating on its own Oracle HCM Cloud global career framework, Oracle categorizes technical roles under Software Development (Oracle Cloud Infrastructure - OCI, Database Kernel, Fusion Applications), Information Technology, and Applied AI / Data Science. Oracle uses a standardized IC1 to IC6 and M1 to M6 taxonomy featuring a distinctive IC5 title: IC1 (Software Developer 1 / Associate), IC2 (Software Developer 2), IC3 (Senior Software Developer / Senior Data Scientist), IC4 (Principal Software Developer / Principal Member of Technical Staff), IC5 (Consulting Member of Technical Staff, equivalent to Staff/Senior Principal Engineer), and IC6 (Software Architect / Distinguished Engineer).   

12. Adobe
On Workday, Adobe categorizes technical talent into Engineering & Product, Data Science & Machine Learning (Firefly / GenAI), and Adobe Research. Adobe uses Mercer and Radford-aligned P (Professional) and M (Management) 2-digit codes (P10 to P80 and M30 to M60) and uniquely retains Computer Scientist as its core internal and external Software Engineering title, progressing from P10 (Computer Scientist 1 - CS1) and P20 (Computer Scientist 2 - CS2) to P30 (Senior Computer Scientist 1 - Sr. CS1 / Machine Learning Engineer 3), P40 (Senior Computer Scientist 2 - Sr. CS2 / Senior Machine Learning Engineer), P50 (Principal Scientist / Principal ML Engineer), P60 (Senior Principal Scientist), and P70–P80 (Adobe Fellow).

13. IBM
IBM classifies technical roles into Software Engineering, Data & Analytics, IBM Research, and Client Engineering (rapid co-creation squads building watsonx AI solutions for enterprise clients). Internally, IBM uses numeric Bands (Band 6 to Band 10) followed by lettered Executive Bands (Band D, Band C, Band B, Band A). Individual contributors progress from Band 6 (Software Developer / Data Scientist), Band 7 (Advisory Software Engineer / Advisory Data Scientist), and Band 8 (Senior Software Engineer / Senior Data Scientist) to Band 9 (Staff / Senior Technical Staff Member - Entry), Band 10 (Senior Technical Staff Member - STSM / Research Staff Member), Band D (Distinguished Engineer - DE, often paired with the patent recognition title Master Inventor), and Band C / Corporate (IBM Fellow).   

14. Cisco Systems
Cisco's Phenom and Workday career portal exposes Engineer - Software (Networking, Silicon One, Security/Splunk), Data & Analytics, and AI/ML. Internally, Cisco uses numeric Job Grades (Grade 4 through Grade 13+), primarily incrementing by even numbers across the early-to-senior levels before shifting to single increments at the executive technical tiers: Grade 4 (Software Engineer I), Grade 6 (Software Engineer II), Grade 8 (Software Engineer III), Grade 10 (Software Engineer IV / Technical Leader I / Engineering Manager), Grade 11 (Technical Leader II), Grade 12 (Principal Engineer), and Grade 13 (Distinguished Engineer / Cisco Fellow).

15. ServiceNow
ServiceNow utilizes SmartRecruiters for job creation and distribution alongside its own ServiceNow Talent Development Core module internally. Within Talent Development Core, technical positions are organized into Role Groups (e.g., Software Engineer, Machine Learning Engineer, Project Manager) and Role Specialties (such as Now Assist GenAI, Agentic Workflows, and Skill Sensing). As documented in ServiceNow's official sn_skills_int_job_level database table schema, ServiceNow levels Individual Contributors from IC1 to IC7 (IC1 Associate SWE, IC2 SWE, IC3 Senior SWE, IC4 Staff SWE, IC5 Senior Staff SWE, IC6 Principal SWE, IC7 Distinguished SWE) and Managers from M1 to M6.   

16. Workday
Serving as the reference implementation of its own Job Architecture Hub, Workday classifies technical roles under the Product & Technology Job Family Group, subdivided into Job Families for Software Application Engineering, Systems & Infrastructure Engineering, Machine Learning & Data Science, and Quality Assurance. Workday maps its internal Job Profiles directly to the Radford P1–P6 (plus P7 Fellow) and M1–M6 scale (P1 Associate Application Developer, P2 Application Developer, P3 Senior Application Developer, P4 Principal Application Developer, P5 Senior Principal, P6 Distinguished Engineer) and uses its internal Career Hub machine learning algorithms to suggest job openings to workers at their current grade or +1 order higher in the level hierarchy.   

17. GitLab
GitLab maintains a public Job Description Library that serves as the Single Source of Truth (SSoT) for all job families and career paths. Following an early-2026 job re-architecture, GitLab's technical taxonomy is structured across four major functional divisions. Within the Engineering Division, job families include Backend Engineering, Frontend Engineer, Fullstack Engineers, Engineering Infrastructure (Site Reliability Engineer, Database Reliability Engineer, Backend/Frontend Engineer, Infrastructure), Cloud Native Engineer, Database Engineer, Monitoring Engineer (Prometheus), Incubation Engineering, Vulnerability Research Engineer, Software Engineer in Test, and Data Science Development (Machine Learning Engineering). Within Enterprise Data, GitLab maintains distinct families for Data Engineering, Data Science, Data Analyst, Data Architect, Data Governance and Quality, and a rapidly growing Analytics Engineer family that bridges Data Analysis, Data Engineering, and Data Science. Within the Product Division, specialized engineering families include Accessibility Engineer, Frontend Engineer (UX), Fullstack Engineer (Technical Writing), and Data Engineer, Corporate Development. Within the Security Division, GitLab established a dedicated AI Security job family reporting directly to the CISO to build first-party AI security observability and protect AI-native development tools, alongside Application Security Engineer, Infrastructure Security, Red Team, and Security Research Engineer.   

GitLab grades technical roles across numeric Job Grades (Grade 5 to Grade 12) coupled with Radford benchmarks and explicit Specialty Designations (such as Backstage Specialist, Distributed Systems Specialist, Issue Triage Specialist, Prometheus Specialist, and Design System). Along the IC track, engineers advance from Associate Engineer (Grade 5), Intermediate Engineer (Grade 6), and Senior Engineer (Grade 7) to Staff Engineer (Grade 8), Principal Engineer (Grade 9), Distinguished Engineer (Grade 10), and Engineering Fellow (Grade 11), which GitLab explicitly defines as the individual contributor equivalent to a VP of Engineering. Along the management track, leaders advance from Engineering Manager (Grade 8) and Senior Engineering Manager (Grade 9) to Director of Engineering (Grade 10), Senior Director of Engineering (Grade 11), and VP of Development / VP of Incubation Engineering (Grade 12).   

18. Palantir Technologies
Palantir's career architecture established one of the most widely imitated role taxonomies in modern enterprise AI: the strict separation between Software Engineer (Core Product R&D engineers building Foundry, Gotham, Apollo, and AIP) and Forward Deployed Software Engineer (FDSE) (historically coded internally as Delta engineers who embed directly with commercial and government clients to architect, integrate, and deploy production data and AI workflows). This Forward Deployed Engineer job family has subsequently been adopted by Google Cloud (AI Outcome Engineer, Forward Deployed Engineering and Staff Forward Deployed Engineer, GenAI), OpenAI, and Scale AI. Externally, Palantir eliminates all numerical and prefix level titles—every engineer is titled simply Software Engineer or Forward Deployed Software Engineer—while calibrating internal compensation and equity refreshes across tenure and impact cohorts mapped to Radford P1–P6 equivalents.   

19. Uber Technologies
Uber categorizes technical talent into Software Engineering (Backend, Mobile, Web, Systems), Data Science, Applied Science (Marketplace pricing, routing, and machine learning models), and Data Engineering. Internally, Uber uses an L3 to L8 grading system featuring a distinctive split at the Senior (L5) level: L3 (Software Engineer I), L4 (Software Engineer II), L5a (Senior Software Engineer I), L5b (Senior Software Engineer II—an advanced senior bridge band between L5a and Staff), L6 (Staff Software Engineer), L7 (Senior Staff / Principal Engineer), and L8 (Distinguished Engineer / Uber Fellow). Management tracks run from L5a/b (Engineering Manager I/II) to L6 (Senior EM), L7 (Director), and L8 (Senior Director).

20. Databricks
Operating on Greenhouse and Workday, Databricks divides technical roles across Engineering (Distributed Systems, Spark/Photon Engine, Lakehouse Storage), Mosaic Research (Research Scientists and ML Engineers building foundation models, pre-training pipelines, and agent evaluation frameworks), and Field Engineering (Solutions Architects and Specialist SAs). Internally, Databricks aligns directly with the Google and Meta L3 to L8 numerical scale: L3 (Software Engineer), L4 (Software Engineer), L5 (Senior Software Engineer), L6 (Staff Software Engineer), L7 (Principal Software Engineer), and L8 (Distinguished Software Engineer).

Comprehensive Overview of the Top 100 Tech, FinTech, and Financial Services Companies
Expanding the analysis from the Top 20 technology firms across the broader Top 100 Technology, FinTech, and Financial Services ecosystem reveals a fundamental structural divergence between Technology-Native Architectures (which separate functional seniority from corporate officer status) and Financial Services Dual-Title Architectures (which bind every technical grade to a corporate banking officer rank such as Associate, Vice President, Executive Director, or Managing Director).   

Sectoral Taxonomy Archetypes Across the Top 100
In global investment banks, commercial banks, and asset managers (such as JPMorgan Chase, Goldman Sachs, Morgan Stanley, Bank of America, Citigroup, Wells Fargo, BlackRock, and Capital One), job architecture must reconcile internal corporate governance—where signature authority, bonus pools, and executive benefits are governed by banking officer titles—with external technical recruiting, where software engineers and AI researchers expect Silicon Valley functional titles. As exposed in Morgan Stanley's Workday requisition Lead-Software-Eng--Vice-President--Software-Engineer_PT-JR043381, Wall Street institutions maintain a dual-key job profile in Workday combining [Functional Level + Job Family] with [Corporate Officer Rank]. At JPMorgan Chase (600-series grades), an entry engineer is classified as Software Engineer I (601 - Analyst), a mid-level engineer is Software Engineer II (602 - Associate), a senior or lead engineer is Software Engineer III / Lead Software Engineer (603 - Vice President), a staff or principal engineer is Executive Director, Software Engineering (604), and an executive architect is Managing Director / Distinguished Engineer (605). Goldman Sachs similarly maps its Engineering division across Analyst, Associate, Vice President (VP), and Executive Director / Managing Director (MD) (and Partner), while classifying front-office algorithmic data scientists and quantitative modelers under the dedicated Quantitative Strategist (Strat) job family.   

Capital One operates a highly distinct hybrid tech-bank ladder that frequently creates false equivalencies if not carefully calibrated against external market data. On Capital One's technical IC ladder, entry-level engineers enter as Associate Software Engineer (0–2 years of experience) and advance to Senior Associate Software Engineer. However, at the senior and staff tiers, Capital One applies management-sounding corporate bands to pure individual contributors: a Principal Associate corresponds to a Senior Software Engineer, a Manager band corresponds to a Lead Software Engineer, a Director band corresponds to a Principal Software Engineer, and Distinguished Engineer is explicitly titled Distinguished Engineer (Director) or Sr. Distinguished Software Engineer (requiring 15–20 years of experience and aligning with a Big Tech L7 Senior Staff or L8 Principal Engineer, rather than an L9/L10 Fellow).   

In contrast, enterprise SaaS and cloud infrastructure firms (such as Sourcegraph, Snowflake, Datadog, CrowdStrike, Cloudflare, Atlassian, HubSpot, and Twilio) typically implement a direct 1-to-1 mapping to Aon Radford's P1–P6 (IC1–IC6) and M1–M6 (M3–M6) framework. As documented in Sourcegraph's handbook, employees view their exact Radford Job Code (e.g., HR.GLBP.P1 or HR.GLBP.M4) in BambooHR and cross-reference their Title, Radford Job Code, and Location-Zone in compensation transparency tools like Assemble (Zone 1 entry point pegged to the 75th percentile of US technology market data in Radford with the top of the band at +15%, and Zone 2 set at 80% of Zone 1). Crucially, these firms explicitly decouple the IC and Manager numbering scales: an IC6 (Principal Engineer) does not map directly to an M6 (VP of Engineering), because the management track begins at M3 (Engineering Manager, parallel to IC4 Senior Engineer).   

Digital-native FinTechs (such as Stripe, Block, PayPal, Adyen, Coinbase, Robinhood, Plaid, and Affirm) reject banking officer titles (VP/MD) entirely for technical staff, adopting the Google/Meta L3–L8 or Radford IC1–IC6 taxonomy. Block (Square/Cash App) uses a dual-numbered scale where L3 SWE is IC3, L4 is IC4, L5 is IC5 (Senior), L6 is IC6 (Staff), and L7 is IC7 (Principal), while PayPal uses numeric bands T22 through T30 (T22 SWE I, T23 SWE II, T24 SWE III, T25 MTS 1 / Senior, T26 MTS 2 / Staff, T27 Sr. MTS / Principal, T28 Architect, T30 Fellow). Meanwhile, quantitative hedge funds and proprietary trading firms (Citadel, Two Sigma, Jane Street, G-Research, Talos) operate flat external title structures that divide talent into three specialized families: Quantitative Researcher (QR) (PhD-level statistical and machine learning alpha modeling), Quantitative Developer / Quantitative Analyst (QD) (low-latency C++/Python/pandas dataframe and execution engineering), and Core Software Engineer (distributed trading systems and data platforms).   


Master Directory: Job Architecture Mapping Across the Top 100 Tech, FinTech, and Financial Services Companies
The following four tables provide the complete classification reference across the Top 100 organizations, segmented by industry cohort.

Cohort A: Hyperscalers, Big Tech, and Semiconductor Leaders (Companies 1–25)
#	Organization	ATS / HRIS Stack	Exposed Career Site Facets	Core Software, Data & AI Job Families	IC Grade Scale	Management Scale
1	Alphabet (Google)	Custom + Workday	
Category + Level Badge (Mid, Advanced)

SWE, SRE, Research Scientist, Data Scientist, Cloud AI Dev, DeepMind Evals Eng

L3–L11	L5 (TLM) to L10 (SVP)
2	Amazon	Custom (amazon.jobs)	
JOB CATEGORY (26 filters)

Software Dev (SDE), Applied Science (AS), Data Science (DS), Data Eng (DE), BIE

L4–L10	L5 (M1) to L10 (VP)
3	Meta Platforms	Custom + Workday	
Teams & Role Tags

SWE, SWE (ML/Ranking), Production Eng, Data Eng (Analytics), Data Scientist, Research

E3–E9 (IC3–IC9)	M1–M2, D1–D2, VP
4	Apple	Custom + Workday	Teams and Sub-Teams	
Software & Services (SWE), ML & AI (ML Engineer, ML Researcher), Data Science

ICT2–ICT6 + Fellow

M1–M5 (VP)
5	Microsoft	Eightfold + SAP	Profession & Discipline	Software Engineering, Data & Applied Science, Research Sciences	L59–L80	M1 (L63) to CVP (L70+)
6	NVIDIA	
Workday + Eightfold

jobFamilyGroup: Engineering - Software

[cite: 75]

System Software, Deep Learning Eng, GPU Arch, Applied Research, Autonomous Vehicles	IC1–IC9	M2–M7+
7	Broadcom	Workday (myworkdayjobs)	Job Family: R&D - Software, R&D - IC Design	Embedded/Systems SWE, ASIC/Silicon Eng, AI Networking Software, Mainframe Software	IC1–IC7 (P1–P7)	M1–M6
8	TSMC	Custom + SAP	Job Category: R&D, IT, Operations	IT Software Engineer, EDA/CAD Engineer, Machine Learning / Smart Manufacturing Eng	Grade 31–39	Grade 34–40+
9	Tesla	Custom / Avature	Category: AI & Robotics, Software, Vehicle Eng	Autopilot / Optimus AI Engineer, Infotainment SWE, Distributed Backend SWE, Data Eng	P1–P6	M1–M5
10	Tencent	Custom Career Portal	Category: Technology (Software, AI/Data)	Backend/Client SWE, Machine Learning Researcher (Hunyuan), Game Engine Developer	Grade 4–17 (T4–T17)	M1–M6
11	ByteDance (TikTok)	Custom Portal	Category: R&D (Backend, Algorithm, Data)	Software Engineer, Machine Learning Engineer (Recommendation/AML), Research Scientist, DE	1-1 to 5-2 (1-2 to 4-1 Core)	3-1 to 5-2
12	Samsung Electronics	Custom + Workday	Category: Software Development, AI/Data	Software Engineer, On-Device AI Engineer (Samsung Research), DS/Semiconductor SW	CL1–CL4 (Career Level)	CL3–CL4 + Exec
13	AMD	
Workday + Eightfold

Category: Software Engineering, Silicon Design	ROCm / AI Software Engineer, ML Compiler Engineer, Systems Architect, Firmware Eng	L4 (Assoc) to L12 (Fellow)	M7–M12
14	Qualcomm	
Workday + Eightfold

Department: Engineering (Software, ML/AI)	
Embedded SWE, Machine Learning Engineer (Radford 5171–5176), AI Research Scientist

P1–P7 (Eng to Sr. Dir Tech)	M1–M6
15	Intel	Workday (myworkdayjobs)	Job Category: Software Engineering, AI	AI Frameworks SWE, Systems/Kernel SWE, Data Scientist, Principal/Fellow Architect	Grade 3–13 (G3–G13)	Grade 7–12+
16	ARM Holdings	iCIMS / Workday	Category: Software Engineering, Hardware	CPU/NPU Architecture Engineer, Open Source / ML Kernel Software Engineer	Grade 2–9 (Grad to Fellow)	Grade 5–9
17	ASML	Workday (myworkdayjobs)	Category: Software Engineering, Data Science	Metrology / Lithography Embedded SWE, Computational Physics & ML Data Scientist	Job Grade 05–14	Job Grade 08–14+
18	Micron Technology	Eightfold + Workday	Discipline: Software Engineering, Data Science	Smart Manufacturing Data Scientist, Firmware/Embedded SWE, AI Systems Engineer	E1–E6 + Fellow	M1–M6
19	Texas Instruments	Custom + Workday	Category: Engineering - Software, IT	Embedded Software Engineer, EDA/Systems Engineer, Data & Analytics Engineer	Grade 24–35+ (Tech Ladder)	Grade 28–35+
20	Applied Materials	Workday + Eightfold	Function: Software Engineering, AI/Data	Semiconductor Control Software Engineer, AI/ML Algorithm Engineer, Data Scientist	E1–E7 (Tech Staff to Fellow)	M1–M6
21	Sony Group	Custom + Workday	Category: Software, AI Research (Sony AI)	PlayStation Systems/Network SWE, AI Research Scientist (Sony AI), Computer Vision Eng	P1–P6 (L3–L8 US/SIE)	M1–M6
22	Dell Technologies	Workday (myworkdayjobs)	Category: Software Engineering, Data Science	Systems Software Engineer, AI Factory / Cloud Infrastructure SWE, Data Scientist	I5 (Assoc) to I12 (Fellow)	M6 to M12 (VP)
23	Hewlett Packard Ent. (HPE)	
Workday (myworkdayjobs)

Category: Engineering, Information Technology	Aruba/Cloud Systems SWE, HPC & AI Supercomputing Engineer (Cray), Data Scientist	
P1–P7 (Radford/Workday)

M1–M6
24	Lenovo	SuccessFactors / Eightfold	Category: Software Development, AI R&D	Cloud/Edge Software Engineer, AI Solutions Architect, Machine Learning Engineer	Band 5–10 + Fellow	Band 7–11+
25	CGI Group	
Custom / Taleo

Category: Software Engineering, Cloud, AI	
Cloud Engineer (Software Engineer - Senior), Application Dev, AI/ML Consultant

Member 1–5 (Dir. Consult.)	Director to SVP
  
Cohort B: Enterprise SaaS, Cloud Infrastructure, and Cybersecurity Leaders (Companies 26–55)
#	Organization	ATS / HRIS Stack	Exposed Career Site Facets	Core Software, Data & AI Job Families	IC Grade Scale	Management Scale
26	Oracle	
Oracle HCM Cloud

Software Development, Product Dev	OCI Cloud SWE, Database Kernel SWE, Applied AI Scientist, Consulting MTS	IC1–IC6	M1–M6
27	Salesforce	Workday	Software Engineering, AI Research	AMTS, MTS, SMTS, LMTS, PMTS, Architect, AI Research Scientist, Data Scientist	Grade 5–12+	Grade 8–12+
28	SAP	
SAP SuccessFactors TIH

Career Area: Software Design & Dev	Developer, Senior Developer, Development Architect, Chief Development Architect, AI Scientist	T1–T5 (T4 Chief Arch)	M1–M5
29	Adobe	Workday	Engineering & Product, Research	Computer Scientist (CS1–CS2, Sr. CS1–CS2), ML Engineer, Research Scientist	P10–P80	M30–M60
30	IBM	Custom + Workday	Software Engineering, Data & Analytics, Research	
Software Developer, Advisory/Sr SWE, STSM, Distinguished Engineer, Research Staff Member

Band 6–10 + Band D/C	Band 7–10 + Exec
31	Cisco Systems	Phenom + Workday	Engineer - Software, Data & Analytics	Software Engineer, Network/Silicon SWE, Machine Learning Engineer, Data Scientist	Grade 4–13	Grade 10–13+
32	ServiceNow	
SmartRecruiters + SN

Engineering, AI & Data, Cloud Ops	
Software Engineer, ML Engineer, AI Research Scientist, SRE (sn_skills_int_job_level)

IC1–IC7

[cite: 5]

M1–M6
33	Workday	
Workday

Product & Technology, Engineering	
Software Application Engineer, Systems Engineer, ML Engineer, Data Scientist

P1–P7

[cite: 41]

M1–M6
34	Intuit	Phenom + Workday	Category: Software Engineering, Data	Software Engineer (SWE 1–2, Sr, Staff, Principal), Data Scientist, ML Engineer (GenOS)	IC1–IC7 (Distinguished)	M1–M6
35	Palo Alto Networks	SmartRecruiters + Workday	Department: Engineering, AI & Data Science	Network/Cloud Security SWE, Threat Intelligence Data Scientist, AI/ML Security Eng	IC1–IC6 (P1–P6)	M1–M6
36	CrowdStrike	Workday (myworkdayjobs)	Job Family: Engineering, Data Science	Sensor/Kernel SWE, Distributed Cloud SWE, AI/Threat Detection Data Scientist	P1–P6 (Eng I to Dist.)	M1–M6
37	Snowflake	Ashby + Workday	Department: Engineering, AI & ML	Database Systems SWE, Distributed Systems SWE, AI Research Scientist (Arctic LLM)	IC1–IC7 (L3–L9 Equiv)	M1–M6
38	Datadog	Greenhouse + Workday	Team: Engineering, Data Science & AI	Distributed Systems SWE, Agent/ebpf SWE, Machine Learning Engineer (Bits AI)	L1–L7 (SWE 1 to Dist.)	M1–M6
39	Cloudflare	Greenhouse + Workday	Department: Engineering, Emerging Tech	Systems Engineer (Rust/Go), Network Engineer, AI Inference Platform Engineer (Workers AI)	P1–P7 (IC1–IC7)	M1–M6
40	Atlassian	iCIMS / Lever + Workday	Category: Engineering, Data Science	Backend/Frontend SWE, Machine Learning Engineer (Rovo AI), Data Scientist, Analytics Eng	P30–P90 (P30 Grad to P80 Dist.)	M30–M80
41	Shopify	SmartRecruiters + Custom	Discipline: Engineering & Data	Software Developer, Data Scientist (Full-stack Data/DE/ML), Machine Learning Engineer	L4–L10 (C1–C7 Craft Track)	M5–M10
42	Autodesk	Workday (myworkdayjobs)	Job Family: Software & Cloud Eng, AI Lab	Cloud/Graphics SWE, Generative Design & 3D AI Research Scientist, Data Engineer	Grade 8–16 (P1–P7)	Grade 11–16+
43	Synopsys	SuccessFactors / Workday	Category: R&D Engineering, AI/ML	R&D Engineer (EDA Algorithms/C++), AI-Driven Chip Design (DSO.ai) ML Engineer	I1–I7 (Eng I to Fellow)	M1–M6
44	Cadence Design	Workday (myworkdayjobs)	Job Family: Engineering - Software	Software Engineer (Lead, Principal, Architect), Computational Software / AI Eng	T1–T7 (Technical Ladder)	M1–M6
45	Fortinet	Custom + Workday	Category: R&D / Software Engineering	FortiOS Kernel/Network SWE, Threat Research & AI/ML Detection Engineer	L1–L6 (P1–P6)	M1–M5
46	Zscaler	Greenhouse + Workday	Department: Engineering, AI & Data	Zero Trust Cloud Proxy SWE (C/C++), Data Scientist, AI/ML Security Engineer	IC1–IC6 (SWE to Dist.)	M1–M6
47	HubSpot	Greenhouse + Workday	Department: Product & Engineering	Software Engineer (SWE, Sr SWE I/II, Tech Lead, Principal), ML Engineer (Breeze AI)	IC1–IC7 (L1–L7)	M1–M6 (Eng Lead+)
48	Twilio	Greenhouse + Workday	Department: Engineering, Data & AI	Distributed Communications SWE, CustomerAI / Segment Data Engineer, ML Engineer	P1–P6 (L1–L6)	M2–M6
49	Okta	Greenhouse + Workday	Department: Engineering, Security & Data	Identity Platform SWE, Staff/Principal Architect, Identity Threat ML Engineer	IC1–IC7 (P1–P7)	M1–M6
50	MongoDB	Greenhouse + Workday	Department: Engineering (Server, Cloud)	Database Kernel SWE (C++), Atlas Cloud SWE (Go), Vector Search & AI Solutions Eng	L2 (SWE 1) to L8 (Dist.)	M3–M8
51	Confluent	Ashby + Workday	Department: Engineering	Kafka/Flink Distributed Stream Processing SWE, Cloud Infrastructure SWE, AI Data Streaming	L2–L8 (IC2–IC8)	M3–M7
52	Elastic	Greenhouse + Workday	Department: Engineering	Search & Vector Database SWE (Lucene/Java), GenAI / Relevance ML Engineer, SRE	L4 (SWE) to L10 (Fellow)	M5–M10
53	GitLab	
Greenhouse + Handbook

Engineering, Enterprise Data, Security

[cite: 69, 94, 95]

Backend/Frontend/Fullstack, Infra/SRE, ML Eng, Data Scientist, Analytics Eng, AI Security

Grade 5–11 (Assoc to Fellow)

Grade 8–12 (EM to VP)

54	Sourcegraph	
Greenhouse + BambooHR

Engineering, Product

[cite: 20]

Software Engineer, AI Coding Agent Engineer (Cody), Security/DevOps (...P1–P6)

IC1–IC6 (Radford P1–P6)

M3–M6 (Radford M3–M6)

55	DocuSign	SmartRecruiters + Workday	Category: Engineering & Tech, AI/Data	Agreement Cloud SWE, Applied NLP / Document AI Scientist, Data Engineer	P1–P7 (Radford Aligned)	M1–M6
  
Cohort C: Frontier AI Labs, Data Platforms, and Consumer Tech Scale-Ups (Companies 56–75)
#	Organization	ATS / HRIS Stack	Exposed Career Site Facets	Core Software, Data & AI Job Families	IC Grade Scale	Management Scale
56	OpenAI	
Ashby + Workday

Research, Applied AI, Safety Systems

[cite: 17]

Member of Technical Staff (MTS), Applied AI SWE, Research Scientist, Forward Deployed Eng

L2–L7+ (Flat MTS Title)	EM / Lead to VP
57	Anthropic	Greenhouse + Workday	
8 Research/Safety Pods (RL, Pretraining, Alignment)

Research Engineer, Research Scientist, AI Engineer, Safeguards / Security Engineer

Flat MTS (L3–L7 Internal)	Pod Lead to Head
58	Databricks	Greenhouse + Workday	Engineering, Mosaic Research, Field Eng	Distributed Systems SWE, Mosaic AI Research Scientist, ML Engineer, Solutions Architect	L3–L8	M3–M7 (VP)
59	Palantir	
Lever + Workday

Software Engineering, Forward Deployed SWE

[cite: 96]

Software Engineer (Foundry/Gotham/AIP), Forward Deployed Software Engineer (FDSE)

Flat Title (L1–L5 Internal)	Lead / Group Lead
60	xAI	Greenhouse	Engineering, Research, Infrastructure	Member of Technical Staff (Pre-training, RL, Grok Coding, Supercluster Infrastructure)	Flat MTS	Flat Engineering Lead
61	Scale AI	Ashby / Greenhouse	Engineering, GenAI, Federal / Public Sector	Software Engineer, Machine Learning Research Engineer, Forward Deployed Engineer, Data Ops	L3–L8	M1–M5
62	Cohere	Ashby	Engineering, Research, Applied AI	Member of Technical Staff, ML Engineer (Enterprise LLM/RAG), Research Scientist	IC2–IC7	M1–M5
63	Mistral AI	Lever / Ashby	Research & Core Eng, Product & Platform	AI Research Scientist, Inference / Kernel Engineer, Forward Deployed AI Engineer	IC3–IC7	Lead to VP
64	Hugging Face	Workable / Custom	Open Source, Science, Infrastructure	Machine Learning Engineer (Open Source Transformers/Diffusers), Research Scientist, Infra Eng	Flat Band (L3–L6 Equiv)	Team Lead
65	Crusoe Energy	
Ashby + Workday

Cloud Engineering, Infrastructure, People

[cite: 114]

AI Cloud Infrastructure SWE, Kubernetes/GPU Cluster Engineer, Network Engineer (2026 Workday JA)

P1–P6 (IC1–IC6)

M1–M5
66	CoreWeave	Greenhouse + Workday	Engineering, Cloud Infrastructure	HPC / GPU Infrastructure Software Engineer, Storage/Networking SWE, AI Solutions Eng	IC1–IC6 (P1–P6)	M1–M6
67	Netflix	Workday + Eightfold	Core Engineering, Data & Insights, ML	Software Engineer, Data Engineer, Analytics Engineer, Machine Learning Scientist/Eng	L3–L7	Mgr, Dir, VP
68	Uber	iCIMS + Workday	Backend, Mobile, Data, Machine Learning	Software Engineer, Systems Engineer, Applied Scientist, Data Scientist, Data Engineer	L3–L8 (L5a / L5b Split)	L5a (EM) to L8+
69	Airbnb	Greenhouse + Workday	Engineering, Data Science & Analytics, AI	Software Engineer, Machine Learning Engineer, Data Scientist (Analytics, Inference, Algorithms)	G7 (SWE I) to G12 (Dist.)	M8 (EM) to M12+
70	DoorDash	Greenhouse + Workday	Engineering, Data Science & ML	Software Engineer, Machine Learning Engineer (Logistics/Ads), Data Scientist	E3 to E8	M3 (E5 Equiv) to VP
71	Spotify	Lever + Workday	Engineering, Data, Research & Insights	Backend/Client Engineer, Machine Learning Engineer (Personalization/Audio), Data Scientist	Step 1–6 (Assoc to Principal)	Chapter Lead to VP
72	Snap Inc.	Workday (myworkdayjobs)	Engineering, Research	Software Engineer, Machine Learning Engineer (AR/Computer Vision/Ads), Research Scientist	L3 to L8	M3 (L5) to L8+
73	Pinterest	Greenhouse + Workday	Engineering, Data Science & ML	Software Engineer, Machine Learning Engineer (Visual Discovery), Data Scientist	L13 (SWE I) to L18 (Dist.)	M15 to M18+
74	Reddit	Greenhouse + Workday	Engineering, Data Science & ML	Software Engineer, Machine Learning Engineer (Feed/Search/LLM Licensing), Data Scientist	IC1–IC7 (L3–L8 Equiv)	M3–M7
75	Roblox	Greenhouse + Workday	Engineering, Data Science & Analytics, AI	Engine/Graphics C++ SWE, Distributed Systems SWE, Generative 3D AI Scientist, Data Scientist	IC1–IC7 (P1–P7)	M1–M6
  
Cohort D: Global Investment Banks, Financial Services, and Digital FinTechs (Companies 76–100)
#	Organization	ATS / HRIS Stack	Exposed Career Site Facets	Core Software, Data & AI Job Families	IC Grade & Officer Scale	Management & Exec Scale
76	JPMorgan Chase	
Oracle HCM / Workday

Technology (Software Eng, Data & Analytics, AI/ML)

Software Engineer (I, II, III, Lead), Applied AI/ML Scientist, Data Engineer, Quant Analytics

601 (Analyst), 602 (Assoc), 603 (VP), 604 (ED), 605 (MD/Dist.)	603 (VP) to 605 (MD)
77	Goldman Sachs	
Custom + Workday

Engineering (Software, Data, Quantitative Strats)

Software Engineer, Quantitative Strategist (Strat), Machine Learning / AI Engineer, Cloud Eng

Analyst 
→ Associate 
→ VP 
→ ED/MD 
→ Partner	VP to MD / Partner
78	Morgan Stanley	
Workday (ms.wd5.myworkdayjobs)

Technology (Software Engineering, Data, AI)

Software Engineer (Assoc, Lead Software Eng - VP), Strats & Modeling, AI/ML Strategist

Analyst 
→ Associate 
→ VP 
→ ED 
→ MD / Fellow

[cite: 72]

VP to MD
79	Capital One	
Workday (myworkdayjobs)

Category: Engineering, Data Science, Machine Learning

[cite: 111]

Software Engineer, Data Engineer, Machine Learning Engineer, Data Scientist

Assoc SWE 
→ Sr Assoc 
→ Principal Assoc (Sr SWE) 
→ Mgr (Lead) 
→ Dir (Principal) 
→ Dist. Eng 
→ Sr. Dist. Eng

[cite: 76, 107, 111]

Mgr to VP / SVP
80	Citigroup	Workday (citi.wd5.myworkdayjobs)	Job Family: Technology (Apps Dev, Data/AI)	Applications Development Programmer Analyst, Data Scientist, AI/ML Engineer	C09 (Analyst), C10 (Sr Analyst), C11 (AVP), C12 (VP), C13 (SVP), C14 (Dir), C15–16 (MD)	C12 (VP) to C16 (MD)
81	Bank of America	Workday (ghr.wd1.myworkdayjobs)	Job Family: Technology, Quantitative Analytics	Software Engineer (I, II, III / Sr), Lead Architect, Data Scientist, Quantitative Finance	Band 6 (Analyst), Band 5 (AVP/VP), Band 4 (VP/Sr SWE), Band 3 (SVP), Band 2–1 (Exec)	Band 4 to Band 1
82	Wells Fargo	
Workday (myworkdayjobs)

Job Family: Engineering, Data & Analytics

[cite: 108]

Software Engineer (Assoc, SWE, Sr, Lead, Principal, Dist.), Data Science Consultant	L1–L7 mapped to AVP, VP, SVP, ED	VP to EVP
83	American Express	Eightfold + Workday	Category: Technology, Data Science & Analytics	Engineer (III, II, I — inverted!), Senior Engineer, Principal Engineer, Director/Decision Science	Band 25 (Eng III Entry) 
→ Band 30 (Eng I) 
→ Band 35 (Sr Eng) 
→ Band 40 (Dir/Principal)	Band 35–40 to VP (Band 50+)
84	Visa	SmartRecruiters + Workday	Department: Technology, Data & AI	Software Engineer (Assoc, SWE, Sr, Staff, Sr Staff, Principal, Dist.), Data Scientist (Visa AI)	P1–P7 (Grade 8–15)	M1–M6 (Dir to SVP)
85	Mastercard	Phenom + Workday	Category: Software Engineering, AI & Data	Software Engineer (I, II, Sr, Principal, Dist.), AI/Fraud Modeling Data Scientist	Level 10 (Entry) down to Level 3 (Exec)	Level 6 (Mgr) to Level 2
86	BlackRock	Workday (myworkdayjobs)	Function: Technology & Enterprise Ops, Aladdin	Aladdin Software Engineer, Quantitative Researcher, AI/NLP Data Scientist (Aladdin Wealth)	Analyst 
→ Associate 
→ VP 
→ Director 
→ MD	VP to MD
87	Fidelity Investments	Custom + Workday	Category: Technology, Data & Analytics	Software Engineer (Assoc, SWE, Sr, Principal, Dist.), Director of Data Science / AI	Grade 3–9 (G5 Sr SWE, G6 Principal, G7 Dir)	Grade 6–9 (VP)
88	Bloomberg L.P.	Avature / Custom	Department: Engineering, CTO / AI Group	Software Engineer, Senior Software Engineer (Flat IC Title), AI Research Scientist (BloombergGPT)	Flat Senior SWE Title (Internal Band 4–8)	Team Lead 
→ EM 
→ Head
89	Citadel / Citadel Sec.	Greenhouse + Workday	Category: Engineering, Quantitative Research	Software Engineer (Low-Latency C++/Distributed), Quantitative Researcher, Quantitative Developer	Flat External Title (Internal L1–L6 Comp Bands)	Team Lead 
→ Head of Eng
90	Two Sigma	Greenhouse / Custom	Career Area: Engineering, Quantitative Research	Software Engineer, Data Engineer, Quantitative Researcher, AI/ML Modeler	L1–L6 + VP / MD Officer Rank	Engineering Manager to MD
91	Jane Street	Custom Portal	Department: Software Engineering, Quantitative Research	Software Engineer (OCaml/Systems), Quantitative Researcher, Machine Learning Engineer	Flat Structure (No numerical IC grades)	Desk / Tech Group Lead
92	PNC Financial	
Workday (myworkdayjobs)

Category: Technology, Data & Analytics

[cite: 116]

Software Engineer, Lead Software Engineer, Data Scientist, Cybersecurity Engineer (McLagan Benchmarked)

Assoc 
→ Sr 
→ Lead (VP) 
→ Principal (SVP)	VP to EVP
93	Stripe	Greenhouse + Workday	Team: Engineering, Data Science, Machine Learning	Software Engineer, Machine Learning Engineer (Payments Fraud/Radar), Data Scientist, Data Eng	L1 (New Grad) 
→ L2 (Mid) 
→ L3 (Sr) 
→ L4 (Staff) 
→ L5 (Principal) 
→ L6 (Dist.)	M1 (L3) to M5
94	Block (Square / Cash App)	SmartRecruiters + Workday	Category: Software Engineering, Data & ML	Software Engineer, Machine Learning Engineer, Data Scientist, Analytics Engineer	L3 (IC3) 
→ L4 (IC4) 
→ L5 (IC5 Sr) 
→ L6 (IC6 Staff) 
→ L7 (IC7 Principal)	M3 (L5) to M7
95	PayPal	Eightfold + Workday	Discipline: Software Development, Data Science	Software Engineer (I–III), MTS (MTS 1, MTS 2, Sr MTS), Architect, Fellow, Data Scientist	T22 (SWE I) 
→ T24 (SWE III) 
→ T25 (MTS 1) 
→ T26 (MTS 2) 
→ T27 (Sr MTS) 
→ T28–T30	M2 (T25) to VP
96	Coinbase	Greenhouse + Workday	Department: Engineering - Backend/Frontend/Data/ML	Software Engineer (Associate, SWE, Senior, Staff, Sr Staff, Principal), ML Engineer	IC3 
→ IC4 
→ IC5 (Sr) 
→ IC6 (Staff) 
→ IC7 (Sr Staff) 
→ IC8 (Principal)	M3 (IC5) to VP
97	Robinhood	Greenhouse + Workday	Department: Engineering, Data & Machine Learning	Software Engineer, Machine Learning Engineer, Staff/Principal Engineer, Data Scientist	L1 (SWE I) 
→ L2 (SWE II) 
→ L3 (Sr SWE) 
→ L4 (Staff) 
→ L5 (Sr Staff) 
→ L6 (Principal)	M1 (L3) to M4+
98	Adyen	Greenhouse + Workday	Team: Tech & Engineering, Data	Developer (Java/Python), Data Engineer, Machine Learning Engineer, Platform Engineer	Flat External Title (Internal Radford/Ravio P1–P6)	Team Lead 
→ VP
99	Plaid	Lever + Workday	Department: Engineering, Data	Software Engineer, Machine Learning Engineer (Risk/Identity), Data Scientist	L3 (New Grad) 
→ L4 
→ L5 (Sr) 
→ L6 (Staff) 
→ L7 (Principal)	M3 (L5) to VP
100	Affirm	Greenhouse + Workday	Department: Engineering, Machine Learning & Data	Software Engineer, Applied Machine Learning Engineer (Credit Underwriting), Data Scientist	L3 
→ L4 
→ L5 (Sr) 
→ L6 (Staff) 
→ L7 (Principal) 
→ L8 (Dist.)	M3 (L5) to VP
  
While 95% of technology and financial services organizations increment level numbers upward with seniority (such as L3 to L8 or P1 to P6), three major financial institutions invert or offset their scales. American Express titles entry-level software engineers Engineer III (Band 25) and promotes them downward in Roman numerals to Engineer II (Band 28) and Engineer I (Band 30) before reaching Senior Engineer (Band 35) and Director / Principal Engineer (Band 40). Similarly, Bank of America numbers its corporate bands inversely from Band 6 (Entry Analyst) down to Band 1 (Senior Executive), and Mastercard numbers its global grades from Level 10 (Entry) down to Level 1 (Executive). Among digital FinTechs, Stripe and Robinhood offset their numerical scales by two levels relative to Google and Meta, meaning a Stripe L3 or Robinhood L3 is a Senior Software Engineer (equivalent to Google/Meta L5), and a Stripe L4 is a Staff Software Engineer (equivalent to Google/Meta L6).

Strategic Synthesis and Architectural Recommendations
The cross-sector mapping of the Top 100 organizations and consulting compensation databases establishes four structural imperatives for organizations designing or modernizing their Software, Data, and AI job architectures in 2026.

First, organizations must decouple Artificial Intelligence and Machine Learning job families from general Software Engineering. Relying on general Software Development survey codes to benchmark AI talent—as 31% of employers did prior to Aon's March 2026 RMCD overhaul—creates severe compensation compression or forces ad-hoc band exceptions that undermine internal pay equity. Enterprise taxonomies should adopt the four-way technical classification model established by Amazon, Meta, and the 2026 RMCD update: Core Software Engineering (SWE/SDE), Applied AI / Machine Learning Engineering (MLE / Applied Scientist) carrying a systematic 15%–25% market pay differential, Frontier AI / Foundation Model Research (Research Scientist), and Forward Deployed AI Engineering (FDSE / AI Outcome Engineer) for customer-embedded multi-agent and LLM orchestration.   

Second, organizations should formalize emerging hybrid sub-families within their Data and Security functions. Within the Data function, traditional boundaries between SQL-focused Data Analysts and infrastructure-focused Data Engineers have converged; following GitLab's 2026 re-architecture, enterprises should establish Analytics Engineering as a distinct sub-family bridging data transformation, dimensional modeling, and product analytics. Concurrently, within the Security function, organizations should establish a dedicated AI Security job family reporting to the CISO to govern LLM guardrails, red-teaming, and agentic security observability.   

Third, HRIS and Total Rewards teams should standardize on a 6-to-7 level Individual Contributor spine mapped to dual external survey keys. To prevent title inflation while enabling seamless multi-source benchmarking, internal HRIS Job Profiles (in Workday or ServiceNow) should anchor on a 6- or 7-level Individual Contributor spine (P1/IC1 Entry through P6/IC6 Principal and P7/IC7 Distinguished/Fellow) and a parallel 5-to-6 level Management spine (M1/M2 Manager through M5/M6 Senior Director/VP). Each internal Job Profile should store both a primary Radford RMCD alphanumeric code ([Function].[Sub-family].[P1-7 / M1-6]) for technology and equity pricing and a secondary Mercer MJL / WTW GGS Global Grade (GG8–GG17) for global corporate and financial services parity.   

Finally, organizations must embed validated skill ontologies directly into HRIS Job Profiles to govern band progression and pay transparency compliance. As US state pay transparency statutes and the EU Pay Transparency Directive mandate objective, auditable criteria for compensation placement and promotion, tenure-based leveling is legally and operationally fragile. Connecting Workday or SAP SuccessFactors Job Profiles directly to curated skill graphs—attaching five to ten verified technical capabilities per level (such as distributed systems architecture, multi-agent SDLC orchestration, or PyTorch/JAX model optimization)—ensures that recruiting scorecards, internal mobility engines, and salary band progressions operate from a single, defensible architectural source of truth.   


careerbird.ai
Job Title Chaos: How to Fix Inconsistent Roles and Leveling Across
Opens in a new window

umbrex.com
Job Family Architecture Models | Talent & HR - Umbrex
Opens in a new window

compensation-iq.com
Job architecture software - Compensation IQ
Opens in a new window

soteriahr.com
Radford Compensation Survey: Cost & Fit - Soteria HR
Opens in a new window

servicenow.com
About Job Architecture - ServiceNow
Opens in a new window

community.sap.com
Unlocking Industry-Specific Value with SAP Talent Intelligence Hub
Opens in a new window

cioreview.com
Enabling Global Human Resources at Willis Towers Watson with
Opens in a new window

cfo.asu.edu
ASU Job Architecture | Arizona State University
Opens in a new window

talentguard.com
What Is Job Architecture? A 2026 Guide + 2 Examples | TalentGuard
Opens in a new window

hyring.com
What Is a Job Family? Definition and Guide - Hyring
Opens in a new window

sanandres.uep.edu.py
2022 Radford Gcd Job Family Descriptions
Opens in a new window

aon.com
Compensation Survey Data for Private Companies - Aon
Opens in a new window

compbldr.ai
Job Families in Compensation Explained - CompBldr
Opens in a new window

aon.com
Job Architecture | Aon
Opens in a new window

irvineanalytics.ai
Workday Job Profile — the job architecture, business-title trap, and
Opens in a new window

scribd.com
Canada Job Matching Booklet | PDF | Subsidiary | Libraries - Scribd
Opens in a new window

sundeepteki.org
AI Career Guides: Anthropic, OpenAI & DeepMind ... - Sundeep Teki
Opens in a new window

handbook.gitlab.com
Engineering Roles | The GitLab Handbook
Opens in a new window

handbook.gitlab.com
Analytics Engineering | The GitLab Handbook
Opens in a new window

github.com
leveling-guide.md - benefits-pay-perks - GitHub
Opens in a new window

imercer.com
Mercer Skills-Edge Suite - Imercer
Opens in a new window

scribd.com
WTW Job Matching Methodology Overview | PDF - Scribd
Opens in a new window

scribd.com
2022 Radford GCD Job Family Descriptions | PDF - Scribd
Opens in a new window

scribd.com
8-Benchmarking-Towers Watson | PDF | Tort | Negligence - Scribd
Opens in a new window

rolemapper.tech
Demystifying Job Levelling: Popular Frameworks for ... - RoleMapper
Opens in a new window

peopleanalyticstoolbox.com
DevOps Engineer · P7 — JobFrame profile - People Analytics Toolbox
Opens in a new window

designgurus.io
FAANG Software Engineer Levels Explained: Apple ICT, Google L
Opens in a new window

h1bgrader.com
Senior Machine Learning Engineer - H1B LCAs with Non-OES
Opens in a new window

scribd.com
Assignment 3 - Workday HCM - Scribd
Opens in a new window

doc.workday.com
Restrict Job Profiles by Country and Organization
Opens in a new window

handbook.gitlab.com
Product Manager | The GitLab Handbook
Opens in a new window

namic.org
2024 NAMIC COMPENSATION SURVEY AND MODULE*
Opens in a new window

ravio.com
12 Radford alternatives for compensation benchmarking in 2026
Opens in a new window

levels.fyi
Levels, Ladders and Titles: Everything You Need to Know
Opens in a new window

careers.google.com
Strategy and Insights Manager, Large Customer Sales
Opens in a new window

brynq.com
Job Architecture Guide: Build Clear Career Paths & Roles - BrynQ
Opens in a new window

techwolf.ai
Skills Data Provider: How to Choose the Right One | TechWolf
Opens in a new window

inop.ai
Skills-Based Pay Bands: How to Build, Examples & Templates (2026)
Opens in a new window

scribd.com
PDF 2025 The New Rules of Job Architecture - Scribd
Opens in a new window

aon.com
SkillsGraph | Aon
Opens in a new window

doc.workday.com
Concept: Optimizing Suggested Job Openings in the Career Hub
Opens in a new window

scribd.com
Radford Job Leveling Framework Overview | PDF | Evaluation - Scribd
Opens in a new window

scribd.com
2025 Radford McLagan Compensation Guide | PDF | Banks - Scribd
Opens in a new window

salarycube.com
15 Best Compensation Benchmarking Companies for 2026
Opens in a new window

github.com
Compensation & Pay Transparency at Sourcegraph - GitHub
Opens in a new window

h1bdata.info
H1B CASE NUMBER I-200-26021-574978
Opens in a new window

hr.uw.edu
2023 Professional Staff Salary Survey - UW Human Resources
Opens in a new window

sempra.com
Sempra 2024 Proxy Statement (DEF14A)
Opens in a new window

psc.ky.gov
Untitled - KY PSC Home
Opens in a new window

scribd.com
Job Leveling - Towers Watson PDF - Scribd
Opens in a new window

prnewswire.com
Aon Launches Radford McLagan Compensation Database
Opens in a new window

pdfcoffee.com
Radford Global Compensation Database (2022) - pdfcoffee.com
Opens in a new window

pdfcoffee.com
2022 Radford GCD Job Family Descriptions - PDFCOFFEE.COM
Opens in a new window

sanandres.uep.edu.py
2022 Radford Gcd Job Family Descriptions
Opens in a new window

ziprecruiter.com
Software Engineer Jobs in Radford, VA (NOW HIRING) - ZipRecruiter
Opens in a new window

explorehumancapital.aon.com
Artificial Intelligence Study - Human Capital
Opens in a new window

aon.mediaroom.com
Aon Launches Radford McLagan Compensation Database
Opens in a new window

mercer.com
Accurate, accessible global job evaluation methodology – Mercer IPE
Opens in a new window

inop.ai
Predictive Compensation Analytics: Meaning + 4 Key Components
Opens in a new window

mercer.com
Global Employee Benefits & Compensation Data - Mercer
Opens in a new window

scribd.com
2018 Mercer Job Library Job Families | PDF - Scribd
Opens in a new window

scribd.com
Global Grading System Overview | Human Resource Management
Opens in a new window

slideshare.net
job-leveling-solutions.pdf - Slideshare
Opens in a new window

scribd.com
Job Family Modeling | PDF | Competence (Human Resources) - Scribd
Opens in a new window

scribd.com
Job Family Modeling - Hay Group, Chemicals Industry | PDF - Scribd
Opens in a new window

omnihr.co
HR's Guide to Compensation Benchmarking in the FinTech Industry
Opens in a new window

rolemapper.tech
What is job levelling and why is it important? - RoleMapper
Opens in a new window

scribd.com
Career Bands and Levels Overview | Human Resource Management
Opens in a new window

handbook.gitlab.com
Product Roles - The GitLab Handbook
Opens in a new window

researchgate.net
Vibe Coding: An experiment with test-driven development
Opens in a new window

metacareers.com
Software Engineering Manager - Meta Careers
Opens in a new window

ms.wd5.myworkdayjobs.com
Lead Software Eng- Vice President- Software Engineer
Opens in a new window

amazon.jobs
Manager, Data Science - Job search | Amazon.jobs
Opens in a new window

apify.com
Workday Jobs Scraper: All Postings from Any Career Site - Apify
Opens in a new window

apify.com
Workday Jobs Scraper: All Postings from Any Career Site · Apify
Opens in a new window

resumeadapter.com
Capital One Levels 2026: SWE Pay, IC Ladder & Resume
Opens in a new window

amazon.jobs
Software Development Engineer, Measurement, Ad Tech, and Data
Opens in a new window

amazon.jobs
Software Development Engineer, AWS Marketing, Data Science
Opens in a new window

amazon.jobs
Software Development Engineer, Leo Data Science Platform - Job ID
Opens in a new window

amazon.jobs
Software Development Engineer II, Omnichannel Metrics (OCM)
Opens in a new window

metacareers.com
Data Engineer, Analytics (Ranking, AI) - Meta Careers
Opens in a new window

metacareers.com
Data Engineer, Meta Superintelligence Labs - Meta Careers
Opens in a new window

metacareers.com
Data Engineer, Analytics (Technical Leadership) - Meta Careers
Opens in a new window

metacareers.com
Data Engineer, Product Analytics - Meta Careers
Opens in a new window

careers.google.com
Supply Chain Manager, DC Equipment Supply Chain, Switchgear
Opens in a new window

careers.google.com
Strategic Partner Development Principal Lead, Google Labs
Opens in a new window

amazon.jobs
Software Development Engineer - 2026 - Job ID - Amazon Careers
Opens in a new window

6figr.com
Apple Machine Learning Engineer Salaries 2026 | $259k-$1.2M
Opens in a new window

reddit.com
Apple High ICT3 Offer Evaluation - ML Researcher : r/csMajors
Opens in a new window

levels.fyi
OpenAI PPUs: How OpenAI's unique equity compensation works
Opens in a new window

convergencedallas.ai
Convergence AI Dallas 2026
Opens in a new window

blog.9cv9.com
Top 10 Best Job Description Generator Software To Use in 2026
Opens in a new window

scribd.com
Workday Job and Position Configuration Guide | PDF - Scribd
Opens in a new window

handbook.gitlab.com
Security Roles | The GitLab Handbook
Opens in a new window

handbook.gitlab.com
Data Analytics | The GitLab Handbook
Opens in a new window

uk.indeed.com
Architecture Placement Part 1 Jobs (with Salaries) - Indeed
Opens in a new window

amazon.jobs
Software Development Engineer, Measurement, Ad Tech, and Data
Opens in a new window

amazon.jobs
Software Development Engineer, AWS Analytics Engineering - Job ID
Opens in a new window

amazon.jobs
Job search - Amazon Careers
Opens in a new window

metacareers.com
Data Scientist, Meta Superintelligence Labs (Safety) - Meta Careers
Opens in a new window

metacareers.com
How data scientists lead and drive impact at Meta
Opens in a new window

metacareers.com
Data Scientist, Product - Meta Careers
Opens in a new window

6figr.com
Apple Machine Learning Cupertino Salaries 2026 | $272k-$1.2M
Opens in a new window

interviewkickstart.com
Apple Software Engineer Salary | Interview Kickstart
Opens in a new window

doc.workday.com
Reference: Job Architecture Hub - Workday Documentation
Opens in a new window

handbook.gitlab.com
People Group Roles | The GitLab Handbook
Opens in a new window

6figr.com
Capital One Salaries 2026 | $137k-$647k - 6figr.com
Opens in a new window

boardinfinity.com
Compensation Structure Case Framework - Board Infinity
Opens in a new window

jobtoday.com
128 Best tech government Jobs in North Bergen, New Jersey
Opens in a new window

lensa.com
Director/Managing Director, AI Software Development - Job - Lensa
Opens in a new window

talents.vaia.com
Sr. Distinguished, Software Engineer - Enterprise Data Storage and
Opens in a new window

bebee.com
Compensation Advisor - Hewlett Packard Enterprise - BeBee
Opens in a new window

talents.vaia.com
Cloud Engineer (Software Engineer - Senior) in Radford at CGI
Opens in a new window

employbl.com
People Programs Specialist (Contract) - Crusoe - Employbl
Opens in a new window

bebee.com
Senior Client Services Specialist/Account Manager, Alternative
Opens in a new window

investor.pnc.com
March 11, 2026 - DEF 14A: Definitive proxy statements
Opens in a new window

makingpublic.work
Training Day
Opens in a new window
