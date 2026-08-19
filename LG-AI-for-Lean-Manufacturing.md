# AI for Lean Manufacturing - Learner Guide

**Course Code:** TGS-2023020425  
**TSC:** Lean Manufacturing (PRE-OPR-4064-1.1)  
**Version:** v7.0 | 19 August 2026

## How to use this guide

The slides explain concepts and decision frameworks. This Learner Guide carries the detailed procedures, case scenarios, questions, evidence requirements and acceptance criteria for all activities.

## Learning Outcomes

- LO1: Identify eight types of production wastes within the organisation, benefits of lean manufacturing and steps to achieve lean performance results.
- LO2: Apply lean principles to compute production capacity and TAKT time.
- LO3: Perform ABC analysis for inventory classification using selective inventory control.
- LO4: Calculate economic batch quantity and number of kanbans required.
- LO5: Identify objectives of production and inventory control and types of inventories by function and condition.
- LO6: Implement lean manufacturing tools for improved inventory flow and material flow.
- LO7: Implement lean manufacturing in an organisation at various levels and within various areas for improvement.
- LO8: Determine the necessity for preventive maintenance within the organisation.
- LO9: Identify performance measurement areas in lean manufacturing and steps required for successful lean implementation.

## Topic Knowledge Briefs

### Topic 1: Lean Foundations, Waste and Flow

Customer value, eight wastes, five principles, capacity, takt and problem framing

#### Lean is a management system for customer value

- **Purpose:** Create the value the customer needs, when it is needed.
- **Method:** Expose and remove non-value-added time, effort, inventory and defects.
- **System:** Link flow, pull, quality at source, people capability and continuous improvement.
- **Discipline:** Use evidence and standard work; do not confuse local speed with system performance.
> **Lean-AI note:** AI supports sensing and decisions; lean supplies the value logic and improvement method.

Source: https://www.twi-global.com/technical-knowledge/faqs/faq-what-is-lean-manufacturing

#### Lean is not simply cost cutting

- **Lean thinking:** Protect customer value; Remove causes of waste; Build capability; Improve the whole system
- **Cost cutting alone:** Targets expense without flow; Can shift waste downstream; Often reduces resilience; May suppress improvement ideas
> **Lean-AI note:** Use total-system measures before declaring a saving.

#### From Toyota Production System to modern lean

- **Stage 1:** Flow production foundations
- **Stage 2:** Just-in-time and jidoka
- **Stage 3:** Toyota Production System
- **Stage 4:** Lean term popularised
- **Stage 5:** Lean applied across sectors
> **Lean-AI note:** The history matters because lean is a socio-technical operating system, not a toolbox.

#### Customer value sets the improvement direction

- **Specific:** Value is defined for a product or service, customer and need.
- **Observable:** Translate needs into quality, delivery, cost, safety and service requirements.
- **Testable:** A change is valuable only if it improves an agreed customer or business outcome.
- **Balanced:** Safety, regulation and ethics remain constraints even when customers do not see them.
#### Three activity types in a value stream

- **Value-adding:** Transforms form, fit or function; Customer is willing to pay; Done right the first time
- **Non-value-adding:** Pure waste: remove; Necessary waste: reduce or redesign; Always test safety and compliance constraints
> **Lean-AI note:** Classify the activity, not the job title or department.

#### The eight wastes: DOWNTIME

- **Defects:** Errors, scrap, rework and inspection loops.
- **Overproduction:** Making earlier or more than downstream demand.
- **Waiting:** Idle people, equipment, information or material.
- **Non-utilised talent:** Ideas, knowledge and capability left unused.
- **Transportation:** Unnecessary movement of materials or information.
- **Inventory:** Excess raw material, WIP or finished goods.
- **Motion:** Unnecessary movement by people or equipment.
- **Extra-processing:** Work beyond what the customer or process needs.
Source: https://www.twi-global.com/technical-knowledge/faqs/faq-what-is-lean-manufacturing

#### Muda, mura and muri reinforce one another

- **What operators see:** Muda: visible waste; Mura: uneven demand and workload; Muri: overburden and strain
- **System response:** Stabilise demand and work; Level flow where practical; Design safe capacity margins; Then remove residual waste
> **Lean-AI note:** Removing muda while ignoring unevenness and overburden can make the system brittle.

Source: https://www.twi-global.com/technical-knowledge/faqs/faq-what-is-lean-manufacturing

#### Waste walk: a symptom is not yet a cause

- **Scenario:** A machining cell misses shipment cut-off twice a week. WIP piles up before inspection while operators search for gauges.
- **Signals:** Waiting before inspection; Motion searching for gauges; Inventory between stages; Potential defects and rework
- **Decision:** Record observable facts first; use root-cause tools before prescribing automation.
#### A Pareto view focuses the first investigation

- **Data:** Late inspection: 38, Gauge search: 24, Rework: 18, Material wait: 12, Other: 8
- **Takeaway:** Two delay categories account for 62% of observed incidents; validate them at the gemba before acting.
#### Five lean principles

- **1 Define value:** Specify value from the customer's point of view.
- **2 Map the value stream:** See every material and information step.
- **3 Create flow:** Reduce stoppages, queues and hand-off friction.
- **4 Establish pull:** Replenish from downstream demand rather than forecast alone.
- **5 Seek perfection:** Continuously close the gap through learning cycles.
Source: https://www.twi-global.com/technical-knowledge/faqs/faq-what-is-lean-manufacturing

#### Value-stream thinking crosses departments

- **Stage 1:** Customer need
- **Stage 2:** Order and planning
- **Stage 3:** Material and production
- **Stage 4:** Quality and release
- **Stage 5:** Delivery and feedback
> **Lean-AI note:** Optimise end-to-end lead time and value, not the utilisation of one function.

#### Current-state mapping needs facts

- **Time:** Cycle, queue, changeover and lead time.
- **Flow:** Material, information, rework and escalation paths.
- **Quality:** First-pass yield, defect and rework rates.
- **Demand:** Customer rate, mix, volatility and due dates.
- **Resources:** People, machines, uptime and constraints.
- **Rules:** Batch sizes, schedules, approvals and policies.
#### Flow and pull solve different problems

