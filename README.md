# threat-modelling
A 'game' / workshop developed by a few of us at MYOB (and iterated on afterwards) to enable rapid collaboration between a engineering team and the security team. It gets rave reviews whenever we run it.
We also run it in a variety of formats and facilitation styles, as the rough structure can be repurposed for in-person or remote discussion, or even for asynchronous work.

It counts as both training and a workshop, as it outputs training for:
- developers on how to identify and solve security problems
- security staff on how systems work and how to collaborate with engineering team
- decision makers on how to think about and prioritise security problems

It also outputs a content that can form the basis of a  document that captures security risks, mitigations and decisions that can be incorporated into design and operational documents.

## Agenda and Attendees
The workshop generally consists of 3 phases accross a 90-minute period. While it needs at least one security expert and one engineer who understands the problem/system, the workshop works better with a facilitator (from the security team or a Business Analyst) and up to 10 attendees. Non-technical staff including product or engineering managers often benefit. You can read more about the 'value' that different staff members in the Value section.

## Content
The primary parts of the workshop are
1. 20 mins: An 'Architectural Description' where engineers pick one system and describe what the system is and what it does. Ideally, they should draw or present an architectural diagram (component, network or trust zone). Partipants annotate the diagram to highlight exposure points, sensitive data, vulnerabilities etc.
2. 50 mins: A 'Threat Modelling' activity where participants are given 'threat actor cards' to roleplay how they would attack the system. It consists of
    1. Solo threat brainstorming (20mins): participants write post its of what attacks they might try agains the system. Given they understand the system, they may be able to generate threats that will work, and this should be encouraged. Security staff may coach participants in how they might attack a system or reference STRIDE or another Threat Modelling framework to help coach participants.
    2. Sharing and Prioritisation: Participants share which threat actor they got and their most serious threats with the group (10mins). The most serious threats are then risk assessed (10-20mins if done unilaterally or by consultation)
4. 20 mins: A 'control mitigation' activity where participants identify 'controls' that mitigate the most serious risks are enumerated and assessed for efficacy. Once this is done, the facilitator can help the team recalculate the residual risk of the mitigated threat.
5. 5 mins:  A 'next steps' decision point - where the team can validate
   1. the facilitator or security team highlights if there is any risk or controls they believe must be implemented, or if more work is required before a decision can be made, and assigns next steps before the workshop wraps. Depending on your organisation's cybersecurity maturity, some tangible decisions to recommend that risks should be accepted or commitments from the team that they will mitigate risks are ideal but may be optimistic.

## Materials Required
You will need
 - A whiteboard or computer + screen where you can 'write up' or 'present' the architecture diagram
 - A way to highlight sensitive data, how the system is exposed, user accesses or critical business processes on the diagram (post its? Annotations in a tool?)
 - A way to 'generate threat ideas' (post its? Virtual Board like miro? Directly into the template?)
 - A way to 'vote on and prioritise importance of threats' (if you need materials for that)
 - A way to generate controls (directly into the template)
 - A document or link that describes how your organisation assesses and manages risk
 - Optional: A scribe with a laptop who captures information into a document live as it is generated
 - Optional: a written or digital survey on the workshop to send to participants to get their feedback on the content, facilitation and value so you can make sure you keep engagement high!

## Value
Generally, the workshop is moderately intense, but no more intense than a normal cybersecurity assessment on a solution. However, it generates high CSAT/NPS, provides ancillary training benefit and teamwork/culture.

In general:
- Security teams note teams that undertake 'threat modelling' often proactively implement security improvements because they understand the value. It reverses the onus from Security teams to convince staff to implement controls, and enables them to support teams to manage risks they now understand.
- Business Analysts, Product Owners and Engineering teams note that 'threat modelling' enables them to understand security requirements, whereas offering standards or controls is like presenting them with solutions. They baulk at being told to implement something they don't understand. However, when they understand the importance and can identify alternative, compensating controls and feel like part of the team identifying solutions and options, they understand what threats and risks they are trying to mitigate.
- Managers and decision makers are often able to understand the probability of the risk better when they understand concepts like exposure, vulnerability and threats. This workshop provides a way for those concepts to be introduced where they get an artifact and training that enables their teams to make prioritisation decisions and decide. It also links the 'possible solutions' directly to the 'requirements' and the 'risks' in a simple framework which enables them to understand it.
- Architects, DevOps and other central technical teams can come together to solve security problems.
