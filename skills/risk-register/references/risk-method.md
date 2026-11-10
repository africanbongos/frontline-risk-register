# Risk Method Reference

How a seasoned safety function assesses, rates and controls risk, and how it proves the controls work. Written for Australian model WHS law first, with ISO 45001, ICMM and UK/NZ equivalents noted.

---

## 1. Hierarchy of controls

The duty is to eliminate risk so far as is reasonably practicable (SFAIRP), and if that is not reasonably practicable, to minimise it SFAIRP, working down the hierarchy. Model WHS Regulations (reg 36) and the model Code "How to manage work health and safety risks" set this out. ISO 45001:2018 clause 8.1.2 uses the same order: eliminate, substitute, engineering controls and reorganisation of work, administrative controls including training, PPE.

| Level | Definition | Examples |
|---|---|---|
| Elimination | Remove the hazard or the task entirely. Most effective. | Design out roof access by putting plant at ground level; buy pre-cut material so no on-site cutting; stop manual cash handling. |
| Substitution | Replace with something less hazardous. | Water-based for solvent-based product; smaller, lighter packaging; electric forklift for LPG indoors; non-engineered-stone benchtops. |
| Isolation | Separate people from the hazard by distance or physical barrier. | Fenced pedestrian walkways; guarded machine enclosure; exclusion zone with hard barrier under a lift; locked switch room. |
| Engineering | Physical change to plant, process or environment that reduces risk at source. | Interlocked guards; on-tool dust extraction; vacuum lifters; proximity detection; speed limiters; edge protection. |
| Administrative | Procedures, training, signage, rosters, permits, supervision. | Permit to work; SWMS; job rotation; warning signs; induction. |
| PPE | Equipment worn by the person. | Harness, respirator, hearing protection, gloves, hi-vis. |

Principles a Head of Safety holds the line on:
- Administrative controls and PPE are the least effective because they do not change the hazard and depend on human behaviour and supervision. Use them only to supplement higher controls, as short-term interim measures, or as a last resort. (Model Code "How to manage WHS risks"; SafeWork NSW lists PPE as "the least effective way to manage risks".)
- A risk with fatal potential controlled only by admin and PPE is a gap, regardless of its score. Flag it.
- Combine controls. One engineering control plus supporting admin (inspection, training) beats three admin controls.
- Training, procedures, inspections and audits are supports or verification, not the control itself (ICMM). Do not list "training" as the control for a fatal risk.
- For hazards that can cause death or serious injury, prefer controls that reduce the consequence or remove exposure over controls that only reduce likelihood (model Code).

Sources:
- https://worksafe.qld.gov.au/__data/assets/pdf_file/0022/72634/how-to-manage-work-health-and-safety-risks-cop-2021.pdf
- https://www.safework.nsw.gov.au/__data/assets/pdf_file/0006/446028/hierarchy-of-controls-SW09182.pdf
- https://blog.auditortrainingonline.com/blog/iso-45001-clause-8-1-2

---

## 2. Risk matrix (5x5) best practice

Note: the model Code does not prescribe a matrix. Matrices are an organisational tool; the legal test is SFAIRP. Use the matrix to prioritise, never to justify stopping short of reasonably practicable controls.

### Likelihood

| Rating | Descriptor | Guidance (use the one that fits the exposure) |
|---|---|---|
| 5 | Almost certain | Expected to occur in most circumstances; happens more than once a year at this site; has happened repeatedly here. |
| 4 | Likely | Will probably occur; about once a year at this site; has happened here. |
| 3 | Possible | Might occur; once in 1 to 10 years at this site; has happened in this organisation or industry recently. |
| 2 | Unlikely | Could occur but not expected; once in 10 to 100 years; has happened in the industry. |
| 1 | Rare | May occur only in exceptional circumstances; less than once in 100 years; not known in the industry. |

### Consequence (people)

| Rating | Descriptor | People outcome |
|---|---|---|
| 1 | Insignificant | First aid only, no lost time. |
| 2 | Minor | Medical treatment injury or restricted duties; no lost shift beyond day of injury. |
| 3 | Moderate | Lost time injury; full recovery expected. |
| 4 | Major | Permanent disability or life-altering injury or illness (amputation, serious fracture with impairment, occupational disease). Notifiable serious injury. |
| 5 | Catastrophic | Single or multiple fatality. |

### Rating bands (likelihood x consequence, scores 1 to 25)

