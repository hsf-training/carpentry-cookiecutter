# Instructions to start an HSF Training module in carpentry style

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/hsf-training/carpentry-cookiecutter/main.svg)](https://results.pre-commit.ci/latest/github/hsf-training/carpentry-cookiecutter/main)
[![Check Markdown links](https://github.com/hsf-training/carpentry-cookiecutter/actions/workflows/check-links.yaml/badge.svg)](https://github.com/hsf-training/carpentry-cookiecutter/actions/workflows/check-links.yaml)

This repository holds the template for starting a new [HSF Training module](https://hepsoftwarefoundation.org/training/curriculum.html) in [carpentries](https://software-carpentry.org/) style (see, for example, our [training on CI/CD](https://hsf-training.github.io/hsf-training-cicd/)).

## How to start a new module

> **Note**
> We happily do this for you! It's always best to talk to us first, if you plan to contribute to our [curriculum](https://hepsoftwarefoundation.org/training/curriculum.html). 

To start a new module, install [Cookiecutter](https://github.com/cookiecutter/cookiecutter) and run

```bash
cookiecutter https://github.com/hsf-training/carpentry-cookiecutter/
```

### Preview website

After answering the questions, you have a directory with a working setup and a `README.md`.
Follow the instructions in `README.md` to take a first look at the corresponding webpage.

### Fill in content 

* Follow the "Jekyll Setup for Lesson Development" instructions of the [carpentry tutorial setup instructions](https://carpentries.github.io/lesson-example/setup.html).
* If you are interested to study the pedagogical concepts behind the carpentries approach, head [to their handbook](https://carpentries.github.io/curriculum-development/)
* [The technological section of their handbook](https://carpentries.github.io/curriculum-development/technological-introductions.html) is a good starting point to create content right away
* The [tutorial on creating content](https://carpentries.github.io/lesson-example/02-tooling/index.html) also gives a nice introduction (but perhaps a bit more from a technological standpoint)

## FAQ

> This is so much to take in, I feel entirely overwhelmed and discouraged.

This is entirely normal, if you're new to the technology stack that we're using (Markdown, Jekyll, git, github, ...). But don't despair, we're here to help you! Simply [write to us](mailto:hsf-training-wg@googlegroups.com) or [join our weekly meeting](https://indico.cern.ch/category/10294/), or join the [Mattermost educators space](https://mattermost.web.cern.ch/signup_user_complete/?id=t9zkdocffbbozqcdy193myre8y) and we'll help you get unstuck. We can also arrange a short meeting where we share screens and figure out problems.
