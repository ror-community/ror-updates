# ROR Updates
This repository tracks proposed changes that are being reviewed and/or prepared for inclusion in [ROR](https://ror.org/). Proposed changes are reviewed by community curators to determine if they are in scope. Approved changes are then prepared for inclusion in a future ROR release. New and/or updated ROR records follow the ROR metadata schema and [metadata policies](https://github.com/ror-community/ror-updates/wiki/ROR-Metadata-Policies).
# ROR scope
The primary focus of ROR is the “affiliation and funder use case” - proper description of relationships between contributions, research sponsors, publishers, and employers. 

We use “affiliation" and "funder” to describe any formal relationship between a researcher and an organization associated with researchers, including but not limited to their employer, educator, sponsor, or scholarly society. 

We define “research organization” as any organization that conducts, produces, manages, or touches research.
# Criteria for inclusion in ROR
ROR is a registry of top-level research organization affiliations. To be included in the registry, an organization should be:
1. A **top-level entity**, meaning that it is:
- A standalone organization
- Sufficiently independent from other organizations it might be related to
- Not a subdivision within an organization
2. A **research organization**, meaning that it is involved in one or more of the following activities:
- Produces research
- Funds research
- Employs researchers
- Facilitates research
- Manages research
- Publishes research
- Educates researchers
3. Is or will be **used as an affiliation** in published research outputs by **multiple people**, meaning that it is:
- Not a one-person organization or consultancy.
# Requesting changes to ROR
Changes can be proposed by anyone via a [feedback form](https://curation-request.ror.org). 

# Community-based curation model
ROR is employing a community-based curation model to maintain the registry. 

Community-based curation means:
- Anyone can submit a request to add or update ROR
- Leveraging knowledge and expertise from across the community in a scalable way
- Promoting broad community ownership of open infrastructure
- Centralizing curation decisions through a community-based curation board to ensure consistency and integrity of metadata and curation policies at scale across the entire registry

# Curation workflow
Requests submitted via the [feedback form](https://curation-request.ror.org) or by [creating issues](https://github.com/ror-community/ror-updates/issues/new/choose) in this repository go through an initial triage and are added to the [ROR Updates tracker](https://github.com/ror-community/ror-updates/projects/1) for community curators to review. Curators review the requests and decide how they should be processed. Approved requests will end up in the queue for metadata preparation so the changes can be deployed on the ROR production site.  
![ROR Curation Workflow Outline (1)](https://github.com/ror-community/ror-updates/assets/5152876/316d4220-d898-4ad4-b0f0-e94d4a63e816)


# Publishing updates to the registry
The ROR API and data dumps are updated on a rolling basis. Curation requests are reviewed continuously and approved requests are held for deployment in the next release. Completed releases will have detailed [release notes](https://github.com/ror-community/ror-updates/releases) about which records were added and changed.  

# Tracking ROR updates
Anyone can follow the [ROR Updates tracker](https://github.com/ror-community/ror-updates/projects/1) to see the requests being reviewed and to see which changes are being queued up for a future release. If you wish to follow and receive notifications about specific changes, sign in with your Github account and add yourself as a watcher to individual issues. 

# Interpreting Github issues
The Github issues on the [ROR Updates tracker](https://github.com/ror-community/ror-updates/projects/1) have [labels](https://github.com/ror-community/ror-updates/labels) that categorize the requests and provide contextual information for curators. The information in these labels includes:
- **Type of request** (e.g., add record or update record)
- **General priority level** (1/2/3). Level 1 issues are primarily requests to add new entries to ROR. Level 2 issues are metadata changes for fields that impact discoverability, e.g., the primary name in a ROR record. Level 3 issues are metadata changes for other fields. 
- **Estimated effort to research and/or implement (lion/jaguar/kitten)**. "Lion" issues require the most investigation and/or entail the most complex metadata. "Jaguar" issues are a bit more straightforward and faster to process. "Kitten" issues are the most simple and straightforward types of changes to review and implement.
- **Source of request**, i.e., whether the proposed change was requested by the organization associated with the ROR record in question, or by an external party. While anyone can propose changes to ROR, it can sometimes be helpful to know who is requesting the changes.
- **Reasons for certain decisions** - i.e., if a request is declined because the changes are not within scope for ROR to implement, an "out of scope" label will be applied to the issue. 

Issues that are approved for a release will be assigned a milestone tag that corresponds to the release version. 


