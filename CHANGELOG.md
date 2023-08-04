<!-- markdownlint-disable MD024 MD051 -->
# Changelog - *Local Project Template*
<!--
-------------------------------------------------------------------------------------------------------------------------------------
___  HEADER     _______________________________________________________________
---------------------------------------------------------------------------------------------------------------------------->

<div style="width: 40em; font-size: normal; margin: 2ex auto 5ex 0">
<div style="font-size: 95%; text-align: justify;">

!!!Hint ""
    This document's format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
    and [Semantic Versionning](https://semver.org/spec/v2.0.0.htmlspec/v2.0.0.html).

</div></div>

<!-- @import "[TOC]" {cmd="toc" depthFrom=2 depthTo=2 orderedList=false} -->
<details open style="margin: 14pt 0pt 32pt 10pt">
<summary style="margin-left: -8pt; font-weight: bold; font-size: larger; font-variant: small-caps">
<span style="margin-left: 3pt">List of versions<span></summary>

<!-- code_chunk_output -->

- [1.0.0 &nbsp;-&nbsp; 2023-08-04](#100httpsgithubcome2d2ipitmpl-local-project-holdercomparev000v100-nbsp-nbsp-2023-08-04)
- [Seed &nbsp;-&nbsp; 2023-07-22](#seedhttpsgithubcome2d2ipitmpl-local-project-holderreleasestagv000-nbsp-nbsp-2023-07-22)

<!-- /code_chunk_output -->

</details>

<!--
-------------------------------------------------------------------------------------------------------------------------------------
___  TEMPLATE     _____________________________________________________________
-----------------------------------------------------------------------------------------------------------------------------

## [Unreleased](https://github.com/e2d2ipi/tmpl-local-project-holder/compare/...HEAD)
## [<vers>](https://github.com/e2d2ipi/tmpl-local-project-holder/releases/tag/<the-tag>) &nbsp;-&nbsp; <yyy-mm-dd>
## [<vers>](https://github.com/e2d2ipi/tmpl-local-project-holder/compare/<to-that>...<this>) &nbsp;-&nbsp; <yyy-mm-dd>

### Added

- ...

### Changed

- ...

### Deprecated

- ...

### Removed

- ...

### Fixed

- ...

### Security

- ...

-->
<!--
-------------------------------------------------------------------------------------------------------------------------------------
___ CHANGELOG   ____________________________________________________________
-----------------------------------------------------------------------------------------------------------------------------
NEW  VERSION  CHECKLIST  (!!! Release Brsnch !!!)
´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´
The first 3 steps below should be taken eright on the `develop` branch, right before  the `telease`
branch is created. If done on the `release` branch, then the changes should be merged back to
the `develop` branch asap (before  its changelog is updated with new entries, otherwise tconflicts
will occur when the `release` branch is merged back to the `develop` branch).

    [   ]  REPLACE [Unrelease] by the last release's next version

    [   ]  MODIFY the comparison settings from `...HEAD` to `<last-vers-tag>...<new-vers-tag>`

    [   ]  REPLACE <yyy-mm-dd> by today's date
          (this update should be the /release / vX.Y.Z' branch's last commit)

    [   ]  REPLACE [Unrelease] by the last release's next version

The step below finalizes the release's changelog. It should be the last commit on the `release`
branch before the final merge happens.

    [   ]  MODIFY the comparison settings from `...HEAD` to `<last-vers-tag>...<new-vers-zag>`

-->

## [1.0.0](https://github.com/e2d2ipi/tmpl-local-project-holder/compare/v0.0.0...v1.0.0) &nbsp;-&nbsp; 2023-08-04

### Added

- VSCode [workspace settings](/vscode-index.code-workspace).
- A folder to hold the project's [ backups and archives](/.bak/.gitkeep).
- A folder to host the project's [deployment environments](/deploy/.gitkeep).
- A folder to host the project's [admininistrative environment ](/admin/.gitkeep):
  - Guidelines on how to handle the project's [archives](/admin/guidelines/handling-archives/handling-archives.md).
  - Guidelines on the recommended [Git branching model](/admin/guidelines/git-branching/git-branching-model.md).
- A folder to hold the user's personal [development resources](/resources/.gitkeep):
  - Various templates: [Assets' folder and standard repo files](/resources/templates/.gitkeep).
  - User's shared assets: [full octicons set and all e2d2lipi logos](/resources/assets/user-interface/.gitkeep).
  - Mini-guide on exploiting VSCode's features in [markdown format](/resources/manuals/vscode-custom-features/vscode-custom-features.md).
- Workspace(s) environment to hold the project and subprojects [directories](/workspaces/.gitkeep).
- Additional dev-related files: [CHANGELOG.md](/CHANGELOG.md), [vscode-index.code-workspace](/vscode-index.code-workspace).

### Changed

- The seeding files were updated:
  - The [.gitignore](/.gitignore) file was rfined.
  - The [LICENCE](/LICENSE) was updated with the needed informatio.
  - The [README](/README.md) file was updated to a detailed description of the project.

-------------------------------------------------------------------------------------------------------------------------------------

## [Seed](https://github.com/e2d2ipi/tmpl-local-project-holder/releases/tag/v0.0.0) &nbsp;-&nbsp; 2023-07-22

### Added

- The standard seeding files:
  - A basic [.gitignore config](/.gitignore).
  - A copy of the [MIT LICENCE](/LICENSE).
  - A brief description of the project in a [README file](/README.md).

<!-- markdownlint-disable MD024 MD051 -->
<!--
-------------------------------------------------------------------------------------------------------------------------------------
___  [ x ]  INSTALLATION  CHECKLIST     __________________________________________
----------------------------------------------------------------------------------------------------------------------------

[ x ]  COPY / MOVE the template to `/CHANGELOG.md` (at repo's root-level)

[ x ]  REPLACE https://github.com/e2d2ipi/tmpl-local-project-holder to the actual repository's URL.
       There are 5 instances of it:
        [ x ]  3x in the TEMPLATE section
        [ x ]  1x in the [0.0.0] vesion
        [ x ]  1x in the [Unreleasd] vesion

[ x ]  UPDATE version [0.0.0] with the project's data
        [ x ]  Set the <yyy-mm-dd> to TODAY's date
        [ x ]  ADD / REMOVE / MODIFY  the version's description (e.g. specify the use license)

[ x ]  DONE! Move this checklist at the bottom of this file (or deleting it)

-->
