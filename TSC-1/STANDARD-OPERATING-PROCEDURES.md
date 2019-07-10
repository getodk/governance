# Standard Operating Procedures

## Quick Links

- [Meeting Agendas and Minutes](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA/edit)
- [Meeting History](https://docs.google.com/spreadsheets/d/1xD44Km1p0LXoIjBkGxolPvkhq7OXlxA28CN2LKrsT2A/edit#gid=0)
- [ODK Roadmap](https://github.com/opendatakit/roadmap/projects/1)
- [Uberconference Room](https://www.uberconference.com/opendatakit)
- [TSC-1 Forum Category](https://forum.opendatakit.org/c/governance/tsc-1)
- [TSC-1 Forum Tag](https://forum.opendatakit.org/tags/tsc-1)
- ODK Project Pages: [Briefcase](https://github.com/opendatakit/briefcase), [Build](https://github.com/opendatakit/build), [Collect](https://github.com/opendatakit/collect), [Documentation](https://github.com/opendatakit/docs), [JavaRosa](https://github.com/opendatakit/javarosa), [ODK XForms specification](https://github.com/opendatakit/xforms-spec), [Validate](https://github.com/opendatakit/validate), [XLSForm offline](https://github.com/opendatakit/xlsform-offline), [XLSForm online](https://github.com/opendatakit/xlsform-online)
- [TSC 1 Tool Governance](https://github.com/opendatakit/governance/blob/master/TSC-1/TOOL-GOVERNANCE.md)
- [TSC Governance Guidelines](https://github.com/opendatakit/governance/blob/master/TSC-GOVERNANCE.md)
- [Public Governance Page with TSC Members & Photos](https://opendatakit.org/community/governance/)
- [Meeting Facilitator Checklist](#meeting-facilitator-checklist)

For more details on the TSC's responsibilities, see the [TSC governance](https://github.com/opendatakit/governance/blob/master/TSC-GOVERNANCE.md) approved on Nov 7, 2017.

## Communications

The TSC engages in various sorts of communication with different audiences. Is it important to understand which communication channel is appropriate for which message.

| Venue | Channel | Visibility | Purpose |
|---|---|---|---|
| UberConference | [Conference Room](https://www.uberconference.com/opendatakit) | Anyone can join, previous calls are not visible | For meetings and synchronous communication. |
| Forums | [tsc-1 Tag](https://forum.opendatakit.org/tags/tsc-1) | Usually public | Used for public posts with TSC-related content, usually in the [Governance](https://forum.opendatakit.org/c/governance) category but not always. |
| Forums | [tsc-1 Category](https://forum.opendatakit.org/c/governance/tsc-1) | TSC-only | For private conversations. |
| Forums | [@TSC-1 Mention](https://forum.opendatakit.org/search?q=@TSC-1) | Public or private, depending on location used | Include in post to request action from TSC. ONLY TSC can use it, and should be used sparingly. Somewhat like a TSC mailing list. |
| Forums | [Meeting Topic](https://forum.opendatakit.org/search?q=TSC-1%20Call) | Public | Topics created for each meeting. Venue for TSC agenda requests from public. |
| Slack | [#tsc-1, #tsc-1-pulse Channels](https://opendatakit.slack.com/channels/tsc-1) | TSC-only | For quick, private ephemeral conversation. |

## Process

The TSC meets every other Wednesday for 1 hour on [Uberconference](https://www.uberconference.com/opendatakit). Meetings are open for non-TSC members to listen. See meeting announcements for dates and times.

Meetings are led by a rotating facilitator. The facilitator is responsible for generating an agenda (see below). Anyone can propose agenda items by commenting on the meeting announcement post.

The agenda includes time caps for each item. A time keeper is selected at the beginning of each meeting and is responsible for stopping discussion when time is up.

The TSC uses [consensus-seeking decision-making](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making). When an agenda item has appeared to reach consensus, the facilitator asks for any dissent. If there is dissent, a vote on the issue can be called by any member.

As much as possible, the TSC operates in public.

## Adding new members

To add new members, a TSC member will send a Google Forms ballot to all TSC members via a private channel. The ballot will have a randomized list of candidate names, with links to their application, and a Yes/No option for each candidate. There will also be a secret passphrase question that members can use to ensure their vote has been counted. After a predetermined period (typically 72 hours), the votes will be counted and the resulting spreadsheet will be made public. The election will be valid only if the results have the correct number of votes and all members can see their secret passphrase.

## Adding new committers

The [TSC governance](https://github.com/opendatakit/governance/blob/master/TSC-GOVERNANCE.md) requires that the TSC choose a process for adding new committers. Because discussions about specific community members are sensitive, nominations and voting occurs in [the private TSC forum category](https://forum.opendatakit.org/c/governance/tsc-1). Selection of a new committer requires consensus approval as described in the [PMC governance](https://github.com/opendatakit/governance/blob/master/PMC-GOVERNANCE.md#types-of-approval): three binding +1 votes and no binding -1 votes are required over a 72 hour period. Further, the three binding votes must be from different organizations.

## Roadmap

The purpose of the roadmap is to document and track proposed changes to the ODK suite of tools. The TSC maintaining this roadmap to ensure a coherent and orderly evolution of the tools. Any TSC member can change the roadmap, but changes should typically be made only after consultation with other TSC members.

The roadmap is maintained in [the Roadmap GitHub project](https://github.com/opendatakit/roadmap/projects/1).

### Roadmap categories
* **"Proposed"**: ideas or new features that are currently being discussed and details worked out, preferably via a Forum thread.
* **"Under Review"**: roadmap items that recently have, or currently are, on a TSC agenda for review.
* **"Approved"**: roadmap items that have been approved by TSC consensus (but not yet assigned to a specific developer). All approved items must have an associated GitHub issue. Typically these are planned for release in the next 1-6 months.
* **"In Progress"**: roadmap items whose GitHub issue has been assigned to a developer (or owner) and is being worked on. Typically these will be completed in the next 1-3 months.
* **"Done"**: roadmap items whose GitHub issue has been closed (ie completed). Done items will be purged from appearing on this roadmap after approx 1 month.

Features will typically progress in a somewhat formal fashion through these category stages, with specific recommended requirements needing to be met to progress from one stage to the next (although anyone with permission may add/move items from categories at any time). Specifically, prior to TSC approval, features, new roadmap ideas, project-related proposals, etc can be somewhat nebulous and may be discussed in a variety of suitable forums; eg simply placeholder notes in the roadmap, or ongoing public discussions in a related [ODK Features](https://forum.opendatakit.org/c/features) forum thread, or more development-focused discussion in an associated GitHub issue, etc. At an appropriate time a TSC member may take any feedback and create a [Roadmap repository](https://github.com/opendatakit/roadmap) issue. Any "Proposed" roadmap issue may then be discussed and refined during subsequent TSC meetings. Once a new feature or proposal is formally 'approved' (TDB) by the TSC, it then needs to exist as a specific GitHub issue associated with a specific GitHub project (including governance) for tracking purposes. The state of the feature/proposal in the roadmap should then mirror its GitHub state, thus reducing inconsistencies; its GitHub issue being the ground-truth.

## Lazy consensus guidelines

The TSC-GOVERNANCE document specifies: "For internal project decisions, Committers shall operate under Lazy Consensus. The TSC shall establish appropriate guidelines for implementing Lazy Consensus (e.g., expected notification and review time periods)." 

This section lays out those guidelines. Our goal is to allow sufficient time for thoughtful, asynchronous deliberation and feedback by the TSC without unduly impeding the work of those in need of a decision.

If a decision from the TSC is called for in a given matter, a proposal should be made by a committer or TSC member and it should have a deadline included. The TSC must be notified by being @mentioned in a post on the forum. Everyone on the forum can @mention the TSC and the notifications will also appear in #tsc-1-pulse on Slack.

TSC members have at least 72 hours (3 days) to object to proposals. Controversial or breaking changes (e.g., spec additions, feature removal, governance changes) require at least 120 hours (5 days) to object. TSC members can request more time (typically no more than a doubling of the initial time).

TSC members should acknowledge reading the proposal (preferably with a comment) so there is a visible record of their approval. If there are no objections, the proposal can proceed. If there are objections, there should be discussion until there are no more objections or the proposal is withdrawn or rejected.

Asynchronous decisions of the TSC may be made only via the forum, and not GitHub PRs (e.g., for the website) or Slack conversations or emails. This is by design. We want to have a single place (the forum) where all TSC members are expected to respond.

## Meeting Facilitator Checklist

### Pre-preparing

When you are assigned to be facilitator, you may want to set a calendar reminder to do the preparation steps below at least a week before the meeting.

### Preparing

At least one week before the meeting:

1. Construct the agenda.
    1. Open [agenda document](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA/edit).
    1. Create a new page (Cmd+Enter or Insert &gt; Break &gt; Page Break) for the meeting.
    1. Copy the agenda template, found at the very bottom of the document, to that page.
    1. Copy action items from the previous meeting into the new agenda for follow up.
    1. If any items from the previous meeting agenda require more discussion, consider adding them to the current meeting or the parking lot.
    1. Look in the [parking lot](https://docs.google.com/spreadsheets/d/15haxZxYvl6BcaPLGw-3zctzUQad8F3hCYqsnD5ylqdo/edit#gid=0) for potential agenda items.
    1. For substantive agenda items:
        1. list the goal(s) of the discussion and any things participants should do to prepare for it.
        1. Check in with the presenter to ensure they are ready to present and get a feel for what the discussion will consist of. This ensures you can facilitate it well.
1. Create a thread for the meeting on the [forum](https://forum.opendatakit.org/).
    1. Title: ODK TSC 1 Call - YYYY-MM-DD
    1. Category: Development
    1. Tags: `tsc-1`, `tsc-meeting`
    1. Date/Time: Date and time of the call (see previous meeting minutes if unsure of time)
    1. Content:
        ```
        These calls bring together the Technical Steering Committee for the ODK suite (@TSC-1) to discuss roadmaps, working groups, and other issues of technical governance. Everyone is welcome to come to these calls, but only TSC members may talk.

        The calls are held every two weeks in [our UberConference room](https://uberconference.com/opendatakit). We put the agenda, audio, and transcript of every call [in this document](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA).

        Our next call will be Wed, ENTER_DATE_ONLY_HERE. The meeting time should be shown in your timezone above.

        The agenda is tentatively as follows:

        PASTE_AGENDA_HERE

        The agenda can also be seen in the [agenda document](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA/edit#)

        If there are topics you would like to add to the TSC's agenda, please comment below. :point_down:
        ```
1. Monitor the meeting thread for any agenda item requests, adjusting the agenda as needed. If something from the thread doesn’t make it into the meeting, put it in the parking lot.

### Running the Meeting

1. Arrive 5 minutes prior to start time to ensure connected, room setup, etc.
1. Work through the agenda, keeping note of the time.

### Wrapping Up

1. Remind @yanokwa to add chat transcript and audio links to the minutes.
1. Add an entry to the [meeting history list](https://docs.google.com/spreadsheets/d/1xD44Km1p0LXoIjBkGxolPvkhq7OXlxA28CN2LKrsT2A/edit#gid=0).
2. Review next meeting time. Ask @yanokwa to update calendar invite time and invitees when necessary.

## Asset Ownership

It is important that key group assets are owned by organizational accounts rather than individuals. The group's assets currently include:

* Google Docs/Drive - should be owned by opendatakit.org@gmail.com (PMC owns that account)
    * If you create a Google Drive asset that is important for the project and should be long-lived, please transfer ownership to opendatakit.org@gmail.com.
* UberConference Room - owned by opendatakit.org@gmail.com
* GitHub projects - owned by the opendatakit GitHub organization
