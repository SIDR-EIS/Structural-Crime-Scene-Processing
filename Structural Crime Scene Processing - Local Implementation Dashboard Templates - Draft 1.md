# Structural Crime Scene Processing

## Local Implementation Dashboard Templates

## Draft 1

---

## Purpose

This document turns the Structural Crime Scene Processing metric and audit logic into practical local reporting templates.

It is written for:

- command sponsors
- implementation owners
- audit leads
- training leads
- patrol and investigative supervisors
- scene-unit supervisors
- laboratory supervisors
- downstream legal supervisors
- steering-group members
- data and quality personnel building local reporting surfaces

Its job is to answer a specific question:

how should an institution build local dashboards that show whether the method is actually being used, whether transfer integrity is improving, where fragility remains, and when leadership should intervene without falling back into comfort metrics.

---

## What This Document Does

This document provides:

- dashboard design rules
- local dashboard templates for different leadership levels
- metric definitions and indicator logic
- narrative-strip templates
- review cadence guidance
- escalation triggers
- dashboard failure warnings

It is not:

- a software implementation manual
- a BI tool specification
- a substitute for audit packets
- a substitute for live-scene observation
- a request to measure everything that moves

The point of a dashboard in this project is not to create more charts.

The point is to make structural adoption, drift, and transfer quality visible quickly enough that leadership can act before the old model quietly reasserts itself.

---

## Why Dashboard Templates Are Needed

Most organizations already have dashboards.

That is not the problem.

The problem is that most existing dashboards overmeasure:

- volume
- speed
- neatness
- low visible friction
- administrative closure

and undermeasure:

- bounded uncertainty
- transferability
- owned residue
- false stability
- drift under pressure
- hidden dependence on oral rescue

Without explicit dashboard templates, institutions usually do one of three things.

First, they bolt a few reform terms onto an old productivity dashboard.

Second, they generate so many indicators that nobody knows what matters.

Third, they create a beautiful reporting surface that hides the exact drift it was supposed to expose.

These templates exist to prevent that.

---

## Relationship to the Existing Project Stack

Use this document with:

- `Structural Crime Scene Processing - Leadership Implementation Playbook - Draft 1.md`
- `Structural Crime Scene Processing - Live Implementation Audit Packets - Draft 1.md`
- `Structural Crime Scene Processing - Live-Scene and Live-Review Observation Checklists - Draft 1.md`
- `Structural Crime Scene Processing - Instructor Scoring Sheets and Thresholds - Draft 1.md`
- `Structural Crime Scene Processing - Courtroom Transfer and Legal Review Scenarios - Instructor Scoring Sheets and Thresholds - Draft 1.md`
- `Structural Crime Scene Processing - Legal Scenario Pass-Fail Signoff Forms - Draft 1.md`
- `Structural Crime Scene Processing - Mixed Investigator-Prosecutor Calibration Packets - Draft 1.md`
- `Structural Crime Scene Processing - Instructor Calibration Packets - Draft 1.md`

The playbook says what leadership should measure.

The observation and audit documents say how to see the work.

The scoring, signoff, and calibration documents say how training and downstream legal readiness are judged.

This document tells leadership how to surface those judgments in a recurring operational reporting layer.

---

## Dashboard Design Rule

Every dashboard in this project should help leadership answer four questions:

- Is the method actually being used?
- Is it reducing uncertainty more honestly?
- Is it increasing transferability?
- Is it revealing false stability rather than hiding it?

If a dashboard cannot answer those questions, it is probably measuring comfort instead of transformation.

---

## Dashboard Principles

Every local dashboard built from this document should follow ten principles.

### Principle 1: Measure structural behavior, not narrative confidence

Prefer indicators about:

- closure criteria
- owned deferrals
- transfer integrity
- bounded legal review
- observation coverage
- audit disposition

over indicators about:

- confidence
- narrative polish
- perceived completeness

### Principle 2: Always show denominator and sample size

A percentage without a denominator often flatters the rollout.

Show counts and sampling base whenever possible.

### Principle 3: Separate secure from fragile

