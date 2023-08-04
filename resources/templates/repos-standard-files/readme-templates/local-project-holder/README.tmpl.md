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
- [Folders Hierarchy](#folders-hierarchy)
- [Project's Roadmap](#projects-roadmap)
- [Project's Contributors](#projects-contributors)

<!-- /code_chunk_output -->

</detail>

## Description

@@POJECT_DESCRIPTION@@

## Folders Hierarchy

Each folder of the template that was used to instantiate this project contains a `.gitkeep` file
containing a description of its purpose. In addition, the folder `resources/manuals` contain several
documents describing in more detail certain aspects of the template and its usage, and suggesting
some best practices and conventions.

As a quick overview, and a reference of the template's structure once the unnecessary files and
folders have been removed, the following tree shows the structure of the template:

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">

```tree


   .                               PROJECT'S ROOT FOLDER
   |                               ``````````````````````
   ├── .bak                        # Project's Backup and Archives
   |   ├── .history                  # Continous backups
   |   └── archives                  # The project's main archives
   |
   ├── deploy                       # Deployment Environement(s)
   |   └── ...                        # Sufolders and files ...
   |
   ├── @rel                         # Exposes the (sub)project(s) latest release(s)
   |   └── ...                        # Sufolders and files ...
   |
   ├── resources                    # Project's Resources
   |   └── ...                        # Sufolders and files ...
   |
   ├── workspace(s)                 # Project's Workspace(s)
   |   └── ...                        # Sufolders and files ...
   |
   └── .gitkeep                     # Describres the template's core structure

```

</div>

## Project's Roadmap

Planned features and improvements as well as known issues and other topics of interest concerning
this template's development status and roadmap are embedded in its `.gitkeep` files in the form of
[Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
comments. They can be viewed in the *Todo Tree* panel of
[Visual Studio Code](https://code.visualstudio.com/) by installing the *Todo Tree* extension and
opening the template's root folder in *Visual Studio Code* using the file named
[vscode-index.code-workspace](vscode-index.code-workspace) and located at the root of this
template's folder.

Note that, due to the custom tags that were used and that are defined in that latter file, opening this
template exactly as just described is mandatory to get an exhaustive view of all the *Todo Tree* tags
that this project contains.

For the record, let's list here the most important entries anyway:

- [ ]  @@ROADMAP_ENTRY_1@@, if applies
- [ ]  @@ROADMAP_ENTRY_2@@, if applies
- [ ]  etc ...

## Project's Contributors

- **@@AUTHOR_NAME@@** - *Initial work* - [@@USER@@](https://github.com/@@USER@@)

<!-- EDIT Make sure that all @@TO-BE-REPLACED@@  were either replaced or deleted with their associated contents. Delete this comment only once this is done! [template]  -->