| Score | Band | Response |
|---|---|---|
| 15 to 25 | Extreme / Critical | Stop or do not start until controls reduce risk. Executive ownership. Critical controls defined and verified. |
| 10 to 14 | High | Senior manager owner; action plan with dates; controls verified at defined frequency. |
| 5 to 9 | Medium | Manager owner; manage by routine procedures; monitor. |
| 1 to 4 | Low | Manage by routine; review at scheduled review. |

Rule overrides (put these in the method, not left to judgement):
- Any risk with a credible consequence of 5 (fatality) is treated as a critical risk and managed by critical control management (section 4), regardless of its likelihood score. A 5 x 1 = 5 "Medium" fatality risk is still a fatal risk.
- Rate the worst credible consequence, not the worst conceivable and not the most common outcome.

### Common pitfalls (and what to check)

1. Residual risk scored lower without control evidence. Residual can only drop for controls that exist and are verified as effective. If the control is "Not verified" or "Ineffective", residual equals inherent.
2. Consequence reduced by administrative controls or PPE. Procedures, training and signage change likelihood, not the energy involved. A fall from 6 m is still a fatality consequence after a toolbox talk. Consequence can only fall when the energy or exposure is physically changed (elimination, substitution, isolation, engineering, for example lowering work height or limiting speed).
3. Averaging. Do not average ratings across sites, tasks or assessors, and do not average multiple hazards into one line. Report the worst credible case and the spread.
4. Likelihood anchored on "it has never happened here". Use industry data. Low local incident counts often mean low reporting.
5. Matrix used to close the conversation. A "Low" rating does not mean further reasonably practicable controls are optional.
6. Inconsistent scoring between assessors. Calibrate with worked examples and peer review for anything rated High or above.
7. Too many risks rated "Extreme" so nothing is. Keep the register focused on hazards, not tasks, and group duplicates.

Sources:
- https://worksafe.qld.gov.au/__data/assets/pdf_file/0022/72634/how-to-manage-work-health-and-safety-risks-cop-2021.pdf (likelihood descriptor "Certain to occur, expected to occur in most circumstances"; no matrix prescribed)
- Bands and descriptors above are common industry practice consistent with ISO 31000; they are not a regulatory requirement.

---

## 3. SFAIRP, ALARP and "reasonably practicable"

- Model WHS Act s18: reasonably practicable means that which is, or was at a particular time, reasonably able to be done to ensure health and safety, taking into account and weighing up all relevant matters including:
  - (a) the likelihood of the hazard or risk concerned occurring;
  - (b) the degree of harm that might result from the hazard or the risk;
  - (c) what the person concerned knows, or ought reasonably to know, about the hazard or risk and ways of eliminating or minimising it;
  - (d) the availability and suitability of ways to eliminate or minimise the risk;
  - (e) after assessing the extent of the risk and the available ways of eliminating or minimising it, the cost associated with those ways, including whether the cost is grossly disproportionate to the risk.
- Cost is considered last and only after (a) to (d). It can only rule out a control if it is grossly disproportionate to the risk. "We could not afford it" is not the test. Capacity of the individual business to pay is not a relevant factor (SWA Interpretive Guideline).
- "Ought reasonably to know" includes industry knowledge: codes of practice, regulator guidance, published incidents and standards. If a control is common practice in your industry, it is very hard to argue it was not reasonably practicable.
- SFAIRP vs ALARP: ALARP (as low as reasonably practicable, UK HSE and many engineering standards) asks whether risk has been reduced to a level where further reduction is grossly disproportionate. SFAIRP (Australian WHS law, also UK Health and Safety at Work Act wording) focuses on whether all reasonably practicable controls have been implemented. In practice: under SFAIRP, start from the controls, not from a tolerable risk number. Engineers Australia guidance notes a target-risk ALARP approach does not by itself demonstrate SFAIRP compliance.
- NZ: Health and Safety at Work Act 2015 s22 uses the same five factors.

Sources:
- https://classic.austlii.edu.au/au/legis/nsw/consol_act/whasa2011218/s18.html
- https://www.safeworkaustralia.gov.au/system/files/documents/1702/interpretive_guideline_-_reasonably_practicable.pdf
- https://www.engineersaustralia.org.au/sites/default/files/resource-files/2017-01/cs_wong_-_alarp_vs_sfairp_whs_legislation.pdf

---

## 4. Critical control management (ICMM)

ICMM published "Health and Safety Critical Control Management: Good Practice Guide" in 2015 (with an Implementation guide). ICMM released a consolidated edition in 2026 that replaces both; the core method is unchanged.