Do not report all positive appearance as success.

A fragile gain is not the same as a secure gain.

### Principle 4: Keep drift visible

Every dashboard should reserve space for:

- regressions
- unresolved high-risk findings
- repeat fault lines

not only for positive motion.

### Principle 5: Show transfer, not just production

If the dashboard shows how much work was produced but not whether the work survives handoff, the reporting layer is incomplete.

### Principle 6: Preserve exception classes

Repeated exceptions often reveal the real system architecture.

Do not flatten them into one generic "issue count."

### Principle 7: Use short narrative strips, not long prose

Dashboards need a concise human explanation field, but they should not rely on narrative to do the work of the indicators.

### Principle 8: Do not let tools become proxy success

Tool usage frequency should never stand in for method adoption.

### Principle 9: Role-specific dashboards should roll upward cleanly

Patrol, scene, detective, lab, training, legal, and audit dashboards should feed higher-level views without losing the warning signal.

### Principle 10: Make the recovery path visible

A good dashboard does not only show what is wrong.

It shows:

- owner
- corrective action
- next review date

for high-risk items.

---

## Dashboard Status Bands

Use four status bands across the templates:

- `Green`
- `Amber`
- `Red`
- `Gray`

These mean:

### Green

The indicator is strong enough that the current stage may continue without special intervention.

### Amber

The indicator is present but fragile, inconsistent, or at risk of drift.

### Red

The indicator shows material weakness, active drift, or structurally unsafe conditions.

### Gray

The indicator is not yet sufficiently measured or the sample is too thin to judge.

The point of `Gray` is to prevent false precision.

Do not force a color where the evidence is not mature enough to support one.

---

## Data Source Families

These dashboard templates assume six major data-source families:

- live observation records
- audit packet outputs
- training and scoring outputs
- signoff and remediation outputs
- package and handoff review outputs
- leadership review and corrective-action ledgers

Each dashboard should state clearly which of these sources feed each section.

If the data source for a tile is unclear, the tile will quickly become political instead of diagnostic.

---

## Metric Families

Use the following families to organize the dashboard layer.

### Family A. Method Adoption

These metrics answer:

- are people actually using the method
- are core documents meaning-bearing
- are structural questions showing up in the work

### Family B. Transfer Integrity

These metrics answer:

- can the work survive handoff
- is oral rescue declining
- are packages intelligible without live narration

### Family C. Boundedness and Honesty

These metrics answer:

- are unresolveds still visible
- are deferrals owned
- is legal and supervisory language staying bounded

### Family D. Training and Certification

These metrics answer:

- are learners improving
- are thresholds credible
- is remediation functioning

### Family E. Specialist Alignment

These metrics answer:

- are lab and downstream legal roles strengthening the method or weakening it

### Family F. Drift and Recovery

These metrics answer:

- what is regressing
- what repeat fault lines keep appearing
- whether corrective action is actually closing those gaps

---

## Core Metric Definitions

Use these definitions consistently across templates.

### 1. Explicit Closure Rate

Question:

- how often does the scene or phase package show a visible closure criterion

Suggested construction:

- numerator: audited packages with explicit closure criterion
- denominator: audited packages in the reporting window

### 2. Named Deferral Ownership Rate

Question:

- how often do live unresolveds have named owners and review points

Suggested construction:

- numerator: reviewed unresolved items with named owner and due point
- denominator: reviewed unresolved items total

### 3. Transfer-Ready Package Rate

Question:

- how often can a downstream reader interpret the package without oral rescue

Suggested construction:

- numerator: sampled packages judged transfer-ready
- denominator: sampled packages total

### 4. Oral Rescue Dependency Rate

Question:

- how often did a sampled package require live explanation to become usable

Suggested construction:

- numerator: sampled packages needing material oral rescue
- denominator: sampled packages total

### 5. Time-in-State Visibility Rate

Question:

- how often can the team show current state and expected next transition

Suggested construction:

- numerator: observed cases with visible current state and next transition
- denominator: observed cases total

### 6. Premature Category Closure Flag Rate

