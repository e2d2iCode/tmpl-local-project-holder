# Handling Archives

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">
<div style="font-size: 95%; text-align: justify;">

!!!Abstract
    *This document describes a set of rules and naming conventions that apply to the **`archives`** of
    a project to ensure efficiency and consistency. These conventions apply to a wide range of
    projects and require little maintenance. The proposed scheme makes it easy to identify the
    content of each archive, bundles them together based on their nature, and induces a natural order
    from newest to oldest.*

</div></div>

<details open style="margin: 14pt 0pt 24pt 10pt">
<summary style="margin-left: -8pt; font-weight: bold; font-size: larger; font-variant: small-caps">
<span style="margin-left: 3pt">Table of contents<span></summary>

- [Overview](#overview)
- [Archives naming scheme](#archives-naming-scheme)
- [Prefixes and contents](#prefixes-and-contents)
- [Suffixes (optional)](#suffixes-optional)

</details>

## Overview

Archive folders contain copies of all or part of the project at a given time, which include the full
releases' history, deprecated features, staged or abandoned development, administrative
information such as the minutes of past meetings or old communication threads, etc. These backups
usually consist of a compressed file named according to a scheme that makes its content easily
identifiable, its name unique among all the archive folders, and the entire archive easily searchable.

## Archives' Conventions

This section describes a consistent and predictable `naming scheme` that allows one to merge the
contents of different archives as a flat list without worrying about name collisions.

### Archives' Format

It may be a no-brainer, but let's start by stating that every archive, or backup, must be bundeled in a
compressed file. Not less obvious is the fact that one should choose a format and stick to it. In the
present case, and due to its ubiquity, the format of choice is the `.zip` format.

<div style="
    width: 45em;
    font-size: normal;
    margin: 0 10% 5ex 5%;"
>

!!!Danger Compression Format
    Every archive must be bundeled in a compressed
    <code><span style="font-size: 115%; font-weight: bold">.zip</span></code> file.

</div>

### Archives' Naming Scheme

The name of the archive should tell about its content, its nature, and the point in time it was created.
 Finally, the scheme should be both speechful enough to be easily understood and simple enough to
  be easily implemented and remembered without having to refer to a manual every time one needs
  to create an archive. The shceme below statisfies each of these requirements. Please note that its
  pieces are meant to concatenate **without any space in-between them**:

<div style="
    width: 45em;
    font-size: normal;
    margin: 0 10% 5ex 5%;"
>

!!!Danger Naming Scheme
    <code><span style="font-size: 110%; font-weight: bold">
    &lt; prefix &gt; \~ &lt; descriptive-name &gt; [ \~ &lt; suffixes &gt; ] \~ &lt; vers|date|tag &gt; . zip
    </span></code>

</div>

where:

- **`< prefix >`** identifies the archive's ***nature***.

- **`< vers|date|tag >`** locates the archive on the  ***timeline***.

- **`< descriptive name >`** describes the archive's ***contents***.

In addition. but *optionally*:

- **`< suffixes >`** break eventual ties using the archive's ***specificities***.

The following sections describe in more details each of these elements and, when it is possible, list
the typical values that they may take on in a given context.

## Prefixes and contents

The following table lists the typical *prefixes* and their associated *contents*:

|  Prefix  | Contents <sup>1</sup>  | Description |
| :-------: | :---------- |:----------- |
| **`all`** | The project's or sub-project's name | Identifies archives containing the full project. |
| **`src`** | The project's or sub-project's name | Identifies archives containing only source-files. |
| **`rel`** | The project's or sub-project's name | Identifies archives corresponding to a release. |
| **`rss`** | A description of the resources' nature | Identifies archives containing only resources. |
| **`adm`** | A description of the information's nature |Identifies archives containing administrative information. |
| **`dpl`** | The project's or sub-project's name |  Identifies archives corresponding to a deployment. |
| **`doc`** | A description of the documentation's nature | Identifies archives containing only documentation.  |
| **`bck`** | A description of the contents' nature | A generic identifier for contents matching none of the above.  |
| **`tag`** | The project's or sub-project's name | Typically a rollback point: such file is linked to the *tag in the commit tree* that corresponds to `<tag>`. |

<i><sup>1</sup> The typical &lt;contents&gt; information
associated to that prefix</i>.

## Tags, Dates and Versions

The `< vers|date|tag >` element is used to locate the archive on the timeline. Whether an archive
takes a *date*, a *version* or a *tag* depends on its nature. The following table lists the typical
values that these elements may take on in a given context:

|  Token  | syntax| Typical use cases |
| :------- | :----------: | :---------- |
| **`tag`** | `bX.Y.Z[<a-z>]` | Backups containing a rollback point referred to by a *tag* in the commit tree. |
| **`vers`** | `vX.Y.Z` |  Archives containing the full project and corresponding to a versionned release. |
| **`date`** | `YYMMDD` |  Archives matching none of the above like, typically, partial archives or backups. |

### Formatting Version Numbers

Version numbers are formatted according to the conventions of
[Semantic Versioning](https://semver.org/spec/v2.0.0.html). In this scheme, each version number is composed of
three integers separated by a dot (`.`) and prefixed by a lower-case `v`.

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">

!!!Tip Semantic Versioning
    `vX.Y.Z` where `X`, `Y`, and `Z` are integers corresponding to the `<major>`, `<minor>` and
    `<patch>` versions, respectively:
    <div style="text-align: center; margin-bottom:1.5ex;font-weight: bold; font-size: larger">
        <code>v2.7.18</code>
    </div>

</div>

The first integer is the *major* version, the second is the *minor* version, and the third is the *patch*
version. Incrementing one of them leaves the ones to its left unchanged and resets those to its right
to zero. For example, incrementing the *minor* version of `v2.7.18` yields `v2.8.0` while
incrementing the *major* version of `v2.7.18` yields `v3.0.0`. Patching it, on the other hand, yields
`v2.7.19`.

|  Version  | Type of change |
| :-------: | :---------- |
| **`<patch>`** | A change that fixes a bug. |
| **`<minor>`** | A change that does not break backward compatibility. |
| **`<major>`** | A change that breaks backward compatibility like, typically, deprecating features. |

The  table above shows the types of changes that an increment of the `<major>` verion, the
`<minor>` and the `<patch>` version correspond to. Note that `patches` are also calle `hot fixes` and
that they profoundly differ from `minor` and `major` versions in that they are usually immediately
reflected in the production environment, without waiting for the next release.

@import "./assets/images/git-branching-model.png" {height="500px" title="Git Model" alt="Git Model" style="display: inline; position: absolute; right: 25pt; "}

<div style="display: inline-block;  width:500px; text-align: justify">
<p>These conventions apply far beyond the scope of naming archives and are the standard for
versionning software. The underlying scheme is known as the *Semantic Versioning* model. A
detailed description of this model is available on the official
<a href="https://semver.org/spec/v2.0.0.html"><i>Semver</i> website</a>.
</p>
<p>
Semantic versionning is also at the core of most <i>Git Models"</i> A typical example is the
<b><i>Branching Model</i></b> illustrated in the figure on the right and which is presented in great
details on
<a href="https://nvie.com/posts/a-successful-git-branching-model/" target="blank">this website</a>.
A  PDF version of the image on the right  can be dowloaded by cliking
<a href="./assets/images/git-model.pdf" target="blank">here.</a>.
</p>
<p>
Note that it is considered a good practice to let every release be tagged with a version number
formatted as described above directly in the commit tree. This is illustrated on right-most branch of
<i>Branching Model Figure</i>. Extending this practice beyond just releases to reference important
backups and archives such as *rollback points* is what yields the <code>tag</code> marker
discussed in the  next section.
<p>

### Formatting Tags

As mentioned above, the practice of tagging releases is extended to reference important backups
and archives, such as <i>rollback points</i>.
</div>

The syntax to be used for such tags is similar to the one used for version numbers, except that the
leading `v` is replaced by a `b` standing for "roll**b**ack" and that a suffix is added to the version
number to avoid collisions in the case where several archives are tagged with the same version
number.

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">

!!!Tip Formatting Rollback Tags
    Rollback tags are of formatted using the version number, prefixed by an `b` and followed by a
    counter in the form of a lower-case letter. In other words, they are of the form `bX.Y.Z[<a-z>]`. The
    following example corresponds to the 3rd rollback point of version `v2.7.18`:
    <div style="text-align: center; margin-bottom:1.5ex;font-weight: bold; font-size: larger">
        <code>b2.7.18c</code>
    </div>

</div>

### Formatting Dates

The last possible temporal maker for in an archive's name is to use the date at which the backup
was made. It is used when the archive does not correspond to a release or a rollback point, but
rather to a partial backup or a backup of a specific component of the project such as the
documentation, the resources, or the administrative information.

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">

!!!Tip Formatting Dates
    The date format to be used is `yymmdd`, where `yy` is the year, `mm` the month, and `dd` the day
    of the month, each represented by two digits. For example, the following date corresponds to the
    *18th of July 2023*:
    <div style="text-align: center; margin-bottom:1.5ex;font-weight: bold; font-size: larger">
        <code>230718</code>
    </div>

</div>

## Suffixes (optional)

The  *suffixes* specify a characteristic of the archive. Typical use cases are to distinguish an
*optimized* archive from one containing unpackaged source, to clearly identify archives meant to be
*private*  in a context where the default is to share all archives or, at the contrary, to mark a *public*
one when restricting access to archives is the norm. These cases and the associated suffixes are
described in the following table:

| Suffix | Meaning |
| :----: | :------ |
| **`opt`** | Optimized version of the project. |
| **`dev`** | Development version of the project. |
| **`pub`** | Public version of the project. |
| **`prv`** | Private version of the project. |
