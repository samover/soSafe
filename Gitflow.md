Git Workflow with Waffle Walkthrough
====================================

1. Clone the repo
  * create development branch: `git checkout -b development`
  * pull remote development: `git pull origin development`

2. Create a ticket
  * visit [repo on waffle](https://waffle.io/samover/soSafe)
  * add issue and note the issue number

3. Move ticket to production:
  * create local branch **from development** starting with the issue number: `git checkout -b 4-new-feature`
  * make a change and push to remote: `git push origin 4-new-feature`
  * your ticket should now be moved automatically to production. if not, give a shout.

4. Merge feature with development branch:
  * when the feature is finished (please have awesome, readable commit messages)
  * visit [repo page](https://github.com/samover/soSafe) and create pull request
  * PR message should include: `close #4`, the number being the issue number
  * merge PR