- **Flow:** Work progresses without interruption; Small transfer batches; Balanced steps; Visible constraints
- **Pull:** Downstream demand authorises work; WIP is bounded; Replenishment signals are explicit; Overproduction is controlled
> **Lean-AI note:** Use flow where processes can connect; use pull where buffers are necessary.

#### Production capacity is a constraint statement

- **Rated capacity:** Theoretical maximum under stated conditions.
- **Effective capacity:** Expected output after planned losses.
- **Actual output:** What the system achieved.
- **Bottleneck capacity:** The lowest sustainable stage rate that governs the flow.
#### Production rate

- **Formula:** Production rate = good units produced / productive time
- **Worked example:** 960 good units / 8 hours = 120 units per hour
- **Interpretation:** State whether downtime, breaks and rejects are included; otherwise rates are not comparable.
#### Takt time aligns work to customer demand

- **Formula:** Takt time = net available production time / customer demand
- **Worked example:** 420 available minutes / 210 units = 2.0 minutes per unit
- **Interpretation:** Takt is a demand rhythm, not the observed cycle time. A process must reliably cycle at or below takt.
#### Takt time, cycle time and lead time

- **Different clocks:** Takt: required demand pace; Cycle: time to complete one unit at a process; Lead: elapsed time from request to delivery
- **Management use:** Takt sizes capacity; Cycle exposes constraints; Lead time reveals queues and delays
> **Lean-AI note:** Do not report one metric as a substitute for another.

#### Capacity decision with variation

- **Scenario:** A line has a 2.0-minute takt. Average cycle time is 1.8 minutes, but the 90th percentile is 2.4 minutes and changeovers create a morning queue.
- **Signals:** Average suggests capacity is sufficient; High-end variation misses takt; Changeover loss is time-dependent; Queueing appears despite acceptable average
- **Decision:** Stabilise the process and changeovers before buying capacity; model the full distribution, not the mean alone.
#### Where AI complements lean foundations

- **Sense:** Detect anomalies, defects and emerging constraints from data.
- **Predict:** Estimate failure, demand or quality risk earlier.
- **Recommend:** Rank options while exposing assumptions and confidence.
- **Generate:** Draft work instructions, summaries and improvement documentation.
- **Learn:** Feed verified outcomes back into standards and models.
> **Lean-AI note:** AI should shorten the learn-and-improve loop without hiding process ownership.

Source: https://www.sciencedirect.com/topics/engineering/lean-manufacturing

#### Automation, analytics, machine learning and GenAI

- **Deterministic:** Automation follows explicit rules; Analytics describes and diagnoses; Outputs are repeatable for the same inputs
- **Probabilistic:** ML predicts from patterns; Computer vision classifies images; GenAI produces new text, images or code; Outputs need confidence and review
> **Lean-AI note:** Choose the least complex method that reliably solves the problem.

#### Lean problem framing before an AI pilot

- **Stage 1:** Define customer and waste
- **Stage 2:** Measure the current state
- **Stage 3:** Find the causal lever
- **Stage 4:** Test simplest countermeasure
- **Stage 5:** Add AI only when it improves the control loop
> **Lean-AI note:** Start with a process problem and measurable outcome - never with a model looking for a use case.

#### AI opportunity: inspection bottleneck

- **Scenario:** Manual inspection takes 45 seconds per part and creates a queue. Defects are visually observable but rare.
- **Signals:** Potential: computer-vision triage; Constraint: class imbalance and image quality; Risk: false negatives release defects; Need: human review and traceable evidence
- **Decision:** Pilot AI as an assistive screen with conservative thresholds; retain human disposition authority.
### Topic 2: Inventory and Production Control

Inventory purpose and types, ABC, EBQ, kanban, JIT, 5S, VSM and QC tools

#### Production and inventory control objectives

- **Service:** Meet demand with the right item, quantity and timing.
- **Flow:** Keep material moving without starving or flooding processes.
- **Cash:** Limit capital tied up in stock and obsolescence.
- **Quality:** Protect identity, condition and traceability.
- **Resilience:** Use explicit buffers for credible variability and risk.
#### Inventory by function

- **Cycle stock:** Supports normal replenishment between orders or batches.
- **Safety stock:** Protects service against demand or supply variability.
- **Pipeline stock:** Material moving or waiting between locations.
- **Anticipation stock:** Built ahead for predictable peaks or shutdowns.
- **Decoupling stock:** Buffers adjacent processes with different rhythms.
- **MRO:** Maintenance, repair and operating supplies.
#### Inventory by condition

- **Raw material:** Not yet transformed.
- **Work in progress:** Partly processed or waiting between operations.
- **Finished goods:** Completed and awaiting shipment.
- **Serviceable:** Fit for planned use.
- **Quarantine:** Held pending inspection or disposition.
- **Obsolete or excess:** No current demand or beyond useful life.
#### Inventory can be protection and waste

- **Useful buffer:** Absorbs known variability; Protects a constraint; Supports service commitments; Has an explicit owner and rule
- **Hidden problem:** Masks quality and downtime; Lengthens lead time; Consumes space and cash; Can become obsolete
> **Lean-AI note:** Every buffer needs a purpose, size rule and exit condition.

#### ABC selective inventory control

- **Stage 1:** Calculate annual usage value
- **Stage 2:** Rank items descending
- **Stage 3:** Compute cumulative share
- **Stage 4:** Assign A, B and C classes
- **Stage 5:** Set differentiated controls
> **Lean-AI note:** ABC prioritises management attention; it does not replace criticality, lead-time or risk analysis.

#### Annual usage value

- **Formula:** Annual usage value = annual demand x unit cost
- **Worked example:** Item P-104: 4,000 units x $18 = $72,000
- **Interpretation:** Sort values before cumulative percentages; keep item identifiers as text.
#### A small item set can dominate annual value

- **Data:** P-104: 72000, M-220: 54000, V-031: 21000, S-410: 10000, B-118: 6000, Other: 9000
- **Takeaway:** The top two items represent most annual usage value and deserve tighter review and records.
#### Class policy must follow the classification

- **A items:** Frequent review; Accurate records; Tight approval and supplier management; Small controlled buffers
- **B and C items:** B: periodic review and balanced control; C: simple controls and efficient ordering; Still override for safety-critical items
> **Lean-AI note:** Use a criticality flag alongside ABC to prevent low-cost safety parts being neglected.

