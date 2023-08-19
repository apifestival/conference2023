# Contributing to Mainflux

The following is a set of guidelines to contribute to apifestival and its repositories, which are hosted on the [apifestival Organization](https://github.com/apifestival) on GitHub.

This project adheres to the [Contributor Covenant 1.2](http://contributor-covenant.org/version/1/2/0). By participating, you are expected to uphold this code. Please report unacceptable behavior to `info[at]pyconke[dot]org`.

## Reporting issues

Reporting issues are a great way to contribute to the project. We are perpetually grateful about a well-written, thorough an issue template.

## Pull requests

Good pull requests (e.g. patches, improvements, new features) are a fantastic help. They should remain focused in scope and avoid unrelated commits.

To contribute to the project, [fork](https://help.github.com/articles/fork-a-repo/) it, clone your fork repository, and configure the remotes:

```bash
git clone https://github.com/<your-username>/conference2023.git
cd conference2023
git remote add upstream https://github.com/apifestival/conference2023.git
```

If your cloned repository is behind the upstream commits, then get the latest changes from upstream:

```bash
git checkout main
git pull --rebase upstream main
```

Create a new topic branch from `main` using the naming convention `SESSION-[TALK-TITLE]` to help us keep track of your contribution scope:

```bash
git checkout -b SESSION-[TALK-TITLE]
```

Commit your changes in logical chunks. When you are ready to commit, make sure to write a Good Commit Message™. Consult the [Erlang's contributing guide](https://github.com/erlang/otp/wiki/Writing-good-commit-messages) if you're unsure of what constitutes a Good Commit Message™. Use [interactive rebase](https://help.github.com/articles/about-git-rebase) to group your commits into logical units of work before making it public.

Note that every commit you make must be signed. By signing off your work you indicate that you are accepting the [Developer Certificate of Origin](https://developercertificate.org/).

If you set your `user.name` and `user.email` git configs, you can sign your commit automatically with `git commit -s`.

Locally merge (or rebase) the upstream development branch into your topic branch:

```bash
git pull --rebase upstream main
```

Push your topic branch up to your fork:

```bash
git push origin SESSION-[TALK-TITLE]
```

[Open a Pull Request](https://help.github.com/articles/using-pull-requests/) with a clear title and detailed description.
