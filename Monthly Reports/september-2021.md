## September 2021

This report was produced by the Community Manager and covers discussions and 
decisions from September 1, 2021 to September 30, 2021.

+ Whenever possible, titles/roles are mentioned alongside names
+ Governance was simple but transparent, and all decisions can be found on this 
public repo
+ Although 1-on-1 discussions occurred, the results of these discussions were 
presented for discussion and ultimately published
+ Because we are currently in the process of being security audited, some discussions
will remain private until it is prudent to publish them
+ Any community member can comment on these decisions by means of a pull request

### Summary

In September, we kicked off on our long-awaited security review with Berlin-based
Cure53. It has been a whirlwind of discussion and a revisit of the project's original
intentions and design choices. Core developers Jean-Paul and meejah had a chance to 
flex their hard-earned Tahoe-LAFS knowledge, while gaining an outsider's insights 
on a familiar codebase. We eagerly await the delivery of Cure53's report in October
so that we can ultimately offer Tahoe-LAFS to the public as a FOSS that provides
nation-state grade encrpytion and storage properties. Or, "close enough."

New contributers and community members entered the IRC, the Discourse and the Mailing
List, highlighting how the completion of the Python 3 port has attracted more
activity to the project. 

Preliminary steps were taken to develop a Trac --> GitLab migration tool and the
deployment of a user test grid (Jean-Paul)

The Tahoe-LAFS project still has a lot to do for the remainder of the year,  but is
headed for a strong Q4 finish.

Governance and Community:
+ One meeting per week rule - either the regular Governance meeting OR special-purpose 
meetings
+ Plans for a private repo to work on audit fixes began

Communications:
+ IRC channel crossed 40 users for the first time since we migrated to Libera.chat
+ Credentials distributed to mailing list admins (Thanks, Sajith!/core dev)

Development:
+ OpenMetrics format statistics endpoint added for scraping by Prometheus (Thanks
hacklschorsch!) https://github.com/tahoe-lafs/tahoe-lafs/pull/1125
+ Fenn (Testing and Release Manager) did the Release for 1.16.0; along with meejah
+ LOTS of work on GBS Spec by Itamar (core dev) and Jean-Paul
+ Jean-Paul continues removing mocks
+ Fenn continues working on testing suite
   
Finance:
+ Discussions on ways to introduce more financial oversight into the project
+ Continuing to use Approver <--> Approvee process on invoices in the meantime

Upcoming items in October:
+ Landing page will be completed
+ Release of 1.16.0
+ Security Audit Report delivered

Ongoing Q4:
+ Deploy User Test Grid
+ GBS Implementation begins after security audit
+ Formalizing organizational processes
+ A virtual summit

Q4 Goals:
+ Begin fixes from Security Review
+ Have a mission statement or formalized list of objectives
+ Retrospective and planning for 2022 begins
