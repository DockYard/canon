# The DockYard Canon
All the must-read articles and must-watch videos for the DockYard engineering team.

Think of this as a reference library for DockYard developers. This should be content that effects the code we are shipping today, not merely interesting articles (Slack is a good place for those still). A new post on Ember's blog would be a good example of an article that would fit here; an article on the hot new JS framework would not be suitable.

# How It Works
Each week will have a single PR with a single markdown file containing
 links to important articles.

Throughout the week, links can be added
to articles that people think the entire team should read. The articles
do not need to have been published that week – they could be years old. Normal PR
review rules apply – people can suggest that links be removed, etc. Everyone is encouraged to discuss the article in the PR, whether it's
closed or not.

At the end of the week, the PR will be merged, and it is expected that the
engineering team at-large will go through the articles.

# To Submit an Article
Every branch and file should be named as follows: `[year]-[month]-[Friday date of current week]`

If there is an existing branch for the given week:

1. Pull down the week's branch
1. Add the link in the appropriate section
1. Add a new commit (do not `rebase` so as to avoid the need for
   everyone to force push) explaining why the article is worth the
entire team reading
1. `git push`

If there is no existing branch:

1. Pull down `master`
1. Create a new branch with a Friday-date-based name
1. Create a new markdown file with the same name as the branch
1. Add the link in the appropriate section
1. Add a new commit (do not `rebase` so as to avoid the need for
   everyone to force push) explaining why the article is worth the
entire team reading
1. `git push` and open up a PR
