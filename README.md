# threat-modelling
A 'game' / workshop developed by a few of us at MYOB (and iterated on afterwards) to enable rapid collaboration between a engineering team and the security team. It gets rave reviews whenever we run it.
We also run it in a variety of formats and facilitation styles, as the rough structure can be repurposed for in-person or remote discussion, or even for asynchronous work.

It counts as both training and a workshop, as it outputs training for:
- developers on how to identify and solve security problems
- security staff on how systems work and how to collaborate with engineering team
- decision makers on how to think about and prioritise security problems

It also outputs a content that can form the basis of a  document that captures security risks, mitigations and decisions that can be incorporated into design and operational documents.

## Agenda and Attendees
The workshop consists of 3 phases accross a 90-minute period, and needs at least one security expert and one engineer who understands the problem/system. The workshop works better with a high-quality facilitator (from the security team or a BA) and up to  10 attendees. Non-technical staff including product or engineering managers often benefit. You can read more about the 'value' that different staff members in the Value section.

## Content
The primary parts of the workshop are
1. 20 mins: An 'Architectural Description' where engineers present a diagram of their system, that is then annotated to and added to by the joint team to expose sensitive data, exposure points
2. 50 mins: A 'Threat Modelling' activity where participants are given 'threat actor cards' to roleplay, and then think about how they would attack their system. There is a solo brainstorming part (20mins) where security staff support 1:many and then a group brainstorming part where all teams provide their most serious (or all) threats their threat actors have generated and share who they were (20mins). The most serious threats are then risk assessed (10-20mins if done unilaterally or by consultation)
3. 20 mins: A 'control mitigation' activity, where the 'controls' that mitigate the most serious risks are enumerated and assessed for efficacy. Once this is done, the residual risk of 1 threat can be calculated.
4. 5 mins:  A 'next steps' decision point - the facilitator or security team highlights if there is any risk or controls they believe must be implemented, or if more work is required before a decision can be made, and assigns next steps before the workshop wraps. Depending on your organisation's cybersecurity maturity, some tangible decisions to recommend that risks should be accepted or commitments from the team that they will mitigate risks are ideal but may be optimistic.

## Materials Required
You will need
 - A whiteboard or computer + screen where you can 'write up' or 'present' the architecture diagram
 - A way to highlight sensitive data, how the system is exposed, user accesses or critical business processes on the diagram (post its? Annotations in a tool?)
 - A way to 'generate threat ideas' (post its? Virtual Board like miro? Directly into the template?)
 - A way to 'vote on and prioritise importance of threats' (if you need materials for that)
 - A way to generate controls (directly into the template)
 - A document or link that describes how your organisation assesses and manages risk
 - Optional: A scribe with a laptop who captures information into a document live as it is generated


## Value
Generally, the workshop is moderately intense for workload but generates high CSAT/NPS.

In general:
- Security teams note teams that undertake 'threat modelling' often proactively implement security improvements because they understand the value. It reverses the onus from Security teams to convince staff to implement controls, and enables them to support teams to manage risks they now understand.
- Business Analysts, Product Owners and Engineering teams note that 'threat modelling' enables them to understand security requirements, whereas offering standards or controls is like presenting them with solutions. They baulk at being told to implement something they don't understand. However, when they understand the importance and can identify alternative, compensating controls and feel like part of the team identifying solutions and options, they understand what threats and risks they are trying to mitigate.
- Managers and decision makers are often able to understand the probability of the risk better when they understand concepts like exposure, vulnerability and threats. This workshop provides a way for those concepts to be introduced where they get an artifact and training that enables their teams to make prioritisation decisions and decide. It also links the 'possible solutions' directly to the 'requirements' and the 'risks' in a simple framework which enables them to understand it.
- Architects, DevOps and other central technical teams can come together to solve security problems.
