
## Create Topic Guides for New Users - Tahoe-LAFS

### About Tahoe-LAFS and the Solution We Need
Founded in 2007, [Tahoe-LAFS](https://tahoe-lafs.org/trac/tahoe-lafs)
is the first FOSS that allows for secure, truly
private storage, independent of provider. It does this by creating encrypted,
redundant pieces of files, known as _shares_, and distributes those shares to
separate storage nodes. 
Because the shares are redundant, data is _secure_ from multiple attacks to
servers.
Because shares must be reassembled and decrypted to retrieve the data, data is
_private_.

So what's the problem? Tahoe-LAFS' documentation has been written piecemeal over
the course of its history. This creates a slightly disjointed, sometimes out-of-date
feel for much of our documentation.
We need documentation that can reach users in 2021 who would benefit from Tahoe-LAFS'
privacy-preserving capabilities.
For this project, a set of six user guides will be written, each covering a specific topic
or usage of Tahoe-LAFS.
We will be focusing heavily on making sure the first three guides are rewritten to be
as user-friendly and welcoming as possible to new users.
The second set of guides does not currently exist and would be of interest to
those seeking to make more of Tahoe-LAFS' capabilities, as well as integrate it
into their own projects.

### The Impact of Your Work
Tahoe-LAFS is already being used in a variety of projects to safeguard
individual privacy, from human rights defenders under surveillance to products
used to mitigate the impact of cyber attacks. The guides you write would allow
anyone worldwide to install and use a safe, trusted solution to secure file storage,
independent of any provider. We suspect that Tahoe-LAFS would be hugely useful
to new users in regions where individuals might face threats to their privacy
and consequences from those threats ranging from social exclusion 
to imprisonment and torture.

## Project Scope and Milestones
Tahoe-LAFS can appear a bit arcane to the outsider, and we have organized the
project to provide a reasonable learning curve to our writer.
The scope of the project will be six topic guides of increasing technical difficulty.
These topic guides will be written in two phases.
The first phase is meant to familiarize a technical writer with Tahoe-LAFS' most basic operations,
and the second phase is more challenging,
requiring not just technical skill but also the Tahoe-LAFS knowledge gained in the first phase.

### Phase 1

#### Milestone 1 (approx. 4-6 weeks)

 - Audit existing documentation against the goals of the first set of
   guides, being in close communication with Tahoe-LAFS' mentor
 - Write first set of guides, on the three most basic Tahoe-LAFS
   functions, including screenshots when appropriate:
	 - Installation
	 - Consuming Storage
	 - Providing Storage

#### Milestone 2 and first checkpoint (approx. 1-2 weeks)

 - Guides will be tested for completeness and accuracy by Tahoe-LAFS
   community members
 - Rewrites/edits

### Phase 2

#### Milestone 3 (approx. 6-8 weeks)

 - Audit existing documentation with goals of second set of topics
 - Write second set of guides, on more sophisticated Tahoe-LAFS
   functions, including screenshots when appropriate
	 - How to run a friend net
	 - Running hybrid local cloud grid, with a backup in the cloud
	 - Integrating Tahoe-LAFS as a storage layer in your app

#### Milestone 4 and second checkpoint (approx. 1-2 weeks)

 - Guides will be tested for completeness and accuracy by Tahoe-LAFS
   community members
 - Rewrites/edits

#### Milestone 5 (approx. 1-2 weeks)
			
 - Go through the documentation that was not used to produce the topic
   guides and organize for relevance

#### Milestone 6 (approx. 1-2 weeks)

 - Collect project learnings
 - Create a roadmap for future projects

### How we’ll measure success
The purpose of this project is primarily to provide guides to potential new
users. 
We would also use this project to test the feasibility of creating
a role for a technical writer in our organization.

Our success criteria are as follows:

 - Positive feedback from reviewers at Milestone 2
 - Positive feedback from reviewers at Milestone 4
 - A Road Map for the next round of documentation
   projects after Milestone 6
 - Views on our Discourse for these guides would be at least 20% of total views
 on the site

##  Proposed Budget
The bulk of our budget would go to our technical writer, with stipends to be given to volunteers from the community 
who provide exemplary support, particularly in Milestones 2 & 4.

Budget item | Amount(USD) | Running Total(USD) | Notes/justifications
------------|--------|---------------|---------------------
Technical writer audit, update, test, and publish new topic guides for Tahoe-LAFS | 9,000.00 | 9000.00
Volunteer stipends  | 1000 | 10,000.00 | 2 volunteer stipends x 500 each
TOTAL |  | 10,000.00 |
## Skills needed

Ability to communicate issues and questions as they arise, via IRC or Slack.

Experience in information architecture or document auditing would be useful,
in addition to experience working with and using decentralized and P2P technologies.

Past experience with installing Tahoe-LAFS or contributing to Tahoe-LAFS is a plus.
Take a look at [our current installation guide](https://tahoe-lafs.readthedocs.io/en/latest/INSTALL.html)
and imagine if you can make improvements to it.

We use `Sphinx` and you will naturally be working on our public repo.

#### Additional information

We know our writers are skilled and capable, but sometimes issues or roadblocks might arise. 
So we expect our writers to communicate with us in a timely manner.
Long absences or unresponsiveness might result in termination of the relationship. 
Additionally, writers are expected to follow our [Code of Conduct](https://github.com/tahoe-lafs/tahoe-lafs/blob/master/docs/CODE_OF_CONDUCT.md).

[More information here](https://github.com/tahoe-lafs/community/blob/main/project-notes/season-of-docs-2021/for-contributors.md)