Question:

- how often are scenes, packages, or legal products showing premature category closure

Suggested construction:

- numerator: events or files with category-closure flag
- denominator: sampled events or files total

### 7. Structural Question Discipline Rate

Question:

- how often are supervisors using state, closure, anchor, residue, and ownership questions

Suggested construction:

- numerator: observed supervisory events with structural question pattern present
- denominator: observed supervisory events total

### 8. Ranked Collection Integrity Rate

Question:

- how often is collection visibly ordered by discriminating value rather than habit

Suggested construction:

- numerator: observed technician events with ranked collection logic present
- denominator: observed technician events total

### 9. Live Hypothesis Integrity Rate

Question:

- how often do detectives or legal reviewers preserve more than one live possibility where the structure requires it

Suggested construction:

- numerator: sampled events with lawful live-hypothesis handling
- denominator: sampled relevant events total

### 10. Lab Structural Intake Rate

Question:

- how often does the lab treat submissions as structural requests rather than routine service orders

Suggested construction:

- numerator: reviewed lab intakes with structural reading present
- denominator: reviewed lab intakes total

### 11. Null Humility Integrity Rate

Question:

- how often are nulls reported without overstatement

Suggested construction:

- numerator: sampled lab outputs with bounded null posture
- denominator: sampled lab outputs total

### 12. Downstream Boundedness Rate

Question:

- how often do legal outputs preserve anchor logic, lawful residue, and bounded sequence

Suggested construction:

- numerator: sampled legal outputs rated bounded
- denominator: sampled legal outputs total

### 13. Severe Overclaim Event Count

Question:

- how many severe downstream rhetorical-closure or package-rewrite events occurred in the reporting window

Suggested construction:

- count only events meeting severe override or audit-trigger criteria

### 14. Pass Rate

Question:

- how many assessed learners or teams received a clear pass

Suggested construction:

- numerator: clear passes
- denominator: completed signoff decisions

### 15. Conditional Pass Rate

Question:

- how many learners or teams were usable only under restrictions

Suggested construction:

- numerator: pass with conditions
- denominator: completed signoff decisions

### 16. Remediation Completion Rate

Question:

- how often are assigned remediations actually completed and re-reviewed

Suggested construction:

- numerator: remediation plans completed with evidence
- denominator: remediation plans due in the reporting window

### 17. Calibration Convergence Rate

Question:

- how often are calibration sessions ending in lawful recorded convergence

Suggested construction:

- numerator: calibration packets with achieved or partial lawful convergence
- denominator: calibration packets run

### 18. Repeat Fault-Line Count

Question:

- how many fault lines have appeared in two or more consecutive review windows

Suggested construction:

- count recurring items, not total findings

### 19. Corrective-Action Closure Rate

Question:

- how many assigned corrective actions closed on time with evidence

Suggested construction:

- numerator: corrective actions closed on time with evidence
- denominator: corrective actions due in window

### 20. High-Risk Drift Indicator Count

Question:

- how many red-level drift indicators are currently open

Suggested construction:

- count all open red indicators requiring leadership attention

---

## Metrics Leadership Should Not Overvalue

Do not place these on the primary rollout dashboard unless they are explicitly contextualized as secondary:

- evidence count
- report speed alone
- scene release speed alone
- low escalation count by itself
- number of documents completed
- tool usage frequency
- volume of charts or visualizations produced
- number of training hours without outcome context

These indicators may matter operationally, but they are not valid proxies for structural adoption.

---

## Dashboard Narrative Strip Rules

Every dashboard should include a short narrative strip with three fixed prompts:

1. what strengthened this period
2. what drifted this period
3. what action happens next

Keep each prompt short.

The narrative strip should clarify the indicators, not substitute for them.

---

## Template A. Command Sponsor Dashboard

### Objective

Give executive and command leadership one concise view of whether the rollout is real, fragile, regressing, or ready to scale.

### Best review cadence

- weekly during early live pilot
- biweekly after initial stabilization
- monthly once the system is holding

### Audience

- executive sponsor
- command sponsor
- implementation owner
- steering group

