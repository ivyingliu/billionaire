# Github Collaboration

## Get start

- Fork the repo on Github.
- Clone repo on Github down to local machine.
- Add git remote that points to Gitlord's Github repo on your local repo.(git remote add gitlord https://github.com/PoAhWong/billionaire)

## Recurring Workflow

1. Make sure you are in the feature branch which contains work you want to provide to Gitlord's Github repo.
2. Add & Commit your work `git add -A` & `git commit -m 'commit message'`.
3. To download commits to local machine:

- **Gitlord**: Run `git fetch origin`
- **Everyone else**: Run `git fetch gitlord`

4. To rebase commits to feature branch:

- **Gitlord**: Run `git rebase origin/master`
- **Everyone else**: Run `git rebase gitlord/master`

5. Run `git push origin feature_branch`, where _feature_branch_ is the name of your branch.
6. Make pull request from your branch to Gitlord's master.
7. **Gitlord**: Merge pull request on Github **if** you are happy with the code contribution.
8. Gitlord to inform teammates to pull down the changes using steps 3 & 4.

### Useful Git Commands

If you get stuck with git, here are some [Useful git commands](https://gist.github.com/kasun-maldeni/2ba7b04c05d66d47c0d3b15ba27b18d3). **Please use with caution**.
