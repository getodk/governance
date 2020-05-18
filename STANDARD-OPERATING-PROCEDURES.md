# Standard Operating Procedures

## Quick Links

- [Meeting Agendas and Minutes](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA/edit)
- [Meeting History](https://docs.google.com/spreadsheets/d/1xD44Km1p0LXoIjBkGxolPvkhq7OXlxA28CN2LKrsT2A/edit#gid=0)
- [ODK Roadmap](https://github.com/getodk/roadmap/projects/1)
- [Uberconference Room](https://www.uberconference.com/getodk)
- [TSC Forum Category](https://forum.getodk.org/c/governance/tsc)
- [TSC Forum Tag](https://forum.getodk.org/tags/tsc)
- ODK Project Pages: [Briefcase](https://github.com/getodk/briefcase), [Build](https://github.com/getodk/build), [Central](https://github.com/getodk/central), [Collect](https://github.com/getodk/collect), [Documentation](https://github.com/getodk/docs), [JavaRosa](https://github.com/getodk/javarosa), [ODK XForms specification](https://github.com/getodk/xforms-spec), [Validate](https://github.com/getodk/validate), [XLSForm Offline](https://github.com/getodk/xlsform-offline), [XLSForm Online](https://github.com/getodk/xlsform-online)
- [TSC Tool Governance](https://github.com/getodk/governance/blob/master/TOOL-GOVERNANCE.md)
- [TSC Governance Guidelines](https://github.com/getodk/governance/blob/master/TSC-GOVERNANCE.md)
- [Public Governance Page with TSC Members & Photos](https://getodk.org/community/governance/)
- [Meeting Facilitator Checklist](#meeting-facilitator-checklist)

For more details on the TSC's responsibilities, see the [TSC governance](https://github.com/getodk/governance/blob/master/TSC-GOVERNANCE.md) approved on Nov 7, 2017.

## Communications

The TSC engages in various sorts of communication with different audiences. Is it important to understand which communication channel is appropriate for which message.

| Venue | Channel | Visibility | Purpose |
|---|---|---|---|
| UberConference | [Conference Room](https://www.uberconference.com/getodk) | Anyone can join, previous calls are not visible | For meetings and synchronous communication. |
| Forums | [tsc Tag](https://forum.getodk.org/tags/tsc) | Usually public | Used for public posts with TSC-related content, usually in the [Governance](https://forum.getodk.org/c/governance) category but not always. |
| Forums | [tsc Category](https://forum.getodk.org/c/governance/tsc) | TSC-only | For private conversations. |
| Forums | [@TSC Mention](https://forum.getodk.org/search?q=@TSC) | Public or private, depending on location used | Include in post to request action from TSC. ONLY TSC can use it, and should be used sparingly. Somewhat like a TSC mailing list. |
| Forums | [Meeting Topic](https://forum.getodk.org/search?q=TSC%20Call) | Public | Topics created for each meeting. Venue for TSC agenda requests from public. |
| Slack | [#tsc, #tsc-pulse Channels](https://getodk.slack.com/channels/tsc) | TSC-only | For quick, private ephemeral conversation. |

## Process

The TSC meets every other Wednesday for 1 hour on [Uberconference](https://www.uberconference.com/getodk). Meetings are open for non-TSC members to listen. See meeting announcements for dates and times.

Meetings are led by a rotating facilitator. The facilitator is responsible for generating an agenda (see below). Anyone can propose agenda items by commenting on the meeting announcement post.

The agenda includes time caps for each item. A time keeper is selected at the beginning of each meeting and is responsible for stopping discussion when time is up.

The TSC uses [consensus-seeking decision-making](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making). When an agenda item has appeared to reach consensus, the facilitator asks for any dissent. If there is dissent, a vote on the issue can be called by any member.

As much as possible, the TSC operates in public.

## Adding new members

To add new members, a TSC member will send a Google Forms ballot to all TSC members via a private channel. The ballot will have a randomized list of candidate names, with links to their application, and a Yes/No option for each candidate. There will also be a secret passphrase question that members can use to ensure their vote has been counted. After a predetermined period (typically 72 hours), the votes will be counted and the resulting spreadsheet will be made public. The election will be valid only if the results have the correct number of votes and all members can see their secret passphrase.

## Adding new committers

The [TSC governance](https://github.com/getodk/governance/blob/master/TSC-GOVERNANCE.md) requires that the TSC choose a process for adding new committers. Because discussions about specific community members are sensitive, nominations and voting occurs in [the private TSC forum category](https://forum.getodk.org/c/governance/tsc). Selection of a new committer requires consensus approval: three binding +1 votes and no binding -1 votes are required over a 72 hour period. Further, the three binding votes must be from different organizations.

## Roadmap

The purpose of the roadmap is to document and track proposed changes to the ODK suite of tools. The TSC maintains this roadmap to ensure a coherent and orderly evolution of the tools. Any TSC member can change the roadmap, but changes should typically be made only after consultation with other TSC members.

The roadmap is maintained in [a project in the roadmap repo](https://github.com/getodk/roadmap/projects/1) and has the following categories.

* Proposed: items that are currently being discussed, preferably on a forum topic.
* Under Review: items that have recently been, or currently are, on a TSC agenda for review.
* Approved: items that have been approved by TSC but not yet assigned to a specific owner. Approved items must have an associated issue. Typically these items are planned for release in the next 6 months.
* In Progress: items whose issue has been assigned to an owner and is currently being worked on. Typically these items will be completed in the next 3 months.
* Done: items whose issue have been closed. Typically these items are removed from the roadmap 1 month after completion.

Items on the roadmap should meet one of these requirements:
* Major change to governance, specifications/APIs, or two or more tools.
* Planned breaking change to any tool.
* Deemed noteworthy by a lead developer or TSC members.

TSC members move items through these categories, starting at Proposed and finishing at Done.

Prior to TSC approval, items can be vaguely specified. Discussions to refine these items should take place in a Google Doc, on a user-facing [features category](https://forum.getodk.org/c/features) forum topic, or developer-facing [development category](https://forum.getodk.org/c/features) forum topic or GitHub issue.

If a TSC member deems an item ready for approval, the member can create a [roadmap issue](https://github.com/getodk/roadmap) issue or an issue in the relevant tool's repo. Any item can be discussed by the TSC, but items must have a issue before they can be approved by the TSC. Once approved, the issue becomes the "ground truth" for the item.

## Lazy consensus guidelines

The TSC-GOVERNANCE document specifies: "For internal project decisions, Committers shall operate under Lazy Consensus. The TSC shall establish appropriate guidelines for implementing Lazy Consensus (e.g., expected notification and review time periods)." 

This section lays out those guidelines. Our goal is to allow sufficient time for thoughtful, asynchronous deliberation and feedback by the TSC without unduly impeding the work of those in need of a decision.

If a decision from the TSC is called for in a given matter, a proposal should be made by a committer or TSC member and it should have a deadline included. The TSC must be notified by being @mentioned in a post on the forum. Everyone on the forum can @mention the TSC and the notifications will also appear in #tsc-pulse on Slack.

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
    1. Look at the [roadmap](https://github.com/getodk/roadmap/projects/1) for potential agenda items.
    1. For substantive agenda items:
        1. list the goal(s) of the discussion and any things participants should do to prepare for it.
        1. Check in with the presenter to ensure they are ready to present and get a feel for what the discussion will consist of. This ensures you can facilitate it well.
1. Create a thread for the meeting on the [forum](https://forum.getodk.org/).
    1. Title: ODK TSC Call - YYYY-MM-DD
    1. Category: Development
    1. Tags: `tsc`, `tsc-meeting`
    1. Date/Time: Date and time of the call (see previous meeting minutes if unsure of time)
    1. Content:
        ```
        These calls bring together the Technical Steering Committee for the ODK suite (@TSC) to discuss roadmaps, working groups, and other issues of technical governance. Everyone is welcome to come to these calls, but only TSC members may talk.

        The calls are held every two weeks in [our UberConference room](https://uberconference.com/getodk). We put the agenda, audio, and transcript of every call [in this document](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA).

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

* Google Docs/Drive - should be owned by getodk@gmail.com (TSC owns that account)
    * If you create a Google Drive asset that is important for the project and should be long-lived, please transfer ownership to getodk@gmail.com .
* UberConference Room - owned by getodk@gmail.com 
* GitHub projects - owned by the Get ODK GitHub organization
