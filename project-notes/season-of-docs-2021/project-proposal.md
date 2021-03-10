# Tahoe-LAFS Google Season of Docs Project Proposal
https://developers.google.com/season-of-docs/docs/org-proposal-template

Creating the organization proposal
bookmark_border
Current phase:
Organization applications open. See timeline.

Use this guide as a template to create your organization's project proposal.

PROPOSAL TITLE - organization name
Your proposal title should be short and specific. “Update ORGNAME Contributor Guide” is a good proposal title. “Documentation Improvements” is too vague; “Update Sections 5,7,23,99 of Contributor Guide, Create FAQ, and Create Style Guide” is too long.

About your organization
In this section, tell us about your organization or project in a few short paragraphs. What problem does your project solve? Who are your users and contributors? How long has your organization or project been in existence? Give some context to help us understand why funding your proposal would create a positive impact in open source and the world.

GloriousPickle (current version 1.2.3, first release in 2009) is an MIT-licensed library for easily calculating the perfect ratio of salt, sugar, vinegar, and spices for every possible pickleable vegetable, in quantities ranging from a single solitary baby cucumber to container-shiploads of radishes. Our contributors are pickle enthusiasts from all around the world, and our users are home chefs, restaurant chefs, and people working in logistics for large food-processing companies and organizations. Our largest user is an organization that helps food banks turn short-shelf-life vegetables into stable jars of pickles, helping feed hungry people in many communities and reducing food waste. In addition, our users send us optional metrics about their use of GloriousPickle, which we use to produce the PickleSet, a large dataset for creating new pickle recipes through machine learning.

About your project
Your project’s problem
Tell us about the problem your project will help solve. Why is it important to your organization or project to solve this problem?

Users want to be able to add information about new spices and other ingredients (especially ingredients from non-European cuisines) to the GloriousPickle tool. Unfortunately, the process for adding this information is not documented well, which means potential contributors have to open an issue in the project to get help (or they just give up altogether). The process also assumes that contributors are already familiar with our pull request process and with GitHub, although many of our users are not professional developers.

The more ingredient information we have, the more useful GloriousPickle is to all of our users!

Your project’s scope
Tell us about what documentation your organization will create, update, or improve. If some work is deliberately not being done, include that information as well. Include a time estimate, and whether you have already identified organization volunteers and a technical writer to work with your project.

The GloriousPickle project (code-named PicklePlus) will:

Audit the existing documentation and create a friction log of the current documentation for the three top use cases (adding a new ingredient, adding a variant ingredient, and updating or correcting information about an ingredient).
Using the friction log as a guide for understanding the gaps in the documentation, create updated documentation for the top use cases.
Create a quick “cheat sheet” to help contributors new to pull requests and GitHub to help them be able to use our process.
Incorporate feedback from documentation testers (volunteers in the project) and the wider GloriousPickle community.
Work with the release team to update the documentation on the GloriousPickle site, and to create a process for keeping the documentation in sync with the update tool going forward.
Work that is out-of-scope for this project:

This project will not create a process for cross-linking between different spellings or names for the same ingredient.
This project will not create any GitHub tutorials; instead, the cheat sheet will link to existing material that is relevant and helpful.
We have two strong technical writing candidates for this project, and we estimate that this work will take three months to complete. The GloriousPickle PickleDocs SIG and @GloriousPicklePat (the core maintainer of the ingredient-adding API) have committed to supporting the project.

Measuring your project’s success
How will you know that your new documentation has helped solve your problem? What metrics will you use, and how will you track them?

GloriousPickle receives an average of ten pull requests a quarter to add or update new ingredients (tagged ‘ingredient’). The majority of these pull requests (>60%) are from previous contributors. We believe that this improved documentation will result in more pull requests and more pull requests from new contributors. Since most of our active contributors began by adding ingredients, we also think improving this documentation will result in more active contributors overall.

We will track two metrics (number of ingredient-related pull requests and number of pull requests from new contributors) monthly after the documentation is published. We will also track the number of contributors who have made more than three contributions overall, starting quarterly after the documentation is published.

We would consider the project successful if, after publication of the new documentation:

The number of ingredient-related pull requests increases by 20%
The number of pull requests from new contributors increases by 15%
The number of contributors who have made >3 contributions increases by 10% (beginning the quarter after the documentation is published)
Project budget
General guidelines
You can include your budget in your proposal, or as a separate link. If your budget is fewer than ten items, we recommend including it in your proposal.
All budgets should be in US dollars. We expect grants to range from US$5000 to US$15000; if your project is outside of that range, please provide additional information to justify your budget.
We expect the bulk of your budget (60-70% minimum) to be allocated to the technical writer working on your project. We recommend budgeting on a per-project basis wherever possible.
We expect open source projects to use open source tools whenever possible; if your project absolutely requires funds for proprietary software licenses or support, please include a justification for the amount.
Other possible expenses include:
Design work to create branding, logos, templates, or other design assets for your documentation site
Minimal amounts (<US$200) for project swag (t-shirts or stickers for your participants). If you use the Season of Docs logo, it must be accompanied by your project or organization logo or name. Your swag may not use the name Google.
Minimal stipends for volunteers who take on considerable mentorship or guidance roles in the project (we recommend no more than $500 per volunteer, please)
Downstream donations to other open source projects should be no more than 10% of your budget total.
Include other budget items as needed, along with justification for the amount sought. Expense justifications should highlight how the expenditure will contribute to the success of the project as a whole.
Sample budget
Budget item	Amount	Running Total	Notes/justifications
Technical writer audit, update, test, and publish new documentation of ingredient-adding process for GloriousPickle	5000.00	5000.00	
Volunteer stipends	500	6500.00	3 volunteer stipends x 500 each
Project t-shirts (10 t-shirts)	150.00	6650.00	
Giant inflatable unicorn (15 foot version)	99.99	6749.99	We will give the inflatable unicorn to the team that answers the technical writer’s questions the fastest during the project development period
TOTAL		6749.99	
Additional information
Include here any additional information that is relevant to your proposal.

Previous experience with technical writers or documentation: If you or any of your mentors have worked with technical writers before, or have developed documentation, mention this in your application. Describe the documentation that you produced and the ways in which you worked with the technical writer. For example, describe any review processes that you used, or how the technical writer's skills were useful to your project. Explain how this previous experience may help you to work with a technical writer in Season of Docs.

Previous participation in Season of Docs, Google Summer of Code or others: If you or any of your mentors have taken part in Google Summer of Code or a similar program, mention this in your application. Describe your achievements in that program. Explain how this experience may influence the way you work in Season of Docs.