#### Economic batch quantity balances two costs

- **Setup cost:** More batches increase preparation, changeover and administration.
- **Holding cost:** Larger batches increase space, capital, damage and obsolescence.
- **Demand:** EBQ assumes a known production requirement.
- **Production rate:** The finite replenishment rate distinguishes EBQ from basic EOQ.
#### Economic batch quantity

- **Formula:** EBQ = sqrt[(2DS/H) x P/(P-D)]
- **Worked example:** D=12,000/year, S=$80/setup, H=$3/unit-year, P=30,000/year -> EBQ approximately 1,033 units
- **Interpretation:** Check P > D and document assumptions; revise when demand, setup or holding costs change.
#### EBQ is a decision aid, not a command

- **Assumptions:** Stable demand and production rate; Known setup and holding costs; No material stockout during production; Consistent quality
- **Reality checks:** Shelf life and space; Supplier or machine constraints; Changeover improvement opportunity; Demand uncertainty
> **Lean-AI note:** Lean often reduces the setup cost itself, allowing smaller economical batches.

#### Kanban is a signal-and-response system

- **Signal:** Card, empty bin, electronic message or controlled slot.
- **Authorisation:** Permits production or movement - no signal, no work.
- **Limit:** The number of cards caps WIP.
- **Feedback:** Blockages and abnormal consumption become visible.
#### Kanban quantity

- **Formula:** Kanbans = demand rate x replenishment lead time x (1 + safety factor) / container quantity
- **Worked example:** 500 units/day x 2 days x 1.10 / 50 units = 22 kanbans
- **Interpretation:** Round up to a whole container and review the safety factor after stabilising lead time.
#### Kanban sensitivity

- **Scenario:** The team wants more kanban cards because stockouts occurred during supplier delays.
- **Signals:** More cards hide the lead-time problem; A permanent buffer increases WIP; Supplier delay distribution is not understood; Container size may be poorly matched
- **Decision:** Contain short-term risk, then reduce and stabilise replenishment lead time before resetting the card count.
#### Lean tools for material flow

- **5S:** Makes location, quantity and abnormality visible.
- **Value-stream mapping:** Connects material and information flow.
- **Standard work:** Defines the current best-known safe method.
- **JIT:** Produces and replenishes near actual demand.
- **Heijunka:** Levels volume and mix where demand permits.
- **SMED:** Reduces changeover so smaller batches are practical.
- **TPM:** Protects equipment availability and stable flow.
- **Poka-yoke:** Prevents or immediately detects errors.
#### 5S creates a visual baseline

- **Stage 1:** Sort
- **Stage 2:** Set in order
- **Stage 3:** Shine
- **Stage 4:** Standardise
- **Stage 5:** Sustain
> **Lean-AI note:** 5S is not a one-time clean-up; it is a control system that makes normal and abnormal conditions obvious.

#### Just-in-time needs stability

- **Enablers:** Reliable processes and suppliers; Short replenishment lead time; Quality at source; Visible demand signals; Flexible people and equipment
- **Failure modes:** Too little buffer for real variability; Expediting replaces improvement; Local pull disconnected from customer demand; Risks transferred to suppliers
> **Lean-AI note:** Design resilience explicitly; low inventory is an outcome, not the sole objective.

#### Heijunka reduces unevenness

- **Stage 1:** Understand demand mix
- **Stage 2:** Select a practical pitch
- **Stage 3:** Sequence product families
- **Stage 4:** Level volume and mix
- **Stage 5:** Review adherence and exceptions
> **Lean-AI note:** Level only what the market and process can support; do not flatten meaningful customer priorities.

#### AI demand forecast versus pull control

- **Scenario:** A forecasting model predicts next week's mix, while the line uses kanban based on actual withdrawal.
- **Signals:** Forecast helps capacity and material planning; Kanban authorises near-term replenishment; Forecast error must not inflate every buffer; Human planners need exception thresholds
- **Decision:** Use prediction for planning horizons and pull for execution; reconcile them through explicit exception rules.
#### AI can improve inventory decisions

- **Demand sensing:** Use recent orders, seasonality and context to update forecasts.
- **Anomaly detection:** Flag unusual consumption, scrap or stock movement.
- **Supplier risk:** Surface lead-time and quality patterns.
- **Replenishment recommendation:** Prioritise reviews while preserving approval authority.
- **Data assistant:** Summarise exceptions and draft action lists from verified ERP data.
Source: https://www.sciencedirect.com/topics/engineering/lean-manufacturing

#### AI recommendation versus replenishment authority

- **AI may:** Score risk; Forecast demand; Rank shortages; Suggest order quantities; Explain drivers
- **Human owner must:** Validate data and constraints; Resolve safety and service trade-offs; Approve material commitments; Record overrides and outcomes
> **Lean-AI note:** Never allow a language model to invent inventory balances or supplier commitments.

#### ABC plus criticality plus AI

- **Scenario:** A low-cost seal is class C by annual value but stops the only coating line when unavailable.
- **Signals:** ABC alone under-prioritises it; Criticality is high; Lead time is volatile; AI forecast confidence is low because failures are rare
- **Decision:** Use a multi-criteria policy: annual value + operational criticality + lead-time risk + data confidence.
### Topic 3: AI-enabled Lean Implementation and Maintenance

Metrics, TPM, predictive maintenance, quality AI, GenAI, governance and scalable implementation

#### Preventive maintenance protects lean flow

- **Reliability:** Avoid breakdown-driven waiting, defects and schedule churn.
- **Safety:** Control equipment deterioration before hazardous failure.
- **Quality:** Keep process conditions inside proven limits.
- **Cost:** Plan labour and parts instead of paying emergency premiums.
- **Learning:** Use work history to remove recurring failure causes.
#### Reactive, preventive, condition-based and predictive

- **Time and event based:** Reactive: after failure; Preventive: calendar, usage or event schedule; Simple to govern; May over-maintain or miss early deterioration
- **Condition and prediction based:** Condition-based: threshold or inspection signal; Predictive: model estimates risk or remaining life; Targets intervention; Depends on data quality and model performance
> **Lean-AI note:** Select the strategy by failure consequence, detectability and economics.

#### Determine the maintenance need

