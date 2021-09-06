## August 2021

This report was produced by the Community Manager and covers discussions and 
decisions from August 1, 2021 to August 31, 2021.

+ Whenever possible, titles/roles are mentioned alongside names
+ Governance was simple but transparent, and all decisions can be found on this 
public repo
+ Although 1-on-1 discussions occurred, the results of these discussions were 
presented for discussion and ultimately published
+ Any community member can comment on these decisions by means of a pull request

### Summary

With the Python 3 port completed, August focused on getting our Security Audit for 
the Great Black Swamp (GBS protocol). We published an RfP, vetted proposals, 
scheduled a vendor and the Core Team got to work. Currently, they are preparing the
codebase, design document and themselves to discuss GBS/Tahoe-LAFS to ensure it 
is as secure as possible, as its founders intended. The codebase, the GBS protocol 
spec and the cryptography will all be looked at to this end. There is a flurry of
activity all around; it's exciting!

Additionally, our mailing list is now actually working, and sending and receiving
mails! We also had a volunteer contributor work on our Nix Packages (now merged)

The icing on the cake this month could be that an RC that supports both Python 2 + 3
was cut, by a core team member and a new(ish) contributor. This brings us closer to
our goal of automating our release process. This Release is expected for early 
September, after which there will no longer be Python 2 supporting releases.

Governance and Community:
+ Summit planning is planning to have a summit
+ Hugo (https://gohugo.io/) will be the tooling for our website, since Anxhelo 
(Internews/BASICS) is doing the web development he gets to choose
+ New project policy for GitHub: No force-pushing or squashing, except when 
working alone and never when reworking a PR

Communications:
+ Mailing list is now up and running! https://lists.tahoe-lafs.org/mailman/listinfo,  
thanks to Sajith (core dev)
+ Presentation of wireframes; mockups by Anxhelo; discussion with core team about website

Development:
+ Published an RfP for a Security Audit; received 3 proposals
+ Cure53 chosen to do the audit; Audit will take place September - October
+ Jean-Paul and Itamar (core devs) begin implementation of GBS and design document: 
https://github.com/tahoe-lafs/tahoe-lafs/blob/3755.gbs-design-doc/docs/proposed/gbs.md
+ Nix packages got merged into https://github.com/NixOS/nixpkgs/pull/132197, 
thanks Aaron Janse! (volunteer contributor)
+ Python 2 + 3 Release candidate 1.16.0 out now https://tahoe-lafs.discourse.group/t/1-16-0-release-candidate-a-message-from-meejah/34/2; 
Thanks meejah (core dev) and Fenn (testing and release manager)!
+ Fenn ran Black on an old branch resulted in too many merge conflicts to be useful; 
work continues:
https://pastebin.pl/view/b955b4a5
   
Finance:
+ Invoices to Aspiration now require at least one approver; processes being 
formalized with more transparency/oversight
+ Memorandum of Understanding submitted to NLnet for GBS development; covers 
the next 12 months

Upcoming items in September:
+ Landing page will be completed
+ Release of 1.16.0
+ Security Audit

Ongoing Q3:
+ Deploy User Test Grid
+ GBS Implementation begins after security audit
+ Formalizing organizational processes
+ A virtual summit

Q4 Goals:
+ Have a mission statement or formalized list of objectives
+ Retrospective and planning for 2022 begins