### Definitions (ICMM 2015)
- Material unwanted event (MUE): an unwanted event where the potential or real consequence exceeds a threshold defined by the company (typically fatality or multiple fatalities).
- Control: an act, object (engineered) or system (combination of act and object) intended to prevent or mitigate an unwanted event.
- Critical control: a control that is crucial to preventing the event or mitigating the consequences of the event. The absence or failure of a critical control would significantly increase the risk despite the existence of the other controls. A control that prevents more than one unwanted event or mitigates more than one consequence is normally classified as critical.
- Performance requirements (performance standard): the standard or criteria the critical control has to perform to, to meet its objective.
- Verification: the process of checking the extent to which the performance requirements set for a critical control are being met in practice.
- ICMM 2026 frames critical controls against "fatal hazards" and "unwanted events" and is explicit that training, competence, procedures, maintenance and risk assessments are support activities, and checks, inspections and audits are verification activities, not controls.

### Critical risk vs critical control
- Critical risk (or fatal hazard / MUE): the hazard and unwanted event with fatal potential, for example "loss of control of mobile plant", "fall from height", "contact with energised conductor".
- Critical control: the specific barrier that, if it failed, would leave people exposed, for example "physical separation of pedestrians from mobile plant", "guardrail at open edge", "isolation and test for dead".

### Selecting critical controls (ICMM step 4 questions)
- Is it crucial to preventing the event or minimising consequences?
- Is it the only control, or is it backed up?
- Would its absence or failure significantly increase the risk despite other controls?
- Does it address multiple causes or mitigate multiple consequences?
- Keep the list short. "More can be less": many critical controls are harder to implement and verify. 3 to 6 per critical risk is typical.
- Prefer object or engineered controls; people-dependent controls are allowed but less reliable.

### The nine ICMM steps
1. Plan the process. 2. Identify fatal hazards and unwanted events. 3. Identify controls. 4. Select critical controls. 5. Define performance (objective, performance requirements, support activities, verification activities). 6. Assign accountability (owner for each risk, control and verification). 7. Implement. 8. Verify and take corrective action. 9. Evaluate, improve and report.

### Performance standard template (one per critical control)
- Objective: what the control must achieve ("prevent pedestrian entry into operating radius of mobile plant").
- Performance requirements: measurable criteria ("hard barrier at least 1 m high, continuous, no gaps over 300 mm; gates interlocked or controlled").
- Support activities: design standard, inspection, maintenance, training.
- Verification: who (supervisor, owner, independent), how (field observation, test, record check), how often, evidence (checklist, photo, test record), and what happens on failure (stop work, escalate).
- Accountable owner.

### Bow-tie lite method
For each critical risk, a one-page bow-tie:
1. Hazard (the energy): e.g. moving forklift.
2. Top event: the moment control of the hazard is lost, e.g. "forklift contacts pedestrian".
3. Threats (causes), left side: 3 to 6, e.g. pedestrian in forklift aisle, operator vision obstructed, excess speed, untrained operator.
4. Preventive controls, mapped to each threat: e.g. segregated walkways, speed limiter, licensed operator with access control, proximity detection.
5. Consequences, right side: e.g. crush fatality, fractures.
6. Mitigating controls, mapped to each consequence: e.g. emergency response and first aid, speed limit reduces impact energy.
7. Mark critical controls (usually those on several lines or the only barrier on a line).
8. Note escalation factors (things that defeat a control, e.g. night shift, peak volume) only where material.
Lite rules: no more than one page; controls must be nouns you can inspect, not "be aware"; each critical control links to a performance standard.

Sources:
- https://alustory.international-aluminium.org//wp-content/uploads/2022/03/guidance_ccm-good-practice.pdf (ICMM 2015 guide)
- https://pimcore.icmm.com/website/publications/pdfs/health-and-safety/2026/guidance_ccm-gpg.pdf (ICMM 2026 edition)

---

## 5. Control effectiveness rating

Rate every control in the register. Residual risk follows from this rating, not the other way round.

| Rating | Criteria | Effect on residual risk |
|---|---|---|
| Effective | Control exists, is designed to the performance requirement, and verification within the defined frequency shows it is in place and working. Evidence is dated and retrievable. No failures in recent verifications, or failures were isolated and corrected. | May be credited in full. |
| Partially effective | Control exists but verification found gaps: some locations or shifts non-compliant, design falls short of standard, or verification frequency missed. Or an incident shows it worked only partly. | Credit partially (typically one likelihood step at most). Action required with owner and date. |
| Ineffective | Control absent, defeated, or verification found it not working; or an incident occurred where it should have prevented or mitigated the event. | No credit. Residual equals inherent. Immediate action; consider stopping the task if critical. |
| Not verified | Control is claimed but no verification has been done, or evidence is out of date or not retrievable. | No credit. Treat as ineffective for rating purposes until verified. |

