# VSP Product Outline - DRAFT!

## Problem Statement
The delivery of high-quality, user-centered digital services for Veterans is currently constrained by the number of DSVA teams available to design, build, and deploy them. It’s difficult for non-DSVA teams to use VSP because the technical components and infrastructure aren’t primarily designed and built to facilitate safe/isolated contributions from multiple external teams in a single ecosystem.

*How might we* build VSP so that technical, design, and product components are useful and sufficiently extensible for non-DSVA teams to build digital services for Veterans?

## North Star Objective
Empower great teams across VA to contribute products/experiences/tools that enable Veterans to more easily and efficiently access their VA benefits and services.

## Desired Outcomes
- “Make the best options the easiest ones”
- Enable diverse teams the flexibility to quickly and easily build great user-centered experiences
- Maintain / improve technical performance and reliability of VA.gov
- Hand VSP and VSA ownership to VA 
- Incentivize innovation, experimentation, and Agile iteration that improve services for Veterans

## KRs Brainstorm (need to pick 5)
_I like this framework: make sure the following concepts are represented across the KRs_
_- Do something good_
_- Prevent something bad_
_- Something delivery-related_
_- Something outcome-related_
_- Something sentimental_

#### In first 8 months…

- > 10 different companies deploy live functionality
- 100% of VSA Teams have DEPO / DSVA lead and VA product owner
- 0 security incidents across all VSP-hosted VSAs
- > 60% of VSAs have launched using beta feature flag model
- > 80% VSAs meeting SLOs
- Per capita volume of Slack activity in Support channel over time
- > 80% of VSA Teams respond with avg positive sentiment
- > 80% of VSAs have had code updated in last 6 months

## VSP Performance Metrics
- Uptime
- Latency
- Speed of CI / CD pipeline
- % test coverage?
- etc

## Biggest pain points
- Current Handbook + checkpoint structure encouraged Waterfall.
- Checklists in their current state didn’t incentivize outcome-driven decision-making.
- Handbook w/o onboarding was hard for VSA teams - made for onerous code reviews.
- When VA stakeholders weren’t bought into the process, regardless of how great the VSA team was, it led to undesirable product decisions.
- VSA teams weren’t discovering errors on their own.
- Bad code contributed without isolation framework in place had wide negative impacts.
- When a VSA needed to be handed off to a different team for longevity, the VSA team didn’t know what info to provide to facilitate a smooth transition.
- When we didn’t catch and fix things early, it was hard to change the course of the train later bc of its momentum.

## Biggest Risks
- If a VSA launches and either isn’t performant or causes negative impact, it will reflect poorly on VSP.
- If process/instrumentation isn’t ready, but we rush to bring VSA Teams through those parts of VSP anyway, we’ll perpetuate the pain points of Apr 2018 - May 2019 and won’t be closer to achieving our desired outcomes.
- If we don’t have funding to apply to the Optional tasks in the near future (next couple of months), we won’t be able to support more than the current external teams (CMS, VA.gov, VA API, Education) and we won’t have MVPs for the full VSP experience - will be missing critical Onboarding and API pieces.
- If we overpack our Sprints, we won’t have time for tech debt or unexpected complexity, and will end up with shoddy, manual-based systems and processes that can’t scale.
- If we don’t make it impossible to ignore issues with product performance, VSA teams will not track/resolve issues with their products’ performance.
- If we continue relying on blocking applications from launching on Platform as a quality management tool, we will not be empowering VA and we will hurt our relationships with stakeholders and VSA teams.
- If we don’t prioritize instrumentation/automation and triage processes early, we will become a full time support/triage team.
- If VA decides not to include long term product/design type work for VSP and instead chooses to go O&M (operations and maintenance) infra support in OY1- ...
- If we keep Engineers in support roles long term, we may lose their talent due to burnout and/or boredom.
- If application maintenance isn’t addressed during intake, it becomes an outstanding risk when the development team transitions off the program (i.e. Drupal CMS, Community Care)

## VSP Near Term Roadmap
1) Create MVPs for most critical pieces of VSP functionality to optimize for 1) mitigating pain points and risks and 2) achieving KRs.
1) Test MVPs of VSP features/services/docs with real VSA Teams. Iterate, and continue testing.
1) Concurrently, as we learn and iterate, define what VSP is (and what it is not) and create outreach materials intended for wide dissemination.
1) Concurrently, compile list of prospective VSA teams and test Intake rules. Iterate, test again.
1) Set expectations (esp wrt intake and onboarding) across VA through comms plan.
1) Continue running intake, iterating on features/processes/docs, supporting VSA teams.

## Assumptions