# ODK TSC Landing Page

The Technical Steering Committee is the technical governing body for Open Data Kit 1 core projects.

## Quick Links

- [Meeting Agendas and Minutes](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA/edit)
- [Agenda Item Parking Lot](https://docs.google.com/spreadsheets/d/15haxZxYvl6BcaPLGw-3zctzUQad8F3hCYqsnD5ylqdo/edit#gid=0)
- [ODK Roadmap](https://github.com/opendatakit/roadmap/projects/1)
- [Uberconference Room](https://www.uberconference.com/opendatakit)
- [TSC Forum Category](https://forum.opendatakit.org/c/governance/tsc)
- [TSC Forum Tag](https://forum.opendatakit.org/tags/tsc)
- ODK Project Pages: [Briefcase](https://github.com/opendatakit/briefcase), [Build](https://github.com/opendatakit/build), [Collect](https://github.com/opendatakit/collect), [Documentation](https://github.com/opendatakit/docs), [JavaRosa](https://github.com/opendatakit/javarosa), [ODK XForms specification](https://github.com/opendatakit/xforms-spec), [Validate](https://github.com/opendatakit/validate), [XLSForm offline](https://github.com/opendatakit/xlsform-offline), [XLSForm online](https://github.com/opendatakit/xlsform-online)
- [Public Governance Page with TSC Members & Photos](https://opendatakit.org/community/governance/)

For more details on the TSC's responsibilities, see the [TSC governance](https://github.com/lognaturel/governance/blob/master/TECHNICAL-STEERING-COMMITTEE.md) approved on Nov 7, 2017.

## Communications
The TSC engages in various sorts of communication with different audiences. Is it important to understand which communication channel is appropriate for which message.

| Venue | Channel | Visibility | Purpose |
|---|---|---|---|
| UberConference | [Conference Room](https://www.uberconference.com/opendatakit) | Anyone can join, previous calls are not visible | For meetings and synchronous communication. |
| Forums | [**tsc** Tag](https://forum.opendatakit.org/tags/tsc) | Usually public | Used for public posts with TSC-related content, usually in the [Governance](https://forum.opendatakit.org/c/governance) category but not always. |
| Forums | [TSC Category](https://forum.opendatakit.org/c/governance/tsc) | TSC-only | For private conversations. |
| Forums | [**@TSC** mention](https://forum.opendatakit.org/search?q=%40TSC%20) | Public or private, depending on location used | Include in post to request action from TSC. ONLY TSC can use it, and should be used sparingly. Somewhat like a TSC mailing list. |
| Forums | [Meeting topic](https://forum.opendatakit.org/search?q=ODK%201%20TSC%20Call) | Public | Topics created for each meeting. Venue for TSC agenda requests from public. |
| Slack | [#tsc](https://opendatakit.slack.com/channels/tsc) | Anyone can join, new members can see history | For quick, semi-private ephemeral conversation. |

## Process
The TSC meets every other Wednesday for 1 hour starting at 16:00 London time on [Uberconference](https://www.uberconference.com/opendatakit). Meetings are open for non-TSC members to listen.

Meetings are led by a rotating facilitator. The facilitator is responsible for generating an agenda (see below). Anyone can propose agenda items by commenting on the meeting announcement post.

The agenda includes time caps for each item. A time keeper is selected at the beginning of each meeting and is responsible for stopping discussion when time is up.

The TSC uses [consensus-seeking decision-making](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making). When an agenda item has appeared to reach concensus, the facilitator asks for any dissent. If there is dissent, a vote on the issue can be called by any member.

As much as possible, the TSC operates in public.

## Adding new committers
The [TSC governance](https://github.com/opendatakit/governance/blob/master/TECHNICAL-STEERING-COMMITTEE.md) requires that the TSC choose a process for adding new committers. Because discussions about specific community members are sensitive, nominations and voting occurs in [the private TSC forum category](https://forum.opendatakit.org/c/governance/tsc). Selection of a new committer requires consensus approval as described in the [PMC governance](https://github.com/opendatakit/governance/blob/master/GOVERNANCE.md#types-of-approval): three binding +1 votes and no binding -1 votes are required over a 72 hour period. Further, the three binding votes must be from different organizations.

## Roadmapping
Most project decisions are made through [lazy consensus](https://github.com/opendatakit/governance/blob/master/GOVERNANCE.md#lazy-consensus). The TSC is responsible for maintaining a roadmap to ensure a coherent evolution of the core tools and to guide contributions from community members. The TSC is also the final authority for specifying larger or more controversial features.

The roadmap is maintained in [the Roadmap GitHub project](https://github.com/opendatakit/roadmap/projects/1).

The typical process is:
- Any community member describes a feature [in the forum Features category](https://forum.opendatakit.org/c/features) and high-level discussion occurs
- A TSC member takes all the feedback from the forum and writes a specification in a [Roadmap repository](https://github.com/opendatakit/roadmap) issue
- The TSC discusses and refines specifications during its meetings
- Accepted specifications are placed on the [roadmap](https://github.com/opendatakit/roadmap/projects/1)

## Meeting Facilitator Checklist
1. Ensure a thread for the meeting is present on the forum. 
    1. Title: ODK 1 TSC Call - YYYY-MM-DD
    2. Category: Development
    3. Tags: `tsc`
    4. Date/Time: Date of the call, 4pm London time (search "London" in the timezone dropdown)
    5. Content:
        ```
        ODK 1 TSC calls bring together the Technical Steering Committee to discuss roadmaps, 
        working groups, and other issues of technical governance. Everyone is welcome to 
        come to these calls, but only TSC members may talk.

        The calls are held every two weeks in 
        [our UberConference room](https://uberconference.com/opendatakit) from 16-17 London time. 
        We put the agenda, audio, and transcript of every call 
        [in this document](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA).
        
        Our next call will be Wed, ENTER_DATE_HERE, from 16-17 London time 
        ([see in your timezone](http://www.thetimezoneconverter.com/?t=16&tz=London)).
        
        If there are topics you would like to add to the TSC's agenda, please comment below. :point_down:
        ```
2. Construct agenda.
    1. Open [agenda document](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA/edit).
    2. Create a new page (Cmd+Enter or Insert  &gt; Break &gt; Page Break) for the meeting.
    3. Copy the agenda template, found at the very bottom of the document, to that page.
    4. Copy action items from the previous meeting into the new agenda for follow up.
    5. If any items from the previous meeting agenda require more discussion, consider adding them to the current meeting or the parking lot.
    6. Look in the [parking lot](https://docs.google.com/spreadsheets/d/15haxZxYvl6BcaPLGw-3zctzUQad8F3hCYqsnD5ylqdo/edit#gid=0) for potential agenda items.
    7. Also check for any agenda item requests in the above forum thread. If something from the thread doesn’t make it into the meeting, put it in the parking lot.
4. At least one week before the meeting, send out the agenda and a reminder of the meeting by placing a link to the agenda document in the meeting thread and mentioning **@TSC** in the post. Calendar reminders can be helpful to get it out on time.
5. Run the meeting.
    1. Arrive 5 minutes prior to start time to ensure connected, room setup, etc.
    2. Work through the agenda, keeping note of the time.
6. Wrap up.
    1. Remind PMC member to add chat transcript and audio links to the minutes.

## Asset Ownership
It is important that key group assets are owned by organizational accounts rather than individuals. The group's assets currently include:

* Google Docs - should be owned by opendatakit.org@gmail.com (PMC owns that account)
* UberConference Room - owned by opendatakit.org@gmail.com
* GitHub projects - owned by the opendatakit GitHub organization