- **Stage 1:** Build equipment inventory
- **Stage 2:** Assess criticality and failure modes
- **Stage 3:** Review maker and legal requirements
- **Stage 4:** Analyse work history and condition data
- **Stage 5:** Select task, interval and owner
- **Stage 6:** Measure and improve
> **Lean-AI note:** Safety-critical maintenance requirements are constraints, not optimisation suggestions.

#### FMEA focuses maintenance effort

- **Failure mode:** How the asset or process could fail.
- **Effect:** Impact on safety, quality, delivery and cost.
- **Cause:** Mechanism that creates the failure.
- **Controls:** Prevention and detection already in place.
- **Priority:** Use severity first, then occurrence and detection evidence.
- **Action:** Assign owner, due date and verification evidence.
#### Total Productive Maintenance

- **Autonomous maintenance:** Operators care for basic conditions and detect abnormalities.
- **Planned maintenance:** Schedule evidence-based tasks and spares.
- **Focused improvement:** Remove chronic losses.
- **Quality maintenance:** Control equipment conditions that create defects.
- **Early equipment management:** Design maintainability into new assets.
- **Training:** Build operator and maintainer capability.
- **Safety and environment:** Eliminate harm and uncontrolled impact.
- **Office TPM:** Improve supporting information and administrative flow.
#### Overall Equipment Effectiveness

- **Formula:** OEE = Availability x Performance x Quality
- **Worked example:** 0.90 x 0.95 x 0.98 = 83.8%
- **Interpretation:** Use OEE to expose loss categories, not to rank unlike equipment or pressure operators.
#### Metric tree prevents local optimisation

- **Lagging outcomes:** Lead time; On-time delivery; Cost per good unit; Customer complaints; OEE and first-pass yield
- **Leading controls:** Standard-work adherence; Changeover completion; Maintenance compliance; Data-quality score; Improvement action closure
> **Lean-AI note:** Pair each outcome with controllable process measures and an owner.

#### Core lean performance measures

- **Flow:** Lead time, cycle time, WIP and queue age.
- **Quality:** First-pass yield, defect rate, rework and escape rate.
- **Delivery:** On-time delivery, schedule adherence and service level.
- **Equipment:** Availability, OEE, MTBF and MTTR.
- **People:** Safety, skills coverage, suggestions and participation.
- **Sustainment:** Audit conformance, action closure and benefit retention.
#### A KPI dashboard should tell a causal story

- **Data:** Availability: 90, Performance: 95, Quality: 98
- **Takeaway:** High quality does not offset availability loss; target the dominant OEE component and verify the constraint.
#### AI use cases in manufacturing

- **Predictive maintenance:** Forecast equipment issues from sensor and work-history patterns.
- **Visual quality:** Detect, classify or triage defects from images.
- **Process optimisation:** Identify bottlenecks and recommend parameter ranges.
- **Demand and inventory:** Forecast needs and surface replenishment risk.
- **Digital twins:** Simulate assets or flows before physical changes.
- **Copilots:** Retrieve manuals, summarise logs and draft controlled work content.
Source: https://www.sciencedirect.com/topics/engineering/lean-manufacturing

#### Computer vision quality system

- **What it can do:** Consistent high-speed screening; Localise visible anomalies; Trend defect classes; Route uncertain cases
- **What can go wrong:** Poor lighting or camera drift; Rare defects and class imbalance; Product-mix change; False negatives released as good; Hidden bias in training images
> **Lean-AI note:** Set disposition authority, confidence thresholds and revalidation triggers.

Source: https://www.sciencedirect.com/topics/engineering/lean-manufacturing

#### Predictive-maintenance data path

- **Stage 1:** Sensors and work orders
- **Stage 2:** Time alignment and context
- **Stage 3:** Features and health indicators
- **Stage 4:** Risk prediction
- **Stage 5:** Maintenance decision
- **Stage 6:** Outcome feedback
> **Lean-AI note:** A model is only as useful as the action workflow it triggers.

Source: https://www.ascm.org/topics/lean-manufacturing/

#### Maintenance companion with GenAI

- **Scenario:** A technician asks a copilot why a spindle alarm recurs. The system retrieves manuals, approved work instructions and recent work orders.
- **Signals:** Faster knowledge access; Risk of hallucinated torque or sequence; Source version may be wrong; Maintenance action affects safety
- **Decision:** Ground responses in approved sources, show citations, require technician verification and never bypass lockout/tagout.
#### Generative AI supports knowledge work

- **Retrieve:** Find relevant clauses in manuals, standards and work history.
- **Summarise:** Condense shift logs, complaints and improvement evidence.
- **Draft:** Create first drafts of work instructions, A3s and training notes.
- **Translate:** Prepare controlled multilingual instructions for review.
- **Explain:** Turn model signals into audience-appropriate decision support.
> **Lean-AI note:** Generated content remains a draft until an authorised person verifies it.

Source: https://www.ascm.org/topics/lean-manufacturing/

#### Classical ML and generative AI

- **Classical / predictive:** Outputs scores, classes or forecasts; Uses structured signals or labelled examples; Evaluate with error metrics and thresholds; Good for anomaly, demand, quality and maintenance
- **Generative:** Outputs text, images or code; Uses prompts plus retrieved context; Evaluate groundedness, usefulness and harm; Good for knowledge access and drafting
> **Lean-AI note:** Some solutions combine both: a predictive model signals risk and a grounded copilot explains the evidence.

#### Start with manufacturing data

- **Relevance:** Use data from the specific asset, process, product and decision.
- **Context:** Connect readings with operating state, product mix, maintenance and environment.
- **Quality:** Control completeness, accuracy, labels, timing and lineage.
- **Ownership:** Assign people accountable for definitions, access and correction.
- **Feedback:** Capture decisions and outcomes to learn whether the system helped.
Source: https://mitsloan.mit.edu/ideas-made-to-matter/ai-manufacturing-start-data

#### Data readiness gate

- **Ready enough to pilot:** Defined outcome and baseline; Representative data; Known labels and units; Access and ownership approved; Action workflow exists
- **Stop and repair:** No process owner; Ambiguous timestamps or units; Missing negative cases; Uncontrolled personal or sensitive data; No way to verify benefit
> **Lean-AI note:** Do not compensate for poor data with a more complex model.

