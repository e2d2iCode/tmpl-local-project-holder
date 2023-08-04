<!-- markdownlint-disable MD024 -->
# Changelog
<!--
-------------------------------------------------------------------------------------------------------------------------------------
___  [   ]  INSTALLATION  CHECKLIST     __________________________________________
----------------------------------------------------------------------------------------------------------------------------

[   ]  COPY / MOVE the template to `/CHANGELOG.md` (at repo's root-level)

[   ]  REPLACE https://github.com/e2d2ipi/tmpl-local-project-holder to the actual repository's URL.
       There are 5 instances of it:
        [   ]  3x in the TEMPLATE section
        [   ]  1x in the [0.0.0] vesion
        [   ]  1x in the [Unreleasd] vesion

[   ]  UPDATE version [0.0.0] with the project's data
        [   ]  Set the <yyy-mm-dd> to TODAY's date
        [   ]  ADD / REMOVE / MODIFY  the version's description (e.g. specify the use license)

[   ]  DONE! Move this checklist at the bottom of this file (or deleting it)

-->
<!--
-------------------------------------------------------------------------------------------------------------------------------------
___  HEADER     _______________________________________________________________
---------------------------------------------------------------------------------------------------------------------------->

All notable changes to this project will be documented in this file.

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">
<div style="font-size: 95%; text-align: justify;">

!!!Hint Conventions
    This document's format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
    and [Semantic Versionning](https://semver.org/spec/v2.0.0.htmlspec/v2.0.0.html) .

</div></div>

<!--
-------------------------------------------------------------------------------------------------------------------------------------
___  TEMPLATE     _____________________________________________________________
-----------------------------------------------------------------------------------------------------------------------------

## [Unreleased](<repo-url>/compare/...HEAD)
## [<vers>](<repo-url>/releases/tag/<the-tag>) &nbsp;-&nbsp; <yyy-mm-dd>
## [<vers>](<repo-url>/compare/<to-that>...<this>) &nbsp;-&nbsp; <yyy-mm-dd>

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

    [   ]  ADD today's date in the format YYYY-MM-DD

    [   ]  REPLACE [Unrelease] by the last release's next version

The step below finalizes the release's changelog. It should be the last commit on the `release`
branch before the final merge happens.

    [   ]  MODIFY the comparison settings from `...HEAD` to `<last-vers-tag>...<new-vers-zag>`

-->

## [Unreleased](<repo-url>/compare/...HEAD)

### Fixed

- ...

### Added

- ...

### Security

- ...

### Changed

- ...

### Removed

- ...

### Deprecated

- ...

-------------------------------------------------------------------------------------------------------------------------------------

## [Seed](<repo-url>/releases/tag/v0.0.0) &nbsp;-&nbsp; <yyy-mm-dd>

### Added

- The standard seeding files:
  - A basic [.gitignore config](/.gitignore).
  - A copy of an [Open Source LICENCE](/LICENSE).
  - A brief description of the project in a [README file](/README.md).

<!-- markdownlint-disable MD024 -->
