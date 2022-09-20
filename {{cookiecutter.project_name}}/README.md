[![HSF Training Center][training-center-badge]][hsf-training-center]
[![Upcoming Events][schools-badge]][schools]
[![Twitter Follow][twitter-badge]][twitter]

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/klieret/{{cookiecutter.project_name}}/main.svg)](https://results.pre-commit.ci/latest/github/klieret/{{cookiecutter.project_name}}/main)
[![pages-build-deployment](https://github.com/hsf-training/{{cookiecutter.project_name}}/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/hsf-training/{{cookiecutter.project_name}}/actions/workflows/pages/pages-build-deployment)

# FIXME: TITLE

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<!-- ALL-CONTRIBUTORS-BADGE:END -->

> **Note**
> Click [here](https://hsf-training.github.io/{{cookiecutter.project_name}}/) for the training website!

FIXME: Describe your module

## 📅 Past events and videos

* 🎥 [Fixme Sample event Dec 1 - 13, 2022](indico.cern.ch/)

Emoji key: 🎥 (full video recordings availabile), ⛏️ (hackathon)

## 🤗 Contributing

We welcome all contributions to improve the lesson! Maintainers will do their best to help you if you have any
questions, concerns, or experience any difficulties along the way.

If you make non-trivial changes (i.e., more than fixing a simple type), you are eligible to be added to the [HSF Training Community page][hsf-training-community],
as well as to the list of contributors [below](#contributors-).

We'd like to ask you to familiarize yourself with our [Contribution Guide](CONTRIBUTING.md) and have a look at
the [more detailed guidelines][lesson-example] on proper formatting, ways to render the lesson locally, and even
how to write new episodes.

Quick summary of how to get a local preview: Install [jekyll][jekyll] and then run

```
bundle install
bundle update
bundle exec jekyll serve
```

Unless we change framework versions, only the last command needs to be typed after the first time.

Before committing anything, we also ask you to install the [pre-commit][pre-commit] hooks of this repository:

```bash
pip3 install pre-commit
pre-commit install
```

Please see the current list of [issues][issues] for ideas for contributing to this
repository. For making your contribution, we use the GitHub flow, which is
nicely explained in the chapter [Contributing to a Project][progit] in Pro Git
by Scott Chacon.
Look for the tag ![good_first_issue][gfi-badge]. This indicates that the maintainers will welcome a pull request fixing this issue.

## ✍️ Citation

To cite this lesson, please consult with [CITATION](CITATION).

## 💖 Authors

<!-- If we have a primary author/maintainer, who kicked off the whole lessen etc, he should get a dedicated shoutout here -->

Thanks goes to these wonderful people ([emoji key][allcontrib-emoji-key] who contributed to
the content of the lesson:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

Even more people contributed to the framework, but they are too many to list!
Instead, all regular contributors are listed on our [HSF Training Community page][hsf-training-community]

[lesson-example]: https://carpentries.github.io/lesson-example
[pre-commit]: https://pre-commit.com/
[hsf-training-community]: https://hepsoftwarefoundation.org/training/community
[hsf-training-center]: https://hepsoftwarefoundation.org/training/curriculum.html
[training-center-badge]: https://img.shields.io/badge/HSF%20Training%20Center-browse-ff69b4
[schools]: https://hepsoftwarefoundation.org/Schools/events.html
[issues]: https://github.com/hsf-training/{{cookiecutter.project_name}}/issues
[progit]: http://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project
[jekyll]: https://jekyllrb.com/
[allcontrib-emoji-key]: https://allcontributors.org/docs/en/emoji-key
[gfi-badge]: https://img.shields.io/badge/-good%20first%20issue-gold.svg
[schools-badge]: https://img.shields.io/badge/upcoming%20events-browse-ff69b4
[twitter-badge]: https://img.shields.io/twitter/follow/hsftraining?style=social
[twitter]: https://twitter.com/hsftraining