Source: https://mitsloan.mit.edu/ideas-made-to-matter/ai-manufacturing-start-data

#### Six building blocks for manufacturing AI

- **Business application:** Prioritised value and use cases.
- **Data:** Quality, access, lineage and single source of truth.
- **Technology:** Connectivity, platforms, tools and interfaces.
- **Talent and organisation:** Domain, data, IT and change capability.
- **Process:** Governance, collaboration and delivery method.
- **Culture:** Experimentation, trust and evidence-based decisions.
Source: https://www.pwc.com/gx/en/industrial-manufacturing/pdf/intro-implementing-ai-manufacturing.pdf

#### Lean-AI pilot lifecycle

- **Stage 1:** Problem and baseline
- **Stage 2:** Data and risk readiness
- **Stage 3:** Small controlled experiment
- **Stage 4:** Human-in-the-loop trial
- **Stage 5:** Measure value and harm
- **Stage 6:** Standardise, scale or stop
> **Lean-AI note:** Think big about the operating model, start small with a measurable lighthouse use case.

Source: https://www.pwc.com/gx/en/industrial-manufacturing/pdf/intro-implementing-ai-manufacturing.pdf

#### Responsible AI controls on the shop floor

- **Govern:** Owner, purpose, approvals, risk class and documentation.
- **Map:** Users, affected people, context, failure modes and dependencies.
- **Measure:** Accuracy, drift, false alarms, latency, safety and business outcomes.
- **Manage:** Thresholds, human review, fallback, monitoring, change control and retirement.
Source: https://www.nist.gov/itl/ai-risk-management-framework

#### Human-in-the-loop is a designed control

- **AI responsibility:** Detect or predict; Present evidence and confidence; Recommend within limits; Log inputs and outputs
- **Human responsibility:** Verify context; Approve consequential action; Handle exceptions; Escalate uncertainty; Own safety and customer impact
> **Lean-AI note:** Name the decision owner and the fallback before deployment.

#### Common AI failure modes

- **Data drift:** Process, product or environment changes.
- **Automation bias:** People accept the recommendation without challenge.
- **Hallucination:** Generated content is plausible but unsupported.
- **Feedback loop:** Decisions alter future data and reinforce errors.
- **Security:** Prompts, data, models or interfaces are manipulated.
- **Hidden transfer:** A vendor model changes without local validation.
#### When a pilot should stop

- **Scenario:** A defect model reaches 96% overall accuracy, but misses two of ten safety-critical crack examples.
- **Signals:** Overall accuracy hides class-specific harm; Safety severity is high; Rare class evidence is weak; Operator over-trust is plausible
- **Decision:** Stop automatic disposition; improve data and controls. Use the model only for assistive triage until the critical-class requirement is met.
#### AI use-case prioritisation

- **Value:** Waste, constraint or risk addressed and size of baseline loss.
- **Feasibility:** Data, integration, skills and actionability.
- **Risk:** Safety, quality, privacy, security and regulatory consequence.
- **Time to learn:** Speed to a controlled, informative experiment.
- **Scalability:** Repeatability across assets, products or sites.
- **Adoption:** Fit with operator work and decision rights.
#### Pilot economics

- **Benefits:** Avoided downtime; Reduced scrap and rework; Lower inspection effort; Inventory and lead-time reduction; Faster knowledge access
- **Full cost:** Data collection and cleaning; Integration and validation; Change management and training; Monitoring, support and model updates; Residual risk and fallback capacity
> **Lean-AI note:** Report net verified benefit and confidence, not vendor headline potential.

#### Simple pilot ROI

- **Formula:** ROI = (verified annual benefit - annualised total cost) / annualised total cost
- **Worked example:** ($120,000 - $80,000) / $80,000 = 50%
- **Interpretation:** Separate realised from projected benefit and include the cost of controls, not only model licensing.
#### Lean implementation sequence

- **Stage 1:** Leadership purpose and governance
- **Stage 2:** Current state and objectives
- **Stage 3:** Capability and cross-functional team
- **Stage 4:** Flow, pull and standard work
- **Stage 5:** Targeted AI experiments
- **Stage 6:** Measure, standardise and scale
> **Lean-AI note:** Implementation is a learning system, not a one-time launch.

#### Sustaining the new standard

- **Standard work:** Document the verified method and decision rights.
- **Visual management:** Show current state, targets, exceptions and ownership.
- **Leader routine:** Review process evidence at the gemba.
- **Skills:** Train operators, engineers, maintainers and managers.
- **Control plan:** Define checks, thresholds, reactions and records.
- **Audit and refresh:** Confirm benefits, data quality, model performance and change triggers.
#### Scaling without copying blindly

- **Scenario:** A predictive-maintenance pilot works on one CNC family. Leaders want to deploy it to every machine next month.
- **Signals:** Sensors and failure modes differ; Maintenance history quality varies; Action thresholds are asset-specific; Support capacity may be insufficient
- **Decision:** Scale through a repeatable qualification gate: process similarity, data readiness, risk review, local validation and owner acceptance.
#### The lean-AI operating principle

- **Lean defines value:** Use customer value and system waste as the compass.
- **People own the process:** Domain expertise frames, verifies and improves decisions.
- **Data makes reality visible:** Quality, context and lineage determine trust.
- **AI shortens the loop:** Sense, predict, retrieve or recommend earlier.
- **Governance protects outcomes:** Design limits, review, fallback and monitoring.
- **Learning sustains improvement:** Standardise verified gains and revisit assumptions.
## Detailed Activity Guides

### Activity 1: Waste Walk and AI Opportunity Scan

- **Level / duration:** Foundation | 60 minutes
- **Criterion mapping:** K1 K2 A1
- **Folder:** `activities/activity-01-waste-walk/`
- **Tools:** Observation CSV; Pareto tool; 5 Whys tool; worksheet

#### Scenario

Orion Precision Components has rising lead time in a CNC-inspection-packaging value stream. Learners use 30 observation records to distinguish facts, waste symptoms and candidate AI support.

#### Goal and deliverable

Identify the eight wastes, separate necessary from pure waste, and frame one evidence-based improvement opportunity without jumping to technology.

**Deliverable:** Completed waste register, Pareto summary, problem statement and AI/non-AI countermeasure screen.

