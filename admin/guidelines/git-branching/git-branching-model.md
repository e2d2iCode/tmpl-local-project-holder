# Git Branching Model

<div style="min-width: 45em; font-size: normal; margin: 0 10% 5ex 5%;">
<div style="font-size: 95%; text-align: justify;">

!!!Abstract
    *This document sketches the **`Git Branching Strategy`** to be followe when working on a
    project. A more detailed description is available on
    [this website](https://nvie.com/posts/a-successful-git-branching-model/)*.

</div></div>

## Overview

@import "./assets/images/git-branching-model.png" {height="600px" title="Git Model" alt="Git Model" style="display: inline; position: absolute; right: 25pt; margin-top: 7.5pt"}

<div style="display: inline-block;  width:400px; text-align: justify">
<p>The figure on the right illustrates a consistent and robust <b><i>Git Branching Model</i></b> that can be successfully applied to small to medium size projects. It can also be easily adapted to match the needs of more complex developments involving large teams.</p>
<p>
A full and very detailed description of that model is available on <a href="https://nvie.com/posts/a-successful-git-branching-model/" target="blank">this website</a>, so no further explanations past the present figure will be provided here. A specific implementation of it involving the syntax to be used for the commit messages may be done in the future.
</p>
<p>
`Tags` for,atting is briefly discussed in the guidelines on how to <a href="../handling-archives/handling-archives.md">Handle Arrchives</a>. However, that document only covers that topic in the specific context of naming the archives' files, which then only considers the cases of tags that are used to identify releases (i.e. version numbers) and tags that are used to identify important backups and archives (i.e. rollback points). Other use cases are not even mentionned.
</p>
<p>
 A  PDF version of the  <i>Git Branching Model</i> illustrated in the present figure is also avalible. It can be downloaded by cliking on the link below:
 <div style="text-align:center; margin: 1ex 0 1ex 0">
 <a href="./assets/images/git-model.pdf" target="blank">A Successfull Git Branching Model</a>.
 </div>
</div>
