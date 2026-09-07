# Feature status — Nonprofit, grants & community

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 311 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 2 | 0 | Native records/view |
| Work items & projects | records | 2 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 4 | 0 | Native records/view |
| Deadlines & reminders | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 7 | 0 | Native records/view |
| Activity & audit trail | audit | 9 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Disaster declaration registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Applicant eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site damage inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency work classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Permanent work classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Force-account labor calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment rate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Procurement evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance reduction coordination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost reasonableness validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project worksheet preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Environmental historic preservation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Documentation request workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Obligation draw tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Closeout audit package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Award and amendment library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget and funding-source control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expenditure ingestion and mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost allowability validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll and time-effort support | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Procurement compliance evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subrecipient cost validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Match and cost-share tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program income accounting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Milestone and deliverable tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drawdown calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment request package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency query and correction workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash receipt reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Award utilization and forecast analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Award agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Indirect rate agreement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Direct cost ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Modified total direct cost base | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Capital expenditure exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subaward threshold exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Participant support exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Indirect cost calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provisional-to-final adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carryforward calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Award ceiling control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drawdown reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sponsor adjustment request | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash recovery tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Award rate analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pipeline | records | 1 | 0 | Native records/view |
| Authoring | records | 1 | 0 | Native records/view |
| Evidence & Budget | records | 1 | 0 | Native records/view |
| Review & Submit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Opportunity | records | 1 | 0 | Native records/view |
| Proposal | records | 1 | 0 | Native records/view |
| Requirement | records | 1 | 0 | Native records/view |
| Source Document | records | 1 | 0 | Native records/view |
| Claim Validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget Line | records | 1 | 0 | Native records/view |
| Reviewer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft Section | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meeting Extract | records | 1 | 0 | Native records/view |
| Submission | records | 1 | 0 | Native records/view |
| Compliance Check | records | 1 | 0 | Native records/view |
| Draft: Go / No-Go Analyst | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Section Drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Claim Auditor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Award budget registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ledger transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll effort linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Original charge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer reason classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Allocability assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benefit-to-award evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ninety-day deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost share treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PI approval workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| High-risk transfer review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Journal entry generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sponsor reporting reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Department award analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sermons | records | 2 | 0 | Native records/view |
| Donations | records | 5 | 0 | Native records/view |
| Members | records | 2 | 0 | Native records/view |
| Volunteers | records | 6 | 0 | Native records/view |
| Prayers | records | 2 | 0 | Native records/view |
| Facilities | records | 2 | 0 | Native records/view |
| Announcements | records | 1 | 0 | Native records/view |
| Attendance | records | 2 | 0 | Native records/view |
| Small Groups | records | 1 | 0 | Native records/view |
| Counseling | records | 1 | 0 | Native records/view |
| Outreach | records | 3 | 0 | Native records/view |
| AI History | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Webhooks | integration | 2 | 0 | Provider request records only |
| Sermon Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Donation Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prayer Guidance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member Engagement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Event Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outreach Strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sermon QA Bot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volunteer Burnout Alert | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prayer Categorization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility Utilization Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Powered time matching engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reputation trustworthiness scoring | records | 1 | 0 | Native records/view |
| Predictive demand forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi modal intake voice photo | records | 1 | 0 | Native records/view |
| Blockchain backed ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Peer review certification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Skill match | records | 1 | 0 | Native records/view |
| Credit valuation | records | 1 | 0 | Native records/view |
| Onboarding interview | records | 1 | 0 | Native records/view |
| Dispute mediation | records | 1 | 0 | Native records/view |
| Reputation analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Governance proposal | records | 1 | 0 | Native records/view |
| Skill gap | records | 1 | 0 | Native records/view |
| Listing from description | records | 1 | 0 | Native records/view |
| Impact report | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Reciprocity balance | records | 1 | 0 | Native records/view |
| Visit Tracking | records | 1 | 0 | Native records/view |
| Inventory | records | 3 | 0 | Native records/view |
| Distributions | records | 2 | 0 | Native records/view |
| Donors | records | 3 | 0 | Native records/view |
| Food Drives | records | 1 | 0 | Native records/view |
| Delivery Routes | records | 1 | 0 | Native records/view |
| Warehouses | records | 2 | 0 | Native records/view |
| Partners | records | 2 | 0 | Native records/view |
| Grants | records | 5 | 0 | Native records/view |
| Fleet | records | 2 | 0 | Native records/view |
| AI Advanced | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Distribution Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud Pattern Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proactive Need Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Donation Appeal Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volunteer Shift Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nutritional Balance Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expiration Risk Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Grant Application Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Community Need Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Food Package Builder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Donor Retention Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pantry allocation | records | 1 | 0 | Native records/view |
| Campaigns | records | 1 | 0 | Native records/view |
| Goal Setting | records | 1 | 0 | Native records/view |
| Email Generator | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Social Media | records | 1 | 0 | Native records/view |
| Thank You Letters | records | 1 | 0 | Native records/view |
| Budget Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Impact Reports | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| A/B Testing | records | 1 | 0 | Native records/view |
| Backlog Tools | records | 2 | 0 | Native records/view |
| Donor Fatigue | records | 1 | 0 | Native records/view |
| Donor Lifetime Value | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Grant Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Event Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Major Donor Cultivation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volunteer Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic grant prospecting scanning grant | records | 1 | 0 | Native records/view |
| donor engagement scoring with real time | records | 1 | 0 | Native records/view |
| event roi simulator predicting attendanc | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi stakeholder survey synthesis colle | records | 1 | 0 | Native records/view |
| peer to peer fundraising team builder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| government procurement advisor scanning | records | 1 | 0 | Native records/view |
| donor lifetime value prediction endpo | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| major donor cultivation plan generato | records | 1 | 0 | Native records/view |
| volunteer skill matching ai peermatch | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| event demand forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited notifications no dedicated modul | records | 1 | 0 | Native records/view |
| webhook dispatch for donor events | integration | 1 | 0 | Provider request records only |
| file upload pipeline for donor | records | 1 | 0 | Native records/view |
| payment processing surfaced beyond st | integration | 1 | 0 | Provider request records only |
| real time donor activity feed | records | 1 | 0 | Native records/view |
| Predictions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Organizations | records | 1 | 0 | Native records/view |
| Proposals | records | 1 | 0 | Native records/view |
| Budget Builder | records | 1 | 0 | Native records/view |
| Impact Measurer | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Funder Research | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Proposal Outline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gap Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Funder Relations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Proposal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Improve Text | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Executive Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Match Grants | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review Proposal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Funder fit gap analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic funder discovery scanning founda | records | 1 | 0 | Native records/view |
| proposal impact simulator modeling lives | records | 1 | 0 | Native records/view |
| peer proposal analyzer extracting succes | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi funder strategy planner diversifyi | records | 1 | 0 | Native records/view |
| compliance audit prep co pilot generatin | records | 1 | 0 | Native records/view |
| funder relationship crm with ai recommen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| real time funder deadline change | records | 1 | 0 | Native records/view |
| proposal style consistency enforcer a | records | 1 | 0 | Native records/view |
| rejection reason classifier for past | records | 1 | 0 | Native records/view |
| backend is monolithic no routes folder | records | 1 | 0 | Native records/view |
| webhook receivers for grant portal | integration | 1 | 0 | Provider request records only |
| real time collaboration on proposals | records | 1 | 0 | Native records/view |
| file upload pipeline for supporting | records | 1 | 0 | Native records/view |
| e signature integration for proposal | integration | 1 | 0 | Provider request records only |
| Programs | records | 1 | 0 | Native records/view |
| Shifts | records | 1 | 0 | Native records/view |
| Incidents | records | 1 | 0 | Native records/view |
| Grant Tracking | records | 1 | 0 | Native records/view |
| AI Predictive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agentic volunteer dispatch | records | 1 | 0 | Native records/view |
| RAG over organizational playbooks | records | 1 | 0 | Native records/view |
| Donor engagement scoring | records | 1 | 0 | Native records/view |
| Field photo upload + tagging | records | 1 | 0 | Native records/view |
| Compliance audit agent | records | 1 | 0 | Native records/view |
| Cases exist without `/case | records | 1 | 0 | Native records/view |
| Donations tracked but no `/donation | records | 1 | 0 | Native records/view |
| Programs without `/program | records | 1 | 0 | Native records/view |
| Shifts without `/shift | records | 1 | 0 | Native records/view |
| No multi | records | 1 | 0 | Native records/view |
| No SMS/bulk communication or notification layer | records | 1 | 0 | Native records/view |
| No reporting export (PDF/CSV for board meetings and funders) | records | 1 | 0 | Native records/view |
| No webhooks or third | integration | 1 | 0 | Provider request records only |
| No file/document storage for case attachments | records | 1 | 0 | Native records/view |
| No RBAC beyond basic auth (no role separation | records | 1 | 0 | Native records/view |
| Translate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bulk SMS | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Field Photos | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Case Triage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volunteer Dispatch | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Grant Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beneficiary Needs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resource Allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Case Resolution Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Donation Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shift Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| skills to opportunity matching engine with explainability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| impact report auto generation for grant submissions | records | 1 | 0 | Native records/view |
| volunteer hour tracking with verification workflow | records | 1 | 0 | Native records/view |
| background check integrations sterling checkr | integration | 1 | 0 | Provider request records only |
| mobile companion app for shift check in | records | 1 | 0 | Native records/view |
| vision based volunteer id verification | records | 1 | 0 | Native records/view |
| conversational onboarding bot for volunteers | records | 1 | 0 | Native records/view |
| volunteer profile crud backend only via ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| opportunity crud backend | records | 1 | 0 | Native records/view |
| shift schedule database tables | records | 1 | 0 | Native records/view |
| notifications subsystem sms email reminders | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| reporting export endpoints | records | 1 | 0 | Native records/view |
| background check compliance tracking | records | 1 | 0 | Native records/view |
| donor funder reporting integration | integration | 1 | 0 | Provider request records only |
| multi organization tenancy | records | 1 | 0 | Native records/view |
| Match volunteers | records | 1 | 0 | Native records/view |
| Recommend opportunities | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Skills extract | records | 1 | 0 | Native records/view |
| Opportunity description | records | 1 | 0 | Native records/view |
| Shift schedule | records | 1 | 0 | Native records/view |
| Retention risk | records | 1 | 0 | Native records/view |
| Training plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Feedback summary | records | 1 | 0 | Native records/view |
| Recruitment message | records | 1 | 0 | Native records/view |
| Recognition note | records | 1 | 0 | Native records/view |
| Gallery | records | 1 | 0 | Native records/view |
| Applications | records | 1 | 0 | Native records/view |
| Investments | records | 1 | 0 | Native records/view |
| Admin | records | 1 | 0 | Native records/view |
| Messaging | records | 1 | 0 | Native records/view |
| Bookmarks | records | 1 | 0 | Native records/view |
| Leaderboard | records | 1 | 0 | Native records/view |
| Donation matching | records | 2 | 0 | Native records/view |
| Grant proposal writer | records | 2 | 0 | Native records/view |
| Donor segmentation | records | 2 | 0 | Native records/view |
| Content moderation | records | 2 | 0 | Native records/view |
| Payment processing | integration | 2 | 0 | Provider request records only |
| Recurring donations | records | 2 | 0 | Native records/view |
| Volunteer management | records | 2 | 0 | Native records/view |
| Grant doc versioning | records | 2 | 0 | Native records/view |
| Tax receipt generation | records | 2 | 0 | Native records/view |
| Mobile app stub | records | 2 | 0 | Native records/view |
| Calculator | records | 1 | 0 | Native records/view |
| Coverage | records | 1 | 0 | Native records/view |
| Financial reports | records | 1 | 0 | Native records/view |
| Consultation | records | 1 | 0 | Native records/view |
| Enrollment | records | 1 | 0 | Native records/view |
| Claims | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policies | records | 1 | 0 | Native records/view |
| Submit claim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment | records | 1 | 0 | Native records/view |
| Claims prediction | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Coverage recommendation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Claim status chatbot | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Claim risk scorer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Policy doc management | records | 2 | 0 | Native records/view |
| Multi policy holder | records | 2 | 0 | Native records/view |
| Renewal tracking | records | 2 | 0 | Native records/view |
| Compliance audit trail | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Provider directory | records | 2 | 0 | Native records/view |
| Broker portal | records | 2 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 311 feature pages were visited in the browser; 309 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 156 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

156 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
