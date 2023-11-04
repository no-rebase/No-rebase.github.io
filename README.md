Author Rebase Consent

This repo is the website for the "No-rebase" movement.

When we contribute patches to other people's projects, often times they rebase / rewrite the Pull Requests we offer.

Some problems with rebasing contributions are:
- By rewriting the submitted commit to change its parent commit, our contribution is made to look like it modified a different code base than the revision we actually modified.
- A patch which is complete and correct when applied to one tree, may be incomplete or incorrect when applied elsewhere. Since the rewritten patch is made to bear the contributor's name as author, the patch looks like the author contributed a bug rather than a worthwhile change.
- A rewritten commit is counterfit. As an author, I also find it offensive that another maintainer would chose a counterfit version of my work, when I made the original available without restrictions.
- It breaks the network of forks (https://github.com/:owner/:repo/network) because features that the community made are not shown as integrated into the upstream.
- If you make significant contributions to someone else's project, it makes it very hard to track which of your features were accepted upstream, making it difficult to keep the upstream updated with your improvements. It makes collaboration unmanageable, putting undue demands on willing contributors.

I believe most maintainers who rebase contributions are not aware how much the rebase practice harms the goodwill of the community.

I have personally given up contributing to at least one signifiant OSS project because the upsteam's rebase policy is hell for me to track.

In order to make maintainers of projects where I'd like to contribute aware of the issues above, this website is a light-hearted way to point them out. It can be linked with an unambiguous trailer line in my commits (feel free to cut and paste into your commits):

```
Author-Rebase-Consent: https://No-rebase.github.io
```

or,

```
Author-Rebase-Consent: https://No-rebase.github.io?drok
```

Civilized [discussion](https://github.com/no-rebase/No-rebase.github.io/discussions) is welcome, as well as [improvements](https://github.com/no-rebase/No-rebase.github.io/pulls)