#### Detailed procedure

1. Read the scenario and agree the customer requirement and observation boundary.
2. Open observations.csv and classify each record using DOWNTIME; do not infer a root cause yet.
3. Total delay minutes and frequency by waste category.
4. Build or verify a Pareto view using the provided online Pareto tool or the worksheet table.
5. Select the largest verified waste and write a neutral problem statement with what, where, when and magnitude.
6. Use the 5 Whys tool to explore possible causes; mark every unverified assumption.
7. List one no/low-tech countermeasure and one AI-assisted option.
8. Apply the value-feasibility-risk screen and select the next experiment.
9. Record evidence and complete the acceptance checklist.

#### Scenario questions

- Which three wastes contribute most to delay?
- What evidence is still missing before causal analysis?
- Which countermeasure should be tried before AI?
- What decision could AI support, and who owns it?

#### Evidence and acceptance

- [ ] All observations are classified with a rationale.
- [ ] Pareto totals reconcile to the CSV.
- [ ] Problem statement contains no proposed solution.
- [ ] AI option names a decision, data, human owner and risk.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

### Activity 2: SIPOC and Value-stream Decision Map

- **Level / duration:** Foundation | 60 minutes
- **Criterion mapping:** K4 A1
- **Folder:** `activities/activity-02-sipoc-value-stream/`
- **Tools:** SIPOC tool; system-loop tool; worksheet

#### Scenario

A medical-device subassembly moves through order entry, kitting, assembly, inspection and release. Handoffs and information delays are not visible in the current flowchart.

#### Goal and deliverable

Define process scope with SIPOC, classify value-added and non-value-added work, and produce a current-state decision map.

**Deliverable:** SIPOC, current-state value-stream worksheet, flow/pull improvement hypothesis and evidence plan.

#### Detailed procedure

1. Read the scenario and select one start and one end boundary.
2. Complete Supplier, Input, Process, Output and Customer fields in the SIPOC tool.
3. Define two measurable customer requirements for the output.
4. List the current material and information steps in sequence.
5. Record process time, wait time, WIP and first-pass yield for each step from process-data.csv.
6. Classify each step as value-adding, necessary non-value-adding or pure waste.
7. Map one reinforcing or balancing feedback loop using the system-loop tool.
8. Draft a future-state hypothesis that improves flow or pull without weakening safety or compliance.
9. Specify the evidence that would confirm the hypothesis.

#### Scenario questions

- What is the customer-defined output?
- Which steps transform the product correctly the first time?
- Where does information wait?
- What feedback loop sustains the queue?

#### Evidence and acceptance

- [ ] SIPOC boundary is one end-to-end process.
- [ ] Customer requirements are measurable.
- [ ] Value classification follows the three lean tests.
- [ ] Future-state hypothesis includes a measure and constraint.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

### Activity 3: Capacity, Takt and Bottleneck Analysis

- **Level / duration:** Intermediate | 75 minutes
- **Criterion mapping:** K4 A4
- **Folder:** `activities/activity-03-capacity-takt/`
- **Tools:** CSV; calculator; worksheet

#### Scenario

Orion must ship 210 good units in a 420-minute net shift. Four process steps have different cycle-time distributions, downtime and yields.

#### Goal and deliverable

Calculate takt, effective capacity and constraint risk, then select an improvement experiment based on facts rather than averages alone.

**Deliverable:** Capacity table, takt comparison, bottleneck decision and countermeasure experiment.

#### Detailed procedure

1. Confirm net available time and customer demand from capacity-data.csv.
2. Calculate takt time in minutes per good unit.
3. For each step, calculate rated units per shift from net time and average cycle time.
4. Adjust capacity for planned downtime and first-pass yield.
5. Compare effective capacity with demand and identify the system constraint.
6. Review the 90th-percentile cycle time and explain variation risk.
7. Test one countermeasure scenario by changing only one assumption.
8. Document the decision, expected benefit and verification measure.

#### Scenario questions

- What is the takt time?
- Which process constrains good-output capacity?
- How does variation change the conclusion?
- What should be stabilised before capacity is purchased?

#### Evidence and acceptance

- [ ] Takt is 2.00 minutes per good unit.
- [ ] Effective capacity calculations show units and assumptions.
- [ ] Constraint decision considers variation and yield.
- [ ] Countermeasure changes one causal factor with a defined test.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

### Activity 4: ABC Inventory Classification with Criticality

- **Level / duration:** Intermediate | 75 minutes
- **Criterion mapping:** K5 K6 A2
- **Folder:** `activities/activity-04-abc-pareto/`
- **Tools:** Inventory CSV; Pareto tool; worksheet

#### Scenario

Orion carries twelve materials with different demand, cost, lead time and operational criticality. Management currently reviews every item monthly.

#### Goal and deliverable

Perform ABC analysis, challenge value-only classification with criticality and design differentiated control policies.

**Deliverable:** Ranked ABC table, cumulative-value chart, criticality overrides and class-control policy.

#### Detailed procedure

1. Open inventory.csv and calculate annual usage value for every SKU.
2. Sort items from highest to lowest annual usage value.
3. Calculate each item's percentage and cumulative percentage of total value.
4. Assign A, B and C using the stated 80/95/100 guide; record boundary judgment.
5. Review operational criticality and lead time; identify justified overrides.
6. Define record accuracy, review frequency, approval and buffer policy by class.
7. Use the Pareto tool to confirm the visual concentration.
8. Draft an AI exception summary that references real rows and preserves planner approval.

#### Scenario questions

- Which items form approximately 80% of annual usage value?
- Which low-value items need an override?
- What review frequency fits each class?
- How could AI assist without auto-ordering?

#### Evidence and acceptance

- [ ] Annual-value total and cumulative percentages reconcile.
- [ ] Classes are based on ranked value and documented boundaries.
- [ ] Criticality overrides are explicit, not hidden.
- [ ] Policy differs meaningfully across A, B and C.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

### Activity 5: EBQ and Kanban Control Design

- **Level / duration:** Intermediate | 75 minutes
- **Criterion mapping:** K7 A3
- **Folder:** `activities/activity-05-ebq-kanban/`
- **Tools:** Calculation worksheet; calculator; checklist

#### Scenario