Tests a reviewer applies:
- Can I see it, test it, or read a dated record of it?
- Does it match the hierarchy level claimed (a "barrier" that is a sign is admin)?
- Was it in place on night shift, for contractors, at the furthest site?
- Has an incident or near miss in the last 12 months shown it failing?

Source: method is practitioner synthesis aligned to ICMM verification principles (section 4) and the model Code requirement to review controls that are not effective.

---

## 6. Psychosocial hazards (SWA Model Code of Practice: Managing psychosocial hazards at work, 2022)

The Code lists 14 common psychosocial hazards. Model WHS Regulations (amended 2022) require PCBUs to manage psychosocial risks using the hierarchy, considering duration, frequency and severity of exposure, how hazards interact, work design, systems of work and the physical environment.

| Hazard | Example controls (from or consistent with the Code) |
|---|---|
| 1. Job demands (high or low) | Schedule non-urgent work for quieter periods; plan shifts so workers recover between high-demand periods; set realistic deadlines and staffing. |
| 2. Low job control | Match autonomy to skill and experience; let workers control workflow and pace where possible; consult on how work is done. |
| 3. Poor support | Train workers on tasks and tools; give supervisors manageable workloads and time to support; access to help. |
| 4. Lack of role clarity | Position descriptions with key tasks and expectations; single immediate supervisor; clear reporting lines. |
| 5. Poor organisational change management | Consult before changes take effect; check workers understand new responsibilities after a restructure; assess WHS impact of change. |
| 6. Inadequate reward and recognition | Fair, transparent recognition including teamwork; prompt, specific feedback. |
| 7. Poor organisational justice | Unbiased, transparent policies developed with workers; ways to report concerns and appeal decisions. |
| 8. Traumatic events or material | Rotate roles to limit exposure; screening software or flagging to limit inadvertent exposure to distressing content; post-incident support. |
| 9. Remote or isolated work | Effective communication systems; buddy systems and movement records; check-in procedures. |
| 10. Poor physical environment | Address noise, temperature and lighting; maintain equipment so it is not unsafe, noisy or vibrating. |
| 11. Violence and aggression | Security measures (CCTV, fixed or portable alarms, tested regularly); physical separation from the public (high counters, screens). |
| 12. Bullying | Control underlying causes (high demands, low support, unclear roles) as well as the behaviour; clear policy and reporting and response process. |
| 13. Harassment including sexual harassment | Safe environment during travel, conferences, off-site and client premises; reporting channels; prevention duty (positive duty under Sex Discrimination Act since Dec 2022). |
| 14. Conflict or poor workplace relationships and interactions | Policies and processes to handle reports of unacceptable behaviour; early resolution; manager capability. |

Practitioner notes:
- Hazards interact and compound (high demands plus low control plus poor support is the classic high-strain combination). Assess combinations, not single hazards.
- Training workers in "resilience" is not a control for a work design hazard. Fix the work.
- Data sources: consultation, surveys, exit interviews, workers' compensation, absenteeism, overtime, complaints and grievances.

Sources:
- https://www.safeworkaustralia.gov.au/sites/default/files/2022-08/model_code_of_practice_-_managing_psychosocial_hazards_at_work_25082022_0.pdf

---

## 7. Risk register review triggers

Model WHS Regulations (reg 38) require control measures to be reviewed, and if necessary revised:
- when the control measure does not control the risk it was implemented to control so far as is reasonably practicable;
- before a change at the workplace that is likely to give rise to a new or different health and safety risk that the measure may not effectively control;
- if a new relevant hazard or risk is identified;
- if the results of consultation indicate a review is necessary;
- if a health and safety representative requests a review (where they reasonably believe one of the above has occurred and it was not adequately reviewed).

Operational triggers a mature system adds:
- After any incident or near miss linked to the risk, and immediately after any HiPo/SIF-potential event.
- After a control verification rates a critical control Ineffective or Not verified.
- New information: regulator safety alert, industry fatality, new code or standard, exposure monitoring result.
- Change: new plant, process, substance, layout, contractor, roster, organisational restructure, new site.
- Worker reports or complaints, including informal ones (psychosocial Code).
- Scheduled: critical and high risks at least every 12 months (many organisations review critical risks quarterly); medium and low every 2 to 3 years.

Sources:
- https://worksafe.qld.gov.au/__data/assets/pdf_file/0022/72634/how-to-manage-work-health-and-safety-risks-cop-2021.pdf
- https://www.safeworkaustralia.gov.au/sites/default/files/2022-08/model_code_of_practice_-_managing_psychosocial_hazards_at_work_25082022_0.pdf
