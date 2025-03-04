# README - @@PROJECT_NAME@@

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

This folder is not meant to be a versioned repository, but rather a local folder structure that will
itself contain one or more repositories. Note that it is not to be confused with a mono-repo either
since its root folders are not meant to be versioned. The contents of the `workspace(s)` folder,
however, *may* be versioned by itself or contain multiple subfolders, each of which being a
mono-repo, a multi-repo or a simple folder.
</div></div></div>
<div style="
   width: 100%;
   text-align: center;
    margin-bottom: 5ex;"
>

</div>

<!-- @import "[TOC]" {cmd="toc" depthFrom=2 depthTo=6 orderedList=false} -->
<details open style="margin: 14pt 0pt 24pt 10pt">
<summary style="margin-left: -8pt; font-weight: bold; font-size: larger; font-variant: small-caps">
<span style="margin-left: 3pt">Table of contents<span></summary>

<!-- code_chunk_output -->

- [Description](#description)
- [Contents](#contents)
- [Roadmap](#roadmap)
- [Contributors](#contributors)

<!-- /code_chunk_output -->

</detail>

## Description

@@POJECT_DESCRIPTION@@

## Contents

Each folder of the template that was used to instantiate this project contains a `.gitkeep` file
containing a description of its purpose. In addition, the folder `resources/manuals` contain several
documents describing in more detail certain aspects of the template and its usage, and suggesting
some best practices and conventions.

As a quick overview, and a reference of the template's structure once the unnecessary files and
folders have been removed, the following tree shows the structure of the template:

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">

``` tree
   .                             PROJECT'S CORE STRUCTURE
   |                             ´´´´´´´´´´´´´´´´´´´´´´´´
   ├─ .bak                        # Backups and archives
   ├─ admin                       # Admin. tools and docs
   ├─ deploy                      # Deployment environments
   ├─ resources                   # User's personal resources
   └─ workspaces                  # Working env: project's sources
      ├─ @@PROJECT_01_NAME@@        # @@PROJECT_01_DESCRIPTION@@
      ├─ @@PROJECT_02_NAME@@        # @@PROJECT_02_DESCRIPTION@@
      └─ ...
```

</div>

## Roadmap

Planned features and improvements as well as known issues and other topics of interest concerning
this template's development status are embedded in its `.gitkeep` files in the form of
[Todo Tree comments](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree). The most important ones are also listed here for convenience:

- [ ]  @@ROADMAP_ENTRY_1@@, if applies
- [ ]  @@ROADMAP_ENTRY_2@@, if applies
- [ ]  etc ...

## Contributors

- **@@AUTHOR_NAME@@** - *Initial work* - [@@USER@@](https://github.com/@@USER@@)

<!-- EDIT Make sure that all @@TO-BE-REPLACED@@  were either replaced or deleted with their associated contents. Delete this comment only once this is done! [template]  -->