A component family is made internally at a finite production rate. Large batches reduce setups but increase WIP; replenishment delay also creates stockouts at assembly.

#### Goal and deliverable

Calculate EBQ and kanban quantity, test assumptions and design a signal-and-response rule.

**Deliverable:** EBQ calculation, kanban quantity, sensitivity table, card/bin rule and review trigger.

#### Detailed procedure

1. Record annual demand D, setup cost S, holding cost H and production rate P.
2. Confirm P is greater than D and that units and time bases match.
3. Calculate EBQ using the finite-production formula.
4. Recalculate EBQ after a 50% setup-cost reduction and explain the lean implication.
5. Record daily demand, lead time, safety factor and container quantity.
6. Calculate kanban quantity and round up to a whole container.
7. Test lead time and safety-factor sensitivity.
8. Write the physical or electronic signal rule, owner and abnormal-condition response.

#### Scenario questions

- What is the EBQ under the base assumptions?
- How does setup reduction change it?
- How many kanbans are required?
- Which assumption most needs evidence?

#### Evidence and acceptance

- [ ] Base EBQ is approximately 1,033 units.
- [ ] Setup reduction produces a smaller economic batch.
- [ ] Kanban result is rounded up and unit-consistent.
- [ ] Signal rule states authorisation, limit and exception response.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

### Activity 6: Root Cause with 5 Whys and Fishbone

- **Level / duration:** Intermediate | 60 minutes
- **Criterion mapping:** K7 A6
- **Folder:** `activities/activity-06-root-cause/`
- **Tools:** 5 Whys tool; Fishbone tool; evidence checklist

#### Scenario

CNC-2 generates intermittent surface marks after changeovers. The first response was to retrain operators, but the problem returned.

#### Goal and deliverable

Use structured root-cause tools to separate evidence from assumptions and select a testable countermeasure.

**Deliverable:** Problem statement, 5 Whys chain, fishbone map, evidence plan and countermeasure test.

#### Detailed procedure

1. Write a measurable problem statement from the scenario evidence.
2. Open the 5 Whys tool and build more than one plausible causal branch.
3. Label statements as observed, calculated, reported or assumed.
4. Open the Fishbone tool and organise causes under People, Machine, Method, Material, Measurement and Environment.
5. Prioritise hypotheses by evidence, severity and ease of testing.
6. Define one disconfirming test for the leading hypothesis.
7. Use GenAI only to suggest overlooked questions; do not treat suggestions as evidence.
8. Select a countermeasure after the test and define the follow-up measure.

#### Scenario questions

- Where does the causal chain rely on an assumption?
- Which cause category is under-investigated?
- What evidence would disconfirm the leading hypothesis?
- How could GenAI help without fabricating a cause?

#### Evidence and acceptance

- [ ] Problem statement includes magnitude, location and time pattern.
- [ ] At least two causal branches are considered.
- [ ] Assumptions are visibly tagged.
- [ ] Countermeasure follows evidence and has a verification date.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

### Activity 7: AI Visual Quality Pilot

- **Level / duration:** Advanced | 75 minutes
- **Criterion mapping:** K3 A6
- **Folder:** `activities/activity-07-ai-quality/`
- **Tools:** Use-case worksheet; sample predictions CSV; checklist

#### Scenario

Final inspection is a bottleneck. Orion is considering a computer-vision model to flag surface defects, but safety-critical cracks are rare.

#### Goal and deliverable

Design a human-in-the-loop visual-quality pilot with suitable data, class metrics, thresholds and fallback.

**Deliverable:** Use-case canvas, data plan, confusion-matrix interpretation, decision rights and pilot acceptance criteria.

#### Detailed procedure

1. Define the quality decision and current inspection baseline.
2. List defect classes, severity and available image sources.
3. Review predictions.csv and calculate true positives, false positives, true negatives and false negatives for critical defects.
4. Calculate recall for critical defects and precision for AI flags.
5. Set a conservative triage threshold and mandatory human-review condition.
6. Define lighting, camera, product-mix and label controls.
7. Specify fallback when the model or connection is unavailable.
8. Set pilot acceptance, stop and revalidation criteria.

#### Scenario questions

- Why is overall accuracy insufficient?
- Which error is most harmful?
- When must a human inspect?
- What change triggers model revalidation?

#### Evidence and acceptance

- [ ] Metrics are class-specific and reconcile to the CSV.
- [ ] Critical false negatives are treated as a stop condition.
- [ ] Human disposition authority is explicit.
- [ ] Data and environment drift triggers are documented.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

### Activity 8: Predictive-maintenance Decision Design

- **Level / duration:** Advanced | 75 minutes
- **Criterion mapping:** K3 A5
- **Folder:** `activities/activity-08-predictive-maintenance/`
- **Tools:** Sensor CSV; FMEA worksheet; maintenance checklist

#### Scenario

CNC-2 shows rising vibration and spindle temperature. A vendor model gives a failure-risk score but does not explain the required maintenance action.

#### Goal and deliverable

Combine asset criticality, condition data, work history and model evidence into a controlled maintenance decision.

**Deliverable:** Criticality/FMEA screen, condition trend, action threshold, work-order recommendation and fallback.

#### Detailed procedure

1. Confirm equipment function, safety consequence and production criticality.
2. Review sensor-history.csv with maintenance and operating context.
3. Plot or inspect vibration, temperature and risk-score trends.
4. List plausible failure modes and current preventive/detection controls.
5. Define normal, alert and stop bands using engineering evidence, not the model score alone.
6. Draft a work-order recommendation with source references and required inspection.
7. Define who approves, defers or escalates the action.
8. Specify monitoring, false-alarm review and fallback procedures.

#### Scenario questions

- What failure mode is plausible?
- Does the trend cross an engineering limit?
- What action follows each risk band?
- Who may defer maintenance and on what evidence?

#### Evidence and acceptance

- [ ] Decision uses both engineering and model evidence.
- [ ] Safety and maker requirements cannot be overridden by AI.
- [ ] Every risk band has an owner and action.
- [ ] Fallback maintains a safe maintenance regime.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

### Activity 9: Grounded GenAI for Standard Work

- **Level / duration:** Advanced | 60 minutes
- **Criterion mapping:** K8 A6
- **Folder:** `activities/activity-09-genai-standard-work/`
- **Tools:** Prompt worksheet; source register; review checklist