### Suggested layout

Use six tiles plus one narrative strip:

- adoption
- transfer
- training
- specialist alignment
- drift
- corrective action

### Recommended tiles

#### Tile 1. Adoption Integrity

Show:

- explicit closure rate
- named deferral ownership rate
- time-in-state visibility rate
- observation coverage count

Leadership question:

- are teams visibly using the method

#### Tile 2. Transfer Integrity

Show:

- transfer-ready package rate
- oral rescue dependency rate
- major interface failures this period

Leadership question:

- is the work becoming more legible across roles

#### Tile 3. Training and Readiness

Show:

- pass rate
- conditional pass rate
- remediation completion rate
- calibration convergence rate

Leadership question:

- is the training system producing real readiness

#### Tile 4. Specialist Alignment

Show:

- lab structural intake rate
- null humility integrity rate
- downstream boundedness rate
- severe overclaim event count

Leadership question:

- are downstream layers reinforcing or weakening the method

#### Tile 5. Drift and Risk

Show:

- premature category closure flag rate
- repeat fault-line count
- high-risk drift indicator count
- current quarterly audit disposition

Leadership question:

- is the rollout drifting beneath the surface

#### Tile 6. Corrective Action

Show:

- corrective-action closure rate
- overdue corrective actions
- top red items by owner

Leadership question:

- is leadership actually closing the problems the dashboard reveals

### Command dashboard narrative strip

Use:

- `Strengthened:`  
- `Drifted:`  
- `Next action:`  

### Command review trigger rules

Escalate immediately if:

- severe overclaim event count rises materially
- oral rescue dependency worsens for two consecutive windows
- corrective-action closure rate falls while red items rise
- audit disposition moves to `Hold and Remediate` or `Reset the Stage`

---

## Template B. Pilot Operations Dashboard

### Objective

Give operational leads a working view of how the live pilot is behaving scene by scene and role by role.

### Best review cadence

- weekly during active pilot blocks

### Audience

- pilot operational lead
- patrol supervisors
- detective supervisors
- scene-unit leads
- lab liaison
- implementation owner

### Suggested layout

Use five sections:

- patrol and first response
- scene processing
- case development
- supervision
- handoff

### Section 1. Patrol and First Response

Show:

- physical / informational boundary integrity rate
- life-safety disturbance accounting rate
- patrol handoff quality rate
- first-radio observational discipline rate

Key prompt:

- is diagnosability being protected in the first minutes

### Section 2. Scene Processing

Show:

- anchor-first behavior rate
- ranked collection integrity rate
- packaging distinction integrity rate
- documentation transferability rate

Key prompt:

- is scene work structural or merely busy

### Section 3. Detectives and Package Development

Show:

- live hypothesis integrity rate
- bounded reconstruction rate
- deferral ownership rate
- reentry-condition visibility rate

Key prompt:

- is the case package being strengthened without narrative inflation

### Section 4. Supervisory Effect

Show:

- structural question discipline rate
- uncertainty protection rate
- after-action review completion rate
- supervisory distortion flags

Key prompt:

- are supervisors reinforcing the new model or pulling the room backward

### Section 5. Handoff Integrity

Show:

- patrol-to-specialist handoff integrity
- technician-to-detective transfer integrity
- detective-to-lab transfer integrity
- detective-to-prosecutor transfer integrity

Key prompt:

- which interface is currently the weakest

### Pilot operations narrative strip

Use:

- `Strongest live behavior:`  
- `Most fragile interface:`  
- `Immediate corrective action:`  

---

## Template C. Training and Certification Dashboard

### Objective

Give the academy and training leadership a stable view of whether the training system is producing credible readiness rather than inflated scores.

### Best review cadence

- after every training block
- monthly during pilot build

### Audience

- training lead
- instructor lead
- implementation owner
- legal training lead
- audit lead

### Suggested layout

Use six sections:

- cohort status
- scoring integrity
- remediation
- instructor calibration
- mixed-role calibration
- downstream legal signoff

### Section 1. Cohort Status

