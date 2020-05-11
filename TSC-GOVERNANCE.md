# TSC Governance

* [Overview](#overview)
* [Roles and responsibilities](#roles-and-responsibilities)
* [Committers](#committers)
* [Membership](#membership)
* [Meetings](#meetings)
* [Decision Making](#decision-making)
* [Attribution](#attribution)

## <a name="overview"></a>Overview

The ODK project is governed by the Technical Steering Committee (TSC).

## <a name="roles-and-responsibilities"></a>Roles and responsibilities

The TSC is responsible for the overall direction of the project. This includes:
* Suite roadmap (feature addition/removal, tool addition/removal, incorporating community feedback, etc.)
* Forming appropriate suite Working Groups (e.g., User Feedback, Documentation, Translation) to gather the necessary community feedback before making decisions
* The suite's technical resources (e.g., code repositories, servers)
* Maintaining the list of the suite's Committers

Standard operating procedures for the TSC can be found at [here](https://github.com/getodk/governance/blob/master/STANDARD-OPERATING-PROCEDURES.md).

The current TSC members are:
* Yaw Anokwa ([@yanokwa](https://github.com/yanokwa)), [Nafundi](http://nafundi.com/)
* Gareth S. Bestor ([@tiritea](https://github.com/tiritea)), [Objective](https://www.objective.com/)
* Adam Butler ([@adamvert](https://github.com/adamvert)), [eHealth Africa](https://www.ehealthafrica.org/)
* Dan Joseph ([@danbjoseph](https://github.com/danbjoseph)), [American Red Cross](https://www.redcross.org/)
* Aurelio Di Pasquale ([@aurdipas](https://github.com/aurdipas)), [Swiss Tropical and Public Health Institute](https://www.swisstph.ch)
* Martijn van de Rijdt ([@martijnr](https://github.com/martijnr)), [Enketo](http://enketo.org)
* Tom Smyth ([@hooverlunch](https://github.com/hooverlunch)), [Sassafras Tech Collective](http://sassafras.coop/)
* Dickson Ukang'a ([@ukanga](https://github.com/ukanga)), [Ona](https://ona.io/)

## <a name="committers"></a>Committers

Committers are community members who have shown that they are committed to the continued development of the suite through ongoing engagement with the community. Commit/write access allows contributors to more easily carry on with their suite-related activities by giving them direct access to the suite's resources.

The suite's technical resources are managed by the TSC. Individuals making significant and valuable contributions are made Committers and given commit or write access to those resources. These individuals are identified by the TSC and their addition as Committers is discussed during the regular TSC meeting. The process for identifying and granting Committer access is determined by the TSC.

_Note: If you make a significant contribution and are not considered for commit/write access on the appropriate resource, file an issue, post on the forum, or contact a TSC member directly and it will be brought up in the next TSC meeting._

Modifications of project resources are made on a collaborative basis. Anybody may file an issue or propose a modification and it will be considered by project Committers. All changes must be reviewed and accepted by a Committer with sufficient expertise who is able to take full responsibility for the change.

In the case of changes proposed by an existing Committer, an additional Committer is required for review. Consensus should be sought if additional Committers participate and there is disagreement around a particular modification.

Committers may opt to elevate significant or controversial modifications or modifications that have not found consensus to the TSC for discussion by assigning the `tsc-agenda` tag to a pull request or issue or forum post. The TSC should serve as the final arbiter where required.

The current list of Committers is here:
* [https://github.com/orgs/getodk/people](https://github.com/orgs/getodk/people)

## <a name="membership"></a>Membership

TSC membership will be determined via a public application process. The application requirements will focus on relevant experience, contributions to the suite ecosystem, and availability to provide technical direction to the suite.

The initial TSC membership will be determined by the PMC after a public application process and initial members will serve for 1 year.

After the initial selection by the PMC, members will be elected by a 2/3rds (rounded up) majority of the current TSC and serve for a term of 2 years, unless they resign or are removed.

The TSC must have at least three members, but there is no fixed size. The expected target is between 6 and 12, from a minimum of 3 separate organizations, to ensure long-term sustainability, adequate coverage of important areas of expertise, and ability to make decisions efficiently.

There is no specific set of requirements or qualifications for TSC membership beyond these rules. That said, the likely best candidates for TSC membership will be Committers.

The TSC may add additional members by a TSC motion. A TSC member may be removed by voluntary resignation, or by a 2/3rds majority (rounded up).

TSC members are expected to regularly participate in TSC activities. Members who have not consistently taken meaningful actions as TSC members in the past 3 months will be considered for removal. Examples of meaningful actions are participating regularly in calls, reviewing code, committing code, providing technical mentorship, leading working groups, etc.

No more than 1/3 of the TSC members may be affiliated with the same organization. If removal or resignation of a TSC member, or a change of employment by a TSC member, creates a situation where more than 1/2 of TSC membership belong to the same organization, the situation must be immediately remedied by the resignation or removal of one or more TSC members affiliated with the over-represented organization(s).

Changes to TSC membership should be posted in the agenda, and may be suggested as any other agenda item.

## <a name="meetings"></a>Meetings

The TSC will meet regularly (generally every two weeks). The meeting will be run by a moderator chosen by the TSC and each meeting will be conducted and published to a publicly accessible platform (e.g., YouTube). Meeting frequency, times, agenda, and notes will also be published to a publicly accessible platform (e.g., the forum, Google Docs).

The TSC will default to working in public, but sensitive topics (e.g., pre-disclosure security problems, confidential pre-agreement discussions with third parties, personal conflicts among personnel) should only be discussed on private channels.

Items typically discussed by the TSC include suite roadmap, feature addition/removal, etc. Items are added to the TSC agenda which are considered contentious or are modifications of governance, contribution policy, TSC membership, or release process. Working Groups that the TSC forms may also add items to the TSC agenda.

The intention of the agenda is not to approve or review modifications to suite resources. That should happen continuously on the relevant resources and are handled by the larger group of Committers.

Any community member or contributor can ask that something be added to the next meeting's agenda by filing an issue or writing a forum post. Any Committer, TSC member, or the moderator can add the item to the agenda by adding the `tsc-agenda` tag to the issue or post.

Prior to each TSC meeting, the moderator will share the agenda with members of the TSC. TSC members can add any items they like to the agenda at the beginning of each meeting. The moderator and the TSC cannot veto or remove items.

The TSC may invite non-members to participate in a non-voting capacity. These invitees will be listed on the agenda.

The moderator is responsible for summarizing the discussion of each agenda item and publishing it on a publicly accessible platform (e.g., the forum). If appropriate, the moderator will also update the relevant issue, pull request or forum post.

## <a name="decision-making"></a>Decision Making

For internal project decisions, Committers shall operate under Lazy Consensus. The TSC shall establish appropriate guidelines for implementing Lazy Consensus (e.g., expected notification and review time periods).

The TSC follows a Consensus Seeking decision-making model. When an agenda item has appeared to reach a consensus, the moderator will ask "Does anyone object?" as a final call for dissent from the consensus.

If an agenda item cannot reach a consensus, a TSC member can call for either a closing vote or a vote to table the issue to the next meeting. The call for a vote must be approved by a majority of the TSC or else the discussion will continue. If all members of the TSC are not present during the meeting for contentious issues, the final vote should happen asynchronously (e.g., via email). Simple majority wins.

## <a name="amendments"></a>Amendments

This document is owned by the PMC and amendments may only be made by decisions of the PMC.

## <a name="attribution"></a>Attribution

This a derivative work of the [Node.js Project Governance](https://raw.githubusercontent.com/nodejs/nodejs.org/0dd684cf21d278ba8aa178db0a20ebc6d587c58e/locale/en/about/governance.md). This work is licensed under the [MIT](https://opensource.org/licenses/MIT) license with copyright held by Node.js Website WG contributors.
