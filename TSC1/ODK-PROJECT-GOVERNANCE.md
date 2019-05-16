# ODK Project Governance

## Preamble

ODK is an open source project consisting of a collection of tools under a common vision. From time to time, certain other projects adhering to that vision may wish to join the ODK project in order to contribute to and benefit from its brand, community, and vitality. The below lays out the process by which a project may join (and leave) ODK, and the rights and responsibilities associated with being part of ODK.

## Scope

This document applies only to projects governed by the ODK/TSC 1. It does not apply to ODK-X/TSC 2 projects.

  
This document does not apply to ODK “[skunkworks](https://github.com/opendatakit/skunkworks)” projects, which have a separate inception process and do not use “ODK” in their name. A skunkworks project become an ODK tool by meeting the criteria below, just like any other project.

## Definitions

- For the purposes of this document, a project wishing to join ODK will be known as a “tool”. When used in sentences such as “the tool must”, it can be assumed that the tool’s maintainers are the party responsible. 
- “The TSC” is the ODK Technical Steering Committee (TSC 1). 
- “The project” is the ODK project as a whole. 
- The “sponsor” is the person who submits the application to join ODK and serves as the chief point of contact. 

## Admission Criteria

In order to be considered for acceptance, a tool must meet the following mandatory requirements:

- The tool must fit the mission and values of the ODK community. 
- All members of the tool’s community must be willing to abide by the ODK code of conduct. 
- The tool must be useful to many members of the ODK community. 
- The tool must primarily be used to interact with an ODK form, data, tool, specification, or API. 
- The tool must have a permissive open-source license, preferably Apache v2. 
- The tool must be under Git version control. 
- The tool must have at least one individual on the TSC commit to contributing to it. 
  
In addition, the following are strongly recommended and should be considered by the TSC in deciding on admission:

- The tool should have two individuals, from separate organizations, who have demonstrated a commitment to contributing to it regularly. 
- The tool should have an issue tracker for bugs and feature requests. 
- The tool should have substantial user-facing and developer-facing documentation coverage or have documentation as one of the top priorities. 
- The tool should have an automated build or continuous integration workflow that includes automated tests. 
- The tool should have substantial test coverage and/or be committed to achieving comprehensive test coverage as one of its top priorities. 
- The tool should have a support strategy to provide timely support for users. 
- The tool should have a communication strategy to inform users of new features, critical issues, etc. 
- The tool should have a clear process governing the design, development, and release of features and bug fixes. 

## Rights & Responsibilities

Once a tool has joined the ODK project, it, like any other tool, becomes subject to the governance of the project. The sponsor should familiarize themselves with the project’s governance.

In particular, the project governance states that “The TSC has authority over all technical aspects including: tool roadmap, forming appropriate Working Groups to gather the necessary community feedback before making decisions, technical resources (e.g., code repositories, servers), and maintaining the list of Committers.” In practice, the day-to-day operations of the tool’s development may not be greatly affected by joining the ODK project, but the tool’s maintainers should be aware that the TSC’s authority over the tool as defined in the project governance is an important condition of its being considered a member of the ODK project.

Upon joining the ODK project, the tool is entitled to:

- Refer to itself as part of the ODK project. 
- Use the ODK logo as part of its brand. 
- Receive assistance from the TSC in shaping its roadmap and strategy. 
- Receive technical assistance and code reviews from project committers. 
- Maintain existing copyright on any project code, past or future (ODK has no contributor license agreement) 
  
The tool is required to, within a 3 month period:

- Change its name to begin with “ODK” and reflect this change in all notable or prominent places where the tool appears. 
- Move its code repository to reside with the other repositories in the project. 
- Submit a pull request adding the tool alongside the other tools in the project on the Open Data Kit website. 
- Submit a pull request adding the tool to the ODK documentation site. If full documentation is not yet available, at least a minimal description of the tool and its purpose should be added as a placeholder for future, fuller documentation. 
- Announce publicly in the Open Data Kit forum, under the Governance category, that the tool has joined ODK. 

If the tool has not fulfilled these requirements within 3 months it may be considered by the TSC for archiving.

## Joining

A tool that meets the above criteria, is willing to submit to the above requirements, and wishes to join the ODK project should submit a written application in the form of a public post to the Governance category on the Open Data Kit forum. The application should:

- Use the `tsc1` tag and clearly indicate the ODK TSC (as opposed to ODKX) as the recipient. 
- Identify a sponsor—one person who will serve as the main point of contact. 
- Describe the tool’s purpose and history. 
- Explain why the tool wishes to join the ODK project. 
- Demonstrate how the tool meets all the above mandatory criteria and any of the recommended ones. 

Upon receipt of the application, the TSC will place it on the agenda of an upcoming meeting for discussion. The TSC has sole authority over the decision to accept or deny the application, and it may deny the application for any reason. The TSC will use its normal decision making processes to reach a decision and may request further input from the sponsor before doing so. The TSC will notify the sponsor via the forum topic once a decision has been reached.

## Departure/Archiving

A tool may be suitable for archiving in a number of situations:

- It shows clear signs of failing and not progressing. 
- It has lost its maintainers and user base, and there is little or no activity. 
- It has achieved its goals and is complete. 
- Its maintainers no longer wish to be associated with ODK. 
  
The archiving process should be triggered by any member of the TSC who becomes aware of a tool’s suitability for archiving. The said member should request time on a TSC meeting agenda to discuss the archiving. If the TSC decides the tool is suitable for archiving, a clear, public notice should be posted on the Open Data Kit forum in the Governance category notifying the community of the TSC’s intent to archive the tool after 30 days. 

Notwithstanding the above, the TSC may decide to archive a tool at any time and for any reason.

Upon the decision to archive a tool, the following should be undertaken by the TSC:

- The tool should be removed from the website and documentation site. 
- A clear notice should be placed in the README file in the tool’s repository stating that the tool has been archived, is no longer supported. 
- The tool’s repository should be made read-only. 
  
Once a tool has been archived, its maintainers may request transferral of its repository to their ownership. Such request must be approved by a decision of the TSC.

The TSC also reserves the right to delete a tool’s repository after it has been archived. The maintainers must be offered, with reasonable notice, the right to take ownership of the repository before it is deleted.

Portions taken from [https://gitlab.com/librehealth/lsc/community-governance/blob/master/GOVERNANCE.md#project-governance](https://gitlab.com/librehealth/lsc/community-governance/blob/master/GOVERNANCE.md#project-governance) under a CC-BY-4.0 license