Show:

- learners assessed
- clear passes
- passes with conditions
- remediation assignments
- not-yet-ready outcomes

### Section 2. Scoring Integrity

Show:

- average score by module
- severe flag count
- score-to-output mismatch cases
- override use count

Key prompt:

- are scores still credible

### Section 3. Remediation System

Show:

- remediation plans issued
- remediation completion rate
- re-run success rate
- repeated remediation loops

Key prompt:

- is remediation corrective or ceremonial

### Section 4. Instructor Calibration

Show:

- instructor calibration sessions run
- convergence rate
- unresolved scoring disagreements
- rule changes carried forward

Key prompt:

- is there still one academy standard

### Section 5. Mixed-Role Calibration

Show:

- mixed investigator-prosecutor sessions run
- lawful convergence rate
- residue-preserving convergence rate
- repeat cross-role disagreement classes

Key prompt:

- are roles reading the same package by the same structural logic

### Section 6. Downstream Legal Signoff

Show:

- legal clear pass count
- legal conditional pass count
- legal remediation count
- revocations or deferred signoffs

Key prompt:

- is the downstream legal track producing safe independent users

### Training dashboard narrative strip

Use:

- `Most credible gain:`  
- `Most concerning scoring or remediation pattern:`  
- `Required training adjustment:`  

---

## Template D. Laboratory and Downstream Legal Dashboard

### Objective

Give specialist supervisors a local reporting surface that shows whether their units are strengthening structural honesty or reintroducing confirmation-service and rhetorical-closure pressure.

### Best review cadence

- monthly during pilot
- after significant charging or transfer cycles

### Audience

- lab supervisor
- downstream legal supervisor
- implementation owner
- audit lead

### Suggested layout

Use two mirrored halves:

- laboratory half
- downstream legal half

### Laboratory half

Show:

- lab structural intake rate
- clarifying-question rate on weak submissions
- null humility integrity rate
- reprocessing boundedness rate
- confirmation-service pressure events

Key prompt:

- is the lab discriminating or merely servicing

### Downstream legal half

Show:

- downstream boundedness rate
- severe overclaim event count
- legal transferability rate
- residue-preservation rate
- signoff distribution by scope category

Key prompt:

- is downstream legal review protecting or erasing the package structure

### Joint specialist risk band

Show one summary band:

- `aligned`
- `fragile`
- `misaligned`

This band should be evidence-based, not intuitive.

### Specialist dashboard narrative strip

Use:

- `What the specialist layers strengthened:`  
- `What pressure they reintroduced:`  
- `What must be corrected before the next cycle:`  

---

## Template E. Drift and Recovery Dashboard

### Objective

Give audit and leadership teams a view of whether the rollout is stabilizing or regressing between formal quarterly audit points.

### Best review cadence

- monthly
- immediately after major regression signals

### Audience

- audit lead
- implementation owner
- steering group
- command sponsor

### Suggested sections

- open red indicators
- repeat fault lines
- corrective-action velocity
- regression source map
- next recovery review date

### Section 1. Open Red Indicators

Show:

- current red indicators by layer
- age in days
- owner

### Section 2. Repeat Fault Lines

Show:

- fault line
- current count
- prior count
- layer classification

### Section 3. Corrective-Action Velocity

Show:

- corrective actions opened
- corrective actions closed
- overdue corrective actions
- closure rate by owner group

### Section 4. Regression Source Map

Break regressions into:

- training failure
- supervisory failure
- document design failure
- governance failure
- role-interface failure
- staffing / capacity failure
- metric distortion
- technology or tool misalignment
- pressure-rehearsal gap

### Section 5. Recovery Commitments

Show:

- one training adjustment due
- one document adjustment due if needed
- one leadership reinforcement action due
- next audit or recovery review date

### Drift dashboard narrative strip

Use:

- `Main regression source:`  
- `Most urgent recovery action:`  
- `Review trigger:`  

---

## Template F. Scale-Up Dashboard

### Objective

Give leadership a compact picture of whether the pilot is mature enough to multiply safely.

### Best review cadence

