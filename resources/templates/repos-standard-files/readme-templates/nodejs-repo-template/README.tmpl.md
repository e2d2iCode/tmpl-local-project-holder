# README - GitHub Templates

---

<div style="
    font-size: normal;
    margin: 0 auto 5ex auto;
    width: 40em;"
>
<div style="font-size: 95%; text-align: justify;">
<div style="
  font-size:135%;
  text-align: center;
  font-weight: bold;
  margin: 0 0 .75ex 0;
  font-variant: small-caps;"
>Abstract</div>
<div style="text-align: justify; font-style: italic">

@@PROJECT_ABSTRACT@@

</div>
<div style="
   width: 100%;
   text-align: center;
   margin-top: 5ex;
    margin-bottom: 5ex;"
>

[![GitHub issues](https://img.shields.io/github/issues/@@USER@@/@@REPO@@.svg)](https://github.com/@@USER@@/@@REPO@@/issues)
[![GitHub forks](https://img.shields.io/github/forks/@@USER@@/@@REPO@@.svg)](https://github.com/@@USER@@/@@REPO@@/network)
[![GitHub stars](https://img.shields.io/github/stars/@@USER@@/@@REPO@@.svg)](https://github.com/@@USER@@/@@REPO@@/stargazers)
[![GitHub license](https://img.shields.io/github/license/@@USER@@/@@REPO@@.svg)](https://github.com/@@USER@@/@@REPO@@/blob/main/LICENSE.md)

</div>
</div></div>

<!-- @import "[TOC]" {cmd="toc" depthFrom=2 depthTo=6 orderedList=false} -->
<details open style="margin: 14pt 0pt 24pt 10pt">
<summary style="margin-left: -8pt; font-weight: bold; font-size: larger; font-variant: small-caps">
<span style="margin-left: 3pt">Table of contents<span></summary>

<!-- code_chunk_output -->

- [Description](#description)
- [Why use a template ... even for small projects](#why-use-a-template--even-for-small-projects)
- [How do these templates help you with this](#how-do-these-templates-help-you-with-this)
  - [Quality and Efficiency](#quality-and-efficiency)
  - [Documentation](#documentation)
  - [Consistency](#consistency)
  - [Security](#security)
  - [Ethics](#ethics)
  - [FOSS](#foss)
- [Installation](#installation)
  - [Pre-requisites](#pre-requisites)
  - [1. Get your own copy of this repository](#1-get-your-own-copy-of-this-repository)
  - [1. Replace `<TAGS>` across the template](#1-replace-tags-across-the-template)
    - [1.1. Replace tags `<USER_NAME>` and `<REPO_NAME>` by your (GituHub) _UserName_ and _RepositoryName_ in](#11-replace-tags-user_name-and-repo_name-by-your-gituhub-_username_-and-_repositoryname_-in)
    - [1.2 In README.md, further provide](#12-in-readmemdreadmemd-further-provide)
    - [1.3. In package.json, specify](#13-in-packagejsonpackagejson-specify)
    - [1.4. Finally, in CODE_OF_CONDUCT.md,  provide](#14-finally-in-code_of_conductmdcode_of_conductmd--provide)
  - [2. Activate Github's features](#2-activate-githubs-features)
  - [3. License your project](#3-license-your-project)
  - [4. Install Conventional Commits Support & all other dependencies](#4-install-conventional-commits-support--all-other-dependencies)
- [Usage](#usage)
- [Support](#support)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Versioning](#versioning)
- [Authors and acknowledgment](#authors-and-acknowledgment)
- [License](#license)

<!-- /code_chunk_output -->

</detail>

## Description

@@POJECT_DESCRIPTION@@

## Why use a template ... even for small projects

Using a template increases productivity, enforces good practices and  results in more consistent projects which can only be beneficial in the long run no matter the project(s) size(s):

- Increase [security](#security)
- Follow recognized [ethical principles](#ethics)
- Promote [Free and Open-source software](#foss)
- Write more [consistent](#consistency) code and foster collaboration
- Write better [documentation](#documentation) for you and the community
- Increase efficiency and productivity using [Automated Workflows](https://docs.github.com/en/actions/using-workflows/about-workflows)

## How do these templates help you with this

Benefits are way too many to claim to list them all. Let's g through the key advantages that can be granted to a specific feature exploited in this template.

### Quality and Efficiency

- Code analysis using [GitHub Actions](https://docs.github.com/en/actions)
- Consistent formatting via [Prettier](https://prettier.io/) and [Markdownlint](https://github.com/DavidAnson/markdownlint)
- Good practices Consistent formatting via [Prettier](https://prettier.io/) and [Markdownlint](https://github.com/DavidAnson/markdownlint)
- Efficiency and consistency relying on [Automated Workflows](https://docs.github.com/en/actions/using-workflows/about-workflows) for repetitive tasks

### Documentation

- [package.json](package.json) according to [npm docs](https://docs.npmjs.com/cli/v7/configuring-npm/package-json)
- Accessible documentation via [gh-pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
- [README.md](README.md) according to [www.makeareadme.com](https://www.makeareadme.com/)
- [CHANGELOG.md](CHANGELOG.md) according to [keepachangelog.com](https://keepachangelog.com/)

### Consistency

- Consistent issues via [issue templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)
- Consistent labels for pull requests via [labeler](https://github.com/actions/labeler)
- Consistent versioning via [Semantic Versioning](https://semver.org/spec/v2.0.0.html)
- Compatibility using [Dependabot Version Updates](https://docs.github.com/en/code-security/dependabot/dependabot-version-updates/configuring-dependabot-version-updates)
- Consistent [fork and pull](https://gist.github.com/Chaser324/ce0505fbed06b947d962) workflow via [GitHub branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/managing-a-branch-protection-rule)
- Consistent commits according to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) via [Husky](https://github.com/typicode/husky) and [Commitizen]Consistent file organization across projects via a [documented](.gitkeep) common file hierarchy.

### Security

- [GitHub security alerts](https://github.blog/2017-11-16-introducing-security-alerts-on-github/)
- [SECURITY.md](SECURITY.md) according to [GitHub](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository)
- Integrity via [GitHub branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/managing-a-branch-protection-rule)
- Safe deployments using  [Environments](https://docs.github.com/en/actions/deployment/targeting-different-environments/using-environments-for-deployment) and [Actions](https://docs.github.com/en/actions/deployment) and

### Ethics

- Friendly first interactions via [greetings](https://github.com/actions/starter-workflows/blob/main/automation/greetings.yml)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) according to [Contributor Covenant](https://www.contributor-covenant.org/)

### FOSS

- [LICENSE.md](LICENSE.md) according to [choosealicense.com](https://choosealicense.com/)

## Installation

All templates, even non-code-oriented ones, use functionalities from [Node.js](https://nodejs.org/en). Also, the installation procedure below assumes [NPM](https://www.npmjs.com/) and [PNPM](https://pnpm.io/) are available. If it's not the case, please proceed to start by installing the missing one(s). The links and instructions you'll need are right below.

> **Note 1.** _We also recommend that you identify the template that best suits your needs before you start the installation procedure The list of the available templates is available [here](???)._
>
> **Note 2.** _Some of the installation steps below call for a commit which, in order to be fully consistent,  should comply with [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). For simplicity reason - and unless you need to follow strict rules in this regard, of course - we suggest to keep it as simple as possible and to commit all the modifications below as `chore(repo): create / init / update ...`_.
>
> **Note 3.** _We suggest that you update your repo's [CHANGELOG](./CHANGELOG.md) at the same time you go  throw the installation steps described below. Not only doing so will give it a good start, but it will also serve as status indicator while you go through the process. As an additional way to check that you did not miss anything, the file [CHANGELOG-INSTALLATION-FINAL-STATUS.md](CHANGELOG-INSTALLATION-FINAL-STATUS.md) shows what your `CHANGELOG` should look like after a successful and complete installation._

### Pre-requisites

Though not a mandatory directive, we recommend installing the following (widely used) tools globally if you can.

- [ ] Install the [latest LTS or higher version of Node](https://nodejs.org/en/download/) and [npm](https://www.npmjs.com/)

- [ ] Install [PNPM](https://pnpm.io/)  (for a local install, skip the `-g` option)

  ```bash
  npm install -g pnpm;
  ```

### 1. Get your own copy of this repository

To initialize the template, [generate](https://github.com/@@USER@@/tmpl-gas-ts-project/generate) a new repository from the current template or clone this repository in your development environment. Then, replace its (whole) content with this of the folder [src](./src/) that best suits your needs and follow the instructions below:

> **Note.** _Hopefully, this quick and dirty initializtion process will be replaced by a sceipted  `install` procedure in the future. In the meanwhile, we suggest that you somehow hide this ugly step by [Amending your lastest commit](https://www.atlassian.com/git/tutorials/rewriting-history#:~:text=The%20git%20commit%20%2D%2Damend,message%20without%20changing%20its%20snapshot) (which should be "Initial Commit")immediately._

### 1. Replace `<TAGS>` across the template

The first step in customizing this template consists in replacing `<TAGS>` with your data in various files. The replacements to make are detailed in the next sections. If this feature is available to you, know that you can safely perform the replacements by running global _Find & Replace_ on the root folder instead of going through each file individually.

#### 1.1. Replace tags `<USER_NAME>` and `<REPO_NAME>` by your (GituHub) _UserName_ and _RepositoryName_ in

- [ ] [CHANGELOG.md](./CHANGELOG.md)
- [ ] [package.json](package.json)
- [ ] [README.md](./README.md)
- [ ] [SECURITY.md](./SECURITY.md)

#### 1.2 In [README.md](./README.md), further provide

- [ ] An `<SHORT_DESCRIPTION>` of your project and
- [ ] The `<FULL_NAME>` the project's main contributor(s)

#### 1.3. In [package.json](package.json), specify

- [ ] An `<VERY_SHORT_DESCRIPTION>` of your project and
- [ ] The main author's data, which is:
- the `<AUTHOR_NAME>`,
- the `<AUTHOR_EMAIL>` and
- the `<AUTHOR_URL>`

#### 1.4. Finally, in [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md),  provide

- [ ] A `<CONTACT_METHOD>` reaching to the community leaders responsible for the code's enforcement

### 2. Activate Github's features

- [ ] Activate [GitHub security alerts](https://github.blog/2017-11-16-introducing-security-alerts-on-github/)

- [ ] Enhance code production and, also, [protecting tags](https://github.com/@@USER@@/@@REPO@@/settings/tag_protection/new)

- [ ] [Protect](https://help.github.com/en/articles/configuring-protected-branches) branches to enforce a [fork and pull](https://gist.github.com/Chaser324/ce0505fbed06b947d962) workflow
  > **Note.** _All of `main`, `master`, `dev` and `develop` brnches can be protectected in one go using the following pattern: `[dm][ea](vis)*`_

- [ ] Activate [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages): select `master` (or `main`) branch and `docs` folder as source

- [ ] Create [Environments](https://github.com/@@USER@@/@@REPO@@/settings/environments):
`production`  is intended to protect actions related to deployments
`development` applies to non-production branches (`main` or `master`, usually)

### 3. License your project

- [ ] Choose an appropriate license with [choosealicense.com](https://choosealicense.com/)

- [ ] Update [README.md](README.md) and [LICENSE.md](LICENSE.md) accordingly

> **Note.** _All templates were licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) by default, which you are free to change for any of the other [foss licences](#foss)._

### 4. Install Conventional Commits Support & all other dependencies

- [ ] Install [Commitizen](https://github.com/commitizen/cz-cli) globally and initialize your project to use it (may require using the --force option)

  ```bash
  npm install -g commitizen;
  commitizen init cz-conventional-changelog --save-dev --save-exact;
  ```

- [ ] Review [package.joon](/package.jon) and install the dependencies it declares

```bash
npm install;
npm run prepare;
```

## Usage

```bash
npm run check
npm run format
```

## Support

This project is maintained by [@<USER_NAME>](https://github.com/<USER_NAME>). Please understand that we won't be able to provide individual support via email. We also believe that help is much more valuable if it's shared publicly so that more people can benefit from it.

| Type                                  | Platforms                                                   |
| ------------------------------------- | ----------------------------------------------------------- |
| 🚨 **Bug Reports**                    | [GitHub Issue Tracker](https://github.com/@@USER@@/@@REPO@@/issues) |
| 🎁 **Feature Requests**               | [GitHub Issue Tracker](https://github.com/@@USER@@/@@REPO@@/issues) |
| 🛡 **Report a security vulnerability** | [GitHub Issue Tracker](https://github.com/@@USER@@/@@REPO@@/issues) |

## Roadmap

No changes are currently planned.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/@@USER@@/@@REPO@@/tags).

## Authors and acknowledgment

- **FULL_NAME** - _Initial work_ - [<USER_NAME>](https://github.com/<USER_NAME>)

See also the list of [contributors](https://github.com/@@USER@@/@@REPO@@/graphs/contributors) who participated in this project.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details