#### Scenario

Maintenance knowledge is split across manuals, approved work instructions and technician notes. Orion wants a copilot to draft troubleshooting guidance.

#### Goal and deliverable

Design prompts, retrieval boundaries and review controls that keep generated standard work grounded and safe.

**Deliverable:** Grounded prompt, source hierarchy, draft instruction, reviewer checklist and controlled-release workflow.

#### Detailed procedure

1. Define the user, decision and prohibited uses of the copilot.
2. Rank approved sources by authority and version status.
3. Write a prompt that requires retrieval citations, uncertainty and refusal when evidence is absent.
4. Generate or manually draft a short troubleshooting response using only the source excerpts in source-pack.md.
5. Check every technical value and step against the cited source.
6. Remove unsupported content and add safety prerequisites.
7. Route the draft to the authorised engineer and document changes.
8. Release only the approved version and record review date and next review trigger.

#### Scenario questions

- Which sources are authoritative?
- What must the model refuse to infer?
- Which fields require exact citation?
- Who releases the final instruction?

#### Evidence and acceptance

- [ ] Response cites an approved source for every technical instruction.
- [ ] Unknown information is stated as unknown.
- [ ] Safety and lockout/tagout prerequisites are retained.
- [ ] Final release has reviewer, version and effective date.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

### Activity 10: Lean-AI Pilot Charter and Control Plan

- **Level / duration:** Capstone | 90 minutes
- **Criterion mapping:** K1-K8 A1-A6
- **Folder:** `activities/activity-10-lean-ai-capstone/`
- **Tools:** SIPOC, system-loop, 5 Whys, Fishbone and Pareto tools; capstone worksheet

#### Scenario

Orion must choose one improvement: reduce inspection queue, improve CNC uptime or stabilise material replenishment. Each option has different value, data readiness and risk.

#### Goal and deliverable

Integrate lean diagnosis, AI use-case selection, implementation planning, governance, economics and sustainment into a defensible pilot charter.

**Deliverable:** A3/pilot charter, SIPOC, baseline, prioritisation matrix, risk controls, ROI, control plan and executive recommendation.

#### Detailed procedure

1. Review the three opportunity briefs and choose one using value, feasibility, risk and time-to-learn.
2. Define customer value, process boundary and accountable owner.
3. Build the current-state evidence and quantify the selected waste or constraint.
4. Use root-cause tools to state the causal hypothesis and simplest countermeasure.
5. Define the AI role, data, human decision rights and fallback.
6. Calculate conservative pilot costs and verified-benefit logic.
7. Write success, harm, stop and revalidation criteria.
8. Build an implementation plan with roles, milestones, review cadence and communication.
9. Create a control plan that sustains the process and AI controls.
10. Present a recommendation to scale, redesign or stop based on evidence.

#### Scenario questions

- Which use case addresses the system constraint?
- What is the simplest informative experiment?
- What are the stop conditions?
- What evidence supports scale, redesign or termination?

#### Evidence and acceptance

- [ ] Selected use case addresses an evidenced system need.
- [ ] Charter includes baseline, target, scope, owner and timebox.
- [ ] Human authority, fallback and stop criteria are explicit.
- [ ] ROI distinguishes projected and verified benefit.
- [ ] Control plan covers process, data, model and adoption measures.

**Verification:** Submit the completed worksheet, calculations or analysis output, and evidence checklist for trainer review.

## Interactive Tools

- **5 Whys:** https://alfredang.github.io/5whys/
- **Fishbone:** https://alfredang.github.io/fishbone/
- **Pareto chart:** https://alfredang.github.io/paretochart/
- **System loop:** https://alfredang.github.io/systemloop/
- **SIPOC:** https://alfredang.github.io/sipoc/

## Sources

- Course listing and registered outcomes: https://www.tertiarycourses.com.sg/wsq-reducing-waste-and-improving-workplace-efficiency-with-lean-six-sigma.html
- Lean manufacturing and five principles: https://www.twi-global.com/technical-knowledge/faqs/faq-what-is-lean-manufacturing
- Lean manufacturing overview: https://en.wikipedia.org/wiki/Lean_manufacturing
- Lean manufacturing topic overview: https://www.sciencedirect.com/topics/engineering/lean-manufacturing
- ASCM lean manufacturing topic: https://www.ascm.org/topics/lean-manufacturing/
- Lean manufacturing benefits and implementation: https://www.netsuite.com/portal/resource/articles/erp/lean-manufacturing.shtml
- Lean manufacturing guide: https://www.planview.com/resources/guide/what-is-lean-manufacturing/
- Lean production topic overview: https://www.sciencedirect.com/topics/economics-econometrics-and-finance/lean-production
- Lean manufacturing overview: https://www.projectmanager.com/blog/what-is-lean-manufacturing
- Training Within Industry and lean: https://www.twi-institute.com/what-is-lean-manufacturing/
- AI in manufacturing use cases: https://www.ibm.com/think/topics/ai-in-manufacturing
- AI in manufacturing: https://www.snowflake.com/en/artificial-intelligence/industries/ai-in-manufacturing/
- AI in manufacturing use cases: https://thinking.inc/en/industry-service/ai-in-manufacturing/
- AI in manufacturing: https://www.autodesk.com/design-make/articles/ai-in-manufacturing
- Manufacturing AI starts with data: https://mitsloan.mit.edu/ideas-made-to-matter/ai-manufacturing-start-data
- Practical AI applications: https://fabrity.com/blog/8-practical-applications-of-ai-in-manufacturing/
- AI in manufacturing opportunities and data barriers: https://www.weforum.org/stories/2024/01/how-we-can-unleash-the-power-of-ai-in-manufacturing/
- AI across engineering, production and supply chains: https://blogs.sw.siemens.com/tecnomatix/ai-in-manufacturing-transforming-engineering-production-and-supply-chains/
- AI in manufacturing guide: https://www.sap.com/resources/ai-in-manufacturing
- Implementing AI in manufacturing: https://www.pwc.com/gx/en/industrial-manufacturing/pdf/intro-implementing-ai-manufacturing.pdf
- NIST AI Risk Management Framework: https://www.nist.gov/itl/ai-risk-management-framework