- at each scale decision point

### Audience

- command sponsor
- executive sponsor
- implementation owner
- steering group

### Suggested sections

- pilot maturity
- supervisory maturity
- training-system maturity
- specialist maturity
- receiving-wave readiness
- scale recommendation

### Section 1. Pilot Maturity

Show:

- transfer-ready package rate
- oral rescue dependency rate
- explicit closure rate
- deferral ownership rate

### Section 2. Supervisory Maturity

Show:

- structural question discipline rate
- after-action review completion rate
- supervisory distortion flags

### Section 3. Training-System Maturity

Show:

- clear pass rate
- conditional pass rate
- remediation completion rate
- instructor calibration convergence rate

### Section 4. Specialist Maturity

Show:

- lab structural intake rate
- downstream boundedness rate
- severe overclaim event count
- cross-role interface red flags

### Section 5. Receiving-Wave Readiness

Show:

- local sponsor named
- local supervisory support confirmed
- local training support confirmed
- first review date set
- local risk conditions logged

### Section 6. Scale Recommendation

Use one of:

- `Proceed`
- `Proceed with Conditions`
- `Hold and Remediate`
- `Reset the Stage`

and show:

- main evidence for recommendation
- main condition if not clear proceed
- first post-scale audit date

### Scale dashboard narrative strip

Use:

- `Why scale is or is not justified:`  
- `Most fragile maturity area:`  
- `Condition before next wave:`  

---

## Template G. Local Team Micro-Dashboard

### Objective

Give a local supervisor or pilot-site lead a small weekly scorecard without forcing a full enterprise dashboard.

### Best review cadence

- weekly

### Audience

- patrol sergeant
- scene-unit lead
- detective lieutenant
- lab lead
- legal review supervisor

### Suggested fields

- observed events this week
- green indicators
- amber indicators
- red indicators
- repeat fault line
- corrective action owner
- next review date

### Micro-dashboard prompt set

- what behavior improved
- what stayed fragile
- what one change is required before next week

This template is useful when the reporting surface needs to stay lightweight but still structurally meaningful.

---

## Dashboard Tile Library

Use this tile library to build local variations without reinventing the meaning of each indicator.

### Adoption tiles

- explicit closure
- named deferrals
- time-in-state visibility
- observation coverage

### Transfer tiles

- transfer-ready packages
- oral rescue dependency
- handoff failure count
- downstream clarification requests

### Integrity tiles

- premature category closure
- structural question discipline
- residue visibility
- bounded legal review

### Training tiles

- pass distribution
- conditional pass distribution
- remediation closure
- severe flag count

### Specialist tiles

- lab structural intake
- bounded null reporting
- severe overclaim events
- demonstrative-discipline issues

### Recovery tiles

- repeat fault lines
- open red indicators
- corrective-action closure
- review-date compliance

---

## Threshold Suggestions for Local Colors

These are starter rules only.

Local programs should calibrate them carefully.

### Green starter pattern

Use green when:

- the sample is adequate
- the indicator is stable or improving
- no severe override risk is attached

### Amber starter pattern

Use amber when:

- the sample is adequate
- the indicator is inconsistent, newly declining, or role-dependent

### Red starter pattern

Use red when:

- severe override risk is present
- the indicator is materially declining
- the indicator reveals unsafe transfer or unsafe overclaim
- a corrective action is overdue against a high-risk item

### Gray starter pattern

Use gray when:

- the sample is too small
- observation coverage is too thin
- the metric definition is not yet stable locally

Never use green simply because the number is missing.

That is how dashboards turn into false reassurance devices.

---

## Dashboard Construction Rules

If a local team builds a digital dashboard from these templates, follow these construction rules.

### Rule 1: Limit the executive layer

The command view should stay compact.

If leadership has to interpret thirty tiles every week, the warning signal will disappear.

### Rule 2: Keep the audit trail beneath the tile

Every important tile should allow the owner to identify:

- data source
- reporting window
- last update date
- current owner

### Rule 3: Preserve text for red items

Red items should always include a short cause line and next action line.

### Rule 4: Show trend and current state together

A stable amber and a worsening amber are not the same condition.

### Rule 5: Do not auto-close red items because a new window started

Closure requires evidence, not time passage.

### Rule 6: Keep role layers separable

Do not aggregate away the role that generated the signal.

If the field, lab, or downstream legal layer is the source of drift, leadership should be able to see that immediately.

---

## Monthly Dashboard Summary Template

Use this at the front of a monthly packet.

**Reporting month:**  
**Prepared by:**  
**Units covered:**  

### Overall rollout status

- Green
- Amber
- Red
- Gray

### Three strongest indicators

1.  
2.  
3.  

### Three most fragile indicators

1.  
2.  
3.  

### Top repeat fault line

1.  

### Corrective-action posture

- on track
- slipping
- materially behind

### Immediate leadership action needed

1.  
2.  
3.  

---

## Dashboard Review Meeting Template

Use this agenda when the dashboard is reviewed live.

### Step 1: Open with red items

Do not open with successes if there are unresolved red indicators.

### Step 2: Review repeat fault lines

Ask:

- what repeated
- what layer owns it
- why the prior action did not close it

### Step 3: Review transfer indicators

Ask:

- are packages becoming more legible
- where is oral rescue still hiding

### Step 4: Review training and signoff posture

Ask:

- are the pass numbers credible
- where are conditional passes clustering
- where are signoffs being revoked or deferred

### Step 5: Review specialist alignment

Ask:

- are lab and downstream legal layers strengthening or weakening the system

### Step 6: Confirm actions and dates

End with:

- owner
- due date
- evidence required at follow-up

If the meeting ends without these, the dashboard has been consumed but not used.

---

## Common Dashboard Failure Modes

### Measuring output instead of architecture

This is the most common failure.

The dashboard becomes a prettier version of the old productivity sheet.

### Aggregating away the warning signal

When too many role-specific problems are combined into one overall average, the dashboard starts flattering the rollout.

### Counting document completion as adoption

Forms present does not mean logic present.

### Using averages to hide red events

One severe overclaim event can matter more than a superficially healthy average.

### Letting the dashboard become a political object

If teams think the dashboard exists mainly to make leadership feel safe, the numbers will drift toward presentation.

### Updating the dashboard without updating the action ledger

Information without ownership produces ritual review and no change.

### Measuring only what is easiest to count

If a metric is easy to count but weakly related to the method, it should stay secondary.

### Failing to show uncertainty in the dashboard itself

If the evidence is too thin, the dashboard should say `Gray`.

False precision at the reporting layer is still false precision.

---

## Recommended Local Dashboard Stack

For a functioning pilot site, the minimum useful stack is:

1. command sponsor dashboard
2. pilot operations dashboard
3. training and certification dashboard
4. specialist dashboard
5. drift and recovery dashboard

The micro-dashboard may be added for individual local leads.

This stack works because it covers:

- leadership
- live operations
- training
- specialists
- recovery

without asking one dashboard to do everything.

---

## Companion Map

### The documents most closely paired with these dashboard templates are

- the leadership implementation playbook
- the live implementation audit packets
- the live-scene and live-review observation checklists
- the instructor scoring sheets and thresholds
- the courtroom transfer and legal review scenarios instructor scoring sheets and thresholds
- the legal scenario pass-fail signoff forms
- the mixed investigator-prosecutor calibration packets
- the instructor calibration packets

### What should come after this document

The next strongest companion documents after this one are:

- role-specific observation variants for agency-specific deployment
- agency-specific dashboard population guides
- local rollout policy templates

Those would let individual agencies adapt these dashboard patterns without breaking the underlying metric logic.

---

## Closing Note

A weak dashboard makes a weak rollout look stable.

A strong dashboard does something harder.

It makes it difficult for the institution to confuse:

- volume with rigor
- fluency with transferability
- calm with structural health
- high scores with safe readiness
- polished legal products with lawful boundedness

That is the standard here.

The dashboard layer should not make leadership more comfortable.

It should make leadership less blind.
